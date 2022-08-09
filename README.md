# git-prueba
Proyecto creado para uso de git

es un proyecto de prueba con git
	el estado que se encuentran tus archivos (si estan en stayin area o en la nube)

git commit
	es el comentario que haces para identificar el archivos modificado
	((( hacemos el comentario, esc, :wq, para guardar )))
	
	git log
	te arroja los commit que hayas elaborado en el transcurso del proyecto

	git checkout --   
	para revertir los cambios de los archivos	
	(ejemplo) git checkout -- index.html

	git diff
	para ver las diferencias fechas en los archivos
	example  git diff index.html

	.gitignore
	en el proyecto elaboramos un archivo
	y ahi pondremos los archivos que deseamos que ignore git
	
	git commit -m "(mensaje)" mas facil de guardar sin ":wq"

git branch
	Se utiliza para visualizar en que proyecto te enceuntras y crear un extra
	para alguna modificacion, una version distinta del proyecto, sin necesidad de 
	regresarse por completo a un archivo nativo (es como clonar tu archivo)

	example (cambio de branch)	git checkout login


git remote add origin
	es para colocar la ubicaicon de donde colocas tu repositorio, cual es el origien 
	o donde vamos almacenar el codigo (su direccion)

		example: git remote add origin https://github.com/javierc89/git-prueba.git
	
git push
	Subes el documento
		example: git push -u origin main

git clone
	descargar o clonas el proyecto q subiste a github
	example: git clone https://github.com/javierc89/git-prueba.git

git pull
	traes los cambios
