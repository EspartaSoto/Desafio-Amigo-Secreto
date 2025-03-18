# Desafio-Amigo-Secreto
# Amigo Secreto - Estilo Arcade Neón

Este proyecto es una aplicación web de "Amigo Secreto" desarrollada como parte de un desafío de programación. Se ha modificado el código original para implementar la lógica del juego y aplicar una estética de estilo arcade con colores neón.

## Funcionalidades

La aplicación permite a los usuarios:

* **Agregar nombres:** Los usuarios pueden ingresar nombres de amigos en un campo de texto y agregarlos a una lista visible.
* **Validar entrada:** Se valida que el campo de texto no esté vacío antes de agregar un nombre.
* **Visualizar la lista:** Los nombres ingresados se muestran en una lista en la página.
* **Sorteo aleatorio:** Al hacer clic en el botón "Sortear Amigo", se selecciona aleatoriamente un nombre de la lista y se muestra en la página.
* **Estilo Arcade Neón:** Se ha aplicado una paleta de colores neón, tipografía de estilo arcade y efectos de resplandor para una apariencia retro y vibrante.

## Modificaciones al Código Original

Las principales modificaciones realizadas al código original son:

* **Lógica de la aplicación (app.js):**
    * Se implementó la función `agregarAmigo()` para capturar y validar los nombres ingresados, y agregarlos a un array.
    * Se creó la función `actualizarListaAmigos()` para mostrar los nombres en una lista HTML dinámica.
    * Se desarrolló la función `sortearAmigo()` para seleccionar un nombre aleatorio del array y mostrar el resultado.
* **Estilo y diseño (style.css):**
    * Se aplicó una paleta de colores neón (#121212, #FF4081, #00FFD4, #FFEB3B, #FFFFFF).
    * Se utilizó la fuente "Press Start 2P" para la tipografía (requiere incluir la fuente de Google Fonts en el HTML).
    * Se añadieron efectos de resplandor neón con `text-shadow`.
    * Se modificaron los estilos de los elementos para adaptarlos a la estética arcade.
* **Estructura HTML (index.html):**
    * Se incluyó la fuente "Press Start 2P" de Google Fonts.
    * Se ajustó la estructura para que coincida con los nuevos estilos y la lógica implementada.
    * Se realizaron modificaciones en las etiquetas y clases para un mejor funcionamiento de la aplicación.

## Instalación

1.  Clona el repositorio: `git clone <URL_del_repositorio>`
2.  Abre el archivo `index.html` en tu navegador.

## Dependencias

* HTML5
* CSS3
* JavaScript
* Google Fonts ("Press Start 2P")

## Cómo Ejecutar el Proyecto

Simplemente abre el archivo `index.html` en cualquier navegador web moderno.

## Posibles Problemas y Soluciones

* **Problema:** La lista de amigos o el resultado no se actualizan correctamente.
    * **Solución:** Verifica que los IDs en el HTML (`listaAmigos`, `resultado`, etc.) coincidan con los utilizados en el JavaScript.
* **Problema:** Los estilos no se cargan correctamente.
    * **Solución:** Asegúrate de que la ruta al archivo `style.css` en el HTML sea correcta.
* **Problema:** La fuente "Press Start 2P" no se muestra.
    * **Solución:** Verifica que la etiqueta `<link>` a Google Fonts esté presente y sea correcta en el `<head>` del HTML.

## Mejoras Futuras

* Implementar persistencia de datos (por ejemplo, usando `localStorage`) para que los nombres no se pierdan al recargar la página.
* Añadir la posibilidad de eliminar nombres de la lista.
* Mejorar la accesibilidad de la aplicación.
* Agregar animaciones o efectos de sonido para una experiencia de usuario más inmersiva.

## Autor

Daniel_Soto
