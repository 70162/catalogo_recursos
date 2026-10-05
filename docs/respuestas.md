1. ¿Cómo identificaste el comando necesario cuando la práctica no lo proporcionó? Primero pensé en lo que necesitaba hacer y busqué cuál comando servía para eso. También me basé en los comandos que ya habíamos usado anteriormente en la práctica.

2. ¿Qué diferencia existe entre preparar un archivo para un commit y crear el commit? En preparar un archivo es decirle a Git cuáles cambios quiero guardar. Crear el commit es guardar esos cambios con un mensaje para saber qué se hizo.

3. ¿Cómo puedes comprobar en qué rama estás trabajando? Se puede usar el comando git branch y en la rama en la que estoy aparece marcada con un *.

4. ¿Cómo puedes determinar qué archivos fueron modificados antes de registrarlos? Con el comando git status, porque ahí aparecen los archivos que fueron modificados, los nuevos y los que están preparados para guardarse.

5. ¿Cómo puedes observar exactamente qué cambió dentro de un archivo? Con el comando git diff, que muestra las partes que fueron agregadas, modificadas o eliminadas de los archivos.

6. ¿Por qué debe reconstruirse .venv después de obtener un repositorio? Porque es el entorno de Python que se usa en una computadora y normalmente no se comparte en el repositorio. Al obtener el proyecto en otra computadora hay que crear nuevamente ese entorno.

7. ¿Qué relación existe entre `requirements.txt` y `.gitignore`? requirements.txt guarda las librerías que necesita el proyecto para que otra persona pueda instalarlas. .gitignore indica qué archivos o carpetas no queremos subir al repositorio, como .venv.

8. ¿Por qué la colaboración se realiza desde una rama y no directamente desde `main`? Porque así los cambios se pueden hacer aparte sin afectar directamente la versión principal del proyecto. Después se pueden revisar antes de agregarlos a main.

9. ¿Por qué una solicitud de cambios no requiere crear un Pull Request nuevo? Porque los cambios se hacen en la misma rama que ya está relacionada con el Pull Request. Al subir nuevos cambios a esa rama, el Pull Request existente se actualiza automáticamente.

10. Después de realizar el merge en GitHub, ¿por qué todavía es necesario actualizar el repositorio local? Porque el merge se hizo en GitHub, pero la computadora todavía puede tener la versión anterior del proyecto. Por eso usamos git pull para traer los cambios nuevos y tener la misma versión que está en GitHub.
