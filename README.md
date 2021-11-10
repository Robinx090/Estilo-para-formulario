<!Doctype html>
<html>
<head>
 <meta charset="UTF-8">
 <title>FORMULARIO</title>
	<style type="text/css">
		th{
			color: red;
			background-color:#EAF38D ;
			font-size: xx-large;
		}
		td{
			background-color: #01DFF9;
		}
		label{
			text-align: center;
			background-color: red;
		}
		#azul{
			color: blue;
		}
		#verde{
			color: green;
		}	
	</style>
</head>
	<body>
	 <table border="2" cellpadding="15">
	 <form method="POST" action="http://formadorestic.com/alumnosasir2/procesaformulario_usuario.php">
	 	<tr>
	 		<th colspan="2">User Form</th>
	 	</tr>
	 	<tr>
	 		<td>
	 			<label for="Nombre">Introduzca Nombre</label>
	 		</td>
	 		<td>
	 				<input type="text" name="nombre" id="Nombre" placeholder="Introduzca su Nombre" required>
	 		</td>
	 	</tr>
	 	<tr>
	 		<td>
	 			<label for="contraseña">Introduzca Contraseña</label>
	 		</td>
	 		<td>
	 			<input type="password" name="password" id="contraseña" placeholder="Introduzca su Contraseña" required>
	 		</td>
	 	</tr>
	 	<tr>
	 		<td>
	 			<label for="direccion">Introduzca Dirección</label>
	 		</td>
	 		<td>
	 			<textarea name="direccion" id="direccion" rows="4" cols="30">C/valladolid 4 1ºD</textarea>
	 		</td>
	 	</tr>
	 	<tr>
	 		<td>
	 			<p>Seleccione Juego</p>
	 		</td>
	 		<td>
	 			<input type="checkbox" id="juego" name="deportes[]" value="hockey">
	 				<label for="juego">Hockey</label><br>
	 			<input type="checkbox" id="futbol" name="deportes[]" value="futbol">
	 				<label for="futbol">Futbol</label><br>
	 			<input type="checkbox" id="Badminton" name="deportes[]" value="Badminton">
	 				<label for="Badminton">Badminton</label><br>
	 			<input type="checkbox" id="cricket" name="deportes[]" value="cricket">
	 				<label for="cricket">Cricket</label><br>
	 			<input type="checkbox" id="Volleyball" name="deportes[]" value="Volleyball">
	 				<label for="Volleyball">Volleyball</label>
	 		</td>
	 	</tr>
	 	<tr>
	 		<td>
	 			<p>Género</p>
	 		</td>
	 		<td>
	 			<input type="radio" name="sexo" id="hombre" value="hombre">
	 				<label for="hombre">Hombre</label>
	 			<input type="radio" name="sexo" id="mujer" value="mujer">
	 				<label for="mujer">Mujer</label>
	 		</td>
	 	</tr>
	 	<tr>
	 		<td>
	 			<label for="edad">Seleccione su edad</label>
	 		</td>
	 		<td>
	 			<select name="edad" id="edad">
	 				<option value="menor">-18</option>
	 				<option value="adolescente">18</option>
	 				<option value="mayor">+18</option>
	 			</select>
	 		</td>
	 	</tr>
	 	<tr>
	 		<td colspan="2">
	 			<input type="file" name="uploadfile" id="azul">
	 		</td>
	 	</tr>
	 	<tr>
	 		<td colspan="2">
	 			<input type="button" name="boton" value="Click Me" id="azul">
	 			<input type="reset" name="resetear" value="Reset" id="azul">
	 			<input type="submit" name="enviar" value="Submit Form" id="verde">
	 		</td>
	 	</tr>
	 </form>
	 </table>
	</body>
</html>
