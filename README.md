<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Batatas do Bahiano</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        header {
            background-color: #f8b400;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            margin: 0;
            padding: 0;
            list-style: none;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            display: inline-block;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }
        .hero {
            background-image: url('Screenshot_20240729-095838~2.png'); /* https://photos.google.com/share/AF1QipNMQ5rn66rPeYYzoCShifHiFPG2HarU9i5fRc4Xulyk2muVc7iYyqyPd1VfBDAQMw?key=QU5obmZ2Wms2Yk11ek53VnJxcXFCSUJrYXZ4TVRB */
            background-size: cover;
            color: white;
            text-align: center;
            padding: 100px 0;
        }
        .hero h1 {
            font-size: 3em;
            margin: 0;
        }
        footer {
            background-color: #f8b400;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
        .map {
            width: 100%;
            height: 400px;
        }
    </style>
</head>
<body>

<header>
    <h1>Batatas do Bahiano</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#sobre">Sobre</a>
        <a href="#cardapio">Cardápio</a>
        <a href="#contato">Contato</a>
        <a href="#localizacao">Localização</a>
    </nav>
</header>

<div id="home" class="hero">
    <h1>Bem-vindo à Batatas do Bahiano!</h1>
    <p>Venha experimentar as melhores batatas recheadas da cidade!</p>
</div>

<div id="sobre" class="container">
    <h2>Sobre Nós</h2>
    <p>Conheça a história da nossa lanchonete e nossa equipe dedicada!</p>
</div>

<div id="cardapio" class="container">
    <h2>Cardápio</h2>
    <p>Confira nossas deliciosas opções!</p>
</div>

<div id="contato" class="container">
    <h2>Contato</h2>
    <form>
        <label for="nome">Nome:</label>
        <input type="text" id="nome" name="nome" required><br><br>
        <label for="email">E-mail:</label>
        <input type="email" id="email" name="email" required><br><br>
        <label for="assunto">Assunto:</label>
        <input type="text" id="assunto" name="assunto"><br><br>
        <label for="mensagem">Mensagem:</label><br>
        <textarea id="mensagem" name="mensagem" rows="4" required></textarea><br><br>
        <input type="submit" value="Enviar">
    </form>
</div>

<div id="localizacao" class="container">
    <h2>Localização</h2>
    <div class="map">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3902.302957820021!2d-39.32858028572309!3d-7.18844196458026!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x70521f7aeb9b7a7%3A0x5d1a8b75c0664f!2sPra%C3%A7a%20Padre%20C%C3%ADcero%2C%20Juazeiro%20do%20Norte%20-%20CE%2C%2046380-000!5e0!3m2!1spt-BR!2sbr!4v1632205638422!5m2!1spt-BR!2sbr" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </div>
</div>

<footer>
    <p>&copy; 2024 Batatas do Bahiano. Todos os direitos reservados.</p>
</footer>

</body>
</html>
