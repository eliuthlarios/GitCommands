Comandos de git

• git --version  <<Ver la version de git>>
• git init //Crear un repositorio local
• git status
• git add  .  //Subir cambios de manera general
• git add <<specific file>> //Subir cambios de manera puntual
• git commit -m "messaje" //Subir un cambio
• git config --global user.mail "@gmail" 
• git config --global user.name "eliuthLarios"
• git config --unset user.mail/user.name
• git config --get user.mail/unser.mail
• git config --global --unset user.name
• git config --global --unset user.email

• ctrl + L  //Limpiar terminal
•  git log //Ver las versiones "commits" confirmadas
•  git checkout <<Iniciales del Hash>> //podes viajar entre viejos commits
• git reset <<Iniciales del hash>>  //Se quitara el commit pero los cambios quedaran en staged area    
• git reset --hard  <<Hash>>  //Eliminar el commit a los cambios que se han hecho despues de el.
• git log --one line  //Mostrar los commits en una sola linea
• rm <<nombre>> //Borrar algo
• git restore <<nombre>> //Recuperar algo borrado
• Ls -a  //Mostrar archivos ocultos
• cd  <<nombre>>  //Moverse entre carpeta
• git checkout -b  <<nombre de rama>> 
• git switch // Cambiar de rama
• git push -u origin master
• git push -u origin <<nombre de la rama>> // Subir una rama al repo r.
• git log --oneline
• 

Github

• git remote add origin <<enlace>>//usar opcion ssh porque https funciona por toquens, pero con ssh hay que crear claves
• git remote -v //
• ssh-keygen -t ed25519 -c "email" // elegir directorio (dejar por defecto) y poner una contraseña
nota; Para crear una clave ssh añadimos el comando anterior  en un nuevo bash y seguimos los pasos. Se nos guardara una  2 claves, una publica y una privada para obtener  las claves criptograficas usamos los siguiente comandos
• cd
• cd .ssh
• ls
nota; Luego pegar la clave criptografiada  en SSH AND GPG keys usando el siguiente comando
• cat <<ide_ed234324>>  //Un ejemplo del codigo
nota: Luego en teoria  de haber creado la clave en la cuenta de github le damos "yes"  al colocar el siguiente comando nos pedira la contraseña.
• git push -u/git push --set-upstream origin masternota; En dado caso se repite todo lo anterior buscar ssh agent en la parte de abajo de la documentacion para no tener que agregar la contraseña tantas veces
 

delete later