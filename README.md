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
       GLOBAL STYLES
    ========================= */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: #0b0b0b;
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
        linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)),
        url("images/background.jpg"); /* ADD YOUR IMAGE HERE */
      background-size: cover;
      background-position: center;
    }

    /* =========================
       HEADER BOX
    ========================= */
    .header-box {
      position: absolute;
      top: 30px;
      left: 30px;
      right: 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 18px 26px;
      border: 1.5px solid rgba(255,255,255,0.4);
      border-radius: 18px;
      backdrop-filter: blur(6px);
    }

    /* LOGO + NAME */
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
      font-size: 1.7rem;
      font-weight: 700;
      letter-spacing: 2px;
    }

    .name-text {
      font-family: 'Great Vibes', cursive;
      font-size: 2.2rem;
      white-space: nowrap;
    }

    /* RESUME BUTTON */
    .resume-box {
      border: 1.5px solid white;
      padding: 10px 24px;
      border-radius: 999px;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    .resume-box:hover {
      background: white;
      color: black;
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
    }

    .hero-subtitle {
      font-size: 1.2rem;
      letter-spacing: 3px;
      text-transform: uppercase;
      margin-bottom: 12px;
      opacity: 0.9;
    }

    .hero-title {
      font-family: 'Great Vibes', cursive;
      font-size: 5.2rem;
      line-height: 1;
    }

    /* =========================
       MAIN CONTENT
    ========================= */
    .container {
      max-width: 1000px;
      margin: auto;
      padding: 80px 20px;
    }

    h2 {
      font-size: 2rem;
      margin-bottom: 14px;
      border-left: 4px solid white;
      padding-left: 12px;
    }

    p {
      opacity: 0.9;
      margin-bottom: 16px;
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
      background: rgba(255,255,255,0.07);
      backdrop-filter: blur(12px);
      border-radius: 16px;
      padding: 22px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.4);
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
      opacity: 0.9;
    }

    .card a {
      display: inline-block;
      margin-top: 10px;
      font-weight: 600;
    }

    /* =========================
       EXPERIENCE
    ========================= */
    .experience {
      background: rgba(255,255,255,0.07);
      padding: 22px;
      border-radius: 16px;
      margin-top: 25px;
    }

    /* =========================
       CONTACT
    ========================= */
    .contact {
      text-align: center;
      margin-top: 60px;
      opacity: 0.9;
    }
  </style>
</head>

<body>

  <!-- HERO -->
  <section class="hero">
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
    <p>
      Relevant Coursework: Mechatronic System Design, Control Systems,
      Fluid Mechanics & Thermodynamics, Integrated Manufacturing
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
        <img src="images/micromixer.png" alt="Micromixer">
        <h3>Passive Microfluidic Micromixer</h3>
        <ul>
          <li>Designed & simulated channels in COMSOL</li>
          <li>Improved mixing efficiency by ~35%</li>
        </ul>
        <a href="https://github.com/alvinbasnet/passive-micromixer-comsol">View Project →</a>
      </div>

      <div class="card">
        <img src="images/pendulum.png" alt="Inverted Pendulum">
        <h3>Self-Balancing Inverted Pendulum</h3>
        <ul>
          <li>Arduino-based control system</li>
          <li>PID & pole placement</li>
        </ul>
        <a href="https://github.com/alvinbasnet/self-balancing-inverted-pendulum-robot">View Project →</a>
      </div>

      <div class="card">
        <img src="images/gauges.png" alt="Gauges">
        <h3>Gauges, Jigs & Fixtures</h3>
        <ul>
          <li>Inspection gauges</li>
          <li>GD&T (MMC, LMC)</li>
        </ul>
        <a href="https://github.com/alvinbasnet/gauges-jigs-fixtures-design">View Project →</a>
      </div>

      <div class="card">
        <img src="images/maintenance.png" alt="Maintenance">
        <h3>Engineering Maintenance (407 ETR)</h3>
        <ul>
          <li>Preventive maintenance</li>
          <li>Reliability-focused engineering</li>
        </ul>
        <a href="https://github.com/alvinbasnet/maintenance-reliability-engineering">View Project →</a>
      </div>

    </div>

    <h2>Experience Highlights</h2>
    <div class="experience">
      <strong>Highway Operations Intern – 407 ETR</strong>
      <ul>
        <li>Electromechanical maintenance & inspections</li>
        <li>Technical data analysis</li>
      </ul>

      <strong>Part-Time Manager – Marigold Indian Bistro</strong>
      <ul>
        <li>Operational problem solving</li>
        <li>Improved efficiency by 30%</li>
      </ul>
    </div>

    <div class="contact">
      📧 alvinbasnet21@gmail.com <br>
      🔗 LinkedIn (add link)
    </div>

  </div>

</body>
</html>
