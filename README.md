<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>🧠💀 BRAINROT MLG ZONE ULTRA EXTREME STROBOSCOPE 💀🧠</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Comic+Neue:wght@700&display=swap');

    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Comic Neue', cursive;
      background: conic-gradient(from 0deg,#ff00ff,#00ff00,#00ffff,#ffff00,#ff0000,#0000ff,#ff00ff);
      background-size: 400% 400%;
      animation: 
        bgSpin 3s linear infinite, 
        screenShake 0.05s infinite,
        strobeFlash 0.1s infinite,
        colorPulse 0.3s infinite;
      overflow-x: hidden;
      min-height: 100vh;
      color: white;
      cursor: none;
      position: relative;
    }
    
    @keyframes bgSpin { 0%{filter:hue-rotate(0deg) saturate(3)}100%{filter:hue-rotate(360deg) saturate(3)} }
    @keyframes screenShake { 
      0%{transform:translate(0)} 
      10%{transform:translate(-5px,3px) rotate(1deg)} 
      20%{transform:translate(4px,-4px) rotate(-1deg)} 
      30%{transform:translate(-3px,-3px) rotate(0.5deg)} 
      40%{transform:translate(5px,2px) rotate(-0.5deg)}
      50%{transform:translate(-2px,-5px) rotate(1deg)}
      60%{transform:translate(3px,4px) rotate(-1deg)}
      70%{transform:translate(-5px,-2px) rotate(0.5deg)}
      80%{transform:translate(2px,5px) rotate(-0.5deg)}
      90%{transform:translate(5px,-3px) rotate(1deg)}
      100%{transform:translate(-3px,2px) rotate(-1deg)} 
    }

    /* EFFETS STROBOSCOPIQUES ULTRA */
    @keyframes strobeFlash {
      0%{background-color: transparent}
      5%{background-color: rgba(255,255,255,0.8)}
      10%{background-color: transparent}
      15%{background-color: rgba(255,0,0,0.6)}
      20%{background-color: transparent}
      25%{background-color: rgba(0,255,0,0.6)}
      30%{background-color: transparent}
      35%{background-color: rgba(0,0,255,0.6)}
      40%{background-color: transparent}
      45%{background-color: rgba(255,255,0,0.8)}
      50%{background-color: transparent}
      55%{background-color: rgba(255,0,255,0.8)}
      60%{background-color: transparent}
      65%{background-color: rgba(0,255,255,0.8)}
      70%{background-color: transparent}
      75%{background-color: rgba(255,255,255,1)}
      80%{background-color: transparent}
      85%{background-color: rgba(255,128,0,0.9)}
      90%{background-color: transparent}
      95%{background-color: rgba(128,0,255,0.9)}
      100%{background-color: transparent}
    }

    @keyframes colorPulse {
      0%{filter: hue-rotate(0deg) brightness(1) contrast(1)}
      25%{filter: hue-rotate(90deg) brightness(2) contrast(3)}
      50%{filter: hue-rotate(180deg) brightness(0.5) contrast(5)}
      75%{filter: hue-rotate(270deg) brightness(3) contrast(2)}
      100%{filter: hue-rotate(360deg) brightness(1) contrast(1)}
    }

    /* STROBOSCOPE OVERLAY */
    body::before {
      content: '';
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      z-index: 5000;
      animation: ultraStrobe 0.05s infinite;
    }

    @keyframes ultraStrobe {
      0%{background: transparent}
      2%{background: rgba(255,255,255,1)}
      4%{background: transparent}
      6%{background: rgba(255,0,0,0.8)}
      8%{background: transparent}
      10%{background: rgba(0,255,0,0.8)}
      12%{background: transparent}
      14%{background: rgba(0,0,255,0.8)}
      16%{background: transparent}
      18%{background: rgba(255,255,0,1)}
      20%{background: transparent}
      22%{background: rgba(255,0,255,1)}
      24%{background: transparent}
      26%{background: rgba(0,255,255,1)}
      28%{background: transparent}
      30%{background: rgba(255,255,255,0.9)}
      35%{background: transparent}
      40%{background: rgba(255,128,0,0.7)}
      45%{background: transparent}
      50%{background: rgba(128,255,0,0.7)}
      55%{background: transparent}
      60%{background: rgba(255,0,128,0.7)}
      65%{background: transparent}
      70%{background: rgba(0,128,255,0.7)}
      75%{background: transparent}
      80%{background: rgba(128,0,255,0.7)}
      85%{background: transparent}
      90%{background: rgba(255,255,255,1)}
      95%{background: transparent}
      100%{background: rgba(0,0,0,0.8)}
    }

    /* EXPLOSIONS MASSIVES */
    .mega-explosion {
      position: fixed;
      width: 400px;
      height: 400px;
      border-radius: 50%;
      background: radial-gradient(circle, 
        #ffffff 0%, 
        #ffff00 20%, 
        #ff8800 40%, 
        #ff0000 60%, 
        #ff00ff 80%, 
        transparent 100%);
      pointer-events: none;
      animation: megaExplode 0.8s ease-out forwards;
      z-index: 4000;
      box-shadow: 
        0 0 100px #ffff00,
        0 0 200px #ff0000,
        0 0 300px #ff00ff;
    }

    @keyframes megaExplode {
      0% { 
        transform: scale(0) rotate(0deg); 
        opacity: 1; 
        filter: brightness(10) saturate(5);
      }
      30% { 
        transform: scale(1.5) rotate(180deg); 
        opacity: 1;
        filter: brightness(8) saturate(4);
      }
      70% { 
        transform: scale(3) rotate(360deg); 
        opacity: 0.7;
        filter: brightness(5) saturate(3);
      }
      100% { 
        transform: scale(5) rotate(720deg); 
        opacity: 0;
        filter: brightness(2) saturate(1);
      }
    }

    /* CHAIN EXPLOSIONS */
    .chain-explosion {
      position: fixed;
      width: 200px;
      height: 200px;
      border-radius: 50%;
      background: radial-gradient(circle, #ffff00, #ff0000, #ff00ff, transparent);
      pointer-events: none;
      animation: chainExplode 0.4s ease-out forwards;
      z-index: 3000;
    }

    @keyframes chainExplode {
      0% { transform: scale(0); opacity: 1; }
      50% { transform: scale(2) rotate(180deg); opacity: 0.8; }
      100% { transform: scale(4) rotate(360deg); opacity: 0; }
    }

    /* FLASH BANGS */
    .flashbang {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: white;
      pointer-events: none;
      animation: flashbangEffect 0.3s ease-out forwards;
      z-index: 6000;
    }

    @keyframes flashbangEffect {
      0% { opacity: 0; }
      10% { opacity: 1; filter: brightness(100); }
      100% { opacity: 0; filter: brightness(1); }
    }

    /* PARTICLE EXPLOSIONS */
    .particle-burst {
      position: fixed;
      width: 10px;
      height: 10px;
      background: #ffff00;
      border-radius: 50%;
      pointer-events: none;
      animation: particleBurst 1s ease-out forwards;
      z-index: 2000;
      box-shadow: 0 0 20px currentColor;
    }

    @keyframes particleBurst {
      0% { 
        opacity: 1; 
        transform: scale(1) rotate(0deg);
        filter: brightness(5);
      }
      100% { 
        opacity: 0; 
        transform: scale(0) rotate(720deg) translate(var(--dx), var(--dy));
        filter: brightness(1);
      }
    }

    /* SCREEN DISTORTION */
    .screen-distort {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      z-index: 1000;
      animation: distortWave 0.5s ease-out forwards;
      background: 
        radial-gradient(circle at 20% 20%, rgba(255,0,0,0.3) 0%, transparent 50%),
        radial-gradient(circle at 80% 80%, rgba(0,255,0,0.3) 0%, transparent 50%),
        radial-gradient(circle at 50% 50%, rgba(0,0,255,0.3) 0%, transparent 50%);
    }

    @keyframes distortWave {
      0% { 
        transform: scale(1) skew(0deg); 
        filter: blur(0px); 
      }
      25% { 
        transform: scale(1.1) skew(5deg); 
        filter: blur(2px); 
      }
      50% { 
        transform: scale(0.9) skew(-5deg); 
        filter: blur(4px); 
      }
      75% { 
        transform: scale(1.05) skew(3deg); 
        filter: blur(2px); 
      }
      100% { 
        transform: scale(1) skew(0deg); 
        filter: blur(0px); 
      }
    }

    /* RAGE MODE EFFECTS */
    .rage-mode {
      animation: 
        rageShake 0.02s infinite,
        rageColors 0.05s infinite,
        rageScale 0.1s infinite !important;
    }

    @keyframes rageShake {
      0%{transform:translate(-10px,8px) rotate(-3deg)}
      25%{transform:translate(8px,-10px) rotate(3deg)}
      50%{transform:translate(-8px,-8px) rotate(-2deg)}
      75%{transform:translate(10px,10px) rotate(2deg)}
      100%{transform:translate(-8px,8px) rotate(-3deg)}
    }

    @keyframes rageColors {
      0%{filter:hue-rotate(0deg) saturate(10) brightness(5)}
      20%{filter:hue-rotate(72deg) saturate(8) brightness(3)}
      40%{filter:hue-rotate(144deg) saturate(12) brightness(7)}
      60%{filter:hue-rotate(216deg) saturate(6) brightness(2)}
      80%{filter:hue-rotate(288deg) saturate(15) brightness(8)}
      100%{filter:hue-rotate(360deg) saturate(10) brightness(5)}
    }

    @keyframes rageScale {
      0%{transform:scale(1)}
      50%{transform:scale(1.2)}
      100%{transform:scale(1)}
    }

    /* INTERFACE STYLES - Ultra enhanced */
    .navbar { 
      display:flex; justify-content:center; gap:20px; margin:20px; 
      flex-wrap:wrap; z-index:10; position:relative;
      animation: navbarStrobe 0.2s infinite;
    }
    @keyframes navbarStrobe {
      0%{box-shadow: 0 0 50px #ff00ff}
      50%{box-shadow: 0 0 100px #00ffff, 0 0 150px #ffff00}
      100%{box-shadow: 0 0 50px #ff00ff}
    }

    .navbar a {
      text-decoration:none; padding:15px 25px;
      background:linear-gradient(45deg, #000, #ff00ff, #000); 
      border-radius:25px; color:#fff;
      font-weight:bold; transition:0.1s; 
      text-shadow:0 0 10px #ff00ff, 0 0 20px #ffff00;
      animation: linkPulse 0.3s infinite;
      border: 2px solid #ffff00;
    }
    @keyframes linkPulse {
      0%{transform: scale(1); filter: brightness(1)}
      50%{transform: scale(1.1); filter: brightness(3) saturate(3)}
      100%{transform: scale(1); filter: brightness(1)}
    }

    .navbar a:hover { 
      background: linear-gradient(45deg, #ff00ff, #ffff00, #00ffff, #ff0000); 
      transform:scale(1.3) rotate(-10deg); 
      box-shadow: 0 0 50px #ff00ff, 0 0 100px #ffff00;
      animation: hoverExplosion 0.1s infinite;
    }
    @keyframes hoverExplosion {
      0%{filter: brightness(1)}
      25%{filter: brightness(5) saturate(5)}
      50%{filter: brightness(10) saturate(10)}
      75%{filter: brightness(5) saturate(5)}
      100%{filter: brightness(1)}
    }

    .main-title {
      text-align:center; font-size:clamp(3rem,8vw,6rem);
      text-shadow:
        0 0 10px #ff00ff,0 0 20px #00ff00,0 0 30px #ff0000,0 0 40px #ffff00,
        0 0 50px #00ffff,0 0 60px #ff00ff,0 0 70px #ffffff;
      margin:20px 0; 
      animation: 
        titleMegaPulse 0.2s infinite alternate,
        titleGlitch 0.05s infinite,
        titleRotate 2s linear infinite;
    }
    @keyframes titleMegaPulse { 
      from{transform:scale(1)} 
      to{transform:scale(1.3) rotate(5deg)} 
    }
    @keyframes titleGlitch { 
      0%{text-shadow:0 0 10px #ff00ff,0 0 20px #00ff00} 
      10%{text-shadow:5px 0 0 #ff00ff,-5px 0 0 #00ffff} 
      20%{text-shadow:0 5px 0 #ffff00,0 -5px 0 #ff0000}
      30%{text-shadow:-3px 3px 0 #00ff00,3px -3px 0 #ff00ff}
      40%{text-shadow:2px -2px 0 #00ffff,-2px 2px 0 #ffff00}
      50%{text-shadow:0 0 20px #ffffff,0 0 40px #ff00ff}
      60%{text-shadow:4px 0 0 #ff0000,-4px 0 0 #00ff00}
      70%{text-shadow:0 4px 0 #0000ff,0 -4px 0 #ffff00}
      80%{text-shadow:-2px -2px 0 #ff00ff,2px 2px 0 #00ffff}
      90%{text-shadow:3px -3px 0 #ffff00,-3px 3px 0 #ff0000}
      100%{text-shadow:0 0 10px #ff00ff,0 0 20px #00ff00}
    }
    @keyframes titleRotate {
      0%{transform: rotate(0deg)}
      25%{transform: rotate(5deg)}
      50%{transform: rotate(0deg)}
      75%{transform: rotate(-5deg)}
      100%{transform: rotate(0deg)}
    }

    .section { display:none; padding:20px; text-align:center; position:relative; z-index:1;}
    .active { display:block; }

    .meme-zone { 
      display:grid; 
      grid-template-columns:repeat(auto-fit,minmax(180px,1fr)); 
      gap:25px; margin:20px; 
    }
    .meme-card {
      background: linear-gradient(45deg, rgba(255,0,255,0.3), rgba(0,255,255,0.3)); 
      padding:20px; border-radius:20px;
      border:3px solid #ff00ff; font-size:24px; 
      transition:0.1s; cursor:pointer; 
      animation: 
        cardStrobe 0.2s infinite,
        cardFloat 1s ease-in-out infinite alternate;
      position: relative;
      overflow: hidden;
      box-shadow: 
        0 0 30px #ff00ff,
        inset 0 0 30px rgba(255,255,255,0.2);
    }

    @keyframes cardStrobe {
      0%{border-color:#ff00ff;box-shadow:0 0 30px #ff00ff}
      20%{border-color:#00ffff;box-shadow:0 0 40px #00ffff}
      40%{border-color:#ffff00;box-shadow:0 0 50px #ffff00}
      60%{border-color:#00ff00;box-shadow:0 0 40px #00ff00}
      80%{border-color:#ff0000;box-shadow:0 0 60px #ff0000}
      100%{border-color:#ff00ff;box-shadow:0 0 30px #ff00ff}
    }

    @keyframes cardFloat {
      from{transform: translateY(0px)}
      to{transform: translateY(-10px)}
    }

    .meme-card:hover { 
      transform:scale(1.5) rotateY(1080deg) rotateX(360deg); 
      animation: cardNuke 0.1s infinite;
      z-index: 1000;
    }

    @keyframes cardNuke {
      0%{filter: brightness(1) saturate(1) hue-rotate(0deg)}
      25%{filter: brightness(10) saturate(10) hue-rotate(90deg)}
      50%{filter: brightness(20) saturate(20) hue-rotate(180deg)}
      75%{filter: brightness(15) saturate(15) hue-rotate(270deg)}
      100%{filter: brightness(1) saturate(1) hue-rotate(360deg)}
    }

    .skibidi-button {
      background: linear-gradient(90deg,#ff00ff,#ffff00,#00ffff,#ff0000,#00ff00,#ff8800);
      border:none; padding:20px 40px; border-radius:30px;
      font-weight:bold; font-size:24px; margin:15px; cursor:pointer;
      animation: buttonMegaPulse 0.1s infinite alternate;
      transition: all 0.05s;
      box-shadow: 
        0 0 50px #ff00ff,
        0 0 100px #ffff00,
        inset 0 0 50px rgba(255,255,255,0.3);
      text-shadow: 0 0 20px #000;
    }

    @keyframes buttonMegaPulse { 
      from{transform:scale(1) rotate(0deg)} 
      to{transform:scale(1.2) rotate(3deg)} 
    }

    .skibidi-button:hover {
      transform: scale(1.5) rotate(10deg);
      animation: buttonNuke 0.05s infinite;
    }

    @keyframes buttonNuke {
      0%{filter: brightness(1) contrast(1)}
      25%{filter: brightness(5) contrast(3) saturate(10)}
      50%{filter: brightness(10) contrast(5) saturate(20)}
      75%{filter: brightness(7) contrast(4) saturate(15)}
      100%{filter: brightness(1) contrast(1)}
    }

    .rizz-counter { 
      font-size:36px; margin:25px; 
      text-shadow:0 0 20px #ff00ff,0 0 40px #ffff00, 0 0 60px #00ffff;
      animation: counterMegaGlow 0.1s infinite alternate;
      background: linear-gradient(45deg, transparent, rgba(255,0,255,0.3), transparent);
      padding: 15px;
      border-radius: 15px;
    }
    @keyframes counterMegaGlow {
      from{filter:drop-shadow(0 0 20px #ff00ff) brightness(1)}
      to{filter:drop-shadow(0 0 60px #00ffff) brightness(3)}
    }

    .ohio-meter { 
      width:90%; max-width:600px; margin:30px auto; 
      position:relative; height:50px;
      border-radius:25px; 
      background:linear-gradient(90deg,#00ff00,#ffff00,#ff8800,#ff0000); 
      overflow:hidden; 
      box-shadow:
        0 0 40px rgba(255,0,255,0.8),
        0 0 80px rgba(255,255,0,0.6),
        inset 0 0 40px rgba(255,255,255,0.3);
      animation: meterPulse 0.2s infinite;
    }
    @keyframes meterPulse {
      0%{transform: scale(1)}
      50%{transform: scale(1.05)}
      100%{transform: scale(1)}
    }

    .ohio-level { 
      position:absolute; left:0; top:0; height:100%; width:0%; 
      background:rgba(0,0,0,0.4);
      animation: fillMeterExtreme 3s ease-in-out infinite;
    }
    @keyframes fillMeterExtreme { 
      0%,100%{width:0%}
      25%{width:50%}
      50%{width:100%} 
      75%{width:75%}
    }

    .ohio-label { 
      position:absolute; width:100%; text-align:center; 
      line-height:50px; font-weight:bold; font-size: 18px;
      animation: labelStrobe 0.1s infinite;
    }
    @keyframes labelStrobe {
      0%{color:#fff; text-shadow: 0 0 10px #ff00ff}
      20%{color:#ffff00; text-shadow: 0 0 20px #ffff00}
      40%{color:#00ffff; text-shadow: 0 0 20px #00ffff}
      60%{color:#ff00ff; text-shadow: 0 0 20px #ff00ff}
      80%{color:#00ff00; text-shadow: 0 0 20px #00ff00}
      100%{color:#fff; text-shadow: 0 0 10px #ff00ff}
    }

    .sigma-grindset {
      margin:20px auto; padding:25px; border-radius:20px;
      background: 
        repeating-linear-gradient(45deg,#ff00ff,#ff00ff 5px,#00ff00 5px,#00ff00 10px),
        repeating-linear-gradient(-45deg,#ffff00,#ffff00 5px,#ff0000 5px,#ff0000 10px);
      color:white; 
      animation: spinMega 2s linear infinite;
      text-shadow: 0 0 20px #000;
      box-shadow: 0 0 60px #ff00ff;
      text-align: center;
      font-weight: bold;
    }
    @keyframes spinMega { 
      from{transform:rotate(0) scale(1)}
      25%{transform:rotate(90deg) scale(1.1)}
      50%{transform:rotate(180deg) scale(1)}
      75%{transform:rotate(270deg) scale(1.1)}
      to{transform:rotate(360deg) scale(1)} 
    }

    /* EMOJI RAIN EXTREME */
    .emoji-rain { 
      position: fixed; top:-50px; font-size:40px; 
      animation: fallExtreme linear forwards; 
      z-index: 200; pointer-events:none;
      filter: drop-shadow(0 0 20px currentColor);
      text-shadow: 0 0 30px #ffff00;
    }
    @keyframes fallExtreme { 
      to{
        transform:translateY(100vh) 
                  rotate(1440deg) 
                  scale(3) 
                  rotateX(720deg) 
                  rotateY(720deg)
                  skew(45deg);
      } 
    }

    .gyatt-button { 
      position:fixed; bottom:20px; right:20px; 
      width:100px; height:100px;
      border-radius:50%; border:5px solid #ffff00; font-size:50px; 
      cursor:pointer; 
      animation:megaBounce 0.2s infinite alternate; 
      background: 
        radial-gradient(circle, #ff0000, #ff00ff, #ffff00, #00ffff);
      box-shadow: 
        0 0 50px #ff00ff,
        0 0 100px #ffff00,
        inset 0 0 50px rgba(255,255,255,0.5);
      z-index: 1000;
    }
    @keyframes megaBounce { 
      from{transform:translateY(0) rotate(0deg) scale(1)} 
      to{transform:translateY(-30px) rotate(45deg) scale(1.3)} 
    }

    /* Curseur MLG Scope EXTREME */
    .cursor-scope { 
      position:fixed; width:120px; height:120px; border-radius:50%;
      border:4px solid #00ff00; pointer-events:none; 
      display:flex; align-items:center; justify-content:center;
      animation:scopeSpinExtreme 1s linear infinite;
      box-shadow: 
        0 0 30px #00ff00,
        0 0 60px #ffff00,
        inset 0 0 30px rgba(0,255,0,0.3);
      z-index: 5001;
    }
    .cursor-scope::before {
      content: '';
      position: absolute;
      width: 60px;
      height: 3px;
      background: #00ff00;
      box-shadow: 0 0 20px #00ff00;
    }
    .cursor-scope::after {
      content: '';
      position: absolute;
      width: 3px;
      height: 60px;
      background: #00ff00;
      box-shadow: 0 0 20px #00ff00;
    }
    @keyframes scopeSpinExtreme { 
      from{transform:rotate(0deg) scale(1)} 
      25%{transform:rotate(90deg) scale(1.2)}
      50%{transform:rotate(180deg) scale(1)}
      75%{transform:rotate(270deg) scale(1.2)}
      to{transform:rotate(360deg) scale(1)} 
    }

    /* AUTO-EXPLOSIONS BACKGROUND */
    .auto-explosion {
      position: fixed;
      width: 300px;
      height: 300px;
      border-radius: 50%;
      background: radial-gradient(circle, #ffff00, #ff0000, transparent);
      pointer-events: none;
      animation: autoExplode 1s ease-out forwards;
      z-index: 1;
    }

    @keyframes autoExplode {
      0% { transform: scale(0) rotate(0deg); opacity: 0.8; }
      50% { transform: scale(1.5) rotate(180deg); opacity: 0.6; }
      100% { transform: scale(3) rotate(360deg); opacity: 0; }
    }
  </style>
</head>
<body>
  <div class="cursor-scope"></div>
  
  <h1 class="main-title">🧠💀 BRAINROT MLG ULTRA EXTREME STROBOSCOPE ZONE 💥💀🧠</h1>
  
  <nav class="navbar">
    <a href="#" onclick="showSection('home')">🏠 MLG EXTREME</a>
    <a href="#" onclick="showSection('skibidi')">🚽 SKIBIDI NUKE</a>
    <a href="#" onclick="showSection('ohio')">💀 OHIO CHAOS</a>
    <a href="#" onclick="showSection('sigma')">🗿 SIGMA RAGE</a>
  </nav>

  <!-- Accueil -->
  <div id="home" class="section active">
    <div class="rizz-counter">
      ⚡ RIZZ LEVEL: <span id="rizzLevel">0</span>/50000 🔥 | 
      💥 MLG SCORE: <span id="mlgScore">0</span> 🎯 |
      💀 CHAOS LEVEL: <span id="chaosLevel">0</span>
