# 🌸 Django Girls Blog

Un proyecto desarrollado como parte del **tutorial oficial de Django Girls**, con el objetivo de aprender los fundamentos del framework **Django** para crear aplicaciones web dinámicas y seguras.  
Este blog permite a los usuarios **crear, editar y publicar posts**, integrando autenticación de usuarios y una interfaz moderna con **Bootstrap**.

---

## 🌍 Enlace del sitio web

🕸️ **[https://miniicow.pythonanywhere.com/](https://miniicow.pythonanywhere.com/)**  
> *El sitio estará activo durante 3 meses a partir del despliegue.*

---

## 📘 Guía base utilizada

Este proyecto fue construido siguiendo la guía oficial de Django Girls:  
🔗 [https://tutorial.djangogirls.org/es/](https://tutorial.djangogirls.org/es/)

---

## ✨ Características principales

- 📝 Crear, editar y publicar publicaciones.
- 💻 Interfaz visual basada en **Bootstrap** con estilos personalizados.
- 🔐 Sistema de autenticación: solo usuarios autenticados pueden crear o editar posts.
- 🧩 Estructura basada en plantillas HTML:
  - `base.html`
  - `post_list.html`
  - `post_detail.html`
- 📅 Visualización de fecha de publicación y contenido en formato legible.

---

## 🗂️ Estructura de carpetas

Ejemplo simplificado del árbol de archivos del proyecto:

DjangoGirlsBlog/
├── blog/
│   ├── migrations/
│   ├── templates/
│   │   └── blog/
│   │       ├── base.html
│   │       ├── post_detail.html
│   │       └── post_list.html
│   ├── admin.py
│   ├── models.py
│   ├── urls.py
│   ├── views.py
│   └── forms.py
├── mysite/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── manage.py
└── requirements.txt


---

## ⚙️ Requisitos del proyecto

- 🐍 **Python 3.x**
- 🌐 **Django**
- 🧱 **Virtualenv**
- 🎨 **Bootstrap**

---


## 🚀 Instrucciones de instalación


# 1️⃣ Clonar el repositorio
```bash
git clone https://github.com/tu-usuario/django-girls-blog.git
cd django-girls-blog
```

# 2️⃣ Crear entorno virtual
```bash
python -m venv venv
```

# 3️⃣ Activar entorno virtual
```bash
# En Windows
venv\Scripts\activate
# En macOS/Linux
source venv/bin/activate
```

# 4️⃣ Instalar dependencias
```bash
pip install -r requirements.txt
```

# 5️⃣ Ejecutar el servidor
```bash
python manage.py runserver
```

# Luego, abre tu navegador en:
```bash
# http://127.0.0.1:8000/
```

👩🏻‍💻 Autor
Manuela Mayorga 💫

💖 Este proyecto fue creado con amor y aprendizaje gracias a la comunidad de Django Girls.
