---
title: "TSEAS"
permalink: /TSEAS/
layout: default
---


<div class="splash-container">
  <!-- Full-width background image -->
  <img src="/assets/images/CABECERA.png" alt="Full Width Image" class="splash-image">

  <!-- Grey transparent background image -->
  <div class="grey-background"></div>

  <!-- Text title at top right -->
  <div class="top-left">Técnico Superior en Enseñanza y Animación Sociodeportiva (TSEAS)</div>

  <!-- Right image upfront -->
  <img src="/assets/images/profesorPablo2.png" alt="Right Image" class="right-image">

  <!-- Text content at bottom left -->
  <div class="bottom-left">
    <p>El Técnico Superior en Enseñanza y Animación Sociodeportiva es un título oficial del Ministerio de Educación y Formación Profesional. Nuestro centro con código 21007304 está autorizado por la Consejería de Educación y Deporte de la Junta de Andalucía para impartirlo.</p>
    <button class="plan-button2" onclick="location.href='https://japonformacion.netlify.app/contacto/'" style="font-weight: 700;">MÁS INFORMACIÓN</button>
  </div>
</div>


<style>
  .splash-container {
    position: relative;
    width: 100%;
    max-width: none;
    overflow: hidden;
    margin-bottom: 3em;
    padding: 0;
    padding-top: 3.5em;
    margin-top: 2em;
    display: grid;
    grid-template-columns: repeat(2, 1fr); /* Default: 2 columns */
    grid-template-rows: 142px 1fr; /* Default: 2 rows */
    grid-column-gap: 20px; /* Adjust spacing between columns */
    grid-row-gap: 20px; /* Adjust spacing between rows */
    align-items: end;
  }

  /* Styling for the right image */
  .right-image {
    grid-row: 1 / 3; /* Both rows */
    grid-column: 2 / 3; /* Default: second column */
    width: 370px;
    z-index: 10; /* Ensure above background image */
    margin: 0 auto;
    transform: translateX(calc(-50% + 80px));
  }

  .grey-background {
    background-color: rgba(127, 127, 127, 0.7); /* Semi-transparent grey */
    position: absolute; /* Ensures it stays within the container */
    top: 0;
    left: 0;
    width: 55%; /* Occupy the left half of the splash container */
    height: 100%; /* Full height of the splash container */
    z-index: 5; /* Below the text but above the background image */
    margin-top: 3.5em;
    transform: translateX(-80px);
  }

  .bottom-left {
    z-index: 10;
    max-width: 650px;
    text-align: left;
    margin-left: auto;
    margin-right: 1em;
    color: white;
    padding: 20px;
    align-self: start;
  }

  .top-left {
    grid-row: 1 / 2; /* First row */
    grid-column: 1 / 2; /* Now in the first column */
    font-size: 30px;
    font-weight: 700;
    color: white;
    z-index: 10;
    text-align: left;
    margin-right: 0em;
    margin-left: auto;
    max-width: 22.5em;
    padding-left: 20px;
  }

  /* Breakpoint for smaller screens: 1 column, 3 rows */
  @media (max-width: 967px) {
    .splash-container {
      grid-template-columns: 1fr; /* 1 column */
      grid-template-rows: repeat(3, auto); /* 3 rows */
      grid-row-gap: 0px; /* Adjust row spacing */
      margin-top: 0;
    }

    /* Adjust the right image to fit in the first column (stacked layout) */
    .right-image {
      grid-row: 2 / 3; /* Place the image in the second row */
      grid-column: 1 / 2; /* Place it in the first column */
      width: 250px; /* Make it responsive */
      transform: none;
    }

    /* Adjust the grey background to occupy the last row */
    .grey-background {
      position: static; /* Remove absolute positioning */
      grid-row: 3 / 3; /* Place it in the last row */
      grid-column: 1 / 2; /* Full width of the single column */
      width: 100%; /* Full width of the column */
      height: 100%; /* Adjust height automatically */
      transform: none; /* Remove the horizontal transform */
    }

    .bottom-left {
      z-index: 10;
      text-align: left;
      color: white;
      padding: 20px;
      align-self: start;
      grid-column: 1 / 1;
      grid-row: 3 / 3;
    }

    .top-left {
      grid-row: 1 / 2; /* First row */
      grid-column: 1 / 2; /* Now in the first column */
      font-size: 34px;
      font-weight: 700;
      color: white;
      z-index: 10; /* Ensure above background image */
      text-align: left;
      margin-right: 0;
      margin-left: 0;
      padding-left: 20px;
    }
  }

  .splash-image {
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    left: 0;
    object-fit: cover;
    z-index: -1;
    margin: 0;
  }

  .bottom-left p {
    font-size: 17px;
    margin-bottom: 3em;
  }
</style>

<div class="full-width-background">
  <div class="info-container">
    <div class="info-item">
      <p>Inicio</p>
      <h3>Septiembre 2025</h3>
    </div>
    <div class="info-item">
      <p>Duración</p>
      <h3>2.000 horas</h3>
    </div>
    <div class="info-item">
      <p>Becas y financiación</p>
      <h3>Financiación mensual disponible</h3>
    </div>
  </div>
</div>


<div style="text-align:center; margin: 2em;">
  ¿PORQUÉ ESTUDIAR FP?
</div>

<div style="text-align: center;margin-bottom: 3em;">
  <div style="display: inline-block; text-align: left; font-size: 17px;max-width: 60em;">
    <ul style="list-style-type: disc; padding-left: 20px; margin: 0;">
      <li><strong>Crecimiento</strong>. En la actualidad la FP son los estudios profesionales más cercanos a la realidad del mercado de trabajo y dan respuesta a la necesidad de personal cualificado especializado en los distintos sectores profesionales para responder a la actual demanda de empleo.</li>
      <li><strong>Desarrollo</strong>. Si analizamos su alta inserción laboral podemos afirmar que la FP ya se ha transformado en una formación que responde a la demanda real de empleo, ahora es el momento del cambio en la sociedad española.</li>
      <li><strong>Innovación</strong>. La Formación Profesional, además, está en permanente contacto con los diferentes sectores productivos y económicos, respondiendo a sus necesidades, por lo que gana en reconocimiento en todos los países de la Unión Europea y sus titulaciones son cada vez más demandadas. Esto convierte a la formación profesional en una opción atractiva, de calidad y que se adapta a las necesidades de cada individuo para la mejora de sus trayectoria profesional.</li>
    </ul>
  </div>
</div>


<div style="text-align:center; margin: 2em;">
  ASIGNATURAS TSEAS
</div>

<div class="table-container">
  <table>
    <thead>
      <tr>
        <th style="width: 500px;text-align: center;"><h2>1º CURSO 2024-25</h2></th>
        <th style="width: 500px;text-align: center;"><h2>2º CURSO 2025-26</h2></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="width: 500ppx;text-align: center;">Valoración de la condición física e intervención en accidentes.</td>
        <td style="width: 500ppx;text-align: center;">Actividades de ocio y tiempo libre.</td>
      </tr>
      <tr>
        <td style="width: 500ppx;text-align: center;">Juegos y actividades físico-recreativas y de animación turística.</td>
        <td style="width: 500ppx;text-align: center;">Dinamización grupal.</td>
      </tr>
      <tr>
        <td style="width: 500ppx;text-align: center;">Actividades físico-deportivas individuales.</td>
        <td style="width: 500ppx;text-align: center;">Planificación de la animación sociodeportiva.</td>
      </tr>
      <tr>
        <td style="width: 500ppx;text-align: center;">Actividades físico-deportivas de equipo.</td>
        <td style="width: 500ppx;text-align: center;">Actividades físico-deportivas de implementos.</td>
      </tr>
      <tr>
        <td style="width: 500ppx;text-align: center;">Metodología de la enseñanza de actividades físico-deportivas.</td>
        <td style="width: 500ppx;text-align: center;">Actividades físico-deportivas para la inclusión social.</td>
      </tr>
      <tr>
        <td style="width: 500ppx;text-align: center;">Formación y orientación laboral.</td>
        <td style="width: 500ppx;text-align: center;">Empresa e iniciativa emprendedora.</td>
      </tr>
      <tr>
        <td style="width: 500ppx;text-align: center;"></td>
        <td style="width: 500ppx;text-align: center;">Formación en centros de trabajo.</td>
      </tr>
      <tr>
        <td style="width: 500ppx;text-align: center;"></td>
        <td style="width: 500ppx;text-align: center;">Proyecto de enseñanza y animación sociodeportiva.</td>
      </tr>
    </tbody>
  </table>
</div>





<div class="prof-container">
    <div class="prof-item">
      <img src="/assets/images/profesorPablo2.png" style="width: 9em;">
      <p>Pablo Benítez Núñez</p>
    </div>
    <div class="prof-item">
      <img src="/assets/images/profesorGregorio2.png" style="width: 13em;">
      <p>Gregorio Morales Delgado</p>
    </div>
    <div class="prof-item">
      <img src="/assets/images/profesorGregorio2.png" style="width: 13em;">
      <p>Gregorio Morales</p>
    </div>
    <div class="prof-item">
      <img src="/assets/images/profesorGregorio2.png" style="width: 13em;">
      <p>Pepe Japón Camacho</p>
    </div>
  </div>


<div style="text-align:center; margin: 2em;">
  Preguntas frecuentes
</div>

<div class="faq-container">
  <div id="faq" class="faq">
    <button class="accordion">¿Es un título oficial?
      <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
    </button>
    <div class="panel">
      <p>Sí. Somos Centro Docente Privado Grupo Japón con código de Centro 21007304.</p>
    </div>

    <button class="accordion">¿Puedo solicitar Becas del Ministerio de Educación?
      <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
    </button>
    <div class="panel">
      <p>Al tratarse de una titulación oficial, tendrás la posibilidad de optar a una de las ayudas formativas que ofrecen las comunidades autónomas, así como a las becas para FP del Ministerio de Educación y Formación Profesional.</p>
    </div>

    <button class="accordion">¿Necesito comprar algún material para el curso?
      <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
    </button>
    <div class="panel">
      <p>No. Todo el material que necesitaremos está incluido en la matrícula. Sí necesitarás una Tablet o portátil para tus trabajos en clase y casa.</p>
    </div>

    <button class="accordion">¿Qué instalaciones ofrece el Centro?
      <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
    </button>
    <div class="panel">
      <p>Las clases teóricas se impartirán en nuestro Centro y las clases prácticas en: Instalaciones Polideportivas Ayuntamiento, Real Club Recreativo de Tenis y Club Asirio de Tiro con Arco de Huelva.</p>
    </div>

    <button class="accordion">¿Después del Ciclo, puedo acceder a la Universidad?
      <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
    </button>
    <div class="panel">
      <p>Si tienes un título de técnico superior de FP podrás acceder directamente a la universidad, y para ello no será necesario superar ninguna prueba de acceso a la universidad como la selectividad (EvAU o EBAU).</p>
    </div>

    <button class="accordion">¿Cómo se calcula la nota de acceso a la universidad con Grado Superior?
      <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
    </button>
    <div class="panel">
      <p>Para calcular tu nota de acceso de FP para entrar a un grado universitario se tiene en cuenta la calificación media obtenida a lo largo del ciclo formativo, es decir, la nota media obtenida en los módulos cursados durante los dos años que dura el Grado Superior. Ésta será como máximo de 10 puntos.</p>
    </div>

    <button class="accordion">¿Qué métodos de pago se aceptan?
      <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
    </button>
    <div class="panel">
      <p>Tienes dos opciones para que sea mas cómoda tu forma de pago: En un único pago o mediante cuotas mensuales durante la realización de los ciclos.</p>
    </div>

    <button class="accordion">¿El centro ofrece prácticas profesionales?
      <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
    </button>
    <div class="panel">
      <p>Sí.Te garantizamos la realización de prácticas en tus estudios de grado superior en TSEAS y el alta en seguridad como exige la nueva normativa de FP.</p>
    </div>
  </div>
</div>


<div style="text-align:center; margin-top:7em">
  ¿Dudas? No te las guardes, pregúntanos.
</div>

<form name="contact" action="/_pages/success.html" method="POST" data-netlify="true" class="contact-form">
  <input type="hidden" name="subject" id="subject" value="Mensaje de (nombre)" />
  
  <p>
    <label for="name">Nombre:</label><br />
    <input type="text" id="name" name="name" required />
  </p>
  
  <p>
    <label for="email">Correo Electrónico:</label><br />
    <input type="email" id="email" name="email" required />
  </p>
  
  <p>
    <label for="phone">Teléfono:</label><br />
    <input type="tel" id="phone" name="phone" required />
  </p>
  
  <p>
    <label for="message">Mensaje:</label><br />
    <textarea id="message" name="message" rows="5" required></textarea>
  </p>
  
  <p style="text-align: center;">
    <button type="submit" class="submit-button">Enviar</button>
  </p>
</form>

<script>
  document.querySelector('form').addEventListener('submit', function(event) {
    var name = document.getElementById('name').value;
    var phone = document.getElementById('phone').value;
    var subjectField = document.getElementById('subject');
    subjectField.value = `Mensaje de ${name} - Teléfono: ${phone}`;
  });
</script>


<style>
.contact-form {
  max-width: 600px;
  margin: 0 auto;
  text-align: left;
}

.faq-container {
  width: 100%;
  max-width: 41rem;
  margin: 4em auto;
  text-align: left;
}

.accordion {
  background-color: transparent !important;
  outline: 0 !important;
  width: 100%;
  padding: 20px;
  text-align: left;
  border: none;
  cursor: pointer;
  line-height: 40px;
  background-color: transparent;
  color: black; /* Ensure it's the same color as the rest of the text */
  outline: none;
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-top: 1px solid #ccc;
  font-family: inherit; /* Inherit the same font as the rest of the text */
  font-size: 17px; /* Set the same size as the answer text */
  font-weight: normal; /* Ensure consistent font weight */
}

.accordion-icon {
  transition: transform 0.3s ease;
}

.accordion-icon.rotated {
  transform: rotate(180deg);
}

.panel {
  font-size: 17px;
  padding: 0 18px;
  height: 0;
  overflow: hidden;
  transition: height 0.3s ease;
}

.panel.open {
  height: auto;
}

.submit-button {
  background-color: #e31c24;
  color: white;
  border: none;
  padding: 15px 100px;
  margin: 40px;
  text-align: center;
  font-size: 20px;
  border-radius: 5px;
  cursor: pointer;
}

.submit-button:hover {
  background-color: #9b1b20;
}

.full-width-background {
    background-color: white;
}

.info-container {
    display: flex;
    width: 100%;
    max-width: 62em;
    margin: -3em auto 4em;
    padding: 0.8em 20px;
}

.info-item {
  margin-right: 3em;
  font-size: 17px;
}

.prof-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    align-items: flex-end;
}

.prof-item {
    margin: 2em;
    display: flex;
    flex-direction: column;
    align-items: center;
}
</style>


<style>
  .table-container {
    margin-bottom: 4em; /* Ajusta el margen superior según sea necesario */
  }

  .table-container table {
    border-collapse: collapse;
    border: none; /* elimina los bordes de la tabla */
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .table-container td {
    padding: 8px;
    border: 1px solid #ccc;
    text-align: left;
  }

  .table-container th {
    padding: 8px;
    background-color: transparent !important; /* Fondo transparente */
    border: none; /* Sin bordes */
  }

  .table-container thead th {
    background-color: transparent !important; /* Fondo transparente */
  }

  .table-container tbody tr:nth-child(even) {
    background-color: #e7e7e7; /* Cambia el color de fondo para las filas pares */
  }

  /* Elimina los bordes de las celdas exteriores */
  .table-container th:first-child,
  .table-container td:first-child {
    border-left: none;
  }

  .table-container th:last-child,
  .table-container td:last-child {
    border-right: none;
  }

  /* Elimina la última línea horizontal */
  .table-container tr:last-child th,
  .table-container tr:last-child td {
    border-bottom: none;
  }

  /* Elimina la primera línea horizontal */
  .table-container tr:first-child th,
  .table-container tr:first-child td {
    border-top: none;
  }

  /* Elimina la segunda línea horizontal */
  .table-container tr:nth-child(2) th,
  .table-container tr:nth-child(2) td {
    border-top: none;
  }
</style>


<script>
  var accordions = document.querySelectorAll(".accordion");

  accordions.forEach(function(accordion) {
    accordion.addEventListener("click", function() {
      this.classList.toggle("active");
      var icon = this.querySelector(".accordion-icon");
      icon.classList.toggle("rotated");

      var panel = this.nextElementSibling;
      if (panel.style.height) {
        panel.style.height = null;
      } else {
        panel.style.height = panel.scrollHeight + "px";
      }
    });
  });
</script>
