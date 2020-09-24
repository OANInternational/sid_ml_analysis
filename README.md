# Detección automática de edificios con Computer Vision

En este proyecto tratamos de entrenar un modelo basado en redes neuronales capaz de identificar edificios y construcciones de forma automática en la región de Nikki (Benín).
Partimos de imágenes satelitales de la región obtenidas a través de la API de Google Maps sin etiquetar.
![Workflow](https://github.com/OANInternational/sid_ml_analysis/blob/master/Images/1.JPG)

Estas imágenes se etiquetarán a través del software LabelIMG en formato YOLO, a partir del cual se generará un archivo .txt para cada imagen con la posición relativa de cada edificio marcado.

Una vez etiquetadas nuestras imágenes de entrenamiento, podremos empezar a entrenar nuestro YOLO (You Only Look Once) de cara a poder realizar predicciones.

