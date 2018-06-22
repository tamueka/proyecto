# proyecto
Entrega practicas GIT Keepcoding

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?

git reset --hard HEAD~1. 

Para deshacer el ultimo commit utilizamos este comando y le ponemos hard 
para borrar el working copy.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

git reset --hard 0442507. Para dar un opaso hacia atras y recuperar el working copy con --hard.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No ningun conflicto. No estamos modificando nada en las dos ramas a la vez.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Si hubo un conflicto, ambas ramas modifican el mismo archivo, antes de merge primero 
arreglamos conflictos y luego hacemos merge.git status para ver archivos

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

No ningun conflicto esta todo correcto, hemos realizado un fast-fordward con exito.

- ¿Qué comando o comandos utilizaste en el paso 25?

git log --graph, podemos crear alias y seria asi: git config alias.graph "log --graph --decorate --pretty=oneline"


- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

Si podria, Lo único que hacemos es avanzar el puntero de la rama que absorbe, al commit en el que 
esta la rama absorbida.


- ¿Qué comando o comandos utilizaste en el paso 27?

git reset HEAD~1 + git status


- ¿Qué comando o comandos utilizaste en el paso 28?

git checkout git-nuestro.md + git status


- ¿Qué comando o comandos utilizaste en el paso 29?

git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?

git reflog + git reset --hard 3741f7e


- ¿Qué comando o comandos usaste en el paso 32?

git reflog + git checkout fe38db2


- ¿Qué comando o comandos usaste en el punto 33?

git reflog + git checkout 3741f7e











