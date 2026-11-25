En el laboratorio vi el como usar github desde su instalacion, creacion de repocitorios, y usar la herramienta de Git bush junto con Visual Studio Code.

Aprendi a utiolizar los comandos:
$ git clone (paste) -> Clonar un repositorio pegando su URL
$ LS -> Para ver los ficheros
$ LS -all -> Muestra los ficheros ocultos

El paso a paso para sincronizar un repositorio Local al repositorio Remoto:

1. Working directory -> Staging area
$ git add (nombre del fichero)
$ git status -> ver los ficheros que están en el área de espera

2. Staging area -> localrepo
$ git commit -m "texto" -> Historia de los cambios del proyecto en mensaje o comentarios

3. locarepo -> remoterepo
$ git push

Remoterepo -> Localrepo: Para que se actualicen los cambios hechos en el remoto al local
$ git pull
