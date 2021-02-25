# refuerzo-JGF

1. Creamos el repositorio
    ![1. Crear un repositorio](imagenes/act1.jpg)

2. Clonamos el repositorio
    ![2. Clonamos el repositorio](imagenes/act2.jpg)

3. Creamos el README
    ![3. Creamos el README](imagenes/act3.png)

4. Hacemos el commit inicial
    ```
    $ git add .
    $ git commit -m "commit inicial"
    ```
    ![4. Hacemos el commit inicial](imagenes/act4.png)
5. Hacemos el push inicial
    ```
    $ git push
    ```
    ![5. Hacemos el push inicial](imagenes/act5.png)
6. Ignoramos los archivos.

    a) Creamos el archivo privado.txt
    ```
    $ touch privado.txt
    ```
    ![6a. Creamos el archivo privado.txt](imagenes/act6a.png)

    b) Creamos la carpeta
    ```
    $ mkdir privada
    ```
    ![6b. Creamos la carpeta](imagenes/act6b.png)

    c) Hacemos los cambios oportunos para que el archivo y la carpeta sean ignorados por git 
    ```
    $ echo "privado.txt" > .gitignore
    $ echo "privado/" >> .gitignore
    ```
    ![6c. Hacemos los cambios oportunos para que el archivo y la carpeta sean ignorados por git ](imagenes/act6c.png)
7. Añadimos el fichero
    ```
    $ touch 1.txt
    ```
    ![6a. Creamos el archivo privado.txt](imagenes/act7.png)
8. Creamos el tag
    ```
    $ git tag -a v0.1 -m "8. Creamos el tag"
    ```
    ![6a. Creamos el archivo privado.txt](imagenes/act8.png)
9. Subimos el tag
    ```
    $ git push --tags
    ```
    ![6a. Creamos el archivo privado.txt](imagenes/act9.png)
10. Mostramos la cuenta de GitHub

    a) Nos ponemos una foto de perfil en GitHub
    ![10. Nos ponemos una foto de perfil en GitHub](imagenes/act10.png)

11. Hacemos un uso social de GitHub

    a)
    ![6a. Creamos el archivo privado.txt](imagenes/act11a1.png)
    ![6a. Creamos el archivo privado.txt](imagenes/act11a2.png)
    b)
    ![6a. Creamos el archivo privado.txt](imagenes/act11b.png)
    c)
    ![6a. Creamos el archivo privado.txt](imagenes/act11c.png)
12. Creamos una tabla en GitHub

| Nombre |  Enlace GitHub
| ------------- | ------------- |
| Pablo Leal  | https://github.com/Pabloleabr  |
| Laura Álcon  |  https://github.com/axrynz |
| Eduardo Martínez | https://github.com/edumarrom |
13. Ponemos a "antvazcar" como colaborador de refuerzo en GitHub