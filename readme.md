# Comando de Git
Comando para eliminar folders que ya estan en el repositorio de git
y se agregaron al gitignore y se desean eliminar cuando se haga un push a la 
rama principal o a la rama de develop

```
git rm -r --cached some-directory
git commit -m 'Remove the now ignored directory "some-directory"'
git push origin master
```