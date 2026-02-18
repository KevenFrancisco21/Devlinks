<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DevLinks - Keven</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      background: linear-gradient(135deg, #121212, #1f1f1f);
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .container {
      width: 100%;
      max-width: 350px;
      text-align: center;
    }

    .profile img {
      width: 100px;
      border-radius: 50%;
      border: 3px solid #00ff88;
    }

    .profile h1 {
      margin-top: 10px;
      font-size: 22px;
    }

    .links {
      margin-top: 25px;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }

    .links a {
      text-decoration: none;
      background: #00ff88;
      color: black;
      padding: 12px;
      border-radius: 8px;
      font-weight: bold;
      transition: 0.3s;
    }

    .links a:hover {
      background: #00cc6a;
      transform: scale(1.05);
    }

    footer {
      margin-top: 20px;
      font-size: 12px;
      opacity: 0.7;
    }
  </style>
</head>

<body>

  <div class="container">

    <div class="profile">
      <img src="https://via.placeholder.com/100" alt="Foto">
      <h1>Keven Santos</h1>
      <p>Desenvolvedor em formação 🚀</p>
    </div>

    <div class="links">
      <a href="#">Meu Portfólio</a>
      <a href="#">Meu GitHub</a>
      <a href="#">Meu LinkedIn</a>
      <a href="#">Fale comigo</a>
    </div>

    <footer>
      Feito com ❤️ por Keven
    </footer>

  </div>

</body>
</html>

