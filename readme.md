# Practica Git

### ¿Qué comando utilizaste en el paso 11? ¿Por qué?
`git reset --hard HEAD~1`, porque se debia deshacer el último commit perdiendo los cambios realizados en el working copy.

### ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
* `git reflog`: Para encontrar el commit que habiamos desecho y tomar el identificador
* `git reset --hard 74e638a` : Para rehacer el último commit que habiamos desecho

### El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No, porque en el grafo de git, la styled y master forman una lista, pero styled esta un commit más actualizado que master, por lo que git entrega como resultado, que styled ya esta actualizado(Already up to date.)

### El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Si, porque la rama styled y htmlify contienen cambios diferentes en las mismas lineas del archivo git-nuestro.md

### El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, porque el commit que tiene la rama master, styled ya lo tiene, por lo que **Git** dio como resultado un **no fast forward merge**, ya que en el grafo se forma una lista entre las dos ramas.

### ¿Qué comando o comandos utilizaste en el paso 25?
`git log --graph --pretty=oneline --decorate`

### El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Si, porque en el grafo de git, title ya tiene todos los commits de master y estas dos ramas forman una lista.

### ¿Qué comando o comandos utilizaste en el paso 27?
`git reset HEAD~1`

### ¿Qué comando o comandos utilizaste en el paso 28?
`git reset --hard HEAD`

### ¿Qué comando o comandos utilizaste en el paso 29?
`git branch -D title`

### ¿Qué comando o comandos utilizaste en el paso 30?
* `git reflog`
* `git reset --hard 91b2875`

### ¿Qué comando o comandos usaste en el paso 32?
* `git reflog`
* `git reset --hard 1369c0a`

### ¿Qué comando o comandos usaste en el punto 33?
* `git reflog`
* `git reset --hard 91b2875`
