INSTRUCCIONES PARA TRANSPORTES YR BACKEND (Django)

1. Crear entorno virtual:
   python -m venv env
   source env/bin/activate  (Linux/Mac)
   env\Scripts\activate   (Windows)

2. Instalar Django:
   pip install django

3. Migrar la base de datos:
   python manage.py migrate

4. Crear superusuario:
   python manage.py createsuperuser

5. Ejecutar servidor:
   python manage.py runserver

Panel de administración:
http://127.0.0.1:8000/admin/
