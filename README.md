<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Ahmad Wali Anwari - Resume</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
  /* Body & Fonts */
  body {
    background-color: #121212;
    color: #E0E0E0;
    font-family: 'Inter', sans-serif;
    margin: 0;
    padding: 0;
    scroll-behavior: smooth;
  }

  a { color: #FF9800; text-decoration: none; }
  a:hover { text-decoration: underline; }

  /* Header */
  header {
    text-align: center;
    padding: 60px 20px;
    background: linear-gradient(135deg,#1a1a1a,#222);
  }
  header h1 {
    font-size: 40px;
    margin-bottom: 10px;
    animation: fadeIn 1s ease-in-out;
  }
  header p {
    font-size: 18px;
    color: #B0B0B0;
    animation: fadeIn 2s ease-in-out;
  }

  /* Sections */
  section {
    max-width: 900px;
    margin: 60px auto;
    padding: 20px;
    animation: fadeUp 1s ease-in-out;
  }
  section h2 {
    border-bottom: 2px solid #555;
    padding-bottom: 5px;
    margin-bottom: 20px;
    color: #FFFFFF;
  }

  /* Lists */
  ul { list-style: none; padding: 0; }
  ul li {
    margin-bottom: 10px;
    padding-left: 15px;
    position: relative;
  }
  ul li::before {
    content: "•";
    position: absolute;
    left: 0;
    color: #FF9800;
  }

  /* Contact Form */
  form input, form textarea {
    width: 100%;
    padding: 12px;
    margin-bottom: 10px;
    border: none;
    border-radius: 6px;
    background-color: #1E1E1E;
    color: #E0E0E0;
  }
  form button {
    padding: 12px 25px;
    background-color: #FF9800;
    color: #121212;
    border: none;
    border-radius: 6px;
    cursor: pointer;
    transition: 0.3s;
  }
  form button:hover {
    background-color: #e68a00;
  }

  /* Responsive */
  @media (max-width: 600px) {
    header h1 { font-size: 32px; }
    header p { font-size: 16px; }
  }

  /* Animations */
  @keyframes fadeIn {
    0% { opacity: 0; transform: translateY(-20px); }
    100% { opacity: 1; transform: translateY(0); }
  }

  @keyframes fadeUp {
    0% { opacity: 0; transform: translateY(30px); }
    100% { opacity: 1; transform: translateY(0); }
  }

  /* Hover effect for projects */
  .project-link:hover { transform: scale(1.02); transition: 0.3s; }
</style>
</head>
<body>

<header>
  <h1>Ahmad Wali Anwari</h1>
  <p>Full-Stack Developer | Passionate About AI & Web</p>
</header>

<section>
  <h2>About Me</h2>
  <p>I am a software engineer with experience in full-stack web development. I love building projects that combine creativity and technology.</p>
</section>

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

<section>
  <h2>Experience</h2>
  <ul>
    <li>Software Engineer at XYZ Company (2023 - Present)</li>
    <li>Full-Stack Developer at ABC Startup (2021 - 2023)</li>
  </ul>
</section>

<section>
  <h2>Portfolio</h2>
  <ul>
    <li><a href="#" class="project-link">Project One</a> - Web application built with React & Node.js</li>
    <li><a href="#" class="project-link">Project Two</a> - Django project with REST API</li>
  </ul>
</section>

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
