<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software 2025-20</strong><br>
    <strong>Aplicaciones Web - 7432 </strong><br>
    <strong>Profesor: Oscar Ivan Villafuentes Bazan </strong><br>
    <strong>
Fundamentos de Desarrollo Web para Jóvenes</strong><br>
    <strong> CICLO 2025-20</strong><br>
</p>

<center>



</center>

<div align="center">

| Member                               | Code        |
|:--------------------------------------:|:-------------:|
|Carlos Alejandro De la cruz Villareal | U20211c036  |
|Franco Gabriel Huang Liu              | U202310345  |
|Gianfranco Luna Morales               | U201824343  |
|Andreow Jomark Santiago Peña          | U202317362  |


</div>

---

# Lección 1: Tu Primera Aventura Web

### Objetivos de la Lección:

- Introducir a los estudiantes al mundo del desarrollo web.
- Explicar qué son HTML y CSS.
- Comparar estos lenguajes mediante una analogía sencilla.
- Presentar CodePen como herramienta práctica para comenzar sin instalaciones.
- Motivar a los estudiantes con ejemplos reales de páginas web.

---

## ¿Qué es un Sitio Web?

Un sitio web es comparado con un libro digital interactivo.
Puede contener:

- Texto
- Videos
- Imágenes
- Enlaces
- Elementos interactivos

Ejemplos mencionados: Google, YouTube, blogs, etc.
Todos construidos con los mismos lenguajes que se aprenderán en el curso: HTML y CSS.

---

## HTML y CSS: Los dos lenguajes principales

### **HTML** - Estructura

Representa el contenido de la Página Web
Define lo que aparece:

- Títulos
- Párrafos
- Imágenes
- Enlaces
- Listas

Ejemplo:
```
<h1>¡Hola Mundo!</h1>
<p>Este es mi primer sitio web.</p>
```

### **CSS** - Estilos

Define cómo se ve la página:

- Colores
- Tamaños
- Tipografía
- Espacios
- Posiciones

Ejemplo:
	
 ```
h1 {
  color: blue;
  font-size: 36px;
}

p {
  color: gray;
}
```
### Analogía: Construir una casa

| Parte | Representa |
| ----------- | ----------- |
| HTML | Paredes, estructura, puertas. Lo que “se construye”. |
| CSS | Colores, muebles, decoración. Lo que “embellece”. |

---

## CodePen:

CodePen permite:

- Escribir HTML y CSS directamente en el navegador.
- Ver los cambios al instante.
- Practicar sin instalar software.
- Usar paneles divididos para HTML, CSS y vista previa.

Sitio mencionado: [codepen.io](https://codepen.io/)

---

# Lección 2: Lección 2: Construyendo con Bloques HTML

Bienvenido a la Lección 2 del curso Fundamentos de Desarrollo Web.
En esta sesión aprenderás las etiquetas esenciales de HTML y construirás tu primera página web completa usando CodePen o cualquier editor.

---

## Objetivos de la lección:

En esta lección los estudiantes aprenderán:

- La estructura básica de un documento HTML.
- Las etiquetas fundamentales para crear contenido.
- A construir su primera página web completa.
- A practicar directamente en CodePen.

---

## 1. Estructura Básica de una Página HTML

```
<!DOCTYPE html>
<html>
<head>
  <title>Mi Primera Página</title>
</head>
<body>
  <!-- Aquí va todo nuestro contenido -->
</body>
</html>
```
- `<!DOCTYPE html>` -> Indica que es un documento HTML moderno.
- `<html>`  -> Contenedor principal.
- `<head>`  -> Información invisible al usuario (título, metadatos).
- `<title>`  -> Título visible en la pestaña del navegador.
- `<body>` -> Contenido visible de la página.

---

## 2. Añadiendo Contenido: Encabezados y Párrafos

**Encabezados:**

```
<h1>¡Hola! Soy [Tu Nombre]</h1>
<h2>Este es un subtítulo</h2>
<h3>Este es un subtítulo más pequeño</h3>
```

- `<h1>` -> Título principal
- `<h2>`  -> Secciones
- `<h3>`  -> Subsecciones

**Parrafos:**

```
<p>Esta es mi primera página web y estoy aprendiendo HTML.</p>
<p>HTML me permite crear contenido para internet.</p>
```

---

## 3. Otras Etiquetas Únicas:

**Negritas y Cursivas:**

```
<p>Palabra en <strong>negrita</strong> y palabra en <em>cursiva</em>.</p>
```

**Saltos de línea**

```
<p>Primera línea<br>Segunda línea</p>
```

---

## 4. Comentarios en HTML:

```
<!-- Esto es un comentario -->
<!-- No se muestra en la página -->
```
Nota: Los comentarios te ayudan a dejar notas y organizar tu código.

---

##5. Ejercicio Práctico:

Crea una página HTML que incluya:

- Un `<h1>` con tu nombre.
- Un `<h2>` con algo que te guste hacer.
- Dos o más párrafos sobre ti.
- Texto en `<strong>` y `<em>`.
- Al menos dos comentarios.



# Lección 4: El Arte de los Colores - CSS Parte 1

Bienvenido a la Lección 4 del curso Fundamentos de Desarrollo Web.
En esta sesión descubrirás cómo dar vida y color a tus páginas web usando CSS.

---

## Objetivos de la lección:

En esta lección los estudiantes aprenderán:

- Qué es CSS y para qué sirve.
- Cómo conectar CSS con HTML usando la etiqueta `<style>`.
- Los selectores básicos: elemento, clase e ID.
- Propiedades fundamentales: colores, fuentes y tamaños.
- Los diferentes sistemas de especificación de colores.

---

## 1. ¿Qué es CSS?

**CSS (Cascading Style Sheets)** es el lenguaje que usamos para dar estilo a nuestras páginas web.

- **HTML** define la estructura y el contenido.
- **CSS** define cómo se ve ese contenido.

Con CSS podemos cambiar:
- Colores
- Tamaños de fuente
- Espaciados
- Posiciones
- Y mucho más

---

## 2. Cómo Conectar CSS con HTML

La forma más sencilla de empezar es usando la etiqueta `<style>` dentro del `<head>`:

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Mi Página con Estilos</title>
    
    <style>
        /* Aquí escribimos nuestro CSS */
        body {
            background-color: #f0f8ff;
        }
    </style>
</head>
<body>
    <h1>¡Hola Mundo!</h1>
</body>
</html>
```

**Nota:** Los comentarios en CSS se escriben con `/* comentario */`

---

## 3. Selectores Básicos

Los selectores nos permiten elegir qué elementos queremos estilizar:

### **Selector de elemento**
Selecciona todas las etiquetas del mismo tipo:

```css
h1 {
    color: blue;
}

p {
    font-size: 18px;
}
```

### **Selector de clase (.clase)**
Selecciona elementos con una clase específica:

```html
<div class="ejemplo-caja">Contenido</div>
```

```css
.ejemplo-caja {
    background-color: lightgray;
    padding: 10px;
}
```

### **Selector de ID (#id)**
Selecciona un elemento único por su ID:

```html
<div id="principal">Contenido principal</div>
```

```css
#principal {
    color: darkblue;
    font-size: 20px;
}
```

---

## 4. Propiedades de Colores y Fuentes

### **Propiedades de Color:**

- `color` -> Color del texto
- `background-color` -> Color de fondo

```css
h1 {
    color: #2563eb;
    background-color: #f0f8ff;
}
```

### **Propiedades de Fuente:**

- `font-family` -> Tipo de fuente
- `font-size` -> Tamaño de la fuente
- `line-height` -> Espaciado entre líneas

```css
p {
    font-family: Arial, sans-serif;
    font-size: 18px;
    line-height: 1.6;
}
```

---

## 5. Sistemas de Color en CSS

CSS nos permite especificar colores de tres formas principales:

### **Nombres de colores:**
```css
color: red;
background-color: blue;
color: green;
```

### **Código Hexadecimal:**
Formato: `#RRGGBB` (Red, Green, Blue)

```css
color: #FF0000;  /* Rojo */
color: #0000FF;  /* Azul */
color: #00FF00;  /* Verde */
color: #333333;  /* Gris oscuro */
```

### **RGB (Red, Green, Blue):**
Valores de 0 a 255 para cada color:

```css
color: rgb(255, 0, 0);    /* Rojo */
color: rgb(0, 0, 255);    /* Azul */
color: rgb(0, 255, 0);    /* Verde */
```

---

## 6. Ejemplo Completo con Código

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lección 4: Introducción a CSS</title>
    
    <style>
        /* Aquí es donde escribimos nuestro CSS */
        
        /* Estilo para el body (toda la página) */
        body {
            background-color: #f0f8ff;
            font-family: Arial, sans-serif;
            padding: 20px;
        }
        
        /* Estilo para los encabezados h1 */
        h1 {
            color: #2563eb;
            font-size: 36px;
        }
        
        /* Estilo para los párrafos */
        p {
            color: #333333;
            font-size: 18px;
            line-height: 1.6;
        }
        
        /* AHORA ES TU TURNO: añade estilos aquí */
        
    </style>
</head>
<body>
    <h1>¡Bienvenido al Mundo de los Estilos!</h1>
    
    <p>
        CSS nos permite cambiar la apariencia de nuestra página web. 
        Podemos cambiar colores, fuentes, tamaños y mucho más.
    </p>
    
    <h2>Conceptos Básicos de CSS</h2>
    
    <h3>1. Selectores</h3>
    <p>
        Los selectores nos permiten elegir qué elementos queremos estilizar.
        Por ejemplo, "h1" selecciona todos los títulos principales.
    </p>
    
    <h3>2. Propiedades</h3>
    <p>
        Las propiedades son las características que queremos cambiar.
        Por ejemplo: color, font-size, background-color.
    </p>
    
    <h3>3. Valores</h3>
    <p>
        Los valores son lo que asignamos a cada propiedad.
        Por ejemplo: red, 20px, #f0f0f0.
    </p>
    
    <!-- Ejemplo con clases -->
    <div class="ejemplo-caja">
        <h3>Esta es una caja de ejemplo</h3>
        <p>Podemos usar clases para aplicar estilos específicos.</p>
    </div>
    
    <!-- 
        DESAFÍO:
        1. Cambia el color de fondo del body
        2. Cambia el color de los h2
        3. Aumenta el tamaño de fuente de los párrafos
        4. Añade un estilo para la clase "ejemplo-caja"
    -->
    
    <hr>
    
    <h2>Colores en CSS</h2>
    <p>Podemos especificar colores de tres maneras:</p>
    <ul>
        <li><strong>Nombres:</strong> red, blue, green</li>
        <li><strong>Hexadecimal:</strong> #FF0000, #0000FF, #00FF00</li>
        <li><strong>RGB:</strong> rgb(255, 0, 0), rgb(0, 0, 255)</li>
    </ul>
    
    <h2>Practica Aquí</h2>
    <p>Añade tu propio contenido y estilos abajo:</p>
    
    <!-- Tu código aquí -->
    
</body>
</html>

## Recursos Adicionales

- **Selector de colores:** [HTML Color Picker](https://www.w3schools.com/colors/colors_picker.asp)
- **Fuentes de Google:** [Google Fonts](https://fonts.google.com/)
- **Práctica en CodePen:** [codepen.io](https://codepen.io/)

