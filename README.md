<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>🎉 Happy Birthday Pinki! 🎉</title>
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Poppins:wght@300;600;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: linear-gradient(135deg, #667eea 0%, #764ba2 25%, #f093fb 50%, #4facfe 75%, #00f2fe 100%);
      background-size: 400% 400%;
      animation: gradientShift 15s ease infinite;
      min-height: 100vh;
      font-family: 'Poppins', sans-serif;
      overflow: hidden;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    @keyframes gradientShift {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .container {
      text-align: center;
      z-index: 10;
      position: relative;
      padding: 20px;
    }

    .main-title {
      font-family: 'Pacifico', cursive;
      font-size: 4rem;
      color: #fff;
      text-shadow: 0 0 20px rgba(255, 100, 200, 0.8), 0 0 40px rgba(100, 200, 255, 0.6);
      margin-bottom: 20px;
      animation: titleBounce 1.2s ease-in-out infinite;
      letter-spacing: 3px;
    }

    @keyframes titleBounce {
      0%, 100% { transform: translateY(0) scale(1); }
      50% { transform: translateY(-30px) scale(1.05); }
    }

    .name {
      font-size: 3.5rem;
      font-weight: 700;
      background: linear-gradient(45deg, #ff6b9d, #feca57, #48dbfb, #ff9ff3);
      background-size: 200% 200%;
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      animation: nameGlow 2s ease-in-out infinite;
      margin-bottom: 30px;
    }

    @keyframes nameGlow {
      0%, 100% { text-shadow: 0 0 20px rgba(255, 107, 157, 0.4); }
      50% { text-shadow: 0 0 40px rgba(255, 200, 100, 0.6); }
    }

    .subtitle {
      font-size: 1.8rem;
      color: #fff;
      margin-bottom: 40px;
      animation: fadeInUp 1s ease-out;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
    }

    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .wish-message {
      background: rgba(255, 255, 255, 0.1);
      backdrop-filter: blur(10px);
      border: 2px solid rgba(255, 255, 255, 0.2);
      border-radius: 20px;
      padding: 30px 50px;
      margin: 30px 0;
      font-size: 1.3rem;
      color: #fff;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
      animation: slideIn 1.2s ease-out;
      box-shadow: 0 8px 32px rgba(0, 0, 0, 0.1);
    }

    @keyframes slideIn {
      from { opacity: 0; transform: translateX(-50px); }
      to { opacity: 1; transform: translateX(0); }
    }

    .cta-button {
      background: linear-gradient(45deg, #ff6b9d, #c44569);
      color: white;
      border: none;
      padding: 18px 50px;
      font-size: 1.2rem;
      font-weight: 600;
      border-radius: 50px;
      cursor: pointer;
      margin: 20px 10px;
      transition: all 0.3s ease;
      box-shadow: 0 10px 30px rgba(255, 107, 157, 0.4);
      animation: buttonPop 0.6s cubic-bezier(0.68, -0.55, 0.265, 1.55);
      text-transform: uppercase;
      letter-spacing: 2px;
    }

    @keyframes buttonPop {
      0% { transform: scale(0); }
      50% { transform: scale(1.1); }
      100% { transform: scale(1); }
    }

    .cta-button:hover {
      transform: scale(1.08) translateY(-3px);
      box-shadow: 0 15px 40px rgba(255, 107, 157, 0.6);
    }

    .cta-button:active {
      transform: scale(0.98);
    }

    .secondary-btn {
      background: linear-gradient(45deg, #4facfe, #00f2fe);
      box-shadow: 0 10px 30px rgba(79, 172, 254, 0.4);
    }

    .secondary-btn:hover {
      box-shadow: 0 15px 40px rgba(79, 172, 254, 0.6);
    }

    /* BALLOONS */
    .balloon {
      position: fixed;
      bottom: -100px;
      width: 50px;
      height: 70px;
      border-radius: 50% 50% 50% 50% / 60% 60% 40% 40%;
      opacity: 0.8;
      animation: float linear infinite;
      z-index: 1;
    }

    .balloon::before {
      content: '';
      position: absolute;
      bottom: -20px;
      left: 50%;
      transform: translateX(-50%);
      width: 2px;
      height: 80px;
      background: #ddd;
    }

    @keyframes float {
      0% {
        bottom: -100px;
        opacity: 0;
      }
      10% {
        opacity: 1;
      }
      90% {
        opacity: 1;
      }
      100% {
        bottom: 100vh;
        opacity: 0;
        transform: translateX(100px);
      }
    }

    .balloon-1 { background: #ff6b6b; animation-delay: 0s; animation-duration: 8s; left: 10%; }
    .balloon-2 { background: #ffd93d; animation-delay: 2s; animation-duration: 9s; left: 20%; }
    .balloon-3 { background: #6bcf7f; animation-delay: 4s; animation-duration: 10s; left: 30%; }
    .balloon-4 { background: #4d96ff; animation-delay: 1s; animation-duration: 8.5s; left: 40%; }
    .balloon-5 { background: #ff6b9d; animation-delay: 3s; animation-duration: 9.5s; left: 50%; }
    .balloon-6 { background: #c44569; animation-delay: 5s; animation-duration: 10.5s; left: 60%; }
    .balloon-7 { background: #feca57; animation-delay: 2.5s; animation-duration: 9s; left: 70%; }
    .balloon-8 { background: #48dbfb; animation-delay: 4.5s; animation-duration: 10s; left: 80%; }
    .balloon-9 { background: #ff9ff3; animation-delay: 1.5s; animation-duration: 8.5s; left: 90%; }

    /* CONFETTI */
    .confetti {
      position: fixed;
      pointer-events: none;
      z-index: 5;
    }

    /* STARS */
    .star {
      position: fixed;
      color: #fff;
      font-size: 1.5rem;
      animation: twinkle 1.5s infinite;
      z-index: 2;
    }

    @keyframes twinkle {
      0%, 100% { opacity: 0.3; }
      50% { opacity: 1; }
    }

    /* FIREWORKS */
    .firework {
      position: fixed;
      width: 5px;
      height: 5px;
      border-radius: 50%;
      pointer-events: none;
      z-index: 3;
    }

    @keyframes explode {
      0% {
        transform: translate(0, 0);
        opacity: 1;
      }
      100% {
        opacity: 0;
      }
    }

    .music-toggle {
      position: fixed;
      bottom: 30px;
      right: 30px;
      background: rgba(255, 107, 157, 0.8);
      border: none;
      color: white;
      width: 60px;
      height: 60px;
      border-radius: 50%;
      font-size: 1.5rem;
      cursor: pointer;
      z-index: 100;
      transition: all 0.3s ease;
      box-shadow: 0 5px 20px rgba(255, 107, 157, 0.4);
    }

    .music-toggle:hover {
      transform: scale(1.1);
      background: rgba(255, 107, 157, 1);
    }

    @media (max-width: 768px) {
      .main-title { font-size: 2.5rem; }
      .name { font-size: 2rem; }
      .subtitle { font-size: 1.2rem; }
      .wish-message { padding: 20px 30px; font-size: 1rem; }
      .cta-button { padding: 15px 40px; font-size: 1rem; }
    }
  </style>
</head>
<body>
  <!-- BALLOONS -->
  <div class="balloon balloon-1"></div>
  <div class="balloon balloon-2"></div>
  <div class="balloon balloon-3"></div>
  <div class="balloon balloon-4"></div>
  <div class="balloon balloon-5"></div>
  <div class="balloon balloon-6"></div>
  <div class="balloon balloon-7"></div>
  <div class="balloon balloon-8"></div>
  <div class="balloon balloon-9"></div>

  <!-- STARS -->
  <div id="stars-container"></div>

  <!-- MAIN CONTENT -->
  <div class="container">
    <div class="main-title">🎉 Happy Birthday! 🎉</div>
    <div class="name">Pinki</div>
    <div class="subtitle">✨ May your day be as special as you are! ✨</div>
    
    <div class="wish-message">
      <p>🎂 Wishing you a year filled with laughter, love, and endless joy! 🎂</p>
      <p style="margin-top: 15px;">May all your dreams come true and every moment be magical!</p>
    </div>

    <div>
      <button class="cta-button" onclick="celebrateBirthday()">🎊 Click Me to Celebrate! 🎊</button>
      <button class="cta-button secondary-btn" onclick="playMusic()">🎵 Play Music 🎵</button>
    </div>
  </div>

  <!-- MUSIC TOGGLE -->
  <button class="music-toggle" id="musicToggle" onclick="toggleMusic()">🔊</button>

  <!-- AUDIO -->
  <audio id="birthdayAudio" loop>
    <source src="https://assets.mixkit.co/active_storage/sfx/2293/2293-preview.mp3" type="audio/mpeg">
  </audio>

  <script>
    // CREATE STARS
    function createStars() {
      const starsContainer = document.getElementById('stars-container');
      for (let i = 0; i < 50; i++) {
        const star = document.createElement('div');
        star.className = 'star';
        star.textContent = '✨';
        star.style.left = Math.random() * 100 + '%';
        star.style.top = Math.random() * 100 + '%';
        star.style.animationDelay = Math.random() * 1.5 + 's';
        starsContainer.appendChild(star);
      }
    }

    // CREATE CONFETTI
    function createConfetti() {
      const colors = ['#ff6b9d', '#feca57', '#48dbfb', '#ff9ff3', '#6bcf7f', '#4d96ff'];
      for (let i = 0; i < 80; i++) {
        const confetti = document.createElement('div');
        confetti.className = 'confetti';
        confetti.style.left = Math.random() * 100 + 'vw';
        confetti.style.top = '-10px';
        confetti.style.background = colors[Math.floor(Math.random() * colors.length)];
        confetti.style.width = (Math.random() * 10 + 5) + 'px';
        confetti.style.height = confetti.style.width;
        confetti.style.borderRadius = '50%';
        
        const duration = Math.random() * 2 + 2;
        confetti.style.animation = `fall ${duration}s linear forwards`;
        document.body.appendChild(confetti);
        
        setTimeout(() => confetti.remove(), duration * 1000);
      }
    }

    // CREATE FIREWORKS
    function createFireworks(x, y) {
      const colors = ['#ff6b9d', '#feca57', '#48dbfb', '#ff9ff3'];
      for (let i = 0; i < 30; i++) {
        const firework = document.createElement('div');
        firework.className = 'firework';
        firework.style.left = x + 'px';
        firework.style.top = y + 'px';
        firework.style.background = colors[Math.floor(Math.random() * colors.length)];
        
        const angle = (Math.PI * 2 * i) / 30;
        const velocity = 5 + Math.random() * 5;
        const tx = Math.cos(angle) * velocity * 50;
        const ty = Math.sin(angle) * velocity * 50;
        
        firework.style.animation = `explode 1s ease-out forwards`;
        firework.style.setProperty('--tx', tx + 'px');
        firework.style.setProperty('--ty', ty + 'px');
        
        document.body.appendChild(firework);
        
        setTimeout(() => firework.remove(), 1000);
      }
    }

    // ADD EXPLODE KEYFRAMES
    const style = document.createElement('style');
    style.innerHTML = `
      @keyframes fall {
        to {
          transform: translateY(100vh) rotate(360deg);
          opacity: 0;
        }
      }
      @keyframes explode {
        to {
          transform: translate(var(--tx), var(--ty));
          opacity: 0;
        }
      }
    `;
    document.head.appendChild(style);

    // CELEBRATE FUNCTION
    function celebrateBirthday() {
      createConfetti();
      createFireworks(window.innerWidth / 2, window.innerHeight / 2);
      
      // Additional fireworks
      for (let i = 0; i < 5; i++) {
        setTimeout(() => {
          const x = Math.random() * window.innerWidth;
          const y = Math.random() * (window.innerHeight * 0.7);
          createFireworks(x, y);
        }, i * 200);
      }
    }

    // MUSIC CONTROL
    const audio = document.getElementById('birthdayAudio');
    let isPlaying = false;

    function playMusic() {
      if (isPlaying) {
        audio.pause();
        isPlaying = false;
        document.getElementById('musicToggle').textContent = '🔊';
      } else {
        audio.play();
        isPlaying = true;
        document.getElementById('musicToggle').textContent = '🔇';
      }
    }

    function toggleMusic() {
      playMusic();
    }

    // INITIALIZE
    createStars();

    // Auto-celebrate on page load
    window.addEventListener('load', () => {
      setTimeout(celebrateBirthday, 500);
    });

    // Celebration on every click
    document.addEventListener('click', () => {
      const rect = event.target.getBoundingClientRect();
      createFireworks(rect.left + rect.width / 2, rect.top + rect.height / 2);
    });
  </script>
</body>
</html>
