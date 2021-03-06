# TUTORIAL
Este tutorial ha sido escrito en formato Markdown.

Enlace a la página [Tutorial](https://quinoescobar.github.io/styw_initialTasks)
Enlace a la página del autor [QuinoEscobar](https://quinoescobar.github.io)

En el presente tutorial se explica el proceso de instalación de Nodejs , Express, Pandoc and Kramdown, y también se muestra la creación del proyecto en la nube, Cloud9.

## Markdown

Markdown es un formato ligero de marcado con texto plano que facilita la conversión hacia otros formatos como HTML y muchos otros formatos  usando un traductor.

##  NodeJS

NodeJS es un driven framework de eventos asincronos, esta diseñado para construir apliaciones web escalables.

A continuación se muestran los pasos seguidos para su instalación:

1. Se accedió a la página de [NodeJS](https://nodejs.org/en/download/package-manager/) y se siguieron los pasos indicados:

![nodejs](images/snode1.PNG "nodejs")

2. Se comprobó la correcta instalación del NodeJS:

![nodejs2](images/s9.PNG "nodejs2")

3. Se comprobó la correcta instalación del npm:

![nodejs3](images/s8.PNG "nodejs3")



##  Express

Express es una  framework minimalista y flexible para NodeJS que provee un set de herramientas robustas para la web y para las aplicaciones móviles.

A continuación se muestran los pasos seguidos para su instalación:

1. Se instaló NodeJS

2. Se accedió a la página de [Express](http://expressjs.com/starter/installing.html) y se siguieron los pasos indicados:

![Express](images/s6.PNG "Express")

3. Se comprobó la corracta instalación :

![Express2](images/s66.PNG "Express2")


##  Traductores

Los traductores Markdown son aplicaciones que permiten convertir un formato en otro formato, en nuestro caso, el formato Markdown a formato HTML.

A continuación se muestran los pasos de instalción de Pandoc and Kramdown:

### Pandoc

1. Se accedió a la página de [Pandoc](http://pandoc.org/installing.html) y se siguieron los pasos indicados.

2. Se utilizó el comando como Super: apt-get install Pandoc

3. Se comprobó su correcta instalación:

![Pandoc](images/s7.PNG "Pandoc")

### Kramdown

1. Se accedió a la página de [Kramdown](http://kramdown.gettalong.org/installation.html) y se siguieron los pasos indicados:

![Kramdown](images/s12.PNG "Kramdown")

2. Se comprobó su correcta instalación:

![Kramdown2](images/s10.PNG "Kramdown2")

## Atom

Atom es un editor de texto realizado y publicado por Github, escrito en NodeJS.

Para su instalación se debe ir a la página de [Atom](https://atom.io/) y descargar el ejecutable, en mi caso uso máquinas virtuales para la realización de las prácticas de las asignaturas, es decir que utilizo Windows OS con máquinas virtuales sobre Linux OS por medio de VirtualBox y que por medio de una terminal en Windows controlo la máquina virtual.

Atom se ha instalado en Windows, para trabajar desde fuera de la máquina virtual de Linux.

Como se puede apreciar en la siguiente imagen.
![sywt](images/s13.PNG "sywt")


## Generación HTML

Para convertir de formato a HTML se usó Pandoc.

Pasos seguidos para la creación del fichero .html:

1. Se abrió una terminal

2. Se utilizó el comando Pandoc -s -o fichero.html ficheroaConvertir.md

![pandocHTML](images/s14.PNG "pHTML")

3. Comprobación página creada

![pandocHTML2](images/s15.PNG "pHTML2")
