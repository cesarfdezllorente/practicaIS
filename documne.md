# GIT
## Configuración básica
Nombre del administrador:

`git config --global user.name "Antonio M.Durán Rosal"`

Correo electronico:

`git config --global user.email udaran@uco.es`

Editor de texto:

`git config --global core.editor "gedit"`

Color de interfaz:

`git config --global color.ui true`

Listado de la configuración:

`git config --list`

![Los tres estados de Git](http://1.bp.blogspot.com/-0ESPAhDYGQ4/ThMfRvj9FGI/AAAAAAAAAMM/Gifzuv9wwEA/s1600/git%2Blocal%2Boperations.jpg)

## Comandos basicos I

Iniciar repositorio en un directorio:

`git init`

Agregar cambios del area de *standing*:

`git add`

Validar cambios en el repositorio:

`git commit -m "Mensaje"`

Hacer los dos pasos anteriores en uno:

`git commit -am "Mensaje"`

Historial de commits:

`git log`

## Comandos Basicos II

Ayuda del listado anterior:

`git help log`

Listar los 5 commits mas recientes:

`git log -n 5`

Listar los commits desde una fecha:

`git log --since=2018-09-18`

Listar los commits por autor:

`git log --author="Antonio"`

Ver los cambios en el directorio:

`git status`

## Comandos Básicos III

Ver diferencia  entre ficheros en el directorio y el repositorio de git:

`git diff`

Ver diferencia entre ficheros en el *staging* y el repositorio:

`git diff --stagged`

Eliminar archivos:

`git rm archivo`

`git commit -m "Mensaje"`

## Comandos Básicos IV

Deshacer cambios con git:

`git checkout -- nombre_fichero`

Retirar archivos del *staging*:

`git reset HEAD nombre_fichero`

Completar último commit:

`git commit --amend -m "Mensaje"`

Recuperar versión de un fichero de commit antiguo:

`git ckeckout <id_commit> -- nombre_archivo`

Revertir un commit:

`git revert <id_commit>`
