* Crear un grandiente lineal 

````html
<!DOCTYPE html>
<html>
<head>
<style>
#grad1 {
    height: 200px;
    background: red; /* For browsers that do not support gradients */
    background: -webkit-linear-gradient(red, yellow); /* For Safari 5.1 to 6.0 */
    background: -o-linear-gradient(red, yellow); /* For Opera 11.1 to 12.0 */
    background: -moz-linear-gradient(red, yellow); /* For Firefox 3.6 to 15 */
    background: linear-gradient(red, yellow); /* Standard syntax (must be last) */
}
</style>
</head>
<body>

<h3>Gradiente Lineal</h3>

<div id="grad1"></div>

</body>
</html>

````

* Crear un gradiente con transparencia.

````html

<!DOCTYPE html>
<html>
<head>
<style>
#grad1 {
    height: 200px;
    background: -webkit-linear-gradient(left, rgba(255,0,0,0), rgba(255,0,0,1)); /* For Safari 5.1 to 6.0 */
    background: -o-linear-gradient(right, rgba(255,0,0,0), rgba(255,0,0,1)); /* For Opera 11.1 to 12.0 */
    background: -moz-linear-gradient(right, rgba(255,0,0,0), rgba(255,0,0,1)); /* For Firefox 3.6 to 15 */
    background: linear-gradient(to right, rgba(255,0,0,0), rgba(255,0,0,1)); /* Standard syntax (must be last) */
}
</style>
</head>
<body>

<h3>Gradiente con transparencia</h3>

<div id="grad1"></div>

</body>
</html>

````

* Crear un ejemplo rotando un elemento.

````html

<!DOCTYPE html>
<html>
<head>
<style>
div {
    width: 200px;
    height: 100px;
    background-color: yellow;
    /* Rotate div */
    -ms-transform: rotate(7deg); /* IE 9 */
    -webkit-transform: rotate(7deg); /* Chrome, Safari, Opera */
    transform: rotate(7deg);
}
</style>
</head>
<body>

<div>Hola</div>
<br>

</body>
</html>

````
