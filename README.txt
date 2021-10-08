Nota: Si obtienen un error en los import keras, anteponer tensorflow. antes de cada import. 

Ejm:  from keras.layers import Dropout
      from tensorflow.keras.layers import Dropout
      
      
# Bird species classification

En este proyecto realizamos un modelo de clasificación de imágenes basado en la red VGG16 usando transfer learning y data augmentation

Data set aves

https://www.kaggle.com/gpiosenka/100-bird-species?


### Pre-requisitos 📋

      _Anaconda
      _Jupyter notebook o google colab
      _Tensorflow 
      _Keras


### Descripción del directorio

1. ...\dataset

      Directorio donde estan las imagenes para el entrenamiento, validación y pruebas

2. ...DataAumgentationTrain
      
      Este documento contiene el código para el entrenamiento y prueba de la red neuronal convolucional
   
3. ...ConfusionMatrix.ipynb

      Documento de trabajo de jupyter notebook donde calculamos las métricas de desempeño y matriz de confusión

4. ... BirdClass.iphnb

      Documento de trabajo de jupyter notebook para entrenamiento del clasificador (actualizado)
