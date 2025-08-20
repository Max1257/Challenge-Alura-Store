# 📊 Análisis de Tiendas – Alura Store

## 📌 Descripción

Este README documenta el proyecto **Alura Store** (Desafío N°1). El notebook principal contiene el análisis exploratorio de ventas, calificaciones y costos por tienda para ayudar al Sr. Juan a tomar la decisión de qué tienda vender.


---

## 🎯 Propósito del análisis

El propósito del análisis es:

- Comparar desempeño entre tiendas (ingresos, cantidad de ventas y calificaciones).
- Identificar la tienda con mayor potencial de rentabilidad para venta.
- Detectar categorías y productos más y menos vendidos para decisiones de inventario.
- Evaluar el efecto del coste de envío sobre las ventas y la satisfacción del cliente.


---

## 📈 Ejemplos de gráficos e insights obtenidos

- Ingresos totales por tienda (bar chart) — identifica tiendas con mayor y menor aporte a los ingresos.

- Ventas por categoría (bar chart) — muestra categorías más vendidas.

- Top N productos más vendidos (bar chart) — detecta los productos que concentran mayor volumen.

- Distribución de calificaciones (histograma/violin) — evalúa satisfacción por tienda.

- Coste de envío vs Ingresos (scatter plot) — revisa correlación entre envío y ventas.


Cada gráfica en el notebook incluye una interpretación y, cuando aplica, un insight concreto (por ejemplo: 'La tienda X genera el 40% de los ingresos, por lo que es la candidata menos recomendable para vender si se busca liquidez rápida').


---

## ▶️ Instrucciones para ejecutar el notebook

1. Coloca los archivos de datos en `data/raw/`.

2. Crea y activa un entorno virtual (recomendado):

```bash
python -m venv venv
# windows (PowerShell)
venv\Scripts\Activate.ps1
```

3. Instala dependencias:

```bash
pip install -r requirements.txt
```

4. Ejecuta Jupyter Lab/Notebook:

```bash
jupyter lab
# o
jupyter notebook
```

5. Abre `notebooks/Desafio_N°_1_Max_Gutierrez_Flores.ipynb` y ejecuta las celdas de arriba a abajo.


**Notas útiles dentro del notebook**:

- Librerías importadas en el notebook: `matplotlib.pyplot, pandas, reduce, seaborn`.


---

## 🧾 Dependencias

- python >= 3.8
- pandas
- numpy
- matplotlib
- seaborn
- jupyterlab / notebook


---
