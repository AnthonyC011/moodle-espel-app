# moodle-espe-app
Ionic hybrid app who notifies if there are pending activities in your own moodle 2.9 account.

##1. Instalar el proyecto remoto por primera vez
-----
1.1. Forkear el proyecto **huasipango/moodle-espel-app** en su cuenta de 
github.
![Ubicación del botón 
fork](https://github-images.s3.amazonaws.com/help/bootcamp/Bootcamp-Fork.png)

1.2. Una vez hecho el fork, clonar el repositorio que se acaba de crear 
en el directorio local que se prefiera.
![Procedimiento para clonar un 
repo](https://help.github.com/assets/images/help/repository/https-url-clone.png)

1.3. Abrimos la consola de comandos de git para configurar el 
repositorio remoto al que hemos hecho fork para que git local lo sepa. 
Usaremos el siguiente comando:

*git remote add origin-root 
https://github.com/huasipango/moodle-espel-app.git*

Revisar esta configuración con:

*git remote -v*

##2. Antes de programar
------
**Siempre** necesitamos crear ramas(branches) antes de empezar a 
codificar.
Los comando git necesarios son:
2.1. git branch nueva-rama
2.2. git checkout nueva-rama

##3. Guardar avances (consola de comandos)
-------
3.1. Actualizar repo local: *git fetch origin-root* 
3.2. Añadir todos los cambios: *git add -A*
3.3. Redactar un detalle del avance: *git commit -m 'mensaje de 
explicación'*
3.4. Publicar los cambios en el repo remoto: *git push*

##4. Enviar avance a rama base (Pull Request)
------
Ir al repositorio remoto forkeado que a recibido nuestros cambios, ejm: 
*https://github.com/huasipango/moodle-espel-app.git*

Dirigirse al repo forkeado y crear Pull Request
![Haciendo pull 
request](https://assets.digitalocean.com/articles/eng_python/PullRequest/PRButton.png)

