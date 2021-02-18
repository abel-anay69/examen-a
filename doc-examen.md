# EXAMEN-A / ABEL ANAYA.

#### 2. Inicializa el repositorio.

*git init*

#### 3. Crea un archivo llamado index.html con el contenido.

*Vamos al VisualStudio y creamos el archivo y lo guardamos en la carpeta "axamen-a".*

#### 4. Crea una carpeta llamada unidades y dentro de esta carpeta dos ficheros llamados.

*Nos movemos hasta la carpeta unidades con un cd y utilizamos los comandos respectivamente:*

*git echo "">unidad1.txt*

*git echo "">unidades2.txt*

#### 5. Pasa los ficheros y directorios a preparado.

*git add --all*

#### 6. Confirma los ficheros con un commit “Index”.

*git commit -m "Index"*

#### 7. Modifica el texto del ultimo commit poniendo "Index y unidades 1 y 2".

*git commit --ammed -m "Index y unidades 1 y 2"*

#### 8. Modifica el fichero unidad2.txt eliminando todo su contenido.

*Entramos dentro del archivo y borramos su contenido.*

#### 9. Pasa a preparado de nuevo el fichero unidad2.txt.

*volvemos a utilizar: git add --all*

#### 10. Mira el estado del proyecto.

*git status*

#### 11. Realiza otra confirmación con comentario "Eliminado texto de unidad 2".

*git commit -m "Eliminado texto de unidad 2"*

#### 12. Visualiza el log de todo el proyectos.

*git log*

*o*

*git log --oneline*

#### 13. Vuelve atrás al commit inicial de Index y unidades 1 y 2.

*Con el log de antes conseguimos el "código" del commit.*

*git checkout 8be38a1*

#### 14. Vuelve al estado final del proyecto (antes de la vuelta atrás).

*git checkout -*

#### 15. Crea un repositorio público en tu GITHUB y haz un push de todo el proyecto.

*Creamos el repositorio público en github*

*git remote add origin https://github.com/abel-anay69/examen-a.git*

*git push -u origin master*


