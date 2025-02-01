# Codtech-Intership-Projects
#   TASK 1
#  DEVELOP A STATIC WEBSITE FOR A DEVELOPERS PORTFOLIO USING HTML, CSS, AND JAVASCRIPT 
# HTML:-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Name - Developer Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Header Section -->
  <header>
    <div class="container">
      <h1>Your Name</h1>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- About Section -->
  <section id="about" class="section">
    <div class="container">
      <h2>About Me</h2>
      <p>Hi, I'm a web developer passionate about building user-friendly websites and applications. I specialize in frontend development using HTML, CSS, and JavaScript, and love creating seamless user experiences.</p>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="section">
    <div class="container">
      <h2>My Projects</h2>
      <div class="project">
        <h3>Project 1</h3>
        <p>A web app that helps users track their tasks.</p>
        <a href="https://github.com/yourgithub/project1" target="_blank">View on GitHub</a>
      </div>
      <div class="project">
        <h3>Project 2</h3>
        <p>A portfolio website template for developers.</p>
        <a href="https://github.com/yourgithub/project2" target="_blank">View on GitHub</a>
      </div>
      <!-- Add more projects here -->
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="section">
    <div class="container">
      <h2>Contact Me</h2>
      <form id="contact-form">
        <label for="name">Your Name</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Your Email</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Your Message</label>
        <textarea id="message" name="message" required></textarea>

        <button type="submit">Send Message</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <div class="container">
      <p>&copy; 2025 Your Name. All rights reserved.</p>
    </div>
  </footer>

  <script src="scripts.js"></script>
</body>
</html>

