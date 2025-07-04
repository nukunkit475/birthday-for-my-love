<script>
    for (let i = 0; i < 30; i++) {
      let heart = document.createElement("div");
      heart.className = "heart";
      heart.style.left = Math.random() * 100 + "vw";
      heart.style.animationDuration = 3 + Math.random() * 3 + "s";
      document.body.appendChild(heart);
    }
  </script>
