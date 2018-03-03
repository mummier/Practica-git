# Practica-git
- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1
Porque éste es el que te borra los cambios en el working copy.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reflog 
git reset _identificador_
y los pasos para hacer un commit
Así nos aseguramos de que hemos rescatado el commit que queríamos.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No ha sido un conflicto como tal. Simplemente ha salido la notificación "Already up-to-date" que nos indica que las ramas ya estaban juntas, pues styled contenía lo de master desde el principio.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
No porque la consola me los hizo en un no fast forward sin decirle nada, pero podría habérmelo causado ya que los archivos de cada rama se solaparían en un ff y el archivo de don-quijote tendría contenido de ambas a la vez.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No. Ninguno sufrió cambios que dañasen los archivos a la vez.

- ¿Qué comando o comandos utilizaste en el paso 25?
git log --graph

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Sí, ya que sólo había una rama con cambios y al hacer un merge 

- ¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28?
git checkout -- . 

- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?
git reflog 
git reset _identificador_
y los pasos para hacerle el commit

- ¿Qué comando o comandos usaste en el paso 32?
git reflog
git checkout _identificador del commit inicial_

- ¿Qué comando o comandos usaste en el punto 33?
git reflog
git checkout _identificador del commit final_

