<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pranab Naskar</title>
<link href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono&family=Syne:wght@800&display=swap" rel="stylesheet">
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    background: #0a0e17;
    font-family: 'Share Tech Mono', monospace;
    color: #c9d1d9;
    min-height: 100vh;
    display: flex;
    align-items: center;
    padding: 3rem 2rem;
  }

  .hero {
    max-width: 900px;
    width: 100%;
  }

  /* Glitch Name */
  .glitch-name {
    font-family: 'Syne', sans-serif;
    font-weight: 800;
    font-size: clamp(3rem, 9vw, 6rem);
    line-height: 1;
    color: #fff;
    position: relative;
    display: inline-block;
    letter-spacing: -2px;
    margin-bottom: 1.2rem;

    /* Green to Pink gradient fill */
    background: linear-gradient(90deg, #00ff88 0%, #ff79c6 50%, #00ff88 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }

  /* Glitch layers */
  .glitch-name::before,
  .glitch-name::after {
    content: attr(data-text);
    position: absolute;
    top: 0; left: 0;
    width: 100%; height: 100%;
    background: linear-gradient(90deg, #00ff88 0%, #ff79c6 50%, #00ff88 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }

  .glitch-name::before {
    animation: glitch1 3.5s infinite;
    clip-path: polygon(0 0, 100% 0, 100% 38%, 0 38%);
    opacity: 0.85;
  }

  .glitch-name::after {
    animation: glitch2 3.5s infinite;
    clip-path: polygon(0 62%, 100% 62%, 100% 100%, 0 100%);
    opacity: 0.85;
  }

  @keyframes glitch1 {
    0%, 88%, 100% { transform: translate(0); }
    90%  { transform: translate(-4px, 0); }
    92%  { transform: translate(4px, 0); }
    94%  { transform: translate(-2px, 0); }
    96%  { transform: translate(0); }
  }

  @keyframes glitch2 {
    0%, 88%, 100% { transform: translate(0); }
    90%  { transform: translate(4px, 0); }
    92%  { transform: translate(-4px, 0); }
    94%  { transform: translate(2px, 0); }
    96%  { transform: translate(0); }
  }

  /* Role line */
  .role-line {
    font-size: 15px;
    color: #8b949e;
    letter-spacing: 1px;
    margin-bottom: 1.6rem;
  }

  .role-line .arrow { color: #00ff88; margin-right: 6px; }
  .role-line .hl    { color: #00ff88; }
  .role-line .sep   { margin: 0 10px; color: #3a4152; }

  /* Badge row */
  .badge-row {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
  }

  .badge {
    font-family: 'Share Tech Mono', monospace;
    font-size: 11px;
    letter-spacing: 1.8px;
    padding: 7px 16px;
    border-radius: 5px;
    border: 1px solid;
    display: inline-flex;
    align-items: center;
    gap: 7px;
  }

  .b-green  { border-color: #00ff88; color: #00ff88; background: rgba(0,255,136,0.07); }
  .b-blue   { border-color: #79c0ff; color: #79c0ff; background: rgba(121,192,255,0.07); }
  .b-pink   { border-color: #ff79c6; color: #ff79c6; background: rgba(255,121,198,0.07); }
  .b-amber  { border-color: #f0a030; color: #f0a030; background: rgba(240,160,48,0.07); }
</style>
</head>
<body>

<div class="hero">

  <div class="glitch-name" data-text="Pranab Naskar">Pranab Naskar</div>

  <div class="role-line">
    <span class="arrow">→</span>
    <span class="hl">BSc IT (AI)</span>
    <span class="sep">·</span>
    MAKAUT University
    <span class="sep">·</span>
    Year 01
  </div>

  <div class="badge-row">
    <span class="badge b-green">◉ OPEN TO COLLABORATE</span>
    <span class="badge b-blue">⚡ AI ENTHUSIAST</span>
    <span class="badge b-pink">🎓 FIRST YEAR</span>
    <span class="badge b-amber">⚙ LEARNING MODE: ON</span>
  </div>

</div>

</body>
</html>

### 🚀 About Me

- 🎓 I’m a **1st-year student at MAKAUT, W.B**, pursuing **BSc. IT in Artificial Intelligence**
- 🌱 Currently learning **Python** and the **JAVA**
- 💬 Ask me about **Python, C, C++**
- 📫 Reach me at: **pranabnaskar2403@gmail.com**
- ⚡ **Fun fact**: I design interfaces by day, explore AI by night, and occasionally build Minecraft worlds in between. 🚀🎨🤖


## 🌐 Socials:
[![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white)](https://discord.gg/ashbornx2407) [![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?logo=Facebook&logoColor=white)](https://facebook.com/pranab.naskar.940142) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/t_soumo_0824) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/pranab-naskar-226a84370?utm) [![Pinterest](https://img.shields.io/badge/Pinterest-%23E60023.svg?logo=Pinterest&logoColor=white)](https://pinterest.com/pranabnaskar2403) [![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/@PranabNaskar24) [![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?logo=YouTube&logoColor=white)](https://youtube.com/@@pngamingworld2007) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:pranabnaskar2403@gmail.com) 

# 💻 Tech Stack:
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) ![Adobe](https://img.shields.io/badge/adobe-%23FF0000.svg?style=for-the-badge&logo=adobe&logoColor=white) ![Xbox](https://img.shields.io/badge/xbox-%23107C10.svg?style=for-the-badge&logo=xbox&logoColor=white) ![Riot Games](https://img.shields.io/badge/riotgames-D32936.svg?style=for-the-badge&logo=riotgames&logoColor=white) ![Epic Games](https://img.shields.io/badge/epicgames-%23313131.svg?style=for-the-badge&logo=epicgames&logoColor=white) ![OpenGL](https://img.shields.io/badge/OpenGL-white?logo=OpenGL&style=for-the-badge) ![AMD](https://img.shields.io/badge/AMD-%23000000.svg?style=for-the-badge&logo=amd&logoColor=white) ![Steam](https://img.shields.io/badge/steam-%23000000.svg?style=for-the-badge&logo=steam&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-stats.shion.dev/api?username=pranab2403&theme=one_dark_pro&hide_border=false&include_all_commits=true&count_private=false)<br/>
![](https://streak-stats.demolab.com/?user=pranab2403&theme=one_dark_pro&hide_border=false)<br/>
![](https://github-readme-stats.shion.dev/api/top-langs/?username=pranab2403&theme=one_dark_pro&hide_border=false&include_all_commits=true&count_private=false&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=pranab2403&theme=radical&no-frame=false&no-bg=true&margin-w=4)

---
[![](https://komarev.com/ghpvc/?username=pranab2403&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
