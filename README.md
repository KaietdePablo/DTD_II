# DTD_II
Ejercicio 1: Factura Electrónica
El ejercicio consiste en crear un documento XML que represente una factura electrónica entre una librería y una biblioteca. La factura debe contener información como
el número y la fecha de emisión, así como los datos del emisor y del cliente. Además, debe incluir un detalle de los productos vendidos, especificando el código del
artículo, tipo, descripción, cantidad y precio de venta por unidad. Algunos productos pueden tener una oferta aplicada. La estructura debe ser validada mediante una
DTD que incluye restricciones sobre los elementos de la factura, como los datos del emisor y del cliente, los detalles de la factura, y la estructura de los productos
vendidos.

Ejercicio 2: Equipos de la NBA
Este ejercicio consiste en diseñar un documento XML que contenga información sobre equipos de la NBA, incluyendo sus títulos, posición en la clasificación y quinteto
titular. Cada equipo debe estar identificado por su nombre y especificarse a qué conferencia pertenece (Este u Oeste). La información de cada equipo incluye el número
de títulos ganados, su posición en la clasificación y el quinteto titular. La DTD define las restricciones sobre los elementos del documento, como el equipo, el
nombre del equipo, los títulos, la posición y el quinteto titular, así como la conferencia a la que pertenece cada equipo.

Ejercicio 3. Aeropuerto

Se debe crear un documento XML junto con una DTD externa que represente la información de un panel de vuelos de salida en el aeropuerto JFK con fecha 20/12/2013. La estructura del XML debe incluir el nombre del aeropuerto, la fecha y una lista de vuelos, cada uno con código, frecuencia diaria, origen, destino, hora de salida, hora de llegada y estado. El código de vuelo es un atributo único y obligatorio, mientras que el estado puede ser Cancelado (C), En hora (E) o Retrasado (R), con E como valor por defecto. Además, se debe incluir un elemento vacío para indicar si un vuelo es de salida. En la DTD, se especifica que debe haber al menos un vuelo y que la información debe aparecer en el mismo orden que en el panel
