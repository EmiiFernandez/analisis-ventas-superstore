# 📊 Análisis de Ventas Retail - Superstore

## 📝 Descripción del Proyecto
Este proyecto simula un entorno de negocio real para analizar las ventas de un retail global. El objetivo fue transformar datos crudos en insights accionables para la toma de decisiones, identificando patrones de ventas, productos estrella y oportunidades de optimización.

## 🛠 Herramientas Utilizadas
* **Python (Pandas, Numpy):** Limpieza de datos, manejo de nulos y detección de outliers (IQR).
* **Visualización (Seaborn, Matplotlib):** Análisis exploratorio de distribuciones y tendencias.
* **SQL (SQLite):** Consultas de negocio para validar KPIs (Ventas totales, Top productos).
* **Looker Studio:** Dashboard interactivo para reporte final.

## 🔍 Hallazgos Clave
1.  **Estacionalidad:** Se detectó una tendencia creciente en las ventas hacia finales de año.
2.  **Outliers:** Existen ventas corporativas atípicas (>$20k USD) que, aunque escasas, impactan significativamente en la facturación.
3.  **Pareto:** Un pequeño grupo de productos tecnológicos genera gran parte del margen de ganancia.

## 📈 Visualización
Puedes ver el Dashboard interactivo completo 👉 
[Looker Studio](https://lookerstudio.google.com/reporting/a92aa016-395b-4c03-97ab-1d0f94a85d3b)

<div align="center">
  <img src="https://github.com/user-attachments/assets/83082a29-0c39-4380-819c-0b090f3d1ce8" alt="Dashboard de Ventas - Superstore Retail" width="700">
</div>
<br>

## 📂 Estructura del Repositorio
* `analisis_ventas.ipynb`: Realizado en Google Colab.
* `superstore_limpio_final.csv`: Dataset utilizado.
