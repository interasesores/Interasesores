<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>InterAsesores</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .hero { background: url('banner.jpg') center/cover; color: white; padding: 100px 0; text-align:center; }
    .services .card:hover { transform: translateY(-5px); box-shadow: 0 4px 8px rgba(0,0,0,0.2); }
    .clients img { max-height: 80px; margin: 10px; }
  </style>
</head>
<body>

  <!-- Cabecera -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="#">InterAsesores</a>
      <button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#nav"><span class="navbar-toggler-icon"></span></button>
      <div class="collapse navbar-collapse" id="nav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#">Inicio</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Servicios</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Clientes</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Contacto</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Banner -->
  <section class="hero">
    <div class="container">
      <h1>Bienvenido a InterAsesores</h1>
      <p>Asesoría experta para tu empresa. ¡Conéctate con nosotros!</p>
      <a href="#contacto" class="btn btn-primary">Contáctanos</a>
    </div>
  </section>

  <!-- Servicios -->
  <section class="services py-5">
    <div class="container">
      <h2 class="mb-4 text-center">¿En qué podemos ayudarte?</h2>
      <div class="row g-4">
        <div class="col-md-4">
          <div class="card text-center p-4">
            <img src="img/servicio1.png" class="card-img-top mx-auto" alt="Servicio 1" style="max-width:100px;">
            <div class="card-body">
              <h5 class="card-title">Consultoría financiera</h5>
              <p class="card-text">Optimiza tus finanzas empresariales con nuestros expertos.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card text-center p-4">
            <img src="img/servicio2.png" class="card-img-top mx-auto" alt="Servicio 2" style="max-width:100px;">
            <div class="card-body">
              <h5 class="card-title">Gestión de proyectos</h5>
              <p class="card-text">Implementamos metodologías eficientes para tus proyectos.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card text-center p-4">
            <img src="img/servicio3.png" class="card-img-top mx-auto" alt="Servicio 3" style="max-width:100px;">
            <div class="card-body">
              <h5 class="card-title">Capacitación corporativa</h5>
              <p class="card-text">Formamos tu equipo en habilidades clave para el éxito.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Clientes -->
  <section class="clients bg-light py-5">
    <div class="container text-center">
      <h2 class="mb-4">Nuestros clientes</h2>
      <div class="d-flex flex-wrap justify-content-center">
        <img src="cliente1.png" alt="Cliente 1">
        <img src="cliente2.png" alt="Cliente 2">
        <img src="cliente3.png" alt="Cliente 3">
        <img src="cliente4.png" alt="Cliente 4">
      </div>
    </div>
  </section>

  <!-- Contacto -->
  <section id="contacto" class="py-5">
    <div class="container text-center">
      <h2>¿Tienes preguntas?</h2>
      <p>Sede principal: Calle 127 bis #88-07, Bogotá, Colombia</p>
      <p>📞 +57 3005564973  ✉️ contacto@interasesores.com</p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3">
    <div class="container">
      <a href="#" class="text-white me-3">Inicio</a>
      <a href="#" class="text-white me-3">Servicios</a>
      <a href="#" class="text-white me-3">Contacto</a>
      <p class="mt-2 mb-0">Copyright © InterAsesores 2025</p>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

