<style>
  @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@700&family=Exo+2:wght@600&family=Roboto+Mono&display=swap');

  :root {
    --neon-cyan: #00ffea;
    --neon-pink: #ff007a;
    --bg-dark: #0a0a1f;
    --text-light: #e0e0e0;
    --card-bg: rgba(0, 255, 234, 0.08);
  }

  body {
    background: linear-gradient(-45deg, #0a0a1f, #1a0033, #000011, #0f0a2e);
    background-size: 400% 400%;
    animation: gradientShift 15s ease infinite;
    color: var(--text-light);
    font-family: 'Roboto Mono', monospace;
    margin: 0;
    padding: 0;
  }

  @keyframes gradientShift {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }

  @keyframes neonPulse {
    from { text-shadow: 0 0 10px var(--neon-cyan), 0 0 20px var(--neon-cyan); }
    to { text-shadow: 0 0 20px var(--neon-cyan), 0 0 30px var(--neon-cyan), 0 0 40px var(--neon-cyan); }
  }

  h1, h2, h3 {
    font-family: 'Exo 2', sans-serif;
  }

  .neon-text {
    color: var(--neon-cyan);
    animation: neonPulse 1.5s ease-in-out infinite alternate;
    font-family: 'Orbitron', sans-serif;
  }

  .section-title {
    color: #ffffff;
    text-shadow: 0 0 8px var(--neon-pink);
    border-bottom: 2px solid var(--neon-pink);
    padding-bottom: 8px;
    display: inline-block;
  }

  .about-card {
    background: var(--card-bg);
    padding: 18px;
    border-radius: 12px;
    margin: 15px 20px;
    backdrop-filter: blur(5px);
    border: 1px solid rgba(0, 255, 234, 0.2);
    box-shadow: 0 0 15px rgba(0, 255, 234, 0.3);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }

  .about-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 0 25px rgba(0, 255, 234, 0.6);
  }

  .tech-icons a {
    transition: all 0.3s ease;
    filter: drop-shadow(0 0 5px var(--neon-cyan));
  }

  .tech-icons a:hover {
    transform: scale(1.25) translateY(-5px);
    filter: drop-shadow(0 0 15px var(--neon-cyan));
  }

  .gif-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 15px;
    margin: 25px 0;
  }

  .gif-container img {
    border-radius: 12px;
    box-shadow: 0 0 15px var(--neon-cyan);
    transition: transform 0.3s ease;
  }

  .gif-container img:hover {
    transform: scale(1.1);
  }

  .stats img {
    border-radius: 12px;
    box-shadow: 0 0 20px rgba(0, 255, 234, 0.4);
    transition: all 0.3s ease;
  }

  .stats img:hover {
    box-shadow: 0 0 30px rgba(0, 255, 234, 0.7);
    transform: translateY(-3px);
  }
</style>

<div align="center">
  <h1 class="neon-text" style="font-size: 3.2em; margin: 30px 0;">
    Kon'nichiwa / こんにちは
  </h1>

  <div class="gif-container">
    <img src="https://media.giphy.com/media/iOkpqb0MRjWqtrOKVU/giphy.gif" width="150" alt="cyberpunk"/>
    <img src="https://media.giphy.com/media/2ZXwdhSx6lWwWkTzE6/giphy.gif" width="150" alt="matrix"/>
    <img src="https://media.giphy.com/media/26uf9smjCawERdCmI/giphy.gif" width="150" alt="hacker"/>
    <img src="https://media.giphy.com/media/xT39DgKMixPKDrwzf2/giphy.gif" width="150" alt="code"/>
  </div>
</div>

---

<h2 class="section-title">🚀 About Me</h2>

<div class="about-card">
  👋 Greetings, I'm <a href="https://github.com/amfam" style="color: var(--neon-cyan); text-decoration: none; font-weight: bold;">@amfam</a>, a <strong>cyber-traveler</strong> coding through the digital cosmos of the 21st century!
</div>

<div class="about-card">
  👀 I harness the power of code, diving into complex algorithms and crafting solutions that push the boundaries of technology. My terminal is my portal to innovation.
</div>

<div class="about-card">
  🌱 Currently decoding the mysteries of <strong>knowledge representation</strong>, transforming raw data into structured intelligence with a passion for discovery.
</div>

<div class="about-card">
  💞️ Seeking collaborators to architect <strong>groundbreaking data science and engineering projects</strong>. Let’s shape the future, one line of code at a time!
</div>

---

<h3 class="section-title">🔧 Languages & Tools</h3>

<p align="left" class="tech-icons">
  <a href="https://developer.android.com" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/>
  </a>
  <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/>
  </a>
  <a href="https://d3js.org/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/d3js/d3js-original.svg" alt="d3js" width="40" height="40"/>
  </a>
  <a href="https://www.python.org" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/>
  </a>
  <a href="https://www.java.com" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/>
  </a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/>
  </a>
  <a href="https://git-scm.com/" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/>
  </a>
  <a href="https://www.docker.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="docker" width="40" height="40"/>
  </a>
  <a href="https://kubernetes.io" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/>
  </a>
  <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/>
  </a>
  <a href="https://pytorch.org/" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="40" height="40"/>
  </a>
  <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/>
  </a>
</p>

---

<div align="center" class="stats" style="margin: 40px 0;">
  <img src="https://github-readme-stats.vercel.app/api?username=amfam&theme=react&hide_border=true&include_all_commits=true&count_private=true&show_icons=true&bg_color=0a0a1f&title_color=00ffea&text_color=e0e0e0&icon_color=00ffea" alt="GitHub Stats"/>
  <br/><br/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=amfam&theme=react&hide_border=true&background=0a0a1f&stroke=00ffea&ring=ff007a&fire=00ffea&currStreakLabel=00ffea" alt="GitHub Streak"/>
  <br/><br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=amfam&layout=compact&theme=react&hide_border=true&bg_color=0a0a1f&title_color=00ffea&text_color=e0e0e0" alt="Top Languages"/>
</div>

<div align="center" style="margin-top: 50px; font-size: 0.9em; color: #888;">
  <i>⚡ Powered by code, caffeine, and curiosity.</i>
</div>
