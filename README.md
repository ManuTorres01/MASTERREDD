¿Qué es Git ?
Es un sistema de control de versiones, es distribuido, es decir que múltiples personas pueden trabajar en equipo, es open source y también se adapta a todo tipo de proyectos desde pequeños hasta grandes, además, se pueden fusionar archivos, guarda una línea de tiempo a lo largo de todo el proyecto.
¿Qué es Github?
Es una plataforma de desarrollo colaborativo, o también llamada la red social de los desarrolladores donde se alojan los repositorios, el código se almacena de forma pública pero se puede hacer privado con una cuenta de pago.
Aprendiendo sobre comandos
Empezaremos con los 6 comandos mas importantes en consola para todo principiante.
pwd : Para ubicarme en que directorio me encuentro.
cd : Para situarse dentro del directorio.
ls : Para listar todo lo que está dentro de donde nos situamos
ll : Para listar de una forma más grande
Qué entendemos por -rw-r-r — 1
READ (r)
WRITE (w)
EXECUTE(x)
Son permisos para los directorios y archivos.
mkdir : Para crear directorios.
touch : Para crear los ficheros archivos.
Primer uso de Git Bash
1.git init : Todo lo que se escriba dentro de la carpeta va a estar dentro del .git
Allí va el historial de versiones y está oculto dentro de la carpeta.
Solo una vez.
2. git add : Lleva el control de los archivos que se agregan luego de escribir ese comando.
2.1 git add . : Es para todo agregar pero no es recomendable.
3. git commit : Comando que indica que esta lista alguna funcionalidad para que sea una versión del código.
4. git commit — m “Mi primer commit”
Se repite n veces cada vez se cambia el código.
Push
Básicamente lo que realiza un push es publicar lo que se encuentra en nuestro servidor local y llevarlo al servidor remoto de Github
El push empuja lo de nuestro servidor local al servidor remoto en github
Pull
El pull trae los cambios de nuestro repositorio remoto y los actualiza al repositorio local.
5. git remote add origin [URL DEL REPOSITORIO EN GITHUB]
6. git push origin master : Es el nombre que se le pone al repositorio remoto al que se conecta.
¿Qué es un Branch ?
Es una rama diferente a la rama master que tenemos y se utiliza para trabajar de forma colaborativa y eficaz con esto podremos asignarnos tareas y ordenar mejor nuestro proyecto.
¿Qué es un Merge?
Es una fusion entre ramas.
Los conceptos entre Branch y Merge suelen ser dificiles de aprender pero con los ejemplos podrás tener una mejor idea de que es y para que utiliza.
Utilizando el comando Branch
git push origin [Nombre de la Rama]
Como Publicar mi proyecto en Github
La práctica es mucho mejor que la teoría estos son los primeros pasos para empezar a familiarizarse con la consola de Git y trabajar en proyectos que se alojen en Github.
Pasos:
Situarse en la carpeta donde esta nuestro contenido con cd
Realizar un git init
Realizar un add ( git add . )
Realizando mi Primer commit
Al escribir el commit cuando lo utilizamos por primera vez nos pide configurar las credenciales
Configurando mis credenciales
git commit — m “Primeros pasos en HTML”
Utilizar un remote add origin para conectar nuestro repositorio local con el github la url tiene que ser exactamente igual al url que creamos en el github.
Realizamos un push
ide credenciales :
Poner nombre de usuario de github y clave de github
Volvemos a hacer el commit
Listo el Repositorio ha sido publicado en Github.
