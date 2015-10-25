Ejercicio 1
===========

<p>___Instalar alguno de los entornos virtuales de node.js y, con ellos, instalar la última versión existente,
la versión minor más actual de la 0.12 y lo mismo para la 0.11 o alguna impar.
Si no se usa habitualmente este lenguaje, hacer lo mismo con cualquier otro lenguaje de scripting.___</p>

<p>Se va a usar Python para este ejercicio, y se instala con brew (Todas las instrucciones serán para equipos con sistema operativo OS X).
Pero primero se necesita instalar Hombrew para poder instalar Python:

<br>
```
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
<br>
<br>
Después de la instalación se necesita insertar el directorio Homebrew al principio de la variable de entorno <b>PATH</b>.
Se hace añadiendo la siguiente linea al final del archivo <b>~/.profile</b>
<br>
```
export PATH=/usr/local/bin:/usr/local/sbin:$PATH
```
<br>
<br>
Ahora, se procede a instalar Python con:
<br>
```
$ brew install python
```
<br><br>
Una vez tenemos nuestro lenguaje script installado, procedemos a instalar el entorno virtual. En este caso es <b>virtualenv</b>.
<br>
```
$ pip install virtualenv
```
<br><br>
La instalación del entorno virtual se completa con este último comando.

</p>
