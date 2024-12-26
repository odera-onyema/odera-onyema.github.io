<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Professional website showcasing my portfolio, experience, and skills.">
    <title>Odera Onyema</title>
    <link rel="stylesheet" href="styles/style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>My Name</h1>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <main>
        <section id="about">
            <div class="container">
                <h2>About Me</h2>
                <p>Welcome to my professional website! I am an expert in public health, with a passion for finance, faith, and well-being.</p>
            </div>
        </section>
        <section id="portfolio">
            <div class="container">
                <h2>Portfolio</h2>
                <div class="portfolio-item">
                    <h3>Project Title</h3>
                    <p>Description of the project.</p>
                </div>
                <!-- Add more portfolio items as needed -->
            </div>
        </section>
        <section id="contact">
            <div class="container">
                <h2>Contact</h2>
                <p>Email: <a href="mailto:example@example.com">example@example.com</a></p>
                <p>LinkedIn: <a href="https://www.linkedin.com/in/your-profile" target="_blank">Your LinkedIn Profile</a></p>
            </div>
        </section>
    </main>
    <footer>
        <div class="container">
            <p>&copy; 2024 My Name. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
/* Reset */
body, h1, h2, h3, p, ul, li, a {
    margin: 0;
    padding: 0;
    list-style: none;
    text-decoration: none;
    font-family: Arial, sans-serif;
}

/* Layout */
.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
}

/* Header */
header {
    background-color: #333;
    color: white;
    padding: 10px 0;
}

header h1 {
    font-size: 2rem;
}

header nav ul {
    display: flex;
    justify-content: flex-end;
}

header nav ul li {
    margin-left: 20px;
}

header nav ul li a {
    color: white;
    font-size: 1rem;
}

/* Sections */
section {
    padding: 20px 0;
}

section h2 {
    font-size: 1.5rem;
    margin-bottom: 10px;
}

#about p {
    line-height: 1.6;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}
