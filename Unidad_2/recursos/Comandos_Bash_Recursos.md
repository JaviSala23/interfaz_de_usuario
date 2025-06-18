
# 📁 Recurso: Comandos esenciales de Bash (Linux Shell)

Este documento incluye una recopilación completa de comandos y herramientas esenciales que se utilizan en la terminal Bash de Linux. Está pensado como referencia rápida para estudiantes y profesionales que comienzan a trabajar con CLI.

---

## 📂 Navegación entre directorios

| Comando               | Descripción                                      |
|------------------------|--------------------------------------------------|
| `pwd`                 | Muestra el directorio actual                     |
| `ls`                  | Lista los archivos y carpetas                    |
| `ls -l`               | Lista con detalles                               |
| `ls -a`               | Incluye archivos ocultos                         |
| `cd nombre/`          | Entra a una carpeta                              |
| `cd ..`               | Sube un nivel                                    |
| `cd /ruta/absoluta`   | Va a una ruta específica                         |
| `tree`                | Muestra la estructura de carpetas en forma de árbol |

---

## 📄 Manejo de archivos y carpetas

| Comando                     | Descripción                                  |
|-----------------------------|----------------------------------------------|
| `touch archivo.txt`         | Crea un archivo vacío                        |
| `mkdir nueva_carpeta`       | Crea una nueva carpeta                       |
| `cp archivo1 archivo2`      | Copia archivos                               |
| `cp -r carpeta1 carpeta2`   | Copia carpetas recursivamente                |
| `mv archivo nuevo_nombre`   | Mueve o renombra archivos o carpetas         |
| `rm archivo.txt`            | Borra un archivo                             |
| `rm -r carpeta/`            | Borra una carpeta y su contenido             |
| `cat archivo`               | Muestra el contenido                         |
| `less archivo`              | Muestra el contenido paginado                |
| `file archivo`              | Muestra el tipo de archivo                   |

---

## 🧮 Gestión de procesos y sistema

| Comando         | Descripción                                      |
|------------------|--------------------------------------------------|
| `top`           | Muestra procesos en tiempo real                  |
| `htop`          | Versión mejorada de `top`                        |
| `ps aux`        | Lista todos los procesos                         |
| `kill PID`      | Termina un proceso por ID                        |
| `killall nombre`| Termina procesos por nombre                      |
| `uptime`        | Tiempo que lleva encendida la máquina            |
| `who`           | Quién está conectado                            |
| `id`            | Muestra info del usuario                         |

---

## 💾 Disco y almacenamiento

| Comando      | Descripción                                          |
|---------------|------------------------------------------------------|
| `df -h`      | Uso del disco en formato legible                     |
| `du -sh *`   | Tamaño de carpetas y archivos                        |
| `mount`      | Muestra particiones montadas                         |
| `lsblk`      | Lista dispositivos de bloques                        |
| `blkid`      | Muestra UUIDs y tipos de particiones                 |

---

## 🌐 Red

| Comando       | Descripción                                      |
|----------------|--------------------------------------------------|
| `ip a`        | Muestra configuración de red                     |
| `ping dominio`| Verifica conectividad                            |
| `curl`        | Descarga contenido desde internet                |
| `wget`        | Otra herramienta para descargar                  |
| `netstat -tuln`| Puertos abiertos                                |
| `ss -tulwn`   | Sockets y conexiones activas                     |

---

## 🔒 Permisos y usuarios

| Comando               | Descripción                                |
|------------------------|--------------------------------------------|
| `chmod 755 archivo`   | Cambia permisos                            |
| `chown usuario archivo`| Cambia el propietario                     |
| `adduser nombre`      | Crea nuevo usuario                         |
| `passwd`              | Cambia contraseña                          |
| `sudo comando`        | Ejecuta como administrador                 |

---

## 📦 Paquetes y actualizaciones (Debian/Ubuntu)

| Comando                   | Descripción                            |
|----------------------------|----------------------------------------|
| `sudo apt update`         | Actualiza la lista de paquetes         |
| `sudo apt upgrade`        | Instala actualizaciones disponibles    |
| `sudo apt install nombre` | Instala un paquete                     |
| `sudo apt remove nombre`  | Elimina un paquete                     |

---

## 📁 Compresión y archivado

| Comando                          | Descripción                      |
|----------------------------------|----------------------------------|
| `tar -czf archivo.tar.gz carpeta/`| Comprime una carpeta en .tar.gz |
| `tar -xzf archivo.tar.gz`       | Extrae archivos .tar.gz          |
| `zip archivo.zip archivo1 archivo2`| Comprime en ZIP               |
| `unzip archivo.zip`             | Descomprime ZIP                  |

---

## 🧰 Otros útiles

| Comando             | Descripción                          |
|----------------------|--------------------------------------|
| `history`           | Muestra comandos ejecutados          |
| `alias`             | Define un alias                      |
| `date`              | Muestra la fecha                     |
| `cal`               | Muestra calendario                   |
| `clear`             | Limpia la pantalla                   |

---

📘 **Tip:** Usá `man comando` (por ejemplo `man ls`) para ver el manual de cada comando.
