# Grupo10Pro
Página Web en grupo
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Formulario de ejemplo</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f6f8;
      max-width: 700px;
      margin: auto;
      padding: 20px;
    }

    h1 {
      text-align: center;
    }

    label {
      font-weight: bold;
      margin-top: 10px;
      display: block;
    }

    textarea, input, select {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
    }

    .buttons {
      margin: 15px 0;
      display: flex;
      justify-content: space-between;
    }

    button {
      width: 48%;
      padding: 10px;
      font-weight: bold;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <h1>Formulario de Contacto</h1>
  <form>
    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" name="nombre">

    <label for="mensaje">Mensaje:</label>
    <textarea id="mensaje" name="mensaje"></textarea>

    <div class="buttons">
      <button type="submit">Enviar</button>
      <button type="reset">Limpiar</button>
    </div>
  </form>
</body>
</html>
