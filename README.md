# Primer dia con Git/Github

Lista de comando git.

* Para poder ver la version de Git.

```bash
git --version
```

* Para configurar el correo.

```bash
git config --global user.email 
```
* Para configurar el nombre de usuario.

```bash
git config --global user.name 
```
* Sirve para poder empezar a usar el control de versiones (Git) en nuestra carpeta.

* Solo una vez.

```bash
git init
```
* Para poder ver el estado de los archivos.

```bash
git status
```
* Agrega los archivos en la memoria de la pc.

```bash
git add .
```

* Crea el registro de los cambios realizados

```bash
git commit -m "Comentario"
```
* Podemos ver el historial de los cambios realizados.

[x] Git log retorna un `id` con este, vamos a poder ver el detalle de los cambios que se hicieron en ese commit.

```bash
git log
```

* Para ver el historia de los cambios realizados en un archivo en especifico.

```bash
git show id
```
* Para cambiar el nombre de la rama principal.

```bash 
git branch -M main
```
* Para poder ver las ramas que tenemos.

```bash
git branch
```
* Para ver a que url esta asociado el repositorio.

```bash
git remote -v
```
* Para asociar el repositorio local con el remoto.

```bash
git remote add origin url
```

* Para cambiar la url del repositorio.

```bash
git remote set-url origin url
```
* Para poder subir los cambios al repositorio remoto.

```bash
git push origin main
```

* Extension utilizada  : Markdown Previe

```bash
Esta extension nos muestra de manera preliminar como se vera nuestro codigo en GitHub.
```
