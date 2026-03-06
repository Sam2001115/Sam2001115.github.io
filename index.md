---
layout: default
title: Sameer Appasa | EE Portfolio
---

<style>
  body { font-family: 'Inter', sans-serif; background-color: #0d1117; color: #c9d1d9; line-height: 1.6; }
  .hero { padding: 60px 20px; text-align: center; background: linear-gradient(135deg, #1f6feb 0%, #111 100%); border-bottom: 1px solid #30363d; }
  .hero h1 { font-size: 2.5rem; color: #fff; margin-bottom: 10px; }
  .container { max-width: 900px; margin: 0 auto; padding: 40px 20px; }
  .skills-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin-bottom: 40px; }
  .skill-card { background: #161b22; padding: 20px; border-radius: 8px; border: 1px solid #30363d; transition: transform 0.3s ease; }
  .skill-card:hover { transform: translateY(-5px); border-color: #58a6ff; }
  .project-card { background: #161b22; margin-bottom: 30px; border-radius: 12px; border: 1px solid #30363d; overflow: hidden; transition: 0.3s; }
  .project-card:hover { border-color: #58a6ff; box-shadow: 0 10px 30px rgba(0,0,0,0.5); }
  .project-content { padding: 25px; }
  .project-tag { background: #1f6feb; color: white; padding: 4px 12px; border-radius: 20px; font-size: 0.8rem; font-weight: bold; }
  .btn { display: inline-block; padding: 10px 20px; background: #238636; color: white; border-radius: 6px; text-decoration: none; font-weight: bold; margin-top: 15px; }
  .btn:hover { background: #2ea043; }
</style>

<div class="hero">
  <h1>Sameer Appasa</h1>
  <p>Electrical Engineering Student | Embedded Systems & IoT Developer</p>
</div>

<div class="container">
  <h2>🛠 Technical Toolkit</h2>
  <div class="skills-grid">
    <div class="skill-card"><h3>Embedded</h3>ESP32, Arduino, OUSB[cite: 1]</div>
    <div class="skill-card"><h3>Languages</h3>C++, Python, Java</div>
    <div class="skill-card"><h3>Sim Tools</h3>Multisim Live, VS Code</div>
    <div class="skill-card"><h3>Connectivity</h3>Telegram API, I2C, Wi-Fi</div>
  </div>

  <h2>🚀 Featured Projects</h2>

  <div class="project-card">
    <div class="project-content">
      <span class="project-tag">Robotics</span>
      <h3>Autonomous Surface Rover</h3>
      <p>A custom-geared mobile platform featuring real-time obstacle avoidance and optimized torque delivery for hardwood cleaning.</p>
      <a href="rover.md" class="btn">View Case Study</a>
    </div>
  </div>

  <div class="project-card">
    <div class="project-content">
      <span class="project-tag">IoT</span>
      <h3>Room Security Monitor</h3>
      <p>Secure room monitoring using ESP32 with Telegram bot integration and a custom healthcheck watchdog system.</p>
      <a href="#" class="btn">Coming Soon</a>
    </div>
  </div>

  <div class="project-card">
    <div class="project-content">
      <span class="project-tag">Software Architecture</span>
      <h3>OUSB Process Control System</h3>
      <p>A high-level C++ implementation for hardware register manipulation with a strict priority error-handling hierarchy[cite: 1].</p>
      <a href="ousb.md" class="btn">Read Technical Brief</a>
    </div>
  </div>
</div>
