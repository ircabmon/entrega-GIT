# entrega-GIT
#Irene Cabria Mondéjar 2DC

**- ¿Qué comando utilizaste en el paso 11? ¿Por qué?**
git reset --hard HEAD~1 //Porque así se eliminan todos los cambios guardados en ese commit.

**- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**
git reflog
git reset --hard 3241700 //(número identificador del commit borrado anteriormente)
El primero es para encontrar el identificador del commit borrado, el segundo es para recuperarlo.

**- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**
No, porque la rama styled es hija de la rama master.

**- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**
Sí, porque los dos archivos de las diferentes ramas son distintos y hay que elegir uno. Styled.

**- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**
No causa ningún conflicto porque ambas ramas no coinciden en algún archivo cambiado.

**- ¿Qué comando o comandos utilizaste en el paso 25?**
git graph

**- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**
Sí, pero el no fast forward hace un commit al terminar la operación; por lo que no tenemos que hacerlo nosotros

**- ¿Qué comando o comandos utilizaste en el paso 27?**
git reset HEAD~1, para que los cambios se queden en workingcopy

**- ¿Qué comando o comandos utilizaste en el paso 28?**
git checkout -- don-quijote.md
Para descartar los cambios.

**- ¿Qué comando o comandos utilizaste en el paso 29?**
git branch //para saber en qué rama estoy
git branch -D title //para eliminar la rama title

**- ¿Qué comando o comandos utilizaste en el paso 30?**
git reflog
git reset --hard e757f8d (identificador del merge de master y title)

**- ¿Qué comando o comandos usaste en el paso 32?**
git reflog
git checkout b52b549 (para acceder al primer commit)
git tag incial (para ponerle la etiqueta del siguiente paso)

**- ¿Qué comando o comandos usaste en el punto 33?**
git reflog
git checkout e757f8d (para acceder al estado final, con el identificador)
git tag title (para ponerle la etiqueta)
