# AW Preguntas
```1. estructura mínima de una web:

<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>

</body>
</html>

2. explica las 3 formas de usar CSS en HTML

CSS externo, es una manera de usar CSS pero poniendolo en un .css y no en el HTML como en este ejemplo:
<link rel="stylesheet" type="text/css" href="index.css" /> este codigo estaria dentro del HTML y aplicaria el index.css que seria donde tenemos todo lo relacionado con el CSS.

CSS interno, este es el que hemos usado mayormente en clase y es el que no ponemos en head, y vamos utilizando divs para asignar los estilos.

CSS embebido, se dice que es el que se pone dentro de las etiquetas donde queremos aplicar el css y basta con poner style y lo que queramos.

3. crea una lista sin ordenar con 5 ingredientes de una receta de cocina

<ul>
	<li>Harina</li>
	<li>Jamon</li>
	<li>Tomante</li>
  <li>Queso</li>
  <li>Aguacate</li>
</ul>


4. como se puede incluir javascript en HTML
Con el siguiente codigo: <script type="text/javascript"></script>

5. ¿Que diferencia hay entre una clase y una ID
ID se usa para seleccionar un elemento unico y Clase se utiliza para seleccionar varios elementos.

6. código para hacer un enlace a otra página y que esta se abra en una nueva ventana
<a href="ejemplo.html" target="_blank">Enlace a otra pagina </a>.

7. ¿Qué son las pseudoclases?, pon ejemplos.
Son palabras clave que se ponen en selectores y especifican un estado especial de un elemento.
como puede ser :visited, :hover.

8. Explica el modelo de caja de CSS (margin, border y padding)
Por un lado tenemos contenido del cuadro donde aparecen imagenes y texto.
Border: Es un borde que rodea el contenido contenido.
Padding: Expande un área alrededor del contenido con un relleno transaparente.
Margin: Expande un área alrededor del contenido y del borde.

9. Explica que son los selectores de CSS y pon ejemplos
Es la union entre la zona de estilos y el documento en el que se apliquen.
ejemplo de selector:
strong {
  color: blue;
}
Ahora cuando usemos el selector strong, saldran tambien en rojo.

10. Di a quien afectan:
p a { color: red; } Los parrafos que tengan enlaces saldran en color rojo
p > a { color: red; }
h1 + h2 { color: red } Los titulos con h1 y h2 apareceran en color rojo
a[class] { color: blue; }    Los enlaces que tengan un class tendran las letras de color azul. 
a[class="externo"] { color: blue; } Los enlaces que tengan un class="externo" tendran la letra de color azul.
a[href="http://www.ejemplo.com"] { color: blue; } Indica que ese enlaze aparecera de color azul```
