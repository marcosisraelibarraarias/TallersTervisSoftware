Querido cliente.
Yo Marcos Israel Ibarra Arias me comprometo a entregar este software en el tiempo convenido.
Muchas gracias y adios.

Un operador usa el sistema para comprar y vender llaves.
El operador guarda las llaves compradas en lugares en el negocio que denominaremos almacenes.

Almacenes 
Cada almacén tiene ciertas características he detectado las siguientes:

Nombre
Es una frase con la que se identifica el almacén, por ejemplo: "Los Ganchos"
Localización (dentro del local)
        Es el lugar en el local en el que se encuentra el almacén, por ejemplo "En la pared izquierda"
Tipo de elementos
        El tipo de elementos que se pueden guardar en este almacén, se entiende que generalmente los elementos son mercancías, por ejemplo "Llaves" otro ejemplo: "Mercancía de diferentes tipos"
Cantidad de elementos
        La cantidad de elementos que este almacén puede contener.
Listado de elementos.
        Es una lista de los elementos que se encuentran en este almacén.
Cada elemento tiene las siguientes características.
Nombre
        El nombre del elemento.
Cantidad.
        Cantidad de elementos que se encuentbankran en este almacén.
Nombre del Proveedor
        El proveedor al que se le compro este elemento.
Precio de compra:
        El precio en que se compre este elemento
Precio de venta
         El precio en que se ofertan estos elembankentos al publico    

Identificador del tipo de elemento
          Es una frase palabra o numero que identifica únicamente al tipo de elemento que se esta almacenando, por ejemplo: Llave para Bougatti modelo num. 15,  otro ejemplo NS1002673A
Numero de serie
El identificador que el vendedor le da a el elemento, por ejemplo: NS1002673A 
Operaciones comunes:
        Movimiento entre almacenes, por ejemplo mover llaves del almacén general al almacén llamado "Gancho", de esta forma siempre se sabe en donde se encuentran los elementos

 Modulo de Ventas

Los empleados con permiso de vender productos podrán usar este modulo para buscar los productos y hacer listas o carritos de los productos que comprara el cliente que esta siendo atendido.
Cuando el carrito este listo y terminado el cliente elegirá el modo de pago: en efectivo o con tarjeta y se le imprimirá un ticket o una factura respectivamente.
Siempre que se haga una venta se imprimirá un ticket que se almacenara para el control interno de la empresa.
En cada venta se actualizara la cantidad de elementos restantes en los almacenes en los que se adquirieron productos.
Las ventas afectaran un listado de ventas, estas ventas incluirán un identificador de la venta (numero de  ticket) y la cantidad desglosada en las cantidades que desees por ejemplo venta neta e impuestos.
Respecto a la facturación hay varios módulos que pueden sugerirse, como la recepción y administración de las facturas generadas por los proveedores, estos módulos no los he incluido en el precio.
Las Compras se incluyen como la captura de los datos de cada almacén en el modulo de almacenes.
Habiendo identificado las características de los elementos a almacenar detectamos la necesidad de almacenar por separado los siguientes datos:

Los datos del Proveedor

Nombre corto o Alias
        Es un nombre corto con el que identificaremos a un proveedor especifico, es exclusivo de cada proveedor y por lo tanto debe ser único, por ejemplo: Ferrari, otro ejemplo "Ford Sucursal Patraix"

Nombre completo
        Es el nombre completo del proveedor puede ser por ejemplo la denominación comercial del proveedor por ejemplo: "Ford de España S.C."

Dirección
        La dirección del proveedor, es un campo sin formato es decir no diferencia por ejemplo el código postal de la calle lo que simplifica en la mayoría de los casos el almacenaje de las direcciones que generalmente es complicado.
Datos Extra
        Estos datos no han sido identificados, te pido por favor que identifiques que datos deseas mantener de tu proveedor, también puede ser simplemente un texto libre en el que se incluyan los datos que consideres necesarios sin diferenciarlos.

Usuarios


Estos datos deberán ser capturados en el sistema por empleados que pueden tener asignados diferentes deberes (roles), estos deberes pueden ser diferenciados como tipos de empleado o pueden ser indiferenciados es decir que cualquier usuario del sistema puede usar el sistema en su totalidad, esta funcionalidad se implementara a tu gusto.
En caso de que los usuarios se diferencien estos son los roles que propongo:
Administrador
        Puede dar de alta otros usuarios, puede bloquear el acceso a algunos de los de los usuarios del sistema, puede dar de alta cualquier elemento del sistema: Proveedores, Clientes, Mercancías, Almacenes etc.

Vendedor
        Es el empleado generalmente encargado del mostrador el que vende y programa las llaves, puede capturar los datos de los clientes y efectuar venta anónimas.

Comprador
        Es un empleado que puede ser el mismo que el vendedor y que compra las mercancías a los proveedores, puede capturar los datos de los proveedores.

Controlador de almacenes
        Es un empleado que puede usar el modulo de almacenes y ver la informacion de los productos es decir cambiar los prtoductos de almacen por lo que seria el encargado de mover fisicamente los productos entre almacenes, es decir por ejemplo ir a la bodega y sacar llaveros de las cajas para remplazarlos en los mostradores y despues actualizar las cantidades en la aplicación, en este caso el controlador no puede capturar ni modificar los datos solo moverlos entre almacenes.
Son los roles principales, a tu gusto se pueden incluir otros roles, por ejemplo repartidor o encargado de los almacenes.

Catálogos de tipos de elementos.


Me refiero a catálogos de tipos de elementos como colecciones de datos que ayudan a describir a los elementos ya sean Mercancías, Clientes, Proveedores, Empleados o Almacenes.
Por lo general son colecciones de características que por lo general solo incluyen un texto descriptivo y algún dato auxiliar.
Por ejemplo:
Que el texto descriptivo no se puede repetir en dos elementos, (hipotéticamente).
Que solo puede haber un empleado que sea el administrador del sistema.
Los catálogos que he detectado son:
Modulo de Contabilidad Basica.
Tipo de Llave
        Por ejemplo, Llave electrónica o Llave mecánica (o simple).
Tipo de empleado
        Contiene los nombres de los tipos de empleado que he descrito anteriormente: Administrador, Vendedor, Comprador.
Otros catálogos serán identificados según sean necesarios y a petición tuya también.

Modulo de Contabilidad Básica.


En este modulo se vera una lista de las ventas por numero de venta, fecha, precio y descripción.
También habrá una lista de los tickets emitidos y se podrán reimprimir siguiendo una búsqueda por diferentes parámetros como fecha o precio.


Otros módulos y funciones tendrán un costo adicional.
