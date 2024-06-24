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

<div class="plan-container">
  <div class="plan">
    <h2>Grados Medios</h2>
    <button class="plan-button" onclick="location.href='/payment_form/?plan=Gratis'">Empieza</button>
    <p>Accede con el título de ESO, Bachillerato o mediante una prueba de acceso.</p>
  </div>

  <div class="plan">
    <h2>Grados Superiores</h2>
    <button class="plan-button" onclick="location.href='/payment_form/?plan=Pro'">Empieza</button>
    <p>Accede con el título de Bachillerato, una FP de Grado Medio o Superior o mediante prueba de acceso.</p>
  </div>

  <div class="plan">
    <h2>Cursos tiempo libre</h2>
    <h3>50€</h3>
    <button class="plan-button" onclick="location.href='/payment_form/?plan=Premium'">Empieza</button>
    <p>Lo que sea</p>
  </div>
</div>

<div style="margin: 0 auto; text-align:center;">
  <video style="border-radius: 20px; width: 100%; height: auto;" autoplay loop muted>
    <source src="/assets/videos/your-video.mp4" type="video/mp4">
  </video>
</div>

<div class="plan-container1">
  <div class="plan1" style="border-left: 0px;">
    <video width="900" height="544" style="border-radius: 40px; width: 100%; height: auto; padding: 1em;" autoplay loop muted>
      <source src="/assets/videos/your-video.mp4" type="video/mp4">
    </video>
    <div class="plan1" style="display: flex; flex-direction: column;">
      <h2>Actualiza tu menú automáticamente y en cualquier momento</h2>
      <p>Personalízalo usando las imágenes, colores e iconos que más te representen. Y si un día no puedes servir un plato, no te preocupes, desactívalo para que no aparezca en el menú!</p>
    </div>
  </div>

  <div class="plan1">
    <div class="plan1" style="display: flex; flex-direction: column;">
      <h2>Máxima sincronización, ¡no pierdas más tiempo!</h2>
      <p>Cuando un cliente realice un pedido, este irá directamente a las pantallas de la cocina, donde los cocineros tan solo haciendo un click, harán saber al camarero cuando puede ir a recogerlo.</p>
    </div>
    <video width="900" height="544" style="border-radius: 40px; width: 100%; height: auto; padding: 1em;" autoplay loop muted>
      <source src="/assets/videos/your-video.mp4" type="video/mp4">
    </video>
  </div>

  <div class="plan1" style="border-left: 0px;">
    <video width="900" height="544" style="border-radius: 40px; width: 100%; height: auto; padding: 1em;" autoplay loop muted>
      <source src="/assets/videos/your-video.mp4" type="video/mp4">
    </video>
    <div class="plan1" style="display: flex; flex-direction: column;">
      <h2>Saca el mayor provecho a tus datos</h2>
      <p>Consulta estadísticas de todo tipo: a qué horas generas más dinero, cuál fue el plato más pedido la semana pasada, ¿tienen tus postres el precio óptimo?</p>
    </div>
  </div>

  <div class="plan1">
    <div class="plan1" style="display: flex; flex-direction: column;">
      <h2>¡Sin líos!</h2>
      <p>¿Tienes varios menús? No te preocupes, añádelos todos y tú decides cuándo se muestra cada uno.</p>
    </div>
    <video width="900" height="544" style="border-radius: 40px; width: 100%; height: auto; padding: 1em;" autoplay loop muted>
      <source src="/assets/videos/your-video.mp4" type="video/mp4">
    </video>
  </div>
</div>

<div style="text-align:center; margin: 2em;">
  Preguntas frecuentes
</div>

<div style="margin: 4em auto; text-align:center;">
  <div id="faq" class="faq" style="margin-top: 20px; margin: 0 auto;">
    <button class="accordion">¿Pregunta 1?
      <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="butImagen" style="vertical-align: middle;">
    </button>
    <div class="panel">
      <p>Respuesta a la pregunta 1.</p>
    </div>

    <button class="accordion">¿Pregunta 2?
      <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="butImagen" style="vertical-align: middle;">
    </button>
    <div class="panel">
      <p>Respuesta a la pregunta 2.</p>
    </div>

    <button class="accordion">¿Pregunta 3?
      <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="butImagen" style="vertical-align: middle;">
    </button>
    <div class="panel">
      <p>Respuesta a la pregunta 3.</p>
    </div>

    <button class="accordion">¿Pregunta 4?
      <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="butImagen" style="vertical-align: middle;">
    </button>
    <div class="panel">
      <p>Respuesta a la pregunta 4.</p>
    </div>
  </div>
</div>

<style>
.plan-container1 {
  display: flex;
  flex-wrap: wrap;
  flex-direction: column;
  align-content: center;
}

.plan1 {
  padding: 20px;
  display: grid;
  grid-template-columns: 1fr 1fr;
  align-items: center;
}

.plan-button {
  background-color: #e31c24;
  color: white;
  border: none;
  padding: 15px 80px;
  margin: 40px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 22px;
  border-radius: 5px;
  cursor: pointer;
}

.faq {
  width: 100%;
  max-width: 41rem;
  margin-left: auto;
  margin-right: auto;
  margin-top: 4em;
  text-align: left;
  border-bottom: 1px solid #ccc;
}

.faq1_question {
  border-top: 1px solid var(--gray-200);
  cursor: pointer;
  justify-content: space-between;
  align-items: center;
  padding-top: 1.5rem;
  padding-bottom: 1rem;
  display: flex;
}

.accordion {
  width: 100%;
  padding: 20px 20px;
  text-align: left;
  border: none;
  cursor: pointer;
  text-decoration: none;
  line-height: 40px;
  outline: none;
  border-top: 1px solid #ccc;
}

.butImagen {
  transition: transform 0.3s ease;
}

.butImagen.rotated {
  transform: rotate(180deg);
}

img {
  float: right;
  margin-left: 10px;
  margin-bottom: 5px;
  margin-top: 5px;
}

.accordion:focus, .accordion:active {
  outline: none;
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

.plan-container {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}

.plan {
  width: 400px; /* Ancho deseado de cada plan */
  padding: 20px;
  border: 1px solid #ccc;
  border-radius: 8px;
  background: white;
  text-align: center;
  margin-bottom: 60px; /* Espacio inferior entre cada plan */
  margin-top: 60px;
  margin-left: 12px;
  margin-right: 12px;
}

.plan-button2 {
  background-color: #e31c24; /* Cambio de color */
  color: white;
  border: none;
  padding: 10px 50px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  border-radius: 5px;
  cursor: pointer;
}

.plan-button2:hover {
  background-color: #9b1b20; /* Cambio de color en el hover */
}

.plan-button {
  background-color: #e31c24; /* Cambio de color */
  color: white;
  border: none;
  padding: 15px 100px;
  margin: 40px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 20px;
  border-radius: 5px;
  cursor: pointer;
}

.plan-button:hover {
  background-color: #9b1b20; /* Cambio de color en el hover */
}
  
  .table-container {
  margin-top: 60px; /* Ajusta el margen superior según sea necesario */
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
  background-color: #e0e0e0; /* Cambia el color de fondo para las filas pares */
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
  var acc = document.querySelectorAll(".accordion");

  acc.forEach(function(item) {
    item.addEventListener("click", function() {
      this.classList.toggle("active");
      this.querySelector("img").classList.toggle("rotated");

      var panel = this.nextElementSibling;
      if (panel.style.height) {
        panel.style.height = null;
      } else {
        panel.style.height = panel.scrollHeight + "px";
      }
    });
  });
</script>
