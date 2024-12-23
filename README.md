<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <style>
    body {
      font-family: -apple-system, sans-serif;
      line-height: 1.6;
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
      background: #0d1117;
      color: #c9d1d9;
      text-align: center;
    }
    
    .typing-effect {
      background: linear-gradient(45deg, #0076D6, #00a6ed);
      padding: 20px;
      border-radius: 10px;
      margin: 20px 0;
      animation: pulse 2s infinite;
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.02); }
      100% { transform: scale(1); }
    }

    .badges {
      display: flex;
      justify-content: center;
      gap: 10px;
      margin: 20px 0;
    }

    .badge {
      background: #161b22;
      padding: 8px 15px;
      border-radius: 20px;
      border: 1px solid #30363d;
    }

    .stats-container {
      display: flex;
      justify-content: space-around;
      margin: 30px 0;
      gap: 20px;
    }

    .stat-card {
      background: #161b22;
      padding: 20px;
      border-radius: 10px;
      border: 1px solid #30363d;
      width: 45%;
    }

    .skills {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
      gap: 20px;
      margin: 30px 0;
      padding: 20px;
      background: #161b22;
      border-radius: 10px;
    }

    .skill-icon {
      width: 50px;
      height: 50px;
      margin: 10px;
      transition: transform 0.3s;
    }

    .skill-icon:hover {
      transform: scale(1.2);
    }

    .connect {
      display: flex;
      justify-content: center;
      gap: 15px;
      margin: 30px 0;
    }

    .social-icon {
      width: 40px;
      height: 40px;
      transition: transform 0.3s;
    }

    .social-icon:hover {
      transform: translateY(-5px);
    }
  </style>
</head>
<body>
  <h1>👋 Web Fullstack Developer</h1>
  
  <div class="typing-effect">
    <h2>Web Developer | Full Stack Developer | Always learning new tech</h2>
  </div>

  <div class="badges">
    <span class="badge">🌟 Profile Views: 1234</span>
    <span class="badge">⭐ Stars: 150</span>
    <span class="badge">📚 Repositories: 45</span>
  </div>

  <div class="stats-container">
    <div class="stat-card">
      <img src="/api/placeholder/350/150" alt="GitHub Stats">
    </div>
    <div class="stat-card">
      <img src="/api/placeholder/350/150" alt="Top Languages">
    </div>
  </div>

  <h2>🛠️ Skills & Tools</h2>
  <div class="skills">
    <!-- Reemplaza las URLs con las de tus propios iconos -->
    <img src="/api/placeholder/50/50" alt="HTML5" class="skill-icon">
    <img src="/api/placeholder/50/50" alt="CSS3" class="skill-icon">
    <img src="/api/placeholder/50/50" alt="JavaScript" class="skill-icon">
    <img src="/api/placeholder/50/50" alt="React" class="skill-icon">
    <img src="/api/placeholder/50/50" alt="Node.js" class="skill-icon">
  </div>

  <h2>🤝 Connect with me</h2>
  <div class="connect">
    <img src="/api/placeholder/40/40" alt="LinkedIn" class="social-icon">
    <img src="/api/placeholder/40/40" alt="GitHub" class="social-icon">
    <img src="/api/placeholder/40/40" alt="Twitter" class="social-icon">
  </div>
</body>
</html>
