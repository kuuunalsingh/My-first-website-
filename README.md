<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Ankush Singh - PlayStation Enthusiast</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@700&display=swap');

    /* Global Styles */
    body, html {
      margin: 0;
      padding: 0;
      height: 100%;
      background: radial-gradient(circle at center, #000000, #0a0a0a 80%);
      color: #0ff;
      font-family: 'Orbitron', sans-serif;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      overflow: hidden;
    }

    .container {
      padding: 2rem 3rem;
      max-width: 600px;
      backdrop-filter: blur(10px);
      background: rgba(0,0,0,0.6);
      border-radius: 20px;
      box-shadow: 0 0 20px #0ff, 0 0 40px #0ff7;
    }

    .logo {
      margin-bottom: 1.5rem;
    }
    .logo img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      box-shadow: 0 0 20px #0ff;
      animation: neonPulse 2.5s ease-in-out infinite alternate;
    }

    .name {
      font-size: 3.5rem;
      color: #0ff;
      text-shadow:
        0 0 5px #0ff,
        0 0 10px #0ff,
        0 0 20px #0ff,
        0 0 40px #0ff,
        0 0 80px #0ff;
      margin: 0 0 1rem 0;
      letter-spacing: 0.12em;
      animation: neonGlow 3s ease-in-out infinite alternate;
    }

    .bio {
      font-size: 1.2rem;
      color: #0ff;
      text-shadow:
        0 0 3px #0ffaa,
        0 0 7px #0ffaafcc;
      line-height: 1.5;
      max-width: 480px;
      margin: 0 auto;
      font-weight: 400;
    }

    @keyframes neonGlow {
      0%, 100% {
        text-shadow:
          0 0 5px #0ff,
          0 0 10px #0ff,
          0 0 20px #0ff,
          0 0 40px #0ff,
          0 0 80px #0ff;
        color: #0ff;
      }
      50% {
        text-shadow:
          0 0 15px #0ff,
          0 0 30px #0ff,
          0 0 45px #0ff,
          0 0 60px #0ff,
          0 0 90px #0ff;
        color: #aff;
      }
    }

    @keyframes neonPulse {
      0%, 100% {
        filter: drop-shadow(0 0 5px #0ff);
      }
      50% {
        filter: drop-shadow(0 0 12px #0ff);
      }
    }
  </style>
</head>
<body>
  <div class="container" role="main" aria-label="Professional bio section">
    <div class="logo" title="Profile Photo">
      <img src="IMG_20250128_234936.jpg" alt="Ankush Singh">
    </div>
    <h1 class="name">Ankush Singh</h1>
    <p class="bio">
      I’m Ankush Singh, a dedicated gamer and tech enthusiast with a passion for the PlayStation universe.
      Whether it’s exploring epic storylines, mastering competitive gameplay, or staying up-to-date with the latest PS5 releases,
      I bring creativity and energy into everything I do. Join me on this journey of immersive gaming and innovation.
    </p>
  </div>
</body>
</html>
