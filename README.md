# Introducción al desarrollo Front-end
En este módulo, conocerá los diferentes tipos de desarrolladores web y las funciones y responsabilidades de los desarrolladores front-end, back-end y full-stack. Echará un primer vistazo a las tecnologías básicas de HTML, CSS y Javascript y explorará los conceptos que sustentan el funcionamiento de Internet.

# Primer proyecto del curso
# Little Lemon - Menú y Ubicación

Este proyecto HTML representa un sitio web simple para "Little Lemon", un lugar ficticio. A continuación, se presenta un resumen de los códigos utilizados en los archivos:

## `index.html` - Menú

```html
<!DOCTYPE html>
<html>
    <head>
        <title> Little Lemon </title>
    </head>
    <body>
        <h1> Our Menu </h1>
        <h2> Falafel </h2>
        <p> Chickpea, herbs and spices</p>
        <h2> Pasta Salad </h2>
        <p> Lettuce, vegetables and mozzarella </p>
        <a href="location.html"> Our Location </a>
    </body>
</html>
```

En este archivo, se presenta un menú simple con platos como "Falafel" y "Pasta Salad". Se incluye un enlace a la ubicación del establecimiento.

## `location.html` - Ubicación

```html
<!DOCTYPE html>
<html>
    <head>
        <title> Little Lemon </title>
    </head>
    <body>
        <h1> Our Location </h1>
        <p> 123 Home Road, Main District, Capital City</p>
    </body>
</html>
```

Este archivo detalla la ubicación de "Little Lemon" con la dirección "123 Home Road, Main District, Capital City".

## Resumen de Aprendizaje

En el desarrollo de estos archivos HTML, se aprendieron los siguientes conceptos:

- Uso del `<!DOCTYPE html>` para indicar que se trata de un documento HTML.
- Estructura básica con las etiquetas `<html>`, `<head>`, y `<body>`.
- Utilización de etiquetas de encabezado `<h1>`, `<h2>` para títulos.
- Creación de párrafos con la etiqueta `<p>`.
- Incorporación de enlaces `<a>` para navegar entre páginas.
- Práctica con etiquetas de énfasis `<strong>`, negrita `<b>`, cursiva `<i>`.
- Creación de listas con `<ul>` y `<ol>`.
- Uso de la etiqueta `<div>` como contenedor genérico.

Estos son solo algunos de los conceptos básicos de HTML cubiertos en este proyecto. Se recomienda revisar las lecciones adicionales y los códigos en mención para obtener más información sobre el desarrollo web con HTML.

# Actualización: Little Lemon - Menú, Ubicación y Más

## `index.html` - Menú y Más

```html
<!DOCTYPE html>
<html>
    <head>
        <title> Little Lemon </title>
    </head>
    <body>
        <h1> Our Menu </h1>
        <h2> Falafel </h2>
        <p> Chickpea, herbs and spices</p>
        <img src="falafel.jpg" width="240" height="135" alt="A falafel">
        <h2> Pasta Salad </h2>
        <p> Lettuce, vegetables and mozzarella </p>
        <img src="salad.jpg" width="240" height="135" alt="A pasta salad"> <br>
        <a href="location.html"> Our Location </a> <br>

        <style>
            table, th, td{
                border: 1px solid black;
                border-collapse: collapse;
            }    
        </style>
        <table>
            <tr>
                <th> Dishes </th>
                <th> Price </th>
            </tr>
            <tr>
                <td> Falafel </td>
                <td> $10.00 </td>
            </tr>
            <tr>
                <td> Past Salad </td>
                <td> $12.00 </td>
            </tr>
        </table>
    </body>
</html>
```

## Resumen de Aprendizaje Adicional

En este código actualizado, se han incluido imágenes para los platos del menú, así como una tabla que muestra los platos y sus precios. 

- Se utiliza la etiqueta `<img>` para mostrar imágenes de los platos del menú.
- La tabla se ha creado con las etiquetas `<table>`, `<th>` y `<td>` para mostrar información tabular.
- Se ha agregado información adicional sobre el DOM y su papel en la manipulación dinámica de documentos HTML.
- Se ha introducido información sobre formularios en HTML y su importancia para la recopilación de datos del usuario.

### DOM (Modelo de Objetos del Documento)

El DOM (Modelo de Objetos del Documento) es una interfaz de programación que proporciona una representación estructurada y jerárquica de un documento. Este documento suele ser un documento HTML o XML, y el DOM permite a los programas o scripts modificar la estructura, el estilo y el contenido del documento de manera dinámica. En el contexto de HTML, el DOM representa la estructura de la página web, permitiendo la manipulación mediante lenguajes como JavaScript.

El DOM organiza el documento en un árbol de nodos, donde cada elemento del documento es un nodo. Los nodos pueden representar etiquetas HTML, atributos, texto, entre otros. Los programadores utilizan el DOM para acceder, modificar y actualizar elementos y atributos del documento HTML, creando así interactividad dinámica en las páginas web.

### Formularios en HTML

Los formularios en HTML son una parte esencial de la interacción del usuario en la web. Permiten a los usuarios ingresar y enviar datos al servidor web. Un formulario puede contener diversos elementos, como campos de texto, casillas de verificación, botones de radio, botones de envío, entre otros.

Algunos elementos clave en la creación de formularios en HTML incluyen:

- `<form>`: Define un formulario y encierra todos los elementos del formulario.
- `<input>`: Crea campos de entrada, como campos de texto, casillas de verificación y botones.
- `<select>`: Define una lista desplegable, también conocida como menú de selección.
- `<textarea>`: Permite a los usuarios ingresar texto en un área de texto de múltiples líneas.
- `<button>`: Crea botones dentro del formulario.

Cuando un usuario completa y envía un formulario, los datos se envían al servidor web para su procesamiento. Los formularios son fundamentales para la recopilación de información y la interacción bidireccional entre los usuarios y las aplicaciones web.
