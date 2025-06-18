# Clase 1: Interfaces de Texto (CLI)

## 👋 Bienvenido a la línea de comandos

¿Te imaginás usar la compu sin mouse? Antes de que existieran las ventanas, botones, íconos y menús gráficos, las personas interactuaban con las computadoras escribiendo comandos en una pantalla negra. A eso se le llama interfaz de línea de comandos, o CLI (Command Line Interface). Escribías lo que querías hacer y la computadora respondía. Nada de hacer doble clic o arrastrar con el mouse: todo se hacía escribiendo instrucciones específicas con el teclado.

Hoy en día estamos tan acostumbrados a lo visual que puede parecer raro o anticuado, pero la CLI sigue siendo fundamental, especialmente para quienes trabajan programando, manteniendo servidores, automatizando tareas o desarrollando software.

Pensá en la CLI como una forma directa de hablar con la computadora, sin intermediarios. No hay ventanas que nos digan qué hacer, ni botones que limiten nuestras opciones: solo vos, el teclado, y la computadora esperando que le digas exactamente qué hacer. Por eso, aunque parezca más difícil al principio, es muchísimo más poderosa y precisa que una interfaz gráfica.

En esta clase, vamos a explorar cómo funciona este tipo de interfaz, por qué sigue siendo tan poderosa hoy en día y cómo se diferencia de las interfaces gráficas (GUI). También vas a aprender comandos básicos que te servirán tanto en Windows como en Linux, especialmente si algún día trabajás con servidores o desarrollo.
---

📌 ¿Qué es la CLI y por qué importa?

La CLI (Command Line Interface), o interfaz de línea de comandos, es un entorno en el que el usuario se comunica con la computadora escribiendo instrucciones de texto. En lugar de hacer clic con el mouse en íconos, botones o menús como en una interfaz gráfica (GUI), acá se escribe directamente lo que se quiere que la computadora haga.

Por ejemplo, si en una GUI hacés clic en una carpeta para abrirla, en la CLI escribirías un comando como cd carpeta para entrar en ella.
## 🧠 ¿Por qué es tan importante?

Aunque a simple vista pueda parecer más difícil, la CLI tiene varias ventajas fundamentales:

    Es rápida y precisa: Un usuario que domina la CLI puede ejecutar tareas en segundos que en una GUI requerirían varios clics y ventanas abiertas.

    Permite automatizar tareas: Se pueden escribir scripts (series de comandos) para repetir procesos automáticamente, lo cual es ideal para programadores o administradores de sistemas.

    Es liviana y no consume recursos: A diferencia de una interfaz gráfica que requiere más memoria y procesamiento, la CLI funciona incluso en computadoras muy modestas.

    Da acceso a funciones avanzadas: Muchas herramientas del sistema operativo y del desarrollo profesional (como Git, Docker o servidores web) funcionan primero desde la CLI.

## 🧾 Características principales

La CLI puede parecer intimidante al principio porque no hay botones ni íconos que nos digan qué hacer. Pero justamente por eso es una herramienta tan poderosa: te da control total sobre la computadora. Veamos algunas de sus características más importantes:
### 🔤 1. Texto puro

Todo lo que ves y hacés es a través de texto. No hay ventanas, ni colores llamativos, ni imágenes. Vos escribís un comando, y la computadora responde con texto. Puede parecer básico, pero esto lo hace muy liviano y funcional incluso en equipos antiguos o servidores remotos.
###  ⚡ 2. Velocidad

Una vez que sabés los comandos, trabajar por CLI es más rápido que con el mouse. Por ejemplo, mover archivos, instalar programas o buscar información se puede hacer en segundos sin necesidad de abrir múltiples ventanas.

###  🎯 3. Precisión y control total

En la CLI, tenés acceso directo a todo lo que hace el sistema operativo. Podés crear, modificar, eliminar archivos y procesos, cambiar configuraciones y más. Esto no siempre es posible desde una GUI, que a veces te oculta funcionalidades por seguridad o simplicidad.

### 🤖 4. Automatización

Uno de los grandes poderes de la CLI es que te permite automatizar tareas. Podés escribir archivos llamados scripts (conjunto de comandos) que se ejecutan uno tras otro, lo que ahorra tiempo y evita errores humanos. Es la base para administrar servidores, desarrollar software y ejecutar tareas programadas.

###  🧱 5. Estabilidad

Como la CLI no necesita elementos gráficos, es más estable y menos propensa a fallos visuales. Esto es clave en servidores, donde el entorno gráfico suele estar desactivado para ahorrar recursos y evitar vulnerabilidades.

## 🧰 ¿Cómo se ve?

Al abrir una terminal o consola, verás una pantalla negra (o blanca) con un símbolo que espera tu comando. Eso se llama prompt, y es el lugar donde el sistema está listo para escuchar tu instrucción.

usuario@equipo:~$ 

Ese es un prompt típico en Linux. Ahí podés escribir comandos como ls, mkdir, python, etc.

### 🎯 ¿Por qué es importante hoy?

Aunque hoy usamos computadoras con interfaces visuales muy atractivas —como Windows, Android o macOS— la línea de comandos no es cosa del pasado. De hecho, sigue siendo una de las herramientas más usadas y valoradas por personas que trabajan en tecnología, y su uso está creciendo por la necesidad de eficiencia, automatización y control profundo del sistema.

Veamos por qué sigue siendo tan importante en la actualidad:

#### 💻 Desarrollo de software

Los programadores y desarrolladores usan la CLI a diario. Muchas herramientas modernas como Git (control de versiones), Node.js, Python, o compiladores de código, se manejan a través de comandos. Además, es común escribir scripts para compilar, probar, empaquetar e instalar software automáticamente.

### 🌐 Administración de servidores

Cuando administrás servidores, especialmente en la nube (como AWS, Google Cloud o servidores Linux), no tenés una interfaz gráfica. Accedés por terminal usando herramientas como ssh, y todo lo hacés desde la CLI: revisar logs, instalar programas, reiniciar servicios, configurar redes y más.

### 🐧 Sistemas operativos Linux

Linux es el sistema operativo más utilizado en servidores, supercomputadoras, y muchas computadoras de programadores. Aunque tiene entornos gráficos, su verdadera potencia está en la terminal. Desde allí se puede controlar todo el sistema con eficiencia, seguridad y velocidad.

### 🤖 Automatización de tareas

Con la CLI podés crear scripts que hacen tareas por vos. Por ejemplo: hacer backups diarios, limpiar archivos innecesarios, actualizar el sistema, enviar reportes por email, etc. Esto es vital para trabajos repetitivos o sistemas que deben operar sin intervención humana.

### 💼 Profesiones técnicas que dependen de la CLI

    Sysadmins (administradores de sistemas).

    DevOps e ingenieros de infraestructura.

    Científicos de datos y analistas.

    Pentesters y expertos en ciberseguridad.

    Programadores full-stack y backend.

---

## 🖥️ Diferencias entre CLI y GUI

| Característica       | CLI               | GUI                 |
| -------------------- | ----------------- | ------------------- |
| Facilidad de uso     | Requiere práctica | Intuitiva           |
| Velocidad            | Muy rápida        | Puede ser más lenta |
| Automatización       | Alta (scripts)    | Limitada            |
| Recursos del sistema | Bajo consumo      | Mayor consumo       |

> 📘 En el libro *En el principio era la línea de comandos*, Neal Stephenson compara la CLI con un piano, donde cada tecla tiene una función precisa, mientras que la GUI es como una máquina expendedora con opciones limitadas.

---

## 💻 Comandos básicos en Windows y Linux

Tanto Windows como Linux tienen terminales que aceptan comandos. En Windows, tenés el **CMD o PowerShell**. En Linux, se usa principalmente **Bash**.

### 🔹 En Windows (CMD o PowerShell)

| Acción           | Comando           |
| ---------------- | ----------------- |
| Ver archivos     | `dir`             |
| Cambiar carpeta  | `cd`              |
| Crear carpeta    | `mkdir nombre`    |
| Borrar archivo   | `del archivo.txt` |
| Limpiar pantalla | `cls`             |
| Ver IP           | `ipconfig`        |

### 🔸 En Linux (Bash)

| Acción           | Comando          |
| ---------------- | ---------------- |
| Ver archivos     | `ls`             |
| Cambiar carpeta  | `cd`             |
| Crear carpeta    | `mkdir nombre`   |
| Borrar archivo   | `rm archivo.txt` |
| Ver contenido    | `cat`, `less`    |
| Ver IP           | `ip a`           |
| Limpiar pantalla | `clear`          |

🎯 **Ejercicio práctico sugerido:**

1. Abrí CMD o Git Bash y probá cada uno de estos comandos.
2. Anotá qué hace cada uno.
3. Compará los nombres de comandos entre Windows y Linux.

---

# 🐧 El mundo Linux y el Bash Shell

## 🔎 ¿Por qué se usa tanto Linux en servidores?

Cuando pensamos en servidores (computadoras que no usamos como usuarios comunes, sino que dan servicios a otros dispositivos, como páginas web, bases de datos, correos, etc.), lo primero que importa es la eficiencia, la seguridad y la confiabilidad. Por eso, Linux es el sistema operativo más elegido en este campo, y acá te explicamos por qué:

### 🛡️ Es estable y seguro

Linux está diseñado para ser sólido y confiable. Puede funcionar durante meses o incluso años sin reiniciarse, lo cual es clave para un servidor que tiene que estar disponible las 24 horas, todos los días. Además, su arquitectura hace que sea menos vulnerable a virus y ataques, especialmente si se configura correctamente. Por eso es el sistema preferido para servidores en Internet.

### 🧠 No necesita interfaz gráfica

Un servidor no necesita mostrar ventanas ni gráficos bonitos. Al contrario, lo que se busca es que consuma la menor cantidad posible de recursos. Linux puede funcionar perfectamente sin entorno gráfico, manejado exclusivamente desde la terminal. Esto libera memoria y procesamiento para las tareas realmente importantes del servidor, como alojar una web o gestionar bases de datos.

### 🎮 Se puede controlar completamente desde CLI

Linux está pensado para ser manejado desde la línea de comandos. Desde allí se puede:

    Instalar o actualizar programas.

    Configurar redes y servicios (como servidores web, FTP, SSH, etc.).

    Crear usuarios, asignar permisos, revisar el estado del sistema.

    Automatizar tareas mediante scripts.

Eso lo hace ideal para trabajar a distancia, ya que podés conectarte desde cualquier parte del mundo por terminal (mediante SSH) y hacer todo sin necesidad de escritorio remoto ni interfaz gráfica.

### 🌍 Está en todas partes

Linux no es solo para servidores grandes: también corre en:

    Routers y dispositivos de red.

    Cajeros automáticos.

    Celulares Android (basados en Linux).

    Supercomputadoras.

    Sistemas embebidos (como los de autos, televisores o IoT).

En resumen: Linux es la base invisible de Internet y de muchas tecnologías que usamos todos los días. Y lo más impresionante es que, en la mayoría de los casos, todo se controla escribiendo comandos desde una CLI.

## 🧠 ¿Qué es Bash?

Bash es uno de los elementos más importantes del entorno de línea de comandos en Linux. Su nombre completo es “Bourne Again Shell”, un juego de palabras, suena como "born again shell", que significa “shell nacido de nuevo”, con el nombre del shell original de Unix: el Bourne Shell (sh). Bash es una evolución de ese shell y se ha convertido en el intérprete de comandos por defecto en la mayoría de las distribuciones de Linux.

### 📥 ¿Qué significa “intérprete de comandos”?

Un intérprete de comandos es como un traductor entre vos y el sistema operativo. Cuando escribís algo como mkdir nueva_carpeta, Bash interpreta eso y le dice al sistema: “creá una carpeta con este nombre en la ubicación actual”.

En otras palabras, Bash:

    Recibe comandos que vos escribís.

    Interpreta lo que significan.

    Ejecuta las instrucciones en nombre del usuario.

### 🧩 ¿Qué más puede hacer Bash?

Bash no solo ejecuta comandos sueltos. También puede:

    Ejecutar scripts (archivos .sh) con múltiples instrucciones.

    Usar estructuras de control como if, for, while (como un lenguaje de programación).

    Manejar variables, funciones, y argumentos.

    Redirigir la salida de un comando (>, >>, |) o combinar comandos (&&, ||).

    Leer entradas del usuario (read) y tomar decisiones.

Esto hace que Bash no sea simplemente una herramienta para dar órdenes sueltas, sino una poderosa plataforma de automatización y administración del sistema.

### 🔁 ¿Dónde lo encontrás?

Prácticamente todas las distribuciones de Linux modernas (Ubuntu, Debian, Fedora, Arch, etc.) incluyen Bash por defecto. También podés usar Bash:

    En macOS, que incluye un shell compatible.

    En Windows, a través de WSL (Windows Subsystem for Linux) o Git Bash.

    En servidores remotos, donde usualmente no hay entorno gráfico y todo se maneja desde Bash.



### 🧰 ¿Cómo se estructura un comando?

```bash
comando [opciones] [argumentos]
```

Ejemplo:

```bash
ls -la /home/usuario
```

Este comando lista en detalle (`-la`) todos los archivos de la carpeta `/home/usuario`.

### 🧾 Comandos muy usados en servidores Linux:

| Comando   | ¿Para qué sirve?                   |
| --------- | ---------------------------------- |
| `top`     | Ver procesos que están corriendo   |
| `ps aux`  | Ver todos los procesos             |
| `df -h`   | Ver espacio en disco               |
| `free -m` | Ver uso de memoria RAM             |
| `nano`    | Editor de texto simple en consola  |
| `chmod`   | Cambiar permisos de archivos       |
| `sudo`    | Ejecutar como administrador (root) |

> ⚠️ Tip: Usar `sudo` te da permisos elevados. Tené cuidado con lo que hacés.

---

## 📌 Para reflexionar al cierre

- ¿En qué casos es mejor usar CLI y en cuáles GUI?
- ¿Cuál creés que te da más control sobre la máquina?
- ¿Qué ventajas tiene la CLI si trabajás en programación o con servidores?

> 📚 Leé el inicio del libro "En el principio era la línea de comandos". Hay una comparación muy interesante entre la cultura del software y los sistemas operativos.

---

## 📝 Tarea para la próxima clase

- Investigá qué es un **script de shell** y qué puede automatizar.
- Probá más comandos por tu cuenta. Anotá para qué sirve cada uno.
- Asegurate de tener **Python instalado** o acceso a **Replit** para la siguiente clase práctica.

---

👨‍💻 **¡Buen trabajo! Recordá que la CLI no es vieja, es poderosa.** Saber usarla te abre muchas puertas como programador, desarrollador o administrador de sistemas.
