# LearningGit 🚀

_Apuntes de comandos git y su uso_

Resumen de [CodeCademy](https://www.codecademy.com/learn/learn-git)

## Generalidades 🚀

_Git es el sistema de control de versiones estándar de la industria para desarrolladores web. Use los comandos de Git para ayudar a realizar un seguimiento de los cambios realizados en un proyecto._

### Instalación (Ubuntu 20.04) 🔧

Administrador de paquetes APT:

_El paquete Git se incluye en los repositorios predeterminados de Ubuntu. Por este motivo, los usuarios vamos a poder instalarlo de forma muy sencilla desde el administrador de paquetes apt._

Ejecutar los siguientes comandos en la terminal para instalar Git:

```
sudo apt update && sudo apt install git
```

Verifique la versión de Git instalada:
```
git --version
```

Si Git está instalado, obtendrá un resultado similar al siguiente:
```
git version 2.25.1
```

* Para mas inforamcion visitar el siguiente enlace: https://www.digitalocean.com/community/tutorials/how-to-install-git-on-ubuntu-20-04-es

_ _ _


![Git Workflow](imgs/git-workflow.png?raw=true "Git Workflow")


## ❶ Flujo de trabajo básico de Git ⚙️
_A continuación se le presenta el flujo de trabajo basico de git por medio de una serie de comandos iniciales._

- `git init` Crea un nuevo repositorio de Git.
- `git status` Inspecciona el contenido del directorio de trabajo y el área de preparación.
- `git add <filename>` Agrega archivos del directorio de trabajo al área de preparación.
- `git diff <filename>` Muestra la diferencia entre el directorio de trabajo y el área de preparación.
- `git commit -m "<annotation>"` Almacena permanentemente los cambios de archivos del área de preparación en el repositorio.
- `git log` Muestra una lista de todos los commits anteriores.

_ _ _


![Git Reset](imgs/git-reset.png?raw=true "Git Reset")


## ❷ Formas de retroceder en Git ⚙️
_Puede utilizar estos comandos para deshacer los cambios realizados en su proyecto Git._

> En muchos casos, el `commit` más reciente se conoce como `HEAD`.

> SHA son los caracteres que identifican un commit del historial, con _git reset_ funciona utilizando los primeros 7 caracteres.

- `git show HEAD` Muestra el ultimo registro de _git log_ (ultimo _commit_), además de todos los cambios realizados en el _HEAD_.
- `git checkout HEAD <filename>` Restaurará el _filename_ en su _directorio de trabajo_ para que se vea exactamente como lo hizo la última vez que realizó un _commit_.
- `git reset HEAD <filename>` Restablece el _filename_ en el _área de preparación_ para que sea el mismo del _HEAD_. No descarta los cambios de _filename_ del _directorio de trabajo_, simplemente los elimina del _área de preparación_.
- `git reset commit_SHA` Los archivos del _directorio de trabajo_ se restablecen a un _commit_ anterior del historial.

_ _ _


![Git Branching](imgs/git-branching.png?raw=true "Git Branching") ![Git Branching](imgs/git-branching2.png?raw=true "Git Branching")


## ❸ Ramificaciones en Git ⚙️
_Aprenda a administrar varias versiones de un proyecto con ramificación_

- `git branch` Muestra en que _Rama_ del proyecto esta ubicado.
- `git branch <new_branch>` Es usado para crear una nueva rama.
- `git checkout <branch_name>` Es usado para cambiar a la rama _<branch_name>_.
- `git merge <branch_name>` Es usado para fusionar _<branch_name>_ en la rama que se encuentra.
- `git branch -d <branch_name>` Eliminará la rama especificada de su proyecto Git.

_ _ _


## ❹ Trabajo en equipo con Git ⚙️

_ _ _