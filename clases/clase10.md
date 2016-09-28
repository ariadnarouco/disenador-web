# Mixins
Nos permiten definir estilos que puedan ser reutilizados en nuestro proyecto, sin necesidad de recurrir a las clases helpers que ya comentamos, también pueden contener complejas reglas de CSS.

### Cómo usar los Mixins en Sass:

Para crearlos debemos utilizar ```@``` seguido de ```mixin``` y por último el nombre que queramos darle al mixin. Luego, para declararlo dentro de un componente, usamos ```@include```, seguido de un espacio, el nombre y por último entre paréntesis ```()``` escribimos los argumentos requeridos por nuestro Mixin. Los argumentos son opcionales.

Por ejemplo, para evitar la repetición de alto y ancho de un componente a lo largo de un proyecto, podemos crear un pequeño Mixin que transforme las habituales dos líneas de código en una sola:

```
@mixin sizes($width, $height: $width) {
  height: $height;
  width: $width;
}
 
.box {
  @include sizes(100px);
}
```

# Extends / Placeholders:

Es una de las más poderosas características de Sass. Nos permite crear un fragmento de estilos que luego podamos reutilizar fácilmente en cualquier componente.

### Cómo usarlo:
Para declarar y crear un fragmento de estilos que necesitamos reutilizar, usamos ```%``` seguido de un nombre, sin espacios. Luego, para imprimir o reutilizar el Extend dentro de un componente, usamos ```@extend``` seguido de un espacio y por último, el nombre que asignamos a nuestro fragmento.

Por ejemplo, si queremos crear un componente básico para imprimir mensajes del sistema, debemos tener una clase para mensajes exitosos, de advertencia y de errores. 

```
// vars
$bg-success: green;
$bg-error: red;
$bg-warning: orange;
 
// extend
%message {
  border-radius: 2px;
  color: white;
  padding: 5px;
  text-align: center;
}
 
.message-success {
  @extend %message;
  background-color: $bg-success;
}
 
.message-error {
  @extend %message;
  background-color: $bg-error;
}
 
.message-warning {
  @extend %message;
  background-color: $bg-warning;
```


###### Sass nos imprimirá el siguiente CSS:

```
.message-success, .message-error, .message-warning {
  border-radius: 2px;
  color: white;
  padding: 5px;
  text-align: center;
}
 
.message-success {
  background-color: green;
}
 
.message-error {
  background-color: red;
}
 
.message-warning {
  background-color: orange;
}
```

Sass, agrupará las clases o atributos que tengan estilos comunes, evitando repetirlos por separado.

# Operadores:

Realizar operaciones matemáticas en CSS, es posible gracias a Sass. Contamos con un puñado de operadores: (+, -, *, / y %) que trabajan de la misma forma que las operaciones matemáticas básicas.

Por ejemplo, para crear un simple grid basado en 960px y que el ancho de cada elemento sea expresado en porcentajes:

```
$wrap: 960px; 
 
article[role="main"] {
  float: left;
  width: 630px / $wrap * 100%;
}
 
aside[role="complimentary"] {
  float: left;
  width: 330px / $wrap * 100%;
}
```

###### Sass nos imprimirá el siguiente CSS:
```
article[role="main"] {
  float: left;
  width: 65.625%;
}
 
aside[role="complimentary"] {
  float: left;
  width: 34.375%;
}
```

De esta manera  tenemos un grid básico que nos permite estructurar nuestro contenido de una manera agradable en dos columnas.

# BEM

La metodología de trabajo BEM (Block,Element,Modifier) que se implementa en las hojas de estilos de los sitios web, se puede definir como una buena practica para crear estilos de manera ordenada, fácil de entender y escalable cuando se utilizan desarrollos que deben ser trabajados por un equipo de personas y se trabajan sitios web de manera modular. Cuando se utiliza esta metodología, el uso de identificadores para los estilos visuales  en la estructura del HTML y dentro de las hojas de estilos deja de servir, ya que la metodología sugiere manejar todo el estilo visual del sitio web mediante el uso de clases; Solo se deben utilizar los identificadores cuando se va a ejecutar alguna acción mediante Javascript.

Yandex es el buscador web más popular  en Rusia, incluso superando al poderoso Google. Este buscador se plantó y estructuró como un ecosistema de servicios web y soluciones online, en un momento de su potencial crecimiento sintió la necesidad de cambiar para mejorar su arquitectura frontend e implementar una metodología que les ayudase a tener su código de estilos rigurosamente estructurado, es así como en el 2010 surgió la idea de estructurar por medio de Bloques, Elementos y Modificadores (BEM), que va más que una metodología de arquitectura CSS, de hecho este es un marco completo para el sistema frontend  que incluye una serie de reglas y herramientas para un desarrollo frontend global.

Esta metodología sugiere una estructura para nombrar tus clases, basado en las propiedades del elemento en cuestión. Si alguna vez has visto un nombre de una clase como header_from-email eso es precisamente BEM en acción. Cuando utilices la metodología BEM, debes tomar en cuenta que solamente usarás nombres de clases (no IDs). Los nombres de clases te permiten repetir el nombre BEM si es necesario, y crear una estructura de código más consistente.

# Ventajas y Desventaja

--------------------

## Ventajas

* Permite el trabajo de módulos para reutilizar de una manera sencilla en el flujo del html.
* Permite el trabajo entre varios desarrolladores ya que promueve la organización de una manera lógica en las hojas de estilos.
* Se puede trabajar de manera muy sencilla con pre procesadores como SASS o STYLUS.

-----------------

## Desventajas

* Las clases pueden quedar muy largas al momento de utilizar la metodología.

# Bloque

El bloque es un contenedor o contexto donde el elemento se encuentra presente. Piensa como si fueran partes estructurales de código más grandes. Puede que tengas un encabezado, pie de página, una barra lateral y un área de contenido principal; cada uno de estos sería considerado como un bloque. Mira la imagen de abajo:

![](http://i.imgur.com/srDeDhQ.jpg)

El bloque de elementos forma la raíz de la clase y siempre irá primero. Solo debes saber que una vez que has definido tu bloque, estarás listo para comenzar a nombrar tus elementos.

# Elemento

El elemento es una pieza de un bloque. El boque es el todo y los elementos son las piezas. Cada elemento se escribe luego del bloque conectado por dos barras bajas.

```
.block__element
```

Es algo extraño al principio pero una vez que comienzas a usarlo te preguntarás cómo es que has escrito CSS sin usar BEM. La doble barra baja te permite visualizar, navegar rápidamente y manipular tu código.

Aquí hay algunos ejemplos de cómo funciona la metodología de elementos:

```
.header__logo {} 
.header__tagline {} 
.header__searchbar {}
.header__navigation {}
```

Como puedes ver, hay espacio para la creatividad y hacer de esta metodología tuya. En el ejemplo, "navigation" puede ser cambiado a "nav", "tagline" puede cambiarse a "tag" o "tagLine". El punto es mantener los nombres simples, claros, y precisos. No lo pienses demasiado, y solo porque tus hojas de estilos y html serán estáticos, no quiere decir que tengas que volver a repetir el mismo código. Actualizar el nombre de las clases no debería ser un problema cuando encuentras una mejor semántica que funcione (solo debes tratar de ser consistente y apegarte a ella). Los elementos se convertirán en el centro de los nombres de tus clases, y te ayudarán a entender cómo estructurar tus hojas de estilos y cómo manejar tu diseño.

# Modificadores

Cuando nombras una clase, la intención es ayudar a que ese elemento pueda ser repetido para que no tengas que escribir nuevas clases en otras áreas del sitio si los elementos de estilo son los mismos. Cuando necesitas modificar el estilo de un elemento específico, puedes usar un modificador. Para lograr esto, añades un doble guión -- luego del elemento (o bloque). Aquí tenemos un corto ejemplo:

```
.block--modifier {}
.block__element--modifier {}
```

Ten cuidado al usar los modificadores, recuerda que se quiere mantener todo más simple y no tener que repetir lo mismo o crear clases extras a menos que sea absolutamente necesario. Lo explicaremos con un código usando el encabezado del sitio como nuestro bloque:

```
.header__navigation {}
.header__navigation--secondary {}
```

Si estás usando una segunda navegación, lo más probable es que el diseño y espaciado no cambien, pero puede que la navegación secundaria tenga un color distinto. Puedes ya sea, duplicar los estilos originales, o mejor aún, usar un pre-procesador. Con Sass, podrías @extender el elemento principal (así el elemento secundario heredará todas las propiedades) y cambiar los estilos apropiados.

```
.header__navigation { 
background: #008cba; 
    padding: 1rem 0; 
    margin: 2rem 0; 
    text-transform: uppercase; 
    } 
     
.header__navigation--secondary { 
    @extend .header__navigation;
    background: #dfe0e0; 
    }
```

Es probable pensar que el nombre de la clase es muy largo.  Sin embargo, los nombres de las clases BEM son específicos, claros, fáciles de leer dentro del html, y comunican claramente para qué existen.

Una ventaja de los nombres de las clases cuando usamos BEM es que solo tienes que usar un nombre de clase por cada etiqueta html. Fíjate cómo funcionaría para la etiqueta "label". Selectores estándares:

```
.label .label-default {} 
.label .label-alert {}
```
vs. selectores BEM:

```
.label {}
.label--alert {}
```

Los lenguajes como Sass (específicamente Scss) nos permiten rápidamente tener elementos, compartir los mismos estilos con pequeñas excepciones. El ejemplo de abajo nos evita duplicar estilos, mas bien cambiamos sólo lo necesario. Otro punto importante de la metodologéa BEM es que no tienes que combinar clases ambiguas como "panel panel-default col-md-3". Si utilizas un framework como Foundation puedes comenzar a nivelar las diferencias. Pero para un ejemplo simple, pongamos estilo a las etiquetas que acabamos de definir.

```
.label { 
background: #eee; 
    border-radius: 505; 
    color: #333; 
    font-size: 1rem; 
    } 
     
.label--alert { 
    @extend .label; 
    background: #da4531; 
    color: #fff; 
    }
```
