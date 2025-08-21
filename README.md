# tripleten_final_proy

## 📂 Contenido del repositorio

### 1. Notebooks de análisis
- `Plan de trabajo - Analisis de desempeño de operadores telefonicos CALLMEMAYBE.ipynb` → Plan de trabajo  de series temporales (llamadas y duración) con descomposición de tendencia, estacionalidad y residuo.  
- `Analisis de factibilidad de granja de sandias en Brasil.ipynb` → Continuación a Prueba A/B sobre factibilidad de una granja de sandías en Brasil realizada en 2020-2021.  
- `Analisis de mercado de Libreria.ipynb` → Consultas SQL y análisis exploratorio en base de datos de libros/autores para entender qué mueve al lector moderno, comprender al mercado de libros y generar una propuesta de valor para un nuevo producto.
- `Analisis de desempeño de operadores telefonicos CALLMEMAYBE.ipynb` → Desarrollo del proyecto de analisis de desempeño de operadores telefonicos de la empresa CallMeMaybe basado en el plan de trabajo expuesto anteriormente.

# 📞 Proyecto Final - Análisis de desempeño de Operadores telefónicos

Este repositorio contiene el proyecto final de análisis de datos aplicado a una empresa de telecomunicaciones.  
El objetivo principal fue identificar operadores **eficientes vs. ineficientes**, analizar patrones de llamadas, y validar hipótesis mediante pruebas estadísticas.

### 2. Dashboard interactivo
- 📊 [Dashboard en Tableau Public](https://public.tableau.com/views/ProyectoFinalTripleTen-KS/Dashboard1?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  
Incluye visualizaciones dinámicas para explorar métricas clave y segmentación de operadores.

### 3. Presentación final
- 🎤 [`Proyecto_Final_Telecom.pdf`](Proyecto_Final_Telecom.pdf)  
Presentación ejecutiva con hallazgos, hipótesis validadas, resultados principales y recomendaciones.

---

## 🎯 Objetivos del análisis
1. Identificar eficiencia de operadores.  
2. Analizar patrones de llamadas (entrantes, salientes, internas, externas).  
3. Detectar factores de ineficacia.  
4. Validar hipótesis sobre comportamiento de operadores y clientes.  

---

## 📈 KPI’s definidos
Un operador se considera **eficiente** si cumple al menos 2 de los siguientes criterios (por cuatrimestre):

- Número de llamadas salientes externas: **≥ 239**  
- Segundos promedio de llamada: **≥ 68**  
- Número de llamadas perdidas: **≤ 111**  
- Segundos promedio de espera en llamada: **≤ 42**

---

## 🧪 Hipótesis probadas
- **H1:** Diferencia significativa en llamadas salientes externas entre operadores eficientes e ineficientes.  
- **H2:** Operadores ineficientes presentan mayor número de llamadas perdidas.  
- **H3:** Tiempo de espera promedio significativamente mayor en operadores ineficientes.  
- **H4:** El `tariff_plan` impacta en el volumen de llamadas entrantes.  

---

## 📊 Resultados principales
- La ineficacia del operador se correlaciona con **menos llamadas salientes externas** y **mayor tiempo de espera**.  
- Operadores ineficientes muestran **más llamadas perdidas**.  
- El **plan tarifario** del cliente impacta significativamente en la carga de llamadas.  
- La **antigüedad (`date_start`)** del cliente no influye de forma significativa.  

---

## ✅ Conclusiones
- La ineficacia de operadores es medible con datos objetivos.  
- Recomendaciones:
  - **Capacitación** en gestión de llamadas externas.  
  - **Monitoreo continuo** de tiempos de espera y llamadas perdidas.  
  - **Asignación estratégica** de clientes según plan tarifario.  

---

## 👤 Autor
**Kevin Sánchez**  
Proyecto final - TripleTen


