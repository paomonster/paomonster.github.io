<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Will You Be My Valentine?</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    .card {
      background: white;
      padding: 40px 30px;
      border-radius: 20px;
      box-shadow: 0 20px 40px rgba(0,0,0,0.15);
      text-align: center;
      max-width: 350px;
      width: 90%;
    }
    h1 {
      color: #e63946;
      margin-bottom: 10px;
    }
    p {
      color: #555;
      margin-bottom: 30px;
    }
    .buttons {
      display: flex;
      justify-content: center;
      gap: 20px;
    }
    button {
      border: none;
      padding: 12px 24px;
      font-size: 16px;
      border-radius: 30px;
      cursor: pointer;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }
    button:hover {
      transform: translateY(-2px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.2);
    }
    .yes {
      background: #e63946;
      color: white;
    }
    .no {
      background: #f1f1f1;
      color: #333;
    }
    .message {
      margin-top: 25px;
      font-size: 18px;
      color: #e63946;
      display: none;
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>💖 Will you be my Valentine? 💖</h1>
    <p>I promise smiles, laughs, and lots of love.</p>
    <div class="buttons">
      <button class="yes" onclick="sayYes()">Yes</button>
      <button class="no" onclick="sayNo()">No</button>
    </div>
    <div class="message" id="message"></div>
  </div>

  <script>
    function sayYes() {
      const msg = document.getElementById('message');
      msg.style.display = 'block';
      msg.textContent = 'Yay! 💕 Best Valentine ever!';
    }

    function sayNo() {
      const msg = document.getElementById('message');
      msg.style.display = 'block';
      msg.textContent = 'Are you sure? 😢 I still think you\'re amazing.';
    }
  </script>
</body>
</html>
