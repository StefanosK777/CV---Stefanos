<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My CV - Stefanos Kelesidis</title>

  <style>
    /* Basic page styling - clean, readable, and responsive */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f9f9f9;
      color: #333;
      scroll-behavior: smooth;
    }

    /* Header section with profile photo and navigation */
    header {
      background: #222;
      color: #fff;
      text-align: center;
      padding: 48px 16px;
    }

    header img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      display: block;
      margin: 0 auto 12px;
      border: 3px solid #fff;
    }

    /* Navigation links */
    nav a {
      color: #ffcc00;
      text-decoration: none;
      margin: 0 8px;
      font-weight: 600;
    }

    nav a:hover {
      text-decoration: underline;
    }

    /* Section styling for clean card-like layout */
    section {
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.06);
      padding: 20px;
      margin: 24px auto;
      max-width: 900px;
    }

    h2 {
      border-bottom: 1px solid #eee;
      padding-bottom: 8px;
      margin: 0;
    }

    /* Skill badges layout */
    .skills { 
      display: flex; 
      flex-wrap: wrap; 
      gap: 8px; 
      margin-top: 8px;
    }

    .skill {
      background: #eef6ff;
      padding: 6px 10px;
      border-radius: 20px;
    }

    /* Button design (used for download link) */
    .btn {
      display: inline-block;
      background: #ffcc00;
      color: #111;
      padding: 8px 12px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: 600;
    }

    .btn:hover { opacity: 0.95; }

    /* Footer text styling */
    footer {
      text-align: center;
      padding: 16px 0;
      color: #666;
      font-size: 0.9rem;
    }

    /* Responsive tweaks for small screens */
    @media (max-width: 600px) {
      header { padding: 32px 12px; }
      header h1 { font-size: 1.6rem; }
    }
  </style>
</head>
<body>

  <header>
    <!-- Profile photo and name -->
    <img src="photo.jpg" alt="Stefanos Kelesidis — profile photo">
    <h1>Stefanos Kelesidis</h1>
    <p>Software Developer • Programmer Enthusiast</p>

    <!-- Main navigation links for page sections -->
    <nav>
      <a href="#about">About</a>
      <a href="#experience">Experience</a>
      <a href="#education">Education</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </nav>

    <!-- Download button for CV PDF -->
    <p style="margin-top:12px;">
      <a href="stefanos-cv.pdf" class="btn" download>Download CV (PDF)</a>
    </p>
  </header>

  <main id="main">
    <!-- About section introducing yourself -->
    <section id="about">
      <h2>About</h2>
      <p>I’m a Developer passionate about writing clean, accessible, 
        and user-friendly code. I’m always eager to learn and expand my 
        skills — whether in frontend, backend, or full-stack development. 
        I’ve studied C++, C#, SQL, JavaScript, and more to grow into a 
        well-rounded developer.</p>
    </section>

    <!-- Work experience details -->
    <section id="experience">
      <h2>Experience</h2>
      <ul>
        <li>
          <strong>Frontend Developer</strong> — Example Company (2023 — Present)
          <p>Developed responsive web apps using HTML, CSS, and JavaScript.</p>
        </li>
        <li>
          <strong>Junior Developer</strong> — Another Company (2021 — 2023)
          <p>Assisted in building UI components and improving website performance.</p>
        </li>
      </ul>
    </section>

    <!-- Education background -->
    <section id="education">
      <h2>Education</h2>
      <ul>
        <li>B.Sc. in Computer Science — European University of Cyprus</li>
      </ul>
    </section>

    <!-- Skills section with highlighted technologies -->
    <section id="skills">
      <h2>Skills</h2>
      <div class="skills">
        <span class="skill">HTML</span>
        <span class="skill">CSS</span>
        <span class="skill">JavaScript</span>
        <span class="skill">SQL</span>
        <span class="skill">C++</span>
        <span class="skill">C#</span>
        <span class="skill">Bash Script</span>


      </div>
    </section>

    <!-- Contact section with email and LinkedIn -->
    <section id="contact">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:kelesidisstephanos@gmail.com">kelesidisstephanos@gmail.com</a></p>
      <p>LinkedIn: <a href="www.linkedin.com/in/stefanos-k-ba68bba7" target="_blank" rel="noopener">Stefanos Kelesidis</a></p>
    </section>
  </main>

  <!-- Simple footer with copyright -->
  <footer>
    <p>&copy; 2025 Stefanos Kelesidis</p>
  </footer>

</body>
</html>
