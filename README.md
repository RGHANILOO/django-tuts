# django-tuts
a walkthrough od django tutorial from  https://docs.djangoproject.com/


- **mysite/** root directory its name doesnt matter
- **manage.py** CLI utility for django interaction 
- **mysite/** inner mysite directory is the actual pythonpackage for the project its name will be used for importing url **mysite.url**
- **mysite/__init__.py** an empty file that tell that tekll python this package should be condiered tha python package

- **mysite/settings.py** settings and configs for django proj 
- **mysite.urls.py** the url devlarations for the django proj a table of content for the project 
- **asgi.py** an aentry point for ASGI compatible web server to serve theproject
    asynch web server an pplication deployment
- **mysite/wsgi.py** and entry pouint for WSGI copatible server to serve 
    Web Server Gateway Interface 
    django primary deployment platform

cd mysite/ python manage.py runserver
Changing the port
By default, the runserver command starts the development server on the internal IP at port 8000.
If you want to change the server’s port, pass it as a command-line argument. For instance, this command starts the server on port 8080:
$ python manage.py runserver 8080