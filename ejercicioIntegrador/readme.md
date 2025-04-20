# Ejercicio Integrador: Color, Muestreo, Cuantización y Segmentación

## Consignas 
### Ejercicio 1: Espacios de Color
Usando una imagen a color de su elección:
a) Cargar la imagen con OpenCV y mostrar los canales BGR por separado. 
b) Identificar cuál de los tres canales tiene mayor información basándose en los valores promedio. 
c) Convertir la imagen de BGR a RGB y explicar por qué los colores se ven diferentes antes y después de la conversión.

### Ejercicio 2: Muestreo y Cuantización
a) Aplicar muestreo espacial a una imagen con factores de 2, 4 y 8. 
b) Para cada caso, calcular:
* El nuevo tamaño de la imagen
* El porcentaje de reducción de datos 
c) Aplicar cuantización con 4 niveles diferentes (32, 64, 128, 256) 
d) ¿En qué nivel de cuantización comienza a ser visible la degradación de la imagen?

### Ejercicio 3: Segmentación por Color
Dada una imagen con objetos de diferentes colores:
a) Implementar una segmentación para extraer objetos de un color específico usando umbrales en los canales RGB. 
b) Calcular y mostrar el histograma de la imagen en escala de grises. 
c) Encontrar las coordenadas del rectángulo que encierra el objeto segmentado. 
d) Dibujar los bordes del objeto segmentado en color rojo.

### Adicionales:
* Se debe considerar un buen uso de prácticas e implementación de código, así como un análisis de resultados y conclusiones.

## Notas
* Este notebook está diseñado como un ejercicio integrador, combinando varios temas importantes del procesamiento de imágenes.
