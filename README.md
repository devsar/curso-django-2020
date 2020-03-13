# Curso Django 2020

Si aún no hemos creado un virtualenv hacemos,

```bash
~/curso-django-2020 $ python3 -m venv venv-curso-django
```

Activamos el virtualenv,

```bash
~/curso-django-2020 $ source venv-curso-django/bin/activate
```

Instalamos Django,

```bash
(venv-curso-django) ~/curso-django-2020 $ pip install django
```

Con Django ya instalado, podemos crear el esqueleto del proyecto.

```bash
(venv-curso-django) ~/curso-django-2020 $ django-admin startproject app .
```

- `app` es el nombre del proyecto
- `.` (punto) es el directorio donde crearlo, en este caso el directorio donde estamos parados.
