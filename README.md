# Análisis de E-commerce — Olist

## Dataset

Elegí este Dataset de Kaggle llamado **"Brazilian E-Commerce Public Dataset by Olist"**, que contiene cerca de 100.000 órdenes reales de un e-commerce brasileño realizadas entre 2016 y 2018.

**Nota:** Los archivos CSV originales no están incluidos en este repositorio debido a su tamaño. Se pueden descargar desde la fuente original.

## Objetivo del proyecto

El objetivo de este proyecto es analizar el desempeño comercial y la eficiencia operativa de un e-commerce, utilizando información relacionada con las órdenes, clientes, productos, pagos, entregas y reseñas.

A partir de estos datos se busca identificar patrones y oportunidades de mejora principalmente en tres áreas:

* **Desempeño comercial:** analizar el revenue, el número de órdenes y el comportamiento de las ventas.
* **Eficiencia logística:** estudiar los tiempos de entrega y los retrasos de los pedidos.
* **Satisfacción del cliente:** analizar las calificaciones de los clientes y su posible relación con el desempeño de las entregas.

## Datos utilizados

Para el análisis se utilizaron las siguientes tablas del dataset:

* `olist_orders_dataset.csv` — información sobre las órdenes y sus fechas.
* `olist_customers_dataset.csv` — información geográfica de los clientes.
* `olist_order_items_dataset.csv` — productos incluidos en cada orden, precios y costos de envío.
* `olist_order_payments_dataset.csv` — información sobre los pagos realizados.
* `olist_order_reviews_dataset.csv` — calificaciones y comentarios de los clientes.
* `olist_products_dataset.csv` — información y características de los productos.

Estas tablas se relacionan principalmente mediante identificadores como `order_id`, `customer_id` y `product_id`, permitiendo integrar la información para realizar el análisis.

## Herramientas utilizadas

* **Python**
* **Pandas** — manipulación y transformación de datos.
* **Matplotlib / Seaborn** — visualización de datos.
* **Jupyter Notebook / Google Colab** — desarrollo del análisis.

## Proceso de análisis

El proyecto se desarrolla siguiendo las siguientes etapas:

1. Carga y exploración inicial de los datasets.
2. Integración de las diferentes tablas.
3. Limpieza y transformación de los datos.
4. Creación de nuevas variables para el análisis.
5. Cálculo de indicadores clave (KPIs).
6. Análisis exploratorio y visualización de resultados.
7. Identificación de patrones y oportunidades de mejora.
8. Conclusiones a partir de los resultados obtenidos.


