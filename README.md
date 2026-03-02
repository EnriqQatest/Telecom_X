📡 **Telecom X: Análisis de Evasión de Clientes (Churn)**

Este proyecto realiza un análisis profundo de los datos de Telecom X para identificar los factores críticos que llevan a la pérdida de clientes (Churn) y proponer soluciones estratégicas basadas en datos.

🎯 **Propósito del Análisis**

El objetivo principal es transformar datos crudos en información accionable para reducir la tasa de abandono de la compañía. El análisis busca:

Identificar el perfil demográfico y de consumo de los clientes que cancelan el servicio.

Evaluar el impacto de los tipos de contrato y métodos de pago en la retención.

Proporcionar recomendaciones estratégicas para mejorar la lealtad del cliente.

📂 **Estructura del Proyecto**

El proyecto está organizado de la siguiente manera:

Telecom_X_.ipynb: Notebook principal que contiene todo el flujo de trabajo (Extracción, Limpieza, EDA y Conclusiones).

Secciones del Notebook:

Extracción: Conexión a la API/URL para obtención de datos JSON.

Transformación: Normalización de datos anidados y limpieza de tipos de datos.

EDA (Análisis Exploratorio): Visualizaciones estadísticas y segmentación.

Insights: Hallazgos clave derivados del análisis.

📊 **Gráficos e Insights Clave**

A continuación, se presentan algunos de los hallazgos más relevantes:

1. Tasa de Abandono General
Se identificó que el 26.5% de los clientes han abandonado la empresa. Este es el punto de partida para entender el riesgo financiero.

2. Impacto del Tipo de Contrato
Los clientes con contratos "Mes a mes" representan la gran mayoría de las cancelaciones. Existe una correlación directa entre la estabilidad del contrato y la retención.

3. Métodos de Pago y Fricción
El uso de Electronic Check está vinculado a una mayor tasa de churn, mientras que los pagos automáticos muestran una base de clientes mucho más sólida.

4. Servicios y Valor Añadido
Los clientes que carecen de servicios como Seguridad Online o Soporte Técnico tienen una probabilidad significativamente mayor de irse.

🛠️ **Instrucciones de Ejecución**

Para replicar este análisis en tu entorno local o en la nube, sigue estos pasos:

Requisitos Previos:

Tener instalado Python 3.x.

Instalar las librerías necesarias:

Bash
pip install pandas requests matplotlib seaborn plotly
Ejecución en Google Colab:

Sube el archivo Telecom_X_.ipynb a Google Colab.

Asegúrate de tener conexión a internet, ya que el notebook descarga los datos directamente desde un repositorio externo.

Ejecuta las celdas en orden secuencial (Runtime > Run all).

Ejecución Local:

Clona este repositorio.

Abre el notebook con Jupyter Notebook o VS Code.

Ejecuta las celdas de extracción para cargar el dataset JSON.

💡 **Recomendaciones Estratégicas**

Migración de Contratos: Incentivar el paso de contratos mensuales a anuales.

Digitalización de Pagos: Promover el registro de tarjetas de crédito para cobros automáticos.

Venta Cruzada (Cross-selling): Ofrecer paquetes de soporte técnico a usuarios de fibra óptica.

**Análisis realizado por el equipo de Data Science - Telecom X.**
