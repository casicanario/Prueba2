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