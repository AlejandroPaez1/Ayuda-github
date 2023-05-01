# Ayuda-github
codigos en caso no se pueda actualizar los cambios

![por_si_acaso](imagen.jpg)

```
git pull --rebase origin master
git fetch origin main:tmp
git rebase tmp
git push origin HEAD:main
git branch -D tmp
```
## para subir a otro repositorio invitado 

- primero hay que crear un alias 
```
git remote add <nombre-alias> <url-remote>
```

```
git pull --rebase <nombre-alias> main
git fetch <nombre-alias> main:tmp
git rebase tmp
git push <nombre-alias> HEAD:main
git branch -D tmp
```
 


## para subir una actualizacion de codigo a github se usan los comandos se pone otro nombre en dnde dice prueba
```
git add .
git status
git commit -m "prueba"
git push -u origin main
```
# Link para ayuda de Sintaxis para editar README
[poder escribir mejor readme](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

> AlejandroP
