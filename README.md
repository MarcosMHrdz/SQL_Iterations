![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Laboratorio | Iteraciones SQL

En esta práctica de laboratorio, continuaremos trabajando en la base de datos de alquiler de películas [Sakila](https://dev.mysql.com/doc/sakila/en/).

### Instrucciones

Escriba consultas para responder las siguientes preguntas:

- Escribe una consulta para saber cuál es el negocio total realizado por cada tienda.
- Convertir la consulta anterior en un procedimiento almacenado.
- Convierta la consulta anterior en un procedimiento almacenado que tome la entrada para `store_id` y muestre las *ventas totales de esa tienda*.
- Actualizar la consulta anterior. Declare una variable `total_sales_value` de tipo float, que almacenará el resultado devuelto (del monto total de ventas de la tienda). Llame al procedimiento almacenado e imprima los resultados.
- En la consulta anterior, agregue otra variable `flag`. Si el valor total de ventas de la tienda es superior a 30.000, etiquételo como "bandera_verde", de lo contrario, etiquételo como "bandera_roja". Actualice el procedimiento almacenado que toma una entrada como `store_id` y devuelve el valor de ventas total para esa tienda y el valor de la bandera.
