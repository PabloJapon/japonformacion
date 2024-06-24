---
title: Contacto
permalink: /contacto/
layout: splash
---

<!-- markdownlint-disable MD033 -->
<style>
img {
  float: right;
  margin-left: 10px;
  margin-bottom: 10px;
  margin-top: 10px;
}
  form {
    max-width: 600px;
    margin: 5em auto;
    padding: 1em;
    background: #f9f9f9;
    border-radius: 5px;
  }
  form p {
    margin-bottom: 1em;
  }
  label {
    margin-bottom: .5em;
    color: #333333;
    display: block;
  }
  input, textarea {
    border: 1px solid #CCCCCC;
    padding: .5em;
    font-size: 1em;
    width: 100%;
    box-sizing: border-box;
    border-radius: 4px;
  }
  button {
    background-color: #e31c24;
    color: white;
    border: none;
    padding: 15px 100px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 20px;
    border-radius: 5px;
    cursor: pointer;
  }
  button:hover {
    background-color: #0056b3;
  }
</style>

<div style="text-align:center;">
  ¿Dudas? No te las guardes, pregúntanos.
</div>

<form name="contact" action="/_pages/success.html" method="POST" data-netlify="true">
  <input type="hidden" name="form-name" value="contact" />
  <p>
    <label for="name">Tu Nombre:</label><br />
    <input type="text" id="name" name="name" required />
  </p>
  <p>
    <label for="email">Tu Correo Electrónico:</label><br />
    <input type="email" id="email" name="email" required />
  </p>
  <p>
    <label for="message">Mensaje:</label><br />
    <textarea id="message" name="message" rows="5" required></textarea>
  </p>
  <p>
    <button type="submit">Enviar</button>
  </p>
</form>
