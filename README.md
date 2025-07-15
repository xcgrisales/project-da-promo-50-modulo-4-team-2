# ✈️ Proyecto de Análisis de Destinos de Viaje

## 🌍 Descripción del Proyecto

Este proyecto tiene como objetivo analizar un conjunto de datos sobre destinos turísticos, considerando factores como el presupuesto estimado, el clima y distintas experiencias temáticas (cultura, aventura, bienestar, etc.).

A través de la limpieza, el análisis exploratorio y la visualización interactiva en Power BI, buscamos identificar patrones que ayuden a comparar destinos y facilitar la toma de decisiones para futuros viajeros o planificadores turísticos.

> **Lema del proyecto:** *Viaja con datos, no con dudas.*

---

## 📁 Estructura del Repositorio

- `viajes.csv`: dataset original con más de 500 destinos turísticos.
- `monthly_temp.csv`: temperaturas mensuales transformadas para visualización.
- `travel_info.csv`: datos procesados y enriquecidos para Power BI.
- `proyecto-modulo-4-equipo-2.ipynb`: análisis exploratorio y limpieza en Python.
- `README.md`: documentación del proyecto.

---

## 🔄 Estructura del Proyecto

### 1. Importación de datos
- Se carga el archivo `viajes.csv` con información de destinos de todo el mundo.

### 2. Análisis exploratorio (EDA)
- Revisión general del dataset: tipos de datos, nulos, duplicados.
- Detección de inconsistencias y oportunidades de transformación.

### 3. Limpieza de datos
- Conversión de valores decimales para compatibilidad con Power BI.
- Normalización de texto en columnas como `region`.
- Generación de dos nuevos CSV tratados: `monthly_temp.csv` y `travel_info.csv`.

### 4. Definición de objetivos
- Ayudar a identificar el destino ideal según clima, presupuesto y experiencias.
- Crear dashboards visuales, intuitivos y útiles para el usuario final.

---

## 📊 Visualizaciones en Power BI

- **Radar de experiencias**: compara destinos según 9 categorías (cultura, aventura, naturaleza, etc.).
- **Gráficos de barras y líneas**: muestran clima promedio y presupuesto estimado.
- **Mapa interactivo**: para explorar ciudades por ubicación.
- **Segmentadores**: por país, continente, duración del viaje y tipo de experiencia.
- **Dashboards navegables**: con botones interactivos, filtros y visualizaciones dinámicas.

---

## ✅ Conclusiones principales

- El clima templado es el más común entre los destinos analizados.
- Asia y América del Sur destacan por tener más opciones económicas.
- La mayoría de destinos están en un rango de presupuesto medio.
- Oceanía y Europa concentran la mayor parte de destinos de lujo.
- Los viajes largos suelen estar ligados a destinos más exclusivos.
- Hay amplia oferta para viajes de corta duración.
- Las experiencias más valoradas por destino son: cultura, gastronomía y naturaleza.

---

## 🧪 Herramientas utilizadas

- **Python** – para limpieza y análisis (pandas, numpy, seaborn).
- **Jupyter Notebook** – para el EDA y transformación de datos.
- **Power BI** – para visualización y dashboards finales.
- **Slack** – para organización del trabajo en equipo y comunicación diaria.
- **Kaggle** – para la búsqueda y elección del dataset.
- **Git & GitHub** – para control de versiones y trabajo colaborativo.

---

## 👭 Equipo del Proyecto

Este proyecto fue desarrollado de forma colaborativa por cuatro integrantes, trabajando de forma remota y coordinada.

- **Carolina Perona** – Limpieza de datos y análisis en Python  
- **Marina Soler** – Visualizaciones y storytelling  
- **Ximena Castaño** – Desarrollo de dashboards en Power BI  
- **Lidia Barcia** – Diseño visual, interactividad y presentación final 

---

¡Gracias por visitar este repositorio! Si quieres ver el dashboard en acción o contactar con el equipo, no dudes en escribirnos o explorar el proyecto.
