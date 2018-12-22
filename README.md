# prueba

comandos basicos para el uso de git
git config --global user.name "clark kent"
git config --global user.mail "super@kripton.sup"

git config --global core.editor "vim"

git config --list

git add <fileName>

git --status

git log --all --decorate --graph --oneline

#Configurando las llaves ssh

ssh-keygen -t rsa -C "super@kripton.sup"

se puede elegir la ruta que uno desee para guardar las llaves
la llave de paso se puede dejar vacia

Se copia el contenido de la llave publica (ojo la publica no la privada), y se sube a github en settings

#Visualizar las conexiones remotas (en realidad revisar a donde apunta nuestro repositorio)
git remote -v

#Eliminar una de las "conexiones remotas"
git remote remove <nombre-de-repositorio>

#Agregar una "conexión" en este caso la dirección puede ser por ssh o por https
git remote add <nombre-de-repositorio>

#Crear un nuevo repositorio
Se crean los archivos (codigos, documentación, etc...)

git init

git add <archivos>

git commit -m "mensaje del commit"

git remote add origin https://github.com/la_ruta_del_repositorio.git

git push -u origin master




