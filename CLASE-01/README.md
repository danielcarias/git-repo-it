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
git config --global user.name "Daniel"
git config user.name "Daniel"
```
#### Configuro el mail

```sh
git config --global user.email "jdcarias01@gmail.com"
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

### Para saber lo que esta pasando en el WD
Comparar el WD con el ultimo commit

```sh
git status
```

### Paso del Working Directory (WD) al Index (staged)
**IMPORTANTE:** Cuidado, es case sensitive

```sh
git add <nombreArchivo>
```

Ej:

```sh
git add README.md
```
### Paso del WD al Index mas de un archivo
```sh
git add .
```


### Para pasar del INDEX al REPOSITORIO LOCAL

```sh
git commit -m <mensaje>
```
Ej:

```sh
git commit -m "Agrego el archivo README.md"
```

### GIT LOG

```sh
git log 
```
### 

```sh
git log --oneline
```

### PASOS para subir mi repo local al remoto

1. git init
2. git status
3. git add README.md
4. git commit -m "first commit"
5. git remote add origin https://github.com/<tuNombreUsuario>/<tuRepo>
6. git push -u origin master


[//]: # (git init && npm init -y && touch index.html && mkdir css && mkdir js)
[//]: # (Grupo Telegram: https://t.me/+lDDtiKn3Isc5OGNh)