# Este es el README del proyecto

## Git Add
### git add -A agrega todos los archivos con cambios
### git add -U agrega todos los archivos modificados o eliminados

## Git Reset
### git reset staging a contexto local

## Git Switch
### git switch -c <rama_a_crear> (alternativa a git checkout -b <rama_nueva>?)
### git switch -d <rama_a_borrar>

## Git Show
### git show {-s, -f} (-s es la versión corta del show, -f es la versión completa)

## Git Stash
### git stash save "nombre_identificador_stash"
### git stash list (devuelve una lista con los cambios guardados)
### git stash pop [stash@{a}] (dónde a es la posición del cambio que queremos agregar en el listado de git stash list)

## Git Checkout
### git checkout {--ours (en merge conflict, para guardar los cambios de la rama padre), --theirs (en merge conflict, para guardar los cambios en la rama hija)} <nombre_archivo_a_agregar>