# TelecomX
Muestra del desarrollo de los desafíos TelecomX 1 y 2 del programa Alura Latam para optar por la certificación en Ciencia de Datos.

La primera parte de este proyecto forma parte del desafío "Churn de Clientes" de Telecom X.
El objetivo es comprender los factores que influyen en la evasión (churn), a partir de la exploración, limpieza y análisis de datos de clientes.

El análisis busca:

Identificar patrones en clientes que cancelan vs. los que permanecen.

Proporcionar insights que ayuden a diseñar estrategias de retención.

Preparar los datos para futuros modelos de Machine Learning predictivos.

📂 Estructura del Proyecto
TelecomX/
│── TelecomX_Data.json               # Dataset original
│── CarolinMejia_TelecomX_LATAM.ipynb # Notebook principal con el análisis
│── README.md                        # Documentación del proyecto

📊 Ejemplos de Análisis y Gráficos
Distribución de Churn

Se observa que cerca del 27% de los clientes cancelaron el servicio:


(Ejemplo ilustrativo, reemplaza con tu propio gráfico del notebook)

Evasión por tipo de contrato

Los contratos mensuales concentran la mayor proporción de cancelaciones:

Gasto total y churn

Los clientes con menor gasto tienden a cancelar con mayor frecuencia:

📈 Insights Principales

Clientes con contratos mensuales muestran mayor evasión.

El método de pago electrónico se asocia con más cancelaciones.

A mayor tiempo de contrato, menor probabilidad de churn.

Programas de fidelización y mejoras en los pagos digitales pueden reducir la evasión.

⚙️ Instrucciones de Ejecución

Clona este repositorio:

git clone https://github.com/tu-usuario/TelecomX.git
cd TelecomX


Instala las dependencias necesarias:

pip install -r requirements.txt


(Crea un archivo requirements.txt con: pandas, numpy, matplotlib, seaborn, jupyter)

Abre el notebook en Jupyter o Google Colab:

jupyter notebook CarolinMejia_TelecomX_LATAM.ipynb


Ejecuta cada celda en orden para reproducir el análisis.

🚀 Próximos Pasos

Implementar modelos predictivos (Regresión Logística, Random Forest, XGBoost).

Crear un dashboard interactivo para monitoreo de churn.
