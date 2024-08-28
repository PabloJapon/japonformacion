---
title: "FP Grado Superior"
permalink: /FPSuperior/
layout: default
---

<style>
  .splash-container {
    position: relative;
    width: 100%;
    max-width: none;
    overflow: hidden;
    margin: 2em 0 3em;
    padding: 0;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: 142px 1fr;
    grid-column-gap: 120px;
    grid-row-gap: 20px;
    align-items: end;
  }

  .splash-image {
    width: 100%;
    display: block;
    position: absolute;
    z-index: -1;
    margin: 0;
  }

  .top-right {
    grid-row: 1 / 2;
    grid-column: 2 / 3;
    font-size: 48px;
    font-weight: 500;
    color: white;
    z-index: 10;
  }

  .left-image {
    grid-row: 1 / 3;
    grid-column: 1 / 2;
    width: 370px;
    z-index: 10;
    margin: 1em auto 0;
  }

  .bottom-right {
    grid-row: 2 / 3;
    grid-column: 2 / 3;
    align-self: start;
    color: white;
    z-index: 10;
    max-width: 504px;
  }

  .bottom-right p {
    font-size: 17px;
  }
</style>

<div class="splash-container">
  <img src="/assets/images/CABECERA.png" alt="Full Width Image" class="splash-image">
  <div class="top-right">Grado Superior FP</div>
  <img src="/assets/images/profesorPablo2.png" alt="Left Image" class="left-image">
  <div class="bottom-right">
    <p>
      Con los Grados Superiores ofrecidos por GRUPO JAPÓN, podrás obtener la titulación oficial 
      de Técnico Superior reconocida por la Junta de Andalucía. Estos programas de formación 
      te preparan para acceder al mercado laboral en solo dos años o continuar con estudios 
      universitarios y másteres. Nuestra metodología práctica te proporciona experiencia directa 
      y relevante, sumergiéndote en el rol de técnico desde el inicio.
    </p>
    <button class="plan-button2" onclick="location.href='https://japonformacion.netlify.app/contacto/'">
      Más Información
    </button>
  </div>
</div>

<style>
  img {
    float: right;
    margin: 5px 0 5px 10px;
  }

  .plan-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
  }

  .plan {
    width: 400px;
    padding: 20px;
    border-left: 1px solid #ccc;
    text-align: center;
    margin: 60px 0;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }

  .plan-button2,
  .plan-button,
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

  .plan-button2:hover,
  .plan-button:hover,
  .submit-button:hover {
    background-color: #9b1b20;
  }

  .table-container {
    margin-top: 60px;
  }

  .table-container table {
    border-collapse: collapse;
    border: none;
  }

  .table-container td,
  .table-container th {
    padding: 8px;
  }

  .table-container tbody tr:nth-child(even) {
    background-color: #e0e0e0;
  }

  .dropdown {
    position: relative;
    display: inline-block;
  }

  .dropdown-content {
    display: none;
    position: absolute;
    background-color: #e31c24;
    min-width: 160px;
    box-shadow: 0 8px 16px rgba(0,0,0,0.2);
    z-index: 1;
  }

  .dropdown-content a {
    color: white;
    padding: 12px 16px;
    display: block;
    font-size: 16px;
  }

  .dropdown:hover .dropdown-content {
    display: block;
  }

  .faq-container {
    width: 100%;
    max-width: 41rem;
    margin: 4em auto;
    text-align: left;
  }

  .accordion {
    background-color: transparent;
    width: 100%;
    padding: 20px;
    border: none;
    cursor: pointer;
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
</style>

<div class="plan-container">
  <div class="plan" style="border-left: 0px;">
    <h2>TSAS HUELVA</h2>
    <p>
      Esta App móvil sirve para que los camareros supervisen las comandas, y puedan comunicarse 
      con cocineros y clientes.
    </p>
    <button class="plan-button" onclick="location.href='/payment_form/?plan=Gratis'">Ir a Playstore</button>
    <img src="/assets/images/unsplash-gallery-image-1.jpg" alt="">
  </div>

  <div class="plan">
    <h2>TURISMO HUELVA</h2>
    <p>
      Este es el software que debes instalar en una pantalla de la cocina para que tus cocineros 
      vean las comandas.
    </p>
    <button class="plan-button" onclick="location.href='/payment_form/?plan=Pro'">Descargar</button>
    <img src="/assets/images/unsplash-gallery-image-2.jpg" alt="">
  </div>

  <div class="plan">
    <h2>TURISMO VALVERDE</h2>
    <p>
      Este es el software que instalará el responsable designado, con el que podrá personalizar 
      la app, crear y editar el menú y consultar las estadísticas y datos.
    </p>
    <button class="plan-button" onclick="location.href='/payment_form/?plan=Premium'">Descargar</button>
    <img src="/assets/images/unsplash-gallery-image-3.jpg" alt="">
  </div>
</div>

<div style="text-align:center; margin: 2em;">
  Preguntas frecuentes
</div>

<div class="faq-container">
  <div id="faq" class="faq">
    <button class="accordion">
      ¿Pregunta 1?
      <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
    </button>
    <div class="panel">
      <p>Respuesta a la pregunta 1.</p>
    </div>

    <button class="accordion">
      ¿Pregunta 2?
      <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
    </button>
    <div class="panel">
      <p>Respuesta a la pregunta 2.</p>
    </div>

    <button class="accordion">
      ¿Pregunta 3?
      <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
    </button>
    <div class="panel">
      <p>Respuesta a la pregunta 3.</p>
    </div>

    <button class="accordion">
      ¿Pregunta 4?
      <img src="/assets/images/angulo-hacia-abajo.png" width="20" height="20" class="accordion-icon">
    </button>
    <div class="panel">
      <p>Respuesta a la pregunta 4.</p>
    </div>
  </div>
</div>
