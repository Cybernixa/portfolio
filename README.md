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

