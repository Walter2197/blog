---
layout: page
title: Contacto
permalink: /contact/
---
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {font-family: Arial, Helvetica, sans-serif;}
* {box-sizing: border-box;}

input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=submit] {
  background-color: #4CAF50;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

.container {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}
</style>
</head>
<body>

<h3>Formulario de Contacto</h3>

<div class="container">
  <form action="/action_page.php">
    <label for="fname">Nombres</label>
    <input type="text" id="fname" name="firstname" placeholder="Tus nombres...">

    <label for="lname">Apellidos</label>
    <input type="text" id="lname" name="lastname" placeholder="Tu apellido...">

    <label for="country">País</label>
    <select id="country" name="country">
	  <option value="ecuador">Ecuador</option>
      <option value="australia">Australia</option>
      <option value="canada">Canada</option>
      <option value="usa">USA</option>
    </select>

    <label for="subject">Asunto</label>
    <textarea id="subject" name="subject" placeholder="Escribe algo..." style="height:200px"></textarea>

    <input type="submit" value="Enviar">
  </form>
</div>

</body>
</html>
