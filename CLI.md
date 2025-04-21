# Resumen: Comandos Básicos de la CLI de Linux

## 1. **mkdir**

### Uso:
```bash
mkdir [opciones] nombre_directorio
```

### Descripción:
Crea un directorio nuevo.

### Ejemplo:
```bash
mkdir carpeta
```

### Opciones comunes:
- `-p`: Crea directorios padre si no existen.
  ```bash
  mkdir -p padre/hijo
  ```

---

## 2. **touch**

### Uso:
```bash
touch archivo
```

### Descripción:
Crea un archivo vacío o actualiza la fecha de modificación si el archivo ya existe.

### Ejemplo:
```bash
touch archivo.txt
```

---

## 3. **cd**

### Uso:
```bash
cd [directorio]
```

### Descripción:
Cambia el directorio actual.

### Ejemplos:
- Ir a un directorio específico:
  ```bash
  cd carpeta
  ```
- Volver al directorio anterior:
  ```bash
  cd ..
  ```
- Ir al directorio raíz:
  ```bash
  cd /
  ```

---

## 4. **ls**

### Uso:
```bash
ls [opciones]
```

### Descripción:
Lista los archivos y directorios.

### Ejemplos:
```bash
ls
ls -l  # Listado detallado
ls -a  # Incluye archivos ocultos
```

### Opciones comunes:
- `-l`: Muestra detalles de los archivos.
- `-a`: Incluye archivos ocultos.
- `-h`: Tamaño de archivo legible para humanos (usado con `-l`).

---

## 5. **pwd**

### Uso:
```bash
pwd
```

### Descripción:
Muestra el directorio actual.

### Ejemplo:
```bash
pwd
```
Resultado: `/home/usuario/carpeta`

---

## 6. **echo**

### Uso:
```bash
echo [texto]
```

### Descripción:
Muestra un texto en la terminal o lo escribe en un archivo.

### Ejemplos:
- Mostrar texto:
  ```bash
  echo "Hola, mundo"
  ```
- Escribir texto en un archivo:
  ```bash
  echo "Contenido del archivo" > archivo.txt
  ```

---

## 7. **cat**

### Uso:
```bash
cat [archivo]
```

### Descripción:
Muestra el contenido de un archivo de texto.

### Ejemplo:
```bash
cat archivo.txt
```

---

### Consejos Generales
- Usa `man [comando]` para obtener más información sobre cualquier comando.
  ```bash
  man mkdir
  ```
- Practica en un entorno de prueba para familiarizarte con los comandos.
