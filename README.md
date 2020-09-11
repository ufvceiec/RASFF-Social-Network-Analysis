# RASFF-Social-Network-Analysis
Aplicación de técnicas de Social Network Analysis sobre los datos de RASFF portal mediante la elaboración de grafos en los cuales cada país constituye un nodo, y cada alerta originada en un pais y detectada o con destino en otro consituye una unión entre nodos.

## Organización de los archivos:
El proyecto cuenta con dos carpetas:
- Data_diagrams_charts
- Graphs_metrics

Todos los archivos están pensados para ejecutarse linealmente.
### Data_diagrams_charts
Archivos con análisis gráfico (diagramas de cuerdas, diagramas de barras, gráficos circulares, diagramas de burbujas..) de los datos.

**Chord_diagram.ipynb**: Diagrama de cuerdas realizado con Bokeh. Para la visualización de todos las figuras realizadas con Bokeh es necesario llevar a cabo los siguientes pasos:

- Abrir Command Prompt 
- Acceder a la carpeta donde esta el notebook
- Introducir el siguiente comando ```bokeh serve --show myapp.py``` cambiando *myapp.py* por el nombre del archivo que contiene la figura.
- Se abrirá en el navegador una pestaña con la siguiente dirección ```http://localhost:5006/myapp``` que contendrá la figura interactiva desarrollada.

**Covid_graphic_analysis.ipynb**: Análisis específico para ver el impacto del covid en las alertas.

**Graphic_analysis_graph_metrics.ipynb**: Análisis mediante diagramas de todo tipo.

### Graphs_metrics
Archivos para la generación de estructuras de grafos y la obtención de diversas métricas relacionadas.

**Metrics_powerlaw_and_monthly_graphs.ipynb**: Powerlaw de el grafo general de todas las alertas, y métricas de grafos mensuales.

**Monthly_most_frequent_path.ipynb**: Paths más frecuentes por mes.

**World_map_graph.ipynb**: Notebook para la generación rápida del grafo general sobre un mapa del mundo, con diversos indicadores.

**World_map_graph_construction.ipynb**: Construcción del grafo general sobre el mapa mundial en varios pasos.

## Ejemplo: World_map_graph
![Map_Image](/readme_images/7_map.png)


## Datasets:
Todos los datasets necesarios para a ejecución de los notebooks se encuentran en el Nas (Volumen 1)/carpeta **RASFF_Social_Network_Analysis**.

## Contact:
Responsible: Alberto Nogales (alberto.nogales@ceiec.es)\
Supervisors : Alberto Nogales\
Main developers: Rodrigo Díaz (rodrigo.diaz@ceiec.es)

