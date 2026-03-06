---
layout: default
title: Sameer Appasa | EE Portfolio
show_downloads: false
---

<style>
  /* Base Styles */
  body { font-family: 'Inter', sans-serif; background-color: #0d1117; color: #c9d1d9; line-height: 1.6; margin: 0; }
  
  /* Transparent Navigation Bar */
  .navbar { 
    position: fixed; top: 0; width: 100%; height: 60px;
    background: rgba(13, 17, 23, 0.8); backdrop-filter: blur(10px); 
    display: flex; align-items: center; justify-content: space-between;
    padding: 0 50px; border-bottom: 1px solid rgba(255,255,255,0.1); z-index: 1000;
  }
  .nav-logo { font-weight: bold; color: #58a6ff; font-size: 1.2rem; }

  /* Hero Section */
  .hero { 
    padding: 120px 20px 80px; text-align: center; 
    background: radial-gradient(circle at center, #1f6feb33 0%, #0d1117 100%); 
  }
  .hero h1 { font-size: 3rem; color: #fff; margin-bottom: 10px; letter-spacing: -1px; }

  /* Content Containers */
  .container { max-width: 900px; margin: 0 auto; padding: 40px 20px; }
  
  .skills-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin-bottom: 40px; }
  .skill-card { background: #161b22; padding: 20px; border-radius: 8px; border: 1px solid #30363d; }
  
  .project-card { 
    background: #161b22; margin-bottom: 30px; border-radius: 12px; 
    border: 1px solid #30363d; overflow: hidden; transition: 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275); 
  }
  .project-card:hover { transform: scale(1.02); border-color: #58a6ff; }
  .project-content { padding: 25px; }
  
  .btn { 
    display: inline-block; padding: 10px 24px; background: transparent; 
    color: #58a6ff; border: 1px solid #58a6ff; border-radius: 6px; 
    text-decoration: none; font-weight: 600; transition: 0.3s;
  }
  .btn:hover { background: #58a6ff; color: #fff; }
</style>

<div class="navbar">
  <div class="nav-logo">SA.Engineering</div>
  <div class="nav-links">
    <a href="mailto:your-email@example.com" style="color: #c9d1d9; text-decoration: none; margin-left: 20px;">Contact</a>
  </div>
</div>

<div class="hero">
  <h1>Sameer Appasa</h1>
  <p style="font-size: 1.2rem; color: #8b949e;">Second Year Electrical Engineering | RMIT University</p>
</div>

<div class="container">
  <h2>🛠 Technical Toolkit</h2>
  <div class="skills-grid">
    <div class="skill-card"><h3>Embedded</h3>ESP32, Arduino, OUSB Hardware</div>
    <div class="skill-card"><h3>Languages</h3>C++, Python, Java, HTML</div>
    <div class="skill-card"><h3>Simulation</h3>Multisim Live, VS Code, Git</div>
  </div>

  <h2>🚀 Featured Projects</h2>

  <div class="project-card">
    <div class="project-content">
      <h3>Autonomous Surface Rover</h3>
      <p>Custom mechanical drive-train design with real-time obstacle avoidance logic.</p>
      <a href="rover.md" class="btn">View Project</a>
    </div>
  </div>

  <div class="project-card">
    <div class="project-content">
      <h3>OUSB Process Control</h3>
      <p>Register-level C++ programming with advanced error-precedence protocols.</p>
      <a href="ousb.md" class="btn">View Technical Brief</a>
    </div>
  </div>
</div>
