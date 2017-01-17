# SaSS
* Cree un archivo .scss
* Cree 3 variable con los nombres color_principal, color_secundario, auxiliar
* Crear 1 mixins para utilizarlos en su archivo
* Definir las dimensiones de sus elementos, de manera proporcional, aprovechando la flexibilidad de utilizar operadores matemáticos en un pre-procesador de CSS.

## Resolución

```CSS
  $color_principal: #556789;
  $color_secundario: #445678;
  $auxiliar: #667789;

  @mixin border-radius($radius) {
    -webkit-border-radius: $radius;
       -moz-border-radius: $radius;
        -ms-border-radius: $radius;
            border-radius: $radius;
  }

  .container {
    width: 600px / 960px * 100%;
  }
```
