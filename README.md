# Creación de sistemas RAG sobre bases de datos vectoriales

## Descripción

Este proyecto desarrolla un entorno para construir sistemas **RAG**, donde el texto se indexa en una  **Vector Store**. A partir de ahí, se pueden hacer consultas para obtener respuestas basadas en la información almacenada.

El proyecto se divide en dos partes principales:

1.  **RAG_EN (página web)**: En este caso, se genera un almacén de vectores a partir de una página web, incluye también una **GUI**.
    
2.  **RAG en castellano (PDF)**: Aquí, se crea una vector store utilizando un  archivo PDF.
    

Para ambos sistemas, se utilizan:

-   **Chroma** para almacenar los vectores de texto.
-   **LangChain** para gestionar todo el flujo de trabajo.
-   **HuggingFaceEmbeddings** para generar las representaciones vectoriales del texto.

El proyecto busca combinar estas herramientas para crear un sistema eficiente que aproveche tanto el almacenamiento de datos como la generación de respuestas inteligentes.

## LLM utilizados
-   **llama-3.2** para el RAG en inglés.
-    **mistral** para el RAG en español.

## Guía de Inicio
Clonado del repositorio:

    git clone git@github.com:AaronPrado/AvaliacionAaronBDA.git

Instalación de librerías:

    pip install requests beautifulsoup4 langchain langchain-ollama langchain_huggingface langchain_chroma gradio PyPDF2

Ejecuta por orden los siguientes cuadernos:

    

> rag_EN.ipynb
> 
> 
>  rag_ES.ipynb