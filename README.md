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

**Projects vs apps**

    What’s the difference between a project and an app? An app is a web application that does something – e.g., a blog system, a database of public records or a small poll app. A project is a collection of configuration and apps for a particular website. A project can contain multiple apps. An app can be in multiple projects.


**When to use include()**

    You should always use include() when you include other URL patterns. admin.site.urls is the only exception to this.