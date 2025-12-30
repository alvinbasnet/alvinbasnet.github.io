<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Alvin Basnet | Engineering Portfolio</title>

  <style>
    :root {
      --primary: #1f4fd8;
      --text: #222;
      --muted: #555;
      --bg: #f5f7fb;
      --card: #ffffff;
    }

    * {
      box-sizing: border-box;
      font-family: "Segoe UI", Tahoma, sans-serif;
    }

    body {
      margin: 0;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 40px 20px;
    }

    h1 {
      font-size: 2.4rem;
      margin-bottom: 5px;
    }

    h2 {
      margin-top: 50px;
      border-left: 5px solid var(--primary);
      padding-left: 12px;
    }

    p {
      color: var(--muted);
    }

    /* ===== PROJECT CARDS ===== */
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
      margin-top: 25px;
    }

    .project-card {
      background: var(--card);
      border-radius: 12px;
      padding: 22px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.08);
      transition: transform 0.25s ease, box-shadow 0.25s ease;
      border-top: 5px solid var(--primary);
    }

    .project-card:hover {
      transform: translateY(-6px);
      box-shadow: 0 14px 28px rgba(0,0,0,0.12);
    }

    .project-card h3 {
      margin-top: 0;
      margin-bottom: 10px;
    }

    .project-card ul {
      padding-left: 18px;
      margin-bottom: 15px;
    }

    .project-card a {
      text-decoration: none;
      color: var(--primary);
      font-weight: 600;
    }

    /* ===== EXPERIENCE ===== */
    .experience {
      background: var(--card);
      padding: 20px;
      border-radius: 12px;
      margin-top: 20px;
      box-shadow: 0 6px 16px rgba(0,0,0,0.08);
    }

    /* ===== FOOTER ===== */
    .contact {
      margin-top: 60px;
      text-align: center;
      font-size: 0.95rem;
    }

    .contact a {
      color: var(--primary);
      text-decoration: none;
      font-weight: 600;
    }
  </style>
</head>

<body>
  <div class="container">

    <h1>Alvin Basnet</h1>
    <p>
      Mechanical Engineering (Mechatronics) student with hands-on experience in
      mechanical design, electromechanical systems, maintenance support, and
      engineering analysis.
    </p>

    <h2>Education</h2>
    <p>
      <strong>BEng – Mechanical Engineering (Mechatronics)</strong><br />
      Toronto Metropolitan University (2020–2025)
    </p>
    <p>
      Relevant Coursework: Mechatronic System Design, Control Systems,
      Fluid Mechanics & Thermodynamics, Integrated Manufacturing
    </p>

    <h2>Technical Skills</h2>
    <p>
      <strong>CAD & Design:</strong> SolidWorks, GD&T<br />
      <strong>Simulation:</strong> COMSOL Multiphysics, MATLAB, Simulink<br />
      <strong>Programming:</strong> Arduino (C/C++), Python<br />
      <strong>Engineering:</strong> Mechanical design, maintenance support, CFD, documentation
    </p>

    <h2>Featured Projects</h2>

    <div class="projects">

      <div class="project-card">
        <h3>Passive Microfluidic Micromixer (Capstone)</h3>
        <ul>
          <li>Designed and simulated passive microfluidic channels in COMSOL</li>
          <li>Achieved ~35% improvement in mixing efficiency</li>
        </ul>
        <a href="https://github.com/alvinbasnet/passive-micromixer-comsol">View Project →</a>
      </div>

      <div class="project-card">
        <h3>Self-Balancing Inverted Pendulum</h3>
        <ul>
          <li>Designed and built an Arduino-based inverted pendulum system</li>
          <li>Implemented PID and pole placement control</li>
        </ul>
        <a href="https://github.com/alvinbasnet/self-balancing-inverted-pendulum-robot">View Project →</a>
      </div>

      <div class="project-card">
        <h3>Gauges, Jigs & Fixtures Design</h3>
        <ul>
          <li>Designed inspection gauges and manufacturing fixtures</li>
          <li>Applied GD&T principles (MMC, LMC)</li>
        </ul>
        <a href="https://github.com/alvinbasnet/gauges-jigs-fixtures-design">View Project →</a>
      </div>

      <div class="project-card">
        <h3>Engineering Maintenance & Reliability (407 ETR)</h3>
        <ul>
          <li>Supported inspections and preventive maintenance</li>
          <li>Applied reliability and safety-focused engineering principles</li>
        </ul>
        <a href="https://github.com/alvinbasnet/maintenance-reliability-engineering">View Project →</a>
      </div>

    </div>

    <h2>Experience Highlights</h2>

    <div class="experience">
      <strong>Highway Operations Intern – 407 ETR</strong>
      <ul>
        <li>Supported maintenance and reliability of electromechanical systems</li>
        <li>Performed inspections and technical data analysis</li>
      </ul>

      <strong>Part-Time Manager – Marigold Indian Bistro</strong>
      <ul>
        <li>Solved operational and maintenance challenges</li>
        <li>Improved efficiency by 30%</li>
      </ul>
    </div>

    <div class="contact">
      📧 alvinbasnet21@gmail.com <br />
      🔗 <a href="#">LinkedIn (add link)</a>
    </div>

  </div>
</body>
</html>
