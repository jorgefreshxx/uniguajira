# UniBus

Proyecto Django para el entregable del segundo corte.

Descripción:
Aplicación para localizar rutas y buses universitarios en tiempo real. Incluye modelos para usuarios, rutas, paradas, buses y registro de ubicaciones.

Instrucciones rápidas:
1. Crear entorno virtual:
   python -m venv venv
   # activar:
   # Windows: venv\Scripts\activate
   # Mac/Linux: source venv/bin/activate

2. Instalar dependencias:
   pip install -r requirements.txt

3. Migrar:
   python manage.py makemigrations
   python manage.py migrate

4. Crear superusuario:
   python manage.py createsuperuser

5. Ejecutar:
   python manage.py runserver

Nota: Cambia SECRET_KEY en unibus/settings.py antes de subir a producción.
