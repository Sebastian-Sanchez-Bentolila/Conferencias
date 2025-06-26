# README: Gráficos Interactivos y Visualizaciones con Plotly

## Descripción del Proyecto
Este repositorio contiene el trabajo final realizado para la materia **Programación Avanzada** de la carrera de **Ciencia de Datos** en la **Universidad Nacional de Guillermo Brown (UNAB)**. El proyecto consiste en una presentación interactiva que explora las capacidades de la biblioteca Plotly para crear visualizaciones de datos dinámicas y profesionales en Python.

## Autores
- Tomas Muino
- Ivana Noelia Zurdo
- Sebastian Sanchez Bentolila
- Uriel Capdevila

## Fecha
09 de junio de 2025

## Contenido
El proyecto abarca los siguientes temas:
1. **Introducción a Plotly**: Características y ventajas de la biblioteca.
2. **Gráficos 2D**: Líneas, dispersión, barras, pastel, caja y bigote, violín e histogramas.
3. **Gráficos 3D**: Superficies, dispersión 3D y mallas.
4. **Subplots**: Creación de múltiples gráficos en una misma figura.
5. **Personalización Avanzada**: Uso de `graph_objects` para control detallado de los gráficos.
6. **Modelado en Clases**: Implementación de Programación Orientada a Objetos (POO) para generar visualizaciones.
7. **Exportación de Gráficos**: Métodos para guardar gráficos en formatos HTML e imágenes estáticas.

## Requisitos
Para ejecutar el código y reproducir los ejemplos, se necesitan las siguientes librerías:
- Python 
- Plotly 6.1.2
- Pandas 2.1.4
- NumPy 1.26.4
- Dash 3.0.4 

Instalación:
```bash
pip install plotly pandas numpy dash
```

## Estructura del Repositorio
- **`/Cuaderno_Plotly_Python.slides.html`**: Presentación interactiva en formato HTML.
- **`/Exportaciones/`**: Ejemplos de gráficos exportados en formato HTML.
- **`/Datasets/`**: Conjuntos de datos utilizados en los ejemplos (ej. `casos_covid19_2020.csv`).
- **`/Imagenes/`**: Imagenes usadas para la presentación.

## Cómo Usar
1. Clona el repositorio:
   ```bash
   git clone https://github.com/Sebastian-Sanchez-Bentolila/Conferencias/tree/f0f1c8bd5656f7b64ed8ebba270144768ef2c667/Plotly%20en%20Python-Trabajo%20Final-Programacion_Avanzada
   ```
2. Abre el archivo `Cuaderno_Plotly_Python.slides.html` en tu navegador para ver la presentación interactiva.
3. Para ejecutar los ejemplos en un entorno Jupyter Notebook, copia el código de los bloques marcados como `In [ ]`.

## Ejemplos Destacados
- **Gráfico de Línea Interactivo**: Visualización de precios de acciones simuladas.
- **Scatter Plot con Iris**: Relación entre dimensiones florales coloreadas por especie.
- **Gráfico 3D**: Dispersión tridimensional con el dataset Iris.
- **Clases para Análisis**: Implementación de POO con `DatasetAnalyzer`, `GeneradorMetricas` y `VisualizadorPlotly`.

## Recursos Adicionales
- [Documentación Oficial de Plotly](https://plotly.com/python/)
- [Galería de Ejemplos](https://plotly.com/python/gallery/)
- [Tutoriales Básicos](https://plotly.com/python/getting-started/)

## Contribuciones
Las contribuciones son bienvenidas. Si deseas mejorar el proyecto, abre un *issue* o envía un *pull request*.

## Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

**Nota**: Para activar el desplazamiento en la presentación HTML, modifica la variable `var scroll = false` a `true` en el archivo `.slides.html` (ver instrucciones en la presentación). 

¡Esperamos que encuentres este material útil para tus proyectos de visualización de datos!
