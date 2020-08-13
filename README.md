# GuiaLabDPS
Desarrollo de Guías / Diseño y Programación de Software Multiplataforma /
Presenta: Daniel Benavides - BH152202

Descripción de los puntos:

1. Se creó este repositorio remoto para versionar el archivo primerversion.html según las indicaciones de la guía 1.
  - En el raíz de la rama "master" encontrará el archivo original primerversion.html de los primeros 3 puntos del análisis de resultados.
  - Comandos utilizados: git remote add origin https://github.com/dbenavides97/GuiaLabDPS.git, git status, git add *, git commit -m, git push -f origin master.

2. Se clonó el archivo primerversion.html dentro de la subcarpeta guia01, se pidió la colaboración de iacr-10 (Irvin Castro) y seguimos las indicaciones.
  - Se pudo observar que los cambios que realicé yo desaparecieron cuando mi colaborador hizo el push de los suyos en la misma rama.
  - Comandos utilizados: git pull origin master, git add *, git commit -m, git push -f origin master.
  
3. Se clonó el archivo primerversion.html dentro de la subcarpeta guia02 y se crearon las ramas: Desarrollo, Pruebas y Producción.
  - En cada rama se colocó un <*h1*><*/h1*> como identificador dentro guia02/primerversion.html para diferenciar que el archivo pertenece a "X" rama.
  - Por ejemplo: En la rama Desarrollo se colocó dentro de guia02/primerversion.html --> <*h1*>Rama Desarrollo<*/h1*> y así sucesivamente con el resto.
  - Comandos utilizados: git branch, git checkout, git push -f origin <branch>.
  
4. Se clonó el archivo primerversion.html dentro de la subcarpeta guia03 y se crearon las ramas: Des, Pru y Pro.
  - En la rama Pru se colocó dentro de guia03/primerversion.html --> <*h1*>Rama Desarrollo Pruebas<*/h1*>.
  - En la rama Des se deshicieron los cambios y para efectos de identificación se colocó dentro de guia03/primerversion.html --> <*h1*>Rama Des<*/h1*>.
  - En la rama Pro no se subió nada porque no estaba especificado en las indicaciones.
  - Comandos utilizados: git branch, git checkout, git push -f origin <branch>.
