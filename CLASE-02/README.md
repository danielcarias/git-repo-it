# Clase 02 - GIT

## GIT LOG

### Muestra los commits
```sh
git log
```
**NOTA:** Para salir es con la letra **q**


### Muestra los commits en forma abreviada
```sh
git log --oneline
```
### Por fecha

```sh
git log --since="2021-12-20"
git log --after="2021-12-20"
git log --before="2021-12-27"
git log --after="2021-12-20" --before="2021-12-27"
```
### Muestra la cantidad de commits elegidos.

Ejemplo: 2 commits

```sh
git log -2 # cantidad de commits que va a mostrar el git log
```

```sh
git log --oneline --decorate --all --graph
```

GIT IGNORE
Sirve para ignorar archivos que no quiero seguir.

Creo el archivo **.gitignore** en el directorio raiz y dentro coloco el nombre del archivo o la carpeta que no quiero seguir.


### GIT KEEP
Me permite seguir una carpeta vacia.

Creo un archivo llamado **.gitkeep** que lo que hace es tener en cuenta la carpeta vacia