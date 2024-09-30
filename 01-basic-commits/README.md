# Git Kata: Commits Básico
This kata will introduce you to the `git add` and `git commit` commands.

## Configuración:

1. Ejecuta `source setup.sh`

## Los ejercicios

1. Usa `git status` para ver en qué rama estás.
2. ¿Cómo se ve `git log`?
3. Crea un fichero
4. ¿Cómo se ve ahora el resultado de `git status`?
5. `add` el fichero al área de preparación
6. ¿Cómo se ve ahora `git status`?
7. `commit` el fichero al repositorio
8. ¿Cómo se ve ahora `git status`?
9. Cambia el contenido del fichero que creaste anteriormente
10. ¿Cómo se ve ahora `git status`?
11. `add` el cambio del fichero
12. ¿Cómo se ve ahora `git status`?
13. Cambia el fichero otra vez

## Comandos útiles
- `git add`
- `git commit`
- `git commit -m "Mi mensaje"`
- `git log`
- `git log -n 5`
- `git log --oneline`
- `git log --oneline --graph`
- `touch filename` para crear un fichero
- `echo contenido > file` para sobreescribir un fichero con contenido
- `echo contenido >> file` para anexar contenido al fichero


## Configuración inicial de git
1. `git config --global user.name "John Doe"`
1. `git config --global user.email "johndoe@example.com`

Para los que tienen miedo a vim:
- `git config --global core.editor nano`

Para los que les gusta el modo windows:
- `git config --global core.editor notepad`
