# ✈️ Proyecto de análisis de destinos de viaje

Este proyecto tiene como objetivo analizar un conjunto de datos sobre destinos turísticos, considerando factores como el presupuesto promedio, la temperatura y distintas experiencias temáticas (cultura, aventura, bienestar, etc.). A través de la limpieza, análisis exploratorio y visualización, buscamos identificar patrones que ayuden a comparar destinos y facilitar la toma de decisiones para futuros viajeros o planificadores turísticos.

---

## 📁 Estructura del proyecto

1. **Importación de datos**
   - Se carga un archivo CSV con información de distintos países/destinos.

2. **Análisis exploratorio (EDA)**
   - Revisión inicial de la estructura del dataset.
   - Identificación de valores nulos, formatos incorrectos o datos duplicados.

3. **Limpieza de datos**
   - Conversión de valores decimales con punto a coma para compatibilidad con Power BI.
   - Normalización de texto en columnas como `region` (reemplazo de guiones bajos, mayúsculas iniciales).

4. **Definición de objetivos**
   - ¿Qué destinos se adaptan mejor a cierto presupuesto?
   - ¿Dónde se combinan mejor temperatura agradable y riqueza cultural?
   - ¿Qué regiones destacan en experiencias de aventura, relajación o vida urbana?

5. **Visualizaciones**
   - Radar charts para comparar el perfil temático de cada país.
   - Gráficos de barras y líneas para analizar presupuesto y temperatura.
   - Segmentadores por país, región o tipo de experiencia.

6. **Dashboard / Informe**
   - Se construye un dashboard en Power BI con visualizaciones interactivas.
   - Permite comparar destinos según diferentes criterios definidos por el usuario.

7. **Conclusiones**
   - Se resumen hallazgos clave como:
     - Relación entre presupuesto y región.
     - Perfiles temáticos destacados por país.
     - Opciones recomendadas para distintos tipos de viajeros.

---

## 🧪 Herramientas utilizadas

- Python (pandas para limpieza y análisis preliminar)
- Power BI (para visualización y dashboard final)
- Jupyter Notebook
