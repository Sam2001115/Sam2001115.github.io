---
layout: null
title: Sameer Appasa | EE Portfolio
---

<head>
    <meta charset="UTF-8">
    <title>Sameer Appasa | Engineering Portfolio</title>
    <style>
        /* This section kills all default GitHub text and headers */
        header, .site-header, .project-name, .project-tagline { 
            display: none !important; 
            visibility: hidden !important;
            height: 0px !important;
            margin: 0px !important;
            padding: 0px !important;
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
        h2 { border-bottom: 1px solid #30363d; padding-bottom: 10px; color: #58a6ff; margin-top: 40px; }

        .project-card { 
            background: #161b22; 
            margin-bottom: 25px; 
            border-radius: 12px; 
            border: 1px solid #30363d; 
            transition: 0.3s; 
        }
        .project-card:hover { border-color: #58a6ff; background: #1c2128; }
        .project-content { padding: 25px; }

        .btn { 
            display: inline-block; 
            padding: 10px 20px; 
            border: 1px solid #58a6ff; 
            color: #58a6ff; 
            border-radius: 6px; 
            text-decoration: none; 
            font-weight: 600; 
            margin-top: 15px;
        }
    </style>
</head>

<div class="hero">
    <h1>Sameer Appasa</h1>
    <p>Electrical Engineering | Embedded Systems & IoT</p>
</div>

<div class="container">
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
            <h3>OUSB Process Control System</h3>
            <p>Developed a C++ command-line tool for register-level hardware interaction and decision logic[cite: 1]. I implemented a robust error-handling hierarchy (P, X, R, V, H, Y) to validate hardware inputs and communication integrity[cite: 1].</p>
            <a href="ousb.md" class="btn">Technical Brief</a>
        </div>
    </div>
</div>
