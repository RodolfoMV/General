# Código 13

## Comandos para GIT
```
git status
```
- Para poder listar y si ver los archivos están listos para subir.
- :eye: En caso de que los archivos no estén listos se verán de color rojo y cuando lo estén se verán de color verde.

```
gid add .
git add nombre_de_archivo
```
- Se encarga de agregar los archivos a la memoria de GIT, es decir los guarda en un stash.

```
git commit -m "Comentario"
```
- Crear un punto en la línea de tiempo :time: de nuestrs cambios y a estos se le es posible adjuntar un comentario.
- :eye: Los menetarios  deben estar relacionados con los cambios que se hicieron.
```
git push origin main
```
- Sirve para subir los cambios a nuestro repositorio en la nube. En este caso a GITHUB.
```
git clone url_de_github.com
```
- Este comando me crea por defauld una carpeta con el nombre del repositorio. A través de este comando puedo descargar un proyecto que se encuentra en repositorios públicos en GITHUB.
```
git pull origin main
```
- Este comando permite actualizar en la computadora local algún cambio realizado en GITHUB.
```
git branch
```
- Sirve para poder listar los branch que tengo localmente y me dice en cual me encuentro catualmente.
```
git checkout -b 'nombre_del_branch'
```
- Sirve para crear una rama.
