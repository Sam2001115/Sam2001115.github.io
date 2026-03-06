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
        /* This hides the GitHub automatic header and project name */
        header, .site-header, #forkongithub, .project-name, .project-tagline { 
            display: none !important; 
        }

        body { 
            font-family: 'Inter', -apple-system, sans-serif; 
            background-color: #0d1117; 
            color: #c9d1d9; 
            margin: 0; 
            padding: 0;
        }

        .hero { 
            padding: 100px 20px 60px; 
            text-align: center; 
            background: radial-gradient(circle at center, #1f6feb22 0%, #0d1117 100%); 
        }

        .hero h1 { font-size: 3.5rem; color: #fff; margin: 0; letter-spacing: -2px; }
        .hero p { font-size: 1.2rem; color: #8b949e; margin-top: 10px; }

        .container { max-width: 850px; margin: 0 auto; padding: 40px 20px; }
        
        h2 { border-bottom: 1px solid #30363d; padding-bottom: 10px; color: #58a6ff; }

        .skills-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 15px; margin-bottom: 40px; }
        .skill-card { background: #161b22; padding: 15px; border-radius: 8px; border: 1px solid #30363d; }
        .skill-card h3 { margin-top: 0; font-size: 1rem; color: #f0f6fc; }

        .project-card { 
            background: #161b22; margin-bottom: 25px; border-radius: 12px; 
            border: 1px solid #30363d; transition: 0.3s; 
        }
        .project-card:hover { border-color: #58a6ff; background: #1c2128; }
        .project-content { padding: 25px; }

        .btn { 
            display: inline-block; padding: 10px 20px; border: 1px solid #58a6ff; 
            color: #58a6ff; border-radius: 6px; text-decoration: none; font-weight: 600; 
        }
        .btn:hover { background: #58a6ff; color: #fff; }
    </style>
</head>
<body>

<div class="hero">
    <h1>Sameer Appasa</h1>
    <p>Electrical Engineering | Embedded Systems & IoT</p>
</div>

<div class="container">
    <h2>🛠 Technical Toolkit</h2>
    <div class="skills-grid">
        <div class="skill-card"><h3>Embedded</h3>ESP32, Arduino, OUSB Hardware [cite: 1]</div>
        <div class="skill-card"><h3>Languages</h3>C++, Python, Java, HTML</div>
        <div class="skill-card"><h3>Simulation</h3>Multisim Live, VS Code, Git</div>
    </div>

    <h2>🚀 Featured Projects</h2>

    <div class="project-card">
        <div class="project-content">
            <h3>Autonomous Surface Rover</h3>
            <p>Custom mechanical drive-train design with real-time obstacle avoidance logic.</p>
            <a href="rover.md" class="btn">View Case Study</a>
        </div>
    </div>

    <div class="project-card">
        <div class="project-content">
            <h3>OUSB Process Control</h3>
            <p>Register-level C++ programming with advanced error-precedence protocols including P, X, R, V, H, and Y codes[cite: 1].</p>
            <a href="ousb.md" class="btn">Technical Brief</a>
        </div>
    </div>
</div>

</body>
</html>
