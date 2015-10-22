**Ejercicios del [tema 1](http://jj.github.io/CC/documentos/temas/Desarrollo_basado_en_pruebas)**

##Ejercicio1

###Instalar alguno de los entornos virtuales de node.js y, con ellos, instalar la última versión existente, la versión minor más actual de la 0.12 y lo mismo para la 0.11 o alguna impar. Si no se usa habitualmente este lenguaje, hacer lo mismo con cualquier otro lenguaje de scripting. 

Para instalar nodeenv simplemente ejecutamos el comando `sudo easy_install nodeenv` 

Trabajaremos con python por lo que instalamos virtualenv con el comando  `sudo apt-get install python-virtualenv`

![Pantallazo mostrando la versión del enterno virtualenv una vez instalado](https://i.gyazo.com/b36d0a16c360e31c324da6b8dff0c06b.png)


##Ejercicio2

###Como ejercicio, algo ligeramente diferente: una web para calificar las empresas en las que hacen prácticas los alumnos. Las acciones serían crear empresa y listar calificaciones para cada empresa, crear calificación y añadirla (comprobando que la persona no la haya añadido ya), borrar calificación (si se arrepiente o te denuncia la empresa o algo) y hacer un ránking de empresas por calificación, por ejemplo. Crear un repositorio en GitHub para la librería y crear un pequeño programa que use algunas de sus funcionalidades. Si se quiere hacer con cualquier otra aplicación, también es válido.
###Se puede hacer un ejercicio equivalente, siempre que tenga operaciones similares: creación, listado, borrado, ciclo CRUD básico. El objetivo de este ejercicio es poner en práctica lo que viene a continuación, NO es un objetivo de la asignatura.


Optaré por la segunda opción, un ejercicio equivalente. Lo desarrollaremos en una [organización de github](https://github.com/ProyectCC), con cada miembro encargado de un submódulo. [Mi submódulo es éste](https://github.com/JCristobal/ProjectCC).



##Ejercicio3

###Ejecutar el programa en diferentes versiones del lenguaje. ¿Funciona en todas ellas?

Ejecuto con python y python3. Funciona correctamente para el primero, pero para la segunda no tiene la sintasis adecuada

![Pantallazo probando las diferentes versiones](https://i.gyazo.com/10d60cfb9eb7fb4d19dbaee3f87cbc8b.png)


##Ejercicio4

###Crear una descripción del módulo usando package.json. En caso de que se trate de otro lenguaje, usar el método correspondiente. 

Con python creamos el archivo requirement.txt, que lista las dependencias que necesitamos. Podemos verlas ejecutando `pip freeze`.

Para crear el archivo con dichas dependencias ejecutamos: `pip freeze >> requirements.txt`.


##Ejercicio5

Automatizar con grunt y docco (o algún otro sistema) la generación de documentación de la librería que se cree. Previamente, por supuesto, habrá que documentar tal librería.

##Ejercicio6

Para la aplicación que se está haciendo, escribir una serie de aserciones y probar que efectivamente no fallan. Añadir tests para una nueva funcionalidad, probar que falla y escribir el código para que no lo haga (vamos, lo que viene siendo TDD).

##Ejercicio7

Convertir los tests unitarios anteriores con assert a programas de test y ejecutarlos desde mocha, usando descripciones del test y del grupo de test de forma correcta. Si hasta ahora no has subido el código que has venido realizando a GitHub, es el momento de hacerlo, porque lo vamos a necesitar un poco más adelante. 


##Ejercicio8


1- Darse de alta. Muchos están conectados con GitHub por lo que puedes usar directamente el usuario ahí. A través de un proceso de autorización, acceder al contenido e incluso informar del resultado de los tests.

2- Activar el repositorio en el que se vaya a aplicar la integración continua. Travis permite hacerlo directamente desde tu configuración; en otros se dan de alta desde la web de GitHub.

3- Crear un fichero de configuración para que se ejecute la integración y añadirlo al repositorio.

(Haced los dos primeros pasos antes de pasar al tercero)









