# practica1github
- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
El comando git reset --hard HEAD~1 para volver al anterior commit y que los cambios anteriormente hechos dede la rama styled sie perdan en el working area

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
El comando git reset para volver al commit donde había hecho los cambios desde la rama styled

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No. Yo creo que es porque fue un merge fast forward que además no veo que haya dejado registro de commit en mi reflog

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Sí, porque el archivo git-nuestro.md había sido editado en varias lineas desde 2 ramas diferentes.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No porque el archivo era el mismo en ambas ramas (master y styled)

- ¿Qué comando o comandos utilizaste en el paso 25?
git log --graph --decorate --pretty=oneline

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Sí, porque forman la misma lista

- ¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28?
git restore git-nuestro.md

- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?
git reset al commit donde habíamos hecho el merge anterior

- ¿Qué comando o comandos usaste en el paso 32?
git reset al primer commit donde creamos el archivo

- ¿Qué comando o comandos usaste en el punto 33?
git reset apuntando al commit cuando pusimos título al documento desde la rama title
