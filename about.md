---
layout: null
---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Unit | Valhalla 13th</title>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;900&family=JetBrains+Mono:wght@400;700&display=swap" rel="stylesheet">
    <style>
        :root { --v-green: #00FF41; --v-black: #020202; --v-glow: rgba(0, 255, 65, 0.2); }
        
        body, html { 
            background-color: var(--v-black); 
            color: #fff; 
            font-family: 'JetBrains Mono', monospace;
            margin: 0; padding: 0; overflow-x: hidden;
        }

        .terminal-container {
            width: 100%; min-height: 100vh;
            display: flex; flex-direction: column; align-items: center;
            background-image: linear-gradient(rgba(0, 255, 65, 0.03) 1px, transparent 1px), linear-gradient(90deg, rgba(0, 255, 65, 0.03) 1px, transparent 1px);
            background-size: 40px 40px;
        }

        /* HEADER HUD */
        .nav-header {
            width: 90%; max-width: 1200px;
            display: flex; justify-content: space-between; align-items: center;
            border-bottom: 1px solid var(--v-glow);
            padding: 15px 0; margin-bottom: 50px;
        }

        .logo { font-family: 'Orbitron'; color: var(--v-green); font-weight: 900; letter-spacing: 2px; text-decoration: none; }
        .nav-links { display: flex; gap: 20px; }
        .nav-links a { color: #888; text-decoration: none; font-size: 0.7rem; text-transform: uppercase; letter-spacing: 1px; transition: 0.3s; }
        .nav-links a:hover { color: var(--v-green); text-shadow: 0 0 10px var(--v-green); }

        .content-body { width: 90%; max-width: 800px; margin-bottom: 100px; }

        .tactical-card {
            border: 1px solid var(--v-glow);
            padding: 30px;
            background: rgba(0, 0, 0, 0.6);
            margin-bottom: 20px;
        }

        h1, h2, h3 { font-family: 'Orbitron'; color: var(--v-green); text-transform: uppercase; letter-spacing: 3px; }
        
        .registry-table { width: 100%; border-collapse: collapse; margin-top: 20px; }
        .registry-table td { padding: 12px; border: 1px solid var(--v-glow); font-size: 0.8rem; }
        .label { color: #555; text-transform: uppercase; font-weight: bold; width: 40%; }
        .value { color: var(--v-green); }

        .btn-dispatch {
            color: var(--v-green); text-decoration: none; font-size: 0.7rem;
            border: 1px solid var(--v-green); padding: 10px 20px;
            display: inline-block; transition: 0.3s;
        }
        .btn-dispatch:hover { background: var(--v-green); color: #000; }

        footer { padding: 40px; text-align: center; border-top: 1px solid #111; width: 100%; margin-top: auto; }
    </style>
</head>
<body>

<div class="terminal-container">
    
    <nav class="nav-header">
        <a href="/" class="logo">VALHALLA'S 13TH</a>
        <div class="nav-links">
            <a href="/architecture/">Architecture</a>
            <a href="/pilot/">Pilot</a>
            <a href="/vision/">Vision</a>
            <a href="/complexity/">Doctrine</a>
            <a href="/about/">About</a>
        </div>
    </nav>

    <div class="content-body">
        
        <div class="tactical-card" style="border-left: 4px solid var(--v-green);">
            <p style="font-size: 0.6rem; color: var(--v-green); letter-spacing: 3px; margin: 0;">UNIT STATUS: OPERATIONAL // CAGE: 188U9</p>
            <h1>13th Innovations Unit</h1>
            <p style="color: #888; font-size: 0.85rem;">Advanced Defense Research & Development. A specialized division of Valhalla's Thirteen LLC focused on hardware-enforced systemic exclusion.</p>
        </div>

        <div class="tactical-card">
            <h3>Corporate Registry</h3>
            <table class="registry-table">
                <tr><td class="label">Legal Entity</td><td class="value">Valhalla's Thirteen LLC</td></tr>
                <tr><td class="label">CAGE Code</td><td class="value">188U9</td></tr>
                <tr><td class="label">UEI</td><td class="value">ZQSVTGA3E563</td></tr>
                <tr><td class="label">Primary Hub</td><td class="value">Jacksonville, FL</td></tr>
            </table>
        </div>

        <div class="tactical-card">
            <h3>Principal Architect</h3>
            <p style="color: #fff; margin-bottom: 20px;"><strong>Thor Whittaker</strong><br><span style="color: #666; font-size: 0.7rem;">Founder & Ghost-Layer Architect</span></p>
            <div style="display: flex; gap: 15px;">
                <a href="mailto:sales@valhallainnovations.com" class="btn-dispatch">SECURE DISPATCH</a>
                <a href="https://github.com/odinsgarden" class="btn-dispatch">GITHUB</a>
                <a href="https://www.linkedin.com/in/thor-ustin-whittaker-b96788252" class="btn-dispatch">LINKEDIN</a>
            </div>
        </div>

    </div>

    <footer>
        <p style="font-size: 0.55rem; color: #333; letter-spacing: 3px;">
            ENTITY: VALHALLA'S THIRTEEN LLC // JAX-ENCLAVE-01
        </p>
    </footer>

</div>

</body>
</html>
