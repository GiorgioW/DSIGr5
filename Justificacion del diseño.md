
# Justificacion del diseño de la aplicacion para la parte cliente

## Extraccion de Requisitos

 - Interfaz sencilla
 - No profundizar mucho en mecanica
 - Muy poca gente paga a traves de la aplicacion
 - La gente suele aceptar que una aplicacoin sepa su ubicación 
 - Que pedir una cita sea lo fundamental, por encima de la averia o el taller.


## Justificacion del diseño de la parte del cliente

Para hacer esta aplicacion preguntamos a los usuarios que colores identificaban con un taller de coches y determinaron que eran azul, gris y blanco. 
A la gente no le importa dar su ubicacion, luego incorporaremos el boton localizame, que permitira ubicar el dispositivo y encontrar tallerers por la zona. tambien habilitamos la opcion de buscar talleres en una ciudad/pueblo concreto introduciendo el codigo postal.
A la gente no le gusta regristarse en una aplicacion cuyo uso es tan rapida como la nuestra, luego permitiremos el uso de la aplicacion sin necesidad de registro, aunque el usuario tendra que presentar cierta informacion para evitar falsas citas al taller.
Para evitar que la gente se pierda en la parte mecanica de la aplicacion, intentaremos ser lo mas generales posible, aunque habilitaremos una textarea opcional para que puedan precisar la averia que han sufrido, y asi que el taller tenga mas informacion sobre la averia, permitiendo fijar fechas mas concretas.
No vamos a tener en cuenta la opcion de pagar a traves de la aplicacion, puesto que la mayoria de personas que completaron la encuesta respondieron que no suelen pagar a traves del movil.
Creemos que es importante poder filtrar los talleres en la lista de talleres, para poder encontrar el que mas se adecue a lo que el cliente busque.
Los talleres que quierean aparecer en la aplicacion deberan registrase en la aplicacion para poder aparecer.
A la hora de concretar las citas, dividiremos el proceo en tres subprocesos pequeños para no abrumar con excesiva informacion al cliente. Ademas evitaremos que el cliente salga de la aplicacion utilizando los minimos datos personales posibles(solo los indispensables).
A la hora de coger una fecha, al cliente solo le apareceran las citas que el taller ha marcado como disponible. Asi evitamos que lleguen demasiados pedidos a la vez al taller, intentando asi que no se sature.
En la pantalla de seleccion de coche, dispondremos de desplegables para evitar que el usuario cuele informaciones falsas.
En el ultimo paso, hemos decidido mostrar un sumario de todos los datos de la cita, para que el usuario la confirme, aunque tambien tiene la posibilidad de editar los datos anteriores. Tambien en este paso tendra que dejar datos personales que le identifiquen, para facilitar el trabajo al taller y corroborar que la cita no sea falsa.

***
# Justificacion del diseño de la aplicacion para la parte profesional

## Extraccion requisitos 

 - Interfaz facil con la mayor informacion posible.
 - Alta usabilidad en pequeñas porciones de tiempo
 - Posibilidad de convertir la agenda de la aplicacion, en la agenda oficial del taller.


## Justificacion del diseño de la parte profesional

Como los clienes nos pidieron una interfaz con mucha informacion, decidimos que teniamos que intentar meter toda la informacion en una sola pantalla, para evitar que un mecanico, con poco tiempo, tenga que navegar entre distintas pestañas, para ver la informacion de los pedidos.
Es por eso que dispusimos de un calendario corto, de 2 semanas, en la que se mostraba todos los pedidos que se habian introducido en la aplicacion, con la informacion relevante del pedido en primera pagina. Ademas el encargado puede moverse entre los dias del calendario, para organizar el trabajo. 
Para intetar mostra informacion de otros dias, en cada dia apareccera un numero de pedidos que ya han sido asignados(no se ha podido realizar en el prototipo), asi como una pequeña notificacion encima de los dias, cuando entra un nuevo pedido al taller.
Los dias del calendario utilizan un codigo de colores(rojo,amarillo,verde) para que se pueda ver como de saturado esta el taller en cada dia( en el prototipo no se ha ppodido hacer).
Para asignar los nuevos pedidos a los mecanicos, se dispondr de una campana en la parte supeerior, que muestra os nuevos pedidos.
Tambien hemos añadido una funcion para añadir pedidos de forma manual( boton + de la parte superior), por si el taller quiere utilizar nuestro sistema como agenda definitiva.

