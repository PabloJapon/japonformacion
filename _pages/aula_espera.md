---
title: "Aula de Espera"
permalink: /aula_espera/
---

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aula de Espera</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    .header {
      text-align: center;
      padding: 20px;
      background-color: #f0f0f0;
    }
    .header h1 {
      margin: 0;
      font-size: 2em;
    }
    .content {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      padding: 20px;
    }
    .content .left-column {
      flex: 0 0 40%;
      max-width: 40%;
      margin-bottom: 20px;
    }
    .content .right-column {
      flex: 0 0 55%;
      max-width: 55%;
    }
    .content img {
      width: 100%;
      display: block;
      margin-bottom: 10px;
    }
    .top-right {
      font-size: 1.5em;
      margin-top: 20px;
      background-color: rgba(255, 255, 255, 0.8);
      padding: 5px 10px;
      border-radius: 5px;
      text-align: right;
    }
    .button-container {
      text-align: center;
      margin-top: 20px;
    }
    .plan-container {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      margin-top: 20px;
    }
    .plan {
      width: 400px;
      padding: 20px;
      border: 1px solid #ccc;
      border-radius: 8px;
      background: white;
      text-align: center;
      margin-bottom: 20px;
      margin-right: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .plan h2 {
      margin-top: 0;
    }
    .plan-button {
      background-color: #e31c24;
      color: white;
      border: none;
      padding: 15px 50px;
      text-align: center;
      text-decoration: none;
      display: inline-block;
      font-size: 16px;
      border-radius: 5px;
      cursor: pointer;
    }
    .plan-button:hover {
      background-color: #9b1b20;
    }
    .table-container {
      margin-top: 30px;
    }
    .table-container table {
      border-collapse: collapse;
      width: 100%;
    }
    .table-container th, .table-container td {
      padding: 8px;
      border: 1px solid #ccc;
      text-align: center;
    }
    .table-container th {
      background-color: #f0f0f0;
    }
    .table-container tbody tr:nth-child(even) {
      background-color: #f9f9f9;
    }
    .table-container tbody tr:hover {
      background-color: #f0f0f0;
    }
    .table-container a {
      text-decoration: none;
      color: #e31c24;
    }
    .table-container a:hover {
      text-decoration: underline;
    }
    .note {
      font-size: 14px;
      font-style: italic;
      text-align: center;
      margin-top: 10px;
    }
  </style>
</head>
<body>

<div class="header">
  <h1>Aula de Espera</h1>
</div>

<div class="content">
  <div class="left-column">
    <img src="/assets/images/profesorPepe.jpg" alt="Left Image">
  </div>
  <div class="right-column">
    <img src="/assets/images/unsplash-image-1.jpg" alt="Full Width Image">
    <p>JAPONEDUCA forma parte del GRUPO JAPÓN y se dedica a ofrecer servicios educativos, ocio y tiempo libre.</p>
    
    <p>Nuestro programa educativo se adapta a los horarios familiares y fortalece la autonomía de los centros escolares bajo el Plan de Apertura de Centros.</p>
    
    <p>Organizamos actividades como aula matinal, comedor, deporte escolar, apoyo lingüístico y proyectos lectores, siguiendo los programas educativos de la Junta de Andalucía.</p>
    
    <p>Contamos con un equipo profesional dedicado a diseñar y llevar a cabo actividades adaptadas a las necesidades de alumnos y centros educativos.</p>
  </div>
</div>

<div class="button-container">
  <button class="plan-button" onclick="location.href='https://app.grupojapon.es/index.php/registro'">Inscríbete</button>
</div>

<div class="plan-container">
  <div class="plan">
    <h2>CEIP El Puntal</h2>
    <p>De lunes a viernes de 14:00 a 15:30 h</p>
    <p>Cuota:</p>
    <ul style="list-style-type: disc; padding-left: 40px; margin: 0; text-align: left;">
      <li>30 €/mes*</li>
      <li>3 € - días sueltos</li>
    </ul>
    <p>Fecha de inicio: 11/09/2024</p>
    <p>Enlaces:</p>
    <ul style="list-style-type: disc; padding-left: 40px; margin: 0; text-align: left;">
      <li><a href="/assets/documents/Nota_informativa_Aula_de_Espera_Ceip_El_Puntal_2023-24.pdf">Más información</a></li>
      <li><a href="https://app.grupojapon.es/index.php/registro">Inscríbete</a></li>
    </ul>
  </div>
  
  <!-- Repeat the above plan block for other schools as needed -->
</div>

<div class="note">
  <p>*Bonificación del 10% para el/la segundo/a hermano/a</p>
</div>

<div class="table-container">
  <table>
    <thead>
      <tr>
        <th><h2>Centro</h2></th>
        <th><h2>Horario</h2></th>
        <th><h2>Cuota</h2></th>
        <th><h2>Fecha de inicio</h2></th>
        <th><h2>Enlaces</h2></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>CEIP Tierno Galván</td>
        <td>De lunes a viernes de 14:00 a 15:00 h</td>
        <td>
          <ul style="list-style-type: disc; padding-left: 40px; margin: 0; text-align: left;">
            <li>25 €/mes*</li>
            <li>3 € - días sueltos</li>
          </ul>
        </td>
        <td>11/09/2024</td>
        <td>
          <ul style="list-style-type: disc; padding-left: 40px; margin: 0; text-align: left;">
            <li><a href="/assets/documents/Nota_informativa_Aula_de_Espera_Ceip_El_Puntal_2023-24.pdf">Más información</a></li>
            <li><a href="https://app.grupojapon.es/index.php/registro">Inscríbete</a></li>
          </ul>
        </td>
      </tr>
      
      <!-- Repeat the above table rows for other schools as needed -->
      
    </tbody>
  </table>
</div>

</body>
</html>
