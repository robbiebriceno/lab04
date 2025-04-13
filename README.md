# 📚 Library Project

Este proyecto es una base para una aplicación Django, estructurada de forma moderna con una carpeta `src/`. Incluye configuración para manejo de imágenes con Pillow y está lista para ser versionada con Git y desplegada. 


⚙️ Pasos para correr el proyecto

Clonar el repositorio

    git clone https://github.com/Hector-Perez-Vengoa/lab_django_04.git
    cd lab_django_04

Crear y activar el entorno virtual

    python -m venv venv

Linux o Mac:

    source venv/bin/activate    

En Windows:

    venv\Scripts\activate

Instalar las dependencias

    pip install -r requirements.txt

Moverse al directorio del código fuente

    cd src

Aplicar migraciones

    python manage.py makemigrations
    python manage.py migrate

Crear datos de muestra

    python manage.py populate_db

Iniciar el servidor de desarrollo

    python manage.py createsuperuser

    python manage.py runserver
