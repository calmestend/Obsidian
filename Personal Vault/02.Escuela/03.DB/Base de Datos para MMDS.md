# Requerimientos
- El administrador en el sistema podra:
	- Dar de alta productos y categorias de productos.
	- Dar de alta clientes nuevos.
	- Consultar las ventas por periodos@.
- El cliente en el sistema podra:
	- Visualizar un catalogo de productos.
	- Realizar compras de diversos productos.
	- Consultar las compras que ha realizado y mostrar de manera ordenada.

# Entidades
> Producto
- ID
- Precio
- Cantidad
- Descripción
- Calificación

> Categoría
- ID
- Nombre
- Existencia

> Usuario
- ID
- Nombre
- Direccion
- Telefono
- Correo
- Contrasena

> Venta
- ID
- Metodo de pago
- Costo
- Cantidad
- producto_venta (garantia) && (envio)

> Agenda
- ID
- Fecha
- Disponilibidad
- Garantia
- Motivo 

> Bodega
- ID
- Direccion