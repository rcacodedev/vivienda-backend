# 🏠 Vivienda Backend · Predicción de precios de vivienda

Este repositorio contiene el **backend** de la aplicación **Vivienda**, un proyecto de predicción de precios de inmuebles usando **Machine Learning supervisado** (regresión lineal múltiple, regularización, etc.).

La idea principal es ofrecer un **SaaS** que permita, por ejemplo, a usuarios particulares, agencias inmobiliarias o tasadores, **predecir el precio de un piso o casa en España** a partir de características como metros cuadrados, barrio, antigüedad, etc.

---

## 🔧 Tecnologías principales

- [Django](https://www.djangoproject.com/) + [Django REST Framework](https://www.django-rest-framework.org/)
- [PostgreSQL](https://www.postgresql.org/) (base de datos principal, con conexión mediante `DATABASE_URL`)
- [SimpleJWT](https://django-rest-framework-simplejwt.readthedocs.io/) (autenticación con tokens)
- [CORS Headers](https://pypi.org/project/django-cors-headers/) (integración frontend-backend)

---

## 🚧 Estado actual

Este repositorio está en **fase inicial**:

- Configuración de entorno Django + DRF
- Conexión a base de datos PostgreSQL
- Endpoint de prueba `/api/health/`

Más adelante añadiremos:

- Autenticación y gestión de usuarios
- Subida y almacenamiento de datasets (ej. CSVs del INE/Idealista)
- Entrenamiento de modelos de regresión
- Endpoints de predicción de precios
- Gestión multi-tenant para SaaS

---

## 📌 Nota

Este README se irá ampliando con **instrucciones de instalación, despliegue y uso** a medida que el proyecto avance.
