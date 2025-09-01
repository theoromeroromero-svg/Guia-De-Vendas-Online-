<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Minha Loja Online</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
      color: #333;
    }
    header {
      background: #007bff;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    .produtos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
      padding: 2rem;
    }
    .card {
      background: white;
      border-radius: 10px;
      padding: 1rem;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
      transition: 0.3s;
    }
    .card:hover {
      transform: scale(1.05);
    }
    .card img {
      max-width: 100%;
      border-radius: 8px;
    }
    .card h3 {
      margin: 0.5rem 0;
    }
    .preco {
      font-size: 1.2rem;
      font-weight: bold;
      color: #28a745;
    }
    button {
      margin-top: 0.5rem;
      padding: 0.6rem 1rem;
      border: none;
      border-radius: 5px;
      background: #007bff;
      color: white;
      cursor: pointer;
      transition: 0.3s;
    }
    button:hover {
      background: #0056b3;
    }
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Bem-vindo à Minha Loja Online</h1>
    <p>Ofertas exclusivas só hoje!</p>
  </header>

  <section class="produtos">
    <div class="card">
      <img src="https://via.placeholder.com/250" alt="Produto 1">
      <h3>Produto 1</h3>
      <p class="preco">R$ 99,90</p>
      <button>Comprar</button>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/250" alt="Produto 2">
      <h3>Produto 2</h3>
      <p class="preco">R$ 149,90</p>
      <button>Comprar</button>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/250" alt="Produto 3">
      <h3>Produto 3</h3>
      <p class="preco">R$ 199,90</p>
      <button>Comprar</button>
    </div>
  </section>

  <footer>
    <p>Minha Loja Online © 2025 — Todos os direitos reservados</p>
  </footer>
</body>
</html>
