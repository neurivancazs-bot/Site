<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site Bonito</title>
    <style>
        /* Reset básico */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(to right, #4facfe, #00f2fe);
            color: #fff;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        header {
            background: rgba(0,0,0,0.3);
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.2);
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            transition: 0.3s;
        }

        nav a:hover {
            color: #ffea00;
        }

        main {
            flex: 1;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 50px 20px;
        }

        main h2 {
            font-size: 2rem;
            margin-bottom: 20px;
        }

        main p {
            font-size: 1.2rem;
            line-height: 1.5;
            max-width: 600px;
            margin: auto;
        }

        footer {
            background: rgba(0,0,0,0.3);
            text-align: center;
            padding: 15px;
        }

        /* Botão simples */
        .btn {
            display: inline-block;
            padding: 10px 25px;
            background: #ffea00;
            color: #333;
            border-radius: 25px;
            font-weight: bold;
            margin-top: 20px;
            text-decoration: none;
            transition: 0.3s;
        }

        .btn:hover {
            background: #ffd700;
            transform: scale(1.05);
        }

        /* Responsividade */
        @media(max-width:768px){
            header h1 {
                font-size: 2rem;
            }

            main h2 {
                font-size: 1.5rem;
            }

            nav a {
                display: block;
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Bem-vindo ao Meu Site</h1>
        <nav>
            <a href="#sobre">Sobre</a>
            <a href="#servicos">Serviços</a>
            <a href="#contato">Contato</a>
        </nav>
    </header>

    <main>
        <div>
            <h2>Crie seu site bonito e rápido!</h2>
            <p>Este é um modelo simples, elegante e responsivo em HTML e CSS que pode ser hospedado online sem travar. Você pode editar facilmente cores, textos e imagens para criar seu próprio site.</p>
            <a href="#contato" class="btn">Entre em Contato</a>
        </div>
    </main>

    <footer>
        &copy; 2025 Meu Site Bonito. Todos os direitos reservados.
    </footer>
</body>
</html>
