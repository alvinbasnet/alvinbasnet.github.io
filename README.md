<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Alvin Basnet – Engineering Portfolio</title>

  <style>

    /* ------------------
       FONT + BASE
    ------------------ */
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');

    body {
      margin: 0;
      padding: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #081224, #1e3057);
      color: #eaeaea;
    }

    .container {
      max-width: 960px;
      margin: auto;
      padding: 40px 20px;
    }

    h1 {
      font-size: 3rem;
      margin: 0;
      font-weight: 700;
      color: #ffffff;
      text-align: center;
    }

    p.subtitle {
      text-align: center;
      font-size: 1.2rem;
      color: #afafaf;
      margin-top: 8px;
    }

    h2.section-title {
      color: #ffffff;
      margin-top: 2.5rem;
      font-size: 2rem;
      border-left: 5px solid #4cc9f0;
      padding-left: 12px;
    }

    /* ==============================
       PROJECT CARDS
    ============================== */
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 22px;
      margin-top: 24px;
    }

    .card {
      background: rgba(255,255,255,0.07);
      backdrop-filter: blur(12px);
      padding: 22px 18px;
      border-radius: 14px;
      box-shadow: 0 8px 28px rgba(0,0,0,0.3);
      border-top: 4px solid #4cc9f0;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .card:hover {
      transform: translateY(-6px);
      box-shadow: 0 14px 34px rgba(0,0,0,0.4);
    }

    .card h3 {
      margin-top: 0;
      color: #ffffff;
      font-weight: 600;
    }

    .card ul {
      padding-left: 18px;
      color: #dcdcdc;
    }

    .card a {
      display: inline-block;
      margin-top: 10px;
      text-decoration: none;
      color: #4cc9f0;
      font-weight: 600;
    }

    /* ===================
       EXPERIENCE
    =================== */

    .experience {
      margin-top: 24px;
      padding: 18px;
      background: rgba(255,255,255,0.07);
      border-radius: 12px;
      backdrop-filter: blur(10px);
      color: #ededed;
      box-shadow: 0 6px 20px rgba(0,0,0,0.25);
    }

    .experience strong {
      display: block;
      margin-top: 12px;
      font-size: 1.1rem;
      color: #ffffff;
    }

    .experience ul {
      padding-left: 18px;
      list-style-type: disc;
    }

    /* ===================
       CONTACT + BUTTON
    =================== */
    .contact {
      text-align: center;
      margin-top: 50px;
      font-size: 1rem;
      color: #dcdcdc;
    }

    .contact a {
      color: #4cc9f0;
      text-decoration: none;
      font-weight: 700;
    }

  </style>
</head>

<body>

  <!-- ===== HERO ===== -->
  <div class="container">
    <h1>Alvin Basnet</h1>
    <p class="subtitle">Mechanical Engineering (Mechatronics) | Design, Simulation & Systems Engineering</p>

    <!-- ===== EDUCATION ===== -->
    <h2 class="section-title">Education</h2>
    <p><strong>BEng – Mechanical Engineering (Mechatronics)</strong><br />
      Toronto Metropolitan University (2020–2025)</p>
    <p>Relevant Coursework: Mechatronic System Design, Control Systems, Fluid Mechanics & Thermodynamics, Integrated Manufacturing</p>

    <!-- ===== SKILLS ===== -->
    <h2 class="section-title">Technical Skills</h2>
    <p>
      <strong>CAD & Design:</strong> SolidWorks, GD&T<br />
      <strong>Simulation:</strong> COMSOL Multiphysics, MATLAB, Simulink<br />
      <strong>Programming:</strong> Arduino (C/C++), Python<br />
      <strong>Engineering:</strong> Mechanical design, maintenance support, CFD, documentation
    </p>

    <!-- ===== PROJECTS ===== -->
    <h2 class="section-title">Featured Projects</h2>
    <div class="projects">

      <div class="card">
        <h3>Passive Microfluidic Micromixer</h3>
        <ul>
          <li>Designed & simulated microfluidic channels in COMSOL</li>
          <li>Improved mixing efficiency by ~35%</li>
        </ul>
        <a href="https://github.com/alvinbasnet/passive-micromixer-comsol" target="_blank">View Project →</a>
      </div>

      <div class="card">
        <h3>Self-Balancing Inverted Pendulum</h3>
        <ul>
          <li>Arduino-based inverted pendulum</li>
          <li>PID + control implementation</li>
        </ul>
        <a href="https://github.com/alvinbasnet/self-balancing-inverted-pendulum-robot" target="_blank">View Project →</a>
      </div>

      <div class="card">
        <h3>Gauges, Jigs & Fixtures</h3>
        <ul>
          <li>Inspection gauges & manufacturing fixtures</li>
          <li>GD&T (MMC, LMC)</li>
        </ul>
        <a href="https://github.com/alvinbasnet/gauges-jigs-fixtures-design" target="_blank">View Project →</a>
      </div>

      <div class="card">
        <h3>Engineering Maintenance (407 ETR)</h3>
        <ul>
          <li>Inspections & preventive maintenance</li>
          <li>Reliability-focused engineering</li>
        </ul>
        <a href="https://github.com/alvinbasnet/maintenance-reliability-engineering" target="_blank">View Project →</a>
      </div>

    </div>

    <!-- ===== EXPERIENCE ===== -->
    <h2 class="section-title">Experience Highlights</h2>
    <div class="experience">
      <strong>Highway Operations Intern – 407 ETR</strong>
      <ul>
        <li>Maintenance & reliability of electromechanical systems</li>
        <li>Inspections & technical data analysis</li>
      </ul>

      <strong>Part-Time Manager – Marigold Indian Bistro</strong>
      <ul>
        <li>Operations & maintenance problem solving</li>
        <li>Improved efficiency by 30%</li>
      </ul>
    </div>

    <!-- ===== CONTACT ===== -->
    <div class="contact">
      📧 alvinbasnet21@gmail.com<br />
      🔗 <a href="#">LinkedIn (add link)</a>
    </div>
  </div>

</body>
</html>
