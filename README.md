# -Application-Web-Design

ACTIVIDAD 1

nombre: GUILLERMO EMILIANO LANDA CERPA
matrícula: 02969076
carrera: IDS
semestre:SEXTO SEMESTRE

los datos de tu asignatura:

nombre de la asignatura: DISEÑO DE APLICACIONES WEB
profesor que la imparte: Erik Ezequiel Carrillo Moo
texto describiendo para qué sirve Markdown: markdown es un lenguaje que tiene la finalidad de permitir crear contenido de una manera sencilla de escribir, y que en todo momento mantenga un diseño legible

TAREA 1

-Seccion 1

Agregue una sección con las opciones de etiquetado que ofrece Markdown.

-markdown ofrece sintaxis de fiefrentes tipos:

primero esta el etiquetado: 

y se usa para los encabezados de las paginas y se remarcan con la siguiente simbologia 
(= = =) setext  
(-----) atx

y para el tamaño de los encabezados existen 6 tipos de tamaños:

esta el # con un solo gato, que significa que el tipo de letra sera para titulo.
y esta el ###### que es para los subtitulos mas pequeños.
este simbolo solo se podra usar hasta seis veces en un texto de titulo.

luego estan las citas en bloque que se utilizan para tener comillas en bloque como en los correos electronicos, aqui un ejemplo:

> este es una cita en tipo de bloque de correo electronico.

y estos mismos bloques se pueden anidar usando un doble simbolo de mayor que, aqui el ejemplo:

>> este es una cita anidada.

tambien existen las listas ordenadas con numeracion y con viñetas, aqui algunos ejemplos:

*hola este es un ejemplo.
+hola este es un ejemplo.
-hola este es un ejemplo.
1.hola este es un ejemplo.

La otra seccion, es la seccion de code blocks, donde se puede escribir codigo del leguaje HTML.

Seccion 2

Agregue otra sección donde enumerará los comandos utilizados en git para hacer lo siguiente:

Comprobar el estado de un repositorio local.

para comprobar el estado de un repositorio local se usara:

git status -s

Agregue archivos individuales o globalmente.

para agregar archivos individuales o globales se usara:

git add .
git commit -m "texto cambio tarea 1"
git push


Agregar comentarios a la confirmación.

para agregar comentarios a la confirmacion se usara:

git commit -m "comentario de confirmacion"

Cargue sus cambios en el repositorio remoto.

para cargar los cambios en el repositorio es:

git add .
git commit -m "cambios"
git push

Cree, explore y elimine sucursales.

para crear y explorar sucursales se hace de la siguiente forma:

para crear:

< p >sucursal benito juarez< / p >

git add .
git commit -m "creando primera sucursal"

para explorar:

git log --oneline

para eliminar sucursales:

git reset -- hard y aqui iria el numero del que se quiera eliminar.


Revertir un repositorio a una confirmación específica.

para revertir un repositorio se haria de la siguiente manera:

git reset -- hard y aqui iria el numero de lo utlimo agregado.
