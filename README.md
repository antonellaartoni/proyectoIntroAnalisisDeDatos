
# 📊 Análisis del Mercado Laboral y Salarial en IA (2025)

Este proyecto analiza el *Global AI Job Market & Salary Trends 2025*, un dataset con miles de ofertas laborales globales relacionadas con Inteligencia Artificial y desarrollo de software. El objetivo es comprender:

* Cómo impacta la especialización en IA en los salarios.
* Qué habilidades son más demandadas y mejor pagadas.
* Cómo varían las oportunidades según la experiencia y región.

---

## 📌 Objetivo del Proyecto

El proyecto busca responder **qué exigen las grandes empresas** y cómo la IA está influyendo en los salarios y oportunidades laborales.

A partir del análisis realizado en Python, se estudian:

* Tendencias salariales según rol y seniority.
* Comparaciones entre roles IA y No IA.
* Habilidades más requeridas por el mercado.
* Regiones mejor pagadas.

---

## 💡 Preguntas Clave de Investigación

### 1️⃣ Impacto de la IA en el salario

¿Cómo influye la especialización en Inteligencia Artificial en el salario de los desarrolladores, considerando nivel de experiencia y región?

### 2️⃣ Habilidades de Alto Valor

¿Qué habilidades asociadas con IA están relacionadas con mejores salarios y mayor demanda global?

---

## 🛠️ Metodología

El análisis se realizó en Python dentro de un entorno Jupyter Notebook.

### **1. Descarga y Carga del Dataset**

Se utilizó **KaggleHub** para descargar automáticamente el dataset.

### **2. Limpieza y Exploración Inicial**

* Inspección de columnas y primeros registros.
* Verificación de tipos de datos.
* Revisión de valores nulos o inconsistencias.

### **3. Ingeniería de Características**

Se creó la columna `rol_ia`, clasificando puestos como:

* **IA**
* **No_IA**

Basado en palabras clave como *Machine Learning, NLP, Deep Learning, Computer Vision, AI Engineer, Research Scientist*.

### **4. Análisis Salarial**

Se evaluaron diferencias de salario según:

* Rol (IA vs No IA)
* Nivel de experiencia (`EN`, `MI`, `SE`, `EX`)
* Distribución general de salarios

Se realizó un enfoque especial en roles de seniority alto (SE y EX), tal como se desarrolla en el notebook.

### **5. Análisis de Habilidades**

Se analizaron:

* Frecuencia de habilidades técnicas solicitadas
* Salario asociado a cada skill
* Identificación de habilidades de alto impacto

---

## 📈 Resultados e Insights Clave

### 🔹 1. La IA incrementa el salario en niveles altos

El análisis mostró que para niveles **Senior (SE)** y **Executive (EX)**, los roles relacionados con IA presentan un salario promedio superior al de roles No IA.

Esta brecha es consistente, aunque no extremadamente pronunciada, y se mantiene en diferentes países.

---

### 🔹 2. Relación entre Experiencia y Salario

La tendencia observada confirma:

> **A mayor seniority, mayor salario**, independientemente del rol y región.

Además, la transición entre cada nivel (EN → MI → SE → EX) muestra incrementos salariales claros y sostenidos.

---

### 🔹 3. Distribución de Salarios

El notebook reveló que:

* La mayoría de los salarios se concentran en un rango medio.
* Existen outliers asociados a roles muy especializados o regiones de alto costo.

---

### 🔹 4. Habilidades Más Demandadas

Se identificaron las skills con mayor frecuencia en ofertas laborales. Este análisis permite observar:

* Qué tecnologías dominan el mercado actual.
* Qué lenguajes y frameworks son imprescindibles.

### 🔹 5. Habilidades Mejor Pagadas

El cruce entre salario y habilidades mostró que:

* Las habilidades más especializadas **no son las más frecuentes**,
* pero sí están asociadas a los **salarios más altos**.

Esto sugiere nichos de gran valor para desarrolladores avanzados.

---

## 💻 Tecnologías Utilizadas

* **Python**
* **Pandas** — limpieza y análisis de datos
* **Matplotlib** — visualizaciones
* **Seaborn** — visualización estadística
* **KaggleHub** — descarga automatizada del dataset

---

## 📂 Estructura del Repositorio

```
├── data/
│   └── dataset.csv
├── notebooks/
│   └── ProyectoFinal_ARTONI.ipynb
├── src/
│   ├── procesamiento.py
│   └── visualizaciones.py
└── README.md
```

---

## 🚀 Conclusión Final

El análisis demuestra que el mercado laboral en IA continúa creciendo con fuerza. Roles especializados en Inteligencia Artificial presentan mejores salarios, especialmente en niveles de seniority altos.

Además, habilidades avanzadas —aunque poco frecuentes— generan oportunidades económicas muy significativas.

Este trabajo permite entender no solo el estado actual del mercado, sino también hacia dónde se dirige la demanda global de talento en IA.
