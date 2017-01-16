# Primeros colores en una web
* Crear una página web que contenga al menos 9 elementos con clases diferentes y dentro de cada uno de ellos escriba texto.
* Utilice los selectores de clases, para dar color de fondo diferentes a cada elemento según su clase. Utilice las 3 sintaxis vistas: nombres, rgb y hex.
* Formatee el texto de cada uno de los elementos, cambiando el tamaño del texto, el tipo de letra y el color.
* Al menos en uno de los elementos, utilizar fuentes obtenidas de internet (Google Fonts o FontSquirl)

## Resolución
```html
<!DOCTYPE html>
    <html>
        <head>
            <meta charset="UTF-8">
            <title>Colores</title>
            <link href="https://fonts.googleapis.com/css?family=Oswald" rel="stylesheet">
            <style>
              .clase-1{
                  background-color: #000;
                  font-size: 18px;
                  color: #00f;
                  font-family: "Times New Roman", Times, serif;
              }
              .clase-2{
                  background-color: #ff5588;
                  font-size: 22px;
                  color: green;
                  font-family: sans-serif;
              }
              .clase-3{
                  background-color: blue;
                  font-size: 12px;
                  color: yellow;
                  font-family: monospace;;
              }
              .clase-4{
                  background-color: rgb(15,64,0);
                  font-size: 1.5em;
                  color: #3c27bd;
                  font-family: 'Oswald', sans-serif;
              }
              .clase-5{
                  background-color: rgb(34,56,200);
                  font-size: 0.8em;
                  color: rgb(146, 175, 136);
              }
              .clase-6{
                  background-color: red;
                  font-size: 33px;
                  color: rgb(182, 76, 31);
              }
              .clase-7{
                  background-color: green;
                  font-size: 2rem;
                  color: #945f58;
              }
              .clase-8{
                  background-color: rgb(0,255,0);
                  font-size: 14pt;
                  color: cyan;
              }
              .clase-9{
                  background-color: #0F0;
                  font-size: 10em;
                  color: DarkBlue;
              }
            </style>
        </head>
        <body>
          <div class="clase-1">
            Primer Elemento
          </div>
          <div class="clase-2">
            Segundo Elemento
          </div>
          <div class="clase-3">
            Tercer Elemento
          </div>
          <div class="clase-4">
            Cuardo Elemento
          </div>
          <div class="clase-5">
            Quinto Elemento
          </div>
          <div class="clase-6">
            Sexto Elemento
          </div>
          <div class="clase-7">
            Septimo Elemento
          </div>
          <div class="clase-8">
            Octavo Elemento
          </div>
          <div class="clase-9">
            Noveno Elemento
          </div>
        </body>
    </html>
```
