# Curso de Fronted Developer

Por: **Estefany Aguilar** [@teffcode](#)

## Introducción

### 1. Inicia tu camino como frontend developer

- HTML
- CSS
- Responsive Design
- Características principales

### 2. Que es HTML y CSS. Para que sirven

#### HTML

- Lenguaje de Marcado de HiperTexto (Hypertext Markup Language)
- Sirve para estructurar la página web (texto, botones, secciones, etc)

#### CSS

- Hojas de estilo en cascada (Cascading Style Sheets)
- Nos permite estilizar un sitio web (color, tamaño, letra, bordes, etc)

### 3. Motores de render: de archivos a pixeles

Los navegadores tienen motores, estos motores se encargan de pasar el código de archivos a pixeles siguiente un proceso. 

Entre los navegadores tenemos: 

- Chrome y su motor *blink*
- Edge y su motor *Edge HTML*
- Safari y su motor *webkit*
- Firefox y su motor *Gecko*

Pasos del navegador para convertir a pixeles un archivo html

1. Pasar los archivos a Objetos
2. Calcular el estilo de cada nodo del DOM
3. Calcular las dimensiones y ubicación en pantalla de cada nodo
4. Pintar las diferentes cajas
5. Toma las capas y las convierte en una imagen para mostrar en pantalla

## Maquetación con HTML

### 4. Anatomía de un documento HTML y sus elementos

#### Elementos HTML

```html
<h1>
     Bienvenidos!
</h1>
```

- `<h1> Bienvenidos </h1>` es un elemento
- `<h1>` es la etiqueta de apertura
- `</h1>` es la etiqueta de cierre
- `Bienvenidos!` es el contenido del elemento **h1**.

#### Atributos HTML

```html
<h1 class='titulo'>
    Bienvenidos
</h1>
```

- `class = 'titulo'`, es un atributo de **clase**.
- `class` es el tipo de atributo
- `titulo` es el valor del atributo **class**.

#### Anidamiento HTML

```html
<section>
	<h1>
        Platzi
    </h1>
    <p>
        Tiene una comunidad
    </p>
    <ul>
        <li>Increible</li>
        <li>Maravillosa</li>
        <li>Inigualable</li>
    </ul>
</section>
```

Los elementos HTML pueden tener anidados dentro otros elementos HTML.

#### Elementos vacíos

No todos los elementos tienen etiqueta de cierre, a este tipo de elementos que no tienen contenido se le llama **elementos vacíos**.

```html
<img src='cat.jpg' alt='cat'>
<!--La etiqueta img es un elemento vacio, no tiene etiqueta de cierre-->
```

#### Anatomía de un documento HTML

```html
<!DOCTYPE html>
<html lang='en'>
    <head>
        <meta clarset='utf-8' >
        <title>My document</title>
    </head>
    <body>
        <header></header>
        <nav></nav>
        <section></section>
        <footer></footer>
    </body>
</html>
```

### 5. Que es HTML semántico

HTML semántico nos indica que debemos usar las etiquetas adecuadas para cada una de las secciones. *Las etiquetas tienen significado.*

Para que sirve el HTML semántico:

- Ayuda a un sitio web a ser accesible
- Mejora el posicionamiento SEO
- Código mas claro y fácil de leer

Por tanto a la hora de escribir código HTML se debe evitar en lo posible el uso de etiquetas `<div>` y en su lugar usar `<header>`, `<nva>`, `<section>`, `<article>`, `<img>`, `<footer>`, etc. según las secciones en la página web.

### 6. Etiquetas HTML mas usadas

#### Layout

```html
<header></header>
<nav></nav>
<section></section>
<article></article>
<aside></aside>
<footer></footer>
<main></main>
```

#### Texto

```html
<h1></h1>...<h6></h6>
<p></p>
<span></span>
```

#### Enlaces

```html
<a></a>
```

#### Imágenes y video

```html
<img>
<svg></svg>
<iframe></iframe>
<video></video>
```

#### Formularios

```html
<form></form>
<input />
<label></label>
<button></button>
```

#### Listas

```html
<ul></ul>
<li></li>
<ol></ol>
```

Referencias HTML y Documentación

[https://htmlreference.io/](https://htmlreference.io/)

## Maquetación con CSS

### 7. Anatomía de una declaración CSS: selectores, propiedades y valores

```css
h1 {
    color: pink;
}
```

- `h1` es el selector
- `color` es la propiedad
- `pink` valor de la propiedad

El selector nos indica el tipo de elemento al cual estamos dando estilos, pueden ser de etiqueta, de clase y de id principalmente.

### 8. Tipos de selectores: básicos y combinadores

#### Selectores básicos

```css
/*De Tipo*/
div {...}
p {...}

/*De Clase*/
•elemento{...}

/*De ID*/
#element-id{...}

/*De Atributo*/
a[href='atrr']{...}

/*Universal*/
*{...}
```

#### Selectores combinadores

- *Descendientes* `div p {...}`, todos los **p** dentro de **div**
- *Hijo directo* `div > p {...}`,  Solo hijos directos
- *Elemento adyacente* `div + p {...}`, uno al lado del otro
- *General de hermanos* `div ~ p {...}`, todos los después de div

#### Colores CSS nombres genericos

Algunos colores tienen nombres genéricos, sin embargo cualquier color se puede expresar en diversos sistemas: *Hex*, *RGB*, *HSL* y *RGBA*.

Aquí podemos encontrar una guía de colores para CSS.

[https://htmlcolorcodes.com/es/](https://htmlcolorcodes.com/es/)

### 9. Tipos de selectores: pseudo clases y pseudo elementos

### 10. Cascada y especificidad en CSS

### 11. Tipos de display mas usados: block, inline e inline-block

### 12. Tipos de display mas usados: flexbox y CSS Grid

### 13. Modelo de caja

### 14. Colapso de márgenes

### 15. Posicionamiento en CSS

### 16. Z-index y el contexto de apilamiento

### 17. Propiedades y valores CSS mas usados

## Diseño responsivo

### 18. Unidades de medida

### 19. Responsive Design

## Arquitectura CSS

### 20. Que son las arquitecturas CSS. Para que sirven

### 21. OOCSS, SMACSS, ITCSS y Atomic Design

## Próximos pasos

### 22. CSS para entrevistas y mundo laboral

### 23. Continúa con el curso Practico de Fronted Developer