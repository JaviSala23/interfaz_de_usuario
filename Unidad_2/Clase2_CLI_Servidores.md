
# Clase 2 – Módulo 2: CLI en acción sobre servidores Linux

**Duración estimada:** 120 minutos  
**Unidad:** 2 - Tipos de Interfaces de Usuario  
**Clase:** 2 (CLI aplicada en servidores reales)

---

## 🎯 Objetivos de la clase
- Aplicar conocimientos previos de CLI en un entorno real de servidor Linux.
- Conectarse a un servidor remoto por terminal (SSH).
- Ejecutar comandos de administración básica.
- Crear y ejecutar scripts `.sh` en el servidor.
- Comprender el rol de Bash como interfaz principal de trabajo remoto.

---

## ⚙️ Parte 1: Conexión al servidor (20 minutos)

### ¿Qué necesitás?
- Acceso a un servidor remoto (IP, usuario y contraseña o clave SSH).
- Terminal instalada (Linux o Git Bash en Windows).

### Conexión por SSH
```bash
ssh usuario@IP_del_servidor
```

### Actividad guiada:
1. Conectarse al servidor.
2. Confirmar con `whoami` que estás dentro.
3. Navegar con `pwd`, `ls`, `cd`.

---

## 🛠️ Parte 2: Administración básica del servidor (30 minutos)

### Comandos prácticos
```bash
uptime          # Tiempo encendido
free -m         # Memoria RAM
df -h           # Espacio en disco
ps aux          # Procesos activos
htop            # Monitor de procesos (si está instalado)
```

### Actividad práctica:
- Identificar cuánta memoria libre hay.
- Saber cuánto espacio en disco queda.
- Ver los procesos más intensivos.

> 🧠 Pregunta al grupo: ¿Por qué no hay entorno gráfico en este servidor?

---

## 📂 Parte 3: Manipular archivos y carpetas (20 minutos)

### Comandos a usar:
```bash
mkdir proyectos
cd proyectos
touch nota.txt
echo "Hola desde el servidor" > nota.txt
cat nota.txt
```

### Actividad práctica:
- Crear una carpeta con tu nombre.
- Crear un archivo `.txt` con contenido personalizado.
- Verificar su existencia y contenido.

---

## 📝 Parte 4: Crear un script Bash y ejecutarlo (30 minutos)

### Crear `info.sh`
```bash
#!/bin/bash
echo "Usuario actual: $(whoami)"
echo "Fecha: $(date)"
echo "Memoria disponible:"
free -m
```

### Instrucciones:
1. Crear el archivo: `nano info.sh`
2. Pegar el código.
3. Guardar y salir (Ctrl + O, Enter, Ctrl + X).
4. Dar permisos: `chmod +x info.sh`
5. Ejecutar: `./info.sh`

### Actividad guiada:
- Explicar cada línea del script.
- Modificar para que guarde la salida en un archivo `log.txt`.

---

## 🧠 Parte 5: Reflexión y discusión final (20 minutos)

- ¿Cómo se siente trabajar sin entorno gráfico?
- ¿Qué ventajas tiene usar CLI en servidores?
- ¿Qué aprendiste hoy que no conocías antes?

---

## 📝 Tarea para la próxima clase
- Escribir un script llamado `monitor.sh` que muestre:
  - Fecha y hora.
  - Nombre del host.
  - Uso de CPU (`top -b -n1 | head -n 5`).
  - Espacio libre en `/`.

> El script debe guardar toda la salida en `monitor.log` cada vez que se ejecute.

---

👨‍💻 **Recordá:** El servidor no tiene ventanas ni íconos, pero desde la terminal se puede hacer TODO. Saber manejarlo es una habilidad clave en el mundo real.
