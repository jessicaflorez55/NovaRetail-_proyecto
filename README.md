# NovaRetail-_proyecto
Este proyecto analiza el comportamiento de clientes de NovaRetail+ con el objetivo de identificar qué variables están más asociadas con el ingreso anual generado.
Se trata de un análisis exploratorio y correlacional, donde se combinan métricas estadísticas y visualizaciones para detectar patrones relevantes, evitando interpretaciones causales incorrectas.

📂 Contenido
Project-NovaRetail.ipynb: Notebook con todo el análisis documentado
README.md: Documentación del proyecto
Visualizaciones:
Heatmap de correlación
Scatterplots de relaciones clave
Métodos utilizados:
Correlación de Pearson
Correlación de Spearman
Correlación punto biserial
V de Cramér

🎯 Objetivo del análisis
Identificar los principales drivers de comportamiento del cliente que están asociados con el ingreso anual, para apoyar decisiones de negocio en marketing, segmentación y retención.

🗂️ Datasets
Archivo: /datasets/novaretail_comportamiento_clientes_2024.csv
Registros: 15,000 filas
Variables:
Comportamiento: visitas_mes, compras_mes
Marketing: gasto_publicidad_dirigida
Cliente: edad, nivel_ingreso
Experiencia: satisfaccion
Segmentación: tipo_dispositivo, region
Binarias: miembro_premium, abandono
Objetivo: ingreso_anual

🔄 Proceso de análisis
Carga y exploración
Validación de estructura, tipos de datos y calidad
Preparación de datos
Revisión de variables numéricas, categóricas y binarias
Ajustes en tipos de datos (ej: edad)
Análisis exploratorio
Distribuciones
Identificación de patrones iniciales
Análisis correlacional
Pearson → relaciones lineales
Spearman → relaciones monotónicas
Punto biserial → variables binarias vs numéricas
V de Cramér → variables categóricas
Interpretación
Dirección, magnitud y significado de relaciones
Enfoque en correlación, no causalidad

🎯 Principales objetivos del análisis
Identificar variables con mayor asociación al ingreso anual
Detectar patrones de comportamiento relevantes
Evaluar impacto del marketing en el comportamiento
Identificar posibles correlaciones engañosas
Traducir hallazgos en decisiones de negocio

💡 Insights clave
Existe una correlación extremadamente alta entre compras_mes e ingreso_anual (0.97)
→ Indica una relación casi lineal: a mayor número de compras, mayor ingreso generado.
La relación entre visitas_mes y gasto_publicidad_dirigida (0.58) es moderada–alta
→ La publicidad sí influye en el tráfico, pero no lo explica completamente.
No todas las visitas se convierten en compras
→ Existe fricción en el funnel (oportunidad de optimización).
Se identifican posibles relaciones indirectas o mediadas
→ Por ejemplo: publicidad → visitas → compras → ingreso.
Presencia de posible colinealidad en variables de comportamiento
→ Especialmente en métricas cercanas a la conversión.

▶️ Cómo ejecutar el proyecto
Opción 1: Desde GitHub
Abre el repositorio
Ingresa al notebook .ipynb
Visualiza el análisis directamente en GitHub
Opción 2: Ejecutar localmente
Clona el repositorio:
git clone  
https://github.com/jessicaflorez55/NovaRetail-_proyecto 
