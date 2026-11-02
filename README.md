# mi_primer_proyecto
Este repositorio se crea para empezar a explorar github\
Lenguaje martdown: para escribir en el md\
Editores de smartdown para escribir código md

    git config --global user.name "Firstname Lastname"
    git config --global user.email "your_email@example.com"

# Cómo subir cambios
<img width="946" height="684" alt="image" src="https://github.com/user-attachments/assets/47e12217-5d4a-4f93-bd85-daff1565d164" />

# Clonar un repositorio de GitHub

1. **Copia el enlace**\
   Ve a tu repositorio en GitHub, haz clic en el botón verde Code y copia la URL que aparece ahí.
2. **Abre tu terminal en la carpeta de destino (como Escritorio o Documentos)**\
   Ve al explorador de archivos de tu computadora, entra a la carpeta donde quieres guardar el proyecto y haz esto:\
   **En Windows:** Haz clic derecho en una zona vacía de la carpeta y elige "Abrir en la Terminal" (o "Git Bash Here").
3. **Clona el proyecto**\
   En la pantalla negra que se abrió, escribe **`git clone`**, dale un espacio, pega el enlace y presiona Enter:\
   **`git clone <pega_aquí_el_enlace>`**
4. Lo que sigue después de clonar es lo que en programación conocemos como el flujo de trabajo de Git (o Git Workflow)

# Conectar carpeta local con GitHub descargando el archivo ZIP

1. Abre la terminal dentro de tu carpeta descomprimida.
2. Inicializa Git: **`git init`**
3. Agrega la dirección de tu GitHub: **`git remote add origin <URL-de-tu-repositorio>`**
4. Trae el historial para que no choque: **`git pull origin main --allow-unrelated-histories`**
5. Sube tus cambios: **`git add ., git commit -m "Mis cambios", git push origin main`**

# Flujo de trabajo correcto en Git

1. **`git fetch`**: Consulta y trae la información sobre los últimos cambios o ramas que existen en GitHub sin alterarte el código local todavía.
2. **`git branch`**: Te muestra la lista de ramas locales.
3. **`git checkout -b <nombre-de-la-nueva-rama>`**: Crea una nueva rama y te pasa a ella automáticamente.
4. **`git switch <nombre-de-la-rama>`**: Te cambia a una rama existente (ejemplo: `git switch main`).
5. **`git pull <nombre-de-la-nube> <nombre-de-la-rama>`**: (Ej: `git pull origin main`). Descarga e integra los últimos cambios remotos.
6. **`git status`**: Revisa qué archivos se han modificado.
7. **`git add <nombre-del-archivo>`**: Prepara los archivos para guardar.\
   **`git add .`**: (con un punto al final). Ese punto le dice a Git: "prepara absolutamente todo lo que haya cambiado en esta carpeta".
9. **`git commit -m "mensaje"`**: Agrupa y guarda la confirmación con un mensaje.
10. **`git push <nombre-de-la-nube>(origin) <nombre-de-la-rama>`**: Sube tus cambios a GitHub.

(**Nota:** Si quieres saber qué nombre o "apodo" tiene tu repositorio en la nube, debes usar el comando **`git remote -v`** en tu terminal).\
(**Nota:** **`git merge <nombre-rama>`** fusiona y une los cambios de otra rama dentro de la rama en la que estás parado actualmente).\
(**Nota:** Si quieres crear una nueva rama desde la consola, también se usa **`git branch <nombre-de-la-nueva-rama>`**).
