# 📌 Nombre del Proyecto

Descripción breve y directa de lo que hace el proyecto.

Proyecto basado en [Python](https://www.python.org/), [Django](https://www.djangoproject.com/) y [PostgreSQL](https://www.postgresql.org/). Incluye autenticación, manejo de datos y funcionalidades CRUD.

## 🖼️ Vista Previa

| Inicio                | Funcionalidad               |
| --------------------- | --------------------------- |
| ![main](img/main.png) | ![feature](img/feature.gif) |

## ⚙️ Requisitos

- Python 3.10+
- Django 4.2
- PostgreSQL 13+

## 🚀 Instalación

```bash
git clone https://github.com/usuario/proyecto.git
cd proyecto
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
cp .env.example .env
python manage.py migrate
python manage.py runserver
```

## 🧪 Tests

```bash
pytest        # Pruebas funcionales
flake8 .      # Estilo de código
black --check .  # Formato
```

## 🔐 Acceso de Ejemplo

**Admin:**
📧 admin@mail.com — 🔑 Abc123#

**Invitado:**
📧 user@mail.com — 🔑 Abc123#

## 🛣️ Roadmap

- [ ] Login con redes sociales
- [ ] API pública
- [ ] Dashboard mejorado

## 🖇️ Contribuye

```bash
# Fork → Crea rama → Cambios → Commit → Pull Request
```

Lee [CONTRIBUTING.md](.github/CONTRIBUTING.md) para más detalles.

## 📄 Licencia

MIT — ver [LICENSE](LICENSE.md)

⌨️ con ❤️ por [Brayan Diaz C](https://github.com/brayandiazc)
