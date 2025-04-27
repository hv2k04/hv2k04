<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Pizzaria Delícia</title>
  <style>
.whatsapp-button {
  position: fixed;
  bottom: 20px;
  right: 20px;
  z-index: 100;
}

    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #fff8f0;
    }
    header {
      background-color: #d62828;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #f77f00;
      padding: 10px;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .container {
      padding: 20px;
    }
    .pizza {
      background-color: #ffe5b4;
      padding: 15px;
      margin-bottom: 20px;
      border-radius: 8px;
      display: flex;
      gap: 15px;
      align-items: center;
    }
    .pizza img {
      width: 150px;
      border-radius: 10px;
    }
    footer {
      background-color: #003049;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

<header>
  <h1>Pizzaria Delícia</h1>
  <p>A melhor pizza da cidade!</p>
</header>

<nav>
  <a href="#">Início</a>
  <a href="#">Cardápio</a>
  <a href="#">Contato</a>
</nav>

<div class="container">
  <h2>Cardápio</h2>

  <div class="pizza">
    <img src="https://images.unsplash.com/photo-1601924928595-d2d49f3fe8f3?w=400" alt="Pizza de Calabresa">
    <div>
      <h3>Pizza de Calabresa</h3>
      <p>Molho de tomate, mussarela, calabresa e cebola roxa.</p>
    </div>
  </div>

  <div class="pizza">
    <img src="https://images.unsplash.com/photo-1585238342028-3edee0bd66a5?w=400" alt="Pizza Margherita">
    <div>
      <h3>Pizza Margherita</h3>
      <p>Molho de tomate, mussarela, tomate fresco e manjericão.</p>
    </div>
  </div>

  <div class="pizza">
    <img src="https://images.unsplash.com/photo-1601925261924-02e5082bdf49?w=400" alt="Pizza Quatro Queijos">
    <div>
      <h3>Pizza Quatro Queijos</h3>
      <p>Mussarela, gorgonzola, parmesão e catupiry.</p>
    </div>
  </div>

</div>

<footer>
  <p>&copy; 2025 Pizzaria Delícia - Todos os direitos reservados.</p>
</footer>

<a href="https://wa.me/5599999999999?text=Olá%2C%20quero%20fazer%20um%20pedido%20🍕" 
   class="whatsapp-button" 
   target="_blank" 
   title="Fale conosco no WhatsApp">
  <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" 
       alt="WhatsApp" 
       style="width:60px;">
</a>

</body>
</html>
