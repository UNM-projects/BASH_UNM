Este script permite subir, de una forma pseudo-automática, archivos preparados por Git
a un repositorio remoto en GitHub. Decimos "psuedo" porque solamente hay que ingresar
algunas especificaciones a la hora de ejecutar el script.

Nos paramos en el directorio donde hayamos alojado 'git_script.sh' y ejecutamos:

		./git_script.sh

Aclaración: Para poder realizar el anterior paso, el archivo "git_script.sh" debe tener
permisos de ejecución, eso lo hacemos con el siguiente comando parados en el directorio
donde se encuentra dicho archivo:

        chmod 666 git_script.sh

Lo primero que vamos a ingresar es la ruta donde se encuentran los archivos que querramos
subir a GitHub, como en el siguiente ejemplo:

	(Linux)		/home/lucas/Repositorios/GitHub/LPC1769_UNM

	(Windows) 	C:Documentos\Repositorios\GitHub\LPC1769_UNM

Aclaración: Es muy importante ingresar bien la ruta, verificar antes de dar "Enter"

Lo próximo es ingresar la 'url' del repositorio donde vayamos a alojar nuestros archivos.
La forma más fácil es ir a la página de GitHub donde se encuentre el repositorio remoto,
copiar la 'url' y pegarla en la línea de comandos (Para evitar errores de tipeo).

Antes de subir los archivos, nos va a pedir Usuario y Contraseña de nuestra cuenta en
GitHub (Esto es algo propio de los comandos de Git, no del script creado).

Esto es todo, al momento de ejecutarse el script arrojará por el stdout (Pantalla) algunos
mensajes programados dentro de git_script.sh, dichos mensajes fueron puestos en mayúsculas
para diferenciarlos de los mensajes de Git, y son una señal de que la carga se está 
realizando con éxito. Si todo sale bien el último mensaje de pantalla debería de ser:

"CARGA TERMINADA"


