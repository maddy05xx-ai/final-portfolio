# final-portfolio
created by maddy .
# Student-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Maddy | Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <script defer src="script.js"></script>
</head>
<body>

    <!-- Navigation Bar -->
    <header>
        <nav class="navbar">
            <div class="logo">Maddy.BCA</div>
            <ul class="nav-links" id="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#Settings">Settings</a></li>
            </ul>
            <div class="menu-toggle" id="menu-toggle">&#9776;</div>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Hi, I’m <span>Maddy</span> 👋</h1>
            <p>A curious learner passionate about <strong>Web Development</strong>, <strong>Design</strong>, and <strong>Problem Solving</strong>.</p>
            <a href="#projects" class="btn">See My Work</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>
            I’m a student developer exploring the world of technology and coding.  
            My main interests include building responsive websites, experimenting with new frameworks,  
            and solving real-world problems through creative solutions.
        </p>
        <p>
            When I’m not coding, I enjoy Sleeping, Watching Tech Channels, and playing Games ♟️.
        </p>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Featured Projects</h2>
        <div class="project">
            <h3>Portfolio Website</h3>
            <p>A personal portfolio built with HTML, CSS, and JavaScript to showcase my skills and projects.</p>
            <a href="#" target="_blank">View Project</a>
        </div>
        <div class="project">
            <h3>Weather App</h3>
            <p>A simple weather app that fetches real-time data from an API and displays current weather conditions.</p>
            <a href="#" target="_blank">View Project</a>
        </div>
        <div class="project">
            <h3>Student Notes App</h3>
            <p>A notes-taking web app with local storage, allowing students to save and manage their study notes easily.</p>
            <a href="#" target="_blank">View Project</a>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Let’s Connect</h2>
        <p>If you’d like to collaborate, share ideas, or just say hi — feel free to drop me a message!</p>
        <form>
            <label for="name">Your Name:</label>
            <input type="text" id="name" placeholder="Enter your name" required>
            
            <label for="email">Your Email:</label>
            <input type="email" id="email" placeholder="Enter your email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" placeholder="Write your message..." required></textarea>
            
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Maddy.BCA | Designed with ❤️ by Maddy</p>
    </footer>
