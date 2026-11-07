# Hito 2 | README de la entrega

Equipo e integrantes: Aliro Torrejón Aquino.
Versión entregada: 1.0
Fecha: Viernes 06 de Noviembre 2026

## Propósito y alcance
Complete el problema, las hipótesis y los límites. Datos de origen simulado.
Este proyecto consiste en analizar el comportamiento de una barra axial, sometida a cargas longitudinales, mediante un modelo de elasticidad lineal. Se busca determinar los desplazamientos nodales, comprobar la consistencia física y númerica del modelo propuesto, realizar un barrido de parámetros y comparar el rendimiento de dos estrategias de cálculos utilizadas para resolver dicho modelo: resolución mediante bucles o mediante opreaciones vectoriales.

El modelo considera pequeñas deformaciones, se trabaje en comportamiento elástico lineal, secciones transversales constantes y ausencia de cargas distribuidas. Los datos utilizados son simulados y corresponden a diversas combinaciones de áreas de sección y cargas aplicadas. 


## Archivos
- Hito2.ipynb: notebook del equipo. En el se encuentra el desarrollo, los cálculos, las comprobaciones, los gráficos y los resultados de la comparación se soluciones mediante bucles y vectorización con Numpy.
- barras_1000_entradas.csv: Archivo original con las 1000 combinaciones de parámetros de entrada (áreas y cargas). el archivo se conserva intacto.
- resultados.csv: Archivo generado con las entradas y los desplazamientos obtenidos para cada combinación del barrido.
- tiempos.csv: mediciones individuales del experimento de rendimiento, para las soluciones mediante ciclos y vectorización.
- Otros archivos imprescindibles: identificar, si corresponden.
Los PDF se entregan separados en Moodle.

## Reproducción desde cero
1. Descargar los archivos del repositorio y abrir Hito2.ipynb mediante Google Colab
2. Cargar el archivo "barras_1000_entradas.csv" en el panel de archivos de la sesión en Colab
3. Ejecutar todas las celdas del notebook en orden, desde el inicio hasta el final.
4. Durante la ejecución se realizan las comprobaciones numéricas del modelo, el barrido de parámetros, la generación de resultados y el experimento de rendimiento.
5. Loa archivos "resultados.csv","tiempos.csv" se generan mediante las celdas correspondientes del notebook. Se pueden descargar desde el panel de archivos de Colab.
## Entorno
Versiones efectivamente usadas de Python, NumPy, Pandas y Matplotlib: completar.
Tipo numérico y recurso de cómputo: completar.

## Fuentes, contribuciones y uso de IA
Complete las fuentes consultadas, que hizo cada integrante y el uso o no uso de asistentes.
Si se utilizó IA: herramienta, propósito, sugerencia, decisión y comprobación técnica.

## Retroalimentación
Observación recibida, cambio y prueba posterior: completar con hechos reales.
