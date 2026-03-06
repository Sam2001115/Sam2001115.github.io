---
layout: null
title: Sameer Appasa | EE Portfolio
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        /* Hides GitHub Branding */
        header, .site-header, .project-name, .project-tagline { display: none !important; visibility: hidden !important; }

        body { font-family: 'Inter', -apple-system, sans-serif; background-color: #0d1117; color: #c9d1d9; margin: 0; padding: 0; }
        .hero { padding: 100px 20px 60px; text-align: center; background: radial-gradient(circle at center, #1f6feb22 0%, #0d1117 100%); }
        .hero h1 { font-size: 3.5rem; color: #fff; margin: 0; letter-spacing: -2px; }
        .hero p { font-size: 1.2rem; color: #8b949e; margin-top: 10px; }

        .container { max-width: 850px; margin: 0 auto; padding: 40px 20px; }
        h2 { border-bottom: 1px solid #30363d; padding-bottom: 10px; color: #58a6ff; margin-top: 40px; }

        .skills-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 15px; margin-bottom: 40px; }
        .skill-card { background: #161b22; padding: 15px; border-radius: 8px; border: 1px solid #30363d; }
        .skill-card h3 { margin-top: 0; font-size: 1rem; color: #f0f6fc; }

        .project-card { background: #161b22; margin-bottom: 25px; border-radius: 12px; border: 1px solid #30363d; overflow: hidden; transition: 0.3s; }
        .project-card:hover { border-color: #58a6ff; background: #1c2128; transform: translateY(-5px); }
        .project-content { padding: 25px; }
        .tag { background: #1f6feb; color: white; padding: 3px 10px; border-radius: 12px; font-size: 0.75rem; font-weight: bold; margin-bottom: 10px; display: inline-block; }

        .btn { display: inline-block; padding: 10px 20px; border: 1px solid #58a6ff; color: #58a6ff; border-radius: 6px; text-decoration: none; font-weight: 600; margin-top: 10px; }
        .btn:hover { background: #58a6ff; color: #fff; }

        footer { text-align: center; padding: 40px; border-top: 1px solid #30363d; color: #8b949e; font-size: 0.9rem; }
    </style>
</head>
<body>

<div class="hero">
    <h1>Sameer Appasa</h1>
    <p>Second Year Electrical Engineering | RMIT University</p>
</div>

<div class="container">
    <h2>🛠 Technical Toolkit</h2>
    <div class="skills-grid">
        <div class="skill-card"><h3>Embedded Systems</h3>ESP32, Arduino, OUSB Hardware</div>
        <div class="skill-card"><h3>Software</h3>C++, Python, Java, HTML</div>
        <div class="skill-card"><h3>Design</h3>Multisim Live, VS Code, Git</div>
    </div>

    <h2>🚀 Engineering Projects</h2>

    <div class="project-card">
        <div class="project-content">
            <span class="tag">Robotics</span>
            <h3>Autonomous Surface Rover</h3>
            <p>Custom mechanical drive-train design with real-time obstacle avoidance logic and manual-override mode.</p>
            <a href="rover.md" class="btn">View Case Study</a>
        </div>
    </div>

    <div class="project-card">
        <div class="project-content">
            <span class="tag">IoT & Security</span>
            <h3>Room Security Monitor</h3>
            <p>ESP32-based intrusion detection system utilizing Telegram Bot API for real-time mobile alerts and uptime monitoring.</p>
            <a href="#" class="btn">Documentation Coming Soon</a>
        </div>
    </div>

    <div class="project-card">
        <div class="project-content">
            <span class="tag">Low-Level C++</span>
            <h3>OUSB Process Control</h3>
            <p>Register-level hardware interaction featuring a strict priority error-precedence hierarchy (P, X, R, V, H, Y).</p>
            <a href="ousb.md" class="btn">Technical Brief</a>
        </div>
    </div>

    <h2>⚡ Simulation & Design</h2>
    <div class="project-card">
        <div class="project-content">
            <span class="tag">Multisim Live</span>
            <h3>Circuit Prototyping</h3>
            <p>Verification of analog signal integrity and power distribution before physical PCB fabrication.</p>
            <a href="#" class="btn">Open Lab Designs</a>
        </div>
    </div>
</div>

<footer>
    <p>&copy; 2024 Sameer Appasa | Built with HTML/CSS on GitHub Pages</p>
    <p>Contact: <a href="mailto:s2335678@student.rmit.edu.au" style="color:#58a6ff">Email Me</a></p>
</footer>

</body>
</html>
