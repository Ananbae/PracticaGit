# Práctica GIT

### Antequera Baeza, Andrea

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset  --hard HEAD~1` 

Porque así se borraría lo último que hubiese sido añadido en el working copy

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reflog` `git reset --hard ef09fa6`

El primero para saber cuan sería la direccion (Código) donde queda lo reseteado y el segundo para volver a él.

--

**3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?** 

No, se ha hecho un merge utilizando la estrategia recursiva. Pone: Already up to date.

--

**4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Sí, da conflicto por el contenido que hay en las rama, ya que modificamos el texto del archivo md.

--

**5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No da ningún conflicto. Se ha hecho un merge utilizando estrategia recursiva. Ha sido fast foward. La rama master tiene el mismo commit que la rama styled, de forma que master absorbería todos los commits creados en la rama styled (y no había ramificaciones).

--

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

`git graph´

Para relizar el diagrama

--

**7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?** 

 Si, porque al estar en la misma lista de ramas (no hay ramificaciones) no se perdería ningún commit de title al ser absorbido por master.

--

**8. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1` 

--

**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git checkout --don-quijote.md` 

--

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -D title` 

--

**11. ¿Qué comando o comandos utilizaste en el paso 30?**

`git reflog` , localizo el commit en el que hice el merge de title con master y ejecuto los comandos `git reset --hard 606af12` 

--

**12. ¿Qué comando o comandos usaste en el paso 32?**

`git reflog`
`git reset --hard d36d767`

--

**13. ¿Qué comando o comandos usaste en el punto 33?**

`git reflog` `git reset --hard 8654803` 

--
