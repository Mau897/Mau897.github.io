# Prototipo de página de descarga de neurona interactiva DUNNE

## Neuron AR Project

Proyecto de neurona interactiva desarrollado en Unity.

Requisitos:
- Unity 2022.3 LTS
- Vuforia Engine
- Blender (modelado 3D)
- C# (scripts de interacción)

Instalación:
1. Descargar repositorio
2. Abrir con Unity Hub
3. Ejecutar escena SampleScene

Controles:
- Tocar soma
- Tocar axón
- Tocar dendritas

Link de descarga de proyecto unity 
-https://drive.google.com/file/d/1gRO4gvStI9SrGLCbsQCDbHLxofhM9vU0/view?usp=sharing
## Estructura del proyecto

Assets/
Models → modelo de neurona 3D  
Scripts → scripts de interacción en C#  
Scenes → escena principal  
Materials → materiales del modelo  

**Carpetas importantes**

Assets/
Contiene todos los recursos del proyecto.

Scripts/
Contiene los archivos .cs que controlan la interacción.

Models/
Contiene el modelo 3D de la neurona exportado desde Blender.

Scenes/
Contiene la escena principal de Unity.

## Instalación

1. Descargar el proyecto
2. Abrir Unity Hub
3. Seleccionar "Open Project"
4. Elegir la carpeta del proyecto

## Uso

1. Ejecutar la escena principal
2. Apuntar la cámara al marcador de imagen
3. La neurona aparecerá en realidad aumentada
4. Tocar partes de la neurona para interacción


¿Que es Vuforia?
Vuforia es un motor de realidad aumentada (AR) que funciona dentro de Unity.

Permite que la cámara del dispositivo detecte una imagen o marcador y coloque un objeto 3D encima de él.

En nuestro caso:

La cámara detecta una imagen marcador

Sobre esa imagen aparece la neurona 3D

Cómo funciona en el proyecto

El sistema tiene tres elementos principales:

1.- AR Camera

Es la cámara especial de Vuforia que:

usa la cámara del dispositivo, analiza lo que ve y busca marcadores reconocidos

2.- Image Target

Es la imagen que Vuforia reconoce.

Puede ser:

un QR, una imagen impresa, una ilustración

Cuando la cámara detecta esa imagen: aparece el modelo 3D.

En Unity aparece como: Image target

RESUMIENDO: 

Sistema de Realidad Aumentada

-El proyecto utiliza Vuforia Engine para implementar realidad aumentada en Unity.

-Vuforia permite reconocer marcadores visuales (Image Targets) mediante la cámara del dispositivo.

-Una vez detectado el marcador, se renderiza un modelo 3D de una neurona sobre la imagen.

-Scripts en C# permiten interactuar con las partes de la neurona, identificando elementos como soma, dendritas y axón.



En scripts pueden encontrar la neurona en obj para su uso en blender

## Autores

Proyecto desarrollado por Mauricio Mendiola Rivera
División Universitaria de Neuroingeniería

