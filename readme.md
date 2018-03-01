
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
	git reflog para ver el código del git deshecho y después git reset --hard "código del commit"


- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
	No, al ser styled hijo de master no puede absorberlo ya que contiene la misma información.



- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
	Sí, porque entre el el archivo guardado en los commits PASO 10 y PASO 13, tienen diferentes contenidos.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
	No, simplemente subimos master a la altura de styled.

- ¿Qué comando o comandos utilizaste en el paso 25?
	git log --graph (git graph no me funcionaba).

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
	No, ya que title y master no se encuentran en la misma línea.

- ¿Qué comando o comandos utilizaste en el paso 27?
	git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28?
	git reset --hard HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 29?
	git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?
	Abrí git reflog para ver el código dónde realicé el merge y utilicé el comando git reset "código de merge"

- ¿Qué comando o comandos usaste en el paso 32?
	git checkout "código del commit inicial"

- ¿Qué comando o comandos usaste en el punto 33? 
	git reset --hard "código estado final"