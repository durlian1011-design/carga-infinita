
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cargando...</title>
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 24px;
      background: #080b12;
      color: #aab3c5;
      font-family: Arial, sans-serif;
    }
    .spinner {
      width: 58px;
      height: 58px;
      border: 5px solid rgba(255,255,255,.14);
      border-top-color: #76a9ff;
      border-radius: 50%;
      animation: girar .85s linear infinite;
    }
    @keyframes girar {
      to { transform: rotate(360deg); }
    }
  </style>
</head>
<body>
  <div class="spinner" role="status" aria-label="Cargando"></div>
  <p>Cargando, por favor espera...</p>
</body>
</html>
