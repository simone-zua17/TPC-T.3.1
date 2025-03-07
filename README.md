
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zun’s FM - Moda & Estilo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #222;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav a {
            color: white;
            text-decoration: none;
        }
        main {
            display: flex;
            flex-wrap: wrap;
            padding: 20px;
        }
        section {
            flex: 3;
            padding: 15px;
            margin-right: 10px;
            border-radius: 10px;
            color: white;
        }
        #masculino {
            background-color: #3498db;
        }
        #feminino {
            background-color: #e74c3c;
        }
        #acessorios {
            background-color: #f1c40f;
        }
        aside {
            flex: 1;
            background-color: #2ecc71;
            padding: 15px;
            border-radius: 10px;
            color: white;
        }
        section img {
            width: 100%;
            max-width: 400px;
            height: auto;
            border-radius: 8px;
            margin-top: 10px;
        }
        .ver-mais {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 15px;
            background-color: #000;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .icon {
            width: 24px;
            height: 24px;
            margin-right: 8px;
            vertical-align: middle;
        }
        @media (max-width: 768px) {
            main {
                flex-direction: column;
            }
            section, aside {
                flex: 1;
                margin-right: 0;
            }
        }
        @media (max-width: 600px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            nav ul li {
                margin: 10px 0;
            }
        }
        @media (max-width: 480px) {
            h1 {
                font-size: 1.5rem;
            }
        }
    </style>
</head>
<body>
 <a href="T.1.html">TPC T.1</a>
    <header>
        <h1>Zun’s FM - Moda & Estilo</h1>
        <nav>
            <ul>
                <li><a href="#masculino">Masculino</a></li>
                <li><a href="#feminino">Feminino</a></li>
                <li><a href="#acessorios">Acessórios</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="masculino">
            <article>
                <h2>Moda Masculina</h2>
                <p>Confira os melhores estilos para homens com qualidade e sofisticação.</p>
                <img src="OIF.jpg" alt="Moda Masculina">
                <a href="masculino.html" class="ver-mais">Ver Mais</a>
            </article>
        </section>
        <section id="feminino">
            <article>
                <h2>Moda Feminina</h2>
                <p>Descubra as coleções femininas mais elegantes e modernas.</p>
                <img src="OIP.jpg" alt="Moda Feminina">
                <a href="feminino.html" class="ver-mais">Ver Mais</a>
            </article>
        </section>
        <section id="acessorios">
            <article>
                <h2>Acessórios</h2>
                <p>Complete seu look com acessórios exclusivos da Zun’s FM.</p>
                <img src="SZ.jpg" alt="Acessórios">
                <a href="acessorios.html" class="ver-mais">Ver Mais</a>
            </article>
        </section>
        <aside>
            <h3>Redes Sociais</h3>
            <p>
                <a href="https://www.instagram.com/virianemiguel" target="_blank">
                    <img src="OI.png" alt="Instagram" class="icon"> Instagram
                </a>
            </p>
            <p>
                <a href="https://www.facebook.com/virianemiguel" target="_blank">
                    <img src="icons/facebook.png" alt="Facebook" class="icon"> Facebook
                </a>
            </p>
            <p>
                <a href="https://wa.me/924222612" target="_blank">
                    <img src="WA.png" alt="WhatsApp" class="icon"> WhatsApp
                </a>
            </p>
            <p>
                <a href="mailto:simonezua14@hotmail.com">
                    <img src="ME.png" alt="E-mail" class="icon"> E-mail
                </a>
            </p>
        </aside>
    </main>
    <footer>
        <p>&copy; 2025 - Zun’s FM. Todos os direitos reservados.</p>
       


    </footer>

</body>
</html>
