# Práctica GIT

### Sierra Vives, Lorena



# PracticaGit - Respuestas

--

**1. ¿Qué comando o comandos utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1` 

Para deshacer el último commit .

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reflog y git reset --hard identificador`

Añado el archivo ''don-quijote.md'' al staging area y rehago el último commit .

--

**3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

`Si, no permitía porque tenía más contenido que la rama absorbida`

Para que la ram "master" absorba la rama  ''styled''.
No causa conflictos.

--

**4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

`No, hace un merge ff`

Para que la rama ''styled'' absorba a la rama ''htmlify''.
Sí causa conflictos.

--

**5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

`No, hace un merge ff`

Para que la rama " master absorba la rama "styled".

--

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

`git log --graph`

--

**7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

`Sí, solo hay que quitar el comando --no-ff. Pero el merge ff no te permite hacer commit` 

--

**8. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1`

--

**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git reset --hard identificador`

--

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -d title`

--

**11. ¿Qué comando o comandos utilizaste en el paso 30?**

`git reflog y git reset --hard identificador`

--

**12. ¿Qué comando o comandos usaste en el paso 32?**

`git checkout identificador`

--

**13.¿Qué comando o comandos usaste en el paso 33?**

`git checkout identificador`

--
