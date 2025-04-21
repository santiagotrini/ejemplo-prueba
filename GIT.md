# Resumen: Comandos Básicos de Git

## 1. **git init**

### Uso:
```bash
git init
```

### Descripción:
Inicializa un nuevo repositorio Git en el directorio actual.

### Ejemplo:
```bash
git init
```
Resultado: Se crea una carpeta `.git` en el directorio.

---

## 2. **git add**

### Uso:
```bash
git add [archivo | directorio]
```

### Descripción:
Añade archivos o cambios al área de preparación (staging area).

### Ejemplos:
- Añadir un archivo específico:
  ```bash
  git add archivo.txt
  ```
- Añadir todos los archivos:
  ```bash
  git add .
  ```

---

## 3. **git commit**

### Uso:
```bash
git commit -m "mensaje"
```

### Descripción:
Guarda los cambios del área de preparación en el historial del repositorio.

### Ejemplo:
```bash
git commit -m "Inicializando el proyecto"
```

### Opciones comunes:
- `-a`: Salta el paso de `git add` y añade automáticamente los archivos modificados.
  ```bash
  git commit -am "Mensaje"
  ```

---

## 4. **git config**

### Uso:
```bash
git config [opciones]
```

### Descripción:
Configura opciones de Git, como el nombre de usuario y el correo electrónico.

### Ejemplos:
- Configurar el nombre del usuario:
  ```bash
  git config --global user.name "Tu Nombre"
  ```
- Configurar el correo electrónico:
  ```bash
  git config --global user.email "tuemail@ejemplo.com"
  ```

### Opciones comunes:
- `--global`: Aplica la configuración a nivel global (para todos los repositorios).

---

## 5. **git remote**

### Uso:
```bash
git remote [opciones]
```

### Descripción:
Gestiona las conexiones a repositorios remotos.

### Ejemplos:
- Añadir un repositorio remoto:
  ```bash
  git remote add origin https://github.com/usuario/repositorio.git
  ```
- Ver repositorios remotos:
  ```bash
  git remote -v
  ```

---

## 6. **git push**

### Uso:
```bash
git push [remoto] [rama]
```

### Descripción:
Envía los cambios locales al repositorio remoto.

### Ejemplo:
```bash
git push origin main
```

---

## 7. **git pull**

### Uso:
```bash
git pull [remoto] [rama]
```

### Descripción:
Actualiza el repositorio local con los cambios del remoto.

### Ejemplo:
```bash
git pull origin main
```

---

### Consejos Generales
- Usa `git status` para ver el estado actual del repositorio.
- Usa `git log` para ver el historial de commits.
- Combina estos comandos para un flujo de trabajo eficiente: `add` → `commit` → `push`.


### Más información (libro de Git)


- [1.3](https://git-scm.com/book/es/v2/Inicio---Sobre-el-Control-de-Versiones-Fundamentos-de-Git)
- [1.6](https://git-scm.com/book/es/v2/Inicio---Sobre-el-Control-de-Versiones-Configurando-Git-por-primera-vez)
- [2.2](https://git-scm.com/book/es/v2/Fundamentos-de-Git-Guardando-cambios-en-el-Repositorio)
- [2.5](https://git-scm.com/book/es/v2/Fundamentos-de-Git-Trabajar-con-Remotos)
