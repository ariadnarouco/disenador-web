# LeSS
* Cree un archivo less
* Cree 3 variable con los nombres color_principal, color_secundario, auxiliar
* Crear 1 mixins para utilizarlos en su archivo
* Definir las dimensiones de sus elementos, de manera proporcional, aprovechando la flexibilidad de utilizar operadores matemáticos en un pre-procesador de CSS.


## Resolución

```CSS
  @color_principal: #556789;
  @color_secundario: #445678;
  @auxiliar: #667789;

  .radius {
    -webkit-border-radius: 5;
       -moz-border-radius: 5;
        -ms-border-radius: 5;
            border-radius: 5;
  }

  .container {
    width: 2 + 5px + 3cm;
  }
```
