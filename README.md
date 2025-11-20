​🤖 Análisis del Mercado Laboral y Tendencias Salariales en Inteligencia Artificial (2025)
​📌 Descripción General del Proyecto
​Este proyecto es un análisis de datos enfocado en comprender la evolución y las dinámicas salariales del mercado global de empleo en Inteligencia Artificial (IA). Utilizando un extenso dataset con más de 15.000 ofertas de trabajo, el objetivo es identificar las tendencias salariales, las habilidades más demandadas y el impacto de la especialización en IA en diferentes contextos geográficos y niveles de experiencia.
​El análisis busca responder a la pregunta de qué exigen las grandes empresas y cómo se posiciona la IA en el panorama laboral actual.
​💡 Preguntas Clave de Investigación
​El proyecto se centró en dos preguntas fundamentales:
​Impacto de la IA en el Salario: ¿Cómo influye la adopción y especialización en Inteligencia Artificial en los salarios de los desarrolladores, considerando su nivel de experiencia y la región donde trabajan?
​Habilidades de Alto Valor: ¿Qué habilidades relacionadas con IA están más asociadas a salarios más altos y a una mayor demanda laboral entre desarrolladores a nivel global?
​🛠️ Metodología
​El análisis se llevó a cabo mediante un pipeline de procesamiento de datos en Python (Pandas), complementado con visualizaciones (Matplotlib y Seaborn).
​Pasos Principales:
​Adquisición y Limpieza de Datos: Se cargó el dataset Global AI Job Market & Salary Trends 2025 y se realizó una limpieza inicial, verificando que no existían valores nulos ni duplicados en las columnas clave (salary_usd, experience_level, job_title).
​Ingeniería de Características: Se creó la columna rol_ia para categorizar los puestos de trabajo como directamente relacionados con IA (IA) o no (No_IA), basándose en la presencia de palabras clave como Machine Learning, Deep Learning, Computer Vision, NLP, entre otras.
​Análisis Salarial Estratificado: Se calculó el salario promedio diferenciando por el enfoque de IA (IA vs No_IA), el nivel de experiencia (EN, MI, SE, EX) y la ubicación geográfica de la compañía.
​Análisis de Habilidades: Se identificó y se cruzó la frecuencia de las habilidades requeridas con su salario promedio asociado, enfocándose en el Top 10 de skills mejor pagadas.
​📈 Resultados e Insights Clave
​Los principales hallazgos del análisis incluyen:
​Salario de Roles Senior/Ejecutivos: Para los niveles de experiencia Senior (SE) y Executive (EX), los roles clasificados como IA presentan un salario promedio ligeramente superior (aproximadamente USD $164,355) en comparación con los roles No_IA (aproximadamente USD $162,423).
​Regiones Mejor Pagadas: La ubicación de la compañía es un factor crucial. Países como Suiza y Noruega mostraron consistentemente los salarios promedio más altos en el mercado global, independientemente de si el rol era IA o No-IA.
​Habilidades de Alto Impacto: Se identificó que las habilidades más especializadas no siempre son las más frecuentes en las ofertas, pero sí están asociadas a los salarios más altos, revelando un nicho de alto valor en el mercado (Ver gráfico de Top 10 Habilidades).
​💻 Tecnologías Utilizadas
​Python
​Pandas (Para manipulación y limpieza de datos)
​Matplotlib y Seaborn (Para visualización de datos)
​KaggleHub (Para la descarga del dataset)
