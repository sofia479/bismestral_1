# Bimestral_-1

Este es un juego simple creado con Pygame, donde controlas un cohete para evitar colisionar con planetas que caen.

## Requisitos

Python 3.x
Pygame (pip install pygame)

## Cómo Ejecutar

1.  Asegúrate de tener Python y Pygame instalados.
2.  Guarda el código en un archivo llamado juego.py.
3.  Crea una carpeta llamada img en el mismo directorio que juego.py.
4.  Coloca las imágenes COHETE.png y PLANETA.png dentro de la carpeta img.
5.  Abre una terminal o línea de comandos, navega al directorio donde guardaste el archivo juego.py y ejecuta:

   bash
    python juego.py
   
## Controles

**Flecha Derecha:** Mueve el cohete a la derecha.
**Flecha Izquierda:** Mueve el cohete a la izquierda.
**ESC:** Cierra el juego.

## Descripción del Juego

El juego presenta un cohete que el jugador controla horizontalmente. El objetivo es evitar colisionar con los planetas que caen desde la parte superior de la pantalla. Cada vez que un planeta pasa sin colisión, el jugador gana un punto. El juego termina si el cohete colisiona con un planeta o si se sale de los bordes de la pantalla.

## Estructura del Código

**Inicialización:** Se inicializa Pygame, se definen las dimensiones de la ventana, los colores, y se cargan las imágenes.
**Variables del Juego:** Se definen variables para la posición y movimiento del cohete, la posición y velocidad de los planetas, la puntuación, y la fuente para mostrar la puntuación.
**Bucle Principal:** El bucle principal del juego se ejecuta hasta que el jugador presiona ESC o el cohete colisiona con un planeta o se sale de los margenes de la ventana.
**Gestión de Eventos:** Se gestionan los eventos de teclado para mover el cohete y cerrar el juego.
**Dibujado en Pantalla:** Se dibuja el fondo, los planetas, el cohete y la puntuación en la pantalla.
**Lógica del Juego:** Se actualiza la posición de los planetas, se verifica la colisión con el cohete, y se actualiza la puntuación.

## Imágenes

El juego utiliza las siguientes imágenes:

img/COHETE.png: Imagen del cohete.
img/PLANETA.png: Imagen de los planetas.

Asegúrate de que estas imágenes estén presentes en la carpeta img para que el juego funcione correctamente.