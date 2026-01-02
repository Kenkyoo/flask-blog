# Flask Blog

Una aplicación de blog simple construida con Flask y Bootstrap.

## 🚀 Demo

**Deploy:** [https://flask-blog-production.up.railway.app/](https://flask-blog-production.up.railway.app/)

## 📋 Características

- Registro y autenticación de usuarios
- Crear, editar y eliminar posts
- Ver posts de todos los usuarios
- Base de datos SQLite
- Interfaz con Bootstrap

## 🛠️ Tecnologías

- Python 3
- Flask 3.1.2
- SQLite3
- Bootstrap
- Gunicorn

## 📦 Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/Kenkyoo/flask-blog.git
cd flask-blog
```

2. Instala las dependencias:
```bash
pip install -r requirements.txt
```

3. Inicializa la base de datos:
```bash
flask --app flaskr init-db
```

4. Ejecuta la aplicación:
```bash
flask --app flaskr run
```

La aplicación estará disponible en `http://127.0.0.1:5000`

## 📁 Estructura
```
flaskr/
├── __init__.py      # Configuración de la app
├── auth.py          # Autenticación
├── blog.py          # Rutas del blog
├── db.py            # Base de datos
├── schema.sql       # Estructura de la BD
└── templates/       # Plantillas HTML
```

## 🔑 Funcionalidades

- **Registro/Login:** Autenticación de usuarios
- **Crear Post:** Usuarios pueden crear posts
- **Editar/Eliminar:** Solo el autor puede modificar sus posts
- **Ver Posts:** Todos pueden ver los posts publicados

## 📄 Licencia

MIT

## 👤 Autor

[Kenkyoo](https://github.com/Kenkyoo)
