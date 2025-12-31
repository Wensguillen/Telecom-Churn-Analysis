# Telecom-Churn-Analysis: Estrategia de Retención basada en Datos

<h1> Acerca del proyecto</h1>

Telecom X es una proveedora de servicios de telecomunicaciones que ofrece soluciones de conectividad, telefonía fija e internet de alta velocidad (Fibra Óptica y DSL). Con una base de más de 7,000 clientes, la empresa se enfrenta al desafío de optimizar la retención de usuarios en un mercado altamente competitivo.

<h2>El Problema</h2> 
El análisis revela una tasa de deserción histórica del 26.5%, con una rotación alarmante en los contratos de corto plazo.
  
<h2> Insights Clave </h2> 

<li> Vulnerabilidad en el Servicio Técnico: La ausencia de soporte técnico es uno de los predictores más fuertes de fuga.</li> 

<li> Barreras de Salida y Contratos: Los contratos mes a mes presentan una tasa de fuga del 42.71%, mientras que los contratos a largo plazo (2 años) logran "blindar" al cliente.</li>

<li> La Paradoja de la Fibra Óptica: Los clientes de alto valor son menos tolerantes a la falta de beneficios adicionales o soporte.</li>

<li> Fricción en Métodos de Pago: El uso de métodos de pago manuales (como el cheque electrónico) está vinculado a una mayor evasión en comparación con los métodos automáticos.</li>

<h3> 🛠️ Sigue estos pasos para la instalación y configuración </h3>

1. Descarga una copia del proyecto <br>
2. Este proyecto fue desarrollado en Python 3.12.<br>
Las librerías necesarias para ejecutar el análisis son:<br>
Pandas, Matlotlib & Seaborn, Numpy.
3. Abre tu entorno de preferencia (Jupyter Notebook, VS Code o Google Colab) <br>
Carga el archivo (esta en formato JSON)<br> 
Ejecuta las celdas en orden secuencial para observar el flujo del análisis, desde la carga hasta las conclusiones finales.

 <h2>⚠️ Posibles Problemas y Soluciones</h2>
 
Error: FileNotFoundError al cargar el JSON
Causa: El archivo de datos no está en el directorio correcto.
Solución: Verifica que la ruta en la función pd.read_json() coincida con la ubicación real del archivo.

Las gráficas no se muestran o se ven cortadas
Causa: Versiones antiguas de Matplotlib.
Solución: Actualiza la librería con pip install --upgrade matplotlib y asegúrate de incluir la línea %matplotlib inline al inicio de tu notebook si estás en un entorno clásico.

Valores nulos en el archivo de salida
Causa: Como se advierte en la documentación de to_json, los valores NaN se convierten a null.
Solución: Esto es normal para mantener la compatibilidad del formato JSON; no afecta la integridad de los datos procesados.


<h3> Sobre mi</h3>

<p> Este análisis, más allá de los códigos y las gráficas, apliqué técnicas de limpieza, análisis exploratorio y visualización estratégica para transformar datos crudos en soluciones de negocios reales.

<strong> Wendy Guillen: wensguillen@gmail.com </strong>

