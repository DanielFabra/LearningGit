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


## 1️⃣ Flujo de trabajo básico de Git ⚙️
_A continuación se le presenta el flujo de trabajo basico de git por medio de una serie de comandos iniciales._

- `git init` Crea un nuevo repositorio de Git.
- `git status` Inspecciona el contenido del directorio de trabajo y el área de preparación.
- `git add` Agrega archivos del directorio de trabajo al área de preparación.
- `git diff` Muestra la diferencia entre el directorio de trabajo y el área de preparación.
- `git commit` Almacena permanentemente los cambios de archivos del área de preparación en el repositorio.
- `git log` Muestra una lista de todos los commits anteriores.


## 2️⃣ Formas de retroceder en Git ⚙️
_Puede utilizar estas habilidades para deshacer los cambios realizados en su proyecto Git._

- `git checkout HEAD filename` Descarta los cambios en el directorio de trabajo.
- `git reset HEAD filename` Anula los cambios de archivo en el área de preparación.
- `git reset commit_SHA` Se restablece a una confirmación anterior en su historial de confirmaciones.