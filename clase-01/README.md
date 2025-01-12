# Git Desarrollo Colaborativo

## Markdown
lenguaje de etiquetado para timar apuntesn anotaciones  y dar instrucciones sobre el proyecto.



```sh
git init # crea la carpeta .git dentro del directorio/carpeta actual
```

## Configuracion Inicial de GIT

```sh
git config --global user.name "Angel Nicolas Solis"  
git config --global user.email "ansolisju@gmail.com"
```

## Verificar que la configuracion se hizo

```sh
git config --get-regexp user
```

## Como remover algo que no deseo que este

```sh
git config --global --unset user.mail
```

## Cambiar el editor a nano

```sh
git config --global core.editor nano
``` 

## Cambiar el nombre por defecto de la rama principal

```sh
git config --global init.defaultBranch main
```
## Ver las configuraciones hechas en un editor

```sh
git config --global -e
```
## Ver el estado de los archivos del proyecto

```sh
git status
```


## Cambiar a Nano

## Areas posibles en las que pueden estar los archivos

*Workig Directory (Directorio de Trabajo) donde van agragando, borrando el archivo del proyecto durante
 desarrollo

*Staging Area (Area de Control de Cambios) Se agregan los archivos para darle seguimiento y posteriormente sacarles una foto (Commit)

*Local Repo (Area de validacion de cambios, donde se registraron las modificaciones realizadas) Donde van a estar todas las fotos (commit) que vaya sacando.