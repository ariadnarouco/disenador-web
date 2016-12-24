# Historia del HTML

El origen de HTML se remonta a 1980, cuando el físico Tim Berners-Lee, trabajador del CERN (Organización Europea para la Investigación Nuclear) propuso un nuevo sistema de "hipertexto" para compartir documentos.

Los sistemas de "hipertexto" habían sido desarrollados años antes. En el ámbito de la informática, el "hipertexto" permitía que los usuarios accedieran a la información relacionada con los documentos electrónicos que estaban visualizando. De cierta manera, los primitivos sistemas de "hipertexto" podrían asimilarse a los enlaces de las páginas web actuales.

Tras finalizar el desarrollo de su sistema de "hipertexto", Tim Berners-Lee lo presentó a una convocatoria organizada para desarrollar un sistema de "hipertexto" para Internet. Después de unir sus fuerzas con el ingeniero de sistemas Robert Cailliau, presentaron la propuesta ganadora llamada WorldWideWeb (W3).

El primer documento formal con la descripción de HTML se publicó en 1991 bajo el nombre HTML Tags (Etiquetas HTML) y todavía hoy puede ser consultado online a modo de reliquia informática.

La primera propuesta oficial para convertir HTML en un estándar se realizó en 1993 por parte del organismo IETF (Internet Engineering Task Force). Aunque se consiguieron avances significativos (en esta época se definieron las etiquetas para imágenes, tablas y formularios) ninguna de las dos propuestas de estándar, llamadas HTML y HTML+ consiguieron convertirse en estándar oficial.

En 1995, el organismo IETF organiza un grupo de trabajo de HTML y consigue publicar, el 22 de septiembre de ese mismo año, el estándar HTML 2.0. A pesar de su nombre, HTML 2.0 es el primer estándar oficial de HTML.

A partir de 1996, los estándares de HTML los publica otro organismo de estandarización llamado W3C (World Wide Web Consortium). La versión HTML 3.2 se publicó el 14 de Enero de 1997 y es la primera recomendación de HTML publicada por el W3C. Esta revisión incorpora los últimos avances de las páginas web desarrolladas hasta 1996, como applets de Java y texto que fluye alrededor de las imágenes.

HTML 4.0 se publicó el 24 de Abril de 1998 (siendo una versión corregida de la publicación original del 18 de Diciembre de 1997) y supone un gran salto desde las versiones anteriores. Entre sus novedades más destacadas se encuentran las hojas de estilos CSS, la posibilidad de incluir pequeños programas o scripts en las páginas web, mejora de la accesibilidad de las páginas diseñadas, tablas complejas y mejoras en los formularios.

# Estructura HTML

## El DOCTYPE

Cuando escribimos nuestro documento HTML, lo primero que tenemos que escribir es el **DOCTYPE**. El doctype declara el tipo de documento, es decir, nos sirve para indicar que nuestro documento está escrito siguiendo la estructura determinada por un DTD concreto.

### ¿Qué es el DTD que utilizamos en el Doctype?
Un **DTD** es la definición del tipo de documento. El doctype que es la forma de declarar el tipo de documento.

Así que, el DTD es dónde se define la estructura que debe tener el documento y utilizamos el doctype para informar qué DTD usamos.

### El doctype en HTML5
A partir de HTML5 la declaración del doctype es notablemente más sencilla, sólo basta con encabezar nuestro documento con la siguiente etiqueta.

```<!DOCTYPE html>```

## Estructura básica de un HTML

Usaremos 3 tags para definir la estructura principal de un HTML, ellos son:

```<html>```: Esta etiqueta delimita el contenido del documento e indica en que lenguaje está escrito.

 ```<head>```: Es la parte privada del documento, se utiliza como un espacio de comunicación entre el sitio web y el navegador para configuración de la visualización del sitio.

```<body>```: Encierra el contenido propiamente dicho del sitio.

Una vez definida la estructura principal, veremos otras etiquetas básicas de HTML.

```<title>```: La etiqueta title define el título de nuestra página, que será visualizado en la solapa del navegador.

 ```<meta>```: Con esta etiqueta definiremos que codificación de caracteres utilizará nuestro sitio.

Utilizaremos todas estas etiquetas en nuestro primero ejemplo de estructura web:

```
<!DOCTYPE html>
    <html>
        <head>
            <meta charset="UTF-8">
            <title>Mi primer sitio web</title>
        </head>
        <body>
            ¡Este es mi primer sitio web!
        </body>
    </html>
```

## Sintaxis HTML

El elemento principal del html es el de etiqueta, éstas sirven para especificar el tipo de contenido al navegador.

Las etiquetas se dividen en cerradas y abiertas.

Las  cerradas  encierran un contenido, por lo general texto. Las abiertas no encierran contenido, y sirven, entre otras cosas, para incluir elementos como imágenes, líneas, etc.

```
<p>Este es un párrafo con texto en su interior</p>
<hr/>
```

En el ejemplo tenemos una etiqueta cerrada parrafo que engloba un texto y una etiqueta abierta para incluir una línea horizontal.
El signo **/** se utiliza para las etiquetas de cierre; en las etiquetas cerradas se pone a continuación  del signo **<**, en las abiertas se pone delante del signo **>**.

# Etiquetas Semánticas
HTML5 incorpora etiquetas semánticas que no sólo generan estructura, si no que también define su contenido.


### Etiquetas
* ```<section>```: Define una sección en un documento.
* ```<nav>```: Define un bloque quecontiene enlaces de navegación, como por ejemplo el menú.
* ``` <article>```: Define contenido autónomo que podría existir independientemente del resto del contenido.
* ```<aside>```: Define contenidos vagamente relacionados con el resto del contenido de la página.
* ```<main>```: Define el contenido principal o importante en el documento. Solamente existe un elemento ```<main>``` en el documento.
* ```<header>```: Define la cabecera de una página o sección.
* ```<footer>```: Define el pie de una página o sección.


