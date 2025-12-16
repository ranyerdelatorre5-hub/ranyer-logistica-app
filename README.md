# ranyer-logistica-app
Distribution
RANYER_ClientApp_WEB/
├── index.html
├── manifest.json
├── flutter_service_worker.js
├── main.dart.js
├── favicon.png
├── icons/
│   ├── Icon-192.png
│   ├── Icon-512.png
├── assets/
│   ├── background_main.jpeg
│   └── logo.png
└── README_CLIENT_WEB.txt<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>RANYER Express</title>
  <meta name="description" content="RANYER Express Distribution LLC - Plataforma de logística y pedidos.">
  <meta name="theme-color" content="#1E1E1E"/>
  <link rel="manifest" href="manifest.json">
  <link rel="icon" href="favicon.png" type="image/png">
  <link rel="apple-touch-icon" href="icons/Icon-512.png">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      background: linear-gradient(145deg, #2B2B2B, #1E1E1E);
      color: white;
      font-family: 'Helvetica Neue', sans-serif;
      text-align: center;
      margin: 0;
      padding: 0;
    }
    #logo {
      margin-top: 25vh;
      width: 200px;
    }
    h1 {
      color: #D4AF37;
      font-weight: 600;
      font-size: 24px;
    }
    .btn {
      margin-top: 20px;
      background: #D4AF37;
      border: none;
      color: #000;
      padding: 12px 30px;
      font-weight: bold;
      border-radius: 6px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <img id="logo" src="assets/logo.png" alt="RANYER Logo">
  <h1>RANYER Express Distribution LLC</h1>
  <p>Plataforma logística y pedidos en línea.</p>
  <button class="btn" onclick="window.location.href='main.dart.js'">Abrir aplicación</button>
</body>
</html>
