
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Minha Empresa</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background-color: #f4f4f4;
    }

    header {
      background: #333;
      color: #fff;
      padding: 15px 0;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      color: #00bcd4;
    }

    section {
      padding: 40px;
      text-align: center;
    }

    .home {
      background: #00bcd4;
      color: white;
    }

    .produtos, .contato {
      background: white;
      margin: 20px;
      border-radius: 10px;
      padding: 30px;
    }

    .card {
      background: #eee;
      margin: 15px;
      padding: 20px;
      border-radius: 8px;
      display: inline-block;
      width: 200px;
    }

    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <!-- MENU -->
  <header>
    <nav>
      <a href="#home">Início</a>
      <a href="#produtos">Produtos</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <!-- TELA INICIAL -->
  <section id="home" class="home">
    <h1>Bem-vindo à Minha Empresa</h1>
    <p>Oferecendo os melhores serviços para você!</p>
  </section>

  <!-- PRODUTOS / SERVIÇOS -->
  <section id="produtos" class="produtos">
    <h2>Nossos Serviços</h2>

    <div class="card">
      <h3>Serviço 1</h3>
      <p>Descrição do serviço.</p>
    </div>

    <div class="card">
      <h3>Serviço 2</h3>
      <p>Descrição do serviço.</p>
    </div>

    <div class="card">
      <h3>Serviço 3</h3>
      <p>Descrição do serviço.</p>
    </div>
  </section>

  <!-- CONTATO -->
  <section id="contato" class="contato">
    <h2>Contato</h2>
    <p>Email: contato@empresa.com</p>
    <p>Telefone: (00) 00000-0000</p>
  </section>

  <!-- RODAPÉ -->
  <footer>
    <p>© 2026 Minha Empresa - Todos os direitos reservados</p>
  </footer>

</body>
</html>
