Realizado por: Noel Padrón Jiménez y Joel Rodríguez González
![image](https://github.com/user-attachments/assets/8d0ba9e6-b5aa-4e49-a4c6-84e26632dd23)

Proyecto de Visión por Computador
Descripción:
Este proyecto implementa diversas tareas de procesamiento de imágenes utilizando técnicas de visión por computador en Python, principalmente a través de la librería OpenCV. A lo largo del proyecto, se desarrollan tareas como la creación de imágenes sintéticas, manipulación de planos de color, y captura de video en tiempo real para detectar características clave de la imagen.

Requisitos
Para ejecutar este proyecto es necesario tener instalados los siguientes paquetes:

OpenCV: Para la captura y procesamiento de imágenes.
NumPy: Para la manipulación de matrices.
Matplotlib: Para la visualización de imágenes.

Funcionalidades Implementadas
1. Creación de Tablero de Ajedrez
Se genera una imagen de 800x800 píxeles que simula un tablero de ajedrez, donde se alternan colores en una cuadrícula de 8x8.

2. Imagen al Estilo Mondrian
Se crea una imagen basada en el estilo artístico de Piet Mondrian, utilizando rectángulos de colores y líneas negras. La imagen es de 400x400 píxeles y contiene áreas en colores rojo, azul, amarillo, blanco y negro.

3. Manipulación de Planos de Color
Se capturan imágenes desde la cámara web y se separan los canales de color (rojo, verde y azul). Luego, se modifican los valores de un canal específico (por ejemplo, aumentando el brillo del canal rojo) y se muestran los tres planos concatenados en una sola imagen.

4. Detección de Zonas Más Claras y Oscuras
En esta tarea, se capturan fotogramas en tiempo real y se detectan las zonas más claras y oscuras de la imagen. Se dibujan círculos en las posiciones correspondientes al píxel más claro y más oscuro.

5. Zonas de 8x8 Más Claras y Oscuras
Se reduce la resolución de la imagen en bloques de 8x8 para identificar las zonas más claras y oscuras. Luego, se dibujan círculos en esas áreas sobre la imagen original.

6. Efecto Pop Art
Se captura video en tiempo real y se crea una composición de 4 cuadrantes con diferentes efectos visuales: imagen original, imagen invertida, detección de bordes, y aplicación de un mapa de color.

Ejecución
Para ejecutar el proyecto, asegúrate de tener conectada una cámara web.
Ejecuta el script de Python que corresponde a la funcionalidad que deseas probar.
Usa la tecla ESC para detener la ejecución y cerrar las ventanas de visualización.
