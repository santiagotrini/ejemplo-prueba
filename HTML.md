# Apunte sobre HTML Básico

## Estructura Básica de un Documento HTML
Un documento HTML tiene una estructura básica que incluye etiquetas necesarias para definir un documento web:

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Título de la Página</title>
</head>
<body>
    <!-- Contenido de la página -->
</body>
</html>
```

### Explicación
- `<!DOCTYPE html>`: Declara el tipo de documento y la versión de HTML (HTML5).
- `<html>`: Elemento raíz que contiene todo el contenido de la página.
- `lang="es"`: Atributo que define el idioma del documento.
- `<head>`: Contiene metadatos (información sobre el documento, no visible directamente).
- `<body>`: Contiene el contenido visible y estructurado del documento.

**Importante**: para linkear la hoja de estilos externa lo hacemos con el elemento `<link>` en el `<head>`. Generalmente escribimos `<link rel="stylesheet" href="styles.css">`.

## Etiquetas, Elementos y Atributos
### Definiciones
- **Etiqueta**: Una palabra clave entre `< >` que define un elemento, por ejemplo, `<p>`.
- **Elemento**: Incluye la etiqueta de apertura, el contenido y la etiqueta de cierre, por ejemplo:
  ```html
  <p>Este es un párrafo.</p>
  ```
- **Atributos**: Propiedades adicionales dentro de la etiqueta de apertura que configuran o describen el elemento:
  ```html
  <a href="https://example.com">Enlace</a>
  ```

## Elementos Básicos para Mostrar Texto

### Encabezados
Los encabezados se definen con etiquetas `<h1>` a `<h6>`:
```html
<h1>Título Principal</h1>
<h2>Subtítulo</h2>
<h3>Encabezado de tercer nivel</h3>
```

### Párrafos
Los párrafos se crean con la etiqueta `<p>`:
```html
<p>Este es un párrafo de texto.</p>
```

### Listas
- **Ordenadas**:
  ```html
  <ol>
      <li>Elemento 1</li>
      <li>Elemento 2</li>
  </ol>
  ```
- **No ordenadas**:
  ```html
  <ul>
      <li>Elemento A</li>
      <li>Elemento B</li>
  </ul>
  ```

### Salto de Línea
Usa `<br>` para un salto de línea:
```html
Línea 1<br>Línea 2
```

### Regla Horizontal
Usa `<hr>` para una línea horizontal:
```html
<p>Texto antes de la línea</p>
<hr>
<p>Texto después de la línea</p>
```

### Enlaces
Los enlaces se crean con la etiqueta `<a>`:
```html
<a href="https://example.com" target="_blank">Visita Example</a>
```
- `href`: Define la URL del enlace.
- `target="_blank"`: Abre el enlace en una nueva pestaña.

## Elemento `<img>`
Usa `<img>` para mostrar imágenes:
```html
<img src="imagen.jpg" alt="Descripción de la imagen" width="300">
```
- `src`: Ruta o URL de la imagen.
- `alt`: Texto alternativo (importante para accesibilidad).
- `width`, `height`: Ajustan el tamaño. Pero mejor haganlo desde el CSS.

## Elementos Estructurales
### `<div>`
Contenedor genérico para estructurar contenido:
```html
<div>
    <h2>Sección</h2>
    <p>Contenido de la sección.</p>
</div>
```

### `<span>`
Contenedor en línea para estilizar texto o agrupar partes pequeñas:
```html
<p>Texto con <span style="color: red;">color rojo</span>.</p>
```

El ejemplo de arriba usa el atributo `style` en el `<span>` para definir lo que se conoce como un estilo en línea.
Los estilos en línea tienen prioridad siempre sobre las hojas de estilo externas o internas.

### `<main>`
Define el contenido principal de la página:
```html
<main>
    <h1>Título Principal</h1>
    <p>Contenido principal aquí.</p>
</main>
```

### `<footer>`
Define el pie de página:
```html
<footer>
    <p>© 2025 Mi Sitio Web</p>
</footer>
```

### Otros elementos estructurales en bloque para delimitar contenido y usarlos como contenedores

```html
<aside></aside>
<head></head>
<article></article>
<section></section>
```

## Elementos en bloque vs elementos en línea

Los elementos que por defecto tienen el valor `block` en la propiedad `display`. Como el `<div>`, el `<h1>`, el `<p>`. Son elementos que siempre ocupan su propia línea y abarcan todo el ancho disponible dentro de su contenedor.
Otros elementos tienen la propiedad `display: inline` y se suelen usar para marcar frases o palabras dentro de un texto. Ejemplos: `<span> <em> <strong> <a>`. Es importante distinguir entre estos dos tipos de elementos a la hora de acomodar las cosas en la pantalla.

## Elementos Vacíos vs Elementos con Contenido
- **Elementos Vacíos**: No tienen contenido ni etiqueta de cierre explícita (ejemplo: `<br>`, `<hr>`, `<img>`).
- **Elementos con Contenido**: Pueden contener nodos de texto o elementos anidados (ejemplo: `<div>`, `<p>`).

## Conclusión
Este apunte cubre los conceptos básicos para entender y usar HTML. Es fundamental practicar creando y estructurando documentos para dominar estos elementos.
