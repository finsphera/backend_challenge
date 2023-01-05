# backend_challenge

1) Crear con graphql, nodejs y las herramientas que consideres necesarias una API con los schemas de (cada esquema debe de contar con los atributos necesarios para cumplir con las evaluaciones).

- Vendedores,
- Compradores,
- Productos (Productos que el vendedor tiene a la venta),
- Órdenes (Orden de compra que genera la aplicación al momento de vender 1 o más productos de uno o varios vendedores al comprador).

Se evaluará:
- Documentación del código.
- Utilización de relaciones uno a uno, uno a varios, varios a varios.
- Utilización de enums, types, datos obligatorios, filtros etc.
- Generar las mutaciones, queries para tener el CRUD de Orden de compra, vendedor o comprador y producto.
- Generar los queries para realizar filtros, ordenamientos por: 
- órdenes completadas (cuando la orden cuenta con 1 o mas items comprados y que ya han sido entregados al comprador) 
- Ordenes canceladas
- Ordenes fuera de tiempo (cuando uno o varios items de la orden de compra se ha pasado de la fecha de entrega prometida)
- Vendedor con evaluaciones mayores a 4 de 5 estrellas.
- Solo mostrar la información personal del Vendedor o Comprador.
- Producto más vendido.
- Producto con mayor calificación


2) Crear una función lambda (AWS) que integre una API gratuita, para recibir datos y devolverlos.

3) Crear una funcion lambda que lea de un bucket de S3 un CSV y devuelva los datos del csv (Plus).

Tiempo de entrega máximo 5 días. 
