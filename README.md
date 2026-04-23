<!DOCTYPE html><html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MB Pinturas</title>
  <meta name="description" content="MB Pinturas - Especialistas em pintura residencial, comercial e acabamentos com qualidade e confiança.">  <!-- Favicon (coloque sua logo com nome favicon.png na mesma pasta) -->  <link rel="icon" href="favicon.png" type="image/png">  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; }
    body { line-height: 1.6; }

    header {
      background: #0a3d62;
      color: #fff;
      padding: 15px 20px;
      position: fixed;
      width: 100%;
      top: 0;
      z-index: 1000;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .logo img {
      width: 45px;
      height: 45px;
      border-radius: 50%;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      font-size: 14px;
    }

    .menu-toggle {
      display: none;
      font-size: 24px;
      cursor: pointer;
    }

    .hero {
      height: 100vh;
      background: url('https://images.unsplash.com/photo-1581578731548-c64695cc6952') center/cover no-repeat;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
      padding: 20px;
    }

    .hero h2 { font-size: 40px; margin-bottom: 20px; }

    .btn {
      background: #f39c12;
      padding: 12px 25px;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      display: inline-block;
      margin-top: 10px;
    }

    section { padding: 80px 20px; max-width: 1100px; margin: auto; }
    h2 { margin-bottom: 20px; color: #0a3d62; }

    .services, .gallery, .testimonials {
      display: grid;
      gap: 20px;
    }

    .services {
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    }

    .card {
      background: #f4f4f4;
      padding: 20px;
      border-radius: 8px;
      text-align: center;
    }

    .gallery {
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    }

    .gallery img {
      width: 100%;
      border-radius: 8px;
    }

    .testimonials {
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    }

    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    footer {
      background: #0a3d62;
      color: white;
      text-align: center;
      padding: 20px;
    }

    .whatsapp-float {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25D366;
      color: white;
      padding: 15px;
      border-radius: 50%;
      text-decoration: none;
      font-size: 20px;
    }

    /* RESPONSIVO */
    @media(max-width: 768px) {
      nav ul {
        position: absolute;
        top: 60px;
        right: 0;
        background: #0a3d62;
        flex-direction: column;
        width: 200px;
        display: none;
        padding: 20px;
      }

      nav ul.active {
        display: flex;
      }

      .menu-toggle {
        display: block;
      }

      .hero h2 {
        font-size: 26px;
      }
    }
  </style></head><body><header>
  <nav>
    <div class="logo">
      <img src="logo.png" alt="MB Pinturas">
      <strong>MB Pinturas</strong>
    </div><div class="menu-toggle" onclick="toggleMenu()">☰</div>

<ul id="menu">
  <li><a href="#home">Home</a></li>
  <li><a href="#sobre">Sobre</a></li>
  <li><a href="#servicos">Serviços</a></li>
  <li><a href="#galeria">Galeria</a></li>
  <li><a href="#contato">Contato</a></li>
</ul>

  </nav>
</header><section class="hero" id="home">
  <div>
    <h2>Transformando ambientes com qualidade e confiança</h2>
    <a href="https://wa.me/5542999690957" class="btn">Solicite seu orçamento</a>
  </div>
</section><section id="sobre">
  <h2>Sobre a Empresa</h2>
  <p>A MB Pinturas é especializada em pintura residencial, comercial e acabamentos em geral. Trabalhamos com dedicação, qualidade e compromisso.</p>
</section><section id="servicos">
  <h2>Serviços</h2>
  <div class="services">
    <div class="card">Pintura Residencial</div>
    <div class="card">Pintura Comercial</div>
    <div class="card">Pintura Interna e Externa</div>
    <div class="card">Acabamentos</div>
    <div class="card">Pequenas Reformas</div>
  </div>
</section><section id="galeria">
  <h2>Galeria</h2>
  <div class="gallery">
    <img src="https://images.unsplash.com/photo-1562259949-e8e7689d7828">
    <img src="https://images.unsplash.com/photo-1581092334651-ddf26d9a09d0">
    <img src="https://images.unsplash.com/photo-1503387762-592deb58ef4e">
  </div>
</section><section class="testimonials">
  <h2>Depoimentos</h2>
  <div class="card">Excelente serviço!</div>
  <div class="card">Muito profissional!</div>
</section><section id="contato">
  <h2>Contato</h2>
  <form>
    <input type="text" placeholder="Nome" required>
    <input type="tel" placeholder="Telefone" required>
    <textarea placeholder="Mensagem" required></textarea>
    <button class="btn" type="submit">Enviar</button>
  </form>
</section><footer>
  <p>MB Pinturas © 2026</p>
</footer><a class="whatsapp-float" href="https://wa.me/5542999690957">💬</a>

<script>
function toggleMenu() {
  document.getElementById('menu').classList.toggle('active');
}
</script></body>
</html>
