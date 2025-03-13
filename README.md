<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu GitHub - Perfil Personalizado</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #121212;
            color: white;
            line-height: 1.6;
            padding: 20px;
        }

        ul {
            list-style-type: none;
            padding-left: 0;
        }
        
        ol {
            list-style-type: none;
            padding-left: 0;
        }
      
        #m1{
            margin: 30px;
        }

        .a1 {
            padding: 2px;
            text-decoration: none;
            color: aliceblue;
            font-family: 'Times New Roman', Times, serif;
            font-size: 20px;
            display: inline-flex; 
            align-items: center; 
            margin: 1px;
        }

        img {
            padding: 0;
            vertical-align: middle; 
            margin-right: 8px; 
        }

        #linkedin {
            background-color: rgb(28, 95, 196);
        }

        #youtube {
            background-color: rgb(179, 53, 53);
        }

        #instagram {
            background: linear-gradient(45deg, #F58529, #D32F6D, #833AB4);
        }

        #twitter {
            background-color: rgb(118, 171, 252);
        }

        .container {
            max-width: 960px;
            margin: 0 auto;
        }

        .intro {
            display: flex;
            align-items: center;
            margin-bottom: 40px;
            justify-content: center;
            text-align: center;
        }

        .intro h1 {
            font-size: 2.5em;
            color: #ff0080;
        }

        .intro p {
            font-size: 1.2em;
            color: #cccccc;
        }

        .social-links {
            text-align: center;
            margin: 20px 0;
        }

        .social-links a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
            font-size: 1.3em;
            transition: color 0.3s ease;
        }

        .social-links a:hover {
            color: #ff0080;
        }

        .technologies {
            text-align: center;
            margin: 40px 0;
        }

        .technologies ul {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        .technologies ul li {
            margin: 8px;
        }

        .stats {
            text-align: center;
            margin: 40px 0;
        }

        .stats img {
            margin: 20px;
            max-width: 100%;
        }

        footer {
            text-align: center;
            color: #888;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Seção de Introdução -->
        <section class="intro">
            <div>
                <h1>Olá, sou GABRIEL CALLEGARI 👋</h1>
                <p>Desenvolvedor apaixonado por aprender novas tecnologias!</p>
            </div>
        </section>

        <!-- Seção de Redes Sociais -->
        <main id="m1">
            <a href="https://www.linkedin.com/in/gabriel-callegari" id="linkedin" class="a1">
                <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="20" height="20" alt="linkedin logo" />LINKEDIN
            </a>
    
            <a href="https://www.youtube.com/c/gabrielcallegari" id="youtube" class="a1">
                <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/youtube/default.svg" width="20" height="20" alt="youtube logo" /> YOUTUBE
            </a>
           
            <a href="https://www.instagram.com/gabrielcallegari" id="instagram" class="a1">
                <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/instagram/default.svg" width="20" height="20" alt="instagram logo" /> INSTAGRAM
            </a>
           
            <a href="https://twitter.com/gabrielcallegari" id="twitter" class="a1">
                <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/twitter/default.svg" width="20" height="20" alt="twitter logo" /> TWITTER
            </a>
        </main>

        <!-- Seção de Tecnologias -->
        <section class="technologies">
            <h2>🚀 Tecnologias que uso</h2>
            <ul>
                <li><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="html5 logo"  /></li>
                <li><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="css3 logo"  /></li>
                <li><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo"  /></li>
                <li><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" alt="nodejs logo"  /></li>
                <li><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" height="40" alt="php logo"  /></li>
                <li><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" height="40" alt="c logo"  /></li>
            </ul>
        </section>

        <!-- Seção de Estatísticas do GitHub -->
        <section class="stats">
            <h2>📊 Estatísticas do GitHub</h2>
            <p>Visualize meu progresso e contribuições.</p>
            <!-- Exemplo de estatísticas -->
            <img src="https://github-readme-stats.vercel.app/api?username=gabrielcallegari&show_icons=true&hide_title=true&count_private=true&theme=dark" alt="Estatísticas GitHub" />
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=gabrielcallegari&theme=dark" alt="GitHub Streak" />
        </section>

        <!-- Rodapé -->
        <footer>
            <p>Feito com ❤️ por Gabriel Callegari</p>
        </footer>
    </div>

</body>
</html>


