<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shreedhar Kulkarni | Fullstack Developer</title>
  <style>
    /* Reset & Basic */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #2c3e50, #3498db);
      color: #fff;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 20px;
    }
    .card {
      background: rgba(0, 0, 0, 0.6);
      padding: 40px;
      border-radius: 20px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.4);
      max-width: 500px;
      width: 100%;
      animation: fadeIn 1.2s ease-in-out;
    }
    h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
      color: #f1c40f;
    }
    h2 {
      font-size: 1.5rem;
      margin-bottom: 20px;
      color: #ecf0f1;
    }
    p {
      font-size: 1rem;
      margin-bottom: 30px;
    }
    button {
      padding: 12px 24px;
      border: none;
      border-radius: 25px;
      background: #f39c12;
      color: #fff;
      font-size: 1rem;
      cursor: pointer;
      transition: 0.3s;
    }
    button:hover {
      background: #d35400;
      transform: scale(1.05);
    }
    footer {
      margin-top: 20px;
      font-size: 0.9rem;
      color: #bdc3c7;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Shreedhar Kulkarni</h1>
    <h2>Fullstack Developer</h2>
    <p>Working at <strong>Punarapi Technologies</strong>, Bangalore 🚀</p>
    <button onclick="sayHello()">Say Hi 👋</button>
    <footer>© 2025 Shreedhar Kulkarni</footer>
  </div>

  <script>
    function sayHello() {
      alert("Hello, I’m Shreedhar Kulkarni 👋\nFullstack Developer @ Punarapi Technologies, Bangalore.");
    }
  </script>
</body>
</html>
