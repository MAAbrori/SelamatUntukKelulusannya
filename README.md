<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Selamat Kelulusan Sayang</title>
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
  <style>
    body {
      background-color: #fb64b4;
      font-family: 'Segoe UI', sans-serif;
      text-align: center;
      padding: 50px;
      color: #ffffff;
    }

    h1 {
      font-size: 3em;
      margin-bottom: 20px;
    }

    .emoji {
      font-size: 2.5rem;
      animation: bounce 2s infinite;
      display: inline-block;
    }

    .heart {
      animation: pulse 1.5s infinite;
      color: red;
    }

    .message {
      font-size: 1.5em;
      margin-top: 30px;
      line-height: 1.8;
    }

    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }

    @keyframes pulse {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }
  </style>
</head>
<body>
  <h1 data-aos="fade-down">🎓 Selamat Kelulusan Sayang! 🎉</h1>

  <div class="emoji" data-aos="zoom-in">💐</div>
  <div class="emoji" data-aos="zoom-in" data-aos-delay="300">🎊</div>
  <div class="emoji" data-aos="zoom-in" data-aos-delay="600">❤️</div>

  <div class="message" data-aos="fade-up" data-aos-delay="900">
    Aku bangga banget sama kamu, sayang. <br>
    Semua kerja kerasmu akhirnya terbayar 🎓<br>
    Jangan pernah berhenti bermimpi, karena masa depanmu cerah sekali! <br>
    💖 Aku akan selalu ada mendukungmu 💖<br>
    <span class="heart">💞</span> Love you always! <span class="heart">💞</span>
  </div>

  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init();
  </script>
</body>
</html>
