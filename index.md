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
        body { 
            background: var(--v-black); 
            color: #fff; 
            font-family: 'JetBrains Mono', monospace; 
            margin: 0; 
            display: flex; 
            flex-direction: column; 
            align-items: center; 
            min-height: 100vh;
            background-image: linear-gradient(rgba(0, 255, 65, 0.05) 1px, transparent 1px), linear-gradient(90deg, rgba(0, 255, 65, 0.05) 1px, transparent 1px);
            background-size: 50px 50px;
        }
        .terminal { 
            padding: 40px; 
            border: 1px solid var(--v-green); 
            margin: 40px auto; 
            max-width: 90%;
            text-align: center;
            background: rgba(0,0,0,0.8);
            box-shadow: 0 0 20px rgba(0, 255, 65, 0.2);
        }
        h1 { font-family: 'Orbitron'; color: var(--v-green); letter-spacing: 8px; text-transform: uppercase; }
        .hero-img { max-width: 100%; border: 1px solid #333; margin: 20px 0; }
        .btn { 
            background: var(--v-green); 
            color: #000; 
            padding: 15px 40px; 
            text-decoration: none; 
            font-weight: 900; 
            font-family: 'Orbitron'; 
            display: inline-block; 
            clip-path: polygon(10% 0, 100% 0, 90% 100%, 0% 100%);
            letter-spacing: 2px;
        }
        .nav { margin-top: 20px; }
        .nav a { color: var(--v-green); text-decoration: none; margin: 0 15px; font-size: 0.8rem; text-transform: uppercase; }
    </style>
</head>
<body>
    <div class="terminal">
        <p style="color: var(--v-green); font-size: 0.7rem; letter-spacing: 3px;">[ MISSION PROFILE: DISCONNECTED // CAGE 188U9 ]</p>
        <h1>VALHALLA'S 13TH</h1>
        
        <nav class="nav">
            <a href="/architecture/">Architecture</a>
            <a href="/pilot/">Pilot</a>
            <a href="/vision/">Vision</a>
            <a href="/about/">About</a>
        </nav>

        <img src="/web_site2.png" class="hero-img" alt="Command Hub">
        
        <br>
        <a href="mailto:sales@valhallainnovations.com?subject=Strategic Briefing Request - CAGE 188U9" class="btn">ACCESS STRATEGIC BRIEF</a>
    </div>
    
    <p style="color: #222; font-size: 0.6rem; letter-spacing: 2px;">ENTITY: VALHALLA'S THIRTEEN LLC // JAX-ENCLAVE-01</p>
</body>
</html>
