# Modulo0_Git_Practica
Práctica Módulo Git Bootcamp FullStack Web - Keepcoding


## Respuestas a cuestionario "Práctica Módulo Git".


-	**¿Qué comando utilizaste en el paso 11? ¿Por qué?**
	`git reset –hard <<identificador commit>>`. Este modo de deshacer un commit, deshace tanto el commit como los cambios asociados en él. Es decir deshace incluso el cambio que había en la zona de working copy. Dejándonos en un estado previo total.

-	**¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**
	En primer lugar `git reflog` para ver un histórico detallado de lo que ha ido pasando a través de nuestras acciones en git y posteriormente una vez localizado el punto desde el cual me gustaría restaurar lo deshecho ejecuto `git reset --hard <<identificador>>`

-	**El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**
    No, ya que no hay archivos que se hayan modificado en las mismas líneas de “código” en ambas ramas.

-	**El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**
    Si, al tener modificaciones en *git-nuestro.md* en ambas ramas se genera un conflicto. Git no sabe cómo ha de fusionar.

-	**El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**
    No, no hay modificaciones en archivos comunes.

-	**¿Qué comando o comandos utilizaste en el paso 25?**
	`git log --graph`

-	**El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**
	Sí, porque en este caso la rama master no ha añadido nuevos commits y junto con title mantendría un formato tipo lista, pudiendo desplazar el puntero HEAD al commit de title y de esta forma la rama master tendría todos los commits realizados, sin necesidad de tener un nodo (commit) que bifurcase hacia title y master. (caso que nos comprende ya que hemos hecho un `--no-ff`)

-	**¿Qué comando o comandos utilizaste en el paso 27?**
    `Git reset HEAD~1`

-	**¿Qué comando o comandos utilizaste en el paso 28?**
    `Git restore <<nombre archivo>>`
-	**¿Qué comando o comandos utilizaste en el paso 29?**
    `Git branch –D <<nombre rama>>`

-	**¿Qué comando o comandos utilizaste en el paso 30?**
    `git checkout <<id>>`
    `git checkout –b <<nombre rama>>`
    `git checkout <<master>>`
    `git merge title`

-	**¿Qué comando o comandos usaste en el paso 32?**
	`git checkout <<identificador commit>>`

-	**¿Qué comando o comandos usaste en el punto 33?**
    `Git checkout <<identificador>>`
