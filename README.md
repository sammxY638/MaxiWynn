# MaxiWynn
my homepage
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anita Max Wynn - Redenschreiberin</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #1e90ff;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #4682b4;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #5a9bd3;
        }
        .container {
            padding: 20px;
        }
        .section-title {
            text-align: center;
            margin: 40px 0 20px;
            color: #1e90ff;
        }
        .biography, .projects, .videos, .contact {
            margin-bottom: 40px;
        }
        .projects ul, .contact ul {
            list-style-type: none;
            padding: 0;
        }
        .projects ul li, .contact ul li {
            background-color: #e6f7ff;
            margin: 10px 0;
            padding: 10px;
            border-radius: 5px;
        }
        .video {
            text-align: center;
            margin: 20px 0;
        }
        footer {
            background-color: #4682b4;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Anita Max Wynn</h1>
        <p>Renommierte Redenschreiberin für Persönlichkeiten wie Donald Duck, Goofy und Bomboclat</p>
    </header>
    <nav>
        <a href="#biografie">Biografie</a>
        <a href="#projekte">Projekte</a>
        <a href="#reden">Beste Reden</a>
        <a href="#kontakt">Kontakt</a>
    </nav>
    <div class="container">
        <section id="biografie" class="biography">
            <h2 class="section-title">Biografie</h2>
            <p>Ich bin Anita Max Wynn, eine erfahrene Redenschreiberin, die für zahlreiche renommierte Persönlichkeiten wie Donald Duck, Goofy und Bomboclat geschrieben hat. Mit meiner Leidenschaft für Worte und meiner Fähigkeit, kraftvolle und unvergessliche Reden zu verfassen, habe ich mir einen Namen in der Branche gemacht.</p>
        </section>
        <section id="projekte" class="projects">
            <h2 class="section-title">Projekte</h2>
            <ul>
                <li>Projekt 1: Rede für Donald Duck - Thema: Freundschaft und Loyalität</li>
                <li>Projekt 2: Rede für Goofy - Thema: Optimismus und Lebensfreude</li>
                <li>Projekt 3: Rede für Bomboclat - Thema: Stärke und Widerstandskraft</li>
            </ul>
        </section>
        <section id="reden" class="videos">
            <h2 class="section-title">Meine besten Reden</h2>
            <div class="video">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/BeispielVideo1" frameborder="0" allowfullscreen></iframe>
                <p>Rede für Donald Duck</p>
            </div>
            <div class="video">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/BeispielVideo2" frameborder="0" allowfullscreen></iframe>
                <p>Rede für Goofy</p>
            </div>
            <div class="video">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/BeispielVideo3" frameborder="0" allowfullscreen></iframe>
                <p>Rede für Bomboclat</p>
            </div>
        </section>
        <section id="kontakt" class="contact">
            <h2 class="section-title">Kontakt</h2>
            <ul>
                <li>Email: anita.max.wynn@example.com</li>
                <li>Telefon: +49 123 456 7890</li>
                <li>LinkedIn: <a href="https://www.linkedin.com/in/anita-max-wynn" target="_blank">linkedin.com/in/anita-max-wynn</a></li>
            </ul>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Anita Max Wynn. Alle Rechte vorbehalten.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anita Max Wynn - Redenschreiberin</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        /* Globale Stile */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
            color: #333;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        h1, h2, h3 {
            color: #1e90ff;
        }
        /* Header */
        header {
            background-color: #1e90ff;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header p {
            font-size: 1.2em;
        }
        /* Navigation */
        nav {
            background-color: #4682b4;
            text-align: center;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            margin: 0 5px;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        nav a:hover {
            background-color: #5a9bd3;
        }
        /* Abschnitte */
        section {
            margin-bottom: 40px;
        }
        .section-title {
            text-align: center;
            margin-bottom: 20px;
            font-size: 1.5em;
        }
        /* Projekte und Kontakt */
        .projects ul, .contact ul {
            padding: 0;
            list-style-type: none;
        }
        .projects ul li, .contact ul li {
            background-color: #e6f7ff;
            padding: 15px;
            margin: 10px 0;
            border-radius: 5px;
        }
        /* Videos */
        .videos {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .video {
            margin: 10px;
        }
        /* Footer */
        footer {
            background-color: #4682b4;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Anita Max Wynn</h1>
        <p>Renommierte Redenschreiberin für Persönlichkeiten wie Donald Duck, Goofy und Bomboclat</p>
    </header>
    <nav>
        <a href="#biografie">Biografie</a>
        <a href="#projekte">Projekte</a>
        <a href="#reden">Beste Reden</a>
        <a href="#kontakt">Kontakt</a>
    </nav>
    <div class="container">
        <section id="biografie">
            <h2 class="section-title">Biografie</h2>
            <p>Ich bin Anita Max Wynn, eine erfahrene Redenschreiberin, die für zahlreiche renommierte Persönlichkeiten wie Donald Duck, Goofy und Bomboclat geschrieben hat. Mit meiner Leidenschaft für Worte und meiner Fähigkeit, kraftvolle und unvergessliche Reden zu verfassen, habe ich mir einen Namen in der Branche gemacht.</p>
        </section>
        <section id="projekte">
            <h2 class="section-title">Projekte</h2>
            <ul>
                <li>Projekt 1: Rede für Donald Duck - Thema: Freundschaft und Loyalität</li>
                <li>Projekt 2: Rede für Goofy - Thema: Optimismus und Lebensfreude</li>
                <li>Projekt 3: Rede für Bomboclat - Thema: Stärke und Widerstandskraft</li>
            </ul>
        </section>
        <section id="reden">
            <h2 class="section-title">Meine besten Reden</h2>
            <div class="videos">
                <div class="video">
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/BeispielVideo1" frameborder="0" allowfullscreen></iframe>
                    <p>Rede für Donald Duck</p>
                </div>
                <div class="video">
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/BeispielVideo2" frameborder="0" allowfullscreen></iframe>
                    <p>Rede für Goofy</p>
                </div>
                <div class="video">
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/BeispielVideo3" frameborder="0" allowfullscreen></iframe>
                    <p>Rede für Bomboclat</p>
                </div>
            </div>
        </section>
        <section id="kontakt">
            <h2 class="section-title">Kontakt</h2>
            <ul>
                <li><i class="fas fa-envelope"></i> Email: anita.max.wynn@example.com</li>
                <li><i class="fas fa-phone"></i> Telefon: +49 123 456 7890</li>
                <li><i class="fab fa-linkedin"></i> LinkedIn: <a href="https://www.linkedin.com/in/anita-max-wynn" target="_blank">linkedin.com/in/anita-max-wynn</a></li>
            </ul>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Anita Max Wynn. Alle Rechte vorbehalten.</p>
    </footer>
</body>
</html>
