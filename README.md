# Comandos Django

## Pasos para trabajar en Django

1. Instalar la librería Django

```bash
pip install django
```

2. Crear un proyecto en Django

django-admin startproject proyectouno

3. Crear el migrate inicial

python manage.py migrate

4. Crear una aplicación

python manage.py startapp [app_name]

5. Agregar las clases en el modelo

6. Agregar la aplicación en el settings, en la variable INSTALLED_APPS

7. Crear makemigrations para la aplicación

python manage.py makemigrations [app_name]

8. Hacer un migrate para pasar los clases del models a base de datos

python manage.py migrate


9. Crear un super usuario:

python manage.py createsuperuser

10. Agregar los modelos al admin.py de la aplicación

11. Levantar el proyecto

python manage.py runserver
