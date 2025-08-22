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

</body>
</html>
/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background: #b19cd9; /* Light purple background */
    color: #333;
}

/* Navbar */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 2rem;
    background: #222;
    color: #fff;
    position: sticky;
    top: 0;
    z-index: 1000;
}

.navbar .logo {
    font-size: 1.5rem;
    font-weight: bold;
}

.navbar ul {
    display: flex;
    list-style: none;
}

.navbar ul li {
    margin-left: 2rem;
}

.navbar ul li a {
    text-decoration: none;
    color: #fff;
    font-weight: 500;
    transition: color 0.3s ease;
}

.navbar ul li a:hover {
    color: #b19cd9; /* Hover effect matching background */
}

/* Header Section */
header {
    padding: 4rem 2rem;
    text-align: center;
    background: #d8b7ff;
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}

header p {
    font-size: 1.2rem;
}

/* Main Section */
main {
    padding: 2rem;
}

/* Footer */
footer {
    text-align: center;
    padding: 2rem;
    background: #222;
    color: #fff;
    margin-top: 2rem;
}

/* Responsive */
@media (max-width: 768px) {
    .navbar ul {
        flex-direction: column;
        gap: 1rem;
    }
}
// Toggle mobile menu

const menuToggle = document.getElementById("menu-toggle");

const navLinks = document.getElementById("nav-links");

menuToggle.addEventListener("click", () => {

    navLinks.classList.toggle("active");

});
