# Repositorio orientado a Tecnicas de Procesamiento de Imagenes (TPDI) para IFTS24 - 2025

## Tabla de Contenidos

- [Descripción](#descripción)
- [Contenidos](#contenidos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)
- [Contacto](#contacto)

## Descripción

### Sobre este repositorio

Este repositorio tiene el propósito de proporcionar un repaso y orientaciones de funcionalidades relacionadas a Python y algunas librerías dedicadas a procesamiento de imágenes, aprovechando el espacio de GitHub para así dar a disposición una estructura más organizada.

Esto es con la finalidad de presentar un proyecto integrador para la materia de Procesamiento de Imágenes en la Tecnicatura en Ciencia de Datos e Inteligencia Artificial del IFTS24.

### Sobre la materia y disciplina

El Procesamiento Digital de Imágenes (PDI) es una disciplina fundamental dentro del campo del Análisis de Datos e IA, que se enfoca en la manipulación y análisis de imágenes digitales para extraer información útil y automatizar tareas visuales. 
Las técnicas de PDI son esenciales para una amplia gama de aplicaciones, desde la visión por computadora hasta el diagnóstico médico.

## Contenidos

Aquí puedes encontrar una lista de las carpetas con los notebooks incluidos en este repositorio y una breve descripción de cada uno:

* [Repaso de Python](000-Repaso): Breve repaso de los fundamentos del lenguaje **python**. El mismo contiene algunos ejemplos.
* [Ejercicio Integrador](001-ManipulacionBasica): Aplicamos tecnicas de separacion de colores, muestreo, cuantizacion y segmentación simple a una imagen, siguiendo una consigna.
* [Ejercicio Integrador 2](002-Segmentacion): Se aplican técnicas de reconocimiento facial, así como de landmarks faciales junto a su selección posterior. Incluye un archivo de laboratorio con pruebas previas de segmentación de imagen.
* [Proyecto Integrador Final](003-IntegradorFinal): Aplicamos las técnicas aprendidas en diferentes clases, así como en los trabajos integradores anteriores, un modelo de reconocimiento de objetos para facilitar la detección de objetos ortopédicos.

## Instalación
### Requisitos y dependencias
* Este notebook requiere las siguientes bibliotecas de Python: `pandas`, `numpy`, `matplotlib`, `opencv-python`.
  Si bien estos ya están declarados en los notebooks, puedes instalarlas ejecutando `pip install pandas numpy matplotlib cv2` en una celda de Colab.
* Algunos notebooks pueden requerir la descarga de conjuntos de datos específicos. Las instrucciones para hacerlo se encuentran dentro de los README.md de las carpetas correspondientes
* Para [Proyecto Integrador](003-IntegradorFinal), se requiere de `ultralytics`. Puede ser instalado usando `pip install ultralytics` y ésta instalará todas sus dependencias

### Comandos de importación para repositorio
```bash
git clone https://github.com/gimb99/gbgTPDI.git
cd gbgTPDI
pip install -r requirements.txt
```
## Uso
### Uso en Colab

Si deseas ejecutar los notebooks del repositorio directamente en Google Colab, sigue estos pasos:

* Abre Google Colab.

* Selecciona la pestaña GitHub en la pantalla de inicio.

* Pega la URL del repositorio: https://github.com/gimb99/PDI_BARTHOU_GONZALO/

* Elige el notebook que deseas abrir.

* Ejecuta el notebook como lo harías en un entorno local.

> Nota: Asegúrate de que tus notebooks tengan las celdas iniciales para configurar adecuadamente el entorno (por ejemplo, configuración de GPU/TPU o instalación específica de dependencias) y que funcionen sin inconvenientes en Colab.

## Contribuciones

Si deseas contribuir a este repositorio añadiendo nuevos notebooks, corrigiendo errores o realizando mejoras, son bienvenidas. Los pasos son los siguientes:

1.  Realiza un "fork" del repositorio.
2.  Crea una nueva rama con tu contribución (`git checkout -b feature/nueva-funcionalidad`).
3.  Realiza tus cambios y commitealos (`git commit -am 'Añade una nueva funcionalidad'`).
4.  Sube tus cambios a tu fork (`git push origin feature/nueva-funcionalidad`).
5.  Crea un "pull request" desde tu rama a la rama principal de este repositorio.

## Licencia

Este proyecto está bajo la licencia GPL-3.0 - consulta el archivo [LICENSE](LICENSE) para más detalles.

## Contacto

Ante cualquier pregunta, sugerencia o posible problema con estos notebooks, no dudes en contactarme a través de los siguientes medios:

* **Nombre:** Gonzalo B
* **Email:** gonzalobarthou.info@gmail.com
* **GitHub:** [gimb99](https://github.com/gimb99)

