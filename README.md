//main html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cybernixa</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.24.1/prism.min.js"></script>
</head>
<body>

    <!-- Header Section -->
    <header>
        <div class="container">
            <div class="logo">Cybernixa</div>
            <nav>
                <ul>
                    <li><b><a href="#home">Home</a></b></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#blog">Blog</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <li><a href="#" id="toggle-mode">Dark/Light Mode</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container">
            <h1>Hi, I'm ABHINAV K S</h1>
            <p>Cybersecurity Expert & Ethical Hacker</p>
            <a href="#projects" class="btn">Explore My Work</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <h2>About Me</h2>
            <p>I'm a cybersecurity professional with 2 years of experience in protecting digital assets...</p>
            <!-- Add more content about background, certifications, etc. -->
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills">
        <div class="container">
            <h2>Skills</h2>
            <div class="skill-item">Penetration Testing</div>
            <div class="skill-item">Network Security</div>
            <div class="skill-item">Cyber Security</div>
            <!-- Add more skills -->
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="projects">
        <div class="container">
            <h2>Projects</h2>
            <div class="project-item">
                <h3>Project Title</h3>
                <p>Brief description of the project...</p>
            </div>
            <!-- Add more project items -->
        </div>
    </section>

    <!-- Blog Section -->
    <section id="blog" class="blog">
        <div class="container">
            <h2>Blog</h2>
            <div class="blog-post">
                <h3>Blog Post Title</h3>
                <p>Excerpt from the blog post...</p>
                <a href="#">Read More</a>
            </div>
            <!-- Add more blog posts -->
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <form action="#" method="post">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <div class="container">
            <p>&copy; 2024 Cybernixa. All rights reserved.</p>
            <div class="social-links">
                <a href="#">LinkedIn</a>
                <a href="#">Twitter</a>
                <a href="#">GitHub</a>
            </div>
        </div>
    </footer>

    <!-- Custom Cursor -->
    <div class="custom-cursor"></div>

    <script src="script.js"></script>
</body>
</html>

//style.css
/* General Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
    scroll-behavior: smooth;
}

body {
    background-color: #121212;
    color: #f1f1f1;
    line-height: 1.6;
    overflow-x: hidden;
    transition: background-color 0.3s ease, color 0.3s ease;
}

.container {
    width: 80%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

/* Header Styles */
header {
    background-color: #1f1f1f;
    padding: 20px 0;
    position: sticky;
    top: 0;
    z-index: 1000;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
}

header .logo {
    font-size: 24px;
    color: #00aaff;
    font-weight: bold;
    letter-spacing: 2px;
    text-transform: uppercase;
    display: inline-block;
}

header nav ul {
    list-style: none;
    display: flex;
    justify-content: flex-end;
}

header nav ul li {
    margin-left: 20px;
}

header nav ul li a {
    color: #f1f1f1;
    text-decoration: none;
    padding: 10px 15px;
    transition: color 0.3s ease;
}

header nav ul li a:hover {
    color: #00aaff;
}

/* Hero Section Styles */
.hero {
    text-align: center;
    padding: 120px 0;
    background: linear-gradient(135deg, #1a1a1a, #212121);
    background-size: cover;
    background-attachment: fixed;
    color: #ffffff;
}

.hero h1 {
    font-size: 50px;
    margin-bottom: 10px;
    letter-spacing: 1.5px;
    animation: fadeInDown 1s ease-in-out;
}

.hero p {
    font-size: 24px;
    margin-bottom: 20px;
    color: #bbbbbb;
    animation: fadeInUp 1.2s ease-in-out;
}

.hero .btn {
    background-color: #00aaff;
    color: #121212;
    padding: 12px 25px;
    text-decoration: none;
    border-radius: 50px;
    font-weight: bold;
    text-transform: uppercase;
    transition: background-color 0.3s ease, transform 0.3s ease;
}

.hero .btn:hover {
    background-color: #0088cc;
    transform: translateY(-5px);
}

/* Section Styles */
section {
    padding: 60px 0;
    transition: transform 0.5s ease;
}

section:hover {
    transform: scale(1.02);
}

.about, .skills, .projects, .blog, .contact {
    background-color: #1f1f1f;
    padding: 60px 20px;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
    margin-bottom: 40px;
}

h2 {
    font-size: 36px;
    margin-bottom: 20px;
    text-align: center;
    color: #00aaff;
    position: relative;
    padding-bottom: 10px;
    animation: fadeInDown 1.5s ease-in-out;
}

h2:after {
    content: '';
    width: 100px;
    height: 2px;
    background: #00aaff;
    display: block;
    margin: 10px auto;
}

.project-item, .blog-post {
    margin-bottom: 20px;
    background-color: #282828;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-item:hover, .blog-post:hover {
    transform: translateY(-5px);
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.7);
}

.project-item h3, .blog-post h3 {
    font-size: 28px;
    color: #00aaff;
    margin-bottom: 10px;
}

.contact form input, .contact form textarea {
    width: 100%;
    padding: 12px;
    margin: 10px 0;
    background-color: #282828;
    border: 2px solid #00aaff;
    color: #f1f1f1;
    border-radius: 5px;
    font-size: 16px;
    transition: border-color 0.3s ease;
}

.contact form input:focus, .contact form textarea:focus {
    border-color: #0088cc;
}

.contact form button {
    background-color: #00aaff;
    color: #121212;
    padding: 12px 25px;
    border: none;
    border-radius: 50px;
    font-weight: bold;
    text-transform: uppercase;
    cursor: pointer;
    transition: background-color 0.3s ease, transform 0.3s ease;
}

.contact form button:hover {
    background-color: #0088cc;
    transform: translateY(-5px);
}

/* Footer Styles */
footer {
    background-color: #1f1f1f;
    padding: 20px 0;
    text-align: center;
    box-shadow: 0 -2px 10px rgba(0, 0, 0, 0.5);
    margin-top: 40px;
}

footer p {
    margin-bottom: 10px;
}

footer .social-links a {
    color: #00aaff;
    margin: 0 10px;
    text-decoration: none;
    font-size: 18px;
    transition: color 0.3s ease;
}

footer .social-links a:hover {
    color: #0088cc;
}

/* Custom Cursor Styles */
.custom-cursor {
    width: 20px;
    height: 20px;
    background-color: #00aaff;
    border-radius: 50%;
    position: absolute;
    pointer-events: none;
    transform: translate(-50%, -50%);
    transition: transform 0.15s ease;
    z-index: 9999;
}

/* Toggle Mode Styles */
.light-mode {
    background-color: #ffffff;
    color: #121212;
}

.light-mode header {
    background-color: #f1f1f1;
}

.light-mode .hero {
    background: linear-gradient(135deg, #f1f1f1, #ffffff);
    color: #121212;
}

.light-mode .hero .btn {
    background-color: #005577;
    color: #ffffff;
}

.light-mode .about, .light-mode .skills, .light-mode .projects, .light-mode .blog, .light-mode .contact, .light-mode footer {
    background-color: #f1f1f1;
    color: #121212;
}

.light-mode h2 {
    color: #005577;
}

.light-mode .project-item, .light-mode .blog-post {
    background-color: #e0e0e0;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.light-mode footer .social-links a {
    color: #005577;
}

.light-mode .custom-cursor {
    background-color: #005577;
}

/* Keyframes for Animations */
@keyframes fadeInDown {
    from {
        opacity: 0;
        transform: translateY(-20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

//script.js
// Custom Cursor
const cursor = document.querySelector('.custom-cursor');
document.addEventListener('mousemove', (e) => {
    cursor.style.top = `${e.clientY}px`;
    cursor.style.left = `${e.clientX}px`;
});

// Toggle Dark/Light Mode
const toggleModeBtn = document.getElementById('toggle-mode');
toggleModeBtn.addEventListener('click', () => {
    document.body.classList.toggle('light-mode');
});

