# Un diseño pensado para conductores
El diseño y la naturaleza de Android Auto está enfocado de forma clara a los conductores, a respetar las normas en materia de seguridad vial y a facilitar la interacción. Google destaca en varias ocasiones estos puntos y parece que los desarrolladores tendrán la obligación de tenerlos en cuenta.
Google no dará grandes opciones a los creadores de contenidos para Android Auto a la hora de innovar con sus diseños. El motivo es que Google no quiere que haya contenidos que puedan restar atención a la circulación y por ello establece restricciones muy concretas y una línea de diseño uniforme para toda la experiencia.

Es importante que conozcamos con detalle qué es y qué no es Android Auto. Aunque puede parecerlo por la idea que todos tenemos de Android, esta propuesta de Google **no es un sistema operativo para coches**. Al menos no lo es si lo contemplamos como un software que se ejecuta en el propio vehículo y que hace las veces de intermediario entre nosotros y las apps. Lo más preciso es que lo veamos como **una extensión del sistema operativo de nuestro teléfono móvil que nos permite disfrutar algunas de nuestras apps en la pantalla de nuestro coche**. Pero ni el sistema operativo ni las apps se ejecutan en nuestro coche. El responsable de «correr» todo el software es el hardware de nuestro teléfono móvil.

**La conexión física entre el móvil y el coche se establece a través de un cable USB** porque nos ofrece la capacidad de transferencia de datos y la estabilidad necesarias para que el teléfono pueda enviar a la pantalla del coche toda la información de la interfaz y las apps. Esto significa, sencillamente, que** la mayor parte del peso recae en nuestro smartphone, y la pantalla de nuestro coche solo se comporta como un dispositivo de salida** que nos permite interactuar con el sistema y las aplicaciones.

**Android Auto no hace más que adaptar la interfaz de las apps al factor de forma y las prestaciones táctiles de las pantallas de los coches**, que no son iguales que las de nuestros smartphones. De lo contrario no se verán bien, y, en consecuencia, no las podremos usar. Por esta razón, necesitamos crear la aplicación para android auto cuando seleccionamos la creación del proyecto , si actualizas android estudio a la última versión , cuando creas un proyecto , en el momento en el que te mada elegir la api , ahora además de poder elegir que sea compatible con televisión y con smartwatch, aparece una opcion que es android auto ,lo cual nos creará un layout del tipo auto, el único requisito para poder marcarlo es que necesitas seleccionar una api igual o mayor a la 5.0(Lollipop), que es la mínima para desarrollo en auto, de esta manera  Android Auto nos ofrezcan una experiencia óptima cuando las usemos desde la pantalla de nuestro coche.

En nuestro caso , la aplicación se quedo muy verde , debido a la dificultad de uso de las nuevas utilidades del nuevo SDK de auto , y de la necesidad de un android 5.0 para poder probarlo.

Hasta el punto actual del proyecto , tenemos un programa de reconocimiento de voz mediante la api de google y que también lee haciendo uso de la clase TextToSpeech que tiene android. Puedes introducir el texto manualmente para que lo lea , o mediante voz ,para que escriba lo que dices y lo pueda leer.
Estas son dos utilidades básicas en caso de querer desarrollar en auto , ya que por ejemplo para poder hacer uso de él es mucho mejor hacerlo mediante voz y sin tener la necesidad de estar atento a pulsar en la pantalla , y en caso de recibir mensajes , es preciso que pueda leerlos el dispositivo , ya que no puedes permitirte  desviar la atención a la lectura, por ejemplo de un wattsapp.

En caso de que alguien quiera desarrollar para Android Auto , google da un curso por udacity:

 * https://www.udacity.com/course/android-auto-development--ud875C
