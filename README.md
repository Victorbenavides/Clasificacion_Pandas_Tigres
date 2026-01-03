# Clasificacion_Pandas_Tigres
Lo que se está haciendo en esta parte es el entrenamiento de la red neuronal con las fotos de tigres y pandas que se procesaron antes. Básicamente, se está construyendo el "cerebro" que va a aprender a reconocer a los animales por su cuenta.

Aquí están los puntos clave del proceso:

Estructura del modelo: Se usa un modelo de tipo Sequential con capas de neuronas. La primera capa, Flatten, estira los píxeles de la imagen para que la computadora los pueda leer en fila, y las capas siguientes se encargan de encontrar los patrones que distinguen a un animal de otro.

Configuración del aprendizaje: El modelo usa el optimizador adam y se enfoca en mejorar la accuracy (precisión). Es como decirle a la IA: "tu objetivo es equivocarte lo menos posible al adivinar".

El entrenamiento (fit): Se pone a la IA a estudiar las imágenes durante 30 vueltas o epochs. En cada vuelta, el sistema intenta identificar si la foto es de un tigre o un panda y ajusta sus parámetros internos según sus aciertos o errores.

Resultado: Al final de las 30 iteraciones, el modelo ya debería tener la capacidad de recibir una imagen nueva y clasificarla correctamente como "Tigre" o "Panda".
<img width="943" height="652" alt="image" src="https://github.com/user-attachments/assets/841d5235-5ddb-4832-8739-7c9256101472" />
