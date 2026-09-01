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



# Caso de estudio SQL: Análisis del Comportamiento de Lectores Durante la Pandemia
Durante la pandemia por COVID-19, el cambio en los hábitos sociales impulsó el crecimiento del consumo de libros y el desarrollo de nuevas plataformas para lectores. En este proyecto, trabajé con una base de datos relacional de una startup del sector editorial que busca lanzar un nuevo producto digital para lectores y lectoras. 

Objetivos del proyecto
- Explorar base de datos para entender el comportamiento de lectura y calificación.
- Ejecutar consultas SQL para extraer métricas clave sobre:
  Publicaciones recientes
  Participación de usuarios
  Rendimiento de autores y editoriales
- Generar insights que fundamenten decisiones de producto y estrategia.

Herramientas utilizadas
- SQL(PostgreSQL)
- Jupiter Notebook
- Python (Pandas para impresión de resultados)

Consultas realizadas y hallazgos clave
Se identificó un volumen creciente de publicaciones tras el año 2000, los títulos más frecuentes fueron los modernos.
Algunos títulos podrían ser considerados "Joyas ocultas" ya que los altamente calificados no eran los más populares en número de reseñas.
La identificación de la editorial líder en publicaciones extensas, es útil para recomendaciones dentro de la app o alianzas comerciales.
Para destacar contenido de calidad, se realizó un ranking confiable de autores con buena recepción crítica.
Los usuarios que escriben más reseñas de texto que el promedio podrían ser creadores de contenido.

Conclusiones
Se podrían desarrollar estrategias para personalizar el contenido de acuerdo a los metadatos editoriales, calificaciones y reseñas.
Los libros con una calificación promedio alta no cuentan con tantas reseñas de usuarios, esto podría indicar que no son tan populares como los que tienen más reseñas.

