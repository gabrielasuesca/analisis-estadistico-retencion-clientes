# Análisis estadístico de retención de clientes

## Descripción del proyecto
Este proyecto analiza factores asociados al abandono de clientes (*customer churn*) en una base pública de ejemplo de una empresa de telecomunicaciones. Se utilizan estadísticas descriptivas, visualizaciones y pruebas de hipótesis para comparar clientes que permanecieron con aquellos que abandonaron el servicio.

## Objetivo
Describir la proporción de abandono y evaluar su asociación con el tipo de contrato y el método de pago, además de comparar la antigüedad y los cargos mensuales entre los grupos.

## Fuente de datos
La base utilizada es **Telco Customer Churn**, publicada en el repositorio de IBM:
https://github.com/IBM/telco-customer-churn-on-icp4d

El notebook descarga la base desde la fuente indicada en el código. Se requiere conexión a internet para ejecutar esa parte.

## Archivos del proyecto
- `Analisis_Estadistico_Retencion_Clientes_Colab.ipynb`: notebook con el código, la preparación de datos, las visualizaciones y las pruebas estadísticas.
- `Informe_Analisis_Estadistico_Retencion_Clientes_APA7.docx`: informe académico en formato Word, estructurado con base en APA 7.ª edición.
- `README.md`: descripción del proyecto e instrucciones de ejecución.
- `requirements.txt`: bibliotecas de Python utilizadas.

## Herramientas
- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Google Colab / Jupyter Notebook

## Cómo ejecutar el notebook
1. Abre Google Colab: https://colab.research.google.com/
2. Selecciona **Archivo > Subir notebook**.
3. Carga `Analisis_Estadistico_Retencion_Clientes_Colab.ipynb`.
4. Ejecuta las celdas en orden, desde la primera hasta la última.
5. Verifica las tablas, gráficos y resultados de las pruebas estadísticas.

## Métodos estadísticos incluidos
- Estadística descriptiva y tablas de frecuencias.
- Tablas de contingencia.
- Pruebas chi-cuadrado de independencia.
- V de Cramér como medida de asociación.
- Pruebas U de Mann–Whitney.
- Prueba de Levene para comparar variabilidad.

## Consideraciones
Los resultados describen asociaciones estadísticas en el conjunto de datos analizado y no demuestran relaciones de causa y efecto. La base es un conjunto público de ejemplo y no necesariamente representa a todas las empresas de telecomunicaciones.

## Autoría académica
Trabajo elaborado para la asignatura **Diseño Estadístico para Datos Estructurados y no Estructurados**, Universidad de Cundinamarca.

**Estudiante:** Gabriela Suesca Castillo  
**Docente:** Paul Alexander Díaz Montaña
