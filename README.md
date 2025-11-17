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
    transform: scale(1.25) translateY(-5px
