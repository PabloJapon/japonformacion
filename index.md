---
title: "Ciclos de FP oficiales en grupos reducidos"
layout: default
permalink: /
---

<div class="splash-container">
  <!-- Full-width background image -->
  <img src="/assets/images/CABECERA.png" alt="Full Width Image" class="splash-image">

  <!-- Grey transparent background image -->
  <div class="grey-background"></div>

  <!-- Text title at top right -->
  <div class="top-left">Ciclos de FP oficiales en grupos reducidos</div>

  <!-- Right image upfront -->
  <img src="/assets/images/profesorPablo2.png" alt="Right Image" class="right-image">

  <!-- Text content at bottom left -->
  <div class="bottom-left">
    <p>"Menos alumnos, más oportunidades"</p>
    <button class="plan-button2" onclick="location.href='https://japonformacion.netlify.app/contacto/'" style="font-weight: 700;">SOLICITA INFORMACIÓN</button>
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
    grid-template-rows: 250px 1fr; /* Default: 2 rows */
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
    margin-right: 11.4em;
    color: white;
    padding: 20px;
    align-self: start;
  }

  .top-left {
    grid-row: 1 / 2; /* First row */
    grid-column: 1 / 2; /* Now in the first column */
    font-size: 40px;
    font-weight: 700;
    color: white;
    z-index: 10;
    text-align: left;
    margin-right: 1.4em;
    margin-left: auto;
    max-width: 15.5em;
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



<div class="plans-container">

  <a href="/tseas" class="plan">
    <h2>Grados Superiores</h2>
    <p>Accede con el título de Bachillerato, una FP de Grado Medio o Superior o mediante prueba de acceso.</p>
  </a>

  <a href="/tegu" class="plan">
    <h2>Grados Medios</h2>
    <p>Accede con el título de ESO, Bachillerato o mediante una prueba de acceso.</p>
  </a>

  <a href="/campamento_urbano" class="plan">
    <h2>Campamento Urbano</h2>
    <p>"Los viajes del Caracol": una propuesta que combina actividades al aire libre con dinámicas en el aula.</p>
  </a>

  <a href="/aula_matinal" class="plan">
    <h2>Aula Matinal</h2>
    <p>JAPONEDUCA ofrece aula matinal en colegios, brindando a los alumnos un espacio seguro y enriquecedor para comenzar el día, facilitando además la organización de las familias.</p>
  </a>

  <a href="/aula_espera" class="plan">
    <h2>Aula de Espera</h2>
    <p>JAPONEDUCA ofrece un servicio de aulas de espera en colegios, proporcionando un espacio seguro y supervisado para los alumnos, adaptándose a las necesidades familiares y escolares.</p>
  </a>

  <a href="/judo" class="plan">
    <h2>Judo</h2>
    <p>Desde 1994, JAPONSPORT promueve el judo en Huelva para fomentar hábitos saludables y mejorar la calidad de vida.</p>
  </a>

</div>


<div class="features-container">
  <div class="feature">
    <img src="/assets/images/TSEAS.jpg" class="feature-video">
    <div class="feature-content">
      <h2>FP Superior</h2>
      <p>Accede con el título de Bachillerato, una FP de Grado Medio o Superior o mediante prueba de acceso.</p>
      <p style="text-align: center;"><button class="submit-button" onclick="location.href='https://japonformacion.netlify.app/tseas/'">Saber más</button></p>
    </div>
  </div>

  <div class="feature">
    <img src="/assets/images/TEGUpeq.jpg" class="feature-video">
    <div class="feature-content">
      <h2>FP Medio</h2>
      <p>Accede con el título de ESO, Bachillerato o mediante una prueba de acceso.</p>
      <p style="text-align: center;"><button class="submit-button" onclick="location.href='https://japonformacion.netlify.app/tegu/'">Saber más</button></p>
    </div>
  </div>
  
  <div class="feature">
    <img src="/assets/images/aulamatinal_peq.png" class="feature-video">
    <div class="feature-content">
      <h2>Aula Matinal</h2>
      <p>JAPONEDUCA ofrece aula matinal en colegios, brindando a los alumnos un espacio seguro y enriquecedor para comenzar el día, facilitando además la organización de las familias.</p>
      <p style="text-align: center;"><button class="submit-button" onclick="location.href='https://japonformacion.netlify.app/aula_matinal/'">Saber más</button></p>
    </div>
  </div>

  <div class="feature">
    <div class="feature-content">
      <h2>Aula de Espera</h2>
      <p>JAPONEDUCA ofrece un servicio de aulas de espera en colegios, proporcionando un espacio seguro y supervisado para los alumnos, adaptándose a las necesidades familiares y escolares.</p>
      <p style="text-align: center;"><button class="submit-button" onclick="location.href='https://japonformacion.netlify.app/aula_espera/'">Saber más</button></p>
    </div>
    <video src="/assets/videos/Aula_de_Espera_2024-25.mp4" class="feature-video" autoplay loop muted></video>
  </div>

  <div class="feature">
    <img src="/assets/images/tatami_peq.png" class="feature-video">
    <div class="feature-content">
      <h2>Judo</h2>
      <p>Desde 1994, JAPONSPORT promueve el judo en Huelva para fomentar hábitos saludables y mejorar la calidad de vida.</p>
      <p style="text-align: center;"><button class="submit-button" onclick="location.href='https://japonformacion.netlify.app/judo/'">Saber más</button></p>
    </div>
  </div>
</div>

<div style="text-align:center; margin-top:7em">
  ¿Dudas? No te las guardes, pregúntanos.
</div>

<form name="contact" action="/_pages/success.html" method="POST" data-netlify="true" class="contact-form">
  <input type="hidden" name="subject" id="subject" value="Mensaje de (nombre)" />
  <input type="hidden" name="page" value="Página Principal" />
  
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
    var page = document.querySelector('input[name="page"]').value;
    var subjectField = document.getElementById('subject');
    subjectField.value = `Mensaje de ${name} - Teléfono: ${phone} - Página: ${page}`;
  });
</script>



<style>
.plans-container {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  max-width: 1400px;
  margin: 0 auto;
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
  margin: 0;
  padding: 0.5em;
  color: inherit;
}

.video-container {
  margin: 0 auto;
  text-align: center;
}

.features-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  max-width: 1400px;
  margin: 0 auto;
}

/* Default styling for larger screens */
.feature {
  display: flex;
  align-items: center;
  padding: 20px;
  margin-bottom: 40px;
}

.feature img {
  order: 0;
}

.feature:nth-child(even) img {
  order: 1;
}

/* Media query for smaller screens (e.g., below 768px) */
@media (max-width: 768px) {
  .feature {
    flex-direction: column;
  }
  
  /* Ensure images are always at the top on small screens */
  .feature img {
    order: -1 !important;
    width: 100%; /* Make images take full width on smaller screens if needed */
  }
  .feature video {
    order: -1 !important;
    width: 100%; /* Make images take full width on smaller screens if needed */
  }
}

.feature-content {
  display: flex;
  flex-direction: column;
  padding: 20px;
  text-align: center;
}

.feature-video {
  border-radius: 40px;
  width: 50%;
  height: auto;
  padding: 1em;
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
  color: black;
  outline: none;
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-top: 1px solid #ccc;
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

.plan-button {
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
