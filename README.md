# Proyecto Final: Una Anomalía, Defendida
**Curso:** IELE756 – Preparación y Análisis de Datos  
**Integrantes:** Felipe Velásquez, Matías Moraga  

## 1. Comunas Analizadas
Este proyecto se enfoca en el análisis demográfico y de salud de las comunas de:
* El Bosque
* Lo Espejo
* Isla de Maipo
* Pirque

## 2. La Anomalía Detectada
Nuestra investigación reveló una **relación negativa entre la proporción de población extranjera y la estadía media hospitalaria (GRD LOS)**. A pesar de la vulnerabilidad socioeconómica asociada a grupos migrantes, los datos muestran que, a nivel comunal, las estadías son más cortas a medida que aumenta el porcentaje de extranjeros.

## 3. Defensa de la Anomalía
A través del análisis en el notebook `final_anomaly.ipynb`, demostramos que este fenómeno se explica por:
1. **Efecto Obstétrico:** La población migrante se hospitaliza mayoritariamente por partos, eventos de estadía corta (2-3 días).
2. **Estructura Etaria:** La población extranjera es significativamente más joven ("Migrante Sano"), lo que reduce la prevalencia de estadías largas por enfermedades crónicas.

## 4. Estructura del Repositorio
* `notebooks/`: Contiene las Tareas 0-3 y el análisis final (`final_anomaly.ipynb`).
* `figs/`: Gráfico principal de la anomalía (`headline.png`).
* `requirements.txt`: Librerías necesarias para ejecutar el proyecto.

## 5. Instalación y Uso
Para replicar este análisis:
1. Clonar el repositorio: `git clone [URL_DE_TU_RECO]`
2. Instalar dependencias: `pip install -r requirements.txt`
3. Ejecutar el notebook `notebooks/final_anomaly.ipynb`.
*Tiempo estimado de ejecución: 1 minuto (utiliza tablas maestras pre-computadas).*

## 6. AI-Use Disclosure
Para este proyecto se utilizó **ChatGPT/Claude** en las siguientes tareas:
* **Redacción:** Apoyo en la síntesis de hallazgos y estructuración del README.
* **Código:** Depuración de gráficos en Matplotlib y optimización de celdas de Join.
* **Análisis:** Ayuda en la interpretación técnica de los resultados de regresión de la Tarea 3.
*Toda la responsabilidad sobre la veracidad de los datos y la lógica del análisis recae en los autores.*
