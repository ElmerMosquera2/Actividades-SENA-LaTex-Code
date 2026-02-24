# SENA - Actividades en LaTeX

Repositorio dedicado a la gestión y control de versiones de mis actividades académicas del SENA. El flujo de trabajo combina la edición en la nube con un respaldo y gestión local.

## 💻 Stack Técnico
*   **Editor:** [Zed](https://zed.dev) (Local) / [Overleaf](https://www.overleaf.com) (Nube).
* - **Entorno:** [Node.js](https://nodejs.org) para automatización de tareas.
*   **Motor LaTeX:** MiKTeX (Windows) / TeX Live (Linux).
*   **Control de Versiones:** Git (Sincronización multiplataforma).

## 📂 Estructura del Repositorio
*   `actividad-x/`: Código fuente `.tex` y recursos (imágenes/tablas).
*   `.gitignore`: Filtro de archivos auxiliares de compilación (`.aux`, `.log`, `.out`).
*   `LICENSE`: Licencia de uso del código.

## ⚙️ Automatización (Node.js)
El proyecto incluye scripts en package.json para agilizar procesos recurrentes

(En desarrollo)

## ⚙️ Mi Configuración Local
Para mantener la consistencia entre Windows y Linux, se utiliza la siguiente configuración de Git:
```bash
# Manejo de finales de línea
git config --global core.autocrlf input # En Linux
git config --global core.autocrlf true  # En Windows

# Editor por defecto
git config --global core.editor "zed --wait"
