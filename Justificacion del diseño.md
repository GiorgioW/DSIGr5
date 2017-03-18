
# Justificación del diseño de la aplicación para la parte cliente

## Extracción de Requisitos

 - Interfaz sencilla
 - No profundizar mucho en mecánica
 - Muy poca gente paga a través de la aplicación
 - La gente suele aceptar que una aplicación sepa su ubicación 
 - Que pedir una cita sea lo fundamental, por encima de la avería o el taller.


## Justificación del diseño de la parte del cliente

Para hacer esta aplicación preguntamos a los usuarios que colores identificaban con un taller de coches y determinaron que eran azul, gris y blanco. 
En el estudio vimos que a la gente no le importa dar su ubicacion, luego creimos que podria ser util incorporar el boton localizame, que permitirá ubicar el dispositivo y encontrar talleres por la zona. También habilitamos la opción de buscar talleres en una ciudad/pueblo concreto introduciendo el código postal, para aquella gente que desconfíe de dar su ubicación a una aplicación.

En el estudio, también vimos que la gente prefiere no registrarse en una aplicación cuyo uso es tan rápido como en la nuestra, luego permitiremos el uso de la aplicación sin necesidad de registro, aunque el usuario tendrá que presentar cierta información para evitar falsas citas al taller.

Cuando preguntamos a la gente que calificase sus conocimientos sobre mecánica,vimos que la mayoría tenía poco o ningún conocimiento sobre este campo, así que para evitar que la gente se pierda en la parte mecánica de la aplicación, tomamos la decisión de ser lo más generales posible, aunque también se habilitará una textarea opcional para que puedan precisar la avería que han sufrido, y así que el taller tenga más información sobre la avería, permitiendo fijar fechas más concretas.

Hemos decidido no tener en cuenta la opción de pagar a través de la aplicación, puesto que la mayoría de personas que completaron la encuesta respondieron que no suelen pagar a traves del movil. Además, así dejaremos a elección del taller el método de pago, sin tener que forzarlos a utilizar un método propuesto por la aplicación. 

Creemos que es importante poder filtrar los talleres en la lista de talleres, para poder encontrar el que más se adecue a lo que el cliente busque, por eso hemos habilitado una serie de filtros para ordenar este listado. Algunos ejemplos son por valoración, cercanía, radio de cobertura...

Los talleres que quieran aparecer en la aplicación deberán registrase en la aplicación para poder aparecer, para evitar tener que hacer una búsqueda masiva de talleres.

A la hora de concretar las citas, dividiremos el proceso en tres subprocesos pequeños para no abrumar con excesiva información al cliente. Además evitaremos que el cliente salga de la aplicación exponiendo los mínimos datos personales posibles(solo los indispensables).

A la hora de escoger una fecha, al cliente solo le aparecerán las citas que el taller ha marcado como disponible. Así evitamos que lleguen demasiados pedidos a la vez al taller, intentando así que no se sature.

En la pantalla de selección de coche, dispondremos de desplegables para evitar que el usuario cuele informaciones falsas.

En el último paso, hemos decidido mostrar un sumario de todos los datos de la cita, para que el usuario la confirme, aunque también tiene la posibilidad de editar los datos anteriores. También en este paso tendrá que dejar datos personales que le identifiquen, para facilitar el trabajo al taller y corroborar que la cita no sea falsa.

***
# Justificación del diseño de la aplicación para la parte profesional

## Extracción requisitos 

 - Interfaz fácil con la mayor información posible.
 - Alta usabilidad en pequeñas porciones de tiempo
 - Posibilidad de convertir la agenda de la aplicación, en la agenda oficial del taller.


## Justificación del diseño de la parte profesional

Como los clientes nos pidieron una interfaz con mucha información, decidimos que teníamos que intentar meter toda la información en una sola pantalla, para evitar que un mecánico, con poco tiempo, tenga que navegar entre distintas pestañas, para ver la información de los pedidos.
Es por eso que dispusimos de un calendario corto, de 2 semanas, en la que se mostraba todos los pedidos que se habían introducido en la aplicación, con la información relevante del pedido en primera página. Además el encargado puede moverse entre los días del calendario, para organizar el trabajo. 
Para intentar mostra información de otros días, en cada dia aparecera un numero de pedidos que ya han sido asignados(no se ha podido realizar en el prototipo), así como una pequeña notificación encima de los días, cuando entra un nuevo pedido al taller.
Los días del calendario utilizan un código de colores(rojo,amarillo,verde) para que se pueda ver como de saturado esta el taller en cada día( en el prototipo no se ha podido hacer).
Para asignar los nuevos pedidos a los mecánicos, se dispondrá de una campana en la parte superior, que muestra los nuevos pedidos.
También hemos añadido una función para añadir pedidos de forma manual( botón + de la parte superior), por si el taller quiere utilizar nuestro sistema como agenda definitiva.

