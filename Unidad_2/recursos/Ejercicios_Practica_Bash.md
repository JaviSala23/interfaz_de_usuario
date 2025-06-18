
# 🧪 Práctica con Scripts Bash (.sh)

Este documento incluye una serie de ejercicios prácticos para aprender a crear, modificar y ejecutar scripts Bash. Ideal para estudiantes que comienzan a automatizar tareas en sistemas Linux.

---

## ✅ Nivel 1: Básico

### 📄 Ejercicio 1: Tu primer script
1. Crear un archivo llamado `mi_nombre.sh`.
2. El script debe imprimir tu nombre, apellido y curso actual.
3. Agregar una línea que muestre la fecha y hora actual.

```bash
#!/bin/bash
# Tu script debería incluir: echo "Tu nombre", date, etc.
```

---

### 📄 Ejercicio 2: Operaciones con variables
1. Crear un script llamado `operaciones.sh`.
2. Definir dos variables con números enteros.
3. Mostrar la suma, resta, multiplicación y división de ambas.

```bash
#!/bin/bash
# Usar: let, echo o expresiones aritméticas $((...))
```

---

### 📄 Ejercicio 3: Comprobar archivos
1. Crear un script `verificar_archivo.sh`.
2. Pedir al usuario que ingrese un nombre de archivo.
3. Verificar si ese archivo existe en el sistema.
4. Mostrar un mensaje según el resultado.

```bash
#!/bin/bash
# Usar: read, if [ -f "$archivo" ]; then ...
```

---

## 🔁 Nivel 2: Condicionales y bucles

### 📄 Ejercicio 4: Comparar cadenas
1. Crear un script llamado `comparar.sh`.
2. Pedir dos palabras al usuario.
3. Compararlas e indicar si son iguales o distintas.

---

### 📄 Ejercicio 5: Bucle for
1. Crear un script llamado `conteo.sh`.
2. Usar un bucle `for` para contar del 1 al 10.
3. Mostrar cada número junto con la frase “Contando…”

---

### 📄 Ejercicio 6: Bucle while
1. Crear `contador.sh`.
2. El script debe contar del 1 al 5 usando `while`.
3. Esperar 1 segundo entre cada número (usar `sleep`).

---

## 📦 Nivel 3: Gestión de archivos y carpetas

### 📄 Ejercicio 7: Backup sencillo
1. Crear `backup.sh`.
2. El script debe verificar si existe una carpeta `backup`, y si no, crearla.
3. Copiar todos los archivos `.txt` del directorio actual a `backup/`.

---

### 📄 Ejercicio 8: Búsqueda de archivos
1. Crear `buscar.sh`.
2. Pedir al usuario que escriba una palabra clave.
3. Buscar archivos que la contengan en su nombre (usar `find`).

---

### 📄 Ejercicio 9: Automatización de limpieza
1. Crear `limpiar_temp.sh`.
2. Eliminar todos los archivos con extensión `.log` del directorio actual.
3. Mostrar cuántos archivos se eliminaron.

---

## 🧠 Nivel extra: Bonus avanzado

### 📄 Ejercicio 10: Menú interactivo
1. Crear `menu.sh`.
2. El script debe mostrar un menú con 3 opciones: ver fecha, listar archivos, salir.
3. Ejecutar la opción seleccionada con un `case`.

---

👨‍💻 **Consejo:** Ejecutá tus scripts con `./nombre.sh` y asegurate de haber usado `chmod +x`.

