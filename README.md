# Hola, soy Adrián 👋

Ingeniero informático en formación, especializado en **Inteligencia Artificial**. Acabo de terminar nueve meses de prácticas en **NTT DATA** como desarrollador SAP y busco mi primera oportunidad profesional a jornada completa.

- 🎓 **Grado en Ingeniería Informática**, mención de Computación, en la **Universidad de Sevilla**. A falta de una asignatura; título previsto en 2027.
- 💼 **Prácticas en NTT DATA** (febrero – noviembre de 2026): desarrollo y soporte SAP con ABAP para un cliente del sector energético.
- 🤖 Mi área principal es la **IA aplicada**: LLMs, machine learning y automatización de procesos. Pero no me cierro a ninguna tecnología: lo que me interesa es resolver problemas reales.
- 📍 Mérida (Badajoz). Abierto a **remoto en España**, **híbrido** en cualquier ciudad o presencial en Extremadura.
- 🌍 Inglés B1 certificado, B2 en conversación.

## 🚀 Proyectos destacados

**Detección de fraude con un sistema multiagente de LLMs** — *Trabajo de Fin de Grado, defendido en octubre de 2026*
Sistema de dos capas para detección de fraude con tarjeta, ejecutado íntegramente en local: un detector tabular (**XGBoost** e **Isolation Forest**) que puntúa y prioriza las transacciones, y un departamento de **seis agentes sobre CrewAI** que interpreta los casos elevados y redacta los informes. La premisa de partida es una entidad que no puede enviar datos a un servicio externo, así que todo corre sin coste recurrente y sin salir de la máquina.

El trabajo está construido para responder a una pregunta concreta y medirla: ¿aporta algo poner una capa de agentes LLM sobre un detector de fraude? **La respuesta es negativa y está cuantificada**: la capa de agentes no mejora la detección, y concederle autoridad para descartar casos la degrada. El detector alcanza un AUC-PR de 0,883 en partición aleatoria y 0,797 en partición temporal, con P@50 = 1,00. Un modelo de 72B emite los mismos veredictos que uno de 14B a 1.790 veces el coste, y se ejecutó en una tarjeta de 16 GB mediante descomposición por capas.
→ [adrmurbau/tfg-multiagente-fraude](https://github.com/adrmurbau/tfg-multiagente-fraude)

**pdf2md**
Herramienta de escritorio que convierte PDFs a Markdown autocontenido optimizado para LLMs. Extrae texto, tablas e imágenes (comprimidas en base64) página a página, manteniendo el contexto visual del documento. Distribuido como `.exe` standalone sin dependencias.
→ [adrmurbau/pdf2md](https://github.com/adrmurbau/pdf2md)

**AIA Final Project – InceptionV3**
Clasificación de imágenes de flores con **InceptionV3** y fine-tuning, junto con ejercicios de ML clásico (árboles de decisión y random forests).
→ [adrmurbau/aia-inceptionv3-final-project](https://github.com/adrmurbau/aia-inceptionv3-final-project)

**Don Tello Golf Club – Odoo 16**
Módulo completo de Odoo para la gestión de un club de golf: socios, membresías, reservas, tarifas y escuelas deportivas.
→ [adrmurbau/odoo-don-tello](https://github.com/adrmurbau/odoo-don-tello)

**Shopify Price Optimizer**
Prototipo de optimización automática de precios para e-commerce: scraping de precios de la competencia, API backend y dashboard en React.
→ [adrmurbau/shopify-price-optimizer](https://github.com/adrmurbau/shopify-price-optimizer)

## 🛠️ Tecnologías

| | |
|---|---|
| **Lenguajes** | Python, Java, JavaScript, ABAP |
| **IA / ML** | LLMs, CrewAI, Ollama, XGBoost, TensorFlow / Keras, scikit-learn, visión por computador |
| **SAP** | ABAP, programas Z, informes ALV, SAP Script, módulos MM / SD / PM |
| **Backend y datos** | Odoo, PostgreSQL, APIs REST |
| **Frontend** | HTML, CSS, React |
| **Herramientas** | Git, Linux, Jupyter, PyInstaller, Tkinter, PyMuPDF, Pillow |

## 📬 Contacto

- 📧 [adrianmb41@gmail.com](mailto:adrianmb41@gmail.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/adrmurbau)
