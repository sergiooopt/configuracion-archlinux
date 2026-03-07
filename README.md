# Configuración de Arch Linux con MkDocs

Este repositorio contiene mi **documentación personal sobre la configuración de Arch Linux**, organizada como una web estática usando **MkDocs**.

La idea del proyecto es documentar paso a paso mi entorno de trabajo: herramientas, configuración del sistema, programas, y ajustes que utilizo en mi instalación de Arch Linux.

La documentación se genera como un sitio web local que permite navegar fácilmente por todas las guías.

---

## Requisitos

Para trabajar con la documentación necesitas tener instalado:

* Python
* pip
* entorno virtual (`venv`)

---

## Crear el entorno virtual

Primero crea un entorno virtual de Python:

```bash
python -m venv venv
```

Actívalo:

```bash
source venv/bin/activate
```

---

## Instalar dependencias

Instala MkDocs y el tema utilizado en el proyecto:

```bash
pip install mkdocs mkdocs-dracula-theme
```

---

## Ejecutar el servidor de desarrollo

Una vez instalado todo, puedes iniciar el servidor local de MkDocs:

```bash
mkdocs serve
```

MkDocs generará el sitio y lo servirá en:

```
http://localhost:8000
```

Desde ahí podrás visualizar y navegar por toda la documentación.

---

## Estructura del proyecto

```
.
├── docs/        # Documentación en formato Markdown
├── assets/      # Recursos adicionales (imágenes, etc.)
├── mkdocs.yml   # Configuración de MkDocs
└── venv/        # Entorno virtual de Python
```

---

## Objetivo del proyecto

Este proyecto sirve como:

* Documentación de mi configuración de Arch Linux
* Referencia rápida para reinstalar mi sistema
* Repositorio público de configuraciones y guías

---

## Licencia

Este proyecto se comparte como documentación abierta para referencia y aprendizaje.
x
