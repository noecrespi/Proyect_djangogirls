# Proyect_djangogirls
Proyecto djangogirls, se usa el lenguaje python y django. 

1. Abrir el proyecto en el editor de texto
2. Abrir la terminal
3. Crear un entorno para ese proyecto

4. Crear un virtualenv
```bash
$ python3 -m venv myvenv
```

5. Instalar Django
```bash
pip in /Users/noecrespi/Library/Python/3.8/lib/python/site-packages (22.3.1)
```

1. Crear el documento requirements.txt

    1. Añadir al documento requirements.txt
    ``` txt
    Django~=3.2.9
    ```
1. Crear el entorno virtual
```bash
python3 -m venv myvenv
```
1. Activar el entorno virtual
```bash
source myvenv/bin/activate
```

1. Instalar los requerimientos
```bash
pip install -r requirements.txt
```
1. Crear el archivo .gitignore

1. crear el proyecto de django
```bash
django-admin startproject mysite .
```
    La estructura del proyecto es la siguiente:
    ```
    djangogirls
    ├───manage.py
    ├───mysite
    │        settings.py
    │        urls.py
    │        wsgi.py
    │        __init__.py
    └───requirements.txt
    ```
    
