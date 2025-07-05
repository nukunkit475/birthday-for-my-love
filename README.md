<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <title>Happy Birthday My Love 🎂</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(#fce3ec, #ffe8d6);
      font-family: 'Sriracha', cursive;
      text-align: center;
      color: #d63384;
      overflow-x: hidden;
    }
    h1 {
      font-size: 2.5em;
      margin-top: 40px;
    }
    p {
      font-size: 1.5em;
      padding: 0 20px;
    }
    .heart {
      position: absolute;
      width: 20px;
      height: 20px;
      background: red;
      transform: rotate(45deg);
      animation: float 5s infinite;
    }
    .heart::before,
    .heart::after {
      content: "";
      position: absolute;
      width: 20px;
      height: 20px;
      background: red;
      border-radius: 50%;
    }
    .heart::before {
      top: -10px;
      left: 0;
    }
    .heart::after {
      top: 0;
      left: -10px;
    }
    @keyframes float {
      0% { transform: translateY(0) rotate(45deg); opacity: 1; }
      100% { transform: translateY(-800px) rotate(45deg); opacity: 0; }
    }
    button {
      margin-top: 30px;
      padding: 10px 20px;
      font-size: 1em;
      background: #ffb3c6;
      border: none;
      border-radius: 10px;
      cursor: pointer;
    }
    #secret {
      display: none;
      margin-top: 20px;
      font-size: 1.2em;
      color: #6f42c1;
    }
  </style>
</head>
<body>

  <h1>สุขสันต์วันเกิดนะคะที่รัก 🎉</h1>
  <p>แม้อยู่ไกล แต่ใจเรายังใกล้กันเสมอ 💖</p>
  <img src="https://i.imgur.com/lOV9V0N.png" width="200" alt="รูปคู่"/>

  <button onclick="document.getElementById('secret').style.display='block'">
    คลิกเพื่อเปิดข้อความลับ 💌
  </button>
  <div id="secret">
    <p>ขอบคุณที่เข้ามาเป็นคนพิเศษของเรา เรารักเธอนะ 🥹</p>
  </div>

  <audio autoplay loop>
    <source src="https://example.com/lovemusic.mp3" type="audio/mpeg">
    เพลงไม่รองรับในเบราว์เซอร์นี้
  </audio>

  <!-- หัวใจลอย -->
  <script>
    for (let i = 0; i < 30; i++) {
      let heart = document.createElement("div");
      heart.className = "heart";
      heart.style.left = Math.random() * 100 + "vw";
      heart.style.animationDuration = 3 + Math.random() * 3 + "s";
      document.body.appendChild(heart);
    }
    <img src="sticker_love.png" width="150" style="position: fixed; bottom: 20px; right: 20px; border-radius: 50%;" alt="sticker">

  </script>
  

</body>
</html>
