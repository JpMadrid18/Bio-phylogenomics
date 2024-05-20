# Análisis de Expresión Diferencial

## Procedimiento
1. **Preprocesamiento de datos**: Lectura y normalización de los datos de expresión génica.
2. **Análisis estadístico**: Uso de herramientas como DESeq2 o edgeR para identificar genes diferencialmente expresados.
3. **Visualización de resultados**: Generación de volcano plots para cada tratamiento, tablas de comparación, heatmap y PCA.

## Resultados e Interpretación

### Volcano Plots
![Volcano Plot](/home/earizaa/Documentos/archivos_jpmadrid/Bioinformatica/Proyecto_rnaseq/repositorio_phylogenomics/Bio-phylogenomics/graficos_y_arboles/differential_expression/volcanoplots/volcano1.jpg)

Los volcano plots muestran la relación entre el valor de fold change y la significancia estadística (p-valor) de cada gen. Los puntos más alejados del centro indican genes con mayor diferencial de expresión y significancia.

### Tabla de Resultados
![Tabla](../results/expresion_diferencial/tabla.png)
La tabla resume los genes diferencialmente expresados, mostrando sus respectivos valores de fold change, p-valor ajustado, y otros métricas relevantes. Genes con p-valores bajos y altos valores absolutos de fold change son los más significativos.

### Heatmap
![Heatmap](../results/expresion_diferencial/heatmap.png)
El heatmap visualiza la expresión de los genes a través de las muestras, permitiendo identificar patrones de expresión similares y agrupaciones entre muestras y genes.

### PCA (Análisis de Componentes Principales)
![PCA](../results/expresion_diferencial/pca.png)
El PCA reduce la dimensionalidad de los datos de expresión y muestra la variación entre las muestras. Muestras agrupadas indican similitud en los perfiles de expresión génica, mientras que muestras separadas indican diferencias significativas.
