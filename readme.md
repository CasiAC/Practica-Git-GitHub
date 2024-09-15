#Práctica Git & GitHub
Profesor:
Alberto Casero
kas.appeal@gmail.com
Alumno Bootcamp de IA2:
Casimiro Aunión
lechu125@hotmail.com

*PREGUNTAS*

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
	$ git reset --hard HEAD~1
	Porque me deshace el ultimo commit, perdiendo los 
	cambios realizados en el working copy.
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
	$ git reflog
	Para ve el codigo del commit al que quiero regresar	
	$ git reset --hard e5e5105
	Para volver al commit que deshice.
	Porque con reset muevo la rama style otra vez al commit
	que necesito para recuperar el archivo git-nuestro.md
	con las últimas modificaciones.
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
	No, porque styled ya tenia todos los commit que
	habia en main
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
	Nos provoca un conflicto porque el archivo git-nuestro.md
	tiene dos modificaciones distintas.
	CONFLICT (content): Merge conflict in git-nuestro.md
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
	No causo ningún conflicto porque hizo un merge fast-forward
- ¿Qué comando o comandos utilizaste en el paso 25?
	$ git log --graph --decorate --pretty=oneline
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
	Si, porque no dejaría ningun commit inaccesible.
- ¿Qué comando o comandos utilizaste en el paso 27?
	$ git reset HEAD~1
- ¿Qué comando o comandos utilizaste en el paso 28?
	$ git restore git-nuestro.md
- ¿Qué comando o comandos utilizaste en el paso 29?
	$ git branch -d title como deshice el merge
	me pide que confirme porque perdería los cambios.
	$ git branch -D title
- ¿Qué comando o comandos utilizaste en el paso 30?
	$ git reflog para ver el commit en que hicimos el merge y
	volver a él.
	$ git reset --hard 00c7712 para volver al commit donde
	hicimos el merge  “no fast-forward”.
- ¿Qué comando o comandos usaste en el paso 32?
	$ git reflog para ver cual era el commit inicial
	$ git checkout 3a25d5091261563f47df043cba227eedfd9733ba
- ¿Qué comando o comandos usaste en el punto 33?
	$ git checkout main