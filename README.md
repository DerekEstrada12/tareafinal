Proyecto Django – Aplicación Web Final
Descripción del Proyecto

Este proyecto es una aplicación web desarrollada con Django, como parte de la tarea final del curso.
Incluye la estructura completa de un proyecto Django con:

Configuración del entorno virtual

Creación del proyecto y la aplicación

Modelos, vistas y templates

Rutas y estructura MVC

Servidor local en modo desarrollo

El objetivo es demostrar el ciclo completo de construcción de una aplicación web funcional usando Django.

📥 Instalación y Ejecución

Sigue estos pasos para correr el proyecto en tu computadora:

1. Clonar el repositorio
git clone https://github.com/tu_usuario/tu_repositorio.git


Entra en la carpeta:

cd tu_repositorio

2. Crear y activar el entorno virtual

Windows

python -m venv venv
venv\Scripts\activate


Linux / Mac

python3 -m venv venv
source venv/bin/activate

3. Instalar dependencias

(Asegúrate de que el entorno virtual esté activo)

pip install -r requirements.txt

4. Aplicar migraciones
python manage.py migrate

 5. Ejecutar el servidor local
python manage.py runserver


La aplicación quedará disponible en:

http://127.0.0.1:8000/

Estructura del Proyecto (ejemplo)
mi_proyecto/
│── manage.py
│── requirements.txt
│── README.md
│
├── mi_app/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   └── admin.py
│
└── mi_proyecto/
    ├── settings.py
    ├── urls.py
    └── wsgi.py
