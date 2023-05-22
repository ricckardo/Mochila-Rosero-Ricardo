
# Git Cheatsheet

Git es un sistema de control de versiones que te ayuda a gestionar cambios en tus archivos. Imagina que estás escribiendo una historia en una computadora y quieres mantener un registro de cada cambio que haces. Git actúa como un marcador mágico que recuerda todas las diferentes versiones de tu historia.




## Configuración e inicialización

Configuración de información de usuario, inicialización y clonación de repositorios
```bash
  git init
```
Inicializando un directorio existente como un repositorio de git
```bash
  git clone
```
Clonar un repositorio entero de una ubicacion alojada via URL

## Stage & Snapshot
```bash
  git status
```
Muestra los archivos modificados en el working directory, que estan staged para tu siguiente commit

```bash
  git add [archivo]
```
Añade un archivo para el siguiente commit (stage)

```bash
  git add .
```
Añade todos los archivos

```bash
  git commit -m "[Mensaje descriptivo]"
```
Hace commit hacia la rama

## Branch & Merge
```bash
  git branch
```
Lista tus branches
```bash
  git branch [nombre-branch]
```
Crea un nuevo branch dentro del commit actual
```bash
  git checkout
```
Cambia hacia otro branch y lo pone en tu working directory
