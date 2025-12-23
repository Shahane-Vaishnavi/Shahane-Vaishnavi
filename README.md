<div align="center">
  <img src="https://i.pinimg.com/originals/0f/ff/3e/0fff3ecb7e2a7dd4e9c1c00761a7ee66.gif" alt="Neon Banner" width="100%">
</div>

<style>
  /* GitHub-safe inline styles to keep the neon-glass look */
  .wrap {
    font-family: "Inter", "Segoe UI", system-ui, -apple-system, sans-serif;
    background: linear-gradient(135deg, rgba(86,100,255,0.12), rgba(203,125,255,0.12));
    border: 1px solid rgba(255,255,255,0.18);
    box-shadow: 0 10px 40px rgba(0,0,0,0.25);
    backdrop-filter: blur(8px);
    border-radius: 18px;
    padding: 24px;
    margin: 18px 0;
  }
  .glass {
    border: 1px solid rgba(255,255,255,0.18);
    background: linear-gradient(135deg, rgba(102,126,234,0.15), rgba(118,75,162,0.15));
    box-shadow: 0 10px 30px rgba(87,128,255,0.25);
    border-radius: 16px;
    padding: 18px;
  }
  .glow {
    transition: all 0.3s ease;
    border: 1px solid rgba(255,255,255,0.2);
    box-shadow: 0 0 12px rgba(125,160,255,0.7);
  }
  .glow:hover {
    transform: translateY(-4px) scale(1.01);
    box-shadow: 0 0 18px rgba(118,75,162,0.9), 0 0 28px rgba(87,128,255,0.8);
  }
  .pill {
    display: inline-block;
    padding: 8px 14px;
    border-radius: 999px;
    color: #eaf0ff;
    font-weight: 600;
    background: linear-gradient(120deg, #667eea, #764ba2);
    box-shadow: 0 8px 25px rgba(102,126,234,0.35);
    border: 1px solid rgba(255,255,255,0.16);
  }
  .grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 16px;
  }
  .card {
    background: linear-gradient(135deg, rgba(10,15,40,0.6), rgba(26,18,60,0.65));
    border: 1px solid rgba(255,255,255,0.15);
    border-radius: 14px;
    padding: 16px;
    color: #dfe7ff;
    box-shadow: inset 0 0 30px rgba(102,126,234,0.08);
    transition: all 0.25s ease;
  }
  .card:hover {
    transform: translateY(-6px) scale(1.02);
    border-color: rgba(118,75,162,0.55);
    box-shadow: 0 0 20px rgba(118,75,162,0.45), 0 0 30px rgba(87,128,255,0.35);
  }
  .badge-btn {
    display: inline-block;
    padding: 10px 16px;
    border-radius: 12px;
    color: #eaf0ff;
    text-decoration: none;
    font-weight: 700;
    background: linear-gradient(120deg, #6a5acd, #00c6ff);
    border: 1px solid rgba(255,255,255,0.2);
    box-shadow: 0 10px 25px rgba(0,198,255,0.35);
    transition: all 0.25s ease;
  }
  .badge-btn:hover { box-shadow: 0 0 18px rgba(0,198,255,0.7); transform: translateY(-3px); }
  .header-glow { text-shadow: 0 0 14px rgba(0,198,255,0.55), 0 0 22px rgba(118,75,162,0.65); }
  .sparkle-bg { background: url("https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines.svg"); background-size: cover; }
  .float {
    animation: float 6s ease-in-out infinite;
  }
  .pulse {
    position: relative;
  }
  .pulse::after {
    content: "";
    position: absolute;
    inset: -6px;
    border-radius: 14px;
    background: radial-gradient(circle, rgba(118,75,162,0.25) 0%, rgba(0,0,0,0) 60%);
    filter: blur(12px);
    z-index: -1;
    animation: pulse 3s ease-in-out infinite;
  }
  @keyframes float { 0% { transform: translateY(0); } 50% { transform: translateY(-8px); } 100% { transform: translateY(0); } }
  @keyframes pulse { 0% { opacity: 0.55; } 50% { opacity: 0.9; } 100% { opacity: 0.55; } }
</style>

<div class="wrap sparkle-bg">
  <h1 align="center" class="header-glow">Hi, I'm Vaishnavi Shahane ✨</h1>
  <h3 align="center">CSE Student | Data Enthusiast | ML Developer</h3>
  <p align="center">
    <img src="https://komarev.com/ghpvc/?username=Shahane-Vaishnavi&label=Profile%20Views&color=6f9dff&style=for-the-badge" alt="Profile views"/>
  </p>
  <p align="center">
    <img src="https://media.giphy.com/media/26AHONQ79FdWZhAI0/giphy.gif" alt="Floating particles" width="240" class="float">
  </p>
  <p align="center"><span class="pill">Modern Web • AI/ML • Data Storytelling</span></p>
</div>

<div class="wrap glass">
  <h2 align="center" class="header-glow">🛠️ Tech Stack</h2>
  <div class="grid">
    <div class="card glow pulse">
      <h4>Languages</h4>
      Java · Python · C++ · C · JavaScript
    </div>
    <div class="card glow pulse">
      <h4>Frontend</h4>
      Next.js · HTML5 · CSS3
    </div>
    <div class="card glow pulse">
      <h4>Backend</h4>
      FastAPI · Node.js
    </div>
    <div class="card glow pulse">
      <h4>Databases & Tools</h4>
      MongoDB · MySQL · Git · GitHub
    </div>
  </div>
</div>

<div class="wrap glass">
  <h2 align="center" class="header-glow">🚀 Projects</h2>
  <table width="100%">
    <tr>
      <td width="50%">
        <div class="card glow pulse">
          <h3 align="center">GATE Assistant</h3>
          <div align="center">
            <img src="https://via.placeholder.com/520x260/667eea/ffffff?text=GATE+Assistant" alt="GATE Assistant" width="100%" class="glow">
          </div>
          <p>AI-powered study tool with personalized plans and intelligent practice for GATE aspirants.</p>
          <div align="center"><a class="badge-btn" href="https://github.com/Shahane-Vaishnavi/GATE-Assistant" target="_blank">View Code</a></div>
        </div>
      </td>
      <td width="50%">
        <div class="card glow pulse">
          <h3 align="center">ML Model Repository</h3>
          <div align="center">
            <img src="https://via.placeholder.com/520x260/764ba2/ffffff?text=ML+Models" alt="ML Models" width="100%" class="glow">
          </div>
          <p>Curated collection of ML experiments, classic algorithms, and production-ready notebooks.</p>
          <div align="center"><a class="badge-btn" href="https://github.com/Shahane-Vaishnavi/ML-Projects" target="_blank">View Code</a></div>
        </div>
      </td>
    </tr>
    <tr>
      <td width="50%">
        <div class="card glow pulse">
          <h3 align="center">Analytics Dashboard</h3>
          <div align="center">
            <img src="https://via.placeholder.com/520x260/f093fb/ffffff?text=Analytics+Dashboard" alt="Analytics Dashboard" width="100%" class="glow">
          </div>
          <p>Interactive dashboards to surface insights fast with clean visuals and smooth filters.</p>
          <div align="center"><a class="badge-btn" href="https://github.com/Shahane-Vaishnavi/Analytics-Dashboard" target="_blank">View Code</a></div>
        </div>
      </td>
      <td width="50%">
        <div class="card glow pulse">
          <h3 align="center">Algorithm Visualizer</h3>
          <div align="center">
            <img src="https://via.placeholder.com/520x260/4facfe/ffffff?text=Algorithm+Visualizer" alt="Algorithm Visualizer" width="100%" class="glow">
          </div>
          <p>Animated walkthroughs of sorting and searching algorithms with step-by-step highlights.</p>
          <div align="center"><a class="badge-btn" href="https://github.com/Shahane-Vaishnavi/Algorithm-Visualizer" target="_blank">View Code</a></div>
        </div>
      </td>
    </tr>
  </table>
</div>

<div class="wrap glass">
  <h2 align="center" class="header-glow">📊 GitHub Stats</h2>
  <p align="center">
    <img class="glow" src="https://github-readme-streak-stats.herokuapp.com/?user=Shahane-Vaishnavi&theme=tokyonight&hide_border=true&background=0d1117" width="49%"/>
    <img class="glow" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Shahane-Vaishnavi&layout=compact&theme=tokyonight&hide_border=true&background=0d1117" width="49%"/>
  </p>
</div>

<div class="wrap glass">
  <h2 align="center" class="header-glow">🌱 Currently Learning</h2>
  <div class="grid">
    <div class="card glow"><img src="https://media.giphy.com/media/l1J9Jzcs9r4GdYnl2/giphy.gif" width="32"> Deep Learning</div>
    <div class="card glow"><img src="https://media.giphy.com/media/xT5LMHxhOfscxPfIfm/giphy.gif" width="32"> Android Development</div>
    <div class="card glow"><img src="https://media.giphy.com/media/3o7btNhMBytxAM6YBa/giphy.gif" width="32"> Data Engineering</div>
    <div class="card glow"><img src="https://media.giphy.com/media/3o6Zt6ML6BklcajjsA/giphy.gif" width="32"> Competitive Programming</div>
  </div>
</div>

<div class="wrap glass">
  <h2 align="center" class="header-glow">💡 What I'm Looking For</h2>
  <div class="grid">
    <div class="card glow">🔮 Collaboration on AI/ML projects</div>
    <div class="card glow">🌌 Mentorship in Data Science</div>
    <div class="card glow">🚀 AI/ML internships</div>
  </div>
</div>

<div class="wrap glass">
  <h2 align="center" class="header-glow">🔗 Connect</h2>
  <p align="center">
    <a class="badge-btn" href="mailto:your-email@example.com">Email</a>
    &nbsp;
    <a class="badge-btn" href="https://www.linkedin.com/in/vaishnavi-shahane-0a3135335/" target="_blank">LinkedIn</a>
    &nbsp;
    <a class="badge-btn" href="https://github.com/Shahane-Vaishnavi" target="_blank">GitHub</a>
  </p>
</div>

<div class="wrap glass">
  <h2 align="center" class="header-glow">🎉 Fun Fact</h2>
  <p align="center">✨ Still a student… already shipping solutions that glow!</p>
  <p align="center">
    <img src="https://media.giphy.com/media/3oz8xIsloV7zOmt81G/giphy.gif" width="120" class="float" alt="Animated emoji">
  </p>
  <div align="center">
    <img class="glow" src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />
  </div>
</div>

<p align="center" class="header-glow"><i>⭐ From Shahane-Vaishnavi</i></p>
