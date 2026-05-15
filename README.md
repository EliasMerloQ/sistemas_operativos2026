# sistemas_operativos2026
# 🖥️ Sistemas Operativos 2026
 
Proyecto web desarrollado con **Django** para la materia Sistemas Operativos — 2° año, ISFDYT N°210.
 
---
 
## 📋 Requisitos previos
 
- Python 3.11 o superior
- pip
- PostgreSQL (si usás base de datos local)
- Git
---
 
## 🚀 Instalación y configuración
 
### 1. Clonar el repositorio
 
```bash
git clone https://github.com/EliasMerloQ/sistemas_operativos2026.git
cd sistemas_operativos2026
```
 
### 2. Crear y activar el entorno virtual
 
```bash
python -m venv env
source env/bin/activate        # Linux / macOS
env\Scripts\activate           # Windows
```
 
### 3. Instalar dependencias
 
```bash
pip install -r requirements.txt
```
 
### 4. Correr el servidor de desarrollo
 
```bash
python manage.py runserver
```
 
Accedé desde el navegador en: [http://127.0.0.1:8000](http://127.0.0.1:8000)
 
---
 
## 📦 Dependencias principales
 
| Paquete | Versión | Descripción |
|---|---|---|
| Django | 5.1 | Framework web principal |
| Whitenoise | 6.6.0 | Servido de archivos estáticos |
| Pillow | 11.2.1 | Procesamiento de imágenes |
| openpyxl | 3.1.2 | Manejo de archivos Excel |
| psycopg2-binary | 2.9.10 | Conector para PostgreSQL |
 
---
 
## 🗂️ Estructura del proyecto
 
```
sistemas_operativos2026/
├── sistemas_operativos_2026/   # Carpeta principal del proyecto Django
│   ├── settings.py             # Configuración general
│   ├── urls.py                 # URLs raíz
│   ├── wsgi.py
│   └── asgi.py
├── requirements.txt            # Dependencias
├── .gitignore
└── README.md
```
 
---
 
## 👥 Integrantes
 
- Elias Merlo
---
 
## 📚 Materia
 
**Prácticas Profesionalizantes II** — ISFDYT N°210 · 2° año · 2026
 
