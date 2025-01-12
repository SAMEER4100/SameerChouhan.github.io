<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sameer Singh Chouhan - Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      scroll-behavior: smooth;
    }
    /* Navbar */
    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background: #1a1a2e;
      padding: 10px 0;
      display: flex;
      justify-content: center;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      z-index: 1000;
    }
    nav ul {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;
      gap: 20px;
    }
    nav ul li {
      display: inline;
    }
    nav ul li a {
      text-decoration: none;
      color: #fff;
      font-weight: 600;
      padding: 10px 15px;
      border-radius: 5px;
      transition: background 0.3s ease;
    }
    nav ul li a:hover {
      background: #e94560;
    }

    /* Hero Section */
    .hero {
      height: 100vh;
      background: linear-gradient(120deg, #1a1a2e, #16213e);
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 20px;
    }
    .hero img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      margin-bottom: 20px;
      border: 4px solid #e94560;
    }
    .hero h1 {
      font-size: 3rem;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 1.2rem;
      margin-bottom: 30px;
    }
    .hero a {
      text-decoration: none;
      color: white;
      background: #e94560;
      padding: 10px 20px;
      border-radius: 5px;
      font-weight: 600;
      transition: background 0.3s ease;
    }
    .hero a:hover {
      background: #0f3460;
    }

    /* Profile Picture in Navbar */
    .profile-picture {
      position: absolute;
      top: 10px;
      left: 10px;
      width: 50px;
      height: 50px;
      border-radius: 50%;
      border: 2px solid #e94560;
    }

    /* About Section */
    .about {
      padding: 60px 20px;
      background: #f4f4f9;
      text-align: center;
    }
    .about h2 {
      font-size: 2rem;
      margin-bottom: 20px;
    }
    .about p {
      font-size: 1.1rem;
      max-width: 800px;
      margin: 0 auto;
      line-height: 1.6;
    }

    /* Projects Section */
    .projects {
      padding: 60px 20px;
      background: #16213e;
      color: white;
      text-align: center;
    }
    .projects h2 {
      font-size: 2rem;
      margin-bottom: 20px;
    }
    .projects .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }
    .projects .card {
      background: #1a1a2e;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
      transition: transform 0.3s ease;
    }
    .projects .card:hover {
      transform: scale(1.05);
    }
    .projects .card h3 {
      margin: 0 0 10px;
    }
    .projects .card p {
      font-size: 0.9rem;
      line-height: 1.4;
    }

    /* Contact Section */
    .contact {
      padding: 60px 20px;
      background: #1a1a2e;
      color: white;
      text-align: center;
    }
    .contact h2 {
      font-size: 2rem;
      margin-bottom: 20px;
    }
    .contact a {
      color: #e94560;
      text-decoration: none;
      font-weight: 600;
    }

    /* Footer */
    footer {
      background: #0f3460;
      color: white;
      text-align: center;
      padding: 10px;
    }
  </style>
</head>
<body>
  <nav>
    <img class="profile-picture" src="/path/to/your/image.jpg" alt="Sameer Singh">
    <ul>
      <li><a href="#hero">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section class="hero" id="hero">
    <img src="https://via.placeholder.com/150" alt="Sameer Singh Chouhan">
    <h1>Sameer Singh Chouhan</h1>
    <p>Finance Enthusiast | Aspiring Consultant | Public Relations</p>
    <a href="#about">Learn More</a>
  </section>

  <section class="about" id="about">
    <h2>About Me</h2>
    <p>Hello! I'm Sameer Singh Chouhan, an MBA student specializing in Finance at New York Tech. With a passion for innovation, public relations, and financial strategies, I aim to bring impactful solutions to the industry.</p>
  </section>

  <section class="projects" id="projects">
    <h2>My Projects</h2>
    <div class="grid">
      <div class="card">
        <h3>A detailed financial analysis of emerging market trends.</h3>
      </div>
      <div class="card">
        <h3>Comprehensive cross-cultural communication strategies for global teams.</h3>
      </div>
       <div class="card">
        <h3>Digital Transformation in the Indian Banking Sector</h3>
      </div>
    </div>
  </section>

  <section class="contact" id="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:SAMEER410SINGH@GMAIL.COM">SAMEER410SINGH@GMAIL.COM</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/sameer410/" target="_blank">linkedin.com/in/sameer410</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Sameer Singh Chouhan. All Rights Reserved.</p>
  </footer>
</body>
</html>
