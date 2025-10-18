**📚 Análisis Predictivo de Precios en el Mercado Editorial Argentino**

**🎯 Descripción del Proyecto**

Proyecto de análisis exploratorio de datos (EDA) y predicción de precios en el mercado editorial argentino, utilizando el catálogo público de Yenny–El Ateneo. El objetivo es identificar los factores que influyen en la formación de precios de libros y desarrollar las bases para un modelo predictivo que permita optimizar estrategias de pricing dinámico.

**🔍 Análisis Realizado**

Análisis Univariado

Distribución de precios y características del catálogo

Análisis por categorías y géneros literarios

Estudio de variables físicas (páginas, encuadernación)


Análisis Bivariado

Correlación precio vs. número de páginas (r = 0.515)

Comparación de precios por categorías literarias

Relación entre tipo de encuadernación y precio


Análisis Multivariado

Matriz de correlaciones completa
Identificación de variables con mayor poder explicativo
Segmentación de mercado mediante clustering (K-Means)
Análisis de interacciones entre variables

**📈 Principales Hallazgos**

**🔹 Variables más influyentes en el precio:**

Editorial (correlación: 0.705)

Número de páginas (correlación: 0.515)

Género literario (correlación: 0.462)



**🔹 Insights clave:**

La editorial es el factor más determinante en el precio

Existe relación directa entre páginas y precio, pero no lineal

Se identificaron nichos de mercado con oportunidades comerciales


**🛠️Lenguaje:**

Python 3.x


**Librerias Utilizadas:**

**Manipulación de Datos:**

pandas - Para cargar, limpiar y manipular el DataFrame

numpy - Para operaciones numéricas y cálculos estadísticos


**Visualización:**

matplotlib - Creación de gráficos base

seaborn - Visualizaciones estadísticas (pairplot, heatmap, boxplots)
