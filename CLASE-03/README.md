# Clase - 03 - GIT

## Repaso de Branch

### Listo ramas

```sh
git branch
```

### Creo una rama

```sh
git branch <nombreRama>
```

### Cambio entre ramas

```sh
git switch <nombreRama>
```

## Git Merge

### Tipos de Merge

Fast-forward - Uniones automaticas (No hay ningun cambio que se solape con lo que esta en la otra rama)

Recursiva - Uniones automaticas (No hay colisiones de cambios)

Manual - Conflictos (Ocurre cuando hay modificaciones en las mismas lineas)

### Abortar Merge

```sh
git merge --abort
```

### TAREAS: Agrego cosas que quiero tomar en consideracion

* Tener en cuenta subir una rama al remoto
* Ver Clone
* Ver Fork

## ALIAS

## Como creo un alias?

```sh
git config alias.lg "log --oneline --decorate --all --graph"
git config alias.l "log --oneline"
git config alias.s "status --short"
```

### Para editar el archivo de configuracion de GIT

```sh
git config -e
```

```sh
git config --unset alias.s
```