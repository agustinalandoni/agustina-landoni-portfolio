# 🎵 Spotify Global Rankings Analysis | Power BI

Proyecto de análisis de datos desarrollado en Power BI para estudiar la difusión internacional, estabilidad y desempeño de canciones en rankings musicales globales de Spotify.

El proyecto busca comprender cómo se propagan los éxitos musicales entre mercados internacionales, qué características presentan las canciones con mejor desempeño y cómo evolucionan dentro de los rankings a lo largo del tiempo.

---

## 📌 Objetivo general del proyecto

El objetivo principal es analizar el comportamiento de las canciones más populares en Spotify, identificando cómo los hits se difunden desde los principales mercados musicales hacia otros países y qué factores influyen en su permanencia y desempeño dentro de rankings globales.

A través del análisis de popularidad, características musicales, permanencia, estabilidad, difusión internacional y evolución temporal, se busca detectar patrones comunes en canciones exitosas y comprender dinámicas de propagación global.

---

## 🌎 Alcance del análisis

El proyecto trabaja con un dataset basado en rankings musicales de Spotify en más de 70 países.

Cada registro representa una canción en una fecha específica, dentro de un país determinado, con su posición en el ranking y características musicales asociadas.

El análisis contempla:

- Comportamiento temporal de las canciones.
- Diferencias entre mercados y regiones.
- Estabilidad y rotación dentro de rankings.
- Expansión internacional de canciones.
- Relación entre características musicales y desempeño.

---

## 👤 Usuario final y aplicación

El dashboard está orientado a profesionales vinculados a la industria musical, áreas de marketing, comunicación, producción, sellos discográficos y perfiles analíticos interesados en tendencias musicales globales.

El análisis tiene una aplicación táctica, ya que permite generar información útil para campañas de promoción, estrategias de lanzamiento, análisis de mercados y posicionamiento internacional de canciones.

---

## 💡 Hipótesis de trabajo

La hipótesis del proyecto plantea que las canciones más exitosas a nivel global tienden a posicionarse primero en mercados líderes de la industria musical —como Estados Unidos, Reino Unido y Japón— y luego expandirse hacia otros países.

---

## 🗂 Modelo de datos

El proyecto fue construido utilizando un modelo relacional compuesto por las siguientes tablas:

- Canción
- Artista
- Álbum
- Características
- País
- Chart
- Calendario

Este modelo permite conectar información de rankings, características musicales y difusión internacional para realizar análisis multidimensionales.

---

## ⚙️ Transformaciones y preparación de datos

Durante el proceso de preparación de datos se realizaron tareas de limpieza, normalización y modelado para asegurar la consistencia del análisis.

Entre las principales transformaciones se incluyen:

- Tipado correcto de columnas.
- Eliminación de duplicados.
- Normalización de tablas.
- Creación de relaciones entre entidades.
- Creación de tabla calendario.
- Incorporación de variable continente.
- Desarrollo de métricas DAX para análisis de desempeño.

---

# 📊 Dashboards desarrollados

---

## 🌍 Dashboard 1: Difusión internacional de canciones

![Difusión internacional](screenshots/difusion-global.png)

<!-- Si tenés GIF, podés usar esta línea en lugar de la imagen:
![Difusión internacional](assets/difusion-global.gif)
-->

### Objetivo

Analizar cómo se distribuye la presencia de canciones entre distintos países y regiones del mundo, identificando cuáles logran mayor alcance internacional.

### ¿Qué permite analizar?

Este dashboard permite observar en cuántos países aparece cada canción, qué regiones concentran mayor presencia y cómo se distribuye el desempeño internacional de los principales hits.

También permite complementar el análisis de rankings con una dimensión geográfica, evaluando no solo qué canciones alcanzan buenas posiciones, sino también en qué mercados logran expandirse.

### Métricas utilizadas

- Cantidad de países
- Días en ranking
- Mejor ranking
- Ranking mediana canción
- Presencia por continente

### Visualizaciones incluidas

- Mapa geográfico
- Ranking de canciones con mayor alcance global
- Tabla comparativa por canción
- Presencia en rankings por continente
- Filtros por país y canción

### Valor analítico

Este panel ayuda a identificar canciones con mayor difusión global y permite comparar si el alcance internacional se relaciona con la permanencia o con las mejores posiciones alcanzadas en rankings.

---

## 📈 Dashboard 2: Popularidad y estabilidad en rankings

![Popularidad en rankings](screenshots/popularidad-rankings.png)

<!-- Si tenés GIF, podés usar esta línea en lugar de la imagen:
![Popularidad en rankings](assets/popularidad-rankings.gif)
-->

### Objetivo

Estudiar la dinámica de los rankings musicales dentro de un mercado y período determinado, analizando estabilidad, permanencia y volatilidad.

### ¿Qué permite analizar?

Este dashboard permite observar cómo evoluciona el ranking promedio a lo largo del tiempo, qué canciones permanecen más días dentro de los rankings y qué tan variable es el comportamiento de las posiciones mes a mes.

El foco está puesto en entender si un ranking presenta estabilidad o alta rotación, y qué canciones logran sostenerse durante más tiempo.

### Métricas utilizadas

- Días en ranking
- Movimiento semanal promedio
- Ranking promedio mensual
- Volatilidad del ranking
- Permanencia por canción

### Visualizaciones incluidas

- Evolución del ranking promedio por mes
- Volatilidad mensual
- Top canciones por permanencia
- Filtros por año y país

### Valor analítico

Este panel permite diferenciar canciones que tienen apariciones breves de aquellas que logran sostener su presencia en rankings. También ayuda a analizar la estabilidad de un mercado musical específico.

---

## 🎤 Dashboard 3: Desempeño de canciones en rankings

![Desempeño de canciones](screenshots/desempeno-canciones.png)

<!-- Si tenés GIF, podés usar esta línea en lugar de la imagen:
![Desempeño de canciones](assets/desempeno-canciones.gif)
-->

### Objetivo

Evaluar qué canciones y artistas combinan buenas posiciones con alta permanencia en rankings para identificar desempeño sostenido en el tiempo.

### ¿Qué permite analizar?

Este dashboard permite comparar canciones según su ranking promedio y sus días de permanencia, diferenciando aquellas que alcanzan buenas posiciones de forma puntual de aquellas que logran mantener un rendimiento consistente.

También permite observar el desempeño de artistas a partir de la relación entre posición promedio y permanencia en rankings.

### Métricas utilizadas

- Score de desempeño
- Días en ranking
- Ranking promedio
- Mejor posición promedio
- Permanencia por artista

### Visualizaciones incluidas

- Canciones con mejor posición promedio
- Canciones con mejor desempeño sostenido
- Scatter plot de artistas
- Filtros por país, año y artista

### Valor analítico

Este panel permite identificar canciones con rendimiento sólido, no solo por alcanzar buenas posiciones, sino por sostenerse en el tiempo. Esto aporta una mirada más completa del éxito musical.

---

## 🎧 Dashboard 4: Características musicales de canciones

![Características musicales](screenshots/caracteristicas-musicales.png)

<!-- Si tenés GIF, podés usar esta línea en lugar de la imagen:
![Características musicales](assets/caracteristicas-musicales.gif)
-->

### Objetivo

Comparar las características musicales de canciones seleccionadas con el perfil del Top 10 para analizar si ciertos atributos se asocian con mejores desempeños en rankings.

### ¿Qué permite analizar?

Este dashboard permite evaluar métricas musicales como danceability, energy y valence, comparándolas contra canciones con mejor desempeño.

El objetivo es observar si las canciones mejor posicionadas comparten ciertos patrones musicales o si existen diferencias relevantes entre la canción seleccionada y el benchmark del Top 10.

### Métricas utilizadas

- Promedio Danceability
- Promedio Energy
- Promedio Valence
- Mejor ranking
- Score de desempeño

### Visualizaciones incluidas

- KPIs principales
- Comparación Danceability vs Energy
- Benchmark contra Top 10
- Filtros por año, canción y artista

### Valor analítico

Este panel permite incorporar una dimensión musical al análisis de desempeño, conectando características de audio con resultados obtenidos en rankings.

---

# 🛠 Herramientas utilizadas

- Power BI
- Power Query
- DAX
- Modelado de datos
- Visualización de datos
- Storytelling analítico

---

# 🧠 Skills demostradas

- Limpieza y transformación de datos
- Modelado relacional
- Creación de medidas DAX
- Análisis exploratorio de datos
- Diseño de dashboards interactivos
- Visualización orientada al usuario
- Storytelling con datos
- Navegación entre páginas
- Uso de filtros dinámicos
- Construcción de KPIs

---

# 🔍 Conclusiones principales

En conjunto, los dashboards permiten abordar el fenómeno musical desde distintas dimensiones:

- **Difusión internacional:** permite analizar en qué mercados se expanden las canciones y cuál es su alcance global.
- **Popularidad en rankings:** permite observar la estabilidad, rotación y permanencia de canciones dentro de los charts.
- **Desempeño en rankings:** permite identificar canciones y artistas que combinan buenas posiciones con permanencia sostenida.
- **Características musicales:** permite comparar atributos como danceability, energy y valence con el desempeño obtenido.

A partir del análisis, se observa que la popularidad de una canción no depende únicamente de alcanzar una buena posición, sino también de su permanencia, estabilidad y capacidad de difusión entre mercados.

---

# 📁 Archivos incluidos

Este repositorio contiene:

- Archivo `.pbix`
- Exportación del dashboard en PDF
- Capturas de pantalla de cada dashboard
- README descriptivo
- Recursos visuales del proyecto

---

# 📌 Dataset

Dataset utilizado con fines educativos y analíticos para explorar el comportamiento de rankings musicales globales de Spotify.

---

# 👩‍💻 Autora

**Agustina Landoni**

Estudiante de Relaciones Públicas con interés en:

- Data Analytics
- Business Intelligence
- Storytelling con datos
- Comunicación estratégica
- Visualización de información

---

# 🚀 Proyecto desarrollado en Power BI

Portfolio personal orientado a análisis de datos y visualización interactiva.
