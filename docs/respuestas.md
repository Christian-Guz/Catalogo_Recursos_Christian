¿Qué ventaja tiene registrar las dependencias del proyecto en
requirements.txt en lugar de compartir la carpeta .venv?

La ventaja de registrar las dependencias en requirements.txt es que permite mantener el control de las versiones de las dependencias y facilita la instalación de las mismas en diferentes entornos.

¿Por qué el repositorio que tienes ahora en tu computadora no es el
mismo concepto que el fork creado en GitHub?

Porque el repositorio que tengo en mi computadora únicamente es local y mantiene cambios directos de mi equipo, mientras que el repositorio creado en GitHub es el que se sincroniza con GitHub y se puede utilizar en cualquier equipo.

1. ¿Cómo identificaste el comando necesario cuando la práctica no lo proporcionó?

Conociendo que herramientas necesito, la forma de identificar el comando permite realizar la tarea, además
de conocer bien los comandos

2. ¿Qué diferencia existe entre preparar un archivo para un commit y crear el commit?

Preparar un archivo para un commit únicamente se agrega como un bloque preparado para guardarse, esto quiere decir
que se pueden generar cambios aún en caso de que se requiera, mientras que crear el commit es guardar en el repositorio los cambios realizados.

3. ¿Cómo puedes comprobar en qué rama estás trabajando?

Con el comando git branch, se puede ver cual es la rama en la cual estamos trabajando al tener un asterisco

4. ¿Cómo puedes determinar qué archivos fueron modificados antes de registrarlos?

Puedes utilizar el comando git status para conocer los estados de los archivos o con el color de los archivos en el explorador

5. ¿Cómo puedes observar exactamente qué cambió dentro de un archivo?

Puedes utilizar el comando git diff para comparar los cambios que se realizaron en el archivo

6. ¿Por qué debe reconstruirse .venv después de obtener un repositorio?

Porque se necesita reconstruir el entorno virtual para poder utilizar las dependencias que se encuentran en el archivo requirements.txt

7. ¿Qué relación existe entre requirements.txt y .gitignore?

El archivo requirements.txt contiene las dependencias del proyecto y el archivo .gitignore contiene los archivos que se deben ignorar en el repositorio

8. ¿Por qué la colaboración se realiza desde una rama y no directamente desde main?

Para evitar conflictos directamente en el código principal e evitar problemas críticos, lo que permite cometer errores en el código local y una vez listo se actualiza la rama principal

9. ¿Por qué una solicitud de cambios no requiere crear un Pull Request nuevo?

Porque se puede hacer directamente desde la rama en la que se encuentra trabajando, sin tener que crear una solicitud de cambios

10. Después de realizar el merge en GitHub, ¿por qué todavía es necesario actualizar el repositorio local?

Porque se necesita actualizar el repositorio local para obtener los cambios realizados en la rama principal