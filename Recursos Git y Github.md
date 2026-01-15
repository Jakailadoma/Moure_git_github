Para los comandos mas usados de git y github:
https://training.github.com/downloads/es_ES/github-git-cheat-sheet/

documentacion de github:
https://docs.github.com/es

Configuracion de Github por primera vez:

Para establecer conexion, ejecutamos git remote add origin git@github.com:<usuario_github>/<nombre_repositorio>.git ddesde la raiz de nuestro proyecto local. Este comando anhade una referencia remota llamada origin asociada a nuestro usuario ede Github y al repositorio que hemos creado.

Una vez que hemos establecido la conexio, podemos subir nuestro codigo local al repositorio remoto en Github utilizando el comando git push. Al hacerlo, Git nos pedira mas informacion sobre a que repositorio remoto y a que rama queremos hacer dicho push.

Es importante tener en cuenta que la primera vez que subimos nuestro codigo al repositorio remoto, debemos utilizar el comando completo git push -u origin <rama_principal> establece una configuracion predeterminada para el comando git push. En particular, establece que el repositorio remoto origin y el nombre de la rama destino predeterminada para futuros comandos push.

Es importante recalcar que ele parametro -u solo se utiliza la primera vez que subimos nuestro codigo al repositorio remoto en Github.

Una vez que hemos subido nuestro codigo al repositorio remoto, cualquier persona con acceso a este, y con los permisos correspondientes, podra descargar el codigo y comenzar a colaborar en el proyecto utilizando el flujo de trabajo de Git y Github.

Como conclusion:
Subir nuestro codigo local al repositorio remoto de github es un proceso esencial para trabajar con Git y Github. Con el comando remote y push de git, podemos establecer la conexion entre nuestro repositorio local y el repositrio remoto en Github, lo que nos permitira trabajar de manera colaborativa y en linea.