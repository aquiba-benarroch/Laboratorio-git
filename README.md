# Laboratorio-git
Aquiba Benarroch Bittan
Leonardo Rodriguez A01029331
# ***GitHub***

![GitHub logo](/Imagenes/github-logo.png)

### ¿Qué es Git?
> Git es un software de control de versiones que nos permite registrar los cambios hechos a archivos de computadora. Un sistema de control de versiones registra los cambios a un archivo, o un conjunto de archivos a lo largo del tiempo, de manera que se puedan recuperar ciertas versiones posteriormente. Git hace esto a través de repositorios (almacenamiento virtual del proyecto).  
### ¿Qué es GitHub?
> GitHub es una plataforma web que permite almacenar los repositorios de una manera remota, con el fin de colaborar y coordinar los avances de un proyecto que pertenece a un equipo de trabajo.

# ***Bitácora***
## Semana Uno
Durante las primeras clases esto es lo que hemos hecho:
- Aprendimos que es Git, GitHub y Git Bash. 
- Instalamos Git 
- Iniciamos sesión en GitHub y creamos una sesión. 
- En Git Bash creamos una SSH (Secure SHell) y la introducimos en GitHub. SSH es una red de comunicación segura para poder comunicar nuestra computadora y el servidor. Lo que se hace es que se crean dos llaves iguales. Una de estas se queda en nuestra computadora y otra en el servidor. Siempre que se quiere hacer un cambio, el servidor nos pide que usemos nuestra llave (contraseña que creamos) y si ambas coinciden te permite hacer los cambios.
- Creamos nuestro repositorio.
- Hicimos un clon del repositorio en la computadora. Esto debido a que normalmente trabajaremos desde la computadora y no directamente en el repositorio en internet. 
- Aprendimos a usar Git Bash
- Creamos un archivo nuevo, lo integramos en el repositorio local y luego lo subimos al repositorio remoto. 
- Instalamos VS Code y creamos la bitácora.
- Instalamos la extensión de Markdown en VS Code y lo aprendimos a usar (poner títulos, subtítulos, imágenes).
## Semana Dos
- Vamos a aprender a hacer diferentes ramas en el repositor, hacer commits en esas ramas y luego integrarlo todo al main. 
- Creamos dos repositorios. El primero se llamó Operations y el segundo Multiplications. Lo creamos a través de Git Bash.
- Hicimos un documento en cada una de las ramas. Este documento lo guardamos en nuestra carpeta de Git.
- Agregamos los cambios e hicimos commit. Esto lo que hace es que agrega los documentos en las ramas, pero no en el Main. 
- Nos metimos en GitHub y hicimos un merge de lo que había en la rama al main. 
- Eliminamos la rama que creamos y todo quedó listo en nuestro repositorio remoto.
- En Git Bash usamos el git fetch para que actualizara y borrara lo que se borró en el repositorio remoto. 
- Hicimos un git pull para actualizar nuestro repositorio local. 
---
# ***Git Bash***

![Git Bash logo](/Imagenes/Logo%20GitBash.webp)

### ¿Qué es Git Bash?
> Git Bash es una aplicación que te permite usar Git en tu
computadora.
##Funcionamiento de Git Bash
### Comandos aprendidos
- `pwd: present working directory` Esto lo que hace es qué nos dice en que directorio estamos. 
- `ls: list` Esto nos enseña que hay dentro de la carpeta en la que estamos.
- `cd: Change directorty`Esto nos sirve para cambiar de directorio. 
- `git status` Este comando nos sirve para ver si ha habido algún cambio en el directorio de trabajo. 
- `git add -A` Este comando sube los cambios realizados a los archivos a una zona de pruebas para que Git empiece a rastrearlos.
- `git commit -m "Descripción del commit"` Sube los archivos o cambios al repositorio local. 
- `git push -u origin main` Sube los archivos del repositorio local (computadora) al remoto (internet). 
- `git pull` Este comando sube los archivos o cambios del repositorio remoto al local. Este se usa en caso de que se trabaje desde el repositorio remoto. 
- `git branch -a` Este comando nos enseña cuales son las ramas que tenemos en el repositorio. 
- `git checkout main` Nos cambia de una rama a la rama principal. 
- `git checkout -b (nombre de la nueva rama. Es sin paréntesis)` Este comando nos cambia a una nueva rama. El -b crea la nueva rama y luego se agrega el nombre de la rama. Esto se usa cuando quieres crear una nueva rama y cambiarte a esa rama en un solo paso.
- `git Branch -b (nombre de la nueva rama. Es sin paréntesis)` Este comando va a borrar una rama. La rama que se borra es la que pongamos. 
- `git fetch –prune` Este comando lo que hace es descargar los cambios que se hicieron en un repositorio remoto. También esto lo que hace es eliminar todo lo que se ha marcado para borrar. Es decir, si borramos un Branch en el repo remoto, esto lo borra en el local y ya luego necesitamos hacer el pull para que se actualice en el local. 

## ***Referencias***
- Markdown Guide: [Markdown Guide](https://www.markdownguide.org/)
