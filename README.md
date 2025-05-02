<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Catálogo - Farmácia de Manipulação</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    header {
      background-color: #00695c;
      color: #fff;
      padding: 1rem;
      text-align: center;
    }
    .container {
      padding: 2rem;
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .card {
      background-color: white;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      padding: 1rem;
    }
    .card h2 {
      margin-top: 0;
      font-size: 1.2rem;
    }
    .card p {
      color: #555;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background-color: #eeeeee;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Catálogo de Produtos - Farmácia</h1>
  </header>

  <div class="container">
    <div class="card">
      <h2>Fortaliz Power</h2>
      <p>Auxilia na queda de cabelo, fortalece unhas e melhora a saúde da pele com vitaminas essenciais.</p>
      <strong>R$ 50,00</strong>
    </div>
    <div class="card">
      <h2>Emagrecedor Extra Forte</h2>
      <p>Com ativos naturais que auxiliam no metabolismo e redução de gordura corporal.</p>
      <strong>R$ 70,00</strong>
    </div>
    <div class="card">
      <h2>Ômega do Coração</h2>
      <p>Suplemento com alta concentração de ômega 3, ideal para cuidar da saúde cardiovascular.</p>
      <strong>R$ 210,00</strong>
    </div>
  </div>

  <footer>
    Farmácia de Manipulação © 2025. Todos os direitos reservados.
  </footer>
</body>
</html>
