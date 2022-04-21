# Clustering
Desarrollado en el curso Reconocimiento de Patrones en Minería de Datos por: Kevin Reyes.
## Objetivos
- Comparar los algoritmos de clustering: K-means, clustering jerárquico aglomerativo y DBSCAN en tres conjuntos de datos distintos.
- Identificar ventanas y desventajas de cada algoritmo analizado.

## Descripción
Estudio comparativo de algoritmos de clustering: K-means, clustering jerárquico aglomerativo y DBSCAN.

## Conclusiones
- K-means reconoce bien clusters con formas circulares de similar tamaño, y no tiene problemas con clusters de distintas densidades, sin embargo, falla cuando hay clusters de distinto tamaño y tiene dificultades con clsuters no circulares o formas complejas como espiras. Además, se debe encontrar el valor de K lo cual podría no ser sencillo en u espacio de alta dimensionalidad.
- DBSCAN detecta clusters de cualquier forma y de distintas densidades, sin embargo, falla cuando los clusters están unidos entre por outliers.
- HAC detecta clusters de formas completas, sin embargo, es sensible a outliers que pueden generar puentes entre distintos clusters. Además, se debe encontrar el valor de K y tipo de linkage más adecuado, lo cual podría no ser sencillo en un espacio de alta dimensionalidad.

## Stack de tecnologías
- Scikit-learn.
- Matplotlib.
- Numpy.
- Pylab.