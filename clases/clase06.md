# Gradientes

CSS3 ha agregado la opción de crear gradientes (fondos en degradé) sin la necesidad de usar imágenes.

Los gradientes en CSS son de dos tipos: lineales (```linear-gradient```) o radiales (```radial-gradient```). En el gradiente lineal, la transformación de color va avanzando línea a línea, mientras que en el radial, la transformación de color se produce debido a que sucesivos círculos concéntricos van cambiando de color.

La propiedad que utilizamos para realizar gradientes lineales, se llama ```linear-gradient``` y esta se agrega al atributo ```background```, que ya vimos con anterioridad.

Esta propiedad maneja dos opciones de parámetros, podemos elegir el punto de inicio o sea si queremos que lo aplique arriba, abajo, a la derecha o a la izquierda de nuestra caja o podemos elegir los grados de inclinación que queremos que tenga nuestro gradiente.

Los puntos de inicio pueden ser ```top```, ```right```, ```left``` o ```bottom```.

Entonces, supongamos que queremos aplicarle a nuestra caja un gradiente que va de negro a gris desde la parte de arriba de la misma. La sintaxis sería la siguiente:

```div {
background: linear-gradient (to top, #000, #ccc)
}```

Si lo que queremos es aplicar un gradiente de 90º, entonces la sintaxis sería así:

```div {
background: linear-gradient (90deg, #000, #ccc)
}```

Algunas cosas a tener en cuenta, la propiedad ```linear-gradient``` no genera un color de fondo, sino una imagen sin dimensiones específicas, esta se va a adaptar automáticamente para cubrir todo el espacio disponible.

Por otro lado, no todos los navegadores soportan esta propiedad.

# Transformaciones

Las transformaciones CSS ofrecen la posibilidad de modificar el desplazamiento, escala, rotación, sesgo de elementos y en combinación con las transiciones nos permite crear animaciones css modificando gradualmente sus propiedades.

De las transformaciones de CSS3 en 2D, las más usadas son:

* **Rotate**: Rotate te permite rotar un elemento dándole un ángulo de giro en grados.
* **Scale**: Scale te permite escalar un elemento, toma valores positivos y negativos y se le pueden poner decimales.
* **Translate**: Translate nos permite trasladar un elemento a la vez en el eje de las X y de las Y, dándole las coordenadas iniciales y finales.
* **Trasladar**: Esta propiedad de CSS3 no hace propiamente una transición, sino que hace que un elemento pase de estar en una posición a estar en otra. Con las transiciones y las animaciones de CSS3 vamos a poder darle un efecto visual de movimiento.

Ejemplo:

```transform: translate(10px, 20px);```

![](https://coderhouse.gitbooks.io/clase-5-fundamentos/content/Captura%20de%20pantalla%202015-10-08%2011.59.56.png)

**Rotación**: Se puede aplicar tanto a elemento inline como a elementos de bloque.

![](https://coderhouse.gitbooks.io/clase-5-fundamentos/content/Captura%20de%20pantalla%202015-10-08%2012.00.04.png)

```.ejemplo {
transform: rotate (45deg);
}```

Los grados se marcan en positivo si el elemento se rota en el sentido de las agujas del reloj y en negativo si es al revés.

Por defecto, el punto de referencia que toma como eje para hacer la rotación es el centro, pero también se puede especificar otro punto.

**Escalar**: Otro punto interesante va a ser escalar un elemento con CSS3.

![](https://coderhouse.gitbooks.io/clase-5-fundamentos/content/Captura%20de%20pantalla%202015-10-08%2012.00.12.png)

Si el valor es positivo, el elemento se hace más grande, y si es negativo se hace más pequeño.

--------------------

# Transiciones

Las transiciones permiten controlar la velocidad a la que se van a modificar las propiedades de un elemento inclusive se pueden aplicar curvas de aceleración permitiendo de esta forma crear animaciones.

# Animaciones

Una animación tiene lugar en el tiempo, con lo que vamos a tener que tomar diferentes puntos dentro de un fragmento de tiempo para especificar que sucede en cada uno de ellos. Es lo que se llaman **keyframes**. Para los que ya han trabajado en Flash u otros programas de animación ya conocen el concepto. En cada keyframe podemos introducir un cambio y la suma de estos cambios es lo que va a dar lugar a la animación final.

Para indicar la duración de una animación utilizaremos la propiedad ```animation-duration```.

La velocidad de la animación estará gestionado por la propiedad ```animation-timing-function```.

También en las animaciones de CSS3 podemos especificar un tiempo de espera antes de iniciar la animación con la propiedad ```animation-delay```.

Con la propiedad ```animation-direction``` podremos indicarle que la propiedad se haga en sentido inverso al habitual, es decir, que empiece por el final.

Para aprender más sobre esto, pueden ver [http://daneden.github.io/animate.css/](http://daneden.github.io/animate.css/)

# Media queries

Los media types permiten indicar una serie de estilos que se aplicarán según el tipo del medio, en algunas páginas, al ver el código fuente, nos encontramos algo como lo siguiente en su head

Las **media queries** son propias de CSS3 y vienen a extender a los media, utilizando un media type con una serie de expresiones relacionadas con las características del dispositivo desde el cual se accede a la web. Las media queries dan como resultado verdadero o falso. Si el resultado es verdadero, se leen las reglas CSS de su interior, si es falso no.

Ejemplo:

```@media (max-width: 600px) {
}```

Este sencillo ejemplo tiene una media query que significa lo siguiente:

Cuando el ancho de la pantalla tenga un ancho menor a 600px lees el código encerrado dentro de las llaves que abren y cierran la media querie.

Ejemplo:

```body {
background: green;
}```

```@media (max-width: 600px) {
body {
background: red;
}
}```

Esto hará que el fondo de la web sea verde, pero cuando la pantalla sea menor a 600px el fondo será rojo.

Las posibilidades y combinaciones son muchas y su uso está generalizado. Bootstrap o Foundation son sólo dos ejemplos de frameworks CSS que basan todo su funcionamiento en las media queries, lo que nos permite tener webs adaptables.

Al igual que hay varios media types, las media queries tienen varias expresiones a utilizar, las más interesantes para el responsive design son:

* **orientation**: permite tomar por valores landscape o portrait lo que significa que la orientación sea horizontal o vertical, o sea, landscape si la ventana es más ancha que alta y portrait si es más alta que ancha.
* **resolution**: Permite las variantes ```min-resolution``` y ```max-resolution```. El valor que toma es la densidad de la pantalla en valor de puntos por pulgada (dpi) o en puntos por pixel (dppx). Su uso principal es para cambiar los background de imágenes según el dispositivo sea de alta resolución (como los retina display, iphone, …) o normal para que no se carguen más datos de los necesarios.
* **width**: El alto del dispositivo. Se permiten las variantes ```min-width``` y ```max-width```. Es la principal expresión para el responsive design.

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