# Sistema de Gestión de Alquiler de Vehículos

Este proyecto implementa una plataforma web para gestionar un emprendimiento de alquiler de vehículos con múltiples sucursales, utilizando Django como framework principal.

## Funcionalidades principales

- Registro y autenticación de clientes
- Gestión de reservas y pagos en línea
- Administración de vehículos y su mantenimiento
- Gestión de empleados (solo para administradores)
- Panel de administración (Django Admin)
- Reportes de facturación y estadísticas
- Historial de reservas y control de multas
- Envío de notificaciones automáticas por email

## Tecnología utilizada

- Python 3.11.9
- Django 5.2
- SQLite / PostgreSQL (a definir)
- Bootstrap / Tailwind CSS (opcional para el frontend)

## Instalación

1. **Clonar el repositorio**

```bash
git clone https://github.com/VasquezMichael/mobirent.git
cd mobirent

2. **Crear y activar un entorno virtual**
python -m venv venv

# En Windows
venv\Scripts\activate

# En Linux/macOS
source venv/bin/activate

3. **Instalar dependencias**
pip install -r requirements.txt

4. **Aplicar migraciones iniciales**
python manage.py migrate

5. **Levantar el servidor de desarrollo**
python manage.py runserver

6. **Abrir el proyecto en el navegador**


📌 Notas importantes
No subir la carpeta venv/ al repositorio.

Se recomienda agregar un archivo .env para manejar configuraciones sensibles si es necesario.

Para salir del entorno virtual: deactivate


👥 Equipo de desarrollo
Vasquez Michael
Ferrer Tomas
Kairiyama Karen
Kairiyama Malena
```
