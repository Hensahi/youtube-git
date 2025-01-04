# Comandos utilies

1. git init > inicializa un repositorio git
2. git init . > prepara los archivos modificados desde el ultimo comit para la siguiente fotografia (commit)
3. git reset . > revierte lo hecho en el paso anterior (saca los archivos del stage)
4. git commit -m > toma la fotografia a los archivos y se guarda para futuras referencias.
5. git checkout -- . > regresa el codigo al estado de la ultima fotografia tomada (ultimo commit).
6. git log > Lista todos los commits hechos
7. git commit --amend > sirve para editar el mensaje puesto en el ultimo commit
8. git checkout -b > crea una nueva rama
9. git checkout main > cambia a la rama main (se puede sustituir main por el nombre de cualquier rama existente y cambiara a ella).
10. git merge > une dos ramas
11. git branch -d "nombre_de_la_rama" > elimina una rama
12. git push > sube los comandos a la rama remota
13. git commit -am "mensaje del commit" > este es un comado que une el git add . y el git commit -m en uno solo (archivo en seguimiento)
