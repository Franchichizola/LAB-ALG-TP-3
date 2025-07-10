Preentrega Django
Trabajo Práctico N°3 – Laboratorio de Algoritmos y Estructuras de Datos

Descripción:
Este repositorio contiene las ocho partes del tutorial de Django.

Contenido del repositorio:
- /docs/: contiene las respuestas al cuestionario sobre Django.
- /tutorial/: desarrollo del tutorial de Django hasta la parte 8 incluida.

Requisitos:
- Python 3.10 o superior
- Django 5.2
- (Opcional) Entorno virtual

Pasos para instalar y ejecutar el proyecto:
1. Clonar el repositorio:
   git clone https://github.com/tu-usuario/nombre-del-repositorio.git
   cd nombre-del-repositorio

2. Crear y activar un entorno virtual (opcional pero recomendado):
   En Windows:
       python -m venv env
       .\env\Scripts\activate
   En Linux/Mac:
       python3 -m venv env
       source env/bin/activate

3. Instalar Django:
   pip install django

4. Realizar migraciones:
   python manage.py migrate

5. Ejecutar el servidor:
   python manage.py runserver

6. Acceder al sitio desde el navegador:
   http://127.0.0.1:8000/
