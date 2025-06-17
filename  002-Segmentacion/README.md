# Ejercicio Integrador 2

## Tabla de Contenidos

- [Laboratorio](#laboratorio)
- [Entregable](#entregable)

## Laboratorio
Se conforma de una actividad donde se pondrá en práctica lo aprendido durante las clases siguientes a la primer parte del Integrador

El objetivo de este proyecto es que utilicen procedimientos básicos de procesamiento de imágenes para leer una imagen, aplicarle mejoras, segmentar objetos y mostrar los resultados en una presentación visual.
**La duración original del ejercicio era para realizarlo en una (1) hora.**

Los puntos incluidos para este ejercicio son los siguientes:
### Importar una imagen de sample
En este caso se usó la imagen `sample2.jpg`. 
La misma debía ser pasada a formato RGB y se aportaría una explicación de por qué se usó.

### Optimización de imagen
Estas incluyen:
* Ajuste de brillo y contraste
* Ecualización de histograma: Se usa ´cv2.equalizeHist()´

### Segmentación de imagen
* Converción a HSV para facilitar definición de rangos de color.
* Definir el rango de color: Se asignan rangos minimos e maximos para los umbrales HSV

### Dibujo de formas y texto sobre imagen segmentada

## Entregable

En esta práctica integradora, aplicaremos y conectaremos dos técnicas importantes de Visión por Computadora que hemos visto: Detección de rostros y de Landmarks Faciales

Estas técnicas son fundamentales en muchas aplicaciones, desde filtros de redes sociales y sistemas de reconocimiento facial hasta análisis de expresiones o detección de somnolencia en conductores.

### Instalación de entorno
#### Instalación de versión alternativa de OpenCV
Se pisa por nueva versión de `opencv-contrib-python`

### Descarga de recursos
Se hace uso de la imagen `sample4.jpg` para llevar adelante la prueba

### Detección de Rostros
Utilizaremos el método de Haar Cascades para encontrar la ubicación de múltiples caras dentro de una imagen. Se hace uso de Haar Cascades

### Detección de Landmarks Faciales
Una vez localizadas las caras, aplicaremos un modelo más avanzado (LBF) para identificar 68 puntos clave específicos en cada rostro (ojos, cejas, nariz, boca, mandíbula).

### Selección y Aplicación de Landmarks
