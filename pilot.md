---
layout: null
permalink: /pilot/
---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pilot Program | Valhalla 13th</title>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;900&family=JetBrains+Mono:wght@400;700&display=swap" rel="stylesheet">
    <style>
        :root { --v-green: #00FF41; --v-black: #020202; }
        body { background: var(--v-black); color: #fff; font-family: 'JetBrains Mono', monospace; margin: 0; display: flex; flex-direction: column; align-items: center; min-height: 100vh; background-image: linear-gradient(rgba(0, 255, 65, 0.05) 1px, transparent 1px), linear-gradient(90deg, rgba(0, 255, 65, 0.05) 1px, transparent 1px); background-size: 50px 50px; }
        .nav { padding: 20px; border-bottom: 1px solid rgba(0, 255, 65, 0.2); width: 100%; text-align: center; background: rgba(0,0,0,0.9); }
        .nav a { color: var(--v-green); text-decoration: none; margin: 0 15px; font-size: 0.7rem; text-transform: uppercase; letter-spacing: 2px; }
        .content { max-width: 800px; padding: 40px; margin-top: 40px; border: 1px solid rgba(0, 255, 65, 0.2); background: rgba(0,0,0,0.8); }
        h1 { font-family: 'Orbitron'; color: var(--v-green); letter-spacing: 5px; text-transform: uppercase; }
        .seal { float: right; width: 100px; margin: 0 0 20px 20px; border: 1px solid var(--v-green); box-shadow: 0 0 10px var(--v-green); }
        .grid { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-top: 30px; }
        .card { border: 1px solid rgba(0, 255, 65, 0.1); padding: 15px; background: #050505; }
        h3 { color: var(--v-green); font-family: 'Orbitron'; font-size: 0.8rem; }
        .btn { background: var(--v-green); color: #000; padding: 12px 30px; text-decoration: none; font-weight: 900; font-family: 'Orbitron'; display: inline-block; clip-path: polygon(10% 0, 100% 0, 90% 100%, 0% 100%); margin-top: 20px; }
    </style>
</head>
<body>
    <nav class="nav">
        <a href="/">[ HOME ]</a>
        <a href="/architecture/">[ ARCHITECTURE ]</a>
        <a href="/pilot/">[ PILOT ]</a>
        <a href="/vision/">[ VISION ]</a>
        <a href="/about/">[ ABOUT ]</a>
    </nav>
    <div class="content">
        <img src="/web_site3.png" class="seal">
        <p style="color: var(--v-green); font-size: 0.6rem;">// ENROLLMENT: ACTIVE // SLOTS: 03 //</p>
        <h1>Municipal Pilot</h1>
        <p>Seeking three government partners for field validation of the THORVEIL hardware-enforced isolation layer.</p>
        <div class="grid">
            <div class="card">
                <h3>ASSETS</h3>
                <ul style="font-size: 0.8rem; color: #888;">
                    <li>High-Assurance Node</li>
                    <li>Ghost-Layer OS</li>
                    <li>Zero-Persistence Audit</li>
                </ul>
            </div>
            <div class="card">
                <h3>COMMITMENT</h3>
                <ul style="font-size: 0.8rem; color: #888;">
                    <li>Allocation: $2,450</li>
                    <li>SCADA Interop Feedback</li>
                    <li>Case Study Access</li>
                </ul>
            </div>
        </div>
        <div style="text-align: center;">
            <a href="mailto:sales@valhallainnovations.com?subject=Pilot Program Application" class="btn">APPLY FOR SLOT</a>
        </div>
    </div>
</body>
</html>
