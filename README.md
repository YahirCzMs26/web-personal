# SitioWebPersonal
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Web de Yahir</title>

  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" />


  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f0f2f5;
    }

    .section {
      padding: 60px 0;
    }

    .section:nth-child(even) {
      background-color: #ffffff;
    }

    .section-title {
      font-size: 2.5rem;
      font-weight: bold;
      color: #0d6efd; 
      margin-bottom: 40px;
    }

    .custom-img {
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      max-height: 300px;
      object-fit: cover;
      width: 100%;
    }

    footer {
      background-color: #0d6efd;
      color: white;
      padding: 20px 0;
    }
  </style>
</head>
<body>


  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <div class="container">
      <a class="navbar-brand" href="#">🟢Web de Yahir🟢</a>

      <div class="mx-auto text-white d-none d-lg-block" id="saludoNavbar" style="font-weight: bold;"></div>

      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#personal">Personal</a></li>
          <li class="nav-item"><a class="nav-link" href="#academica">Académica</a></li>
          <li class="nav-item"><a class="nav-link" href="#experiencias">Experiencias</a></li>
          <li class="nav-item"><a class="nav-link" href="#aprendizajes">Aprendizajes</a></li>
          <li class="nav-item"><a class="nav-link" href="#contacto">Contacto</a></li>
        </ul>
      </div>
    </div>
  </nav>
  <section class="section bg-white">
    <div class="container text-center">
      <h1 class="mb-4">¡Hola! Bienvenido al sitio web de Yahir👋</h1>
      <p class="lead">
        Es un gusto tenerte por aquí. A continuación te presento información sobre mí, pasajes y experiencias académicas, además de distintos medios para contactarme.
        <p class="lead">
        Para mayor comodidad, en la esquina superior derecha puedes acceder directamente al apartado informativo de tu interés. 
    </div>
  </section>
 
  <section id="personal" class="section">
    <div class="container">
      <h2 class="section-title text-center">Información Personal📝</h2>
      <div class="row align-items-center">
        <div class="col-md-6">
          
          <img src="Yo.jpeg" class="custom-img" alt="Foto personal" />
        </div>
        <div class="col-md-6">
         
          <p><strong>Nombre completo:</strong> Kevin Yahir Cortez Morales</p>
          <p><strong>Edad:</strong> 20 años</p>
          <p><strong>Fecha de nacimiento:</strong> 20 de Abril del 2005</p>
          <p><strong>Lugar de origen:</strong> Cosolapa, Oaxaca.</p>
        </div>
      </div>
    </div>
  </section>

  
  <section id="academica" class="section">
    <div class="container">
      <h2 class="section-title text-center">Información Académica✍🏽</h2>
      <div class="row align-items-center">
        <div class="col-md-6">
          
          <img src="YoAcademico.jpeg" class="custom-img" alt="Educación" />
        </div>
        <div class="col-md-6">
          
          <ul>
            <li><strong>Universidad:</strong> Universidad Veracruzana (2023 - 2028)</li>
            <li><strong>Facultad:</strong> Negocios y Tecnologías.</li>
            <li><strong>Región:</strong> Córdoba - Orizaba</li>
            <li><strong>Programa educativo:</strong> Tecnologías de información en las organizaciones</li>
            <li><strong>Semestre actual y grupo:</strong> 4° - 401</li>
            
            <br>

            
            <h4>Trayectoria previa</h4>
            <li><strong>Preparatoria:</strong> Instituto de Estudios de Bachillerato del Estado de Oaxaca (IEBO) Plantel 001 (2020 - 2023)</li>
            <li><strong>Secundaría:</strong> Escuela Secundaria Técnica Número 53 (2017 - 2020)</li>
            <li><strong>Primaria:</strong> Escuela Primaria Gabriel Lucio (2011 - 2017)</li>
            <li><strong>Preescolar:</strong> Preescolar Frida Kahlo Calderón (2008 - 2011)</li>
            <br>

            <h4>Demás...</h4>
            <li><strong>Certificado:</strong> Cómputo básico - Capacitate</li>
            <li><strong>Curso:</strong> Crear una app - PruébaT</li>
            <li><strong>Curso:</strong> Hablar en público - PruébaT</li>
            <li><strong>Idiomas:</strong> Inglés Intermedio I (Cursando actualmente - C.I. Orizaba)</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

 
  <section id="experiencias" class="section">
    <div class="container">
      <h2 class="section-title text-center">Participaciones destacadas🌟</h2>
      <div class="row align-items-center">
        <div class="col-md-6">
          
          <img src="YoPasado.jpeg" width="100%" alt="Experiencia" />
        </div>
        <div class="col-md-6">
          <div class="card shadow-sm">
            <div class="card-body">
              <h5 class="card-title">IEBOLOGÍA</h5>
              <p class="card-text">"IEBOLOGÍA" fue el nombre de un proyecto educativo que impulsaba fomentar el aprendizaje colaborativo entre los estudiantes, además de promover el uso de la tecnología dentro de las instalaciones del IEBO 001. Junto a 2 compañeros más, creamos y el establecimos todos los detalles acerca del proyecto. La organización y el plan de financiamiento fue de los aspectos más complejos en los que recuerdo, me tocó trabajar directamente. </p>
              <p class="card-text"><small class="text-muted">El impacto del proyecto fue limitado a las instalaciones del bacchillerato en el que cursé</small></p>
            </div>

            <div class="card-body">
              <h5 class="card-title">Oratoria</h5>
              <p class="card-text">Desde 5° de primaria incursioné en esta arte de la palabra, ahí representé a mi primaria a nivel zona, gané y obtuve mi pase al concurso regional en donde conservo un grato recuerdo de la experiencia en general. Nuevamente, en 2° año de secundaria, representé a mi secundaria a nivel zona y finalmente en la preparatoria gané el consurso interno, sin embargo, no existió una competición más allá para representar a mi plantel</p>
              <p class="card-text"><small class="text-muted">Considero que la habilidad de hablar frente a un cierto público y la comunicación efectiva es fundamental para el desarrollo personal y profesional, más dentro del área de la tecnología.</small></p>
            </div>

            <div class="card-body">
              <h5 class="card-title">CEKE Conmutación</h5>
              <p class="card-text">Fue el nombre de un proyecto con impacto social, no lucrativo, el cual buscaba mejorar la comunicación y el entendimiento entre diferentes comunidades a través de talleres y actividades interactivas. Ofrecer apoyo de parte de estudiantes a un sector de la comunidad en situación de vulnerabilidad o desconocimiento del tema</p>
              <p class="card-text"><small class="text-muted">La gestión, desarrollo y ejecución de proyectos son de las prácticas comunes dentro del área tecnológica</small></p>
            </div>

            
          </div>
          
          

        </div>
      </div>
    </div>
  </section>

  <section id="aprendizajes" class="section">
    <div class="container">
      <h2 class="section-title text-center">Aprendizajes Universitarios📚</h2>
      <div class="row align-items-center">
        <div class="col-md-6">
          <iframe width="560" height="315" src="https://www.youtube.com/embed/Ju2yrHQn9VI?si=A9BD_0QelqqDOnYt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
        <div class="col-md-6">
          
            <p>Dentro de estos ya casi dos años en la Universidad Veracruzana he tenido significativas experiencias educativas que han contribuido a expandir mi conocimiento,
               aunque tomando en cuenta que no tan orientado aún a mi carrera, derivado del programa de estudios vigente en la carrera. Sin embargo, destaco el punto más importante por semestre que
              considero yo, ha sido más interesante para mi....</p>
            <footer class="blockquote-footer" style="color: #ffffff;">
              <ul>
                <li><strong>Primero:</strong> La gestión de los recursos humanos, especificamente los filtros que son prudentes establecer ante el reclutamiento de personal,
                   además de la empatía que debe exitir dentro de un entorno laboral</li>
                <li><strong>Segundo:</strong> Requerimientos, conceptos, instalación y consultas de base de datos. Creación y gestión de base de datos, además de la realización de consultas </li>
                <li><strong>Tercero:</strong> Importancia de los sistemas de datos, variaciones y tipos dependiendo del contexto de una organización</li>
              
              </ul>
            </footer>
          </blockquote>
          <p>Y como sigue en tránsito el 4° semestre no destaco un punto en especifico aún, más sin embargo
            adjunto un video reciente, consecuencia de una actividad de la experiencia educativa 
             "Entorno Legal en los Negocios de T.I." en el cual se abarca el tema de la igualdad digital. Para la realización de este material
             se utilizaron multiples recursos tecnológicos y de software para la edición y difusión del material mencionado, además de adentrarse
             a normativas y leyes que toda persona debería conocer, más aún las personas profesionales en este medio, el tecnológico.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="contacto" class="section">
    <div class="container text-center">
      <h3 class="section-title">Medios de contacto📲</h3>
      <div class="d-flex justify-content-center gap-4 flex-wrap">
        
        <a href="https://www.facebook.com/share/1ANK9y5hCx/" target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook" width="50" height="50">
        </a>
  
        
        <a href="https://www.instagram.com/yahircz_26/" target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram" width="50" height="50">
        </a>
  
        
        <a href="https://www.linkedin.com/in/kevin-yahir-c-morales-45abb3361/" target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn" width="50" height="50">
        </a>
  
        
        <a href="https://github.com/YahirCzMs26" target="_blank">
          <img src="https://cdn-icons-png.flaticon.com/512/733/733553.png" alt="GitHub" width="50" height="50">
        </a>

        <br>
        <ul>
        <p><strong>Correo institucional:</strong> zS23004879@estudiantes.uv.mx</p>
        <p><strong>Correo personal:</strong> cortezmoralesk55@gmail.com</p>
        <p><strong>Núm. Telefonico:</strong> 278-115-5197</p>
        </ul>

      </div>
    </div>
  </section>
  

  <footer class="text-center">
    <div class="container">
      <p class="mb-0">Realizado por Kevin Yahir Cortez Morales.</p>
      <p class="mb-0">Diseñado con plantillas de Bootstrap - Actividad de Diseño Web</p>
      <p class="mb-0">&copy; 2025</p>
    </div>
  </footer>

  <script>
    document.querySelectorAll('a.nav-link[href^="#"]').forEach(enlace => {
      enlace.addEventListener('click', function(e) {
        const destino = document.querySelector(this.getAttribute('href'));
        if (destino) {
          e.preventDefault();
          destino.scrollIntoView({ behavior: 'smooth' });
        }
      });
    });
  </script>
  
  <script>
    const hora = new Date().getHours();
    let saludo;
  
    if (hora >= 6 && hora < 12) {
      saludo = "¡Buen día! ☀️";
    } else if (hora >= 12 && hora < 18) {
      saludo = "¡Buena tarde! 🌤️";
    } else {
      saludo = "¡Buena noche! 🌙";
    }
  
    document.getElementById("saludoNavbar").textContent = saludo;
  </script>
  
</body>
</html>
