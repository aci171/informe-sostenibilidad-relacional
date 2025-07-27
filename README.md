# 🧭 Generador de Informes con Sostenibilidad Relacional

Esta aplicación web permite generar informes estructurados y personalizados en torno a la **sostenibilidad relacional** dentro de organizaciones con carisma, utilizando el modelo de lenguaje **Gemini 2.5 Pro** de Google.

Los usuarios pueden subir documentos (`.pdf`, `.docx`, `.txt`) o introducir texto manualmente para que la IA genere un informe claro, humano y profesional que podrá ser descargado en formato `.docx`.

---

## 🚀 Funcionalidades

✅ Subida de archivos en `.pdf`, `.docx`, `.txt`  
✅ Entrada de texto manual  
✅ Generación automática de informes con Gemini  
✅ Visualización del resultado en pantalla  
✅ Descarga directa del informe en `.docx`  
✅ Interfaz web sencilla, adaptable y rápida (Streamlit)

---

## ⚙️ Requisitos

- Cuenta en [Google AI Studio](https://aistudio.google.com/app/apikey) con una **API Key de Gemini**
- Cuenta en [GitHub](https://github.com)
- Cuenta en [Streamlit Cloud](https://streamlit.io/cloud) para desplegar la app

---

## 🛠 Instalación local (opcional)

```bash
git clone https://github.com/tu-usuario/informe-sostenibilidad-relacional.git
cd informe-sostenibilidad-relacional
pip install -r requirements.txt
streamlit run streamlit_app.py
```

Agrega tu clave API en el archivo `.streamlit/secrets.toml`:

```toml
GEMINI_API_KEY = "tu_clave_de_api"
```

---

## ☁️ Despliegue en Streamlit Cloud

1. Crea un repositorio privado y sube el código
2. Accede a [Streamlit Cloud](https://streamlit.io/cloud) y selecciona “New App”
3. Elige el repositorio y establece el archivo principal como:

```
streamlit_app.py
```

4. En la sección **Secrets**, añade tu clave de API:

```toml
GEMINI_API_KEY="tu_clave_de_api"
```

5. Pulsa **Deploy**

---

## 📄 Créditos

Desarrollado por [Tu nombre o institución]  
Basado en la API de Google Generative AI (Gemini) y construido con Streamlit

---

## 🛡️ Licencia

Este proyecto es de uso privado. Todos los derechos reservados.
