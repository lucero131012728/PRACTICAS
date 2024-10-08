# Práctica 8

## a. ¿Cómo se inicializa un repositorio en Git?
- Para inicializarinicar un repositorio en Git, se utiliza el siguiente comando en la terminal dentro de la carpeta del proyecto:

**Asi se ve en la terminal :**
```bash
git init

```

## b. ¿Cómo creas un repositorio en GitHub? 
- Para crear un repositorio en GitHub, primero inicia sesión en tu cuenta, luego haz clic en el botón "New" en la parte superior derecha y sigues las instrucciones para nombrar y configurar tu nuevo repositorio.

## c. ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?
- Para vincular un repositorio local con uno remoto,se usa en sig comando en la terminal comando, reemplazando <URL-del-repositorio> 
**Asi se ve en la terminal :**
```bash
git remote add origin <URL-del-repositorio>
```

## d. ¿Cuál es el flujo básico de trabajo en Git y GitHub?
- El flujo básico de trabajo incluye los siguientes pasos:

1 Hacer cambios en el código.

2 Agregar cambios al "stage" con git add.

3 Hacer un commit con git commit.

4 Subir los cambios al repositorio remoto con git push.

**Asi se ve en la terminal :**

```bash
git add 
git commit
git push
```

## e. ¿Para qué sirve el archivo .gitignore?
- gitignore se utiliza para especificar qué archivos o directorios deben ser ignorados por Git, evitando que se suban al repositorio

**Asi se ve en la terminal :**

```bash
touch .gitignore
```

## f. ¿Cuál es el propósito de una rama?
- Una rama en Git permite trabajar en diferentes versiones del proyecto de manera aislada.

**Asi se ve en la terminal :**

Crear una nueva rama:

```bash

git branch nombre-de-la-rama
```
Cambiar a una rama existente:

```bash

git checkout nombre-de-la-rama
```
Crear y cambiar a una nueva rama (comando abreviado):

```bash
git checkout -b nombre-de-la-rama
```
Listar todas las ramas:

```bash

git branch
```
Fusionar una rama en la rama actual:

```bash
git merge nombre-de-la-rama
```
Eliminar una rama:

```bash

git branch -d nombre-de-la-rama
```
Eliminar una rama de forma forzada (si tiene cambios no fusionados):

```bash
git branch -D nombre-de-la-rama
```
Ver el estado de las ramas y su historial:

```bash

git log --oneline --graph --decorate --all
```
## g. ¿Qué es una fusión?
- Una fusión (merge) es el proceso de combinar cambios de una rama en otra. Para fusionar, usas:

**Asi se ve en la terminal :**

```bash
git merge nombre-de-la-rama
```

## h. Explica los diferentes tipos de fusión que existen.
 
- Los tipos de fusión son:

Merge directo:

```bash

git merge nombre-de-la-
```
Fast-forward: Ocurre automáticamente si no hay commits en la rama principal.

Rebase:

```bash

git rebase nombre-de-la-rama
```
## i. ¿Cómo puedes ver el historial de tu repositorio?
- Para ver el historial de commits, usa:

```bash
git log
```
## j. ¿Cuál es el propósito de una etiqueta?
- Las etiquetas marcan puntos específicos en la historia del repositorio. Para crear una etiqueta, utiliza:

```bash

git tag -a v1.0 -m "Descripción de la versión"
```

