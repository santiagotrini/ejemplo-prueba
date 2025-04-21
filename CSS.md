# Apunte sobre Propiedades de CSS

## Propiedades Generales de CSS

### `width` y `height`
Definen el ancho y alto de un elemento.
```css
.box {
    width: 200px;
    height: 100px;
}
```

### `margin`
Define el espacio externo alrededor de un elemento.
```css
.box {
    margin: 10px; /* Espaciado uniforme */
    margin: 10px 20px; /* Vertical | Horizontal */
}
```

### `padding`
Define el espacio interno entre el contenido y el borde del elemento.
```css
.box {
    padding: 15px;
    padding: 10px 20px; /* Vertical | Horizontal */
}
```

### `border`
Define el borde de un elemento.
```css
.box {
    border: 2px solid black;
}
```

### `border-radius`
Redondea las esquinas de un elemento.
```css
.box {
    border-radius: 10px; /* Radio uniforme */
    border-radius: 10px 0 0 10px; /* Esquinas individualizadas */
}
```

### `color`
Establece el color del texto.
```css
.text {
    color: #ff5733;
}
```

### `background-color`
Define el color de fondo de un elemento.
```css
.box {
    background-color: lightblue;
}
```

### `font-family`
Especifica la fuente del texto.
```css
.text {
    font-family: 'Arial', sans-serif;
}
```

### `font-size`
Establece el tamaño del texto.
```css
.text {
    font-size: 16px;
}
```

### `font-weight`
Controla el grosor de la fuente.
```css
.text {
    font-weight: bold; /* o un valor numérico como 400, 700 */
}
```

### `text-align`
Alinea el texto dentro de su contenedor.
```css
.text {
    text-align: center; /* Valores: left, right, center, justify */
}
```

### `text-decoration`
Aplica decoraciones al texto.
```css
.text {
    text-decoration: underline; /* Valores: none, overline, line-through */
}
```

### `list-style`
Configura el estilo de listas.
```css
.list {
    list-style: square; /* Cambia el marcador */
    list-style: none; /* Quita los marcadores */
}
```

## Propiedades de Flexbox

### `display`
Establece el contenedor como un elemento Flexbox.
```css
.container {
    display: flex;
}
```

### `flex-direction`
Determina la dirección de los elementos.
```css
.container {
    flex-direction: row; /* Valores: row, row-reverse, column, column-reverse */
}
```

### `flex-wrap`
Controla si los elementos deben ajustarse al contenedor.
```css
.container {
    flex-wrap: wrap; /* Valores: nowrap, wrap, wrap-reverse */
}
```

### `flex-flow`
Combina `flex-direction` y `flex-wrap`.
```css
.container {
    flex-flow: row wrap;
}
```

### `justify-content`
Alinea los elementos horizontalmente.
```css
.container {
    justify-content: space-between; /* Otros valores: flex-start, flex-end, center, space-around, space-evenly */
}
```

### `align-items`
Alinea los elementos verticalmente.
```css
.container {
    align-items: center; /* Otros valores: flex-start, flex-end, stretch, baseline */
}
```

### `gap`
Establece el espacio entre los elementos hijos.
```css
.container {
    gap: 10px;
}
```

## Conclusión
Este apunte cubre las propiedades más comunes de CSS y su aplicación práctica, incluyendo una sección dedicada a Flexbox. Practicar con estas propiedades ayudará a entender cómo controlar el diseño y estilo de los elementos en una página web.
