<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover" />
  <title>A Question for You 💕</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      /* Removes ugly blue box on mobile tap */
      -webkit-tap-highlight-color: transparent; 
    }

    body {
      background-color: #fce4ec;
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      min-height: 100dvh; /* Mobile browser height fix */
      overflow: hidden;
      padding: 20px 10px;
      user-select: none; /* Prevents text highlighting on rapid taps */
    }

    .container {
      position: relative;
      display: flex;
      flex-direction: column;
      align-items: center;
      width: 100%;
      max-width: 360px;
      padding-top: 60px; /* Gives room for letter to slide up */
    }

    .instruction {
      font-size: 1.1rem;
      color: #ad1457;
      margin-bottom: 25px;
      font-weight: 600;
      text-align: center;
      animation: bounce 2s infinite;
      transition: opacity 0.3s ease;
    }

    /* Envelope Styling */
    .envelope-wrapper {
      position: relative;
      width: 280px;
      height: 180px;
      cursor: pointer;
      touch-action: manipulation;
    }

    .envelope {
      position: relative;
      width: 100%;
      height: 100%;
      background-color: #f48fb1;
      border-bottom-left-radius: 12px;
      border-bottom-right-radius: 12px;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
    }

    /* Envelope Top Flap */
    .flap {
      position: absolute;
      top: 0;
      left: 0;
      border-left: 140px solid transparent;
      border-right: 140px solid transparent;
      border-top: 98px solid #f06292;
      transform-origin: top;
      transition: transform 0.4s ease-in-out, z-index 0.4s;
      z-index: 3;
    }

    /* Envelope Front Pocket */
    .pocket {
      position: absolute;
      top: 0;
      left: 0;
      width: 0;
      height: 0;
      border-left: 140px solid #f48fb1;
      border-right: 140px solid #f48fb1;
      border-bottom: 90px solid #ec407a;
      border-top: 90px solid transparent;
      border-bottom-left-radius: 12px;
      border-bottom-right-radius: 12px;
      z-index: 2;
    }

    /* Letter inside */
    .letter {
      position: absolute;
      bottom: 8px;
      left: 12px;
      width: 256px;
      height: 165px;
      background: #ffffff;
      border-radius: 12px;
      padding: 16px 12px;
      text-align: center;
      transition: transform 0.5s ease-in-out, z-index 0.5s;
      z-index: 1;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
    }

    .letter p {
      font-size: 1.1rem;
      color: #880e4f;
      font-weight: bold;
      line-height: 1.35;
      margin-top: 4px;
    }

    /* Buttons */
    .btn-group {
      display: flex;
      gap: 10px;
      width: 100%;
      justify-content: center;
    }

    .btn {
      background-color: #ec407a;
      color: white;
      border: none;
      padding: 10px 20px; /* Sized for finger taps */
      font-size: 0.95rem;
      font-weight: bold;
      border-radius: 20px;
      cursor: pointer;
      transition: transform 0.15s ease, background-color 0.15s ease;
      box-shadow: 0 3px 8px rgba(236, 64, 122, 0.35);
      touch-action: manipulation;
      min-width: 90px;
    }

    /* Active feedback on mobile touch */
    .btn:active {
      background-color: #d81b60;
      transform: scale(0.95);
    }

    /* Open Envelope State */
    .envelope-wrapper.open .flap {
      transform: rotateX(180deg);
      z-index: 0;
    }

    .envelope-wrapper.open .letter {
      transform: translateY(-115px);
      z-index: 4;
    }

    /* Success Card Overlay */
    .success-card {
      display: none;
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      background: white;
      padding: 25px 30px;
      border-radius: 20px;
      text-align: center;
      box-shadow: 0 15px 35px rgba(0, 0, 0, 0.25);
      z-index: 10;
      width: 85%;
      max-width: 320px;
    }

    .success-card h2 {
      color: #ec407a;
      font-size: 1.6rem;
      margin-bottom: 8px;
    }

    .success-card p {
      color: #555;
      font-size: 1rem;
    }

    /* Animations */
    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-6px); }
    }

    .heart {
      position: fixed;
      font-size: 1.5rem;
      animation: floatUp 3s linear forwards;
      z-index: 9;
      pointer-events: none;
    }

    @keyframes floatUp {
      0% {
        transform: translateY(100vh) scale(0.8);
        opacity: 1;
      }
      100% {
        transform: translateY(-10vh) scale(1.2);
        opacity: 0;
      }
    }
  </style>
</head>
<body>

  <div class="container">
    <div class="instruction" id="instruction">Tap the envelope to open! ✉️</div>

    <div class="envelope-wrapper" id="envelope">
      <div class="envelope">
        <div class="flap"></div>
        <div class="pocket"></div>
        <div class="letter">
          <p>Do you wanna go on a date with august? 💖</p>
          <div class="btn-group">
            <button class="btn" id="btn1">Yes! 💕</button>
            <button class="btn" id="btn2">Yes! 🥰</button>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="success-card" id="successCard">
    <h2>Yay! It's a Date! 🎉</h2>
    <p>August can'wait! ❤️</p>
  </div>

  <script>
    const envelope = document.getElementById('envelope');
    const instruction = document.getElementById('instruction');
    const successCard = document.getElementById('successCard');
    const btn1 = document.getElementById('btn1');
    const btn2 = document.getElementById('btn2');

    let isOpen = false;

    // Mobile-optimized tap listener
    envelope.addEventListener('click', function(e) {
      if (e.target.classList.contains('btn')) return;

      if (!isOpen) {
        envelope.classList.add('open');
        instruction.style.opacity = '0';
        isOpen = true;
      }
    });

    function acceptDate(e) {
      e.stopPropagation(); // Prevents tapping button from toggling envelope

      successCard.style.display = 'block';

      // Launch floating hearts
      for (let i = 0; i < 30; i++) {
        setTimeout(createHeart, i * 100);
      }
    }

    btn1.addEventListener('click', acceptDate);
    btn2.addEventListener('click', acceptDate);

    function createHeart() {
      const heart = document.createElement('div');
      heart.classList.add('heart');
      
      const emojis = ['💖', '💕', '🌸', '✨', '😍'];
      heart.innerText = emojis[Math.floor(Math.random() * emojis.length)];
      
      heart.style.left = Math.random() * 100 + 'vw';
      heart.style.animationDuration = (Math.random() * 2 + 2) + 's';
      
      document.body.appendChild(heart);

      setTimeout(() => {
        heart.remove();
      }, 3500);
    }
  </script>
</body>
</html>
