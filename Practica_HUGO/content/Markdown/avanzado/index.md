+++
draft = false
title = 'Markdown Avanzado'
+++
## Tablas
Para tablas podemos usar los carácteres "|" y "-" :

Ejemplo: 

```
| Nombre       | Edad         |
|--------------|--------------|
| David        | 28           |
| María        | 26           |
```
Se veria: 

| Nombre       | Edad         |
|--------------|--------------|
| David        | 28           |
| María        | 26           |

## Codigo
Para indicar el encabezado de un código utilizamos ``` `Encabezado` ``` y para el código en si
podemos utilizar
``` 
```código``` 
```
Ejemplo:

`Encabezado`

```javascript
console.log("Hola Mundo");

```
## Tareas
Para tareas por ejemplo podemos usar:
``` 
- []  
- [x] Para indicar que esta realizada
```

Ejemplo:

- [x] Hacer la compra
- [ ] Limpiar el baño

## Diagramas: 



Ejemplo: 

<div class="mermaid">
graph TD;
    A[Inicio] --> B[Proceso 1];
    B --> C{Decisión};
    C -->|Sí| D[Proceso 2];
    C -->|No| E[Proceso Alternativo];
    D --> F[Fin];
    E --> F;
</div>
