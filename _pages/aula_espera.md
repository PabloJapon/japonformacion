---
title: "Aula de Espera"
permalink: /aula_espera/
layout: default
---

<style>
  .splash-container {
    display: grid;
    grid-template-columns: 1fr; /* Single column layout */
    grid-template-rows: auto auto; /* Two rows: title and content */
    position: relative;
    width: 100%;
    max-width: none;
    overflow: hidden;
    margin: 0;
    padding: 0;
    margin-top: 5em;
  }

  .splash-image {
    width: 100%;
    display: block;
    grid-column: 1 / -1; /* Span across all columns */
  }

  .top-right {
    grid-row: 1; /* First row */
    grid-column: 1; /* First column */
    justify-self: end; /* Align to the end of the column */
    align-self: start; /* Align to the start of the row */
    font-size: 1.5em;
    background-color: rgba(255, 255, 255, 0.8);
    padding: 5px 10px;
    border-radius: 5px;
    z-index: 10;
    position: relative; /* Ensure stacking context */
  }

  .left-image {
    grid-row: 2; /* Second row */
    grid-column: 1; /* First column */
    justify-self: start; /* Align to the start of the column */
    align-self: center; /* Align to the center of the row */
    max-width: 40%;
    z-index: 10;
    position: relative; /* Ensure stacking context */
  }

  .bottom-right {
    grid-row: 2; /* Second row */
    grid-column: 1; /* First column */
    justify-self: end; /* Align to the end of the column */
    align-self: center; /* Align to the center of the row */
    max-width: 55%;
    text-align: left;
    z-index: 10;
    position: relative; /* Ensure stacking context */
    color: white;
  }

  .bottom-right p {
    font-size: 17px;
  }
</style>

<div class="splash-container">
  <!-- Full-width background image -->
  <img src="/assets/images/CABECERA.png" alt="Full Width Image" class="splash-image" style="margin-bottom: 0;">

  <!-- Text title at top right -->
  <div class="top-right">Aula de Espera</div>

  <!-- Left image upfront -->
  <img src="/assets/images/profesorPablo2.png" alt="Left Image" class="left-image">

  <!-- Text content at bottom right -->
  <div class="bottom-right">
    <p>JAPONEDUCA forma parte del GRUPO JAPÓN y se dedica a ofrecer servicios educativos, ocio y tiempo libre.</p>
    
    <p>Nuestro programa educativo se adapta a los horarios familiares y fortalece la autonomía de los centros escolares bajo el Plan de Apertura de Centros.</p>
    
    <p>Organizamos actividades como aula matinal, comedor, deporte escolar, apoyo lingüístico y proyectos lectores, siguiendo los programas educativos de la Junta de Andalucía.</p>
    
    <p>Contamos con un equipo profesional dedicado a diseñar y llevar a cabo actividades adaptadas a las necesidades de alumnos y centros educativos.</p>
  </div>
</div>






<div style="text-align:center;">
  <button class="plan-button" onclick="location.href='https://app.grupojapon.es/index.php/registro'">Inscríbete</button>
</div>


<div class="table-container">
  <table>
    <thead>
      <tr>
        <th style="width: 200px;text-align: center;"><h2>Centro</h2></th>
        <th style="width: 200px;text-align: center;"><h2>Horario</h2></th>
        <th style="width: 200px;text-align: center;"><h2>Cuota</h2></th>
        <th style="width: 200px;text-align: center;"><h2>Fecha de inicio</h2></th>
        <th style="width: 200px;text-align: center;"><h2>Enlaces</h2></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="width: 200px;text-align: center;">CEIP El Puntal</td>
        <td style="width: 200px;text-align: center;">De lunes a viernes de 14:00 a 15:30 h</td>
        <td style="width: 200px;text-align: center;">
          <ul style="list-style-type: disc; padding-left: 40px; margin: 0; text-align: left;">
            <li>30 €/mes*</li>
            <li>3 € - días sueltos</li>
          </ul>
        </td>
        <td style="width: 200px;text-align: center;">11/09/2024</td>
        <td style="width: 200px;text-align: center;">
          <ul style="list-style-type: disc; padding-left: 40px; margin: 0; text-align: left;">
            <li><a href="/assets/documents/Nota_informativa_Aula_de_Espera_Ceip_El_Puntal_2023-24.pdf">Más información</a></li>
            <li><a href="https://app.grupojapon.es/index.php/registro">Inscríbete</a></li>
          </ul>
        </td>
      </tr>
      <tr>
        <td style="width: 200px;text-align: center;">CEIP Tierno Galván</td>
        <td style="width: 200px;text-align: center;">De lunes a viernes de 14:00 a 15:00 h</td>
        <td style="width: 200px;text-align: center;">
          <ul style="list-style-type: disc; padding-left: 40px; margin: 0; text-align: left;">
            <li>25 €/mes*</li>
            <li>3 € - días sueltos</li>
          </ul>
        </td>
        <td style="width: 200px;text-align: center;">11/09/2024</td>
        <td style="width: 200px;text-align: center;">
          <ul style="list-style-type: disc; padding-left: 40px; margin: 0; text-align: left;">
            <li><a href="/assets/documents/Nota_informativa_Aula_de_Espera_Ceip_El_Puntal_2023-24.pdf">Más información</a></li>
            <li><a href="https://app.grupojapon.es/index.php/registro">Inscríbete</a></li>
          </ul>
        </td>
      </tr>
      <tr>
        <td style="width: 200px;text-align: center;">CEIP Prácticas</td>
        <td style="width: 200px;text-align: center;">De lunes a viernes de 14:00 a 15:30 h</td>
        <td style="width: 200px;text-align: center;">
          <ul style="list-style-type: disc; padding-left: 40px; margin: 0; text-align: left;">
            <li>30 €/mes*</li>
            <li>3 € - días sueltos</li>
          </ul>
        </td>
        <td style="width: 200px;text-align: center;">11/09/2024</td>
        <td style="width: 200px;text-align: center;">
          <ul style="list-style-type: disc; padding-left: 40px; margin: 0; text-align: left;">
            <li><a href="/assets/documents/Nota_informativa_Aula_de_Espera_Ceip_El_Puntal_2023-24.pdf">Más información</a></li>
            <li><a href="https://app.grupojapon.es/index.php/registro">Inscríbete</a></li>
          </ul>
        </td>
      </tr>
      <tr>
        <td style="width: 200px;text-align: center;">CEIP Pura Domínguez</td>
        <td style="width: 200px;text-align: center;">De lunes a viernes de 14:00 a 15:30 h</td>
        <td style="width: 200px;text-align: center;">
          <ul style="list-style-type: disc; padding-left: 40px; margin: 0; text-align: left;">
            <li>30 €/mes*</li>
            <li>3 € - días sueltos</li>
          </ul>
        </td>
        <td style="width: 200px;text-align: center;">11/09/2024</td>
        <td style="width: 200px;text-align: center;">
          <ul style="list-style-type: disc; padding-left: 40px; margin: 0; text-align: left;">
            <li><a href="/assets/documents/Nota_informativa_Aula_de_Espera_Ceip_El_Puntal_2023-24.pdf">Más información</a></li>
            <li><a href="https://app.grupojapon.es/index.php/registro">Inscríbete</a></li>
          </ul>
        </td>
      </tr>
      <tr>
        <td style="width: 200px;text-align: center;">CEIP Antonio Guerrero</td>
        <td style="width: 200px;text-align: center;">De lunes a viernes de 14:00 a 15:30 h</td>
        <td style="width: 200px;text-align: center;">
          <ul style="list-style-type: disc; padding-left: 40px; margin: 0; text-align: left;">
            <li>30 €/mes*</li>
            <li>3 € - días sueltos</li>
          </ul>
        </td>
        <td style="width: 200px;text-align: center;">11/09/2024</td>
        <td style="width: 200px;text-align: center;">
          <ul style="list-style-type: disc; padding-left: 40px; margin: 0; text-align: left;">
            <li><a href="/assets/documents/Nota_informativa_Aula_de_Espera_Ceip_El_Puntal_2023-24.pdf">Más información</a></li>
            <li><a href="https://app.grupojapon.es/index.php/registro">Inscríbete</a></li>
          </ul>
        </td>
      </tr>
      <tr>
        <td style="width: 200px;text-align: center;">CEIP Doce de Octubre</td>
        <td style="width: 200px;text-align: center;">De lunes a viernes de 14:00 a 15:30 h</td>
        <td style="width: 200px;text-align: center;">
          <ul style="list-style-type: disc; padding-left: 40px; margin: 0; text-align: left;">
            <li>30 €/mes*</li>
            <li>3 € - días sueltos</li>
          </ul>
        </td>
        <td style="width: 200px;text-align: center;">11/09/2024</td>
        <td style="width: 200px;text-align: center;">
          <ul style="list-style-type: disc; padding-left: 40px; margin: 0; text-align: left;">
            <li><a href="/assets/documents/Nota_informativa_Aula_de_Espera_Ceip_El_Puntal_2023-24.pdf">Más información</a></li>
            <li><a href="https://app.grupojapon.es/index.php/registro">Inscríbete</a></li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</div>

<div style="font-size: 17px;text-align: center;font-style: italic;">
  <p>*Bonificación del 10% para el/la segundo/a hermano/a</p>
</div>


<style>
  img {
    float: right;
    margin-left: 10px;
    margin-bottom: 5px;
    margin-top: 5px;
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
    margin-top: 30px; /* Ajusta el margen superior según sea necesario */
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
