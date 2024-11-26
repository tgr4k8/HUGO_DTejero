+++
draft =  false
title = "Apuntes sobre CSS"

draft=  false
+++
---
# Apuntes sobre CSS

CSS (Cascading Style Sheets) es un lenguaje que define la apariencia y formato de un documento escrito en HTML. Aquí encontrarás conceptos clave, propiedades importantes y ejemplos prácticos.

---

## 1. **Selectores Básicos**
Los selectores en CSS permiten aplicar estilos a elementos específicos del DOM.  
Algunos de los más comunes son:

- **Universal (`*`)**: Selecciona todos los elementos.
```
  ```css
  * {
      margin: 0;
      padding: 0;
  }
 ```

- Elemento (h1, p): Aplica estilos a etiquetas específicas.
```
p {
color: blue;
}
```


- Clase (.clase): Selecciona elementos con una clase específica.
```
.destacado {
    font-weight: bold;
}
```

## Modelo caja

El modelo de caja describe cómo se calculan los tamaños de los elementos en CSS.
Incluye las siguientes propiedades:

    Content: El contenido del elemento.
    Padding: Espacio entre el contenido y el borde.
    Border: El borde alrededor del padding.
    Margin: Espacio externo fuera del borde.

Ejemplo:

```
div {
    width: 100px;
    height: 100px;
    padding: 10px;
    border: 5px solid black;
    margin: 20px;
}
```