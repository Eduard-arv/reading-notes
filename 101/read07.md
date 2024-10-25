# CONTROL DE VERSIONES

## ¿Qué es el control de versiones?
Es una herramienta que permite inspeccionar los archivos o proyectos en una computadora ademas de registrar los cambios que puedan hacerse en dicho archivo. A través de el, se puede trabajar en equipo, modificar y guardar todas las versiones anteriores sin depender necesariamente de un servidor central para guardar las versiones de un proyecto. Sumado a ello, si se comete un error se puede regresar a la versión anterior para hacer la corrección permitente, comparar los cambios con versiones anteriores, trabajar en equipo y crear versiones diferentes del mismo proyecto para entablar comparaciones en la ejecución del mismo.

---
## ¿Qué es “clone” en Git?

Permite crear una copia exacta de un repositorio, bien sea de un servidor local *(tu computadora)* o de un servidor remoto *(github.com)*.

---
## ¿Cuál es el comando para agregar los archivos modificados a la zona de preparación?
El comando a utilizar par agregar archivos modificados a tu repositorio debe ser ***git add***, ya que este toma los cambios que se han realizado en el archivos y los prepara para ser incluidos en el siguiente commit. Ejemplo: ***git add archivo.txt***

---
## ¿Cuál es el comando para enviar la captura de los archivos modificados a Github?

Primeramente se debe verificar que los archivos hayan sido modificados utilizando el comando ___git status___, luego se agregan los archivos modificados al área de prepracioón utlizando ___git add___. Acto seguido, se crea un  un ___commit___ con un mensaje descriptivo de los cambios, para esto se emplea el comando ___git commit -m "Descripción de los cambios realizados"___. Por último, se envian los cambios al repositorio remoto en Github aplicando ___git push origin nombre_rama___. Cabe destacar, que ___nombre_rama___ es el nombre de la rama a la que quieres enviar los cambios. El código correcto sería de la siguiente manera:


| **COMANDOS**                                         |                            | 
|------------------------------------------------------|----------------------------|
| ___Git Status___                                     | # Ver Archivos Modificados |      
| ___Git Add .___                                      | # Agregar Cambios          |      
| ___Git Commit -M "Actualización Del README"___       | # Crear Commit             |      
| ___Git Push Origin Main___                           | # Enviar A GitHub          |



