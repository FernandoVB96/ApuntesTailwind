# Apuntes de Estilos con Tailwind CSS

## 1. Colores (Textos y Fondos)

### Textos
```html
text-{color}-{shade}
```
Ejemplo:
text-red-500: Texto de color rojo con una intensidad de 500.

### Fondo
```html
bg-{color}-{shade}
```
Ejemplo:
bg-green-300: Fondo verde con una intensidad de 300.

## 2. Tipografía

### Tamaño de fuente
```html
text-{size}
```
Ejemplos:

text-xs: Fuente muy pequeña.  
text-lg: Fuente grande.  
text-4xl: Fuente extra grande.  

### Grosor de Fuente
```html
font-{weight}
```
Ejemplos:

font-thin: Fuente delgada.  
font-bold: Fuente negrita.  
font-black: Fuente extra negrita.  

### Alineación de Texto
```html
text-{alignment}
```
Ejemplos:

text-left: Alinear texto a la izquierda.  
text-center: Centrar texto.  
text-right: Alinear texto a la derecha.  

## 3. Espaciados

### Márgenes (Margin)
```html
m-{size} 
mx-{size} // solo en los ejes x (horizontal)
my-{size} // solo en los ejes y (vertical)
```
Ejemplos:

m-4: Margen de 1 rem.  
mx-2: Margen horizontal de 0.5 rem.  
my-6: Margen vertical de 1.5 rem.  

### Padding (Relleno)
```html
p-{size}
px-{size} // solo en los ejes x (horizontal)
py-{size} // solo en los ejes y (vertical)
```
Ejemplos:

p-2: Padding de 0.5 rem.  
px-3: Padding horizontal de 0.75 rem.  
py-4: Padding vertical de 1 rem.  

## 4. Dimensiones

### Ancho (Width)

```html
w-{size}
```
Ejemplos:

w-1/2: Ancho del 50%.  
w-full: Ancho del 100%.  
w-96: Ancho de 24 rem.  

### Altura (Height)
```html
h-{size}
```
Ejemplos:

h-64: Altura de 16 rem.  
h-screen: Altura completa de la pantalla.  

## 5. Bordes

### Bordes
```html
border-{size} 
border-{color}-{shade}}
```
Ejemplos:

border-2: Borde de 2px.  
border-red-500: Borde de color rojo con intensidad 500.  

### Bordes Redondeados
```html
rounded-{size}
```
Ejemplos:

rounded-sm: Bordes ligeramente redondeados.  
rounded-full: Bordes completamente redondeados (círculo).  

## 6. Flexbox y Grid

### Flexbox
```html
flex
justify-{alignment}
items-{alignment}
```
Ejemplos:

flex: Convertir un contenedor en un flexbox.  
justify-center: Centrar elementos horizontalmente.  
items-center: Centrar elementos verticalmente.  

### Grid
```html
grid
grid-cols-{n}
gap-{size}
```
Ejemplos:

grid: Crear un contenedor de grid.  
grid-cols-3: Crear una cuadrícula con 3 columnas.  
gap-4: Establecer una separación de 1 rem entre los elementos del grid.  

## 7. Sombras
```html
shadow-{size}
```
Ejemplos:

shadow-sm: Sombra pequeña.  
shadow-lg: Sombra grande.  

## 8. Opacidad
```html
opacity-{percentage}
```
Ejemplos:

opacity-50: 50% de opacidad.  
opacity-100: Opacidad completa (100%).  








