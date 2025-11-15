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
