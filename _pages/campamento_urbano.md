---
title: "Campamento Urbano"
permalink: /campamento_urbano/
layout: default
---



<div class="splash-container">
  <!-- Full-width background image -->
  <img src="/assets/images/aulamatinal.png" alt="Full Width Image" class="splash-image">

  <!-- Grey transparent background image -->
  <div class="grey-background"></div>

  <!-- Text title at top right -->
  <div class="top-left">Campamento Urbano</div>

  <!-- Right image upfront -->
  <img src="/assets/images/Caracol.png" alt="Right Image" class="right-image">

  <!-- Text content at bottom left -->
  <div class="bottom-left">
    <p>Grupo Japón organiza en el CEIP Prácticas su campamento urbano “Los viajes del Caracol”, una propuesta que combina actividades al aire libre con dinámicas en el aula, garantizando una experiencia divertida, segura y enriquecedora para todos los participantes.</p>
    <button class="plan-button2" onclick="location.href='https://forms.gle/RddqdtHEoDhM2YPXA'" style="font-weight: 700;">INSCRÍBETE</button>
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
    font-size: 42px;
    font-weight: 700;
    color: white;
    z-index: 10; /* Ensure above background image */
    text-align: left;
    margin-right: 4.25em;
    margin-left: auto;
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

<div style="text-align:center; margin: 2em;">
  ¿EN QUÉ CONSISTE?
</div>

<p style="text-align: center;font-size: 17px;margin: 2em auto 4em;max-width: 78em;">
Con la llegada del verano, también llegan las vacaciones escolares. Para muchas familias, esto puede representar un reto, ya que los padres y madres deben seguir trabajando y no siempre es fácil encontrar un lugar seguro y enriquecedor donde dejar a sus hijos e hijas durante el día.
<strong>Grupo Japón</strong> presenta una excelente solución: un <strong>Campamento Urbano</strong> que se desarrollará en el propio colegio de los niños y niñas, rodeados de sus compañeros y compañeras, bajo la supervisión de monitores especializados, y con una amplia variedad de actividades lúdicas y educativas. Alternando el tiempo al aire libre con dinámicas en el aula, este campamento garantiza una experiencia divertida, segura y enriquecedora.
Además, para aquellas familias que necesitan comenzar su jornada laboral antes de las 9:00 h (inicio del campamento), se ofrece también un servicio de <strong>Aula Matinal</strong> desde las 7:30 h.
</p>

<div style="text-align:center; margin: 2em;">
  ¿DÓNDE?
</div>

<p style="text-align: center;font-size: 17px;margin: 2em auto 4em;max-width: 78em;">
El campamento se realizará en las instalaciones del <strong>CEIP PRÁCTICAS (Huelva)</strong>.
Contaremos con todo el material necesario para las actividades: material escolar, deportivo, audiovisual, de identificación, y de primeros auxilios.
</p>

<div style="text-align:center; margin: 2em;">
  HORARIOS
</div>

<div class="table-container">
  <table>
    <thead>
      <tr>
        <th style="width: 200px;text-align: center;"><h2>Horario</h2></th>
        <th style="width: 570px;text-align: center;"><h2>Actividad</h2></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="width: 200px;text-align: center;">7:30 – 9:00</td>
        <td style="width: 570px;text-align: center;"><strong>Aula Matinal</strong> (con desayuno)</td>
      </tr>
      <tr>
        <td style="width: 200px;text-align: center;">9:00 – 9:30</td>
        <td style="width: 570px;text-align: center;"><strong>Buenos días</strong> en el patio</td>
      </tr>
      <tr>
        <td style="width: 200px;text-align: center;">9:30 – 10:30</td>
        <td style="width: 570px;text-align: center;"><strong>Juegos deportivos</strong> en el patio</td>
      </tr>
      <tr>
        <td style="width: 200px;text-align: center;">10:30 – 11:00</td>
        <td style="width: 570px;text-align: center;"><strong>Concursos</strong> en clase (Are you ready?)</td>
      </tr>
      <tr>
        <td style="width: 200px;text-align: center;">11:00 – 12:00</td>
        <td style="width: 570px;text-align: center;"><strong>Talleres creativos</strong>: lectura, idiomas, manualidades, juegos</td>
      </tr>
      <tr>
        <td style="width: 200px;text-align: center;">12:00 – 12:30</td>
        <td style="width: 570px;text-align: center;"><strong>Descanso y tentempié</strong> en el patio</td>
      </tr>
      <tr>
        <td style="width: 200px;text-align: center;">12:30 – 14:00</td>
        <td style="width: 570px;text-align: center;"><strong>Taller temático</strong>: “Los viajes del caracol”</td>
      </tr>
      <tr>
        <td style="width: 200px;text-align: center;">14:00 – 15:00</td>
        <td style="width: 570px;text-align: center;"><strong>Despedida</strong>: juegos, canciones, etc.</td>
      </tr>
    </tbody>
  </table>
</div>






<div style="text-align:center; margin: 2em;">
  PARTICIPANTES
</div>

<p style="text-align: center;font-size: 17px;margin: 2em auto 2em;max-width: 78em;">
El campamento está dirigido a niños y niñas de entre <strong>3 y 12 años</strong>. Se organizarán en grupos por edades para facilitar el trabajo y fomentar la cohesión grupal:
</p>

<div style="text-align: center;margin-bottom: 3em;">
  <div style="display: inline-block; text-align: left; font-size: 17px;">
    <ul style="list-style-type: disc; padding-left: 20px; margin: 0;">
      <li><strong>Pequeños (Naranjas)</strong>: 3, 4 y 5 años</li>
      <li><strong>Medianos (Verdes)</strong>: 6, 7 y 8 años</li>
      <li><strong>Mayores (Azules)</strong>: 9 a 12 años</li>
    </ul>
  </div>
</div>





<div style="text-align:center; margin: 2em;">
  ACTIVIDADES
</div>

<p style="text-align: center;font-size: 17px;margin: 2em auto 0em;max-width: 78em;">
Este verano viajaremos con nuestra mascota al mundo mágico de: 🎪 <strong>"EL CIRCO"</strong>
</p>
<p style="text-align: center;font-size: 17px;margin: 0.5em auto 2em;max-width: 78em;">
Donde aprenderemos, jugaremos, bailaremos, cantaremos y nos divertiremos como verdaderos artistas. Entre las actividades destacadas están:
</p>

<div style="text-align: center;margin-bottom: 3em;">
  <div style="display: inline-block; text-align: left; font-size: 17px;max-width: 60em;">
    <ul style="list-style-type: disc; padding-left: 20px; margin: 0;">
      <li><strong>Construimos nuestro circo</strong>. Diseñaremos y crearemos nuestro propio circo con jaulas, domadores, animales y más, utilizando murales, juegos y talleres.</li>
      <li><strong>Animales salvajes</strong>. Descubriremos el mundo de los animales salvajes: dónde viven, qué comen, cómo cuidarlos, y la importancia de proteger su hábitat.</li>
      <li><strong>Creamos nuestra pista de circo</strong>. A través del reciclaje y la imaginación, seremos payasos, magos, malabaristas, domadores y más, aprendiendo que no hacen falta juguetes caros para divertirse.</li>
      <li><strong>El espectáculo final</strong>. Montaremos nuestro propio show de circo. Crearemos bolas de malabares, vestuarios, disfraces, instrumentos musicales, cariocas... ¡y lo daremos todo sobre el escenario!</li>
    </ul>
  </div>
</div>



<div style="text-align:center; margin: 2em;">
  Y ADEMÁS...
</div>

<p style="text-align: center;;font-size: 17px">
Cada día, los niños y niñas disfrutarán de un sinfín de actividades variadas, como:
</p>

<div style="text-align: center;margin-bottom: 3em;">
  <div style="display: inline-block; text-align: left; font-size: 17px;">
    <ul style="list-style-type: disc; padding-left: 20px; margin: 0;">
      <li>Juegos deportivos y al aire libre</li>
      <li>Juegos de ingenio y lógica</li>
      <li>Cuentacuentos</li>
      <li>Actividades de expresión corporal y artística</li>
      <li>¡Y muchas sorpresas más!</li>
    </ul>
  </div>
</div>


<div style="text-align:center; margin: 2em;">
  PRECIOS
</div>

<div class="table-container">
  <table>
    <tbody>
      <tr>
        <td style="width: 500px;text-align: center;">Semana de junio con Aula Matinal</td>
        <td style="width: 200px;text-align: center;">70 €</td>
      </tr>
      <tr>
        <td style="width: 500px;text-align: center;">Mes de Julio</td>
        <td style="width: 200px;text-align: center;">190 €</td>
      </tr>
      <tr>
        <td style="width: 500px;text-align: center;">Mes de julio del 2º hermano/a</td>
        <td style="width: 200px;text-align: center;">155 €</td>
      </tr>
      <tr>
        <td style="width: 500px;text-align: center;">Aula matinal al mes</td>
        <td style="width: 200px;text-align: center;">30 €</td>
      </tr>
      <tr>
        <td style="width: 500px;text-align: center;">Semana de Campamento con Aula Matinal</td>
        <td style="width: 200px;text-align: center;">70 €</td>
      </tr>
      <tr>
        <td style="width: 500px;text-align: center;">Día suelto de Campamento con Aula Matinal</td>
        <td style="width: 200px;text-align: center;">30 €</td>
      </tr>
    </tbody>
  </table>
</div>


<div class="plan-container">

  <!-- TARJETA 1: CAMPAMENTO MENSUAL -->
  <div class="plan plan-highlight">
    <h2>Campamento mensual (con Aula Matinal incluida)</h2>
    <ul class="price-list">
      <li><strong>Mes de julio</strong> – 190 €</li>
      <li><strong>Mes de julio (2º hermano/a)</strong> – 155 €</li>
    </ul>
  </div>

  <!-- TARJETA 2: SEMANAL Y DÍA SUELTO -->
  <div class="plan plan-highlight">
    <h2>Campamento semanal o diario (con Aula Matinal incluida)</h2>
    <ul class="price-list">
      <li><strong>Semana suelta (junio o julio)</strong> – 70 €</li>
      <li><strong>Día suelto</strong> – 30 €</li>
    </ul>
  </div>

  <!-- TARJETA 3: SOLO AULA MATINAL -->
  <div class="plan plan-highlight">
    <h2>Extras y descuentos</h2>
    <ul class="price-list">
      <li><strong>Aula Matinal mensual (sin campamento)</strong> – 30 €</li>
    </ul>
  </div>

</div>






<p style="text-align: center;;font-size: 17px">
El precio cubre todas las actividades que se llevarán a cabo , con todos los materiales.
</p>



<p style="text-align: center;">
  <button class="plan-button2" onclick="location.href='https://forms.gle/RddqdtHEoDhM2YPXA'" style="font-weight: 700;margin: 0em 0 4em;">INSCRÍBETE</button>
</p>





<div style="text-align:center; margin: 2em;">
    Preguntas frecuentes
  </div>
  
  <div class="faq-container">
    <div id="faq" class="faq">
      <button class="accordion">¿Cuándo se abre el periodo de inscripción?
        <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
      </button>
      <div class="panel">
        <p>A partir del 20 de mayo 2025.</p>
      </div>
  
      <button class="accordion">¿Puedo elegir sólo el servicio de Campamento sin Aula Matinal?
        <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
      </button>
      <div class="panel">
        <p>Sí. Si optas únicamente por el campamento, el horario será de 9:00 a 15:00 horas.</p>
      </div>
  
      <button class="accordion">¿Puedo elegir días sueltos?
        <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
      </button>
      <div class="panel">
        <p>Sí. En el formulario de inscripción, encontrarás la opción para seleccionar días específicos según tus necesidades.</p>
      </div>
  
      <button class="accordion">¿Hay descuentos por hermanos?
        <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
      </button>
      <div class="panel">
        <p>Sí. A partir del segundo hermano/a, se aplicará un descuento en la cuota.</p>
      </div>
  
      <button class="accordion">¿Cuál es la forma de pago?
        <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
      </button>
      <div class="panel">
        <p>Mediante ingreso o transferencia bancaria. Se realizará por anticipado al realizar la inscripción.</p>
      </div>
  
      <button class="accordion">¿Cómo puedo tener más información?
        <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
      </button>
      <div class="panel">
        <p>Enviado un email a través de nuestro correo: contacto@grupojapon.es</p>
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
.plans-container {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}

.plan {
  width: 400px;
  padding: 20px;
  border: 1px solid #ccc;
  border-radius: 8px;
  background: white;
  text-align: center;
  margin: 60px 12px;
  text-decoration: none;
  color: inherit;
  transition: background-color 0.3s ease, box-shadow 0.3s ease;
}

.plan:hover {
  background-color: #f0f0f0;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  text-decoration: none;
}

.plan h2, .plan p {
  color: inherit;
}

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

.plan-button:hover {
  background-color: #9b1b20;
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


<style>
.plan-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  margin-top: 40px;
  gap: 30px;
}

.plan {
  width: 320px;
  border: 1px solid #ccc;
  border-radius: 10px;
  padding: 30px 20px;
  background-color: #fff;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
  text-align: center;
}

.plan h2 {
  font-size: 22px;
  margin-bottom: 1.5em;
  color: #333;
}

.price-list {
  list-style-type: disc;
  padding-left: 20px;
  text-align: left;
  font-size: 17px;
  color: #555;
  margin: 0;
}

.price-list li {
  margin-bottom: 1em;
}

.plan-highlight {
  border-color: #e31c24; /* brand red */
}

@media (max-width: 768px) {
  .plan {
    width: 90%;
  }
}

</style>
