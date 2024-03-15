# Guía del Facilitador: Clase 04 - Estructurar páginas web con HTML

Utiliza etiquetas HTML semánticas para el éxito!

En lugar de dar una conferencia sobre HTML, te diremos lo que sabemos. Utiliza este tiempo de discusión para resaltar POR QUÉ, QUÉ y CÓMO. En cuanto al CÓMO, concéntrate específicamente en la anatomía de un elemento (etiquetas de apertura, cierre, atributos, contenido), algunas etiquetas comunes (o cualquier cosa que podamos informarte) y enfatiza que HTML se trata de estructurar páginas con etiquetas semánticas.

La demostración generará una wireframe para un proyecto arbitrario y luego codificarás la estructura básica.

Durante la demostración en clase, deberías dividir la pantalla entre VSCode y Chrome para mostrar la extensión VSCode Live Server. Luego, podras ver cómo HTML llena el navegador durante la demostración en vivo.

- Nota: si no está familiarizado con la extensión VSCode:
   - [Servidor VScode Live](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
   - Potencialmente menos confuso para tí que el paquete de servidor en vivo instalado globalmente y usado comúnmente en 201/301
   - Te guiaré para que instales la extensión si aún no lo has hecho a través de VS Code.

## Preparación

1. Revisa la discusión de lectura, la demostración y la tarea de laboratorio.
1. Es hora de ejecutar el código de VS Code en tu navegador. Instala la extensión del servidor en vivo e indica a los estudiantes que hagan lo mismo:
     - <https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer>

## Asignaciones

*Todas las tareas deben entregarse antes de la medianoche. Dedica un par de minutos a repasar cada tarea en Canvas antes de la hora de lectura y laboratorio.*

- Lab 04: Estructurar Páginas Web con HTML
- Read 04: Estructurar Páginas Web con HTML
- Test 04: Estructurar Páginas Web con HTML

## Temas principales de la conferencia y flujo general

### Revisar diapositivas y notas del presentador

Practica el tiempo y el lenguaje para cada diapositiva en la [Plataforma de diapositivas] (https://codefellows.github.io/common_curriculum/slides/template/index.html?slides=/code-102-guide/curriculum/class-04/slides /slides.md).

Revisa las notas del presentador en cada diapositiva para poder expresarlas con **tus propias palabras**.

### Horario del día

| Hora | ~Duración| Tarea |
|--- |--- |--- |
| 0:00 | 15 minutos | Review clonación/gitflow |
| 0:15 | 15 minutos | Resumen HTML: ¿qué sabes? |
| 0:30 | 45 minutos | Read 04: Estructurar Páginas Web con HTML |
| 1:15 | 30 minutos | Demostración en vivo: de la maqueta al marcado |
| Descanso | | |
| 1:45 | 75 minutos | Lab 04: wireframe y construcción con socios|
| 3:00 | | Fin |

## Preguntas y desafíos esperados de los estudiantes

Algunos estudiantes confundirán qué etiquetas van y dónde (por ejemplo, `nav` para enlaces).

## Comentarios y notas varios

- Utiliza la pantalla dividida con VSCode y Chrome para mostrar la extensión VSCode Live Server
- utiliza el mismo wireframe HTML para la siguiente clase
- útiles inclusiones en tu wireframe:
   - Encabezado
     - h1
     - nav > ul > li*4
   - main
     - Sectión > article*3 > figure > img
     - inserte figcaption como primer o último hijo de la figura (¡accesibilidad FTW!)
   - footer
     - `&copy;` - inserción de símbolo
     - sitemap - nav > ul > li*4
- *tenga en cuenta las oportunidades de CSS en la clase-05*: usando estas inclusiones de wireframe

## Vocabulario Nuevo

- HTML / Marcado - El lenguaje de marcado de hipertexto es un conjunto de símbolos insertados en un archivo para mostrarlo en Internet. El marcado le dice a los navegadores web cómo mostrar palabras e imágenes.
- Semántica: describe claramente un significado. HTML semántico se refiere a etiquetas que describen claramente su significado tanto para el navegador como para el desarrollador.
- Wireframe: Se utiliza para el diseño y la estructura de una página web.
- Personas - Representación ficticia, específica y concreta de un usuario objetivo.
- Meta: describe y proporciona información sobre algo.
- Content: Hace referencia a las palabras, videos e imágenes de un sitio web.
- Element: Es todo lo que hay en una página, desde cada campo, enlace, imagen, prueba y muchas otras cosas.
- Tag: Es un comando que define cómo su navegador web formatea y muestra el contenido.
- Attribute: Es un cambio o modificador de una etiqueta que cambia el comportamiento predeterminado
- Estructura vs Presentación
   - Estructura: este es el diseño HTML que proporciona el contenido de tu página web.
   - Presentación: este es el estilo que le das a tu página con CSS.
