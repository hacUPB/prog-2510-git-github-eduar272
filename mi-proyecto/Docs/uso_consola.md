# <span style="color: green;">Uso de consola</span>
 
El uso de la consola es la parte fundamental para la realzacion de la evaluacion, el buen manejo de la imagen ayudara para la buena relizacion del examen, todas la herramientas para acortar la escritura de los comandos es algo que debemos manejar al día a día.  
Tal vez la parte más fundamental de esta actividad es el afianzamniento que debemos crear con la consola y los diferentes comandos que tenmso que ejecutar  
Por ejemplo:

| Comando                                | Descripción                                                                 |
|----------------------------------------|-----------------------------------------------------------------------------|
| **Configuración**                      |                                                                             |
| `git config --global user.name "Nombre"` | Configura tu nombre de usuario.                                             |
| `git config --global user.email "email"`| Configura tu dirección de correo electrónico.                               |
| `git config --list`                    | Muestra la configuración actual de Git.                                     |
| **Inicialización y Clonación**         |                                                                             |
| `git init`                             | Inicializa un nuevo repositorio Git en el directorio actual.                |
| `git clone <url>`                      | Clona un repositorio existente desde una URL.                               |
| **Trabajo con Archivos**               |                                                                             |
| `git status`                           | Muestra el estado de los archivos en el directorio de trabajo.              |
| `git add <archivo>`                    | Añade un archivo al área de preparación (staging).                          |
| `git add .`                            | Añade todos los archivos modificados al área de preparación.               |
| `git commit -m "mensaje"`              | Guarda los cambios en el repositorio con un mensaje descriptivo.            |
| `git diff`                             | Muestra las diferencias entre el directorio de trabajo y el área de staging.|
| `git diff --cached`                    | Muestra las diferencias entre el área de staging y el último commit.        |
| **Ramas**                              |                                                                             |
| `git branch`                           | Lista todas las ramas en el repositorio.                                    |
| `git branch <nombre_rama>`             | Crea una nueva rama.                                                        |
| `git checkout <nombre_rama>`           | Cambia a la rama especificada.                                              |
| `git checkout -b <nombre_rama>`        | Crea una nueva rama y cambia a ella.                                        |
| `git merge <nombre_rama>`              | Fusiona la rama especificada con la rama actual.                            |
| `git branch -d <nombre_rama>`          | Elimina la rama especificada.                                               |
| **Historial y Cambios**                |                                                                             |
| `git log`                              | Muestra el historial de commits.                                            |
| `git log --oneline`                    | Muestra el historial de commits en una sola línea por commit.               |
| `git log --graph`                      | Muestra el historial de commits con un gráfico de ramas.                    |
| `git show <commit_hash>`               | Muestra los detalles de un commit específico.                               |
| `git revert <commit_hash>`             | Revierte un commit específico.                                              |
| **Sincronización con Remotos**         |                                                                             |
| `git remote add <nombre> <url>`        | Añade un repositorio remoto.                                                |
| `git remote -v`                        | Lista los repositorios remotos configurados.                                |
| `git fetch <nombre_remoto>`            | Descarga los cambios del repositorio remoto, pero no los fusiona.           |
| `git pull <nombre_remoto> <rama>`      | Descarga los cambios y los fusiona con la rama actual.                      |
| `git push <nombre_remoto> <rama>`      | Sube los cambios locales al repositorio remoto.                             |
| **Etiquetas**                          |                                                                             |
| `git tag`                              | Lista todas las etiquetas.                                                  |
| `git tag <nombre_etiqueta>`            | Crea una nueva etiqueta en el commit actual.                                |
| `git tag -a <nombre_etiqueta> -m "msg"`| Crea una etiqueta anotada con un mensaje.                                   |
| `git push <nombre_remoto> <etiqueta>`  | Sube una etiqueta al repositorio remoto.                                    |
| `git push <nombre_remoto> --tags`      | Sube todas las etiquetas al repositorio remoto.                             |
| **Limpieza y Mantenimiento**           |                                                                             |
| `git clean -n`                         | Muestra qué archivos serán eliminados (simulación).                         |
| `git clean -f`                         | Elimina archivos no rastreados del directorio de trabajo.                  |
| `git reset --hard`                     | Restaura el directorio de trabajo al último commit, descartando cambios.    |
| `git stash`                            | Guarda temporalmente los cambios no commitidos.                             |
| `git stash pop`                        | Aplica los cambios guardados en el stash y los elimina del stash.           |

Aunque se ven muchos, me es desarfotunado decir que todos los anterios son primordiales para el manejo y navegacion correcta por git, que vamos a ir viendo y afianzando a nuestro ritmo