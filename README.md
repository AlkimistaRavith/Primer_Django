# Primer_Django
Clases Django Mod 6

PASOS:
    ##crear entorno
python -m venv entorno
    ##activar entorno
source entorno/bin/activate
    ##Instala Djgango
pip install django 
    ##Levanta proyecto
django-admin startproject proyecto .  
    ##correr servidor
python manage.py runserver 
    ##Migraciones
python manage.py makemigrations
python manage.py migrate
    ##Crear app
python manage.py startapp 