# Template básico Lógica de Programación

Este es un template **basico** que incluye un archivo HTML y 3 Hojas de estilos en la cual se podrá desarrollar el proceso de maquetación de nuestros sitios web aplicando los conceptos vistos en clase.

# Archivos

Los archivos que incluye este template son: 

**Carpeta CSS:** Donde se encuentra alojados los archivos CSS 
**Carpeta Imagenes:** Donde se colocaran todas las imágenes cortadas de nuestros diseños
**Archivo Index.html** Donde maquetaremos todo nuestro HTML.

## Estilos CSS

En la carpeta CSS encontraremos los archivos llamados:

**estilos.css** En este archivo colocaremos todos nuestros estilos CSS
**grid.css** En este archivo se encuentra toda la configuración básica de una retícula por medido el método de la w3cschool. https://www.w3schools.com/css/css_rwd_grid.asp
**reset.css** En este archivo es para borrar todos los estilos basicos de HTML. https://meyerweb.com/eric/tools/css/reset/

**Recuerden: Revisar el archivos grid.css para eliminar el borde de las columnas**

## Creación de un contenedor
Para crear un contenedor lo que debemos hacer es en nuestro archivo **index.html** es crear un div con el class contenedor

    <div class="contenedor"></div>
 
 y en nuestro archivo **estilos.css** colocamos el siguiente codigo:

    .contenedor {
	    margin: 0 auto;
	    width: 1024px; /* Aca colocaremos el tamaño de nuestro contenedor */
	}

## Creación de retícula

Para crear columnas por medio del metodo de la **grid.css** debemos de crear una div con la clase llamada **row** y dentro de ella vamos a colocar nuestras columnas. Colocaremos una div class con el numero de columnas por ejemplo: **col-1**

    <!-- Creamos una div con la clase row -->
    <div class="row">
		<!-- Aca adentro iran nuestras columnas -->
	</div>

Para crear columnas es importante siempre crear una clase llamada **row** y dentro de ella colocar nuestras columnas.

**2 Columnas de 6 -- 50% Cada una**

    <!-- Creamos una div con la clase row -->
    <div class="row">
		<!-- Aca adentro iran nuestras columnas -->
			<div class="col-6">
				<!-- Columna de 50% -->
			</div>

			<div class="col-6">
				<!-- Columna de 50% -->
			</div>
	</div>

**4 Columnas de 3 -- 25% Cada una**

	<!-- Creamos una div con la clase row -->
    <div class="row">
		<!-- Aca adentro iran nuestras columnas -->
			<div class="col-3">
				<!-- Columna de 25% -->
			</div>
			<div class="col-3">
				<!-- Columna de 25% -->
			</div>
			<div class="col-3">
				<!-- Columna de 25% -->
			</div>
			<div class="col-3">
				<!-- Columna de 25% -->
			</div>
	</div>

## Referencias
Para mayor información sobre etiquetas HTML y propidades CSS pueden visitar los siguientes links:
http://htmlcheatsheet.com/
http://htmlcheatsheet.com/css/
https://www.w3schools.com/html/
https://www.w3schools.com/css/