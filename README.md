<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Jacob Estember | GitHub Profile</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: linear-gradient(to right, #ffe4ec, #ffcce0);
      background-image: url('https://www.transparenttextures.com/patterns/flower-trail.png');
      background-repeat: repeat;
      min-height: 100vh;
      color: #333;
    }

    header {
      width: 100%;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #ffb6c1;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      position: sticky;
      top: 0;
      z-index: 10;
    }

    .logo {
      font-size: 24px;
      font-weight: bold;
      color: #fff;
    }

    nav {
      display: flex;
      gap: 20px;
    }

    nav a {
      text-decoration: none;
      color: white;
      font-weight: bold;
      padding: 8px 16px;
      border-radius: 20px;
      transition: 0.3s;
      cursor: pointer;
    }

    nav a:hover {
      background-color: #ff69b4;
    }

    .home-container {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: calc(100vh - 80px);
      background: url('https://www.transparenttextures.com/patterns/flower-trail.png') repeat,
                  linear-gradient(to bottom, #fff0f5, #ffe4ec);
      text-align: center;
      padding: 20px;
    }

    .home-container .profile-pic {
      width: 200px;
      height: 200px;
      border-radius: 50%;
      border: 6px solid #ff69b4;
      background: url('hk4.jpeg') center/cover no-repeat;
      margin-bottom: 20px;
    }

    .home-container h1 {
      color: #d63384;
      font-size: 36px;
      margin-bottom: 10px;
    }

    .home-container p {
      font-size: 16px;
      color: #555;
      max-width: 600px;
    }

    .section {
      display: none;
      margin-top: 40px;
      padding: 40px;
      background: rgba(255, 255, 255, 0.95);
      border-radius: 15px;
      width: 80%;
      max-width: 900px;
      margin-left: auto;
      margin-right: auto;
      box-shadow: 0 10px 20px rgba(255, 105, 180, 0.1);
    }

    .section.active {
      display: block;
    }

    .section h2 {
      color: #ff69b4;
      margin-bottom: 20px;
    }

    .section img {
      float: right;
      margin-left: 20px;
      width: 140px;
    }

    ul.services-list {
      margin-top: 15px;
      padding-left: 20px;
    }

    ul.services-list li {
      margin-bottom: 10px;
      line-height: 1.6;
    }

    /* 👇 Project Card Styles */
    .project-card {
      background-color: #ffe4ec;
      border: 2px solid #ffb6c1;
      border-radius: 12px;
      padding: 20px;
      margin-bottom: 20px;
      box-shadow: 0 5px 15px rgba(255, 105, 180, 0.1);
      transition: transform 0.2s ease;
    }

    .project-card:hover {
      transform: scale(1.02);
    }

    .project-card h3 {
      color: #d63384;
      margin-bottom: 8px;
    }

    .project-card p {
      color: #555;
      margin-bottom: 12px;
    }

    .project-card a {
      background-color: #ff69b4;
      color: white;
      padding: 8px 14px;
      border-radius: 20px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    .project-card a:hover {
      background-color: #d63384;
    }

    @media (max-width: 600px) {
      .section img {
        float: none;
        display: block;
        margin: 0 auto 20px;
      }

      .home-container h1 {
        font-size: 28px;
      }
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">🌸 Jacob's Hub</div>
    <nav>
      <a onclick="showSection('home')">HOME</a>
      <a onclick="showSection('about')">ABOUT</a>
      <a onclick="showSection('services')">SERVICES</a>
      <a onclick="showSection('projects')">PROJECTS</a>
    </nav>
  </header>

  <div id="home" class="home-container">
    <div class="profile-pic"></div>
    <h1>Jacob A. Estember</h1>
    <p>💻 A passionate IT student at CvSU - CCAT who codes with creativity and wears pink with pride.</p>
  </div>

  <div class="section" id="about">
    <h2>About Me</h2>
    <img src="hk5.jpeg" alt="Student Icon">
    <p>
      My name is <strong>Jacob A. Estember</strong>, a 23-year-old student currently pursuing a Bachelor of Science in Information Technology at Cavite State University – CCAT Campus. I’m passionate about programming and love continuously expanding my skills.
    </p>
    <p>
      My favorite color is <strong>pink</strong> — it reflects my creative and open personality. I bring this same positivity into both my studies and how I work with others.
    </p>
    <p>
      I’ve learned multiple programming languages: <strong>C++, Java, JavaScript, and Python</strong>. C++ lets me dive deep into hardware control, Java is versatile, JavaScript powers the web, and Python is simple yet powerful for data and automation.
    </p>
    <p>
      Beyond the classroom, I explore coding challenges and real projects to apply theory to practice. My goal is to stay current and adaptable in tech while mastering both fundamental and emerging tools.
    </p>
    <p>
      I also value teamwork. Collaborating with peers strengthens my communication and growth as a developer. I aim to build a future in tech full of creativity, code, and continuous learning.
    </p>
  </div>

  <div class="section" id="services">
    <h2>Services I Offer</h2>
    <img src="https://cdn-icons-png.flaticon.com/512/3050/3050525.png" alt="Services Icon">
    <ul class="services-list">
      <li><strong>Custom Website Development</strong> – Fully tailored designs based on client needs.</li>
      <li><strong>Responsive Web Design</strong> – Optimized for all devices.</li>
      <li><strong>Front-End Development</strong> – Stylish, interactive user interfaces.</li>
      <li><strong>Back-End Development</strong> – Secure server-side logic and databases.</li>
      <li><strong>E-commerce Development</strong> – Sell products online with ease.</li>
      <li><strong>Website Maintenance</strong> – Ongoing support, fixes, and updates.</li>
      <li><strong>CMS Integration</strong> – Set up WordPress, Joomla, etc.</li>
      <li><strong>SEO Optimization</strong> – Boost visibility on search engines.</li>
      <li><strong>Landing Page Creation</strong> – High-conversion promotional pages.</li>
      <li><strong>Performance Optimization</strong> – Faster, smoother user experiences.</li>
    </ul>
  </div>

  <div class="section" id="projects">
    <h2>My Projects</h2>

    <div class="project-card">
      <h3>HELLO KITTY LOG IN PHASE</h3>
      <p>It is just a design log in phase related to Hello Kitty</p>
      <a href="Untitled-1.html" target="_blank">View Project</a>
    </div>

    <div class="project-card">
      <h3>MCDO LOG IN PHASE</h3>
      <p>It is just a design log in phase related to MCDONALD'S</p>
      <a href="Untitled-2.html" target="_blank">View Project</a>
    </div>

    <div class="project-card">
      <h3>MANG INASAL LOG IN PHASE</h3>
      <p>It is just a design log in phase related to MANG INASAL</p>
      <a href="Untitled-3.html" target="_blank">View Project</a>
    </div>
  </div>

  <script>
    function showSection(sectionId) {
      document.querySelectorAll('.section, .home-container').forEach(sec => sec.style.display = 'none');
      const selected = document.getElementById(sectionId);
      if (selected) selected.style.display = 'flex';
      if (selected?.classList.contains('section')) selected.style.display = 'block';
    }

    // Show home section by default
    showSection('home');
  </script>

</body>
</html>
