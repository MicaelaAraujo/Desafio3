# Desafio3
1) Será un trabajo muy simple de hacer pero debes
hacerlo ya y no tienes tiempo de completar el
commit ¿Cómo podrías pausar el trabajo en el
commit actual para dedicarte a trabajar en
master?

podria realizar en la rama que estoy trabajando git add .
git commit -m "mensaje del commit" y antes de hacer el push, me cambio a la otra rama master con 
git checkout master.

¿Cómo podrías subir los cambios a producción si
es la rama master la que se usa para
producción?

estoy en la rama front-react 
git checkout master   cambio a la rama master
git pull origin master obtengo la ultima version
git merge front-react 
git push

