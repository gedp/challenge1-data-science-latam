# 📊 Desafío Alura Store - Análisis de Ventas 🛍️

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)

## 📝 Descripción del proyecto

¡Bienvenido al desafío Alura Store! 🎯 Este proyecto ayuda al señor Juan a decidir qué tienda de su cadena debe vender para iniciar un nuevo emprendimiento.

Mediante el análisis de datos de ventas, rendimiento y reseñas de las 4 tiendas de Alura Store, identificamos la tienda menos eficiente y presentamos una recomendación final basada en datos concretos. 📈

## 🎯 Objetivo principal

El objetivo es analizar 5 aspectos clave de cada tienda:
- 💰 Facturación total
- 🏷️ Categorías más populares
- ⭐ Evaluación promedio de clientes
- 📦 Productos más y menos vendidos
- 🚚 Costo promedio de envío

Y con esta información, recomendar cuál tienda vender para invertir en un nuevo negocio. 💡

## 🛠️ Tecnologías utilizadas

- ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) - Lenguaje de programación principal
- ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) - Manipulación y análisis de datos
- ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white) - Visualización de datos
- ![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white) - Entorno de desarrollo

## 🚀 Cómo ejecutar el proyecto

1. **Clona el repositorio** 📥:
    ```bash
    git clone [https://github.com/gedp/challenge1-data-science-latam.git](https://github.com/gedp/challenge1-data-science-latam.git)
    ```
2. **Abre el notebook** en Google Colab o tu entorno de desarrollo Python preferido.
3. **Ejecuta todas las celdas** para cargar los datos, realizar el análisis y generar las visualizaciones. ✨

## 📈 Análisis de datos y visualizaciones

Aquí encontrarás las visualizaciones clave generadas a partir del análisis de datos de las tiendas. Las imágenes se encuentran en la carpeta `graficas`.

### 💰 Facturación total por tienda

![Gráfico de Facturación](graficas/Facturacion_total_por_tiendas.png)
*Análisis:* Este gráfico de barras muestra la facturación total generada por cada una de las cuatro tiendas. La altura de cada barra representa el total de ingresos por ventas de cada tienda. Observamos que la Tienda 1 tiene la facturación más alta, seguida por la Tienda 2, Tienda 3 y finalmente la Tienda 4 con la facturación más baja. Esto indica la contribución directa de cada tienda a los ingresos generales.

---

### 🏷️ Categorías más populares por tienda

![Gráfico de Categorías Populares](graficas/categorias_populares.png)
*Análisis:* Estos gráficos de pastel (uno por tienda) muestran la distribución porcentual de las ventas entre las tres categorías de productos más populares en cada tienda. Cada porción del pastel representa el porcentaje de ventas que proviene de una categoría específica. Al comparar los gráficos, podemos ver qué categorías son las que más contribuyen a las ventas en cada tienda. En general, se observa que "Muebles", "Electrónicos" y "Juguetes" son consistentemente las categorías más vendidas en todas las tiendas, aunque el porcentaje de contribución puede variar ligeramente entre ellas.

---

### ⭐ Evaluación promedio por tienda

![Gráfico de Evaluación Promedio](graficas/Evaluacion_promedio.png)
*Análisis:* Este gráfico de barras compara la evaluación promedio de los productos en cada tienda, con una línea de referencia en 4.0. La altura de cada barra indica la calificación promedio que los clientes han dado a los productos de esa tienda (en una escala de 1 a 5). Una evaluación promedio más alta sugiere una mayor satisfacción del cliente. La línea de referencia permite visualizar rápidamente qué tiendas cumplen o superan una meta de 4.0. Observamos que las Tiendas 2 y 3 superan la meta, mientras que la Tienda 1 y Tienda 4 están ligeramente por debajo.

---

### 📦 Productos más y menos vendidos por tienda

![Gráfico de Productos Más y Menos Vendidos](graficas/productos_mas_vendidos.png)
*Análisis:* Estos gráficos de barras horizontales (uno por tienda) muestran los 5 productos más vendidos en cada tienda y la cantidad de ventas. La longitud de cada barra indica el volumen de ventas de un producto específico. Esto ayuda a identificar los productos estrella en cada ubicación. Al comparar entre tiendas, podemos ver si ciertos productos son consistentemente populares o si hay variaciones locales en las preferencias de los clientes.

---

### 🚚 Costo promedio de envío por tienda

![Gráfico de Costo de Envío Promedio](graficas/costo_promedio.png)
*Análisis:* Este gráfico de barras muestra el costo promedio de envío por tienda, con una línea de referencia para el promedio general. La altura de cada barra representa el costo promedio asociado al envío de un producto desde cada tienda. La Tienda 4 presenta el costo de envío promedio más bajo, mientras que la Tienda 1 tiene el más alto.

---

### 🔗 Relación entre precio y costo de envío

![Relación entre Precio y Costo de Envío](graficas/relacion_precio_envio.png)
*Análisis:* Este gráfico de dispersión muestra la relación entre el precio de un producto y su costo de envío para todos los datos combinados. Cada punto en el gráfico representa un producto individual. Observamos una clara tendencia lineal ascendente, lo que sugiere que, en general, los productos con precios más altos tienden a tener costos de envío más elevados.

---

### 📈 Distribución de calificaciones de productos

![Distribución de Calificaciones de Productos](graficas/calificaciones_de_productos.png)
*Análisis:* Este histograma muestra la frecuencia con la que aparecen las diferentes calificaciones de productos (de 1 a 5) en el conjunto de datos combinado. La altura de cada barra indica cuántos productos recibieron una calificación particular. Podemos observar que la barra más alta está en la calificación de 5, lo que sugiere que una gran parte de los productos reciben la máxima puntuación.

---

### 💡 Recomendación de la tienda a vender

![Recomendación de la Tienda a Vender](graficas/tienda_recomendada.png)
*Análisis:* Este gráfico de barras muestra un puntaje general de desempeño (normalizado entre 0 y 1) calculado a partir de la facturación, evaluación y costo de envío de cada tienda. La tienda con el puntaje más bajo está resaltada. La Tienda 1 tiene el puntaje más bajo, lo que la identifica como la candidata recomendada para vender según este análisis.

---

## 💡 Conclusiones y recomendación final

Basado en el análisis exhaustivo de las 4 tiendas, se recomienda **vender la Tienda 1**.

**Razones principales:**
1. Presenta el menor puntaje general de desempeño, indicando menor eficiencia.
2. Tiene la facturación más baja en comparación con las otras tiendas.
3. Registra la evaluación promedio más baja de los clientes.
4. Presenta los costos de envío más elevados.

Estos factores la posicionan como la tienda menos rentable y con mayor potencial de mejora o desinversión.

---
Hecho con ❤️ para el desafío de Alura Latam, por: [SynergyaTech](https://synergya.tech)
