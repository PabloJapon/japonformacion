---
title: "FP Grado Superior"
permalink: /FPSuperior/
layout: default
---


<div class="splash-container">
  <!-- Full-width background image -->
  <img src="/assets/images/CABECERA.png" alt="Full Width Image" class="splash-image">

  <!-- Grey transparent background image -->
  <div class="grey-background"></div>

  <!-- Text title at top right -->
  <div class="top-left">Grado Superior FP</div>

  <!-- Right image upfront -->
  <img src="/assets/images/profesorPablo2.png" alt="Right Image" class="right-image">

  <!-- Text content at bottom left -->
  <div class="bottom-left">
    <p>Con los Grados Superiores ofrecidos por GRUPO JAPÓN, podrás obtener la titulación oficial de Técnico Superior reconocida por la Junta de Andalucía. Estos programas de formación te preparan para acceder al mercado laboral en solo dos años o continuar con estudios universitarios y másteres. Nuestra metodología práctica te proporciona experiencia directa y relevante, sumergiéndote en el rol de técnico desde el inicio.</p>
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

  /* Breakpoint for smaller screens: 1 column, 3 rows */
  @media (max-width: 767px) {
    .splash-container {
      grid-template-columns: 1fr; /* 1 column */
      grid-template-rows: repeat(3, auto); /* 3 rows */
      grid-row-gap: 20px; /* Adjust row spacing */
    }

    /* Adjust the right image to fit in the first column (stacked layout) */
    .right-image {
      grid-row: 2 / 3; /* Place the image in the second row */
      grid-column: 1 / 2; /* Place it in the first column */
      width: 250px; /* Make it responsive */
      transform: none; /* Remove the horizontal transform */
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

  .top-left {
    grid-row: 1 / 2; /* First row */
    grid-column: 1 / 2; /* Now in the first column */
    font-size: 42px;
    font-weight: 700;
    color: white;
    z-index: 10; /* Ensure above background image */
    text-align: left;
    margin-right: 6.25em;
    margin-left: auto;
    padding-left: 20px;
  }

  .grey-background {
    background-color: rgba(127, 127, 127, 0.7); /* Semi-transparent grey */
    position: absolute; /* Ensures it stays within the container */
    top: 0;
    left: 0;
    width: 50%; /* Occupy the left half of the splash container */
    height: 100%; /* Full height of the splash container */
    z-index: 5; /* Below the text but above the background image */
    margin-top: 3.5em;
    transform: translateX(-80px);
  }

  .bottom-left {
    z-index: 10;
    max-width: 600px;
    text-align: left;
    margin-left: auto;
    margin-right: 3em;
    color: white;
    padding: 20px;
    align-self: start;
  }

  .bottom-left p {
    font-size: 17px;
    margin-bottom: 3em;
  }
</style>


<div style="text-align:center;">
  Encuentra tu título FP oficial
</div>

<div class="plans-container">
  <a href="/FPMedio" class="plan">
    <h2>Grados Medios</h2>
    <p>Accede con el título de ESO, Bachillerato o mediante una prueba de acceso.</p>
  </a>

  <a href="/FPSuperior" class="plan">
    <h2>Grados Superiores</h2>
    <p>Accede con el título de Bachillerato, una FP de Grado Medio o Superior o mediante prueba de acceso.</p>
  </a>

  <a href="/payment_form/?plan=Premium" class="plan">
    <h2>Servicios educativos</h2>
    <p>Lo que sea</p>
  </a>
</div>


<div style="text-align:center; margin: 2em;">
  Preguntas frecuentes
</div>

<div class="faq-container">
  <div id="faq" class="faq">
    <button class="accordion">¿Pregunta 1?
      <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
    </button>
    <div class="panel">
      <p>Respuesta a la pregunta 1.</p>
    </div>

    <button class="accordion">¿Pregunta 2?
      <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
    </button>
    <div class="panel">
      <p>Respuesta a la pregunta 2.</p>
    </div>

    <button class="accordion">¿Pregunta 3?
      <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
    </button>
    <div class="panel">
      <p>Respuesta a la pregunta 3.</p>
    </div>

    <button class="accordion">¿Pregunta 4?
      <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
    </button>
    <div class="panel">
      <p>Respuesta a la pregunta 4.</p>
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
