# Django-Platzy


#Inicializadores de proyecto
#django-admin startproject Django-Platzy .

python manage.py startapp products

#django-admin startproject Django-Platzy .

python manage.py startapp task - Creacion de una nueva aplicacion
python manage.py migrate - Migra los datos al servidor de sql lite
python manege.py makemigrations - cuando se crea una nueva tabla y se debe correr de nuevo el migrate
python manage.py createsuperuser - Para crear super usuario de SQLlite
python manage.py runserver - ejecuta el servidor

---Entorno virtual 

pip install virtualenv

** En la carpeta ejecutar el comando

python -m venv venv - Para crear el entorno 

.\venv\Scripts\activate - Activa el entorno 
deactivate - Apaga el entorno virtual

pip install -r .\requerements.txt - Instala las dependencias en el entorno virutal 
