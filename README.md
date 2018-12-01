# GitNuestro
Ejercicio 1 de la práctica del módulo de Git

<p><strong>¿Qué comando utilizste en el paso 11?. ¿Por qué?.</strong><br />
<code>git reset --hard HEAD~1</code><br />
Utilizamos *reset HEAD~1* para regresar al commit anterior, al incluir el parametro *--hard* forzamos que se modifique el contenido del working copy con el del commit al que nos desplazamos.</p>

<p><strong>¿Qué comando o comandos utilizaste en el paso 12?. ¿Por qué?.</strong><br />
<code>git reflog</code><br />
<code>git reset --hard <commit_hash></code><br />
Realizamos un *git reflog* para localizar el hash del commit donde estábamos antes de deshacerlo. Finalmente realizamos un *reset --hard* al commit restableciendo el working copy al estado de ese commit</p>

<p><strong>El merge del paso 13, ¿causó algún conflicto?. ¿Por qué?.</strong><br />
No causo ningún conflicto ya la rama styled contenía todos los commits de master y no se realizó ningún cambio del fichero en ninguna de las dos ramas.
</p>

<p><strong>El merge del paso 19, ¿causó algún conflicto?. ¿Por qué?.</strong><br />
Sí que se produjo un conflicto ya que el fichero fue modificado en ambas ramas, en este caso nos quedamos con los cambios del fichero *styled*.
</p>

<p><strong>El merge del paso 21, ¿causó algún conflicto?. ¿Por qué?.</strong><br />
En este caso no se produjo conflicto ya que desde la rama styled accedemos a los commits de master y el fichero es el mismo, se realizó un merge fast forward.
</p>

<p><strong>¿Qué comando o comandos utilizaste en el paso 25?.</strong><br />
<code>git log --graph --decorate --pretty=oneline</code><br />
</p>

<p><strong>El merge del paso 26, ¿podría ser fast forward?. ¿Por qué?.</strong><br />
Sí que podría ser fast forward ya que la rama master está absorviendo el trabajo de la rama title, ambas forman una lista.
</p>

<p><strong>¿Qué comando o comandos utilizaste en el paso 27?.</strong><br />
<code>git reset HEAD~1</code><br />
</p>

<p><strong>¿Qué comando o comandos utilizaste en el paso 28?.</strong><br />
<code>git checkout -- git-nuestro.md</code><br />
</p>

<p><strong>¿Qué comando o comandos utilizaste en el paso 29?.</strong><br />
<code>git branch -D title</code><br />
</p>

<p><strong>¿Qué comando o comandos utilizaste en el paso 30?.</strong><br />
<code>git reflog</code><br />
<code>git reset -- hard <commit_hash></code><br />
</p>

<p><strong>¿Qué comando o comandos utilizaste en el paso 32?.</strong><br />
<code>git reflog</code><br />
<code>git checkout <commit_hash></code><br />
</p>

<p><strong>¿Qué comando o comandos utilizaste en el paso 33?.</strong><br />
<code>git reflog</code><br />
<code>git checkout <commit_hash></code><br />
</p>
