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

<<<<<<< HEAD
Fast-Forward (No hay ningun cambio que se solape con lo que esta en la otra rama)

Agrego cosas que quiero tener en consideracion.

* Tener en cuenta subir una rama al remoto
* Ver Clone
* Ver Fork
=======
Fast-forward - Uniones automaticas (No hay ningun cambio que se solape con lo que esta en la otra rama)

Recursiva - Uniones automaticas (No hay colisiones de cambios)

Manual - Conflictos (Ocurre cuando hay modificaciones en las mismas lineas)
>>>>>>> master
