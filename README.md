# Análisis de Ventas Minoristas con Pandas, Matplotlib y Seaborn

## Descripción

Este proyecto realiza un análisis exploratorio de un conjunto de datos de ventas minoristas utilizando Python. Se emplean las bibliotecas Pandas para la manipulación de datos, Matplotlib para la creación de visualizaciones y Seaborn para el análisis gráfico avanzado.

El objetivo es identificar patrones, tendencias y relaciones entre variables como ventas, beneficios, categorías de productos y costos de envío mediante diferentes tipos de gráficos.

## Tecnologías utilizadas

* Python 3
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

## Estructura del proyecto

```text
Visualizacion-datos/
│
├── superstore_dataset2012.csv
├── analisis_ventas.ipynb
├── heatmap_correlacion.png
├── requirements.txt
├── .gitignore
└── README.md
```

## Análisis realizados

### 1. Exploración inicial de datos

* Carga del dataset.
* Inspección de registros.
* Identificación de tipos de datos.
* Verificación de valores nulos.
* Estadísticas descriptivas.

### 2. Preparación de datos

* Conversión de columnas de fechas.
* Verificación de tipos de datos.

### 3. Visualizaciones

* Histograma de distribución de ventas.
* Boxplot de beneficios por categoría.
* Gráfico de dispersión entre ventas y beneficios.
* Gráfico de regresión utilizando Seaborn.
* Mapa de calor de correlaciones.
* Subplots con resumen general del análisis.

## Principales hallazgos

* La mayoría de las ventas se concentran en montos bajos y medios.
* Existe una relación positiva entre las ventas y los beneficios.
* La categoría Technology presenta beneficios generalmente superiores.
* Furniture muestra una mayor variabilidad y algunos de los valores negativos más significativos.
* El análisis de correlación permitió identificar relaciones entre variables numéricas del conjunto de datos.

## Ejecución del proyecto

1. Crear y activar un entorno virtual:

```bash
python -m venv myenv
source myenv/bin/activate
```

2. Instalar dependencias:

```bash
pip install -r requirements.txt
```

3. Abrir Jupyter Notebook:

```bash
jupyter notebook
```

4. Ejecutar el archivo:

```text
analisis_ventas.ipynb
```

## Autor

Jeffrey Vasquez