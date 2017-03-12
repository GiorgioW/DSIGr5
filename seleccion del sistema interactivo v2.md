La idea del proyecto ha sufrido un cambio importante, por tanto, nos gustaría remodelar la explicación del sistema interactivo. En este documento de hecho se explica unicamente la vista del cliente, con lujo de detalles.

Se ha pensado que, limitar el funcionamiento de la aplicación a un ssolo taller no es una buena idea, normalmente cuando un usuario busca una aplicación para ayudarle con la interacción con un taller es porque no conoce ninguno.

Con esta idea se ha pensado en crear una aplicación que, aparte de crear el contacto entre usuario y taller, localice al cliente qué taller tiene más cercano en función de sus necesidades, es decir, el cliente debe geolocalizarse en la aplicación, decir qué problema en concreto tiene y será la aplicación la que le ofrezca un listado con los talleres cercanos que pueden responder a esta incidencia ordenados por ejemplo, por las valoraciones de otros usuarios. Esa es la idea general, vamos a detallar las pantallas:

La primera sería la pantalla de inicio, con una estetica muy cuidada, que enganche, y con simplemente el boton de localizar (que haría uso del gps) o, para dar más opciones, ingresar el codigo postal. En esta página NO se realiza ningun tipo de registro.
Pasariamos a la pagina principal, donde vienen recuadros con las distintas opciones que el cliente puede elegir. Se peude imaginar como una cuadricula de dos por dos que se pueda mover con un scroll. Cada recuadro es una opción padre que desmboca en opciones hijas, por ejemplo:

-revision -estetica -problemas de pintura -defectos en el interior -llantas

-mecanica facil -lunas -pinchazo -alineacion de ruedas -venta de componentes(Norauto, Midas...)

 -averías - motor - tranmision - accidentes - otro fallo mecanico

3.Una vez el cliente haya elegido una de las opciones que, por supuesto, no son fijas y pueden ser modificables o agrandar el abanico, se le ofrecerá un listado con los talleres de su zona, que pueden dar solución al problema ordenados por valoración. Cada fila del listado es pulsable y lleva a una pagina propia del taller. Aparecerán grisáceos como que no se peudene elegir, los talleres que estén ocupados (hayan superado su numero maximo de pedidos al dia que comentaremos posteriormente).

4.Esta pagina, consta de una foto del taller, en el fondo la ubicacion del mismo, su nombre y las distintas valoraciones con posibles opiniones que ha recibido por otros usuarios de la aplicación. Con un boton grande que sea, contactar.

5.Aquí sera donde el cliente deba rellenar dos formularios, sencillos y rapidos pero entendemos que necesarios. El primero es introducir su nombre (para que el taller sepa cómo dirigirse a él) e introducir su telefono (para que el taller pueda contactar con el cliente). Si estos datos ya se han introducido (sobre todo el telefono) la aplicación lo reconocerá y le sugiere informacion del siguiente "formulario" relativo a su coche, pero que podrá cambiar por si ha cambiaod de vehiculo o simplemente quiere introducir otro. Serán tres desplegables con la marca, el año y el año, de vital importancia para el profesional saber que tipo de coche va a tratar. Los desplegables son fijos, el cliente no podrá introducir informacion falsa. Se da a "continuar".

6.Ahora si visualiza un marcador como el de las cajas fuertes, rotativo, con dos campos, dia y hora. Se ha decidido dar soporte a 14 dias posteriores, por tanto el marcador día viene limitado. El marcador hora, se entiende de la cita, contendra las horas que el taller pone a disposicion del cliente. "Continuar"

7.Ultima pantalla, donde se le solicita al cliente si desea introducir algun comentario de la averia o el suceso que sea de vital importancia y un boton que sea el de confirmar cita, para el cliente la aplicacion termina aqui.

Ni que decir tiene que todas las pantallas tendran un boton de atras, para poder manejarnos perfectamente por la aplicacion.
