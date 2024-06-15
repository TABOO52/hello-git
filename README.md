# Hello-git

## Comandos GIT WINDOWS


> Inicializar el control de versiones
```sh
git init
```
> REVISAR ESTADO DE LOS FICHEROS
```sh
git status
```
> PREPARAR FICHEROS
```sh
git add.
```
```sh
git add "nombre del fichero".py
```
> REALIZAR COMMIT
```sh
git commit -m "primer cambio"
```
## E-mail y User en git
> Eliminar usuarios y E-mails antiguos (ayuda a corregir conflictos relacionados con "**Error: Permission denied (publickey)**" 
```sh
git config --global --unset user.name
```
```sh
git config --global --unset user.email
```
> Crear User y E-mail (Recomendado que el usuario sea distinto al de Git-hub y el E-mail el mmismo)
```sh
git config --global user.name "user_desktop"
```
```sh
git config --global user.email "tugmaildegithub@gmail.com"
```

## Creacion de SSH 
```sh
ssh-keygen
```
