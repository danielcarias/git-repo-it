# Clase 01 - GIT

## Archivos Markdown (archivo.md)

https://www.markdownguide.org/cheat-sheet/

## Saber si tengo git instalado

**Nota:** ` = backtick => ALT + 96

```sh
git --version
```

### Configuracion inicial de GIT

#### Configuro el usuario

```sh
git config user.name "Daniel"
```
#### Configuro el mail

```sh
git config user.email "jdcarias01@gmail.com"
```

#### Listo la configuracion del usuario

```sh
git config --get-regexp user
```

## Comando de consola

### Limpio la consola

```sh
clear
```

### Ingreso a un directorio

```sh
cd <directorio>
```

### Retrocedo directorio

```sh
cd ..
```

### Listar archivos en consola

```sh
ls -la
```

# Creo repositorio GIT

```sh
git init
```

### Paso del Working Directory (WD) al Index (staged)
**IMPORTANTE:** Cuidado, es case sensitive

```sh
git add <nombreArchivo>
```

### Paso del WD al Index mas de un archivo
```sh
git add .
```

[//]: # (git init && npm init -y && touch index.html && mkdir css && mkdir js)