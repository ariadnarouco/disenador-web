* Vamos a crear nuestros primeros contenedores.

````html
<!DOCTYPE html>
<html>
<head>
<style>
.flex-container {
    display: -webkit-flex;
    display: flex;
    width: 400px;
    height: 250px;
    background-color: lightgrey;
}

.flex-item {
    background-color: Black;
    color: white;
    width: 100px;
    height: 100px;
    margin: 10px;
}
</style>
</head>
<body>

<div class="flex-container">
  <div class="flex-item">El item 1</div>
  <div class="flex-item">El item 2</div>
  <div class="flex-item">El item 3</div>
</div>

</body>
</html>

````
