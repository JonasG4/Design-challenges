## Envelope Open Animation

![Alt Text](https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExMWRrcTZ2a2RhYXE2dHUxZndybmlkajVmMmhmYWx2eWwzNHd4Zng1OCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/xeG1vYCiimZzwWH31d/giphy.gif)

#### Importante

**Flap**
Es la mitad de grande que el `envelope` pero la punta cubre por `8px` al `pocket`

**Heart**
Al terminar la animación los corazones no deben mostrarse. No tiene animación de cierre.

#### Conocimiento necesario

**Transform-origen**
El origen de la transformación es el punto alrededor del cual se aplica una transformación. Por ejemplo, el origen de transformación de la función rotar() es el centro de rotación. De hecho, esta propiedad envuelve un par de traducciones alrededor de las otras transformaciones del elemento.

Ejemplo:

```css
. clock-min-hand {
  width: 2px;
  height: 50px;
  background-color: black;
  animation: wheel 60s infinity;
  transform-origin: right;
}
```

**Función Calc()**

La función calc() de CSS nos permite asignar cálculos aritméticos a propiedades de elementos de nuestras hojas de estilo

Ejemplo:

```css
.rectangle {
  width: 100px;
  height: calc(100px / 2); /*50px */
}
```

**Hacer un triángulo**

Dependiendo del border que tenga el color será la dirección. Los demás deberán ser transparentes.

Ejemplo:

```css
.triangule {
  border-bottom: 100px solid transparent;
  border-top: 100px solid transparent;
  border-left: 100px solid transparent;
  border-right: 100px solid red;
}
```
