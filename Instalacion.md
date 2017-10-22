# Instalación
___:

## Dependencias

La **API** de detección de objetos de Tensorflow depende de las siguientes bibliotecas:

- [x] Jupyter Notebook
- [x] Tensorflow
- [x] Pillow 
- [ ] Matplotlib
- [ ] lxml
- [x] tf Slim (which is included in the "tensorflow/models/research/" checkout)
- [x] Protobuf 2.6

Para más detalles sobre la instalacion de *tensorflow*, aquí [Instalación detallada de Tensorflow](https://www.tensorflow.org/install/). 
Pro lo general los comandos basicos para instalarlo son:

```
#Para CPU
pip install tensorflow

#For GPU
pip install tensorflow-gpu
```

## Compilación de Protobuf

___:

Esto nos ayuda a traducir el archivo de texto que hace tensorflow parseandolo para generar clases en C o Python.
