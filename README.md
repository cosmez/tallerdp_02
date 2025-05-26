# Taller 02 - Estructura y Razonamiento en Modelos de Lenguaje

Este repositorio contiene material educativo completo para un taller sobre Large Language Models (LLMs), enfocado en aspectos fundamentales, implementación práctica y uso avanzado de modelos de lenguaje.

## 📋 Descripción del Proyecto

El taller está diseñado para proporcionar una comprensión profunda de los modelos de lenguaje, desde su estructura interna hasta su implementación práctica usando APIs como Gemini y frameworks como HuggingFace. El contenido está organizado en módulos progresivos que cubren tanto conceptos teóricos como ejercicios prácticos.

## 🗂️ Estructura del Proyecto

### 1. Estructura Interna
**Carpeta: `1. Estructura interna/`**
- `1-Tokens.ipynb` - Introducción a la tokenización y manejo de tokens
- `2-Contexto.ipynb` - Comprensión del contexto en LLMs
- `3-Parametros.ipynb` - Parámetros configurables de los modelos

### 2. Razonamiento Interno
**Carpeta: `2. Razonamiento Interno/`**
- `1-Razonamiento.ipynb` - Cómo razonan los LLMs internamente

### 3. Principios de Diseño de Prompts
**Carpeta: `3. Principios de diseño de prompts/`**
- `1-Prompting.ipynb` - Técnicas y mejores prácticas para diseño de prompts

### 4. Formato de Conversación
**Carpeta: `4. Formato Conversacion/`**
- `1-Conversacion.ipynb` - Manejo de conversaciones y formatos de diálogo

### 5. Herramientas y Agentes
**Carpeta: `5. Herramientas/`**
- `1-Herramientas.ipynb` - Tool calling y uso de herramientas externas
- `2-Agente.ipynb` - Implementación de agentes inteligentes

### 6. API de Gemini
**Carpeta: `6. Gemini/`**
- `1-Gemini.ipynb` - Integración y uso avanzado de la API de Gemini

### 7. Contenido Extra
**Carpeta: `7. Extra/`**
- `Modelos locales y HuggingFace.ipynb` - Trabajo con modelos locales y HuggingFace
- `Runtimes,_Cuantizacion,_Ollama,_LM_Studio.ipynb` - Runtimes locales, cuantización y herramientas

## 🚀 Instalación y Configuración

### Prerrequisitos
- Python 3.8 o superior
- Jupyter Notebook o JupyterLab
- Acceso a API de Google Gemini (API Key requerida)

### Instalación

1. **Clonar el repositorio:**
```bash
git clone <repository-url>
cd tallerdp_02
```

2. **Crear entorno virtual (recomendado):**
```bash
python -m venv venv
# En Windows:
venv\Scripts\activate
# En macOS/Linux:
source venv/bin/activate
```

3. **Instalar dependencias:**
```bash
pip install -r requirements.txt
```

### Configuración de API Keys

1. **Google Gemini API:**
   - Crear archivo `.env` en la raíz del proyecto
   - Agregar tu API key: `GOOGLE_API_KEY=tu_api_key_aqui`
   - Consultar las imágenes en `1. Estructura interna/Img/` para obtener la API key

## 🛠️ Dependencias Principales

- **google-generativeai**: Integración con la API de Gemini
- **transformers**: Biblioteca de HuggingFace para modelos transformer
- **torch**: Framework de deep learning PyTorch
- **pandas**: Manipulación y análisis de datos
- **tiktoken**: Tokenización de OpenAI
- **numpy**: Computación numérica

Ver `requirements.txt` para la lista completa de dependencias.

## 📚 Cómo Usar Este Taller

### Orden Recomendado
1. Comenzar con **Estructura Interna** para entender los fundamentos
2. Continuar con **Razonamiento Interno** para comprender el funcionamiento
3. Aprender **Principios de Diseño de Prompts** para mejores interacciones
4. Explorar **Formato de Conversación** para diálogos efectivos
5. Implementar **Herramientas y Agentes** para casos de uso avanzados
6. Practicar con **API de Gemini** para integración real
7. Experimentar con **Contenido Extra** para casos especializados

### Ejecutar los Notebooks
```bash
# Iniciar Jupyter Notebook
jupyter notebook

# O Jupyter Lab
jupyter lab
```

## 🔧 Funcionalidades Cubiertas

### Conceptos Fundamentales
- ✅ Tokenización y manejo de tokens
- ✅ Contexto y ventanas de atención
- ✅ Parámetros configurables (temperatura, top-p, etc.)
- ✅ Razonamiento interno de los LLMs

### Técnicas Avanzadas
- ✅ Diseño optimizado de prompts
- ✅ Conversaciones multi-turno
- ✅ Tool calling y function calling
- ✅ Implementación de agentes

### Integraciones Prácticas
- ✅ API de Google Gemini
- ✅ HuggingFace Hub y Transformers
- ✅ Modelos locales y cuantización
- ✅ Runtimes locales (Ollama, LM Studio)

## 🎯 Objetivos de Aprendizaje

Al completar este taller, serás capaz de:

1. **Comprender** la estructura interna y funcionamiento de los LLMs
2. **Diseñar** prompts efectivos para diferentes casos de uso
3. **Implementar** conversaciones inteligentes y agentes
4. **Integrar** APIs de LLMs en aplicaciones reales
5. **Trabajar** con modelos locales y herramientas especializadas
6. **Optimizar** el rendimiento usando parámetros avanzados


---

**Nota:** Este taller está diseñado para ser ejecutado tanto en entornos locales como en Google Colab. Algunas celdas pueden contener código específico para Colab que debe ser adaptado para ejecución local.

