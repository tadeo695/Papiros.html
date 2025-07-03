<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Papiros Gráfica</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f9f9f9; color: #333; }
    header { background: #fff; padding: 20px; text-align: center; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
    header h1 { margin: 0; color: #333; font-size: 2.5rem; }
    nav { background: #eee; padding: 10px; text-align: center; }
    nav a { margin: 0 15px; text-decoration: none; color: #333; font-weight: bold; }
    section { padding: 40px 20px; max-width: 1000px; margin: auto; }
    h2 { color: #444; border-bottom: 2px solid #ccc; padding-bottom: 5px; }
    .producto { border: 1px solid #ddd; padding: 10px; margin: 10px 0; border-radius: 8px; background: #fff; }
    .galeria img { width: 100px; height: auto; margin: 5px; border-radius: 5px; }
    footer { text-align: center; padding: 20px; background: #eee; font-size: 0.9rem; }
    .boton { display: inline-block; padding: 10px 15px; background: #00BCD4; color: #fff; border-radius: 5px; text-decoration: none; }
  </style>
</head>
<body>
  <header>
    <h1>Papiros Gráfica</h1>
    <p><em>Diseñamos, imprimimos y damos vida a tus ideas</em></p>
  </header>
  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#servicios">Servicios</a>
    <a href="#catalogo">Catálogo</a>
    <a href="#galeria">Galería</a>
    <a href="#nosotros">Sobre Nosotros</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="inicio">
    <h2>Bienvenido</h2>
    <p>En Papiros Gráfica transformamos tus ideas en productos visuales únicos. Con creatividad, calidad y atención personalizada, te acompañamos en cada paso.</p>
  </section>

  <section id="servicios">
    <h2>Servicios</h2>
    <ul>
      <li>Diseño gráfico (logos, flyers, redes sociales)</li>
      <li>Impresión (tarjetas, lonas, stickers)</li>
      <li>Merchandising (tazas, remeras, libretas)</li>
      <li>Artículos promocionales y personalizados</li>
    </ul>
  </section>

  <section id="catalogo">
    <h2>Catálogo de Productos</h2>
    <div class="producto">
      <h3>Tarjetas Personales</h3>
      <p>Diseños personalizados. Impresión frente y dorso. Papeles de alta calidad.</p>
    </div>
    <div class="producto">
      <h3>Stickers</h3>
      <p>Vinilo resistente. Cortes personalizados. Ideales para promociones o packaging.</p>
    </div>
    <div class="producto">
      <h3>Remeras Personalizadas</h3>
      <p>Estampado a pedido. Talles varios. Diseños únicos para eventos o regalos.</p>
    </div>
    <a class="boton" href="#contacto">Solicitar Presupuesto</a>
  </section>

  <section id="galeria">
    <h2>Galería de Trabajos</h2>
    <div class="galeria">
      <img src="https://via.placeholder.com/150" alt="Sticker personalizado">
      <img src="https://via.placeholder.com/150" alt="Tarjeta de presentación">
      <img src="https://via.placeholder.com/150" alt="Remera con diseño">
    </div>
  </section>

  <section id="nosotros">
    <h2>Sobre Nosotros</h2>
    <p>Papiros Gráfica nació con la idea de mezclar arte y servicio. Nos apasiona el diseño y buscamos que cada trabajo tenga identidad propia. Somos un equipo joven, creativo y comprometido con la calidad.</p>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>

    <!-- 🔧 PONÉ TU EMAIL ACÁ -->
    <form action="https://formsubmit.co/TU_CORREO@gmail.com" method="POST">
      <label>Nombre:<br><input type="text" name="nombre" required></label><br><br>
      <label>Email:<br><input type="email" name="email" required></label><br><br>
      <label>Mensaje:<br><textarea name="mensaje" rows="4" required></textarea></label><br><br>
      <input class="boton" type="submit" value="Enviar">
    </form>

    <br>

    <!-- 🔧 PONÉ TU NÚMERO DE WHATSAPP ACÁ -->
    <p>O escribinos por 
      <a class="boton" href="https://wa.me/5491123456789" target="_blank">WhatsApp</a>
    </p>
  </section>

  <footer>
    <p>&copy; 2025 Papiros Gráfica. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
