# Tarea Recetas

## Creación del repositorio

1 En la página principal de GitHub en la parte superior izquierda encontramos
un botón verde "New", podemos dar en éste para crear el nuevo repositorio con el nombre Recetas

2 En nuestro escritorio abrimos el Git Bash y nos ubicamos en  el directorio donde
queremos guardar nuestro repositorio.

3 Una vez ubicados hacemos un git clone <URL>, en este caso [https://github.com/carloshoyos98/recetas.git](https://github.com/carloshoyos98/recetas.git)

4 Creamos y modificamos el README con el comando *nano README.md*

5 Añadimos el README al repositorio local con *git add .* y hacemos el primer commit
con *git commit -m "Mensaje del commit"*

6 Para subir los cambios al repositorio remoto de GitHub hacemos *git push origin master*

7 Creamos otra rama *git branch recetas* en la que añadimos los ficheros con las recetas.

8 Añadimos y subimos los cambios de la rama igual que en la master con el README.

9 Finalmente uno las dos ramas con un *git merge recetas*

***********
## Recetas

1 [Crema de calabaza](./cremacalabaza.md)

2 [Salmón al horno](./salmonhorneado-md)
