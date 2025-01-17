<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chris van Valderen</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: linear-gradient(135deg, #f7f7f7, #ececec);
      font-family: Arial, sans-serif;
      color: #333;
      text-align: center;
    }
    .container {
      padding: 20px;
      box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
      background-color: #fff;
      border-radius: 10px;
      max-width: 500px;
    }
    h1 {
      font-size: 2em;
      margin-bottom: 10px;
    }
    p {
      margin: 0;
      font-size: 1em;
      color: #666;
    }
    .loader {
      margin: 20px 0;
      display: flex;
      justify-content: center;
      gap: 5px;
    }
    .loader div {
      width: 10px;
      height: 10px;
      background-color: #333;
      border-radius: 50%;
      animation: bounce 1.2s infinite;
    }
    .loader div:nth-child(2) {
      animation-delay: 0.2s;
    }
    .loader div:nth-child(3) {
      animation-delay: 0.4s;
    }
    @keyframes bounce {
      0%, 80%, 100% {
        transform: scale(0);
      }
      40% {
        transform: scale(1);
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>We’re Under Construction</h1>
    <p>This site is coming soon! Stay tuned for something amazing.</p>
    <div class="loader">
      <div></div>
      <div></div>
      <div></div>
    </div>
    <p>&copy; 2025 Chris van Valderen</p>
  </div>
</body>
</html>
