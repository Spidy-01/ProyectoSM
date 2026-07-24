# 🤖 ProyectoSM
Se encuentra todo lo relacionado a la creacion de un proyecto IA

## 1. Requisitos
Porfavor, asegurarse de contar con los siguientes elementos antes de que se inicie la ejecución:
* **Python 3.10** o superior instalado en el sistema.
* Una **API KEY activa de Google Gemini GenAI** (Google AI Studio).

---
## 2. ⚙️ Opcional (Crear y activar un Entorno Virtual)
Para aislar las dependencias del proyecto

👉 **En windows:**
      
    python -m venv venv
    venv\Scipts\activate

👉 **En Linux / macOS:**
      
    python3 -m venv venv
    source venv/bin/activate

## 4. 📦 Instalar Las Dependencias
Ejecutar el pip de las librerias en nuestro entorno jupyter, debe verse asi

    !pip install -q langchain langchain-google-genai chromadb pydantic

## 5. 🔑 Configurar La API KEY de Google
Se debe configurar en el **Bloque 01**, asignar la clave de Gemini antes de iniciar el cliente, debe verse así:

```
  import os
  os.environ["GOOGLE_API_KEY"] = "TU_API_KEY_AQUI"
```

## 6. 🚀 Ejecutar con normalidad el resto de los bloques
En cada celda de los bloques se ejecuta cada uno en orden como va avanzando
## 7. 💬 Interacción con el Asistente
- AL ejecutar el Bloque, aparecerá un cuadro interactivo (input).
- En el cualpodemos ingresar cualquier pregunta (ojo: relacionada con los documentos).
- Despues de realizar la consulta, escribir *salir* y presionar Enter.

---
Debería de verse así el chatbot

```text
============================================================
🤖 SISTEMA RAG ACTIVADO
Escribe 'salir' para finalizar la sesión.
============================================================

Tú: ¿Cuál es el plazo de pago establecido en las cláusulas?
