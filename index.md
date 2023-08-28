<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ininteligible</title>
  <style>
    :root {
      --bg-color: #282a36;
      --text-color: #f8f8f2;
      --link-color: #bd93f9;
      --sepia-color: #c0c090; /* Nuevo color sepia */
    }

    body {
      background-color: var(--bg-color);
      color: var(--text-color);
      font-family: Arial, sans-serif;
      transition: background-color 0.5s, color 0.5s;
    }

    a {
      color: var(--link-color);
    }

    /* Estilos para el texto que se escribe letra por letra */
    #text {
      display: inline-block;
      overflow: hidden;
      white-space: nowrap;
      border-right: 0.15em solid var(--text-color);
 
      animation: typing 4s steps(14), blink-caret 0.75s step-end infinite;
    }
    @keyframes typing {
      from {
        width: 0;
      }
      to {
        width: 100%;
      }
    }
    @keyframes blink-caret {
      from,
      to {
        border-color: transparent;
      }
      50% {
        border-color: var(--text-color);
      }
    }
    #cat {
      font-family: monospace;
      white-space: pre;
      font-size: 20px;
    }
    #textBubble {
      background-color: #28282B;
      border-radius: 10px;
      padding: 10px;
      margin-top: 20px;
    }
  </style>
</head>

<body>
  <p>
  <b>hiato: 28/08/2023 ~ </b>><br>
  Dejo este espejo de Narciso moderno de forma indefinida. 
El consumo de contenido curado específicamente para vender una imagen particular, el egocentrismo y autocentrismo se ha vuelto francamente repugnante.
Si encuentra algo gracioso o interesante que quiere que vea, siéntase libre de enviármelo; o mejor aún, muéstremelo.
</p>
</body>

</html>
