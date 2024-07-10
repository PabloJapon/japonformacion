---
title: "Ciclos formativos de grado medio y superior"
layout: splash
header:
  overlay_image: /assets/images/page-header-teaser.png
  #overlay_filter: rgba(102,153,255,0.5)
  actions:
    - label: "Solicita información"
      url: "https://japonformacion.netlify.app/contacto/"
excerpt: "Clases presenciales y en horario de mañanas"
---

<div style="text-align:center;">
  Encuentra tu título FP oficial
</div>

<div class="plans-container">
  <a href="/payment_form/?plan=Gratis" class="plan">
    <h2>Grados Medios</h2>
    <p>Accede con el título de ESO, Bachillerato o mediante una prueba de acceso.</p>
  </a>

  <a href="/payment_form/?plan=Pro" class="plan">
    <h2>Grados Superiores</h2>
    <p>Accede con el título de Bachillerato, una FP de Grado Medio o Superior o mediante prueba de acceso.</p>
  </a>

  <a href="/payment_form/?plan=Premium" class="plan">
    <h2>Servicios educativos</h2>
    <p>Lo que sea</p>
  </a>
</div>

<div class="video-container">
  <video autoplay loop muted style="border-radius: 20px; width: 100%; height: auto;">
    <source src="/assets/videos/your-video.mp4" type="video/mp4">
  </video>
</div>

<div class="features-container">
  <div class="feature">
    <video autoplay loop muted class="feature-video">
      <source src="/assets/videos/your-video.mp4" type="video/mp4">
    </video>
    <div class="feature-content">
      <h2>Actualiza tu menú automáticamente y en cualquier momento</h2>
      <p>Personalízalo usando las imágenes, colores e iconos que más te representen. Y si un día no puedes servir un plato, no te preocupes, desactívalo para que no aparezca en el menú!</p>
    </div>
  </div>

  <div class="feature">
    <div class="feature-content">
      <h2>Máxima sincronización, ¡no pierdas más tiempo!</h2>
      <p>Cuando un cliente realice un pedido, este irá directamente a las pantallas de la cocina, donde los cocineros tan solo haciendo un click, harán saber al camarero cuando puede ir a recogerlo.</p>
    </div>
    <video autoplay loop muted class="feature-video">
      <source src="/assets/videos/your-video.mp4" type="video/mp4">
    </video>
  </div>

  <div class="feature">
    <video autoplay loop muted class="feature-video">
      <source src="/assets/videos/your-video.mp4" type="video/mp4">
    </video>
    <div class="feature-content">
      <h2>Saca el mayor provecho a tus datos</h2>
      <p>Consulta estadísticas de todo tipo: a qué horas generas más dinero, cuál fue el plato más pedido la semana pasada, ¿tienen tus postres el precio óptimo?</p>
    </div>
  </div>

  <div class="feature">
    <div class="feature-content">
      <h2>¡Sin líos!</h2>
      <p>¿Tienes varios menús? No te preocupes, añádelos todos y tú decides cuándo se muestra cada uno.</p>
    </div>
    <video autoplay loop muted class="feature-video">
      <source src="/assets/videos/your-video.mp4" type="video/mp4">
    </video>
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
    <button type="submit">Enviar</button>
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
  margin: 0;
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
}

.feature {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 20px;
  margin-bottom: 40px;
}

.feature-content {
  display: flex;
  flex-direction: column;
  padding: 20px;
  text-align: center;
}

.feature-video {
  border-radius: 40px;
  width: 100%;
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
