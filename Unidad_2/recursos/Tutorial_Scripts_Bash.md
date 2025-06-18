
# 📘 Introducción a scripts Bash (.sh)

Los **scripts en Bash** permiten automatizar tareas en sistemas Linux o Unix. Son archivos de texto con extensión `.sh` que contienen una serie de comandos que la terminal puede ejecutar uno tras otro.

---

## 🧠 ¿Qué es un script?

Un **script** es como una receta de cocina: contiene pasos (comandos) escritos en un archivo, que luego se ejecutan en orden. En lugar de escribir cada comando manualmente en la terminal, podés escribirlos una vez en un archivo `.sh` y luego ejecutarlos cuando quieras.

---

## 📄 Crear tu primer script

### 1. Crear el archivo

Usá un editor como `nano`, `vim` o cualquier editor de texto:

```bash
nano hola.sh
```

### 2. Escribir el contenido

```bash
#!/bin/bash
echo "Hola, este es mi primer script"
date
```

La primera línea (`#!/bin/bash`) se llama **shebang** e indica que el script debe ejecutarse usando Bash.

### 3. Dar permisos de ejecución

```bash
chmod +x hola.sh
```

### 4. Ejecutar el script

```bash
./hola.sh
```

---

## 🛠️ Estructura básica de un script

```bash
#!/bin/bash

# Comentario
echo "Inicio del script"

# Variables
nombre="Juan"
echo "Hola $nombre"

# Condicional
if [ "$nombre" = "Juan" ]; then
  echo "Tu nombre es Juan"
fi

# Bucle
for i in 1 2 3
do
  echo "Iteración $i"
done
```

---

## 📦 Buenas prácticas

- Usá `#!/bin/bash` al inicio.
- Comentá tu código usando `#`.
- Probá cada script en un entorno seguro antes de ejecutarlo en producción.
- Usá nombres claros para tus archivos y variables.

---

## 📚 Recursos adicionales

- `man bash`: manual completo de Bash.
- [https://explainshell.com](https://explainshell.com): explicador interactivo de comandos.
- Curso oficial GNU Bash scripting: [https://www.gnu.org/software/bash/manual/](https://www.gnu.org/software/bash/manual/)

---

🎯 **Ejercicio propuesto:**  
Escribí un script llamado `sistema.sh` que:
1. Muestre tu nombre.
2. Muestre la fecha actual.
3. Verifique si existe una carpeta llamada `backup` y, si no existe, la cree.
4. Liste el contenido de la carpeta actual.

