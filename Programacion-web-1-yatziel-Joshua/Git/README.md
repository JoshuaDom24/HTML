# Git

Es el sistema de control de versiones distribuido más usado en el mundo del desarrollo

## Comandos Principales

1. Git init -> Inicializa un repoitorio. (Un repositorio es un folder que se ha estblecido con control de versiones)

Al inicializar un repositorio se crea na carpeta oculta llamada .git

Este folder contiene la información y metadatos que permite el control de versiones.

No hy que borrarlo o todo se va al carajo 🙀

Al inicializar el repositorio se establece la rama principal con el nombre "main" o "master"

2. git branch -m -> Cambiar el nombre de la rama principal de "master" a "main"

3. git config --local user.name "Joshua" -> Guarda en l configuración local del repositorio local, el nombre del repositorio que hará los cambios.

4. git config --local user.email "JoshuaDom24@puchunguito.com -> Guarda en la confiuración el email 

5. git config --global init.defaultBranch main -> Configura de nabera global que la rama principal se llame "main"

6. Git status -> Revis los cambios que se han hecho en un repositorio.

7. Git add nombre-archivo.ext ->Agrega archivos al "staging area" para ser rastreados

8. Git commit -m "Mensaje" -> Conforma, guarda los cambios en un commit y le agrega un mensaje. El mensaje debe ser concreto y descriptivo de los cambios

NOTA: Los comandos más usados en nuestras sesiones serán "Git add" y "Git commin -m"