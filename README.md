<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Núcleo Electrónico</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; }
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(to bottom right, #eef2f3, #8e9eab);
      color: #333;
    }
    header {
      background: linear-gradient(to right, #003366, #00509e);
      color: white;
      padding: 40px 20px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0,0,0,0.2);
    }
    nav {
      background-color: #004080;
      padding: 15px;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    nav a {
      color: #fff;
      margin: 10px 15px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffd700;
    }
    section {
      padding: 40px 20px;
    }
    h2 {
      color: #002244;
      border-bottom: 2px solid #0074D9;
      padding-bottom: 10px;
    }
    .product {
      background: white;
      margin: 20px 0;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }
    .product:hover {
      transform: scale(1.02);
    }
    ul li {
      margin: 10px 0;
    }
    .contact-info p {
      margin: 8px 0;
    }
    footer {
      background-color: #002b5c;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .btn {
      display: inline-block;
      padding: 10px 20px;
      background-color: #0074D9;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      transition: background 0.3s;
    }
    .btn:hover {
      background-color: #005bb5;
    }
  </style>
</head>
<body>
  <header>
    <h1>🔌 Núcleo Electrónico</h1>
    <p>Tu tienda de confianza en tecnología, computación y electrónica</p>
  </header>

  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#productos">Productos</a>
    <a href="#promociones">Promociones</a>
    <a href="#servicios">Servicios</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="inicio">
    <h2>Bienvenido</h2>
    <p style="font-size: 1.2em;">Ofrecemos lo mejor en innovación tecnológica para que tu día a día esté siempre conectado.</p>
    <a class="btn" href="#productos">Ver productos</a>
  </section>

  <section id="productos">
    <h2>Productos Destacados</h2>
    <div class="product">
      <h3>🖥️ Computadora Ryzen 7 + RTX 5070</h3>
      <p><strong>Precio:</strong> $33,000 MXN</p>
      <p>✔️ 32 GB RAM | 1 TB SSD | Ideal para ingeniería y renderizado</p>
    </div>
    <div class="product">
      <h3>🎧 Audífonos Bluetooth Pro</h3>
      <p><strong>Precio:</strong> $1,299 MXN</p>
      <p>✔️ Cancelación de ruido, batería de 20 hrs</p>
    </div>
    <div class="product">
      <h3>🔋 Cargador Rápido Universal 65W</h3>
      <p><strong>Precio:</strong> $599 MXN</p>
      <p>✔️ Compatible con laptop, tablet y celular</p>
    </div>
    <div class="product">
      <h3>💡 Foco LED Inteligente WiFi</h3>
      <p><strong>Precio:</strong> $349 MXN</p>
      <p>✔️ Control con app, colores RGB, ahorro de energía</p>
    </div>
  </section>

  <section id="promociones">
    <h2>🎉 Promociones</h2>
    <ul>
      <li>✅ 20% de descuento en computadoras y accesorios</li>
      <li>✅ Instalación gratis en compras mayores a $2,000</li>
      <li>✅ Participa en la rifa de una bocina Bluetooth</li>
    </ul>
  </section>

  <section id="servicios">
    <h2>🔧 Servicios</h2>
    <ul>
      <li>🛠️ Reparación de laptops, celulares y consolas</li>
      <li>📷 Instalación de cámaras de seguridad</li>
      <li>🧰 Armado de PC personalizada</li>
      <li>🧑‍💻 Asesoría técnica y actualización de equipos</li>
    </ul>
  </section>

  <section id="contacto">
    <h2>📞 Contacto</h2>
    <div class="contact-info">
      <p><strong>Dirección:</strong> Av. Tecnología #123, Ciudad Electrónica, MX</p>
      <p><strong>WhatsApp:</strong> 55 1234 5678</p>
      <p><strong>Email:</strong> contacto@nucleoelectronico.com.mx</p>
      <p><strong>Redes:</strong> Facebook | Instagram | TikTok</p>
      <p><strong>Horarios:</strong> Lunes a Sábado: 10:00 AM - 7:00 PM | Domingo: Cerrado</p>
    </div>
  </section>

  <footer>
    © 2025 Núcleo Electrónico. Todos los derechos reservados.
  </footer>
</body>
</html>
