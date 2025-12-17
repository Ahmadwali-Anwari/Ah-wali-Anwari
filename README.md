<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Ahmad Wali Anwari - Resume</title>
  <style>
    /* Body & Fonts */
    body {
      background-color: #121212;
      color: #E0E0E0;
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
    }

    /* Header */
    header {
      text-align: center;
      padding: 50px 20px;
    }

    header h1 {
      font-size: 36px;
      margin-bottom: 10px;
    }

    header p {
      font-size: 18px;
      color: #B0B0B0;
    }

    /* Sections */
    section {
      max-width: 800px;
      margin: 50px auto;
      padding: 20px;
    }

    section h2 {
      border-bottom: 2px solid #555;
      padding-bottom: 5px;
      margin-bottom: 20px;
      color: #FFFFFF;
    }

    /* Lists */
    ul {
      list-style-type: none;
      padding: 0;
    }

    ul li {
      margin-bottom: 10px;
      padding-left: 10px;
      position: relative;
    }

    ul li::before {
      content: "•";
      position: absolute;
      left: 0;
      color: #FF9800;
    }

    /* Links */
    a {
      color: #FF9800;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    /* Contact Form */
    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: none;
      border-radius: 5px;
      background-color: #1E1E1E;
      color: #E0E0E0;
    }

    form button {
      padding: 10px 20px;
      background-color: #FF9800;
      color: #121212;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    form button:hover {
      background-color: #e68a00;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Ahmad Wali Anwari</h1>
    <p>Full-Stack Developer | Passionate About AI & Web</p>
  </header>

  <!-- About Section -->
  <section>
    <h2>About Me</h2>
    <p>I am a software engineer with experience in full-stack web development. I love building projects that combine technology and creativity.</p>
  </section>

  <!-- Skills Section -->
  <section>
    <h2>Skills</h2>
    <ul>
      <li>HTML, CSS, JavaScript</li>
      <li>React, Node.js, Express</li>
      <li>Python, Django</li>
      <li>Git & GitHub</li>
      <li>SQL & NoSQL Databases</li>
    </ul>
  </section>

  <!-- Experience Section -->
  <section>
    <h2>Experience</h2>
    <ul>
      <li>Software Engineer at XYZ Company (2023 - Present)</li>
      <li>Full-Stack Developer at ABC Startup (2021 - 2023)</li>
    </ul>
  </section>

  <!-- Portfolio Section -->
  <section>
    <h2>Portfolio</h2>
    <ul>
      <li><a href="#">Project One</a> - Web application built with React & Node.js</li>
      <li><a href="#">Project Two</a> - Django-based project with REST API</li>
    </ul>
  </section>

  <!-- Contact Section -->
  <section>
    <h2>Contact</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message" rows="5" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

</body>
</html>
