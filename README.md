# Alura Telecom X
### Repositorio para el análisis de evasión de clientes de Telecom X

---

### 📊 Análisis de Evasión de Clientes (Churn) - Challenge Data Science
Este proyecto es parte de un desafío de Data Science aplicado a la industria de las telecomunicaciones.
El objetivo es analizar el fenómeno del Churn (cancelación de clientes) en la empresa Telecom X, identificando los factores demográficos, financieros y contractuales que influyen en la pérdida de usuarios para proponer estrategias de retención.

### 🎯 Objetivo del Proyecto
Realizar un Análisis Exploratorio de Datos (EDA) que permita:
Identificar el Churn: Determinar la proporción real de clientes que abandonan la compañía.
Perfiles de Riesgo: Analizar cómo influyen variables como el género, ser adulto mayor o tener dependientes en la evasión.
Análisis de Servicios: Evaluar si el tipo de internet o los servicios adicionales (seguridad, backup) reducen el riesgo de churn.
Impacto Financiero: Estudiar la relación entre los cargos mensuales, el gasto total y la permanencia del cliente.
ETL Eficiente: Consumir y normalizar datos complejos desde una API en formato JSON.

### 🛠️ Tecnologías Utilizadas
Python 3.12
Pandas: Para la extracción de la API, normalización de JSON (flattening) y limpieza de datos.
Matplotlib & Seaborn: Para visualizaciones estratégicas, análisis de densidad (KDE) y matrices de correlación.
Google Colab: Entorno de desarrollo para el procesamiento de los datos.

### 📈 Visualizaciones Incluidas
Gráfico de Torta (Pie Chart): Distribución global de la tasa de evasión.
Gráficos de Barras (Countplots): Comparativa de evasión por tipo de contrato y métodos de pago.
Gráficos de Densidad (KDE Plot): Análisis de la permanencia (tenure) frente a la evasión.
Gráficos de bigotes (Boxplot): Comparativa de cargos mensuales vs. churn para identificar sensibilidad al precio.
Matriz de Correlación: Identificación de variables con mayor peso en la decisión de salida.

### Gráficos Visibles
1. Distribución Global de Evasión
Muestra la proporción de clientes que se han ido vs. los que permanecen.
<img width="283" height="255" alt="image" src="https://github.com/user-attachments/assets/9258f584-422c-4f23-8e94-06aaaa14cfb8" />


---
2. Evasión por Tipo de Contrato
Análisis del riesgo según el compromiso contractual del cliente.
<img width="374" height="281" alt="image" src="https://github.com/user-attachments/assets/db600020-310f-4856-953b-4bb0b1c532cb" />


---
3. Relación Cargo Mensual vs. Evasión
Identificación de la sensibilidad del cliente al precio del servicio.
<img width="370" height="280" alt="image" src="https://github.com/user-attachments/assets/247630bd-02e8-4394-b408-e5b6e2f746af" />


---
4. Densidad de Evasión según Meses de Contrato
Visualización del punto crítico de tiempo donde los clientes suelen cancelar.
<img width="386" height="275" alt="image" src="https://github.com/user-attachments/assets/a9151de8-1b62-482e-a291-ebd3fbe6b222" />


---
5. Matriz de Correlación entre Variables (Extra)
Mapa de calor que muestra qué factores financieros y de servicio están más ligados al Churn.
<img width="341" height="299" alt="image" src="https://github.com/user-attachments/assets/8f4b7756-cf5a-43fc-95cc-15ed334bb90b" />


---
### 📋 Estructura del archivo Python: Evasión de Clientes (Churn) - Telecom X
1. Extracción
2. Transformación
3. Carga y Análisis Exploratorio de Datos (EDA)
4. Informe final

---
### 🎯 Conclusiones e Insights
El "Mes a Mes" es el riesgo #1: La flexibilidad del contrato sin permanencia facilita que el cliente se retire ante cualquier insatisfacción o oferta de la competencia.
Barrera del Primer Año: Los primeros meses son críticos. Si no se logra fidelizar al cliente en su primer semestre, es muy probable que se retire.
Fuga de "Alto Valor": No solo se van muchos clientes, sino que se van aquellos que pagan facturas más altas, lo que impacta severamente el flujo de caja.

### 🚀 Cómo ejecutar este proyecto
1.  **Clona este repositorio:**
    ```bash
    git clone https://github.com/MervyMulatillo/TelecomX-Churn-Analysis.git
    ```
2.  **Abre el archivo `.ipynb`** en Google Colab o Jupyter Notebook.
3.  **Asegúrate de tener instaladas las librerías necesarias:**
    ```bash
    pip install pandas numpy matplotlib seaborn requests
    ```
4.  **Ejecuta las celdas** El notebook descargará automáticamente los datos de la API de Telecom X y generará el análisis.


#### Autor: [Mervy Mulatillo Piñin]
#### Curso/Challenge: Alura Latam - Challenge Data Science - Telecom X
