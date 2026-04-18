# Aplicación de Lista de Tareas

Una aplicación simple de gestión de tareas basada en Django para crear, ver y administrar tus tareas diarias.

## Características

- **Lista de Tareas**: Visualiza todas tus tareas en una lista limpia y organizada.
- **Agregar Tareas**: Agrega fácilmente nuevas tareas con descripciones.
- **Marcar como Completadas**: Actualiza el estado de las tareas para rastrear el progreso.
- **Interfaz Amigable**: Construida con vistas basadas en clases de Django para simplicidad.

## Requisitos

- Python 3.8+
- Django 6.0+

## Instalación

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/tuusuario/task_list.git
   cd task_list
   ```

2. **Crea un entorno virtual**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # En Windows: venv\Scripts\activate
   ```

3. **Instala las dependencias**:
   ```bash
   pip install django
   ```

4. **Ejecuta las migraciones**:
   ```bash
   python manage.py migrate
   ```

5. **Inicia el servidor de desarrollo**:
   ```bash
   python manage.py runserver
   ```

6. **Accede a la aplicación**:
   Abre tu navegador y ve a `http://127.0.0.1:8000/`.

## Uso

- Navega a la página principal para ver tu lista de tareas.
- Agrega nuevas tareas a través del formulario proporcionado.
- Edita o elimina tareas según sea necesario.

## Estructura del Proyecto

- `base_project/`: Configuraciones principales del proyecto Django.
- `tasks/`: Aplicación que contiene modelos, vistas y URLs para la gestión de tareas.
- `templates/`: Plantillas HTML para la interfaz de usuario.
- `static/`: Archivos estáticos (CSS, JS, imágenes).

## Contribuyendo

1. Haz un fork del repositorio.
2. Crea una rama de características.
3. Realiza tus cambios y prueba.
4. Envía una solicitud de pull.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT.