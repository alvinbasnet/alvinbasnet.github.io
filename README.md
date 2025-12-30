<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Alvin Basnet | Mechanical Engineering Portfolio</title>

  <!-- GOOGLE FONTS -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&family=Great+Vibes&display=swap" rel="stylesheet">

  <style>
    /* =========================
       GLOBAL RESET
    ========================= */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #0a2a66, #0f4c81);
      color: white;
      line-height: 1.6;
    }

    a {
      color: white;
      text-decoration: none;
    }

    /* =========================
       HERO SECTION
    ========================= */
    .hero {
      position: relative;
      min-height: 100vh;
      background:
        linear-gradient(rgba(0,0,0,0.45), rgba(0,0,0,0.45)),
        url("images/background.jpg"); /* optional image */
      background-size: cover;
      background-position: center;
    }

    /* =========================
       HEADER BOX (TOP)
    ========================= */
    .header-box {
      position: absolute;
      top: 20px;
      left: 20px;
      right: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 18px 26px;
      border: 1.5px solid rgba(255,255,255,0.6);
      border-radius: 18px;
      backdrop-filter: blur(8px);
      background: rgba(255,255,255,0.03);
    }

    .logo-area {
      display: flex;
      align-items: center;
      gap: 16px;
    }

    .logo-box {
      width: 58px;
      height: 58px;
      border: 1.5px solid white;
      border-radius: 14px;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .logo-text {
      font-size: 1.6rem;
      font-weight: 700;
      letter-spacing: 2px;
    }

    .name-text {
      font-family: 'Great Vibes', cursive;
      font-size: 2.2rem;
      white-space: nowrap;
    }

    /* Resume Button */
    .resume-box {
      border: 1.5px solid white;
      padding: 10px 26px;
      border-radius: 999px;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    .resume-box:hover {
      background: white;
      color: #0a2a66;
      transform: translateY(-2px);
    }

    /* =========================
       CENTER HERO TEXT
    ========================= */
    .hero-center {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
      width: 100%;
      padding: 0 20px;
    }

    .hero-subtitle {
      font-size: 1.2rem;
      letter-spacing: 3px;
      text-transform: uppercase;
      margin-bottom: 12px;
      opacity: 0.95;
    }

    .hero-title {
      font-family: 'Great Vibes', cursive;
      font-size: 5.5rem;
      line-height: 1;
    }

    /* =========================
       MAIN CONTENT
    ========================= */
    .container {
      max-width: 1000px;
      margin: auto;
      padding: 90px 20px;
    }

    h2 {
      font-size: 2rem;
      margin-bottom: 14px;
      border-left: 4px solid white;
      padding-left: 12px;
    }

    p {
      margin-bottom: 16px;
      opacity: 0.95;
    }

    /* =========================
       PROJECT CARDS
    ========================= */
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 22px;
      margin-top: 25px;
    }

    .card {
      background: rgba(255,255,255,0.08);
      backdrop-filter: blur(12px);
      border-radius: 18px;
      padding: 22px;
      box-shadow: 0 12px 32px rgba(0,0,0,0.35);
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-6px);
    }

    .card img {
      width: 100%;
      height: 160px;
      object-fit: cover;
      border-radius: 12px;
      margin-bottom: 12px;
    }

    .card h3 {
      margin-bottom: 10px;
    }

    .card ul {
      padding-left: 18px;
      opacity: 0.95;
    }

    /* =========================
       EXPERIENCE
    ========================= */
    .experience {
      background: rgba(255,255,255,0.08);
      padding: 22px;
      border-radius: 18px;
      margin-top: 25px;
    }

    /* =========================
       CONTACT
    ========================= */
    .contact {
      text-align: center;
      margin-top: 60px;
      opacity: 0.95;
    }
  </style>
</head>

<body>

  <!-- HERO -->
  <section class="hero">

    <!-- TOP HEADER BOX -->
    <div class="header-box">
      <div class="logo-area">
        <div class="logo-box">
          <span class="logo-text">AB</span>
        </div>
        <div class="name-text">Alvin Basnet</div>
      </div>

      <div class="resume-box">
        Resume
      </div>
    </div>

    <!-- CENTER TEXT -->
    <div class="hero-center">
      <div class="hero-subtitle">Mechanical Engineering Portfolio</div>
      <div class="hero-title">Alvin Basnet</div>
    </div>

  </section>

  <!-- MAIN CONTENT -->
  <div class="container">

    <h2>Education</h2>
    <p>
      <strong>BEng – Mechanical Engineering (Mechatronics)</strong><br>
      Toronto Metropolitan University (2020–2025)
    </p>

    <h2>Technical Skills</h2>
    <p>
      <strong>CAD & Design:</strong> SolidWorks, GD&T<br>
      <strong>Simulation:</strong> COMSOL Multiphysics, MATLAB, Simulink<br>
      <strong>Programming:</strong> Arduino (C/C++), Python<br>
      <strong>Engineering:</strong> Mechanical design, maintenance support, CFD, documentation
    </p>

    <h2>Featured Projects</h2>
    <div class="projects">

      <div class="card">
        <img src="images/micromixer.png">
        <h3>Passive Microfluidic Micromixer</h3>
        <ul>
          <li>Designed & simulated channels in COMSOL</li>
          <li>Improved mixing efficiency by ~35%</li>
        </ul>
      </div>

      <div class="card">
        <img src="images/pendulum.png">
        <h3>Self-Balancing Inverted Pendulum</h3>
        <ul>
          <li>Arduino-based control system</li>
          <li>PID & pole placement</li>
        </ul>
      </div>

    </div>

    <div class="contact">
      📧 alvinbasnet21@gmail.com
    </div>

  </div>

</body>
</html>
