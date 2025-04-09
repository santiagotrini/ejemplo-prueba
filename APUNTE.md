# 🧪 Apuntes para la prueba: CLI, Git, GitHub, HTML y CSS

---

## 🖥 CLI (Command Line Interface)

| Comando             | Para qué sirve                                                      |
|---------------------|---------------------------------------------------------------------|
| `mkdir nombre`      | Crea una nueva carpeta. ("make directory")                         |
| `cd nombre`         | Entra a una carpeta. ("change directory")                          |
| `cd ..`             | Sube un nivel en la estructura de carpetas.                        |
| `ls`                | Lista los archivos y carpetas del directorio actual.               |
| `echo "texto"`      | Muestra texto en consola o crea archivos con contenido.            |

---

## 🧠 Git

| Comando                          | Explicación                                                                 |
|----------------------------------|-----------------------------------------------------------------------------|
| `git init`                       | Inicializa un nuevo repositorio local.                                     |
| `git add archivo`               | Agrega un archivo al área de staging.                                      |
| `git commit -m "mensaje"`        | Guarda los cambios localmente con un mensaje.                              |
| `git config`                     | Configura opciones de Git (usuario, email, etc.).                          |
| `git remote add origin URL`      | Conecta el repo local con uno remoto (GitHub).                             |
| `git push origin main`           | Sube los commits al repositorio remoto.                                    |
| `git pull`                       | Trae los cambios desde el repo remoto al local.                            |

---

## 🌐 GitHub

| Tema                               | Explicación                                                                 |
|------------------------------------|------------------------------------------------------------------------------|
| Crear nuevo repo                   | Botón "New repository" en GitHub, completás datos y lo creás.              |
| PATs (Personal Access Tokens)      | Token que reemplaza contraseña para autenticar en GitHub desde la terminal.|
| Pushear repo desde terminal        | `git init` → `git remote add` → `git add .` → `git commit` → `git push`.  |
| GitHub Pages                       | En Settings del repo, activás Pages con la rama main y carpeta `/root`.   |

---

## 🕸 HTML

### 1. Elementos y atributos

- **Elementos**: Etiquetas como `<p>`, `<a>`, `<img>`.
- **Atributos**: Propiedades dentro de las etiquetas (`src`, `href`, `alt`, `class`, `id`).

### 2. Texto

- `<h1>` a `<h6>`: Encabezados (más grande a más chico).
- `<p>`: Párrafo.
- `<ul>`: Lista desordenada.
- `<li>`: Elemento de lista.
- `<a href="">`: Enlace.

### 3. Estructura

- **Bloque**: Ocupa todo el ancho. Ej: `div`, `p`, `h1`.
- **En línea**: Ocupa solo el ancho necesario. Ej: `span`, `a`, `img`.
- **Elementos vacíos**: No tienen contenido interno (ej: `<img>`, `<br>`).

### 4. Estructura semántica

- `<div>`: Contenedor genérico.
- `<span>`: Contenedor en línea.
- `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`: Contenedores semánticos.

### 5. Head y recursos

- `<title>`: Título del sitio en la pestaña.
- `<link rel="stylesheet" href="estilo.css">`: Conecta un CSS externo.

### 6. Imagenes

```html
<img src="ruta.jpg" alt="Descripción">