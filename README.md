# PRESENTACION:
# SEMILLERO DE DESARROLLO DE SOFTWARE
## SOFTCARIBEAN
## PRACTICA 1
## GIT Y GITHUB

## De: Ing. Jonnier Andrés Terán Morales
## Año 2023

# --------------------------------------------------------------------------
#### Nota: Se creo en el repositorio una carpeta llamada evidenciasGit para guardar todas las evidencias de la ejecucion de la practica.
![Directorio para evidencias](./EvidenciasGit/DirectorioEvidenciasGit.PNG)


# Desarrollo de la practica 1 git-gitHub:
## - Crear repositorio
1. Crear un repositorio en vuestro GitHub llamado Practica1Softca
    - Descripción: Se crea un repositorio remoto en GitHub, el cual   llevara por nombre Practica1Softca.	
    - Evidencia: 
        - ![Creacion del Repositorio Remoto](./EvidenciasGit/CrearRepositorio1.png)
        - ![Creacion del Repositorio Remoto](./EvidenciasGit/RespositorioCreado.png)

2. Clonar vuestro repositorio en local.
-	Comando implementado:  
~~~
    - git clone https://github.com/JonnierTeran/Practica1Softca.git
~~~
-	Descripción: 
    - git clone url, Este comando nos permite clonar nuestro repositorio Remoto en un Repositorio de forma Local en el directorio en que estemos ubicados con nuestra terminal de comandos.
-	Evidencia: 
    - Principalmente nos ubicamos en nuestro escritorio, luego ejecutamos nuestro comando para clonar el repositorio remoto de GitHub, posteriormente accedemos a la carpeta que se ha creado al clonar el repositorio y procedemos a listar todos sus elementos, incluidos los elementos ocultos y podemos observar una carpeta .git La cual es oculta y contiene nuestro repositorio.
    - ![Clonar  Repositorio Remoto a local](./EvidenciasGit/ClonarRepositorio.png)

# README
3. Crear (si no lo habéis creado ya) en vuestro repositorio local un documento README.md.
    * Notas: en este documento tendrán que ir poniendo los comandos
    * que han tenido que utilizar durante todos los ejercicios
    * y las explicaciones y capturas de pantalla que consideres necesarias.

-  Comando implementado:  
~~~
    - touch README.md
~~~
-	Descripción: 
    - touch README.md, Este comando nos permite crear un archivo vacido, con el nombre y la extension que indiquemos.
-	Evidencia: 
    - Luego de generar el archivo README.md procedemos a listar todos el contenido del directorio, incluyendo los archivos ocultos del mismo y accedemos a abrir nuestro archivo README.md en nuestro editor de codigo Visual Studio Code.
    - ![Crear Archivo README.md](./EvidenciasGit/CreacionReadme.PNG)

# Commit inicial
4. Añadir al README.md los comandos utilizados hasta ahora y hacer un commit inicial con el mensaje commit inicial.
-  Comando implementado:  
~~~
    - git add . / git commit -m "initial commit"
~~~
-	Descripción: 
    - git add . , nos permite Agregar todos los Archivos que queremos añadir al el "staging" o area de preparación, y con git commit -m "initial commit" confirmamos los cambios y los guardamos en el repositorio de forma local.
-	Evidencia: 
    - Luego de generar el archivo README.md y abrirlo en visual studio code, procedemos a insertar todos los comandos y evidencias que llevamos hasta el momento, y procedemos a agregar el archivo al Area de preparacion y luego confirmamos los cambios con el primer commit.
    - ![Estructurar Archivo README.md](./EvidenciasGit/EstructuraReadme.PNG)
    - ![Git Add](./EvidenciasGit/gitadd.PNG)
    - ![Git Commit](./EvidenciasGit/gitcommit.PNG)

# Push inicial
5. Subir los cambios al repositorio remoto.
-  Comando implementado:  
~~~
    - git push -u origin maestro
~~~
-	Descripción: 
    - git push -u origin maestro, Este comando envia los commits que tengamos en nuestra rama maestro hacia la rama maestro del repositorio remoto, agregandoe el parametro -u para realizar un seguimiento a la rema remota y rama local que queremos enviar. 
-	Evidencia: 
    - Luego de hacer nuestro primer commit, procedemos a enviarlo  del repositorio local, al repositorio Remoto.
    - ![Push Inicial](./EvidenciasGit/gitpush.PNG)
    - ![Push Inicial](./EvidenciasGit/pushremoto.PNG)

# Ignorar archivos
6. Crear en el repositorio local un fichero llamado privado.txt.
-  Comando implementado:  
~~~
    - touch privado.txt
~~~
-	Descripción: 
    - touch privado.txt, nos permite crear un archivo llamado privado y que sea de estension txt.
-	Evidencia: 
    - Luego de ejecutar el comando touch privado.txt podemos mirar que se a agregado un nuevo archivo a nuestro directorio.
    - ![Crear privado.txt](./EvidenciasGit/CrearPrivado.PNG)

7. Crear en el repositorio local una carpeta llamada privada.
-  Comando implementado:  
~~~
    - mkdir privada
~~~
-	Descripción: 
    - mkdir privada, nos permite crear una nueva carpeta dentro de nuestro directorio raiz.
-	Evidencia: 
    - Luego de ejecutar el comando mkdir privada podemos mirar que se a agregado una nueva carpteta  a nuestro directorio.
    - ![Crear carpeta privada](./EvidenciasGit/Carpeta%20privada.PNG)
8. Realizar los cambios oportunos para que tanto el archivo como la carpeta sea ignorada por git.
-  Comando implementado:  
~~~
    - touch .gitignore
~~~
-	Descripción: 
    - touch .gitignore, nos permite crear un archivo oculto de texto plano, donde podremos listar todos los archivos y rutas que queremos que sean ignoradas por git.
-	Evidencia: 
    - Luego de ejecutar el comando touch .gitingnore procedemos a abrir el archivo en nuestro editor y listar los archivos que no querermos que sean rastreados por git, lugo miraremos el estado del repositorio y veremos que el archivo privado.txt y la carpeta privada no sean leidos por el repositorio.
    - ![Crear gitignore](./EvidenciasGit/creargitignore.PNG)
    - Archivos que seran ignorados:
    - ![Listar Archivos a Ignorar](./EvidenciasGit/ArchivosIgnorados.PNG)
    - Status del repositorio, donde ignora los archivos privado.txt y la carpeta privada creados anteriormente
    - ![status del proyecto ignorando](./EvidenciasGit/StatusIgnored.PNG)

# Añadir fichero 1.txt
9. Añadir fichero 1.txt al repositorio local.
-  Comando implementado:  
~~~
    - touch 1.txt
    - git add 1.txt
~~~
-	Descripción: 
    - touch 1.txt, nos permite crear un nuevo archivo llamado 1.txt
    - git add 1.txt nos permite agregar al repositorio local nuestro archivo 1.txt
-	Evidencia: 
    - Luego de ejecutar crear el archivo y ejecutar el comando git add 1.txt podemos mirar que se a agregado con exito el archivo 1.txt a nuestro repositorio.
    - ![Add 1.txt](./EvidenciasGit/add1txt.PNG)

