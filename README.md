# Análisis de Tiendas - Colab

## Descripción
Este proyecto es un análisis de datos de ventas de cuatro tiendas diferentes. El objetivo es determinar cuál de las tiendas representa la mejor opción para enfocar las ventas del Sr. Juan, considerando ingresos, satisfacción del cliente, productos más y menos vendidos, y costos de envío.  

El análisis se realiza en **Google Colab** utilizando Python y librerías como `pandas`, `matplotlib` y `seaborn`. El proyecto incluye cálculos de métricas clave y visualizaciones para facilitar la interpretación de los datos.

## Objetivos
- Calcular los **ingresos totales** de cada tienda.  
- Analizar la **cantidad de productos vendidos por categoría**.  
- Calcular la **calificación promedio de los clientes** por tienda.  
- Identificar los **productos más y menos vendidos**.  
- Calcular el **costo de envío promedio** por tienda.  
- Generar **gráficos** para visualizar los insights más importantes.  
- Recomendar la tienda más adecuada para enfocar las ventas.

## Estructura del Colab
1. **Carga de datos:** Se leen archivos CSV de cada tienda desde URLs públicas.  
2. **Análisis de ingresos:** Suma de la columna `Precio` para cada tienda.  
3. **Análisis por categoría:** Conteo de productos vendidos por cada categoría.  
4. **Calificaciones promedio:** Promedio de la columna `Calificación`.  
5. **Productos más y menos vendidos:** Identificación de productos top y bottom por tienda.  
6. **Costo de envío promedio:** Promedio de la columna `Costo de envío`.  
7. **Visualizaciones:**  
   - Barra de ingresos totales por tienda.  
   - Pastel o barras de productos por categoría.  
   - Scatter de precio vs calificación.  
8. **Informe final:** Síntesis de hallazgos y recomendación de la tienda más adecuada.

## Cómo usar
1. Abre el archivo en **Google Colab**.  
2. Ejecuta cada celda paso a paso.  
3. Observa los resultados impresos y los gráficos generados.  
4. Al final, consulta el **Informe Final**, que resume todos los insights y la recomendación.

## Librerías utilizadas
- `pandas`  
- `matplotlib`  
- `seaborn`  

## Datos
Los datos provienen de archivos CSV alojados en GitHub, correspondientes a las cuatro tiendas:  
- Tienda 1  
- Tienda 2  
- Tienda 3  
- Tienda 4  

## Conclusión
Tras el análisis, se recomienda que el Sr. Juan enfoque sus ventas en **Tienda 1**, debido a su mayor ingreso total y productos con alta demanda, considerando también estrategias para mejorar la satisfacción del cliente y optimizar los costos de envío. Como alternativa secundaria, la **Tienda 3** es atractiva por su alta calificación promedio y buen desempeño de ventas.
