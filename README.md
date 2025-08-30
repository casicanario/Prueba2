Pasos a Seguir
1. Inicializa el repositorio local
Abre la terminal o línea de comandos, navega hasta la carpeta de tu proyecto y ejecuta el siguiente comando:

Bash

git init
Este comando crea una nueva carpeta oculta llamada .git que rastreará los cambios de tu proyecto.

2. Agrega los archivos a la "zona de preparación" (staging area)
Este paso le dice a Git qué archivos quieres incluir en tu próximo commit (instantánea de tu proyecto).

Para agregar todos los archivos nuevos y modificados:

Bash

git add .

Para agregar un archivo específico:

Bash

git add nombre_del_archivo.txt

3. Crea el primer "commit"
Un commit es como una instantánea o punto de guardado de tu proyecto. El mensaje debe ser claro y conciso, describiendo los cambios que has hecho.

Bash

git commit -m "Descripción inicial del proyecto"

4. Crea un nuevo repositorio en GitHub
Ve a tu perfil de GitHub y crea un nuevo repositorio. No marques la opción de inicializarlo con un README.md o un archivo .gitignore.

5. Conecta tu repositorio local con GitHub
Copia la URL del repositorio que acabas de crear en GitHub y usa los siguientes comandos en tu terminal.

Para conectar tu repositorio local con el remoto:

Bash

git remote add origin https://github.com/tu-usuario/nombre-del-repositorio.git
Para verificar que la conexión se hizo correctamente:

Bash

git remote -v

6. Sube los archivos a GitHub
Finalmente, sube tu código del repositorio local al remoto con el siguiente comando:

Bash

git push -u origin master
Nota: En algunos casos, la rama principal se llama main en lugar de master. Si es tu caso, usa git push -u origin main.





Subir los cambios realizados al repositorio con el comando "git push".

C:\Codenotch\Prueba2>git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 345 bytes | 345.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/casicanario/Prueba2
   777fd29..e576c64  main -> main

Esto significa que tu push funcionó correctamente y tu repositorio local ahora está completamente sincronizado con GitHub.
