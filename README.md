<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Project Dashboard</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#certifications">Certifications</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <h1>Welcome to My Project Dashboard</h1>
            <p>Your one-stop solution for project management.</p>
            <a href="#about" class="cta">Learn More</a>
        </section>
        <section id="about">
            <h2>About Me</h2>
            <p>Detailing my experiences and skills.</p>
        </section>
        <section id="projects">
            <h2>My Projects</h2>
            <div class="project-grid">
                <!-- Project items go here -->
            </div>
        </section>
        <section id="certifications">
            <h2>Certifications</h2>
            <div class="certificate">
                <h3>My Certification</h3>
                <img src="certificate.jpg" alt="Certification">
            </div>
        </section>
        <section id="testimonials">
            <h2>Testimonials</h2>
            <blockquote>
                <p>"This is the best project management tool I've ever used!"</p>
                <footer>- Happy User</footer>
            </blockquote>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 My Project Dashboard</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1rem 0;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

main {
    padding: 20px;
}

h1, h2 {
    text-align: center;
}

.project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    margin-top: 20px;
}

section {
    margin: 20px 0;
    padding: 20px;
    background: #fff;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.cta {
    display: block;
    width: 200px;
    margin: 20px auto;
    padding: 10px;
    background: #007BFF;
    color: #fff;
    text-align: center;
    border-radius: 5px;
    text-decoration: none;
    font-size: 18px;
}

footer {
    text-align: center;
    padding: 10px;
    background: #333;
    color: #fff;
    position: relative;
    bottom: 0;
    width: 100%;
}

blockquote {
    font-style: italic;
    margin: 10px auto;
    max-width: 600px;
}

.certificate {
    text-align: center;
}

.certificate img {
    margin-top: 20px;
    border: 1px solid #ccc;
    border-radius: 8px;
    max-width: 100%;
    height: auto;
}