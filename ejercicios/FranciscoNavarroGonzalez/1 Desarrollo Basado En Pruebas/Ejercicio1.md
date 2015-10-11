Ejercicio 1
==============================

1. Instalar alguno de los entornos virtuales de node.js y, con ellos, instalar la última versión existente, la versión minor más actual de la 0.12 y lo mismo para la 0.11 o alguna impar. 
Si no se usa habitualmente este lenguaje, hacer lo mismo con cualquier otro lenguaje de scripting.

Solucion 
==============================
1.Instalacion de las herramientas para la creación de entornos virtuales

1.1 NodeJS

Para NodeJS existen varios entornos virtuales la mayoría por no decir todos son software libre. 
Pero como siempre hay una solución que se extiende sobre el resto, en este caso las soluciones más populares entre la comunidad son [Nodeenv](https://github.com/ekalinin/nodeenv) y [Nave](https://github.com/isaacs/nave)

Lo bueno de Nodeenv es que te permite integrarlo con virtualenv y python, de hecho, su instalación se realiza a través de python y sus herramientas de gestión de dependencias easy_install/pip.

1.2 Python

Uno de los lenguajes que más he utilizado ha sido python, por lo tanto para este ejercicio también crearé un entorno virtual para este lenguaje. 
Para instalar virtualenv se puede hacer desde los repositorios de la mayoría de las distribuciones de linux. 
En concreto para las últimas versiones de Fedora (>21)  
Sudo dnf install python-virtualenv (para la version 2.7)
sudo dnf install python3-virtualenv (para la version 3)
 
