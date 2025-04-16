<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>John Doe | Web Developer Portfolio</title>
  <style>
    /* General Styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
      color: #333;
    }

    header {
      background: #333;
      color: #fff;
      padding: 2em 3em;
      text-align: center;
    }

    header h1 {
      margin: 0;
    }

    header nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-size: 1.1em;
    }

    header nav a:hover {
      text-decoration: underline;
    }

    section {
      padding: 3em;
    }

    /* About Section */
    #about {
      background: #fff;
      text-align: center;
    }

    #about p {
      max-width: 800px;
      margin: 0 auto;
      font-size: 1.2em;
    }

    /* Projects Section */
    #projects {
      background: #f9f9f9;
    }

    .project {
      margin-bottom: 2em;
      background: #fff;
      padding: 1.5em;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    .project h3 {
      margin-top: 0;
    }

    .project p {
      font-size: 1.1em;
      margin-bottom: 1em;
    }

    .project a {
      color: #333;
      text-decoration: none;
      background: #4CAF50;
      padding: 10px 20px;
      border-radius: 4px;
      font-weight: bold;
    }

    .project a:hover {
      background: #45a049;
    }

    /* Contact Form */
    #contact {
      background: #fff;
      padding: 2em;
      text-align: center;
    }

    form input,
    form textarea {
      width: 100%;
      padding: 0.8em;
      margin: 0.5em 0;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 1em;
    }

    form button {
      background-color: #333;
      color: white;
      padding: 0.8em 2em;
      border: none;
      cursor: pointer;
      border-radius: 4px;
      font-size: 1.1em;
    }

    form button:hover {
      background-color: #555;
    }

    /* Footer Section */
    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 1.5em;
      margin-top: 2em;
    }

    footer p {
      font-size: 1.1em;
    }

    /* Media Queries for Mobile Responsiveness */
    @media (max-width: 768px) {
      header {
        padding: 1.5em;
      }

      section {
        padding: 2em;
      }

      header nav a {
        display: block;
        margin-bottom: 10px;
      }
    }
  </style>
</head>

<body>

  <header>
    <h1>John Doe</h1>
    <p>Web Developer | Designer | Tech Enthusiast</p>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm John, a passionate web developer who loves building beautiful and functional websites. I enjoy learning new technologies and solving real-world problems through code. I have experience working with HTML, CSS, JavaScript, and various frameworks and libraries. When I'm not coding, I enjoy exploring new tech trends and keeping up-to-date with the latest industry news.</p>
  </section>

  <section id="projects">
    <h2>My Projects</h2>

    <div class="project">
      <h3>Portfolio Website</h3>
      <p>This is my personal portfolio, designed to showcase my web development skills. It is built using HTML, CSS, and JavaScript, with a clean and modern design that adapts to all screen sizes.</p>
      <a href="#" target="_blank">View Project</a>
    </div>

    <div class="project">
      <h3>To-Do App</h3>
      <p>A simple to-do list app where users can add, edit, and remove tasks. It uses local storage to save tasks between sessions, making it a handy tool for organizing day-to-day activities.</p>
      <a href="#" target="_blank">View Project</a>
    </div>

    <div class="project">
      <h3>Weather Dashboard</h3>
      <p>This project fetches real-time weather data based on the user's location or city input. Built using JavaScript, APIs, and a responsive design for seamless mobile experience.</p>
      <a href="#" target="_blank">View Project</a>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form>
      <label for="name">Name:</label><br />
      <input type="text" id="name" name="name" required><br /><br />

      <label for="email">Email:</label><br />
      <input type="email" id="email" name="email" required><br /><br />

      <label for="message">Message:</label><br />
      <textarea id="message" name="message" rows="5" required></textarea><br /><br />

      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>© 2025 John Doe. All rights reserved.</p>
  </footer>

</body>

</html>

