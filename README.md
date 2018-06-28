# YOLO Notebooks
### ¿Qué son los notebooks de Jupyter?
Los cuadernos de Jupyter son un aplicación web de código abierto que permite crear y compartir documentos que contengan tanto código, como ecuaciones, como texto que permite explicar los pasos realizados.

### Notebooks
Aquí nos podemos encontrar con un conjunto de Noteboks de Jupyter, que se corresponden con la implementación del Trabajo de Fin de Máster:
* **Filtros.ipynb**: en este notebook veremos cómo funciona el operador de convolución y cómo los filtros nos van a permitir, entre otras cosas, resaltar los bordes de la imagen para su detección. 
* **VentanaDeslizante.ipynb**: en este notebook se definen las técnicas clásicas para la detección de objetos en imágenes como la ventana deslizante, la pirámide de imágenes y el *non maximmun supression*. Además contamos con un clasificador (previamente entrenado) que nos dirá la clase del objeto y utilizaremos las técnicas anteriores para realizar una predicción.
* **CPUs-GPUs.ipynb**: en este notebook vamos a realizar una comparación de los entrenamientos de varias redes en distintos entornos, en este caso se realizarán las pruebas con la CPU.
* **CPUs-GPUsDrive-GPU.ipynb**: en este notebook vamos a realizar una comparación de los entrenamientos de varias redes en distintos entornos, en este caso se realizarán las pruebas con la GPU cedida por Google Drive.
* **YOLO1.ipynb**: este notebook permite descargar la red neuronal YOLO, además de copiar dentro de la carpeta donde se encuentra YOLO un conjunto de notebooks con ejemplos de modelos realizados.
* **YOLO2.ipynb**: este notebook contiene las explicaciones para comenzar a usar YOLO y también contiene una serie de ejemplos donde se puede observar como funciona, tanto para el caso de imágenes como de vídeos.
* **YOLO_PASCAL_VOC.ipynb**: en este caso se ha desarrollado un notebook donde vamos a ver cómo se entrena la red YOLO desde cero utilizando un dataset llamado Pascal VOC.
* **YOLO_CoCo.ipynb**: en este notebook vamos a ver cómo se entrena la red YOLO desde cero utilizando un dataset llamado CoCo.  
* **YOLO_Estomas.ipynb**: en este notebook vamos a ver cómo se entrena la red YOLO desde cero utilizando un dataset de estomas, el fin de este dataset consiste en dadas unas imágenes que detecte si hay estomas y donde.
* **CLODSA_Estomas.ipynb**: este notebook nos permite aumentar el dataset en caso de contar con un número reducido de imágenes.
* **NotebookGeneral.ipynb**: En este caso se va a realizar un notebook general que permita crear un modelo de detección, para que cualquier usuario pueda usarlo dado un conjunto de datos cualquiera.
* **NotebookGeneralEstomas.ipynb**: El notebook genérico aplicado para crear un modelo de detección de estomas.
