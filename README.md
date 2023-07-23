# PowerBI-Dashboards

## Dashboard - Sales (Ventas)
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

## Dashboard - Manufacturing (Producción)
![Alt text](image.png)
El Panel de Producción ofrece una serie de métricas fundamentales para análisis y toma de decisiones eficientes. Las principales métricas incluidas son:

Horas Productivas: Esta métrica registra el total de horas en que la producción estuvo activa y operacional, incluyendo el tiempo de funcionamiento de las máquinas y la actividad del equipo de producción.

Horas Paradas: A través de una medida específica, se registran las horas en que la producción fue interrumpida, lo que posibilita la identificación de las causas y la búsqueda de soluciones para minimizar el tiempo de inactividad.

Horas de Disponibilidad: Esta medida se calcula a partir de la información de "Horas Productivas" y "Horas Paradas", proporcionando una visión clara del tiempo neto de producción y su efectiva utilización.

Cantidad Producida: Con base en una medida personalizada, se registra el número total de unidades o productos fabricados durante el período analizado, facilitando el seguimiento de la productividad.

Cantidad Rechazada: Utilizando medidas específicas, se registran las unidades o productos rechazados durante la producción, lo que permite el análisis de los factores que afectan la calidad.

Calidad: Esta métrica compleja fue creada para evaluar la excelencia de los productos fabricados, incluyendo tasas de defectos y otras informaciones relevantes para garantizar la calidad de los productos entregados a los clientes.

El panel cuenta con dos filtros que permiten el análisis de los datos de acuerdo con el operador responsable y el mes específico. Esto proporciona una visión segmentada y detallada del desempeño de la producción, permitiendo identificar variaciones y tendencias a lo largo del tiempo y entre diferentes operadores.

Para visualizar las horas productivas por mes, se ha creado un gráfico de área, que posibilita la observación de las variaciones en el tiempo de producción a lo largo de los meses. Además, se han incluido dos gráficos "speedy" para presentar porcentajes importantes: la disponibilidad (horas productivas / horas trabajadas) y la calidad (cantidad producida / cantidad producida + cantidad rechazada). Estos gráficos facilitan que el equipo de gestión comprenda la eficiencia del tiempo de producción y la eficacia general en relación a la calidad.
## Dashboard - RH
## Dashboard - Financial
