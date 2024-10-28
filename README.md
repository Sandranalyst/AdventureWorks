Adventure Wors Cycles es una gran empresa multinacional   de fabricación que produce y distribuye bicicletas, piezas y accesorios para mercados comerciales en Norteamerica, Europa y Asia. La empresa tiene 500 trabajadores. 

Con este proyecto se va analizar las ventas y varios indicadores para obtener información para una toma de decisiones basadas en datos, que sea eficiente, óptima y que induzca a la acción, utilizando Power BI. La multinacional inicialmente no cuenta con estos indicadores.  Con Power Bi se logra proporcionar a los directivos e interesados entregar una vision integral y detallada de las operaciones, ventas y rendimiento financiero para la mejor toma de decisiones estratégicas y operativas.
Dentro de los objetivos organizacionales se tienen,
La optimización del proceso de toma de decisiones informadas y oportunas, que reduce el tiempo para el análisis de información, aumento en la precisión de toma de decisiones, mejora en la gestión de ventas y rendimiento financiero.
 Mediante la visualización de indicadores como ingresos, utilidades y COGS (Costo de los Bienes Vendidos) y margen de beneficio, la empresa puede identificar áreas de mejora en la cadena de suministro y operaciones de venta, lo que los lleva a ser más eficientes y a optimizar su margen de beneficio.
 
El análisis detallado por estado y ciudad permite identificar tendencias locales y segmentar sus estrategias de marketing y ventas.
La segmentación por producto permite identificar los mas rentable e identificar los que requieren ajustes , con el fin de optimizar el portafolio de productos de la empresa
La comparación en los periodos de ventas, gastos e ingresos genera una visión clara de las tendencias de crecimiento  y de las áreas que requieren atención, al igual que ajustar las estrategias de ventas.

Inicialmente  se conecta y limpian los datos de Adventure Works, se descargo la base de datos, se restauró en SQL server y se conectó con Power Bi.

se crea el modelo relacional y el Mokup del proyecto, con el fin de responder preguntas clave sobre el negocio relacionadas con ingresos, ventas, utilidades, costos  y distribución geográfica de clientes y productos. El diseño debe ser eficiente con el fin de optimizar el rendimiento y facilidad de análisis. 

se crearon medidas y columnas calculadas, comenzando con la utilización del lenguaje DAX para crear medidas y columnas calculadas con el fin de analizar ingresos, costos, gastos, ventas y otros indicadores clave. 
Se agregan columnas personalizadas como la de fecha corta, se deshabilita la carga de algunas tablas como ProductCategory, ProductSubcategory y Geography en Power Query para no hacer tan pesado e ineficiente el modelo. 

Como resultados principales se tienen:
Resumen General
El análisis de ventas ha revelado un crecimiento constante, aunque moderado, a lo largo del período evaluado. Además, se identificó un patrón estacional en las ventas, que sugiere la influencia de ciertos factores temporales o eventos en el comportamiento de compra de los clientes.
 Desempeño por Región
La región de Estados Unidos se destaca como el mercado de mayor rendimiento. Sus ventas contribuyen significativamente al incremento de las ventas totales, compensando otras áreas que muestran menor rendimiento. Esta región presenta una estructura de demanda sólida, lo que representa una oportunidad para implementar estrategias de optimización que puedan ser replicadas en otras regiones.

Análisis de Costos
Los costos operativos han mantenido una tendencia constante, lo que sugiere una eficiencia en el control de gastos a lo largo del tiempo. No obstante, es esencial monitorear estos costos en cada región para asegurar que el margen de beneficio no se vea afectado con el crecimiento en ventas proyectado.

Recomendaciones:
Dado el desempeño observado, es recomendable llevar a cabo un análisis más profundo en las siguientes áreas:
Categorías de Productos: Identificar los productos con mayor y menor demanda en cada región para evaluar su impacto en las ventas globales.
Canales de Distribución: Examinar el rendimiento de cada canal de venta (online, puntos de venta físicos, distribuidores) para entender mejor su contribución y optimización.
Experiencia del Usuario: Realizar estudios de satisfacción para identificar oportunidades de mejora en la experiencia del cliente, lo cual puede traducirse en una mayor fidelización y en un aumento en las ventas a largo plazo.




