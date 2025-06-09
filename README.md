# 💊 Biogenesys – Expansión Estratégica en América Latina

### 🚀 Proyecto de Análisis de Datos con Python & Power BI

---

## 🧬 Introducción

La farmacéutica **Biogenesys** busca identificar ubicaciones estratégicas para la expansión de laboratorios en América Latina, con el fin de:

- Mejorar la **respuesta ante pandemias**  
- Optimizar el **acceso a vacunas**

El análisis se centró en **6 países clave**:  
🇨🇴 Colombia · 🇦🇷 Argentina · 🇨🇱 Chile · 🇲🇽 México · 🇵🇪 Perú · 🇧🇷 Brasil

Como equipo de **Data Analysts**, fuimos contratados para:

> 📌 Realizar un estudio de datos epidemiológicos, demográficos y sanitarios para recomendar ubicaciones óptimas de nuevos centros de vacunación y laboratorios.

---

## 🛠️ Fases del Proyecto

### 📊 Avance 1: Recopilación y Preparación de Datos

🔹 Recolección de datos de fuentes oficiales sobre:  
COVID-19, vacunación, salud pública, condiciones demográficas

🔹 Creación del dataset maestro:  
`Df_datos_finales_filtrado.csv`

**Tareas clave:**

- 🌎 Filtrado por países objetivo  
- 📅 Filtrado por fechas (2021–2022)  
- 🧹 Limpieza: valores nulos, duplicados  
- 📌 Selección por `location_key`

---

### 📈 Avance 2: Análisis Exploratorio y Visualización

📚 Tecnologías: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`

**Análisis realizados:**

- 📐 Estadísticas descriptivas: media, mediana, desviación estándar, rango  
- 📊 Visualizaciones: histogramas, boxplots, mapas de calor, diagramas de dispersión  
- 🔗 Correlaciones: temperatura, densidad poblacional, incidencia

**Insights clave:**

- 🔥 Mayor temperatura promedio → menor incidencia  
- 🧍‍♂️ Alta densidad → mayor propagación  
- 🏥 Falta de infraestructura en zonas con alta mortalidad

---

### 🕒 Avance 3: Análisis Temporal y Series de Tiempo

**Objetivo:** Identificar patrones críticos y prever áreas de intervención

- 📆 Tendencias mensuales en contagios y vacunación  
- ♻️ Estacionalidad de incidencia  
- 📊 Análisis de autocorrelación y picos epidemiológicos

---

### 📊 Avance 4: Dashboard Interactivo en Power BI

🔧 Se desarrolló un dashboard interactivo para la toma de decisiones ejecutivas.

**Características:**

- 🔍 Filtros por país, fecha, variable y tipo de zona  
- 📌 KPIs dinámicos de salud y vacunación  
- 📈 Visualización mensual de casos y dosis administradas

---

## 🔍 Insights Relevantes del Análisis

| Categoría | Insight |
|----------|---------|
| 🏥 Infraestructura | Desigualdad en zonas con alta incidencia |
| ❤️‍🩹 Comorbilidades | Diabetes y tabaquismo → mayor mortalidad |
| 🌄 Zonas rurales | Cobertura sanitaria deficiente |
| 👵 Edad media | Influye en la recuperación y mortalidad |

---

## 📊 Análisis del Dashboard

**Visualizaciones destacadas:**

- 🌍 Ritmo de propagación por país: Brasil con mayor volumen  
- 📈 Olas epidemiológicas: picos en 2021 y 2022  
- 🧬 Mortalidad asociada a comorbilidades: alta en Chile  
- 💉 Dosis administradas: Brasil, México y Perú lideran  
- ⚠️ Impacto severo: Perú y México  
- 🌡️ Temperatura vs. casos: sin correlación directa clara  
- 🔄 Matriz de correlación: relaciones fuertes entre infraestructura, comorbilidades y vacunación

> 🧭 Este dashboard es clave para decisiones estratégicas de expansión.

---

## 🧾 Conclusiones y Recomendaciones

### ✅ Conclusiones Generales

- 📍 Casos concentrados en áreas urbanas densas  
- 💉 Vacunación desigual, sobre todo en zonas rurales  
- ⚕️ Mortalidad ligada a comorbilidades y acceso a salud

### 📌 Recomendaciones Estratégicas

- 🏗️ Expandir en zonas densamente pobladas con baja infraestructura  
- 🏥 Aumentar vacunación en regiones rurales  
- 📊 Incorporar indicadores como diabetes, contaminación y edad media  
- 🌐 Aplicar estrategias diferenciadas por país

---

## 📍 Ubicaciones Recomendadas para Expansión

| País / Región | Justificación |
|---------------|---------------|
| 🇧🇷 Brasil | Alta población y baja infraestructura |
| 🇵🇪 Perú (zona andina) | Riesgo elevado y baja cobertura rural |
| 🇨🇴 Colombia (zona andina) | Alta densidad rural, riesgo sanitario |
| 🇦🇷 Conurbano Bonaerense | Alta densidad y desigualdad sanitaria |

---

## ✅ Impacto Esperado

- 📈 Maximizar el retorno e impacto social de la inversión  
- 🛡️ Fortalecer la salud pública en América Latina  
- 🧪 Prepararse para futuras crisis sanitarias

---

## 💻 Tecnologías Usadas

- **Python** – Análisis de datos (`pandas`, `numpy`, `seaborn`, `matplotlib`)  
- **Power BI** – Visualización interactiva de resultados  
- **CSV / Excel** – Integración y tratamiento de fuentes de datos

---

## 🧑‍💼 Autores

- 👨‍💻 Roman Mtheus – www.linkedin.com/in/roman-matheus-9a6689159 · [GitHub](https://github.com/tuusuario)  

---

## 📁 Estructura del Repositorio

