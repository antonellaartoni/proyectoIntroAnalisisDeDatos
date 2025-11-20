
# 📊 Análisis del Mercado Laboral y Tendencias Salariales en Inteligencia Artificial (2025)

Este proyecto presenta un análisis de datos enfocado en comprender la evolución, demanda y tendencias salariales del mercado global de empleo en Inteligencia Artificial (IA). Basado en un dataset con más de **15.000 ofertas laborales**, busca identificar:

* Cómo influye la especialización en IA en los salarios.
* Qué habilidades son más demandadas.
* Qué regiones ofrecen las mejores oportunidades.
* Cómo se posicionan los roles de IA frente a roles tradicionales.

---

## 📌 Objetivo del Proyecto

El objetivo principal es responder **qué exigen las empresas líderes en tecnología** y cómo la IA está redefiniendo el panorama laboral global.

Este análisis proporciona una visión clara sobre:

* La relación entre especialización en IA y nivel salarial.
* Las habilidades técnicas con mayor impacto económico.
* Cómo cambia el mercado según nivel de experiencia y ubicación geográfica.

---

## 💡 Preguntas Clave de Investigación

### 1. Impacto de la IA en el Salario

¿Cómo influye la adopción y especialización en Inteligencia Artificial en los salarios de los desarrolladores, considerando su nivel de experiencia y la región donde trabajan?

### 2. Habilidades de Alto Valor

¿Qué habilidades relacionadas con IA están asociadas con salarios más altos y mayor demanda laboral a nivel global?

---

## 🛠️ Metodología

El análisis se desarrolló mediante un pipeline de procesamiento de datos en **Python**, utilizando Pandas para la manipulación y Matplotlib/Seaborn para las visualizaciones.

### **Pasos principales del proyecto:**

#### 1. Adquisición y Limpieza del Dataset

* Dataset utilizado: *Global AI Job Market & Salary Trends 2025* (descargado desde Kaggle vía KaggleHub).
* Verificación de valores nulos, duplicados y formato de datos.
* Columnas clave: `salary_usd`, `experience_level`, `job_title`, etc.

#### 2. Ingeniería de Características

Se creó la columna **`rol_ia`** categorizando los puestos como:

* **IA**
* **No_IA**

Basándose en palabras clave como:
*Machine Learning, Deep Learning, NLP, Computer Vision, AI Engineer, Research Scientist*, etc.

#### 3. Análisis Salarial Estratificado

Se calcularon promedios salariales diferenciados por:

* Nivel de experiencia: `EN`, `MI`, `SE`, `EX`
* Tipo de rol: IA vs No_IA
* Ubicación geográfica de la compañía

#### 4. Análisis de Habilidades y su Impacto Salarial

* Identificación de las skills más frecuentes
* Cálculo del salario promedio asociado
* Obtención del **Top 10 de habilidades mejor pagadas**

---

## 📈 Resultados e Insights Clave

### 🔹 1. IA aumenta el salario en niveles altos (SE y EX)

Los roles IA presentan salarios **ligeramente superiores**:

| Nivel   | IA (USD)     | No IA (USD) |
| ------- | ------------ | ----------- |
| SE / EX | **$164,355** | $162,423    |

La diferencia no es extrema, pero es **consistente en todas las regiones**.

---

### 🔹 2. Regiones Mejor Pagadas

Los países con salarios promedio más altos fueron:

* 🇨🇭 **Suiza**
* 🇳🇴 **Noruega**

Destacan por:

* Alto costo de vida
* Fuerte inversión en tecnología
* Políticas laborales robustas

---

### 🔹 3. Habilidades de Mayor Impacto Salarial

El análisis reveló que:

* Las **skills más especializadas** no son las más frecuentes en las ofertas.
* Aun así, **concentran los salarios más altos** del mercado.

---

## 💻 Tecnologías Utilizadas

* **Python**
* **Pandas** (Limpieza y manipulación de datos)
* **Matplotlib** (Visualización)
* **Seaborn** (Visualización estadística)
* **KaggleHub** (Descarga del dataset)

---

## 📂 Estructura del Repositorio

```
├── data/
│   └── dataset.csv
├── notebooks/
│   └── analisis.ipynb
├── src/
│   ├── procesamiento.py
│   └── visualizaciones.py
└── README.md
```

---

## 🚀 Conclusión

Este proyecto revela cómo el mercado laboral en IA continúa expandiéndose y generando salarios competitivos, especialmente en roles especializados. También evidencia la importancia estratégica de ciertas habilidades avanzadas, que aunque menos frecuentes, concentran los salarios más altos en la industria tech.
