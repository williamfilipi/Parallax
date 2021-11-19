##Parallax 

///ESTRUTURA HTML

<html>
		<head>

			<title>Parallax</title>
			<meta charset="utf-8">
			<link rel="stylesheet" type="text/css" href="css/estilo.css">

		</head>

		<body>

			<div class="caixa1">
				<div class="conteudo-titulo">
					<span class="titulo">
						Passeio de Balões
					</span>
				</div>
			</div>			

			<div class="caixa2">
				<div class="conteudo-titulo">
					<span class="titulo">
						pegando a estrada
					</span>
				</div>
			</div>
			
			<div class="caixa3">
				<div class="conteudo-titulo">
					<span class="titulo">
						pôr do sol
					</span>
				</div>
			</div>

			<div class="caixa4">
				<div class="conteudo-titulo">
					<span class="titulo">
						montanhas
					</span>
				</div>
			</div>

		</body>

</html>



///ESTILO CSS////


body, html {
	margin: 0;
	font: 16px "Lato", sans-serif;
	color: #777;
	height: 100%;
}

.conteudo {
	color: #777;
	background-color: white;
	text-align: justify;
	padding: 50px 80px;
}

h3{
	text-transform: uppercase;
	color: #111;
	text-align: center;
}

p{
	margin-bottom: 20px;
}

/*///EFEITO PARALLAX///*/

.caixa1, .caixa2, .caixa3, .caixa4 {
	position: relative;
	height: 100%;
	opacity: 0.8;
	background-repeat: no-repeat;
	background-size: cover;
	background-position: center;
	background-attachment: fixed;
}
.caixa1 {
	background-image: url(../imagens/imagem1.jpg);
}

.caixa2 {
	background-image: url(../imagens/imagem2.jpg);
}

.caixa3 {
	background-image: url(../imagens/imagem3.jpg);
}

.caixa4 {
	background-image: url(../imagens/imagem5.jpg);
}

.conteudo-titulo{
	position: absolute;
	left: 0;
	top: 45%;
	width: 100%;
	text-align: center;
}

.conteudo-titulo span.titulo{
	color: #fff;
	background-color: #111;
	padding: 18px;
	font-size: 25px;
	letter-spacing: 5px;
	text-transform: uppercase;
}
