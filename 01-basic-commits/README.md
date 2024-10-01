# Git Kata: Commits Básico
This kata will introduce you to the `git add` and `git commit` commands.

## Configuración:

1. Utiliza el commando `git log --oneline -- 01-basic-commits/` para ver los ejercicios.
2. Ejecuta `source setup.sh` (o `setup.ps1` en PowerShell)

## Comandos útiles
- `git add`
- `git commit`
- `git commit -m "Mi mensaje"`
- `git log`
- `git log -n 5`
- `git log --oneline`
- `git log --oneline --graph`
- `touch filename` para crear un fichero (o `sc filename ''` en PowerShell)
- `echo contenido > file` para sobreescribir un fichero con contenido (o `sc filename 'contenido'` en PowerShell)
- `echo contenido >> file` para anexar contenido al fichero (o `ac filename 'contenido'` en PowerShell)


## Configuración inicial de git
1. `git config --global user.name "John Doe"`
2. `git config --global user.email "johndoe@example.com`

Para los que tienen miedo a vim:
- `git config --global core.editor nano`

Para los que les gusta el modo windows:
- `git config --global core.editor notepad`
