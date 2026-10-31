# mi_primer_proyecto
Este repositorio se crea para empezar a explorar github\
Lenguaje martdown: para escribir en el md\
Editores de smartdown para escribir código md

    git config --global user.name "Firstname Lastname"
    git config --global user.email "your_email@example.com"

# Cómo subir cambios
<img width="946" height="684" alt="image" src="https://github.com/user-attachments/assets/47e12217-5d4a-4f93-bd85-daff1565d164" />

# Flujo de trabajo correcto en Git

1. **`git fetch`**: Consulta y trae la información sobre los últimos cambios o ramas que existen en GitHub sin alterarte el código local todavía.
2. **`git switch <nombre-de-la-rama>`**: Te cambia a la rama en la que vas a trabajar (por ejemplo: `git switch main`).
3. **`git pull <nombre-de-la-nube> <nombre-de-la-rama>`**: (Ej: `git pull origin main`). Descarga e integra los últimos cambios remotos a tu equipo para tener el proyecto al día antes de empezar a modificarlo.
4. **`git status`**: Te permite verificar en qué rama estás parado y revisar qué archivos se van modificando a medida que trabajas.
5. **`git add <nombre-del-archivo>`**: Selecciona y prepara los archivos modificados que deseas incluir para guardar.
6. **`git commit -m "mensaje"`**: Agrupa los archivos preparados y les guarda una "foto" (confirmación) con un mensaje claro descriptivo.
7. **`git push <nombre-de-la-nube> <nombre-de-la-rama>`**: (Ej: `git push origin main`). Sube tus commits locales al repositorio remoto en GitHub.
