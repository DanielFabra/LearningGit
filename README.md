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

## Flujo de trabajo básico de Git ⚙️
_A continuación se le presenta el flujo de trabajo besico de git por medio de una serie de comandos iniciales._

- `git init` crea un nuevo repositorio de Git.
- `git status` inspecciona el contenido del directorio de trabajo y el área de preparación.
- `git add` agrega archivos del directorio de trabajo al área de preparación.
- `git diff` muestra la diferencia entre el directorio de trabajo y el área de preparación.
- `git commit` almacena permanentemente los cambios de archivos del área de preparación en el repositorio.
- `git log` muestra una lista de todas las confirmaciones anteriores.