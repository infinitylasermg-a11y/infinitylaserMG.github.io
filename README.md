
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Infinity Láser MG | Corte láser en Bogotá</title>
  <style>
    :root {
      --primary: #0b2c5f;
      --primary-2: #153d7a;
      --accent: #25d366;
      --bg: #f5f7fb;
      --text: #1e293b;
      --muted: #64748b;
      --white: #ffffff;
      --shadow: 0 10px 30px rgba(11, 44, 95, 0.12);
      --radius: 18px;
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    .container {
      width: min(1120px, 92%);
      margin: 0 auto;
    }

    header {
      background: linear-gradient(135deg, var(--primary), var(--primary-2));
      color: var(--white);
      padding: 18px 0;
      position: sticky;
      top: 0;
      z-index: 20;
      box-shadow: 0 4px 16px rgba(0, 0, 0, 0.08);
    }

    .nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 18px;
      flex-wrap: wrap;
    }

    .brand {
      font-size: 1.4rem;
      font-weight: bold;
      letter-spacing: 0.5px;
    }

    .nav a {
      color: var(--white);
      text-decoration: none;
      margin-left: 18px;
      font-size: 0.95rem;
    }

    .hero {
      padding: 72px 0 56px;
      background: linear-gradient(180deg, #eaf0fb 0%, #f5f7fb 100%);
    }

    .hero-grid {
      display: grid;
      grid-template-columns: 1.2fr 0.8fr;
      gap: 32px;
      align-items: center;
    }

    .badge {
      display: inline-block;
      background: rgba(11, 44, 95, 0.08);
      color: var(--primary);
      padding: 8px 14px;
      border-radius: 999px;
      font-size: 0.9rem;
      font-weight: bold;
      margin-bottom: 14px;
    }

    h1 {
      font-size: clamp(2rem, 5vw, 3.5rem);
      line-height: 1.1;
      margin: 0 0 16px;
      color: var(--primary);
    }

    .hero p {
      font-size: 1.08rem;
      color: var(--muted);
      margin-bottom: 24px;
      max-width: 640px;
    }

    .btns {
      display: flex;
      flex-wrap: wrap;
      gap: 14px;
    }

    .btn {
      display: inline-block;
      padding: 14px 22px;
      border-radius: 12px;
      text-decoration: none;
      font-weight: bold;
      transition: transform 0.2s ease, opacity 0.2s ease;
    }

    .btn:hover { transform: translateY(-2px); }

    .btn-primary {
      background: var(--accent);
      color: var(--white);
    }

    .btn-secondary {
      background: var(--white);
      color: var(--primary);
      border: 1px solid rgba(11, 44, 95, 0.12);
      box-shadow: var(--shadow);
    }

    .hero-card {
      background: var(--white);
      border-radius: 24px;
      padding: 28px;
      box-shadow: var(--shadow);
    }

    .hero-card h3 {
      margin-top: 0;
      color: var(--primary);
    }

    .mini-list {
      padding: 0;
      margin: 18px 0 0;
      list-style: none;
    }

    .mini-list li {
      padding: 10px 0;
      border-bottom: 1px solid #e5e7eb;
    }

    section {
      padding: 56px 0;
    }

    .section-title {
      text-align: center;
      margin-bottom: 32px;
    }

    .section-title h2 {
      font-size: 2rem;
      margin-bottom: 8px;
      color: var(--primary);
    }

    .section-title p {
      color: var(--muted);
      max-width: 720px;
      margin: 0 auto;
    }

    .grid-3 {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 22px;
    }

    .card {
      background: var(--white);
      padding: 24px;
      border-radius: var(--radius);
      box-shadow: var(--shadow);
    }

    .product-btn {
      display: inline-block;
      margin-top: 12px;
      background: var(--accent);
      color: var(--white);
      padding: 10px 16px;
      border-radius: 10px;
      text-decoration: none;
      font-weight: bold;
    }

    .card h3 {
      margin-top: 0;
      color: var(--primary);
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 18px;
    }

    .gallery-item {
      background: var(--white);
      border-radius: var(--radius);
      min-height: 190px;
      padding: 24px;
      box-shadow: var(--shadow);
      display: flex;
      align-items: end;
      font-weight: bold;
      color: var(--primary);
      background-image: linear-gradient(135deg, rgba(11, 44, 95, 0.08), rgba(21, 61, 122, 0.18));
    }

    .product-image {
      width: 100%;
      border-radius: 12px;
      margin-bottom: 12px;
      aspect-ratio: 4 / 5;
      object-fit: cover;
      object-position: center;
      background: #f8fafc;
    }

    .rotate-right {
      transform: rotate(90deg);
      transform-origin: center;
    }

    .rotate-left {
      transform: rotate(-90deg);
      transform-origin: center;
    }

    .video-frame {
      width: 100%;
      border-radius: 12px;
      background: #000;
    }

    .cta {
      background: linear-gradient(135deg, var(--primary), var(--primary-2));
      color: var(--white);
      border-radius: 26px;
      padding: 42px;
      text-align: center;
      box-shadow: var(--shadow);
    }

    .cta h2, .cta p { color: var(--white); }

    footer {
      background: #081f44;
      color: #dbe6f7;
      padding: 30px 0;
      margin-top: 30px;
    }

    footer p {
      margin: 6px 0;
      text-align: center;
    }

    @media (max-width: 900px) {
      .hero-grid,
      .grid-3,
      .gallery {
        grid-template-columns: 1fr;
      }

      .nav {
        justify-content: center;
      }

      .nav-links {
        text-align: center;
      }

      .nav a {
        margin: 0 10px;
      }

      .hero {
        padding-top: 48px;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <div class="brand" style="display:flex; align-items:center; gap:14px;"><img src="img 2/p00.png" alt="Logo Infinity Láser MG" style="width:78px; height:78px; object-fit:contain; background:white; border-radius:16px; padding:8px; box-shadow:0 8px 24px rgba(0,0,0,0.12);"> <span>Infinity Láser MG</span></div>
      <div class="nav-links">
        <a href="#servicios">Servicios</a>
        <a href="#trabajos">Catálogo</a>
        <a href="#contacto">Contacto</a>
      </div>
    </div>
  </header>

  <section class="hero">
    <div class="container hero-grid">
      <div>
        <span class="badge">Corte láser en Bogotá</span>
        <h1>Precisión, diseño y calidad para cada proyecto</h1>
        <p>
          En <strong>Infinity Láser MG</strong> ofrecemos soluciones de corte láser para piezas personalizadas,
          trabajos decorativos, producción por volumen y proyectos a medida. Convertimos tus ideas en resultados
          profesionales con acabados limpios y exactos.
        </p>
        <div class="btns">
          <a class="btn btn-primary" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20un%20trabajo%20de%20corte%20l%C3%A1ser%20con%20Infinity%20L%C3%A1ser%20MG">Cotizar por WhatsApp</a>
          <a class="btn btn-secondary" href="#servicios">Ver servicios</a>
        </div>
      </div>

      <div class="hero-card">
        <div style="text-align:center; margin-bottom:18px;"><img src="p3.png" alt="Logo Infinity Láser MG" style="max-width:240px; width:100%; object-fit:contain; background:white; border-radius:20px; padding:10px; box-shadow:0 8px 24px rgba(0,0,0,0.08);"></div>
        <h3>¿Qué hacemos?</h3>
        <p>Trabajamos proyectos personalizados para clientes, negocios y emprendimientos.</p>
        <ul class="mini-list">
          <li>Corte láser en MDF y otros materiales</li>
          <li>Grabado láser de alta precisión</li>
          <li>Diseños personalizados</li>
          <li>Producción en cantidad</li>
        </ul>
      </div>
    </div>
  </section>

  <section id="servicios">
    <div class="container">
      <div class="section-title">
        <h2>Servicios</h2>
        <p>Soluciones pensadas para proyectos personalizados, decorativos, comerciales y de producción.</p>
      </div>
      <div class="grid-3">
        <div class="card">
          <h3>Corte láser</h3>
          <p>Realizamos cortes precisos para piezas decorativas, letras, cajas, señalización y más.</p>
        </div>
        <div class="card">
          <h3>Grabado láser</h3>
          <p>Personalizamos superficies con acabados limpios y detallados para productos y recuerdos.</p>
        </div>
        <div class="card">
          <h3>Diseños a medida</h3>
          <p>Adaptamos cada trabajo según tu idea, necesidad o referencia visual.</p>
        </div>
      </div>
    </div>
  </section>

  <section>
    <div class="container">
      <div class="section-title">
        <h2>¿Por qué elegirnos?</h2>
        <p>Nos enfocamos en entregar un servicio confiable, rápido y con excelente terminación.</p>
      </div>
      <div class="grid-3">
        <div class="card">
          <h3>Alta precisión</h3>
          <p>Cada detalle cuenta. Trabajamos con cortes definidos y acabados profesionales.</p>
        </div>
        <div class="card">
          <h3>Atención personalizada</h3>
          <p>Te acompañamos desde la idea inicial hasta la cotización y producción final.</p>
        </div>
        <div class="card">
          <h3>Entregas ágiles</h3>
          <p>Buscamos tiempos de respuesta rápidos para que tu proyecto avance sin demoras.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="trabajos">
    <div class="container">
      <div class="section-title">
        <h2>Catálogo de trabajos</h2>
        <p>Organizamos nuestros productos por categorías para mostrar mejor los trabajos personalizados, recuerdos, decoración, detalles para eventos y piezas promocionales.</p>
      </div>

      <div style="display:grid; gap:42px;">
        <div>
          <h3 style="color: var(--primary); margin-bottom: 18px;">Navidad y portavelas personalizados</h3>
          <div class="gallery">
            <div class="card"><img src="WhatsApp Image 2025-11-24 at 6.20.33 PM.jpeg" alt="Adorno navideño personalizado" style="width:100%; border-radius:12px; margin-bottom:12px;"><strong>Adornos navideños</strong><p>Modelos circulares con nombre personalizado, ideales para regalos y decoración de temporada.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20adornos%20navide%C3%B1os%20personalizados">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 2.21.16 PM (7).jpeg" alt="Adorno navideño Dariana" class="product-image"><strong>Adornos con nombre</strong><p>Piezas decorativas en MDF o acrílico con corte fino y excelente presentación.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20adornos%20con%20nombre">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 2.21.16 PM (6).jpeg" alt="Portavela promocional Yaya Cars" class="product-image"><strong>Portavelas promocionales</strong><p>Diseños funcionales con nombre, marca o mensaje publicitario personalizado.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20portavelas%20promocionales">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 2.21.16 PM (5).jpeg" alt="Portavelas Yaya Cars personalizados" class="product-image"><strong>Publicidad en MDF</strong><p>Detalles creativos para negocios, campañas, recordatorios y eventos corporativos.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20publicidad%20en%20MDF">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 2.21.16 PM (4).jpeg" alt="Portavelas encendidos personalizados" class="product-image"><strong>Centros de mesa</strong><p>Opciones decorativas y personalizadas para reuniones, celebraciones y ambientación.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20centros%20de%20mesa%20personalizados">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 2.21.15 PM.jpeg" alt="Esferas navideñas colgantes" class="product-image"><strong>Esferas colgantes</strong><p>Adornos navideños livianos con nombre personalizado para árbol o decoración interior.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20esferas%20colgantes%20personalizadas">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 2.21.15 PM (1).jpeg" alt="Adornos circulares con base" class="product-image"><strong>Modelos con base</strong><p>Diseños para exhibir sobre mesa, escritorios o zonas decorativas.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20modelos%20con%20base">Cotizar por WhatsApp</a></div>
          </div>
        </div>

        <div>
          <h3 style="color: var(--primary); margin-bottom: 18px;">Recuerdos y eventos</h3>
          <div class="gallery">
            <div class="card"><img src="WhatsApp Image 2026-02-01 at 12.43.09 PM.jpeg" alt="Recuerdo de bautizo en corte láser" class="product-image"><strong>Recuerdos para bautizo</strong><p>Diseños personalizados para celebraciones, recuerdos y detalles especiales.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20recuerdos%20para%20bautizo">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 2.21.15 PM (3).jpeg" alt="Recuerdos de bautizo en serie" class="product-image"><strong>Producción por cantidad</strong><p>Elaboración de recuerdos en serie con nombres, fechas y textos personalizados.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20producci%C3%B3n%20por%20cantidad">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 2.21.15 PM (2).jpeg" alt="Recuerdos de bautizo sobre mesa" class="product-image"><strong>Detalles para eventos</strong><p>Opciones especiales para bautizos, comuniones, cumpleaños y fechas memorables.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20detalles%20para%20eventos">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 1.42.11 PM.jpeg" alt="Portarretrato con nombre Antonella" class="product-image"><strong>Portarretratos personalizados</strong><p>Base con portarretrato y compartimiento auxiliar, ideal para regalos y decoración.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20portarretratos%20personalizados">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 1.42.11 PM (1).jpeg" alt="Portarretrato personalizado Antonella" class="product-image"><strong>Detalles con nombre</strong><p>Trabajos en MDF personalizados con nombres y acabados decorativos.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20detalles%20con%20nombre">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 2.21.16 PM (1).jpeg" alt="Portacelular madrina" class="product-image"><strong>Souvenirs especiales</strong><p>Diseños con mensajes personalizados para padrinos, madrinas y familiares.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20souvenirs%20especiales">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 2.21.16 PM.jpeg" alt="Portacelulares personalizados en serie" class="product-image"><strong>Portacelulares personalizados</strong><p>Modelos prácticos y decorativos para regalos y recordatorios de eventos.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20portacelulares%20personalizados">Cotizar por WhatsApp</a></div>
          </div>
        </div>

        <div>
          <h3 style="color: var(--primary); margin-bottom: 18px;">Relojes, decoración y señalización</h3>
          <div class="gallery">
            <div class="card"><img src="WhatsApp Image 2026-02-28 at 9.35.59 PM.jpeg" alt="Reloj temático Star Wars" class="product-image"><strong>Relojes temáticos</strong><p>Diseños con personajes, nombres y temáticas personalizadas.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20relojes%20tem%C3%A1ticos">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-28 at 5.54.34 PM.jpeg" alt="Reloj personalizado Carlos Andres" class="product-image"><strong>Relojes personalizados</strong><p>Opciones para regalos, habitaciones y decoración especial.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20relojes%20personalizados">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 1.42.09 PM.jpeg" alt="Escudo decorativo Alejo" class="product-image"><strong>Escudos decorativos</strong><p>Diseños grandes para pared, habitaciones o espacios personalizados.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20escudos%20decorativos">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 2.21.16 PM (3).jpeg" alt="Numeración en MDF 401" class="product-image"><strong>Números y señalización</strong><p>Piezas en MDF para puertas, oficinas, apartamentos y señalización personalizada.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20n%C3%BAmeros%20y%20se%C3%B1alizaci%C3%B3n">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 2.21.16 PM (2).jpeg" alt="Placa grabada con foto y mensaje" class="product-image"><strong>Placas grabadas</strong><p>Diseños con foto, mensaje y grabado láser para recuerdos especiales.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20placas%20grabadas">Cotizar por WhatsApp</a></div>
          </div>
        </div>

        <div>
          <h3 style="color: var(--primary); margin-bottom: 18px;">Nombres, frases y flores decorativas</h3>
          <div class="gallery">
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 1.42.08 PM.jpeg" alt="Frase Mi Bautizo" class="product-image"><strong>Frases decorativas</strong><p>Letras recortadas para eventos, mesas principales y decoración temática.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20frases%20decorativas">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 1.42.08 PM (1).jpeg" alt="Nombre Antonella en dorado" class="product-image"><strong>Nombres en glitter</strong><p>Nombres personalizados para cumpleaños, bautizos y celebraciones.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20nombres%20en%20glitter">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 1.42.08 PM (2).jpeg" alt="Rosa decorativa Feliz dia de mujer" class="product-image"><strong>Rosas decorativas</strong><p>Detalles especiales para fechas importantes y regalos personalizados.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20rosas%20decorativas">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 1.42.08 PM (3).jpeg" alt="Rosa decorativa roja" class="product-image"><strong>Diseños en acrílico o MDF</strong><p>Piezas delicadas y elegantes para obsequios y decoración.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20dise%C3%B1os%20en%20acr%C3%ADlico%20o%20MDF">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 1.42.08 PM (4).jpeg" alt="Rosas decorativas de varios tamaños" class="product-image"><strong>Modelos por tamaño</strong><p>Opciones personalizadas en distintas medidas según tu necesidad.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20modelos%20por%20tama%C3%B1o">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 3.41.51 PM.jpeg" alt="Placa decorativa frase de agradecimiento" class="product-image"><strong>Frases en MDF</strong><p>Mensajes largos y decorativos para pared, eventos y regalos especiales.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20frases%20en%20MDF">Cotizar por WhatsApp</a></div>
          </div>
        </div>

        <div>
          <h3 style="color: var(--primary); margin-bottom: 18px;">Reconocimientos, medallas y trabajos institucionales</h3>
          <div class="gallery">
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 3.41.55 PM (1).jpeg" alt="Placa Marching Band Tibabita 2025" class="product-image"><strong>Placas institucionales</strong><p>Reconocimientos con escudos, nombres y textos grabados para colegios y grupos.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20placas%20institucionales">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 3.41.55 PM.jpeg" alt="Medallas cubo Rubik" class="product-image"><strong>Medallas para competencias</strong><p>Diseños personalizados para torneos, festivales y eventos escolares.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20medallas%20para%20competencias">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 3.41.54 PM (1).jpeg" alt="Medallas Rubiks en serie" class="product-image"><strong>Producción de medallas</strong><p>Elaboración por cantidad para primeros, segundos y terceros puestos.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20producci%C3%B3n%20de%20medallas">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 3.41.54 PM.jpeg" alt="Medalla cohetería LICOL" class="product-image"><strong>Medallas temáticas</strong><p>Piezas para actividades académicas, ferias y concursos temáticos.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20medallas%20tem%C3%A1ticas">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 3.41.53 PM.jpeg" alt="Medallas cohetería en serie" class="product-image"><strong>Series institucionales</strong><p>Producción en serie para colegios, grupos de trabajo y proyectos especiales.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20series%20institucionales">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 3.41.52 PM (2).jpeg" alt="Escudo Testronics robotica" class="product-image"><strong>Escudos y logos</strong><p>Grabados y cortes para clubes, grupos escolares y marcas personalizadas.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20escudos%20y%20logos">Cotizar por WhatsApp</a></div>
          </div>
        </div>

        <div>
          <h3 style="color: var(--primary); margin-bottom: 18px;">Grabado láser y cuadros personalizados</h3>
          <div class="gallery">
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 2.21.16 PM (2).jpeg" alt="Placa grabada con foto y mensaje" style="width:100%; border-radius:12px; margin-bottom:12px;"><strong>Placas grabadas</strong><p>Diseños con foto, mensaje y grabado láser para recuerdos especiales.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20placas%20grabadas">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 3.41.52 PM (1).jpeg" alt="Foto grabada en MDF" class="product-image"><strong>Fotos grabadas</strong><p>Grabado de imágenes en MDF para recuerdos familiares y regalos únicos.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20fotos%20grabadas">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 3.41.51 PM (1).jpeg" alt="Marco decorativo con foto grabada" class="product-image"><strong>Marcos decorativos</strong><p>Cuadros con marco ornamental y grabado láser para decorar y regalar.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20marcos%20decorativos">Cotizar por WhatsApp</a></div>
          </div>
        </div>

        <div>
          <h3 style="color: var(--primary); margin-bottom: 18px;">Personalización textil y otros trabajos</h3>
          <div class="gallery">
            <div class="card"><img src="WhatsApp Image 2026-03-30 at 3.41.52 PM.jpeg" alt="Camiseta personalizada con dragon" class="product-image"><strong>Personalización en ropa</strong><p>Diseños para camisetas y prendas con nombres, figuras y arte personalizado.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20personalizaci%C3%B3n%20en%20ropa">Cotizar por WhatsApp</a></div>
          </div>
        </div>

        <div>
          <h3 style="color: var(--primary); margin-bottom: 18px;">Llaveros y detalles empresariales</h3>
          <div class="gallery">
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.49.03 AM.jpeg" alt="Llavero Renault personalizado" class="product-image"><strong>Llaveros de marcas</strong><p>Llaveros personalizados con logos de marcas, nombres o identidad visual de negocio.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20llaveros%20de%20marcas">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.49.02 AM (4).jpeg" alt="Llavero Renault detalle" class="product-image"><strong>Llaveros promocionales</strong><p>Detalles prácticos para obsequios, campañas y recordación de marca.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20llaveros%20promocionales">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.49.02 AM (3).jpeg" alt="Llavero Yaya Cars Renault" class="product-image"><strong>Llaveros para negocios</strong><p>Modelos con nombre de empresa y número de contacto para fidelización de clientes.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20llaveros%20para%20negocios">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.49.02 AM (2).jpeg" alt="Llavero Mitsubishi Yaya Cars" class="product-image"><strong>Diseños por marca</strong><p>Opciones en MDF y acabados metálicos para automotriz, talleres y negocios personalizados.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20dise%C3%B1os%20de%20llaveros%20por%20marca">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.49.02 AM (1).jpeg" alt="Llavero Mitsubishi detalle" class="product-image"><strong>Llaveros corporativos</strong><p>Detalles para entregar a clientes, talleres, concesionarios y eventos empresariales.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20llaveros%20corporativos">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.49.02 AM.jpeg" alt="Llavero BMW Yaya Cars" class="product-image"><strong>Modelos premium</strong><p>Diseños con logos icónicos y excelente presentación para regalo o promoción.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20llaveros%20premium">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.49.01 AM (3).jpeg" alt="Serie de llaveros BMW y Mitsubishi" class="product-image"><strong>Producción por cantidad</strong><p>Fabricación en serie para negocios, promociones y entregas comerciales.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20producci%C3%B3n%20de%20llaveros%20por%20cantidad">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.49.01 AM (2).jpeg" alt="Serie de llaveros empresariales" class="product-image"><strong>Colecciones empresariales</strong><p>Varias referencias en un mismo pedido con acabados consistentes y personalizados.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20colecciones%20empresariales%20de%20llaveros">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.49.01 AM (1).jpeg" alt="Llaveros Nissan y corporativos" class="product-image"><strong>Llaveros personalizados variados</strong><p>Creación de modelos a medida según referencia, marca o idea del cliente.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20llaveros%20personalizados%20variados">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.49.01 AM.jpeg" alt="Llavero Nissan Yaya Cars" class="product-image"><strong>Llaveros automotrices</strong><p>Especiales para talleres, latonería, pintura y servicios del sector automotor.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20llaveros%20automotrices">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.48.54 AM (1).jpeg" alt="Serie de llaveros BMW y Mitsubishi sobre base" class="product-image"><strong>Series listas para entrega</strong><p>Producción completa y organizada de llaveros para pedidos de varias unidades.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20series%20listas%20para%20entrega">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.48.54 AM.jpeg" alt="Colección de llaveros empresariales completa" class="product-image"><strong>Pedido empresarial completo</strong><p>Conjuntos de llaveros terminados para negocio, promoción y fidelización.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20pedido%20empresarial%20de%20llaveros">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.48.53 AM (1).jpeg" alt="Exhibidores con llaveros y grabados de animales" class="product-image"><strong>Llaveros con exhibidor</strong><p>Presentación de llaveros junto con porta celulares o exhibidores grabados.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20llaveros%20con%20exhibidor">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.48.53 AM.jpeg" alt="Llaveros BMW sobre exhibidor azul" class="product-image"><strong>Exhibición premium</strong><p>Presentación más atractiva para mostrar productos de marca y captar clientes.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20exhibici%C3%B3n%20premium%20de%20llaveros">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.48.45 AM (1).jpeg" alt="Medallón Baby Shower grabado" class="product-image"><strong>Colgantes personalizados</strong><p>Piezas grabadas para recuerdos, baby shower y regalos personalizados.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20colgantes%20personalizados">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.48.45 AM.jpeg" alt="Colgantes Baby Shower en serie" class="product-image"><strong>Recuerdos colgantes</strong><p>Opciones en serie para eventos infantiles, recuerdos y detalles especiales.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20recuerdos%20colgantes">Cotizar por WhatsApp</a></div>
          </div>
        </div>

        <div>
          <h3 style="color: var(--primary); margin-bottom: 18px;">Trofeos y reconocimientos en acrílico</h3>
          <div class="gallery">
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.51.57 AM.jpeg" alt="Reconocimiento en acrílico Festival de Cometas" class="product-image"><strong>Reconocimientos en acrílico</strong><p>Trofeos y placas de premiación con grabado láser para concursos, eventos y festivales.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20reconocimientos%20en%20acr%C3%ADlico">Cotizar por WhatsApp</a></div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="videos">
    <div class="container">
      <div class="section-title">
        <h2>Videos de trabajos reales</h2>
        <p>También puedes mostrar a tus clientes el proceso, la terminación y el resultado final con videos reales de tus productos.</p>
      </div>
      <div class="grid-3">
        <div class="card">
          <video controls class="video-frame">
            <source src="WhatsApp Video 2026-03-30 at 1.41.59 PM.mp4" type="video/mp4">
          </video>
          <p>Video de producto personalizado</p>
        </div>
        <div class="card">
          <video controls class="video-frame">
            <source src="WhatsApp Video 2026-03-30 at 1.42.08 PM.mp4" type="video/mp4">
          </video>
          <p>Video de detalle y acabado</p>
        </div>
        <div class="card">
          <video controls class="video-frame">
            <source src="WhatsApp Video 2026-03-30 at 1.42.11 PM.mp4" type="video/mp4">
          </video>
          <p>Video de muestra adicional</p>
        </div>
        <div class="card">
          <video controls class="video-frame">
            <source src="WhatsApp Video 2026-03-31 at 11.49.00 AM.mp4" type="video/mp4">
          </video>
          <p>Video de llaveros y detalles empresariales</p>
        </div>
        <div class="card">
          <video controls class="video-frame">
            <source src="WhatsApp Video 2026-03-31 at 11.51.57 AM.mp4" type="video/mp4">
          </video>
          <p>Video de reconocimiento en acrílico</p>
        </div>
      </div>
    </div>
  </section>

  <div>
          <h3 style="color: var(--primary); margin-bottom: 18px;">Trofeos, medallas y reconocimientos</h3>
          <div class="gallery">
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.51.57 AM.jpeg" alt="Reconocimiento en acrílico Festival de Cometas" class="product-image"><strong>Reconocimientos en acrílico</strong><p>Trofeos y placas de premiación con grabado láser para concursos, eventos y festivales.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20reconocimientos%20en%20acr%C3%ADlico">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.44.19 AM (2).jpeg" alt="Trofeo coheteria en forma de cohete" class="product-image"><strong>Trofeos temáticos</strong><p>Diseños especiales para concursos de ciencia, cohetería y premiaciones escolares.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20trofeos%20tem%C3%A1ticos">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.44.19 AM (1).jpeg" alt="Medalla Rubiks primer puesto" class="product-image"><strong>Medallas de competencia</strong><p>Medallas y piezas para torneos, ajedrez, cubo Rubik y actividades escolares.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20medallas%20de%20competencia">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.44.19 AM.jpeg" alt="Torre de ajedrez primer puesto" class="product-image"><strong>Reconocimientos de ajedrez</strong><p>Piezas personalizadas para campeonatos, clubes y torneos escolares.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20reconocimientos%20de%20ajedrez">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.44.18 AM.jpeg" alt="Certificado grabado concurso de coheteria" class="product-image"><strong>Certificados grabados</strong><p>Placas tipo diploma para premiación y eventos institucionales.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20certificados%20grabados">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.44.17 AM (1).jpeg" alt="Set de certificados grabados escolares" class="product-image"><strong>Sets institucionales</strong><p>Producción de varios reconocimientos para ceremonias, colegios y concursos.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20sets%20institucionales">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.48.04 AM (3).jpeg" alt="Rubiks primer puesto varios acabados" class="product-image"><strong>Medallas en distintos acabados</strong><p>Modelos en MDF natural, pintado o con acabados brillantes según tu necesidad.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20medallas%20en%20distintos%20acabados">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.48.04 AM (2).jpeg" alt="Placa ajedrez primer puesto" class="product-image"><strong>Trofeos de ajedrez</strong><p>Reconocimientos personalizados para torneos con diseño de piezas de ajedrez.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20trofeos%20de%20ajedrez">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.48.04 AM (1).jpeg" alt="Certificado grabado robotica o coheteria" class="product-image"><strong>Placas conmemorativas</strong><p>Reconocimientos personalizados con grabado fino para eventos y premiaciones.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20placas%20conmemorativas">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.48.04 AM.jpeg" alt="Certificado grabado participacion picabots" class="product-image"><strong>Diplomas en MDF</strong><p>Alternativa creativa a los diplomas tradicionales para participación y reconocimiento.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20diplomas%20en%20MDF">Cotizar por WhatsApp</a></div>
          </div>
        </div>

        <div>
          <h3 style="color: var(--primary); margin-bottom: 18px;">Portacelulares y grabados decorativos</h3>
          <div class="gallery">
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.48.05 AM (1).jpeg" alt="Portacelulares grabados con animales" class="product-image"><strong>Portacelulares grabados</strong><p>Modelos funcionales con diseños decorativos de animales y figuras artísticas.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20portacelulares%20grabados">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.48.05 AM.jpeg" alt="Colección de portacelulares con animales" class="product-image"><strong>Colección de portacelulares</strong><p>Varios estilos y materiales para regalos, decoración y uso diario.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20colecci%C3%B3n%20de%20portacelulares">Cotizar por WhatsApp</a></div>
          </div>
        </div>

        <div>
          <h3 style="color: var(--primary); margin-bottom: 18px;">Rosas, detalles y regalos personalizados</h3>
          <div class="gallery">
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.48.01 AM.jpeg" alt="Rosas decorativas con nombres" class="product-image"><strong>Rosas con nombres</strong><p>Detalles románticos y decorativos con brillo, color y nombres personalizados.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20rosas%20con%20nombres">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.48.44 AM (1).jpeg" alt="Rosa decorativa empacada para regalo" class="product-image"><strong>Regalos empacados</strong><p>Presentación lista para obsequiar con empaque decorativo y detalle personalizado.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20regalos%20empacados">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.48.44 AM.jpeg" alt="Rosa decorativa empacada detalle" class="product-image"><strong>Detalles especiales</strong><p>Opciones decorativas para fechas especiales, aniversarios y celebraciones.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20detalles%20especiales">Cotizar por WhatsApp</a></div>
          </div>
        </div>

  <div>
          <h3 style="color: var(--primary); margin-bottom: 18px;">Rosas, flores y detalles para regalo</h3>
          <div class="gallery">
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.43.26 AM.jpeg" alt="Rosa roja personalizada" class="product-image"><strong>Rosas personalizadas</strong><p>Detalles decorativos en MDF con nombres, colores y acabados brillantes para regalar.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20rosas%20personalizadas">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.43.25 AM.jpeg" alt="Rosa personalizada de dos colores" class="product-image"><strong>Rosas en varios estilos</strong><p>Diseños en una o varias piezas, con combinaciones de color y grabado personalizado.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20rosas%20en%20varios%20estilos">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.43.24 AM.jpeg" alt="Rosas rojas en serie" class="product-image"><strong>Producción por cantidad</strong><p>Elaboración de rosas y detalles decorativos en serie para fechas especiales y eventos.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20rosas%20por%20cantidad">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.43.23 AM.jpeg" alt="Rosa y flor feliz día mamá" class="product-image"><strong>Detalles Día de la Madre</strong><p>Modelos especiales con frases, corazones, flores y presentación para regalo.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20detalles%20para%20el%20D%C3%ADa%20de%20la%20Madre">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.42.04 AM.jpeg" alt="Rosa decorativa con base" class="product-image"><strong>Rosas con base</strong><p>Modelos de mesa con base decorativa para obsequios y decoración personalizada.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20rosas%20con%20base">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.42.03 AM.jpeg" alt="Rosa de mesa con caja decorativa" class="product-image"><strong>Rosas con caja</strong><p>Presentación elegante para regalo con caja decorativa y detalle personalizado.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20rosas%20con%20caja">Cotizar por WhatsApp</a></div>
          </div>
        </div>

        <div>
          <h3 style="color: var(--primary); margin-bottom: 18px;">Llaveros escolares y promocionales</h3>
          <div class="gallery">
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.42.06 AM.jpeg" alt="Llavero triangular escolar" class="product-image"><strong>Llaveros institucionales</strong><p>Llaveros personalizados para colegios, cursos, promociones y eventos académicos.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20llaveros%20institucionales">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.41.10 AM.jpeg" alt="Serie de llaveros escolares" class="product-image"><strong>Series escolares</strong><p>Fabricación por cantidad de llaveros con mensajes, nombres de curso y promoción.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20llaveros%20escolares%20por%20cantidad">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.41.09 AM (3).jpeg" alt="Llaveros escolares organizados" class="product-image"><strong>Producción organizada</strong><p>Pedidos múltiples listos para entregar, ideales para grupos, promociones o instituciones.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20producci%C3%B3n%20organizada%20de%20llaveros">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.41.09 AM (2).jpeg" alt="Llaveros escolares en serie" class="product-image"><strong>Llaveros por promoción</strong><p>Modelos con texto grabado para instituciones, docentes y grupos escolares.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20llaveros%20por%20promoci%C3%B3n">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.41.09 AM (1).jpeg" alt="Llavero escolar individual" class="product-image"><strong>Modelo individual</strong><p>Ejemplo de llavero personalizado para recuerdo escolar o empresarial.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20un%20llavero%20personalizado">Cotizar por WhatsApp</a></div>
          </div>
        </div>

        <div>
          <h3 style="color: var(--primary); margin-bottom: 18px;">Nombres decorativos y letreros temáticos</h3>
          <div class="gallery">
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.42.18 AM (1).jpeg" alt="Letrero Halloween Vale" class="product-image"><strong>Letreros temáticos</strong><p>Nombres y decoraciones grandes para habitaciones, fiestas y temporadas especiales.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20letreros%20tem%C3%A1ticos">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.42.18 AM.jpeg" alt="Letrero Vale temático" class="product-image"><strong>Nombres en foamy o MDF</strong><p>Diseños llamativos con brillo, color y figuras decorativas según el tema que desees.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20nombres%20decorativos">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.42.08 AM (1).jpeg" alt="Letreros Timotea y Timotea coloridos" class="product-image"><strong>Nombres ornamentales</strong><p>Letreros elegantes y recargados para decorar puertas, habitaciones o celebraciones.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20letreros%20ornamentales">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.42.08 AM.jpeg" alt="Nombres Timotea en colores" class="product-image"><strong>Diseños en color</strong><p>Opciones en diferentes combinaciones de color para nombres personalizados y decoración.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20dise%C3%B1os%20de%20nombres%20en%20color">Cotizar por WhatsApp</a></div>
          </div>
        </div>

        <div>
          <h3 style="color: var(--primary); margin-bottom: 18px;">Cajas y empaques decorativos</h3>
          <div class="gallery">
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.42.07 AM.jpeg" alt="Caja decorativa naranja" class="product-image"><strong>Cajas para detalles</strong><p>Cajas decorativas para regalos, sorpresas y presentaciones especiales.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20cajas%20para%20detalles">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.41.08 AM (1).jpeg" alt="Plantilla caja decorativa" class="product-image"><strong>Diseño y corte de cajas</strong><p>Se entrega armado o en piezas listas para ensamblar según el proyecto.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20dise%C3%B1o%20y%20corte%20de%20cajas">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.41.08 AM.jpeg" alt="Caja blanca con luna y estrellas" class="product-image"><strong>Cajas recordatorio</strong><p>Modelos en MDF para centros de mesa, recordatorios o detalles de eventos.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20cajas%20recordatorio">Cotizar por WhatsApp</a></div>
            <div class="card"><img src="WhatsApp Image 2026-03-31 at 11.41.07 AM.jpeg" alt="Caja blanca decorativa vista superior" class="product-image"><strong>Cajas personalizadas</strong><p>Opciones minimalistas o decoradas con cortes especiales, nombres o figuras.</p><a class="product-btn" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20cotizar%20cajas%20personalizadas">Cotizar por WhatsApp</a></div>
          </div>
        </div>

  <section id="contacto">
    <div class="container">
      <div class="cta">
        <h2>Solicita tu cotización hoy</h2>
        <p>Cuéntanos tu idea y te ayudamos a convertirla en una pieza real con corte láser de alta calidad.</p>
        <div class="btns" style="justify-content:center; margin-top: 20px;">
          <a class="btn btn-primary" href="https://wa.me/573138274878?text=Hola%2C%20quiero%20informaci%C3%B3n%20sobre%20sus%20servicios%20de%20corte%20l%C3%A1ser">Escribir por WhatsApp</a>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <div class="container">
      <p><strong>Infinity Láser MG</strong></p>
      <p>Bogotá, Colombia</p>
      <p>WhatsApp: 313 827 4878</p>
      <p>© 2026 Todos los derechos reservados</p>
    </div>
  </footer>
</body>
</html>
