# Ejercicio curso GIT


* ¿Qué comando utilizaste en el paso 11? ¿Por qué?

    **`git reset --hard HEAD~1**  
  

     > Porque para poder perder los cambios realizados en el working copy (nuestro directorio del repositorio) es necesario indicarle el modificador --hard, de lo contrario no eliminaria el working copy

* ¿Qué comando utilizaste en el paso 12? ¿Por qué?

     **`git reflog`**  // para poder ver toda la actividad en el repositorio y poder indentificar que punto tengo que restaurar

     **`git reset --hard "dirección hash"`** // Primero probé con reset, pero rehacia el commit sin los cambios en git-nuestro.md asi que luego utilicé --hard. Pero lo cierto es que me costó entenderlo.

* ¿El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

    > Al ejecutar **`git merge master`** apareció un mensaje en pantalla que decía ***"Already up to date"*** esto quiere decir que las ramas que estamos intentando hacer merge entre ellas son iguales, creo que es porque styled es hija de master.
    
* El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

    > Al hacer merge salió el siguiente mensaje: ***"Automatic merge failed; fix conflicts and then commit the result."***  
    Se estaba modificando el mismo archivo en dos ramas diferentes, hubo que modificar el archivo y quedarse con una versión del mismo para poder hacer el merge correctamente
    
* El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

    > No ha creado ningun conflicto, porque al ser la rama master la que absorbe, el archivo modificado en styled es el mismo que en master.

* ¿Qué comando o comandos utilizaste en el paso 25?

    `git log --graph --decorate --pretty=oneline` 

* El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

    > Si, el HEAD continuaría por la arista generada por la rama 

* ¿Qué comando o comandos utilizaste en el paso 27?

    ` git reset direccion hash `
    
* ¿Qué comando o comandos utilizaste en el paso 28?

    `git reset --hard HEAD~1`
    
* ¿Qué comando o comandos utilizaste en el paso 29?

    `git branch -D title`
    
* ¿Qué comando o comandos utilizaste en el paso 30?

    `git reflog`  

    `git reset --hard direccion hash`
    
* ¿Qué comando o comandos usaste en el paso 32?

    `git reflog`  

    `git reset --hard dirección HASH`

* ¿Qué comando o comandos usaste en el punto 33?

    `git reflog`  

    `git reset --hard dirección HASH`
