# Asistente Correos – Email Assistant (LangChain / LLM Agent)

Este repositorio contiene un asistente inteligente para generar, corregir y clasificar correos electrónicos utilizando modelos de lenguaje.  
El proyecto está implementado en un **notebook Jupyter (`AsistenteCorreos.ipynb`)** y utiliza herramientas de LangChain, agentes, routers y un conjunto de prompts especializados.

---

## 🚀 Características principales

- Simulación de respuestas a correos electrónicos.
- Clasificación y análisis de mensajes.
- Arquitectura basada en:
  - **Router**
  - **State Graph**
  - **Tools**
  - **Agente principal**
- Integración con proveedores de LLM compatibles con LangChain.


## 🛠️ Requisitos

Antes de ejecutar el proyecto, asegúrate de tener instalado:

- Python 3.10+
- pip o conda
- Una clave API para tu proveedor de OpenAI

---

## 📦 Instalación

Clona este repositorio:

```bash
git clone https://github.com/degalvis/email-assistant-agent.git
```

Instalar las dependencias
```bash
pip install -r requirements.txt
```

## Como ejecutar el archivo
Para ejecutar el script, se debe hacer en el siguiente orde:

1. Configuración e imports
2. Tools
3. State
4. Router
5. Agente
6. Ejecuciones de prueba

