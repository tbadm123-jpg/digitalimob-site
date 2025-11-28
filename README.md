<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DIGITALIMOB - Imobiliária</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      color: #333;
    }
    header {
      background: #0a3d62;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #0652dd;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1560185007-c5ca9d2c2f71?auto=format&fit=crop&w=1500&q=80') no-repeat center/cover;
      height: 380px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 0 2px 6px rgba(0,0,0,0.6);
      font-size: 2.2rem;
      font-weight: bold;
    }
    .section {
      padding: 40px 20px;
      max-width: 1100px;
      margin: auto;
    }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }
    .card-content {
      padding: 15px;
    }
    .card h3 {
      margin: 0 0 10px;
      color: #0a3d62;
    }
    .btn {
      display: inline-block;
      background: #0a3d62;
      color: white;
      padding: 10px 16px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 10px;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #0a3d62;
      color: white;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <h1>DIGITALIMOB</h1>
    <p>Realizando sonhos, encontrando oportunidades.</p>
  </header>

  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#imoveis">Imóveis</a>
    <a href="#contato">Contato</a>
  </nav>

  <div class="hero">
    Encontre o imóvel perfeito hoje mesmo!
  </div>

  <section id="sobre" class="section">
    <h2>Sobre Nós</h2>
    <p>Somos uma imobiliária especializada em oferecer as melhores oportunidades de compra, venda e repasse de imóveis na região. Atendimento rápido, seguro e sem burocracia!</p>
  </section>

  <section id="imoveis" class="section">
    <h2>Imóveis em Destaque</h2>
    <div class="cards">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1568605114967-8130f3a36994?auto=format&fit=crop&w=800&q=80" />
        <div class="card-content">
          <h3>Casa no Albano</h3>
          <p>3/4 sendo 2 suítes, sala ampla e quintal. R$ 200.000</p>
          <a class="btn" href="#contato">Quero saber mais</a>
        </div>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1570129477492-45c003edd2be?auto=format&fit=crop&w=800&q=80" />
        <div class="card-content">
          <h3>Apartamento na Barra</h3>
          <p>2 quartos, térreo, saldo + chave acessível!</p>
          <a class="btn" href="#contato">Tenho interesse</a>
        </div>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1554995207-c18c203602cb?auto=format&fit=crop&w=800&q=80" />
        <div class="card-content">
          <h3>Casa na Piabeta</h3>
          <p>2/4, garagem, quintal amplo. Chave R$ 40 mil.</p>
          <a class="btn" href="#contato">Ver detalhes</a>
        </div>
      </div>
    </div>
  </section>

  <section id="contato" class="section">
    <h2>Contato</h2>
    <p>Fale com a gente pelo WhatsApp e receba atendimento imediato:</p>
    <a href="https://wa.me/5579991770014" class="btn">📲 Chamar no WhatsApp</a>
  </section>

  <footer>
    © 2025 DIGITALIMOB — Todos os direitos reservados.
  </footer>
</body>
</html>
