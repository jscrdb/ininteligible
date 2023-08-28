<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ininteligible</title>
  <style>
	:root {
	  --bg-color: #0c295e; /* Nuevo color de fondo azul */
	  --text-color: #f8f8f2;
	  --link-color: #00a8e8; /* Nuevo color de enlace azul */
	  --sepia-color: #c0c090;
	  --blue-theme-color: #3a86ff; /* Nuevo tono de azul */
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

	/* Resto de estilos... */

	/* Nueva opción de tema */
	@media (prefers-color-scheme: dark) {
	  :root {
		--bg-color: #05264c;
		--text-color: #f8f8f2;
		--link-color: #00a8e8;
		--sepia-color: #c0c090;
		--blue-theme-color: #3a86ff;
	  }
	}

	/* Aplicar tema por defecto al cargar la página */
	:root {
	  --bg-color: var(--blue-theme-color);
	  --text-color: #f8f8f2;
	  --link-color: #00a8e8;
	  --sepia-color: #c0c090;
	}
  </style>
</head>

<body>
  <!-- Resto del contenido de la página... -->

  <label for="theme-select">Pick your poison:</label>
  <select id="theme-select">
	<option value="dark">Nic Cage (Dracula)</option>
	<option value="light">Light</option>
	<option value="sepia">Sepia</option>
	<option value="blue">The Ghost of Billy Royalton</option>
  </select>

  <!-- Resto del script... -->
</body>
</html>
