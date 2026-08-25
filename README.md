# Caso de Estudio: Detección de Operadores Ineficaces en un Servicio de Telefonía Virtual
La empresa de telefonía virtual CallMeMaybe buscaba identificar operadores ineficientes para mejorar la atención al cliente. Implementé un proyecto de análisis exploratorio para detectar operadores con bajo rendimiento, utilizando múltiples indicadores operativos. 

Objetivos del proyecto
- Realizar un análisis exploratorio de datos para comprender el comportamiento operativo.
- Establecer métricas para identificar operadores ineficaces.
- Detectar operadores con bajo rendimiento.
- Validar hipótesis mediante pruebas estadísticas.

Herramientas utilizadas
- Jupyter Notebook
- Python (Pandas, Seaborn, SciPy).
- Pruebas estadísticas: prueba U de Mann-Whitney.
- Visualización: Matplotlib, Seaborn.

Criterios de ineficiencia
- Alta tasa de número de llamadas por operador.
- Promedio bajo de duración en llamadas.
- Promedio bajo de número de llamadas.
- Baja cantidad de llamadas salientes en operadores cuya función incluye realizarlas.

Análisis y resultados
- Se identificaron a 95 operadores con alta tasa de llamadas perdidas y con baja duración promedio de llamadas.
- Los operadores ineficientes pierden 47 de 100 llamadas.
- Los operadores con menor duración de llamadas son los que realmente podrían estar cortando llamadas prematuramente.

Conclusiones y recomendaciones
- Los operadores considerados ineficientes  representan el 8.7% del total de operadores.
- Poner a prueba a los empleados por un tiempo y ver si sus estadísticas mejoran.
- Se podrían revisar otros datos, por ejemplo, la antigüedad de estos operadores dentro de la empresa.



