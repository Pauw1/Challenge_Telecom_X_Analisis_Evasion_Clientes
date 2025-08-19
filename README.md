# Challenge_Telecom_X_Analisis_Evasion_Clientes
Challenge N°2 de Especialización en Data Sience 2025 - Grupo 8 del Programa ONE con Alura Latam

# 📊 Telecom X - Análisis de Evasión de Clientes (Churn Analysis)

## 📌 Descripción del Proyecto  
Este proyecto corresponde al **Challenge 2 de Data Science**, cuyo objetivo es **analizar la evasión de clientes (churn)** en una empresa de telecomunicaciones ficticia llamada **Telecom X**.  

Se implementó un flujo **ETL + EDA** para:  
- Extraer y limpiar los datos desde una API en formato JSON.  
- Transformar y normalizar tablas anidadas (`customer`, `phone`, `internet`, `account`).  
- Realizar un análisis exploratorio de datos (EDA) para identificar factores asociados al abandono de clientes.  
- Generar insights de negocio y recomendaciones estratégicas.  

---

## ⚙️ Tecnologías utilizadas  
- **Python 3.9+**  
- Librerías principales:  
  - `pandas`, `numpy` → Manipulación de datos  
  - `matplotlib`, `seaborn`, `plotly` → Visualización  
  - `requests` → Extracción desde API  
  - `scikit-learn` → Preparación para modelos predictivos  

---

## 🔍 Insights principales  

1. **Tipo de contrato es el factor más crítico**  
   - Clientes con contrato mensual presentan un 41% de abandono, mientras que en contratos de 2 años solo un 2.7%.  

2. **Método de pago influye fuertemente**  
   - El pago con *electronic check* tiene un 43% de churn, el más alto entre los métodos.  

3. **Internet de fibra óptica tiene mayor tasa de abandono**  
   - Indica posibles problemas de precio o calidad de servicio.  

4. **Segmentos de riesgo**  
   - Seniors, clientes sin dependientes y usuarios nuevos (<6 meses) muestran mayor probabilidad de churn.  

5. **Facturación mensual alta aumenta el abandono**  
   - Clientes con cargos >80 USD son más propensos a cambiar de proveedor.  

---

## 🚀 Próximos pasos  
- Preparar dataset final para **modelado predictivo de churn**.  
- Entrenar modelos de clasificación (L
