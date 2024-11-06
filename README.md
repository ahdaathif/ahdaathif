<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A personal portfolio showcasing my skills, projects, and experience.">
    <title>Your Name - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">Your Logo</div>
            <ul class="nav-links">
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <div class="container">
            <h1>About Me</h1>
            <p>Hi, I'm [Your Name], a passionate web developer with experience in front-end and back-end technologies. I love building clean and scalable web applications. Here are some of my skills:</p>
            <ul>
                <li>HTML, CSS, JavaScript</li>
                <li>React, Node.js</li>
                <li>Python, Django</li>
                <li>Git, GitHub</li>
            </ul>
        </div>
    </section>

    <section id="projects">
        <div class="container">
            <h1>Projects</h1>
            <div class="project-card">
                <img src="project1.jpg" alt="Project 1">
                <h3>Project 1</h3>
                <p>A short description of the project and the technologies used.</p>
                <a href="https://github.com/yourusername/project1" target="_blank">View on GitHub</a>
            </div>
            <div class="project-card">
                <img src="project2.jpg" alt="Project 2">
                <h3>Project 2</h3>
                <p>A short description of the project and the technologies used.</p>
                <a href="https://github.com/yourusername/project2" target="_blank">View on GitHub</a>
            </div>
            <!-- Add more project cards as needed -->
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h1>Contact</h1>
            <p>If you'd like to get in touch with me, feel free to send a message!</p>
            <form action="mailto:your-email@example.com" method="post" enctype="text/plain">
                <label for="name">Your Name</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Your Email</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Your Name. All rights reserved.</p>
            <div class="social-links">
                <a href="https://github.com/yourusername" target="_blank">GitHub</a>
                <a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
            </div>
        </div>
    </footer>
</body>
</html>
