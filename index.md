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
        :root { --v-green: #00FF41; --v-black: #020202; --v-glow: rgba(0, 255, 65, 0.3); }
        
        body, html { 
            background-color: var(--v-black); 
            color: #fff; 
            font-family: 'JetBrains Mono', monospace;
            margin: 0; padding: 0; overflow-x: hidden;
        }

        /* GRID BACKGROUND */
        .terminal-container {
            width: 100%; min-height: 100vh;
            display: flex; flex-direction: column; align-items: center;
            background-image: 
              linear-gradient(rgba(0, 255, 65, 0.03) 1px, transparent 1px),
              linear-gradient(90deg, rgba(0, 255, 65, 0.03) 1px, transparent 1px);
            background-size: 40px 40px;
            padding-top: 20px;
        }

        /* HEADER NAV (REPLACING THE DROPDOWN) */
        .nav-header {
            width: 90%; max-width: 1200px;
            display: flex; justify-content: space-between; align-items: center;
            border-bottom: 1px solid var(--v-glow);
            padding: 15px 0; margin-bottom: 30px;
        }

        .logo { font-family: 'Orbitron'; color: var(--v-green); font-weight: 900; letter-spacing: 2px; }

        .nav-links { display: flex; gap: 20px; }
        .nav-links a { 
            color: #888; text-decoration: none; font-size: 0.7rem; 
            text-transform: uppercase; letter-spacing: 1px; transition: 0.3s;
        }
        .nav-links a:hover { color: var(--v-green); text-shadow: 0 0 10px var(--v-green); }

        /* THE MAIN IMAGE HERO */
        .hero-frame {
            position: relative; width: 90%; max-width: 1100px;
            border: 1px solid var(--v-glow); padding: 10px;
            background: rgba(0,0,0,0.5); margin-bottom: 40px;
        }

        .hero-image { width: 100%; display: block; filter: brightness(0.9); }

        /* TACTICAL BUTTONS */
        .btn-dispatch {
            background-color: var(--v-green); color: #000;
            padding: 18px 50px; text-decoration: none;
            font-family: 'Orbitron'; font-weight: 900;
            display: inline-block; clip-path: polygon(10% 0, 100% 0, 90% 100%, 0% 100%);
            font-size: 1.1rem; transition: 0.3s; border: none; cursor: pointer;
        }
        .btn-dispatch:hover { transform: scale(1.05); box-shadow: 0 0 30px var(--v-green); }

        .status-footer {
            margin-top: auto; padding: 40px; text-align: center;
            width: 100%; border-top: 1px solid #111;
        }

        /* MOBILE FIX */
        @media (max-width: 768px) {
            .nav-links { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
            .nav-header { flex-direction: column; gap: 20px; }
        }
    </style>
</head>
<body>

<div class="terminal-container">
    
    <nav class="nav-header">
        <div class="logo">VALHALLA'S 13TH</div>
        <div class="nav-links">
            <a href="/architecture/">Architecture</a>
            <a href="/pilot/">Pilot</a>
            <a href="/vision/">Vision</a>
            <a href="/complexity/">Doctrine</a>
            <a href="/about/">About</a>
        </div>
    </nav>

    <div class="hero-frame">
        <img src="/web_site2.png" alt="Command Interface" class="hero-image">
    </div>

    <div style="text-align: center;">
        <p style="font-family: 'Orbitron'; font-size: 0.6rem; color: var(--v-green); letter-spacing: 4px; margin-bottom: 20px;">
            // SYSTEM ACTIVE: CAGE 188U9 //
        </p>
        <a href="mailto:sales@valhallainnovations.com?subject=Secure Dispatch: Priority Inquiry" class="btn-dispatch">
            INITIATE SECURE DISPATCH
        </a>
    </div>

    <footer class="status-footer">
        <p style="font-size: 0.55rem; color: #333; letter-spacing: 3px;">
            ENTITY: VALHALLA'S THIRTEEN LLC // JACKSONVILLE DEFENSE ENCLAVE
        </p>
    </footer>

</div>

</body>
</html>
