# Performance Analysis – CallMeMaybe Call Center

**Live dashboard:** https://https://public.tableau.com/views/Callmemaybe_17579587067620/DashboardCallMeMaybe?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link


## Project Description
This project analyzes call center performance for the virtual telecom service **CallMeMaybe**, aiming to identify inefficiencies in operators and customer service.

## Objective
The main goals of this project were to:
- Reduce the number of missed incoming calls.  
- Decrease customer waiting times before being attended.  
- Improve productivity in outgoing calls when appropriate.  

## Tools & Libraries
- Python (pandas, numpy, matplotlib, seaborn)  
- Statistical analysis and exploratory data analysis (EDA)  

## Methodology
1. Data validation and cleaning (removal of duplicates, normalization of dates, categorical adjustments).  
2. Exploratory analysis of call volumes by type (incoming, outgoing, internal).  
3. Calculation of missed call rates and wait times.  
4. Segmentation of clients based on usage and inefficiency patterns.  

## Key Results
- **Data quality:** cleaned 9% duplicates, standardized categories → dataset reliable for analysis.  
- **Call distribution:** 75% of all calls are outgoing, but 99% of incoming are external (real customers).  
- **Missed calls:** more than half of incoming external calls (52.7%) are missed → 1 out of 2 customers never gets attended.  
- **Waiting times:**  
  - 25% of calls end instantly (abandoned).  
  - Median wait time: ~58 seconds.  
  - 10% of customers wait >23 minutes.  
- **Call durations:**  
  - 25% last <38s (likely abandons).  
  - Median of 2.5 minutes.  
  - 10% exceed 27 minutes, 5% reach up to 45 minutes.  
- **Client patterns:**  
  - A small group generates most calls, saturating operations.  
  - Some clients are never attended at all.  
  - Others consume disproportionate time, affecting efficiency.  

## Conclusion
The analysis reveals **structural inefficiencies**:  
- Half of customers are not being served.  
- Waiting times are unacceptably high.  
- A few clients disproportionately impact operations.  

Immediate corrective measures and differentiated client strategies are required to improve service quality and avoid customer churn.  

---

# Versión en Español

## Descripción del proyecto
Este proyecto analiza el desempeño del call center del servicio de telefonía virtual **CallMeMaybe**, con el objetivo de identificar ineficiencias en la operación y en la atención al cliente.

## Objetivo
Los principales objetivos del análisis fueron:  
- Reducir el número de llamadas entrantes perdidas.  
- Disminuir el tiempo de espera de los clientes antes de ser atendidos.  
- Mejorar la productividad en llamadas salientes cuando corresponde.  

## Herramientas y librerías
- Python (pandas, numpy, matplotlib, seaborn)  
- Análisis estadístico y exploratorio (EDA)  

## Metodología
1. Validación y limpieza de datos (eliminación de duplicados, normalización de fechas, ajuste de categorías).  
2. Análisis exploratorio de volúmenes de llamadas por tipo (entrantes, salientes, internas).  
3. Cálculo de tasas de llamadas perdidas y tiempos de espera.  
4. Segmentación de clientes según patrones de uso e ineficiencia.  

## Resultados principales
- **Calidad de datos:** se eliminaron 9% de duplicados y se estandarizaron variables → dataset confiable.  
- **Distribución de llamadas:** 75% son salientes; de las entrantes, 99% provienen de clientes reales.  
- **Llamadas perdidas:** más de la mitad de las entrantes externas (52.7%) se pierden → 1 de cada 2 clientes no logra ser atendido.  
- **Tiempos de espera:**  
  - 25% de las llamadas terminan de inmediato (abandono).  
  - Mediana de espera: ~58 segundos.  
  - 10% de los clientes espera más de 23 minutos.  
- **Duración de llamadas:**  
  - 25% duran menos de 38s (probablemente abandonos).  
  - Mediana de 2.5 minutos.  
  - 10% supera los 27 minutos y 5% llega hasta 45 minutos.  
- **Patrones de clientes:**  
  - Un grupo reducido genera la mayoría de llamadas, saturando la operación.  
  - Algunos clientes nunca reciben atención.  
  - Otros consumen tiempos desproporcionados, afectando la eficiencia global.  

## Conclusión
El análisis revela **ineficiencias estructurales**:  
- La mitad de los clientes no recibe atención.  
- Los tiempos de espera son excesivos.  
- Unos pocos clientes distorsionan la operación.  

 Se requieren medidas correctivas inmediatas y estrategias diferenciadas por cliente para mejorar la calidad del servicio y evitar la fuga de clientes.  
