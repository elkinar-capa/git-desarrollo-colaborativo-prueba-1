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








