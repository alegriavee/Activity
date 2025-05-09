<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Veejay Alegria Adame</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@600&family=Roboto&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      background: linear-gradient(to right, #2c3e50, #3498db);
      font-family: 'Roboto', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
    }
    .intro-container {
      text-align: center;
      color: white;
      animation: fadeIn 2s ease-in-out;
    }
    h1 {
      font-size: 3em;
      font-family: 'Montserrat', sans-serif;
      background: linear-gradient(90deg, #f39c12, #e74c3c);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      animation: colorShift 5s infinite alternate;
    }
    p {
      font-size: 1.2em;
      margin-top: 10px;
      opacity: 0.8;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes colorShift {
      0% { background-position: 0% 50%; }
      100% { background-position: 100% 50%; }
    }
  </style>
</head>
<body>
  <div class="intro-container">
    <h1>Hi, I am Veejay Alegria Adame</h1>
    <p>Welcome to my awesome corner of the web.</p>
  </div>
</body>
</html>
