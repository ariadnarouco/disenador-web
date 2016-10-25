* Crear un archivo CSS y un parrafo.

***CSS***
````css
p {
    color: red;
    text-align: center;
}
````
***HTML***
````html
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam sed metus tempus, pretium purus vitae, congue sem. 
Vestibulum aliquam diam quam, ut rhoncus justo sodales sed. Integer placerat fermentum mi, eu volutpat risus. 
Etiam interdum vestibulum sapien eu fringilla. Pellentesque congue purus massa, sit amet cursus mi dictum eu. 
Mauris rhoncus blandit ante. Ut fringilla augue enim, a imperdiet purus vulputate scelerisque.

Nullam ullamcorper risus ac faucibus congue. Aliquam id felis velit. Vivamus metus enim, fermentum nec tortor vitae, 
imperdiet cursus risus. Ut tristique, arcu eu luctus convallis, elit odio bibendum nisl, sed pharetra massa metus at augue. 
Aliquam erat volutpat. Nullam ultrices sed libero sit amet commodo. Curabitur porta sapien ac mauris sagittis rhoncus.
</p>
````


* Luego utilizar un ID para1

***CSS***

````css
#para1 {
    text-align: center;
    color: red;
}
````
***HTML***

````html
<div id="para1">
Lorem ipsum dolor sit amet, consectetur adipiscing elit.
</div>
````

* Agregar fuentes y estilos a un parrafo.

***CSS***

````css
p { font-family: Arial, Helvetica, sans-serif; font-size: 14px; font-style: italic; }
````

* Agregar fuentes de Google Fonts

````html
<link href='http://fonts.googleapis.com/css?family=Euphoria+Script' rel='stylesheet' type='text/css'>
````
````css
h1 { font-family: 'Euphoria Script', cursive; }
````

* Agregar iconos 

````html
<link href='http://code.ionicframework.com/ionicons/2.0.1/css/ionicons.min.css' rel='stylesheet' type='text/css'>
````
````html
<i class="icon ion-checkmark-round></i>
````
