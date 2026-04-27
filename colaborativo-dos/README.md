# CLASE 2

## .gitignore
Me permite indicar los archivos o carpetas que quiero que no fomen parte del repositorio.

**Se crea el archivo .gitignore dentro de la raiz del proyecto. **

## .gitkeep
Ayuda a git a versionar carpetas que quiero que sean parte del repositorio pero estan vacias.

** Se crea l archivo .gitkeep dentro de la carpta que quiero que git verione**

## RAMAS (branches)

Las ramas me permiten trabajar en diferentes partes del proyecto de manera auxiliar sin afectar las funcionalidades (del codigo fuente que ya funciona)

### Listar ramas locales

```sh
git branch
```
### Listar ramas remotas

```sh
git branch -r
```
### Listar ramas locales y remotas

```sh
git branch -a
```
```sh
git commit (sin -m)

agregar mensaje y tocar donde dice commit
```

** ver como cambiar de vim o vsc a nano

## Otra manera de hace un commit para agregar mas informacion de lo que se hizo dentro de ese commit (A PARTIR DE LA TERCERA LINEA)

```sh
git add <nombre/archivo>
```
2. Hago un commit

```sh
git commit # Abre el nano o editor que tenga VIM/Vsc para agregar mensaje, titulo y a partir de la tercera linea mas detalles

```
3. Una vez escrito el mensajes para confirmar

Ctrl+ O + Enter (guardar) | Ctrl + x











** Crear una rama/bifurcacion
```sh
 git branch feature/ramas  #cambiar a main
```
** Cambiar/moverme a otra rama
```sh
 git switch feature/ramas  #cambiar a feature/ramas
```


** Feature/ rama
```sh

git switch -c feature/ramas #crear rama feature/ramas y cambiar a ella

```

```sh
 git branch -av  #para ver en que rama estoy
```

```sh
 git switch main  #cambiar a main
```


```sh
 git switch -  #cambiar a la rama anterior
```


*** Ver diferencia entre dos ramas

```sh
 git diff <nombre-rama>

```
# En main y quiero ver la direrencia entre amin y feature/ramas

```sh
 git diff feature/ramas

```


## Fucionar dos ramas

**IMPORTANTE** Siempre que quiera traerme los cambios de una rama a otra tengo que estar ubicado en la rama a donde quiero traer los cambioss

```sh
 git merge feature/ramas # fusionar main con feature/ramas

```

# Solo si el archivo esta en el repositorio
```sh
 git commit -am "add y commit juntos"

```
* Fast/forward: fusion hecha automaticamente por git, sin conflictos
* Conflictos: Sucede cuando en las diferentes ramas hay cambis en las mimas lineas de los mismos archivos

