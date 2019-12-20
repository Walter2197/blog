---
layout: page
title: Suscríbete
permalink: /sub/
---
<html>
<style>
body {font-family: Arial, Helvetica, sans-serif;}

form {
  border: 3px solid #f1f1f1;
  font-family: Arial;
}

.container {
  padding: 20px;
  background-color: #f1f1f1;
}

input[type=text], input[type=submit] {
  width: 100%;
  padding: 12px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  box-sizing: border-box;
}

input[type=checkbox] {
  margin-top: 16px;
}

input[type=submit] {
  background-color: #4CAF50;
  color: white;
  border: none;
}

input[type=submit]:hover {
  opacity: 0.8;
}
</style>
<body>

<h2>Formulario de Suscripción </h2>

<form action="/action_page.php">
  <div class="container">
    <h2>Suscríbete a mi Blog</h2>
    <p>Te llegarán los últimos posts y noticias sobre todo lo relacionado al mundo de la informática totalmente gratis!</p>
  </div>

  <div class="container" style="background-color:white">
    <input type="text" placeholder="Nombre" name="nombre" required>
    <input type="text" placeholder="E-mail" name="mail" required>
    <label>
      <input type="checkbox" checked="checked" name="subscribe"> Información diaria
    </label>
  </div>

  <div class="container">
    <input type="submit" value="Suscribirme">
  </div>
</form>

</body>
</html>
