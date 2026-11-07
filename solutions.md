HTML
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Atim Akhtar - Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Atim Akhtar</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Hello! I am a first-year B.Tech CSE student passionate about web development, building clean interfaces, and coding.</p>
        </section>

        <section id="skills">
            <h2>My Skills</h2>
            <ul>
                <li>HTML & CSS</li>
                <li>JavaScript</li>
                <li>Java Programming</li>
            </ul>
        </section>

        <section id="projects">
            <h2>Featured Projects</h2>
            <p>Check out my latest portfolio and web design assignments built using semantic HTML and custom CSS.</p>
        </section>
    </main>

    <footer id="contact">
        <h2>Contact Details</h2>
        <p>Email: atim.akhtar@example.com</p>
        <p>&copy; 2026 Atim Akhtar. All rights reserved.</p>
    </footer>
</body>
</html>
CSS
/* style.css */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f7f6;
    color: #333333;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

header {
    background-color: #2c3e50;
    color: #ffffff;
    padding: 1rem 2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 {
    margin: 0;
    font-size: 1.5rem;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    gap: 20px;
}

nav a {
    color: #ffffff;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #3498db;
}

main {
    max-width: 800px;
    margin: 2rem auto;
    padding: 0 1rem;
}

section {
    background: #ffffff;
    padding: 1.5rem;
    margin-bottom: 1.5rem;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

h2 {
    color: #2c3e50;
    border-bottom: 2px solid #3498db;
    padding-bottom: 0.5rem;
    margin-top: 0;
}

p {
    margin: 0.5rem 0 1rem 0;
}

ul {
    padding-left: 20px;
}

footer {
    background-color: #2c3e50;
    color: #ffffff;
    text-align: center;
    padding: 1.5rem;
    margin-top: 2rem;
}

footer h2 {
    color: #ffffff;
    border-bottom: none;
    font-size: 1.2rem;
}

footer p {
    margin: 0.3rem 0;
}