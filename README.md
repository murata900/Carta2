<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Para Ari 💌</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: #ffeef2;
      font-family: 'Arial', sans-serif;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
    }

    .carta {
      position: relative;
      width: 300px;
      height: 200px;
      background: transparent;
    }

    .sobre {
      width: 100%;
      height: 100%;
      background: #e74c3c;
      clip-path: polygon(0 100%, 50% 50%, 100% 100%, 100% 100%, 0 100%);
      display: flex;
      align-items: flex-end;
      justify-content: center;
      position: relative;
      transition: transform 0.4s ease-in-out;
    }

    .sobre:hover {
      transform: scale(1.05);
    }

    .contenido {
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      position: absolute;
      top: -150px;
      width: 260px;
      text-align: center;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
    }
  </style>
</head>
<body>
  <div class="carta">
    <div class="sobre">
      <div class="contenido">
        <h2>💖 Feliz mesaniversario 💖</h2>
        <p>
          Te quiero muchísimo 💕<br>
          Gracias por compartir tu tiempo, tu cariño y tu risa conmigo.  
        </p>
      </div>
    </div>
  </div>
</body>
</html>
