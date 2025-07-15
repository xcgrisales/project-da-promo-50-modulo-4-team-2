# ✈️ Proyecto de análisis de destinos de viaje

Este proyecto tiene como objetivo analizar un conjunto de datos sobre destinos turísticos, considerando factores como el presupuesto promedio, la temperatura y distintas experiencias temáticas (cultura, aventura, bienestar, etc.). A través de la limpieza, análisis exploratorio y visualización, buscamos identificar patrones que ayuden a comparar destinos y facilitar la toma de decisiones para futuros viajeros o planificadores turísticos.

---

## 📁 Estructura del proyecto

1. **Importación de datos**
   - Se carga un archivo CSV ('viajes.csv') con información de distintos países/destinos.

2. **Análisis exploratorio (EDA)**
   - Revisión inicial de la estructura del dataset.
   - Identificación de valores nulos, formatos incorrectos o datos duplicados.

3. **Limpieza de datos**
   - Conversión de valores decimales con punto a coma para compatibilidad con Power BI.
   - Normalización de texto en columnas como `region` (reemplazo de guiones bajos, mayúsculas iniciales).
   - Se generan dos nuevos csv con todos los datos tratados: 'monthly_temp.csv' y 'travel_info.csv'

4. **Definición de objetivos**
   - Ayudarte a decidir el destino ideal de tu viaje
   - Crear dashboards claros, útiles y visuales

5. **Visualizaciones**
   - Radar charts para comparar el perfil temático de cada país.
   - Gráficos de barras y líneas para analizar presupuesto y temperatura.
   - Segmentadores por país, región o tipo de experiencia.

6. **Dashboards**
   - Se construyen dashboards en Power BI con visualizaciones interactivas.
   - Permite comparar destinos según diferentes criterios definidos por el usuario.

7. **Conclusiones**
   - Se resumen hallazgos clave como:

       - En general, predomina el clima templado.
       - Para viajes económicos destacan Asia y América del Sur.
       - La mayoría de destinos son de presupuesto medio.
       - Si buscas una experiencia más premium, Oceanía y Europa son las mejores opciones.
       - Los destinos ideales para viajes largos suelen ser menos comunes y más lujosos.
       - Hay gran variedad de destinos para viajes de corta duración.
       - Dentro de las nueve experiencias valoradas, las que mejor puntuación alcanzan son cultura, gastronomía y naturaleza.

---

## 🧪 Herramientas utilizadas

- Python (pandas para limpieza y análisis preliminar)
- Power BI (para visualización y dashboard final)
- Jupyter Notebook

---

## 👭 Conoce al equipo detrás del proyecto

- Carolina Perona (@carolinaperona)
- Marina Soler (@marinarsd)
- Ximena Castaño (@xcgrisales)
- Lidia Barcia (@LidiaBDLI)

  
