# santon17.github.io
<!DOCTYPE html>
<html lang="es">
	<head>
		<meta charset="utf-8">
		<title>Saúl Santonja</title>
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<link rel="stylesheet" href="estilo.css">
	</head>

	<body>
		<h1>Formulario de prueba.</h1>
		<form action="ejemplo.php" method="get">
		  
		  <p>Nombre: <input type="text" name="nombre" size="20"></p>
		  <p>Apellidos: <input type="text" name="nombre" size="40"></p>
		  <p>Año de nacimiento: <input type="date" name="fecha">

		  <p>Sexo:
			<input type="radio" name="hm" value="h"> Hombre
			<input type="radio" name="hm" value="m"> Mujer
		  </p>
		  <p>Nivel de programación:<input type="range" name="rango"></p>
		  
		  <p>Elija una opcion:
			<select name="menu">
			    <option value="1">Grado superior</option>
				<option value="2">Grado universitario</option>
				<option value="3">FP Basica</option>
			</select>
		  </p>
		  <textarea name="texto" rows="4" cols="40" placeholder="Experiencia laboral"></textarea>
		  <p>
			<input type="submit" value="Enviar">
			<input type="reset" value="Borrar">
		  </p>
		</form>
	</body>
</html>
