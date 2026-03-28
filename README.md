# 📚 Análisis Predictivo de Precios — Mercado Editorial Argentino

## Descripción

Proyecto de análisis exploratorio (EDA) y predicción de precios en el mercado editorial argentino, utilizando el catálogo público de Yenny–El Ateneo. El objetivo es identificar los factores que determinan la formación de precios de libros y sentar las bases de un modelo predictivo orientado al pricing dinámico.

Los datos fueron obtenidos mediante scraping del catálogo público de Yenny–El Ateneo y procesados en Python con Google Colab.

## Objetivos

- Identificar las variables con mayor influencia sobre el precio de los libros.
- Segmentar el mercado editorial por categorías, géneros y editoriales.
- Desarrollar un modelo predictivo de precios como base para estrategias de pricing.

## Dataset

Catálogo de libros obtenido del sitio público de Yenny–El Ateneo, con variables como editorial, género literario, número de páginas, tipo de encuadernación y precio.

## Metodología

1. **Análisis Univariado**: distribución de precios, análisis por categorías, géneros y características físicas del libro.
2. **Análisis Bivariado**: correlación precio vs. número de páginas (r = 0.515), comparación por categorías y encuadernación.
3. **Análisis Multivariado**: matriz de correlaciones, segmentación con K-Means e identificación de variables con mayor poder explicativo.
4. **Modelado**: bases de un modelo predictivo de precios con las variables más relevantes.
5. **Analisis y visualización de Resultados**: Revision de metricas y visualizacion de los resultados para corroborar el funcionamiento del modelo.

## Principales hallazgos

| Variable | Correlación con precio |
|---|---|
| Editorial | 0.705 |
| Número de páginas | 0.515 |
| Género literario | 0.462 |

- La editorial es el factor más determinante en el precio final.
- La relación entre páginas y precio existe pero no es lineal.
- Se identificaron nichos de mercado con oportunidades comerciales diferenciales.

## Tecnologías utilizadas

| Herramienta | Uso |
|---|---|
| Python 3.x | Lenguaje principal |
| pandas / numpy | Manipulación y cálculos estadísticos |
| matplotlib / seaborn | Visualizaciones (heatmap, boxplots, pairplot) |
| scikit-learn | Clustering K-Means y modelado |
| Google Colab | Entorno de desarrollo |

## Estructura del repositorio
```
├── Informe_predictivo_mercado_editorial.ipynb   # Notebook principal
├── publicaciones_libros_actualizado.csv         # Dataset procesado
└── Informe.pdf                                  # Informe ejecutivo del análisis
```

## Cómo ejecutar el proyecto

1. Clonar el repositorio:
```bash
   git clone https://github.com/pragamarcos/Informe_predictivo_mercado_editorial.git
```
2. Instalar las dependencias:
```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
```
3. Abrir `Informe_predictivo_mercado_editorial.ipynb` en Google Colab o Jupyter Notebook y ejecutar las celdas en orden.

## Contacto

[LinkedIn](https://www.linkedin.com/in/marcospraga/) · [GitHub](https://github.com/pragamarcos)
