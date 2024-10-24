# READ 06

## ¿Qúe hacen los siguientes comandos?
- **pwd:** muestra la rutra completa del directorio en el cual te encuentres trabajando, permitiendo conocer la ubicación exacta en el sistema.
- **ls:** este expresa la línea de contenido y archivos de tu directorio. Es decir, al ejecutar este comando, se obtiene una lista de todos los archivos y subdirectorios que se encuentran dentro de la carpeta donde estes trabajando.  
- **cd:** la función principal de este comando es moverte entre los diferentes directorios de tu sistema de archivos, permitiendo explorar la estructura de directorios de tu sistema y moverte entre cada archivo de forma organizada.
- **mkdir:** permite crear nuevos directorios dentro de un sistema de archivos, facilitando construir nuevos espacios de trabajo, crear estructura y archivos dentro del sistema. 
- **touch:** su función es crear archivos vacíos o actualizar la fecha y hora de acceso y modificación de un archivo o directorio existente.

## ¿Puedes explicar qué sucede en el siguiente escenario si ingresas estos comandos y argumentos en la línea de comandos? (Los argumentos son instrucciones adicionales dadas a un comando).
- **cd projects:** crea una carpeta nueva llamada projects
- **mkdir new-project:** dentro de la carpeta projects, crea una nueva carpeta llamada new-project
- **touch new-project/newfile.md:** dentro de la carpeta que acabamos de crear llamada new-project, crea crea un archivo vacío llamado comunmente "newproject.md" (tiende a crearse en formato markdowm al ser un archivo de texto)
- **cd ..:** te mueve un nivel hacia arriba en la jerarquía de directorios. Es decir, sales de la carpeta "projects" y vuelves a la carpeta que la contenía.
- **ls projects/new-project:** este comando te mostrará el contenido de la carpeta "new-project". en este caso solo se observará la carpeta "newfile.md".

## ¿Qué comando usarías en la terminal para listar todos los archivos, incluidos los archivos ocultos, en un directorio de Linux o macOS? Explica qué significan los parámetros utilizados en el comando.

En este caso, utilizaría el comando ls-a, este mostrará todos los elemento dentro del directorio (incluyendo los archivos ocultos)
  
