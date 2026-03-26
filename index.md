---
layout: null
---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Valhalla's 13th Innovations Unit</title>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;900&family=JetBrains+Mono:wght@400;700&display=swap" rel="stylesheet">
    <style>
        :root { --v-green: #00FF41; --v-black: #020202; }
        
        body, html { 
            background-color: var(--v-black); 
            color: #fff; 
            font-family: 'JetBrains Mono', monospace;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }

        /* TACTICAL OVERLAY */
        .terminal-container {
            width: 100%;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            background-image: 
              linear-gradient(rgba(0, 255, 65, 0.05) 1px, transparent 1px),
              linear-gradient(90deg, rgba(0, 255, 65, 0.05) 1px, transparent 1px);
            background-size: 50px 50px;
        }

        .hero-image {
            width: 90%;
            max-width: 1200px;
            border: 1px solid var(--v-green);
            box-shadow: 0 0 30px rgba(0, 255, 65, 0.2);
            margin-bottom: 40px;
        }

        .nav-hub {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            width: 90%;
            max-width: 1200px;
            margin-bottom: 50px;
        }

        .nav-btn {
            border: 1px solid rgba(0, 255, 65, 0.3);
            padding: 15px;
            text-align: center;
            text-decoration: none;
            color: var(--v-green);
            font-family: 'Orbitron';
            font-size: 0.8rem;
            text-transform: uppercase;
            letter-spacing: 2px;
            transition: 0.3s;
            background: rgba(0, 255, 65, 0.05);
        }

        .nav-btn:hover {
            background: var(--v-green);
            color: #000;
            box-shadow: 0 0 20px var(--v-green);
        }

        .dispatch-area {
            text-align: center;
            padding: 40px;
            border-top: 1px solid #111;
            width: 100%;
        }

        .btn-dispatch {
            background-color: var(--v-green);
            color: #000;
            padding: 20px 60px;
            text-decoration: none;
            font-family: 'Orbitron';
            font-weight: 900;
            display: inline-block;
            clip-path: polygon(10% 0, 100% 0, 90% 100%, 0% 100%);
            font-size: 1.2rem;
        }
    </style>
</head>
<body>

<div class="terminal-container">
    
    <img src="/web_site2.png" alt="Valhalla 13th Command Hub" class="hero-image">

    <div class="nav-hub">
        <a href="/architecture/" class="nav-btn">Architecture</a>
        <a href="/pilot/" class="nav-btn">Pilot Program</a>
        <a href="/vision/" class="nav-btn">Vision</a>
        <a href="/complexity/" class="nav-btn">Doctrine</a>
        <a href="/about/" class="nav-btn">About Unit</a>
    </div>

    <div class="dispatch-area">
        <p style="font-size: 0.6rem; color: #444; letter-spacing: 5px; margin-bottom: 20px;">
            // AUTHORITY: VALHALLA'S THIRTEEN LLC // CAGE: 188U9 //
        </p>
        <a href="mailto:sales@valhallainnovations.com?subject=Secure Dispatch: Priority Inquiry" class="btn-dispatch">
            INITIATE SECURE DISPATCH
        </a>
    </div>

</div>

</body>
</html>
