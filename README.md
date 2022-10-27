# Comandos Django

## Pasos para trabajar en Django

1. Instalar la librería Django

```bash
pip install django
```

2. Crear un proyecto en Django

```bash
django-admin startproject [nombre-proyecto]
```

3. Crear el migrate inicial

```bash
python manage.py migrate
```

4. Crear una aplicación

```bash
python manage.py startapp [app_name]
```

5. Agregar las clases en el modelo

6. Agregar la aplicación en el settings, en la variable INSTALLED_APPS

7. Crear makemigrations para la aplicación

```bash
python manage.py makemigrations [app_name]
```

8. Hacer un migrate para pasar los clases del models a base de datos

```bash
python manage.py migrate
```

9. Crear un super usuario:

```bash
python manage.py createsuperuser
```

10. Agregar los modelos al admin.py de la aplicación

11. Levantar el proyecto

```bash
python manage.py runserver
```
