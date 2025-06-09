💊 Farmacéutica - Biogenesys.

🚀 Expansión Estratégica de Biogenesys con Python

🧬 Introducción
La empresa farmacéutica BIOGENESYS busca identificar las ubicaciones óptimas para la expansión de laboratorios en América Latina, enfocándose en seis países clave: Colombia, Argentina, Chile, México, Perú y Brasil.
El objetivo es mejorar la respuesta ante pandemias y optimizar el acceso a vacunas mediante el análisis de datos epidemiológicos, demográficos y sanitarios.

BIOGENESYS nos ha contratado como equipo de Data Analysts para realizar un estudio exhaustivo basado en datos reales. El fin es ofrecer recomendaciones sobre dónde establecer nuevos centros de vacunación y laboratorios, con un enfoque preventivo y de desarrollo de infraestructura sanitaria.

🛠️ Desarrollo del Proyecto
📊 Avance 1: Recopilación y Preparación de Datos
Se recopilaron y consolidaron datos relevantes de fuentes oficiales sobre COVID-19, vacunación, salud pública y condiciones demográficas.
Se creó el archivo maestro: Df_datos_finales_filtrado.csv.

Tareas clave:

🌎 Filtrado por los seis países objetivos.

📅 Filtrado por fechas (años 2021-2022).

🧹 Limpieza de datos: eliminación de registros vacíos, duplicados y valores nulos.

🔍 Filtrado por location_key.


📈 Avance 2: Análisis Exploratorio y Visualización
Utilizando Pandas, NumPy, Matplotlib y Seaborn, se realizaron:

📐 Estadísticas descriptivas: medias, medianas, desviaciones, rangos.

📊 Visualizaciones: histogramas, boxplots, mapas de calor, barras, dispersión.

🔗 Correlaciones entre: temperatura, densidad poblacional y número de casos/muertes.

🧠 Insights clave:

🔥 Regiones con mayor temperatura promedio mostraron menor incidencia.

🧍‍♂️ Alta correlación entre densidad poblacional y propagación del virus.

🏥 Déficit de infraestructura sanitaria en zonas con alta mortalidad.


🕒 Avance 3: Análisis Temporal y Tendencias
Se trabajó con series temporales para detectar:

📆 Tendencias mensuales en contagios y vacunación.

♻️ Estacionalidad de incidencia.

📊 Autocorrelaciones y picos epidemiológicos.

Esto permitió prever áreas de alta prioridad y periodos críticos que requieren intervención.


📊 Avance 4: Dashboard Interactivo en Power BI
Se diseñó un dashboard interactivo para facilitar la exploración por parte de los directivos.

Características principales:

🔍 Filtros por país, fecha, variable y tipo de región.

📌 KPIs dinámicos de salud y vacunación.

📈 Evolución mensual de casos y dosis administradas.


🔍 EDA e Insights Relevantes
🏥 Infraestructura desigual vs. incidencia de casos.

❤️‍🩹 Comorbilidades (diabetes, tabaquismo) correlacionadas con mayor mortalidad.

🌄 Desigualdad urbana-rural: cobertura deficiente en zonas rurales.

👵 Edad media influye en recuperación y mortalidad.

📊 Análisis del Dashboard
El dashboard desarrollado en Power BI brinda una vista integral del impacto del COVID-19 en los seis países analizados.


Visualizaciones clave:

🌍 Ritmo de propagación por país: Brasil destaca por volumen de casos.

📈 Picos y olas epidemiológicas: principalmente en 2021 y 2022.

🧬 Comorbilidades y mortalidad: Chile con niveles más altos.

💉 Dosis administradas: Brasil lidera, seguido por México y Perú.

⚠️ Impacto severo: Perú y México muestran los niveles más altos.

🌡️ Comparación temperatura - nuevos casos: no hay correlación directa clara.

🔄 Matriz de correlación: relaciones fuertes entre infraestructura, densidad, comorbilidades y vacunación.

📌 Este dashboard es una herramienta clave para la toma de decisiones estratégicas en expansión e inversión.

🧾 Conclusiones y Recomendaciones
✅ Conclusiones Generales
📍 Casos concentrados en zonas urbanas densamente pobladas.

💉 Vacunación desigual, especialmente en áreas rurales.

⚕️ Mortalidad influida por comorbilidades y acceso a salud.


🧭 Conclusiones Estratégicas
🏗️ Priorizar expansión en zonas de alta densidad y baja infraestructura sanitaria.

🏥 Ampliar cobertura de vacunación en regiones rurales.

📊 Considerar indicadores como diabetes, contaminación y edad media.

🌐 Diseñar estrategias diferenciadas por país.

📌 Respuesta Principal del Proyecto
Se recomienda iniciar la expansión en las siguientes ubicaciones estratégicas:

🇧🇷 Brasil: Alta población y baja infraestructura sanitaria.

🇵🇪 🇨🇴 Regiones andinas de Perú y Colombia: Zonas rurales densas con alto riesgo.

🇦🇷 Conurbano Bonaerense, Argentina: Alta densidad y desigualdad en acceso a salud.

Estas ubicaciones permitirán a Biogenesys:

✅ Maximizar el impacto positivo de su inversión.

🛡️ Reforzar la salud pública regional.

🧪 Prepararse ante futuras crisis sanitarias.
