# Visualizador Interactivo de Arreglos (Arrays)

Este programa es un visualizador interactivo de arreglos (arrays), diseñado como un recurso didáctico para la materia de Estructuras de Datos.

## Información del Desarrollo

*   **Desarrollador:** MTI. José Arturo Bustamante Lazcano
*   **Institución:** Instituto Tecnológico Superior de San Andrés Tuxtla (ITSSNA)
*   **Materia:** Estructuras de Datos
*   **Unidad:** 3: Estructuras Lineales
*   **Semestre:** Agosto - Diciembre 2025

## Objetivo

El principal objetivo de esta herramienta es facilitar la comprensión visual y práctica de las operaciones fundamentales que se pueden realizar con arreglos, una de las estructuras de datos lineales más básicas y esenciales en programación. Permite a los estudiantes observar en tiempo real cómo los datos son manipulados dentro de un arreglo, mejorando la asimilación de conceptos abstractos.

## Herramientas Utilizadas

El visualizador está construido con tecnologías web estándar, lo que lo hace accesible y fácil de ejecutar en cualquier navegador moderno:

*   **HTML5:** Utilizado para estructurar el contenido y los elementos de la página web.
*   **CSS3 (con Tailwind CSS):** Empleado para el diseño y la estilización de la interfaz de usuario, proporcionando un aspecto moderno, responsivo y limpio.
*   **JavaScript:** La lógica interactiva del visualizador, la manipulación del arreglo en memoria y la actualización dinámica de la interfaz de usuario se gestionan completamente con JavaScript.

## ¿Cómo se usa?

La interfaz del visualizador es intuitiva y permite a los usuarios interactuar con un arreglo de las siguientes maneras:

1.  **Agregar Elementos:**
    *   **`.push(val)`:** Añade un nuevo valor al final del arreglo.
    *   **`.unshift(val)`:** Inserta un valor al principio del arreglo, desplazando todos los elementos existentes hacia la derecha para hacer espacio.

2.  **Eliminar Elementos:**
    *   **`.pop()`:** Remueve y devuelve el último elemento del arreglo.
    *   **`.shift()`:** Elimina y devuelve el primer elemento del arreglo, desplazando todos los elementos restantes hacia la izquierda.

3.  **Acceder a Elementos:**
    *   **`Acceder: [i]`:** Permite buscar y resaltar visualmente un elemento específico del arreglo utilizando su índice numérico.

4.  **Limpiar Arreglo:**
    *   Esta función reinicia el arreglo, eliminando todos sus elementos y dejándolo vacío.

Cada operación realizada se refleja visualmente en el contenedor del arreglo y se registra en una consola de ejecución. Esta consola muestra el código JavaScript equivalente a la operación realizada y una breve explicación de lo sucedido, lo que ayuda a reforzar el aprendizaje y la comprensión de la sintaxis y el comportamiento de los métodos de arreglo.
