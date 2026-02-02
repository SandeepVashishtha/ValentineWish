# Valentine Wish 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>For You ❤️</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      background: linear-gradient(135deg, #ff758c, #ff7eb3);
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: "Segoe UI", sans-serif;
    }

    .card {
      background: white;
      padding: 35px;
      border-radius: 20px;
      text-align: center;
      max-width: 360px;
      box-shadow: 0 15px 30px rgba(0,0,0,0.25);
    }

    h1 {
      color: #e63946;
      margin-bottom: 10px;
    }

    p {
      color: #333;
      font-size: 16px;
      margin: 10px 0;
    }

    .heart {
      font-size: 40px;
      animation: beat 1s infinite;
      margin: 15px 0;
    }

    button {
      margin-top: 15px;
      padding: 10px 20px;
      border: none;
      border-radius: 25px;
      background: #e63946;
      color: white;
      font-size: 15px;
      cursor: pointer;
    }

    button:hover {
      background: #d62839;
    }

    @keyframes beat {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.3); }
    }
  </style>
</head>
<body>

  <div class="card">
    <h1>Hey My Love 💕</h1>
    <p>I just want you to know something...</p>
    <p>You make my life brighter every single day.</p>
    <div class="heart">❤️</div>
    <p id="secret" style="display:none;">
      I love you more than words can ever explain 😘  
      You are my happiness, my peace, my everything.
    </p>
    <button onclick="showLove()">Click for Surprise 💝</button>
  </div>

  <script>
    function showLove() {
      document.getElementById("secret").style.display = "block";
    }
  </script>

</body>
</html>

