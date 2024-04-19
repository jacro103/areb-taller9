# TALLER 9: Large Lenguage Models (LLMs)



## Comenzando

A continuación, te proporciono las instrucciones para obtener una copia del proyecto en funcionamiento en tu máquina local con el propósito de desarrollo y pruebas:

### 1 Requisitos

- [Python 3.x](https://www.python.org/downloads/) - Lenguaje de programación
- Tener cuenta en githun
- Tener cuenta en openai



### 2  Instalación

Realice los siguientes pasos para clonar el proyecto en su máquina local.

```bash
git clone https://github.com/jacro103/areb-taller9.git
```

Cree un entorno virtual python e instale las dependencias del proyecto.

#### Crear un entorno virtual

```bash
python -m venv .venv
```

#### Activar el entorno virtual

Windows
  
```bash
.venv\Scripts\activate 
```


#### Instalar dependencias

```bash
.venv\Scripts\python.exe -m pip install --upgrade pip
.venv\Scripts\python.exe -m pip install -r requirements.txt
```

## Descripción de la aplicación

Este laboratorio se centra en el uso de [Lang Chain](https://python.langchain.com/docs/get_started/introduction), [Pinecone](https://www.pinecone.io/) y [OpenAI](https://openai.com/) para desarrollar los siguientes desafíos:

### Enviar solicitudes a Chatgpt y recuperar respuestas

Se utiliza la biblioteca Lang Chain para interactuar con OpenAI y enviar las solicitudes a Chatgpt. Se configura un modelo de lenguaje de aprendizaje profundo (LLM) de OpenAI para generar respuestas a partir de las solicitudes enviadas.

```bash
python main.py
```


### Escribir un RAG simple utilizando una base de datos de vectores en memoria

Creación de un Recuperador de Respuestas Generativas (RAG) simple utilizando una base de datos de vectores en memoria para almacenar y recuperar información relevante para responder a preguntas.

```bash
python inmemorydb.py
```


### Crear un RAG simple utilizando Pinecone

Creación de un Recuperador de Respuestas Generativas (RAG) simple utilizando Pinecone para almacenar y recuperar información relevante para responder a preguntas.

```bash
python Pinecone.py
```


## Construido con 

- [Python](https://www.python.org/) - Lenguaje de programación.
- [Lang Chain](https://python.langchain.com/docs/get_started/introduction) - Biblioteca de Python para interactuar con OpenAI.
- [Pinecone](https://www.pinecone.io/) - Servicio de indexación y búsqueda de vectores.
- [OpenAI](https://openai.com/) - Plataforma de inteligencia artificial.



## Autor

- **Jose Alejandro Correa Rodriguez**

