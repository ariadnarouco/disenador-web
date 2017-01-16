# Media queries
* Crear un elemento que cambie de color de fondo en 4 puntos al redimensionar nuestra página web
* La letra del elemento anterior, debera de cambiar de color dependiendo si la página está en un formato portrait o landscape
* Utilizar metodología "Movil First"

## Resolución

```html
<!DOCTYPE html>
  <html>
    <head>
      <meta charset="UTF-8">
      <title>Colores</title>
      <style>
      .clase-1{
        background-color: white;
        font-size: 32px;
      }
      @media only screen and (orientation: landscape) {
        .clase-1 {
            color: orange;
        }
      }
      @media only screen and (min-width: 480px) {
        .clase-1 {
            background-color: blue;
        }
      }
      @media only screen and (min-width: 600px) {
        .clase-1 {
            background-color: red;
        }
      }
      @media only screen and (min-width: 768px) {
        .clase-1 {
            background-color: green;
        }
      }
      </style>
    </head>
    <body>
      <div class="clase-1">
        RESPONSIVE!!!!!!!
      </div>
    </body>
  </html>
```
