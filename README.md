# Cineplus2
Aplicaciòn bàsica de cobro para  un cine creada en python con wxglade. Consta de 4 ventanas:inicio de sesiòn sin conexion a BD, taquilla, dulcerìa y ticket.
creada por almno de Baquillerato.

Ventana Inicio de Sesiòn (Login)
--El sistema debe tener una pantalla de inicio de sesiòn.
--Para este proyecto, el inicio de sesiòn se harà con datos preestables (por ejemplo, usuario: cajero y contraseña:12345). No es necesario implementar una base de datos.
 Venta de Boletos (Taquilla)
 --El sistema debe permitir al empleado seleccionar la pelìcula, el horario y la sala.
 "IT" 14:00, 17:00, 20:00 sala 1
 "La Hermanastra" 13:30, 16:30, 19:30 sala 2
 "Arriety" 15:00, 18:00, 21:00 sala 3 

 --se debe especificar la cantidad de boletos.
 --se debe indicar si los boletos son para adultos o para menores de edad, ya que el precio es diferente (adultos $90, menores de edad $80).
 --Al finalizar la selecciòn de boletos, el sistema debe mostrar un resumen de los boletos adquiridos y calcular el subtotal de la taquilla.

 ventana de productos (Dulcerìa)
 --El sistema debe permitir al empleado seleccionar los productos que el cliente desea comprar en la dulcerìa.
 --Los productos son:
 .Bàsico($75):palomitas chicas + refresco chico.
 .Cuate($130):palomitas medianas + 2 refrescos chicos.
 .Familiar($200):palomitas grandes+ 3 refrescos chicos.
 Productos individuales:
 .Palomitas:chicas,medianas y grande
 .Refrecos:seleccionar tamaño, sabor y cantidad.

--Se debe especificar la cantidad de cada producto o paquete.
--El sistema debe calcular automàticamente el subtotal de la dulcerìa segùn los productos seleccionados.
--El sistema debe mostrar un resumen de los productos adquiridos(por ejemplo:"2 Bàsico, 1 Familiar, 3 Palomitas Medianas,2 Refrescos Grandes sabor coca cola").
--El sitema debe permitir limpiar los datos para iniciar una nueva selecciòn.
--Al finalizar la compra de dulcerìa, el sistema debe permitir continuar a la siguiente ventana.

ventana de Boletos (Ticket)
--El sistema debe mostrar  un resumen detallado de la compra de boletos, incluyendo:
.Nombre de la pelicula, sala y horario seleccionado.
.Cantidad de boletos para adultos y para menores de edad.
.El subtotal correspondiente a la selecciòn de taquilla.
--El sistema debe mostrar un resumen detallado de los productos de la dulcerìa adquiridos,incluyendo
.Lista de combos y productos individuales con sus respectivas cantidades.
.El subtotal correspondiente a la selecciòn de dulcerìa.
--El sistema debe calcular y mostrar el total general de la compra de (suma del subtotal de taquilla y dulcerìa).
--El sistema debe ofrecer al empleado las opciones de "Cancelar" la transacciòn o "Finalizar" la compra.
