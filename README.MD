### Empezando:
Para bajar este proyecto a tu computadora:
1. INSTALL GIT: https://git-scm.com/downloads
1. Ve a tu directorio principal de proyecto, abrir el powershell y colocar la siguiente linea de comando:<br />
´git clone https://github.com/your:username/your_project.git´

## Usando git en ALTIUM:
1. **SAVE:** Toda vez que se haga algún cambio, guardar el archivo o proyecto.
1. **COMMIT:** Click derecho en el acrhivo o proyecto, despues Control->Commit.
Añade una nota diciendo los cambios que haz realizado o han realizado.
1. **PUSH:** Cuando quieras actualizar todos los cambios a github, click derecho 
en el archivo/proyecto -> Version control.
1. **Check:** Controlar en github que se haya subido correctamente nuestra actualización.

## Usando git desde la linea de comando (manualmente):
1. **OPEN CMD:** Toda vez que haya un algun cambio, ve hacia tu directorio de proyecto 
abre una linea de comando y run:<br />
1.´git status´ # Esto va a mostrarte que cambios se han hecho <br />.
1.´git add [path/file]´ # Esto va a preparar un archivo especifico para realizar un 
commit, para añadir todos los archivos de una sola vez, usar add .<br />
1.´git commit -a "CHANGE DESCRIPTION"´ # Esto va a realizar un commit del cambio con 
una descripcion especifica <br />
1.´git push origian / git push origin master´ # Esto va a copiar tus cambios en Github <br />

### Bajar la ultima version 
Si usted desaria bajar los ultimos cambios desde Github, entonces <br />
1.´git pull origin master´ # Esto va a bajar la ultima version de github a tu 
computadora local <br />  
