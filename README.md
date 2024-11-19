# Examen-1-ETS
## Ejercicio 1 Tienda de Comercio Electrónico

Una tienda en línea necesita un sistema que permita a los clientes comprar productos a través de un sitio web.

Como parte de los requisitos funcionales, el sistema debe incluir los siguientes procesos:

1. El cliente puede **navegar por el catálogo** para visualizar los productos disponibles.
2. Una vez que el cliente selecciona un producto, tiene la opción de **colocar el artículo en el carrito**.
3. Para completar la compra, el cliente debe realizar las siguientes acciones:
   - **Informar su dirección de envío** (extensión opcional si ya tiene una dirección registrada).
   - **Completar los datos de su tarjeta de crédito** para el pago.
4. Durante la transacción, el sistema debe:
   - **Verificar los datos de la tarjeta de crédito** del cliente.
   - **Facturar la compra** exitosamente.
   - **Enviar un e-mail de confirmación** con los detalles de la compra al cliente.

El sistema también debe mostrar qué partes de este flujo son obligatorias y cuáles son opcionales. A partir de los requerimientos indicados:

Diseña un diagrama de casos de uso que represente las interacciones entre el cliente, el sistema y los `casos de uso necesarios`y los `actores implicados` para realizar una compra. Usa relaciones como `<<include>>` y `<<extend>>` según corresponda.

<img src="Ejercicio 1 Tienda de Comercio Electrónico.drawio.png">

## Ejercicio 2: Realiza la especificación de Casos de Uso

Realiza la especificación de casos de uso de la siguiente imagen.

<img src="images/alguiler-pelicula-cu.png">

## Actores

Cliente
Descripción: Usuario del sistema VIDEOMAX

Proveedor
Descripción: Proveedor de película de VIDEOMAX

Administrador Videomax:
Descripción: Usuario que controla todas las acciones de VIDEOMAX

# Operaciones por actor

## Cliente

i Pone sus datos personales.

ii Puede alquilar películas.

iii Puede reservar películas.

iv Puede seleccionar películas.

v Puede devolver películas.

## Proveedor

i Distribuye películas según existencias.

## Administrador Videomax

i Registrar clientes.

ii Registrar alquileres.

iii Registrar reservas.

iv Registrar películas.

v Actualiza los proveedores.



|  Actor | Cliente  |
|---|---|
| Descripción  | _Usuario del sistema VIDEOMAX_  |
| Características  | __ |
| Relaciones | _Registrar datos personales, alquilar películas, reservar películas_  |
| Referencias | _Proporciona datos personales,alquila película, reserva película, devuelve película, seleccionar película, registra película_ |
|  Notas |  __ |
| Autor  | _Santiago Ruiz Martín_ |
|Fecha | _18/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |


|  Actor | Proveedor |
|---|---|
| Descripción  | _Proveedor de película de VIDEOMAX_  |
| Características  | __ |
| Relaciones | _Abastecer películas_  |
| Referencias | _Abastece películas según existencias_ |
|  Notas |  __ |
| Autor  | _Santiago Ruiz Martín_ |
|Fecha | _18/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |


|  Actor | Administrador Videomax|
|---|---|
| Descripción  | __  |
| Características  | __ |
| Relaciones | _Hace registros de personas, hace registros de alquileres, registro de reserva, registro de películas y actuliza los proveedores_  |
| Referencias | _Registra los clientes, registra alquiler,registra reserva, registra película, actualiza proveedor_ |
|  Notas |  __ |
| Autor  | _Santiago Ruiz Martín_ |
|Fecha | _18/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
