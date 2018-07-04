# Java 8 Fundamentals

Este es el proyecto base que utilizaremos para almacenar sus avances individuales.

Por favor sigan los siguientes pasos que se les indican para poder utilizar este repositorio:

- Crear cuenta de [github](https://github.com/) en la version publica

- Enviar solicitud de ingreso al siguiente correo: **alfonso.valdezaltamirano@gmail.com** indicando el nombre de usuario de github

- Esperar solicitud de colaboracion y aceptar

- Vamos a clonar el codigo del proyecto [java8fundamentals](https://github.com/breakponchito/java8fundamentals) en nuestro ambiente local

> Nota: Si no tienes git en tu maquina primero debes descargarlo de la siguiente pagina [download git](https://git-scm.com/downloads ) y seguir las instrucciones para su instalación

- Ejecuta el siguiente comando en tu equipo en un folder de tu conocimiento para que sea tu zona de trabajo

`git clone https://github.com/breakponchito/java8fundamentals.git`

- Una vez clonado el proyecto entrar a la carpeta src y localizar la carpeta con el nombre de usuario que corresponda

> Nota: la relacion de nombres de carpeta y la correspondencia de cada uno de los alumnos se localiza en el siguiente [documento](https://docs.google.com/spreadsheets/d/1pe63Cq3i0WDK9NfHJ1_-8kYctnAbMDACZ1HdoxQrewc/edit?usp=sharing)

- Dentro de la carpeta agregar el codigo correspondiente a los ejercicios y las practicas

- Un ejemplo de estructura valida de carpetas es la siguiente:

1. src
	- main
	   - java
			- avaldez
				- practices
					- practice_06_objectsclasses_2
						- soccer
						   
						   Goal.java
						  
						   Game.java
						  
						   League.java
						   
						   Player.java
						   
						   Team.java
				- exercises
					- ex03_1_exercise
						
						SayHello.java
					
> Nota: En el caso de las practicas la carpeta base nombrarla con base en el nombre de proyecto NetBeans que crearon en su equipo, 
> utilizando el siguiente formato **practice_numeromodulo_nombremodulo_numeropractica** todo en minusculas y utiizando guiones bajos. Entonces un ejemplo seria como
> sigue **practice_06_objectsclasses_2** 
> Agregar los paquetes de cada proyecto netbeans en la carpeta correspondiente a la practica y refactorizar los paquetes. Revisar el codigo de ejemplo en la carpeta **avaldez**

- Para consultar los cambios realizado utilizar el comando `git log` en caso de tener dudas consultar la siguiente [liga](https://git-scm.com/docs/git-log)

- crear un branch con el siguiente comando `git checkout -b nameofbranch` , si tienes dudas de como crear un branch consulta la siguiente [liga](https://git-scm.com/docs/git-checkout)

- Para indicar que cambios se van a promover para subir utilizar el comando `git add nameoffile` , si tienes dudas de como utilizar el comando consulta la siguiente [liga](https://git-scm.com/docs/git-add)

- Cuando todos los cambios esten en stage entonces es momento de crear un commit con el siguiente comando `git commit -m "message"` , este comando utiliza la opción -m para que podamos agregar un mensaje descriptivo del cambio que queremos publicar

- Ahora vamos a enviar los cambios al repositorio remoto con el comando `git push --set-upstream origin branchname` , en donde branchname es el nombre del branch que genere previamente y en donde estan mis cambios
	 
- Cuando tengamos este avance ahora vamos a generar un pull request desde la interfaz web de github, por lo que debemos logearnos en nuestra cuenta y entrar al repositorio del proyecto

- Dentor del repositorio del proyecto vamos a buscar el boton **Compare & pull request** le damos click y observamos la siguiente interfaz

- Agregamos un titulo al pull request y agregamos un comentario en el cuerpo del pull request

- En la sección de **Reviewers** seleccionar mi nombre de usuario de github **breakponchito** , yo sere el unico que aprobara sus cambios

- Cuando tengan esto ya solo falta dar click en el boton **Create Pull Request** dan click y esperan mi aprobacion y merge del branch para que el codigo que agregaron se propage al proyecto base master

- Ahora lo que tienes que hacer en tu local es moverte al branch master con el comando `git checkout master`

- Y borras el branch que utilizaste con el comando `git branch -d localbranchname` , donde localbranchname es el nombre del branch que crearon

- Dudas o comentarios enviarlos a mi correo: **alfonso.valdezaltamirano@gmail.com**





