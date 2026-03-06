---
layout: null
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <style>
        /* This hides every possible GitHub and browser element at the top */
        header, .site-header, .project-name, .project-tagline { 
            display: none !important; 
            height: 0; 
            margin: 0; 
            padding: 0; 
        }

        body { 
            font-family: 'Inter', sans-serif; 
            background-color: #0d1117; 
            color: #c9d1d9; 
            margin: 0; 
        }

        /* Adds space so your name isn't touching the very top of the screen */
        .hero { 
            padding: 100px 20px 60px; 
            text-align: center; 
            background: radial-gradient(circle at center, #1f6feb22 0%, #0d1117 100%); 
        }

        .hero h1 { font-size: 3.5rem; color: #fff; margin: 0; }
        .container { max-width: 850px; margin: 0 auto; padding: 40px 20px; }
        .project-card { background: #161b22; margin-bottom: 25px; border-radius: 12px; border: 1px solid #30363d; padding: 25px; }
        .btn { display: inline-block; padding: 10px 20px; border: 1px solid #58a6ff; color: #58a6ff; border-radius: 6px; text-decoration: none; }
    </style>
</head>
<body>

<div class="hero">
    <h1>Sameer Appasa</h1>
    <p>Electrical Engineering | RMIT University</p>
</div>

<div class="container">
    <h2>🚀 Engineering Projects</h2>

    <div class="project-card">
        <h3>Autonomous Surface Rover</h3>
        <p>Custom mechanical drive-train design with real-time obstacle avoidance.</p>
        <a href="rover.md" class="btn">View Project</a>
    </div>

    <div class="project-card">
        <h3>OUSB Process Control</h3>
        <p>Register-level C++ interaction for hardware logic and error handling[cite: 1].</p>
        <a href="ousb.md" class="btn">Technical Brief</a>
    </div>
</div>

</body>
</html>
