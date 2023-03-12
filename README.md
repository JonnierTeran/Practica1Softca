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
    - git clone https://github.com/JonnierTeran/Practica1Softca.git
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
    - touch README.md
-	Descripción: 
    - touch README.md, Este comando nos permite crear un archivo vacido, con el nombre y la extension que indiquemos.
-	Evidencia: 
    - Luego de generar el archivo README.md procedemos a listar todos el contenido del directorio, incluyendo los archivos ocultos del mismo y accedemos a abrir nuestro archivo README.md en nuestro editor de codigo Visual Studio Code.
    - ![Crear Archivo README.md](./EvidenciasGit/CreacionReadme.PNG)

# Commit inicial
4. Añadir al README.md los comandos utilizados hasta ahora y hacer un commit inicial con el mensaje commit inicial.
-  Comando implementado:  
    - git add . / git commit -m "initial commit"
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
    - git push -u origin maestro
-	Descripción: 
    - git push -u origin maestro, Este comando envia los commits que tengamos en nuestra rama maestro hacia la rama maestro del repositorio remoto, agregandoe el parametro -u para realizar un seguimiento a la rema remota y rama local que queremos enviar. 
-	Evidencia: 
    - Luego de hacer nuestro primer commit, procedemos a enviarlo  del repositorio local, al repositorio Remoto.
    - ![Push Inicial](./EvidenciasGit/gitpush.PNG)
    - ![Push Inicial](./EvidenciasGit/pushremoto.PNG)


