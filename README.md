# Clasificación automática de residuos con IA
**Proyecto realizado por el alumnado de 1º Bachillerato del IES Valle del Sol de Álora (Málaga)**

El proyecto consiste en abrir durante unos segundos y cerrar el contenedor correspondiente al plástico, papel y cartón u orgánico en función de la clasificación que hace una IA de un objeto mostrado ante la cámara.

Para ello un conjunto de más de 1000 imágenes imágenes de objetos plásticos, papel, cartón y orgánicos sobre fondo blanco han servido para entrenar un modelo de imágenes con Teachable Machine.

![Captura](https://github.com/TecnoProfesor/Residuos/assets/65020790/72bbe42e-4c24-4b5b-aabd-d223456ea2f5)

El enlace al modelo es público, por lo que puede usarse para programar otros proyectos. La URL al modelo es: 

La IA reconoce tres clases de objetos con las siguientes etiquetas: 'Envase', 'Papel  y cartón' y 'Orgánico'

Con CodeSkool se puede integrar el modelo desde Teachable Machine con una placa Micro:bit V2 usando las respectivas extensiones disponibles.

Usando una placa de extensión de conexiones para Micro:bit, se conectan tres servos de 5V para la apertura y cierre de los contenedores correspondientes según la imagen reconocida por el modelo.
