<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <title>Lebenslauf – Kevin Weber</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: #007BFF;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background: #222;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0;
        }
        nav ul li a {
            display: block;
            padding: 15px 20px;
            color: white;
            text-decoration: none;
        }
        nav ul li a:hover {
            background: #444;
        }
        section {
            padding: 40px 20px;
            max-width: 900px;
            margin: auto;
        }
        h2 {
            border-bottom: 2px solid #007BFF;
            padding-bottom: 5px;
        }
        .card {
            background: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 15px;
        }
        /* Dark Mode */
        .dark {
            background-color: #121212;
            color: #eee;
        }
        .dark header { background: #1e1e1e; }
        .dark nav { background: #000; }
        .dark .card {
            background: #1e1e1e;
            color: #eee;
        }
        .dark nav ul li a:hover { background: #333; }
        .toggle-btn {
            position: fixed;
            bottom: 20px;
            right: 20px;
            padding: 12px 16px;
            border: none;
            border-radius: 50px;
            background: #007BFF;
            color: white;
            cursor: pointer;
        }
    </style>
</head>
<body>

<header>
    <h1>Kevin Weber</h1>
    <p>IT Business Analyst| UX | Product</p>
</header>

<nav>
    <ul>
        <li><a href="#about">Über mich</a></li>
        <li><a href="#skills">Fähigkeiten</a></li>
        <li><a href="#experience">Erfahrung</a></li>
        <li><a href="#education">Ausbildung</a></li>
        <li><a href="#contact">Kontakt</a></li>
    </ul>
</nav>

<section id="about">
    <h2>Über mich</h2>
    <div class="card">
        <p>Ich bin ein motivierter Wirtschaftsinformatiker mit Interesse an modernen Webtechnologien und sauberem Design.</p>
    </div>
</section>

<section id="skills">
    <h2>Fähigkeiten</h2>
    <div class="card">
        <ul>
            <li>HTML, CSS, JavaScript</li>
            <li>Responsive Design</li>
            <li>Dark Mode & UI/UX</li>
        </ul>
    </div>
</section>

<section id="experience">
    <h2>Berufserfahrung</h2>
    <div class="card">
        <h3>IT Business Analyst Landeskrankenhilfe (LKH)</h3>
        <p>2022 – Heute</p>
        <p>Entwicklung und Pflege von App und Kundenportal.</p>
    </div>
</section>

<section id="education">
    <h2>Ausbildung</h2>
    <div class="card">
        <h3>Master of Science Wirtschaftsinformatik</h3>
        <p>2020 – 2022</p>
    </div>
</section>

<section id="contact">
    <h2>Kontakt</h2>
    <div class="card">
        <p>Email: max@example.com</p>
        <p>Telefon: +49 123 456789</p>
    </div>
</section>

<footer>
    <p>© 2026 Kevin Weber</p>
</footer>

<button class="toggle-btn" onclick="toggleDarkMode()">🌙</button>

<script>
    function toggleDarkMode() {
        document.body.classList.toggle("dark");
    }
</script>

</body>
</html>
