<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>InkPrint Studio GT</title>  <!-- Google Fonts -->  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">  <style>
    * { margin:0; padding:0; box-sizing:border-box; }

    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #000, #050b14);
      color: #fff;
    }

    header {
      display:flex;
      justify-content:space-between;
      align-items:center;
      padding:20px 40px;
      background: rgba(0,0,0,0.8);
      position: sticky;
      top:0;
      z-index:1000;
    }

    header img { height:60px; }

    nav a {
      margin-left:20px;
      text-decoration:none;
      color:#00cfff;
      font-weight:600;
      transition:0.3s;
    }

    nav a:hover { color:#fff; }

    .hero {
      height:90vh;
      display:flex;
      flex-direction:column;
      justify-content:center;
      align-items:center;
      text-align:center;
      background: radial-gradient(circle, rgba(0,207,255,0.2), transparent);
    }

    .hero h1 {
      font-size:3rem;
      color:#00cfff;
    }

    .hero p {
      margin-top:10px;
      font-size:1.2rem;
    }

    .btn {
      margin-top:20px;
      padding:12px 25px;
      background:#00cfff;
      color:#000;
      text-decoration:none;
      border-radius:30px;
      font-weight:600;
      transition:0.3s;
    }

    .btn:hover {
      background:#fff;
      transform:scale(1.05);
    }

    .products {
      padding:50px 20px;
    }

    .products h2 {
      text-align:center;
      margin-bottom:30px;
      color:#00cfff;
    }

    .grid {
      display:grid;
      grid-template-columns: repeat(auto-fit, minmax(250px,1fr));
      gap:25px;
    }

    .product {
      background:#0a0f1a;
      border-radius:15px;
      overflow:hidden;
      transition:0.3s;
    }

    .product:hover {
      transform: translateY(-10px);
      box-shadow:0 10px 30px rgba(0,207,255,0.3);
    }

    .product img {
      width:100%;
      height:220px;
      object-fit:cover;
    }

    .product-content {
      padding:15px;
      text-align:center;
    }

    .product-content h3 { margin-bottom:10px; }

    .about {
      padding:60px 20px;
      text-align:center;
      background:#050b14;
    }

    .about h2 { color:#00cfff; }

    footer {
      text-align:center;
      padding:30px;
      background:#000;
      margin-top:30px;
    }

    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25D366;
      color: white;
      padding: 18px;
      border-radius: 50%;
      font-size: 22px;
      text-decoration: none;
      box-shadow:0 5px 15px rgba(0,0,0,0.4);
    }

  </style></head>
<body><header>
  <img src="logo.png">
  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#productos">Productos</a>
    <a href="#nosotros">Nosotros</a>
  </nav>
</header><section class="hero" id="inicio">
  <h1>InkPrint Studio GT</h1>
  <p>Diseños personalizados que destacan</p>
  <a class="btn" href="https://wa.me/502XXXXXXXX">Ordenar ahora</a>
</section><section class="products" id="productos">
  <h2>Nuestros Productos</h2>  <div class="grid"><div class="product">
  <img src="producto1.jpg">
  <div class="product-content">
    <h3>Playera Personalizada</h3>
    <p>Q100</p>
    <a class="btn" href="https://wa.me/502XXXXXXXX">Comprar</a>
  </div>
</div>

<div class="product">
  <img src="producto2.jpg">
  <div class="product-content">
    <h3>Taza Personalizada</h3>
    <p>Q50</p>
    <a class="btn" href="https://wa.me/502XXXXXXXX">Comprar</a>
  </div>
</div>

  </div>
</section><section class="about" id="nosotros">
  <h2>Sobre Nosotros</h2>
  <p>En InkPrint Studio GT creamos productos personalizados de alta calidad para que destaques con tu estilo único.</p>
</section><footer>
  <p>© 2026 InkPrint Studio GT - Todos los derechos reservados</p>
</footer><a class="whatsapp" href="https://wa.me/502XXXXXXXX">💬</a>

</body>
</html>
