# proyecto_sqlserver_dsrp

Una tienda minorista requiere un sistema para gestionar sus procesos de ventas, inventario y pagos de manera eficiente. Este sistema permitirá registrar y consultar información sobre los productos, las categorías de productos, los empleados, las ventas realizadas, los detalles de cada venta, los pagos efectuados y los métodos de pago utilizados.

## Requerimientos:

### Productos y Categorías:
- Los productos deben estar clasificados por categorías (como ropa, electrodomésticos, alimentos, etc.).
- Se debe almacenar información básica de los productos, como su nombre, precio y stock disponible.
- Cada producto debe estar asociado a una categoría.

### Empleados y Usuarios:
- Se debe registrar información sobre los empleados que trabajan en la tienda, como su nombre, apellido, correo electrónico y teléfono.
- Cada empleado tiene un usuario en el sistema, con un nombre de usuario y clave de acceso para realizar operaciones en el sistema.
- Los usuarios pueden tener estados (activo o inactivo) según su nivel de acceso al sistema.

### Ventas:
- Cada venta debe registrar el cliente (nombre o razón social), el empleado que la realizó, la fecha y el importe total.
- Cada venta puede incluir varios productos (detalles), especificando las cantidades, precios y subtotales.
- El sistema debe calcular automáticamente el subtotal y el importe total de la venta.

### Detalles de Venta:
- Cada venta debe desglosarse en sus detalles, asociando los productos vendidos, las cantidades y los precios individuales.
- Los detalles deben permitir identificar cuánto de un producto específico fue vendido en cada transacción.

### Pagos y Métodos de Pago:
- Los clientes pueden realizar pagos por las ventas realizadas, ya sea en una sola transacción o mediante múltiples pagos.
- Cada pago debe registrar la fecha, el importe abonado y los detalles adicionales (como notas u observaciones).
- Los métodos de pago pueden incluir efectivo, tarjeta de crédito, transferencia bancaria, entre otros. Cada método de pago debe estar previamente definido en el sistema.

## Modelo Entidad Relación
![tarea1_mco](https://github.com/user-attachments/assets/31cf4203-7dda-4bbe-a5c0-a0d8290d8501)

## Modelo Lógico
![tarea2_mco](https://github.com/user-attachments/assets/10beccdb-ec38-4f8a-abef-bfa25d13f46b)
