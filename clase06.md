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

