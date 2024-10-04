# Apuntes de Estilos con Tailwind CSS

## Tabla de Contenidos
1. [Colores (Textos y Fondos)](#1-colores-textos-y-fondos)
2. [Tipografía](#2-tipografía)
3. [Espaciados](#3-espaciados)
4. [Dimensiones](#4-dimensiones)
5. [Bordes](#5-bordes)
6. [Flexbox y Grid](#6-flexbox-y-grid)
7. [Sombras](#7-sombras)
8. [Opacidad](#8-opacidad)

---

## 1. Colores (Textos y Fondos)

### Textos
Usa la clase `text-{color}-{shade}` para cambiar el color del texto.  
Ejemplo:

| Clase        | Descripción                           |
|--------------|---------------------------------------|
| `text-red-500` | Texto de color rojo con una intensidad de 500 |

### Fondo
Para cambiar el color de fondo, usa la clase `bg-{color}-{shade}`.  
Ejemplo:

| Clase          | Descripción                             |
|----------------|-----------------------------------------|
| `bg-green-300` | Fondo verde con una intensidad de 300 |

---

## 2. Tipografía

### Tamaño de Fuente
```html
text-{size}
```
Ejemplos:

| Clase      | Descripción             |
|------------|-------------------------|
| `text-xs`  | Fuente muy pequeña       |
| `text-lg`  | Fuente grande            |
| `text-4xl` | Fuente extra grande      |

### Grosor de Fuente
```html
font-{weight}
```
Ejemplos:

| Clase        | Descripción             |
|--------------|-------------------------|
| `font-thin`  | Fuente delgada           |
| `font-bold`  | Fuente negrita           |
| `font-black` | Fuente extra negrita     |

### Alineación de Texto
```html
text-{alignment}
```
Ejemplos:

| Clase         | Descripción                         |
|---------------|-------------------------------------|
| `text-left`   | Alinear texto a la izquierda         |
| `text-center` | Centrar texto                       |
| `text-right`  | Alinear texto a la derecha          |

---

## 3. Espaciados

### Márgenes (Margin)
```html
m-{size} 
mx-{size} // solo en los ejes x (horizontal)
my-{size} // solo en los ejes y (vertical)
```
Ejemplos:

| Clase  | Descripción                           |
|--------|---------------------------------------|
| `m-4`  | Margen de 1 rem                       |
| `mx-2` | Margen horizontal de 0.5 rem          |
| `my-6` | Margen vertical de 1.5 rem            |

### Padding (Relleno)
```html
p-{size}
px-{size} // solo en los ejes x (horizontal)
py-{size} // solo en los ejes y (vertical)
```
Ejemplos:

| Clase  | Descripción                             |
|--------|-----------------------------------------|
| `p-2`  | Padding de 0.5 rem                      |
| `px-3` | Padding horizontal de 0.75 rem          |
| `py-4` | Padding vertical de 1 rem               |

---

## 4. Dimensiones

### Ancho (Width)
```html
w-{size}
```
Ejemplos:

| Clase    | Descripción             |
|----------|-------------------------|
| `w-1/2`  | Ancho del 50%           |
| `w-full` | Ancho del 100%          |
| `w-96`   | Ancho de 24 rem         |

### Altura (Height)
```html
h-{size}
```
Ejemplos:

| Clase      | Descripción                  |
|------------|------------------------------|
| `h-64`     | Altura de 16 rem              |
| `h-screen` | Altura completa de la pantalla|

---

## 5. Bordes

### Bordes
```html
border-{size} 
border-{color}-{shade}
```
Ejemplos:

| Clase            | Descripción                           |
|------------------|---------------------------------------|
| `border-2`       | Borde de 2px                          |
| `border-red-500` | Borde de color rojo con intensidad 500 |

### Bordes Redondeados
```html
rounded-{size}
```
Ejemplos:

| Clase           | Descripción                             |
|-----------------|-----------------------------------------|
| `rounded-sm`    | Bordes ligeramente redondeados          |
| `rounded-full`  | Bordes completamente redondeados (círculo) |

---

## 6. Flexbox y Grid

### Flexbox
```html
flex
justify-{alignment}
items-{alignment}
```
Ejemplos:

| Clase           | Descripción                               |
|-----------------|-------------------------------------------|
| `flex`          | Convertir un contenedor en un flexbox      |
| `justify-center`| Centrar elementos horizontalmente          |
| `items-center`  | Centrar elementos verticalmente            |

### Grid
```html
grid
grid-cols-{n}
gap-{size}
```
Ejemplos:

| Clase           | Descripción                                  |
|-----------------|----------------------------------------------|
| `grid`          | Crear un contenedor de grid                  |
| `grid-cols-3`   | Crear una cuadrícula con 3 columnas          |
| `gap-4`         | Separación de 1 rem entre los elementos del grid |

---

## 7. Sombras
```html
shadow-{size}
```
Ejemplos:

| Clase        | Descripción            |
|--------------|------------------------|
| `shadow-sm`  | Sombra pequeña          |
| `shadow-lg`  | Sombra grande           |

---

## 8. Opacidad
```html
opacity-{percentage}
```
Ejemplos:

| Clase         | Descripción                   |
|---------------|-------------------------------|
| `opacity-50`  | 50% de opacidad                |
| `opacity-100` | Opacidad completa (100%)       |

---








