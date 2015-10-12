#Ejercicio 2
=================
Como ejercicio, algo ligeramente diferente: una web para calificar las empresas en las que hacen prácticas los alumnos. Las acciones serían crear empresa y listar calificaciones para cada empresa, crear calificación y añadirla (comprobando que la persona no la haya añadido ya), borrar calificación (si se arrepiente o te denuncia la empresa o algo) y hacer un ránking de empresas por calificación, por ejemplo. Crear un repositorio en GitHub para la librería y crear un pequeño programa que use algunas de sus funcionalidades. Si se quiere hacer con cualquier otra aplicación, también es válido.
Se puede hacer un ejercicio equivalente, siempre que tenga operaciones similares: creación, listado, borrado, ciclo CRUD básico. El objetivo de este ejercicio es poner en práctica lo que viene a continuación, NO es un objetivo de la asignatura.


#Solucion
================
El repositorio para el ejercicio es [RankingEmpresas](https://github.com/fnavarrogonzalez/RankingEmpresas).

Para ello vamos a utilizar un virtualenv con python 2.7 y django. 
La instalación de django es trivial con el uso de pip. 
![PythonDjangoInstall](https://github.com/fnavarrogonzalez/clases-CC-2015-16/blob/master/ejercicios/FranciscoNavarroGonzalez/1 Desarrollo Basado En Pruebas/imagenes/2djangoinstall.png)
Además utilizamos django-admin para crear la primera aplicación.
Para ello vamos a poner un proyecto de ejemplo "Ejercicio2" con una aplicación "Rankingempresas". Ya que el análogo a Django de bibliteca sería una aplicación. 
