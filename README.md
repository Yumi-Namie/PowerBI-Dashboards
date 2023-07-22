# PowerBI-Dashboards

##Dashboard Financero
![image](https://github.com/Yumi-Namie/PowerBI-Dashboards/assets/109878163/c62a0e13-96a2-4167-a60a-cfeeac463a15)

Visualización interactiva de datos que muestra información sobre la parte de ventas de produtos. Tomé un archivo de Excel con más de 2000 filas que contenía columnas de:

- fecha
- producto
- categoría
- precio unitario
- costo unitario
- marca
- cantidad de ventas
- país y continente en una misma columna
- nombre del cliente con el apellido separado por una coma del primer nombre.

Utilizando <b>Power Query</b>, eliminé una columna vacía, ajusté el nombre del cliente con 'split column' para separarlo en dos columnas de país y continente utilizando 'Column from Example', y creé una nueva columna utilizando 'add column multiply' para calcular el total de facturación.

El objetivo principal de este tablero era mostrar el total de facturación, los productos más vendidos (Top N 1), la facturación por marca y la facturación por mes.

