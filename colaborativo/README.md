# Clase 01 - Git desrrollo colaborativo


## Crear un repositorio de GIT

```sh
    git init
```

## Configurar por primera vez y unica  A GIT

```sh

git config --global user.name "maxi principe"
git config --global user.email "elll@gmail.com"

## git config --list para ver si tengo sesion inciada

```
## Cambiar de aca en adelante como se va  llamar la rama principal por defecto

```sh
git config --global init.defaultBranch main
```

```

otros

git log --oneline

git log

```

```
para pasar de working directory:

git add <nombre-archivo>

para pasar a staging area/index:

git commit -m "mensaje"

```

```

git status para ver estado

untraked: git sabe que existe pero no los esta siguiendo

que se hizo en el ultimo commit?
git show hash (identificador de commit: se ve con git log --oneline) ---> para salir de los cambios tocar q

head: (tracked)


modifided -> significa que hay un cambio en el archivo commiteado sobre el que git ya tiene seguimiento

¿que se modifico? git diff, para salir es con q

