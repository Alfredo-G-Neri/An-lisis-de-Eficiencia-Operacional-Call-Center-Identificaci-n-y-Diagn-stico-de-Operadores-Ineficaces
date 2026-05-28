# Análisis de Eficiencia Operacional Call Center: Identificación y Diagnóstico de Operadores Ineficaces

> **Impacto Comercial:** Identificación de problema SISTÉMICO (no individual) afectando 500+ operadores (23.9% de base). Root Cause Analysis en 5 dimensiones. Proyección de mejora: 25-40% en eficiencia operacional, 15-20% reducción en turnover, $500k-$1.2M en valor anual.

---

## 📋 Descripción del Proyecto

Análisis operacional integral ejecutado para empresa de telecomunicaciones con el objetivo de diagnosticar desempeño crítico de call center y generar plan de acción estratégico. El proyecto analizó 53,902 registros de llamadas durante período de 4 semanas, implementando **KPI Identification** con Percentile-based Thresholds para identificar operadores con underperformance.

El análisis reveló hallazgo crítico: el problema es **SISTÉMICO, no individual**. A través de **Root Cause Analysis** se identificaron 5 causas raíz: ambiente laboral deficiente, gestión interna fallida, presión extrema/sobrecarga, capacitación insuficiente, e incentivos desalineados.

Los 500+ operadores flagged se segmentaron en 3 categorías distintas ("Drowning" 2.8%, "Struggling" 4.7%, "Specific Issue" 16.4%), cada una requiriendo intervenciones diferenciadas. Las recomendaciones generadas contemplan impacto comercial cuantificable: $500k-$1.2M en valor anual con ROI de 2-5x.

---

## 🎯 Objetivo

Desarrollar análisis operacional que permita:
1. Identificar operadores con desempeño crítico usando metodología de KPI rigurosa
2. Caracterizar dimensiones de underperformance (missed calls, wait times, outgoing volume, internal ratio)
3. Ejecutar Root Cause Analysis determinando si problema es sistémico o individual
4. Segmentar operadores por tipo de problema para intervenciones específicas
5. Generar recomendaciones accionables con estimación de impacto financiero

---

## 🔴 Problema de Negocio

### Contexto
Empresa de telecomunicaciones con 2,000+ operadores en 5 centros de contacto enfrenta desempeño operacional deficiente impactando NPS scores, customer satisfaction y costos operacionales. Call center representa centro de costo (~$50M anuales) y customer touchpoint crítico simultáneamente.

### Desafío Específico
- **Síntoma:** NPS scores bajos, customer complaints elevados
- **Hipótesis inicial:** "Tenemos 500+ operadores malos que necesitan ser reemplazados"
- **Costo de solución:** Reemplazar 500 operadores = $5M+ en recruitment, training, turnover
- **Pregunta crítica:** ¿Es realmente problema de operadores individuales, o problema del SISTEMA?

### Preguntas de Negocio
1. ¿Cuántos operadores tienen desempeño realmente crítico?
2. ¿Cuáles son las causas raíz? ¿Sistémicas u organizacionales?
3. ¿Podemos mejorar sin reemplazar masivamente la base de operadores?
4. ¿Cuál es el impacto financiero potencial de mejoras?

---

## 🛠️ Tecnologías Utilizadas

### Lenguaje & Herramientas
- **Python 3.x** - Lenguaje principal
- **Pandas** - Data manipulation, filtering, grouping
- **NumPy** - Operaciones numéricas, percentiles
- **SciPy** - Statistical analysis (skewness, kurtosis, distributions)
- **Matplotlib & Seaborn** - Data visualization

### Metodologías & Técnicas
- **KPI Identification** - Definición de métricas operacionales
- **Percentile-based Thresholds** - 75º y 25º percentiles para flagging
- **Root Cause Analysis** - Sistemática para identificar causas subyacentes
- **Segmentation** - Clustering de operadores por patrón de problema
- **Descriptive Statistics** - Media, mediana, desv.est., percentiles, skewness
- **Correlation Analysis** - Entender relaciones entre métricas
- **Distribution Analysis** - Visualizar normalidad vs anomalías

### Infraestructura
- **Jupyter Notebook** - Development environment
- **Git/GitHub** - Version control
- **Python Virtual Environment** - Dependency management

---

## 🎓 Habilidades Demostradas

### 1. Operational Intelligence & KPI Design
- ✅ **KPI Definition:** Diseño de métricas operacionales relevantes (missed calls, wait time, outgoing volume, internal ratio)
- ✅ **Threshold Setting:** Metodología percentile-based para identificar "high-risk" vs normal
- ✅ **Metric Aggregation:** Cálculo de rates, ratios, distribuciones por operador
- ✅ **Composite Metrics:** Flagging basado en MÚLTIPLES KPIs simultáneamente

### 2. Root Cause Analysis & Critical Thinking
- ✅ **Systematic Analysis:** 4-punto evidencia framework (distribuciones, concentración, correlaciones, volume analysis)
- ✅ **Hypothesis Testing:** Planteamiento de hipótesis (individual vs sistémico) y validación con data
- ✅ **Causal Reasoning:** Entender por qué metrics correlacionan y qué significa
- ✅ **Systems Thinking:** Reconocer ciclos perpetuos (stress → performance → stress)

### 3. Data Analysis & Statistical Expertise
- ✅ **Distribution Analysis:** Evaluación de skewness, kurtosis, normalidad
- ✅ **Percentile-based Methods:** Uso de percentiles para flagging (no asume normalidad)
- ✅ **Correlation Analysis:** Cálculo e interpretación de correlaciones (¿causales o coincidencia?)
- ✅ **Outlier Detection:** Identificación de valores extremos (5.7 horas waiting time)

### 3. Segmentation & Classification
- ✅ **Unsupervised Categorization:** Agrupación de 500+ operadores en 3 segmentos sin etiquetas previas
- ✅ **Behavioral Pattern Recognition:** Identificación de "Drowning" vs "Struggling" vs "Specific Issue"
- ✅ **Persona Development:** Caracterización de cada segmento con métricas específicas
- ✅ **Intervention Planning:** Recomendaciones diferenciadas por segmento

### 4. Business Acumen & Strategic Thinking
- ✅ **Problem Framing:** Traducción de síntoma ("operadores malos") a pregunta analítica correcta
- ✅ **Impact Quantification:** Proyección de $500k-$1.2M en valor anual
- ✅ **ROI Calculation:** 2-5x retorno en inversión de intervenciones
- ✅ **Multi-dimensional Recommendations:** 5 intervenciones específicas con detalle de implementación

### 5. Communication & Executive Presence
- ✅ **Clear Findings:** Presentación de hallazgo crítico (problema es sistémico) de forma clara
- ✅ **Data Storytelling:** Narrativa coherente de data → insights → recomendaciones
- ✅ **Non-technical Audience:** Explicación de statistical concepts para management
- ✅ **Actionability:** Recomendaciones no son vague sino específicas y implementables

### 6. Problem-Solving & Analytical Framework
- ✅ **Hypothesis-Driven:** Comenzar con hipótesis ("operadores malos"), validar con data, pivotear si necesario
- ✅ **Multi-level Analysis:** Explorar problema en múltiples niveles (distribuciones, correlaciones, segments)
- ✅ **Critical Evaluation:** Cuestionar assumptions, buscar alternative explanations
- ✅ **Systemic Solutions:** Reconocer que problema requiere solución sistémica, no individual

---

## 🔗 Insights Relacionados

- **Análisis de Churn (Companion Project):** Similar metodología podría predecir qué customers abandonarán servicio
- **Training Effectiveness:** Post-intervention analysis para medir impacto de onboarding changes
- **Incentive Impact:** A/B test de esquemas de incentivos para determinar effectiveness

---

## 📝 Notas Técnicas

### Assumptions
- Datos de call records son completos y accurate (no sesgo de reporting)
- Período de 4 semanas es representativo de operación normal
- Distribuciones estatales reflejan true operational state (no anomalías temporales)
- Flagged operators no son nuevos hires en ramp (si, requeriría filtering)

### Limitaciones
- Análisis no incluye customer satisfaction scores (CSAT)
- No hay información de customer resolution satisfaction
- Temporal dimension limitada (4-week snapshot)
- Factores externos (seasonality, campaigns) no aislados

### Mejoras Futuras
- Time-series tracking: Cómo evolucionan métricas post-intervención
- Customer satisfaction correlation: Cómo missed calls impactan NPS
- Causal inference: A/B testing de interventions para validar causal impact
- Predictive modeling: ML para predecir qué operators mejorarán o abandonarán

---

## 👨‍💼 Autor

**José Alfredo González Neri**
- Data Analyst & Operational Intelligence Specialist
- Especialización: Root Cause Analysis, Operational Intelligence, KPI Design
- Email: j.alfredo.gn1@gmail.com
- LinkedIn: linkedin.com/in/jose-alfredo-gonzalez-neri/
- GitHub: github.com/Alfredo-G-Neri

---

## 📄 Licencia

Este proyecto está disponible bajo licencia MIT. Siéntete libre de usar, modificar y distribuir.

---

**Última actualización:** Mayo 2026  
**Status:** ✅ Production Ready
