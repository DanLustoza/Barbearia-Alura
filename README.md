# Barbearia-Alura
Meu primeiro projeto no GitHub
<!DOCTYPE html>
<html lang="pt-br">
	<head>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width">
		<title>Barbearia Alura</title>

		<link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
		<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100;200;300&display=swap" rel="stylesheet">
	</head>

	<body>
		<header>
            <div class="caixa">
                <h1><img src="logo.png"></h1>
                
                <nav>
                    <ul>
                        <li><a href="index.html">Home</a></li>
                        <li><a href="produtos.html">Produtos</a></li>
                        <li><a href="contato.html">Contato</a></li>
                    </ul>
                </nav>
            </div>
		</header>

		<img class="banner" src="banner.jpg">

		<main>
			<section class="principal">
				<h2 class="titulo-principal">Sobre a Barbearia Alura</h2>

				<img class="utensilios" src="utensilios.jpg" alt="Utensilios de um barbeiro">
		
				<p>Localizada no coração da cidade a <strong>Barbearia Alura</strong> traz para o mercado o que há de melhor para o seu cabelo e barba. Fundada em 2019, a Barbearia Alura já é destaque na cidade e conquista novos clientes a cada dia.</p>

				<p id="missao"><em>Nossa missão é: <strong>"Proporcionar auto-estima e qualidade de vida aos clientes"</strong>.</em></p>

				<p>Oferecemos profissionais experientes e antenados às mudanças no mundo da moda. O atendimento possui padrão de excelência e agilidade, garantindo qualidade e satisfação dos nossos clientes.</p>
			</section>

			<section class="mapa">
				<h3 class="titulo-principal">Nosso Estabelecimento</h3>
				<p>Nosso estabelecimento está localizado no coração da cidade</p>

				<div class="mapa-conteudo">
					<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d233916.22037880574!2d-46.841852784025434!3d-23.642285912589706!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94ce5a2b2ed7f3a1%3A0xab35da2f5ca62674!2sCaelum%20-%20Escola%20de%20Tecnologia!5e0!3m2!1spt-BR!2sbr!4v1649891629022!5m2!1spt-BR!2sbr" width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
				</div>
				</section>
 
			<section class="beneficios">
				<h3 class="titulo-principal">Benefícios</h3>

				<div class="conteudo-beneficios">

						<ul class="lista-beneficios">
						<li class="itens">Atendimento aos Clientes</li>
						<li class="itens">Espaço diferenciado</li>
						<li class="itens">Localização</li>
						<li class="itens">Profissionais Qualificados</li>
						<li class="itens">Pontualidade</li>
						<li class="itens">Limpeza</li>
					</ul><img src="beneficios.jpg" class="imagem-beneficios">		
				</div>

				<div class="video">
					<iframe width="100%" height="315" src="https://www.youtube.com/embed/wcVVXUV0YUY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
				</div>
			</section>
		</main>

		<footer>
            <img src="logo-branco.png">
            <p class="copyright">&copy; Copyright Barbearia Alura 2022</p>
        </footer>
	</body>
</html>

body {
    font-family: 'Montserrat', sans-serif;
}

header {
    background: #BBBBBB;
    padding: 20px 0;
}

.caixa {
    position: relative;
    width: 940px;
    margin: 0 auto;
}

nav {
    position: absolute;
    top: 110px;
    right: 0;
}

nav li {
    display: inline;
    margin: 0 0 0 15px;
}

nav a {
    text-transform: uppercase;
    color: #000000;
    font-weight: bold;
    font-size: 22px;
    text-decoration: none;
}   

nav a:hover {
    color: #C78C19;
    text-decoration: underline;
}

.produtos {
    width: 940px;
    margin: 0 auto  ;
    padding: 50px 0;
}

.produtos li {
    display: inline-block;
    text-align: center;
    width: 30%;
    vertical-align: top;
    margin: 0 1.5%  ;
    padding: 30px 20px;
    box-sizing: border-box;
    border: 2px solid #000000;
    border-radius: 10px;
}   

.produtos li:hover {
    border-color: #C78C19;
   
}

.produtos li:active {
    border-color: #088C19;
}

.produtos li:hover h2 {
    font-size: 34px;

}
.produtos h2 {
    font-size: 30px;
    font-weight: bold;
}

.produto-descrição {
    font-size: 18px;
}

.produto-preço {
    font-size: 22px;
    font-weight: bold;
    margin-top: 10px;
}

footer {
    text-align: center;
    background: url("bg.jpg");
    padding: 40px 0;
}

.copyright {
    color: #FFFFFF;
    font-size: 13px;
    margin: 20px 0 0;
}

main {
    
}

form {
    margin: 40px 0;
}

form label, form legend {
    display: block;
    font-size: 20px;
    margin: 0 0 10px;
}

.input-padrao {
    display: block;
    margin: 0 0 20px;
    padding: 10px 25px;
    width: 50%;
}

.checkbox {
        margin: 20px 0;
}

.enviar {
    width: 40%;
    padding: 15px 0;
    background: orange;
    color: white;
    font-weight: bold;
    font-size: 18px;
    border: none;
    border-radius: 5px;
    transition: 1s all;
    cursor: pointer;
}

.enviar:hover {
    background: darkorange;
    transform: scale(1.2);
}

table {
    margin: 20px 0 40px;
}

thead {
    background:#555555;
    color: white;
    font-weight: bold;
}

td, th {
    border: 1px solid #000000;
    padding: 8px 15px;
}

/* css da página inical */
.banner {
    width: 100%;
}

.titulo-principal {
    text-align: center;
    font-size: 2em;
    margin: 0 0 1em;
    clear: left;
}

.principal {
    padding: 3em 0;
    background: #fefffe;
    width: 940px;
    margin: 0 auto;
}

.principal p {
    margin: 0 0 1em;
}

.principal strong {
    font-weight: bold;
}

.principal em {
    font-style: italic;
}

.utensilios {
    width: 120px;
    float: left;
    margin: 0 20px 20px 0;
}

.mapa {
    padding: 3em 0;
    background: linear-gradient(#fefefe, #88888888);
}

.mapa-conteudo {
    width: 940px;
    margin: 0 auto;
}
.mapa p {
    margin: 0 0 2em;
    text-align: center;
}

.beneficios {
    padding: 3em 0;
    background: #88888888;  
}

.conteudo-beneficios {
    width: 640px;
    margin: 0 auto;
}

.lista-beneficios {
    width: 40%;
    display: inline-block;
    vertical-align: top;
}

.itens {
    line-height: 1.5;
}

.itens:first-child {
    font-weight: bold;
}

.itens:before {
    content: "⭐";
}

.imagem-beneficios {
    width: 60%;
    opacity: 1;
    transition: 400ms;
    box-shadow: 10px 10px 10px 0 #000000;
}

.imagem-beneficios:hover {
    opacity: 0.3;
}


.video {
    width: 560px;
    margin: 2em auto;
}

@media screen and (max-width: 480px) {
    .caixa, .principal, .conteudo-beneficios, .mapa-conteudo, .video {
      width: auto;
  }

h1 {
    text-align: center;
}

nav {
    position: static;
}

.lista-beneficios, .imagem-beneficios {
    width: 100% ;
}
