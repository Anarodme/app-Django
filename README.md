# Proyecto de Autenticación de Usuarios

Este proyecto implementa la autenticación de usuarios con las siguientes funcionalidades:

- **Registrar un nuevo usuario**
- **Autenticar al usuario (login)**
- **Cerrar sesión del usuario (logout)**
- **Validar que la página de mantenimiento solo se presente si el usuario se autenticó en el sistema**

## Requisitos para ejecutar el proyecto

### Instalaciones necesarias

Asegúrese de tener instalados los siguientes paquetes mediante el uso de pip:

- pip install Django==2.1.15
- pip install django-mssql-backend
- pip install django-pyodbc-azure-2019

- Crear proyecto Django desde cmd.
django-admin startproject DjangoMVC (Este nombre puede ser el que usted desee
ponerle al proyecto).

- Crear un directorio para el proyecto desde la terminal del editor (Pycharm-
Visual Studio Code)

python manage.py startapp app (Este nombre puede ser el que usted desee
ponerle al directorio).

- Migrar las carpetas a SQL Server (django-mssql-backend)
python .\manage.py migrate

- Ejecución del programa
python .\manage.py runserver

- Extra: Crear un superusuario para ingresar a la ventana de administración(admin)
de Django
python manage.py createsuperuser
Opciones que debe completar:
Username (leave blank to use 'usuario'): anar
Email address:ana@gmail.com
Password: ___________
Password (again): ______________
The password is too similar to the email address.
Bypass password validation and create user anyway? [y/N]: y
Superuser created successfully.
