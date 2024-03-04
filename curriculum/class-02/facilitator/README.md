# Guía del Facilitador: Clase 02 - La Computadora del Programador

¡Es hora del Installfest! Este es el día de configuración de la computadora. Vale la pena tomar una sesión de clase completa solo para hacerlo bien, ya que el resto de la carrera del estudiante será trabajar con este tipo de herramientas en una computadora.

Una configuración adecuada ahora significa que los estudiantes pueden concentrarse en el contenido de todas las clases futuras, en lugar de luchar contra sus sistemas.

## Preparación

1. Asegúrate de que los estudiantes puedan acceder a las grabaciones del curso.
     - Verifica que  puedas acceder a un enlace de estos videos del curso en el programa de estudios de Canvas. Compártelo también a través de Slack.
     - Confirma que los estudiantes puedan acceder a conferencias grabadas en sus computadoras y que se les haya mostrado cómo hacerlo.
1. Revisa la [Reading Assignment](../DISCUSSION.md) y los recursos vinculados.
1. Lee la Guía de configuración de la computadora (vinculada desde el laboratorio) en tu propia computadora, para comprender los pasos y dónde las personas puedan quedarse atrapadas.
1. Si no está en Windows, instale una [Máquina virtual Win10] (https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/) para que pueda ayudar a las personas durante la instalación de Windows. Esto funciona bastante bien con VirtualBox gratuito (un administrador de VM), que se puede instalar en macOS con "brew cask install virtualbox".

## Asignaciones

*Todas las tareas deben entregarse antes de la medianoche. Dedica un par de minutos a repasar cada tarea en Canvas antes de la hora de lectura y laboratorio.*

- Read: 02 - La computadora del Programador
- Lab: 02 - La computadora del Programador
- Review: Clase 02 - Configuración de computadora

## Temas principales de la conferencia y flujo general

### Revisar diapositivas y notas del presentador

Practica el tiempo y el lenguaje para cada diapositiva en la [Slide Deck] (https://codefellows.github.io/common_curriculum/slides/template/index.html?slides=/code-102-guide/curriculum/class-02/slides /slides.md).

Revisa las notas del presentador en cada diapositiva para poder expresarlas con **tus propias palabras**.

### Horario del día

| Hora | ~Duración| Tarea |
|--- |--- |--- |
| 0:00 | 15 minutos | Review Markdown |
| 0:15 | 15 minutos | Herramientas para desarrolladores |
| 0:30 | 20 minutos | Demostración Terminal/GUI |
| 0:50 | 10 minutos | Demostración en vivo HTML en VS Code / Observaciones |
| 1:00 | 30 minutos | Read 02 La computadora del Programador |
| Descanso | | |
| 1:30 | 10 minutos | Abstracción |
| 1:40 | 80 minutos | Lab 02 ¡¡La computadora del Programador / Installfest!!|
| 3:00 | | Fin |

## Preguntas y desafíos esperados de los estudiantes

- sistemas operativos obsoletos
- máquinas usadas con configuraciones de desarrollo existentes
- Se espera que los estudiantes intenten ejecutar comandos de terminal asignados sin completar la configuración.
- considere compartir comentarios 102 anteriores sobre las lecturas. Señale que las lecturas están en las tareas de Canvas y que los estudiantes pueden revisar esas lecturas (posiblemente la noche anterior).
- `eslint` ha causado errores a algunos estudiantes en el pasado en Windows. Si esto ocurre, intente forzar una versión que funcione.
   -`instalación npm -g eslint@6.8.0`

### Errores de línea de comando

Los estudiantes no están acostumbrados a usar la terminal. Pueden surgir dificultades al distinguir entre un comando que se ejecuta correctamente y un comando que falla y muestra un mensaje de error.

### WSL

Los usuarios de Windows tienen un conjunto adicional de pasos para instalar la línea de comandos de Ubuntu. Déjalo muy claro:

1. No necesitan comprender conceptualmente todo lo que están haciendo.
2. Es importante seguir los pasos con cuidado de todos modos.

**Soluciones de errores comunes de WSL**:

- Error: `Failed to attach disk: ... The system cannot find the file specified`
- Causa: Esto puede suceder durante un intento de reinstalar Ubuntu, si ya estaba instalado anteriormente.
- Solución: ejecute estos comandos:

    - ```text
    wsl --shutdown
    wslconfig /unregister ubuntu
    wsl --install --distribution Ubuntu
    ```

## Comentarios y notas varios

- El mayor error en la configuración de WSL: lectura de instrucciones. Los estudiantes no comprenden conceptualmente, por lo tanto, es más probable que se presenten obstáculos durante el festival de instalación. Anime a los estudiantes a seguir el proceso paso a paso y hacer preguntas según sea necesario.
- Se necesitan permisos de nivel de administrador si la computadora fue utilizada por hermanos o cónyuges, pueden surgir problemas

## Vocabulario Nuevo

- CLI (Interfaz de línea de comandos): te proporciona comandos para navegar, controlar y manipular el sistema de archivos de tu computadora.
- Terminal: Es un programa de interfaz basado en texto que te permite enviar comandos a tu computadora.
- GUI (Interfaz gráfica de usuario): Es un sistema de interfaz gráfica que facilita la navegación en la computadora en un entorno amigable y fácil de usar.
- IDE - Entorno de Desarrollo Integrado. Es un programa que te ayuda con la codificación. Ofreciendo resaltado de sintaxis y  detección de errores.
- VS Code: Es un programa gratuito proporcionado por Microsoft que te ayuda en la programación.
- Abstracción - Consiste en utilizar detalles específicos para estudiar objetos o sistemas.