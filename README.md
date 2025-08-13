# Meu-site-2
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site Incrível</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            background: linear-gradient(270deg, #ff0066, #ff6600, #6600ff);
            background-size: 600% 600%;
            animation: bgMove 10s infinite alternate;
            font-family: Arial, sans-serif;
            color: white;
            text-align: center;
            padding: 50px;
        }
        @keyframes bgMove {
            0% { background-position: 0% 50%; }
            100% { background-position: 100% 50%; }
        }
        header {
            padding: 20px 0;
        }
        nav {
            margin-bottom: 40px;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
            border-bottom: 2px solid transparent;
            transition: 0.3s;
        }
        nav a:hover {
            border-bottom: 2px solid white;
        }
        h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        p {
            font-size: 1.2em;
            margin-bottom: 30px;
        }
        button {
            background: white;
            color: #ff0066;
            border: none;
            padding: 12px 25px;
            font-size: 16px;
            border-radius: 25px;
            cursor: pointer;
            transition: 0.3s;
        }
        button:hover {
            background: #ff0066;
            color: white;
        }
        footer {
            margin-top: 50px;
            font-size: 0.9em;
            opacity: 0.8;
        }
    </style>
</head>
<body>
    <header>
        <h1>🚀 Meu Site Incrível</h1>
        <p>Feito 100% pelo celular 📱</p>
        <nav>
            <a href="#home">Início</a>
            <a href="#sobre">Sobre</a>
            <a href="#contato">Contato</a>
        </nav>
    </header>

    <section id="home">
        <h2>Bem-vindo!</h2>
        <p>Este é um site animado, feito usando apenas HTML e CSS, sem precisar de computador.</p>
        <button onclick="alert('Obrigado por visitar!')">Clique Aqui</button>
    </section>

    <section id="sobre" style="margin-top:40px;">
        <h2>Sobre</h2>
        <p>Você pode editar este site e deixar do seu jeito, trocar cores, textos e até adicionar animações.</p>
    </section>

    <section id="contato" style="margin-top:40px;">
        <h2>Contato</h2>
        <p>Me mande uma mensagem e vamos conversar! 📩</p>
    </section>

    <footer>
        <p>© 2025 - Meu Site Incrível. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
