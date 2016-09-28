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

# ¿Qué es Git?
Git es un sistema de control de versiones, gratuito y de código abierto, diseñado para manejar desde pequeños a grandes proyectos de manera rápida y eficaz. Se entiende como control de versiones a todas las herramientas que nos permiten hacer modificaciones en nuestro código y hacen que sea más fácil la administración de las distintas versiones de cada producto desarrollado.

# ¿Qué es GitHub?
Github es un servicio para alojamiento de repositorios de software gestionados por el sistema de control de versiones Git. Github es un sitio web pensado para hacer posible el compartir el código de una manera más fácil y al mismo tiempo darle popularidad a la herramienta de control de versiones en sí, que es Git. Cabe destacar que Github es un proyecto comercial, a diferencia de la herramienta Git que es un proyecto de código abierto.

# Crear una cuenta 
1. Descargar e instalar la última versión de <a href=https://desktop.github.com target=_blank>GitHub Desktop</a>. Al finalizar la instalación el sistema lo mantendrá actualizado a la última versión.
2. Desde la computadora, abrir la aplicación **Git Shell**
3. En primera instancia se debe igresar el nombre del usuario en Git para que al momento de hacer commit, todo quede correctamente etiquetado. Se deberá escribir todo después del símbolo ```$```.
```
$ git config --global user.name "NOMBRE"
```
4. Se deberá ingresar una dirección de email que quedará asociada a tus commits de Git. 
```
$ git config --global user.email "EMAIL"
```

# Crear un nuevo repositorio en GitHub 

En GitHub, se pueden guardar toda clase de proyectos en repositorios. Los repositorios personales pertenecen a las cuentas de los usuarios, así que luego de haber creado una cuenta y entrar al sistema, ya podemos crear nuestor primer repositorio. 
Los pasos son los siguientes: 

1. Situándonos en el menú principal, en la esquina superior derecha, podemos ver un ícono de **+** donde se despliegan diferentes opciones. La primera es "Nuevo repositorio". 
2. Debemos elegir un nombre para el repositorio. Se recomiendan nombres cortos y fáciles de recordar. 
3. Podemos agregar, de manera opcional, una breve descipción del repositorio. Por ejemplo: "Este es mi primer repositorio en GitHub". 
4. Luego debemos elegir si el repositorio será Público o Privado. 
- Público: Estará visible para cualquier usuario de GitHub. 
- Privado: Se encontrará disponible sólamente para nosotros, los dueños del repositorio, y para aquellas personas con las que decidamos compartirlo. 
5. Seleccionamos la opción Iniciar el reposito con un archivo Léeme. 
6. Crear el repositorio. 
¡Ya está! Con estos pocos pasos ya creamos el repositorio. En la siguiente imagen se verán todos los puntos mencionados anteriormente.


![](http://i.imgur.com/aMC2des.jpg)

# Clonar repositorios localmente

Cuando creamos un repositorio en GutHub, éste existe como un repositorio remoto. Existe la posibilidad de crear una copia o clon del repositorio de manera local y sincronizar el mismo entre ambos lugares. 

1.  Ingresamos a GitHub y nos situamos en el menú principal. 
2.  Debajo del nombre de un repositorio existente, clickeamos el ícono para colonar la URL del repositorio. 
3.  Abrimos Terminal (para usuarios de Mac o Lunux), o el Símbolo de sistema (para usuarios de Windows). 
4.  Ubicamos el directorio donde queremos que se genere el repositorio clonado. 
5.  Tipear git clone /* en código */, y luego copiar la URL que tomamos en el Paso 2. 
```
$ git clone https://github.com/USUARIO/REPOSITORIO 
```
6. Presionar Enter, y el repositorio local se creará.
```
$ git clone https://github.com/USUARIO/REPOSITORIO 
Cloning into `Location`... 
remote: Counting objects: 10, done. 
remote: Compressing objects: 100% (8/8), done. 
remove: Total 10 (delta 1), reused 10 (delta 1) 
Unpacking objects: 100% (10/10), done. 
```

## Clonar usando la aplicación de escritorio 

Para esto necesitamos intalar la <a href=https://desktop.github.com/ target=_blank>aplicación de escritorio</a> 

1. Ingresamos a GitHub y nos situamos en el menú principal. 
2. Debajo del nombre de un repositorio existente, clickeamos el ícono para colonar la URL del repositorio.

![](http://i.imgur.com/z8m0VR4.png) 

3. Dentro de la aplicación de escritorio, luego de verificar el nombre y el directorio en la unidad de disco donde queremos que se encuentre el repositorio clonado, clickeamos el botón Clonar.

![](http://i.imgur.com/jdKovQk.png)

# Conectar un repositorio local con tu repositorio en GitHub
El beneficio de tener un repositorio local es una manera efectiva de poder hacer modificaciones sin siquiera tener que estar conectado a internet. Luego, se puede subir el trabajo terminado a GitHub para que esté diponible para todos los usuarios.

Asumiendo que, por ejemplo, tenemos en GitHub un repositorio ubicado en https://github.com/usuario/ejemplo.git, la construccción sería:

```git remote add origin https://github.com/username/myproject.git```

* Modificamos "usuario" con tu usario real de GitHub.
* Modificamos "ejemplo" con el nombre real del repositorio en GitHub.
* Para informar a Git que el repositorio remoto realmente existe en algún lugar de internet utilizamos ```git add```.
* El código ```origin``` indica que esos archivos van a tener un nuevo destino.
* ```remote``` describe al código ```origin``` ya que va a estar subido de manera remota y no se va a tratar de un directorio local.

Para verificar, usamos: ```git remote -v```.

Para subir (“push”) nuestros cambios usamos ```git push```.
