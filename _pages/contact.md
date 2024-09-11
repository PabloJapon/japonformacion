---
title: Contacto
permalink: /contacto/
layout: splash
---

<div class="contact-background" style="text-align:center; margin-top:7em">
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

<style>
  /* CSS to set the background image */
  .contact-background {
    background-image: url('/assets/images/CABECERA.png');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    height: 300px; /* Adjust the height based on your layout */
  }

  /* Optional: Additional styling for the form */
  .contact-form {
    margin: 2em auto;
    max-width: 600px;
    padding: 20px;
    background-color: rgba(255, 255, 255, 0.8); /* White background with transparency */
    border-radius: 10px;
  }
</style>
