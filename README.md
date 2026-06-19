[![Validacion de archivos y pulls](https://github.com/perex2007-cell/festival-devops-2026/actions/workflows/ci.yml/badge.svg)](https://github.com/perex2007-cell/festival-devops-2026/actions/workflows/ci.yml)

# 🎵 Festival DevOps Music Fest

## Descripción

Festival DevOps Music Fest es un proyecto académico desarrollado para practicar el uso de Git, GitHub, Docker y Docker Compose dentro del flujo de trabajo DevOps.

El proyecto cuenta con una interfaz web sencilla (Frontend) y una API desarrollada con Flask (Backend), administradas mediante contenedores Docker.

---

# Tecnologías Utilizadas

* HTML5
* CSS3
* Python 3
* Flask
* Docker
* Docker Compose
* Git
* GitHub

---

# Estructura del Proyecto

```
festival-devops/
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   ├── artistas.html
│   ├── tickets.html
│   └── contacto.html
│
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   └── Dockerfile
│
├── docker-compose.yml
└── README.md
```

---

# Funcionalidades

* Landing Page del festival.
* Página de artistas invitados.
* Página de compra de tickets.
* Página de contacto.
* API básica desarrollada en Flask.
* Contenedorización mediante Docker.

---

# Control de Versiones

Durante el desarrollo se implementó un flujo básico de Git utilizando ramas independientes para cada funcionalidad:

* feature-landing
* feature-backend
* feature-artistas
* feature-tickets
* feature-contacto

Cada rama fue integrada posteriormente a la rama principal mediante Merge.

---

# Docker

El backend se ejecuta dentro de un contenedor Docker utilizando un Dockerfile con Python y Flask.

Docker permite:

* Aislar la aplicación.
* Facilitar el despliegue.
* Mantener un entorno consistente.

---

# Docker Compose

Docker Compose permite administrar los servicios del proyecto desde un único archivo:

```
docker-compose.yml
```

Con este archivo es posible iniciar todos los contenedores mediante:

```
docker-compose up
```

---

# Git y GitHub

Se utilizaron las siguientes operaciones:

* git init
* git add
* git commit
* git checkout
* git branch
* git merge
* git remote add origin
* git push

El repositorio remoto fue publicado en GitHub para mantener un control de versiones colaborativo y seguro.

---

# Autor

Proyecto desarrollado como actividad de aprendizaje del programa DevOps y Contenedores (Docker).

SENA – Centro de Tecnología y Manufactura Avanzada (CTMA)

Año: 2026


