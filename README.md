CRUD API con FastAPI 🚀
===========

#### Este repositorio es un proyecto de práctica que implementa un CRUD (Create, Read, Update, Delete) utilizando FastAPI, un framework moderno y de alto rendimiento para construir APIs con Python.

## 📌 Características

Endpoints RESTful para operaciones CRUD.

Uso de Pydantic para validación de datos.

Conexión a base de datos con SQLite.

Manejo de respuestas y excepciones.

Documentación automática con Swagger UI y Redoc.

## 📂 Tecnologías

Python

FastAPI

SQLite

Pydantic

Uvicorn

### 🚀 Instalación y ejecución

### Clona el repositorio:
```bash
git clone https://github.com//victorgp01/CRUD_FastAPI.git 
```
```bash
cd curso-fastapi-project
```

### Crea y activa un entorno virtual:
```
python 3.11 -m venv env
```
```
source env/bin/activate
```

### Instala las dependencias:
```
pip install -r requirements.txt
```

### Ejecuta el servidor:
```
uvicorn main:app --reload
```

### Accede a la documentación en:

Swagger UI: http://localhost:8000/docs

Redoc: http://localhost:8000/redoc

📌 Notas

Este proyecto es solo con fines de aprendizaje y práctica. Se pueden agregar mejoras como autenticación, middleware o integración con frontend.

