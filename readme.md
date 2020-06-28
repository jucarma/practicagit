  GNU nano 4.9.3                                                                                       readme.md
#Preguntas Practica Git, GitHub y Sourcetree

**¿Qué comando utilizaste en el paso 11? ¿Por qué?**
*git reset --hard HEAD~1*
porque este comando deshace el ultimo commit y el working copy, de manera que todo quede como estaba previamente

**¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**
*Git reflog* para mostrar los commit por los que he pasado y poder ver sus id, para continuar
con *git reset 78339fe* para rehacer lo deshecho, y quedaria como si no hubiesemos borrado nada.

**El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**
*Git merge master*. No, porque las ramas comparten los mismos datos del poema. Y fue un fast-forward y estos no generan conflictos.

**El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**
 Si, porque hay diferencias en las lineas de codigo del archivo *git-nuestro.md* en las distintas ramas.

**El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**
No, porque fue un fast forward y estos no generan conflictos.

**¿Qué comando o comandos utilizaste en el paso 25?**
*git log --pretty=oneline --graph*

**El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**
Si, porque *title* es hijo de *master*

**¿Qué comando o comandos utilizaste en el paso 27?**
*git reflog* para ver la id de los commit anteriores
y *git reset 78339fe*

**¿Qué comando o comandos utilizaste en el paso 28?
git reflog para ver el id del commit
git reset –hard aa57986

**¿Qué comando o comandos utilizaste en el paso 29?**
*git branch -d title*

**¿Qué comando o comandos utilizaste en el paso 30?**
*git reflog*
*git reset –hard 78339fe*

**¿Qué comando o comandos usaste en el paso 32?**
*git reflog*
*git checkout eace74c*

**¿Qué comando o comandos usaste en el punto 33?**
*git reflog*
*git checkout abdb860*
