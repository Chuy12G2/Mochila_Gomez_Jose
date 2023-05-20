obtiene y configura las variables de git:
Git config

configurar nombre:
$ git config --global user.name "nombre de usuario"
configurar email:
$ git config --global user.email "email"

Comprobar la configuración del servidor remoto:
$ git remote -v

Crear un repositorio local:
$ git init

Hace una copia local de unn repositorio:
$ git clone

añadir un archivo a staging:
$ git add nombre_del_archivo

Graba el archivo de forma permanente en el historial de versiones con un mensaje:
$ git commit -m "mensaje"

Muestra el estado del directorio de trabajo y del área de preparación:
$ git status

Muestra los commits más recientes y el estado de la HEAD
$ git log

Cambiar entre ramas en un repositorio:
Cambiar a una rama en particular:
$ git checkout "branch"

Crear una nueva rama y cambiarse a ella:
$ git checkout -b "branch"

Fusionar las ramas
$ git merge
