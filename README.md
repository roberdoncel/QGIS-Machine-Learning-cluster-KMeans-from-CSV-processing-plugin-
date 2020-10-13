# QGIS-Machine-Learning-cluster-KMeans-from-CSV-processing-plugin-
Versión propia, para practicar, del plugin de agrupación KMeans con la capacidad de calcular por si mismo el número de clusters idóneo, aplicando el coeficiente de silhouette. Como input requiere un CSV con alguna columna con coordenadas y retorna la posición de los centroides. Con alguna linea de código más se podría generar una capa con los agrupamientos de los puntos calculados. 

Es necesario tener instalado en QGIS la librería scikit-sklearn. 

Para el ejemplo se ha usado un dataset del despliegue de redes Ftth en Francia, https://www.data.gouv.fr/es/datasets/planning-des-deploiements-ftth/. Aunque no tiene mucho sentido práctico, el ejercicio se podría interpretar como donde y cuantas oficinas de apoyo pondrías para atender de manera eficiente toda la red.

