
La necesidad de tener una copia del repositorio es que cada cambio que se realice en este se "descargara" de forma automatica al repositorio local.

Para clonar el repositorio FSB, primero se creó un directorio nuevo con el comando mkdir <DirectoryName>, luego se inicio el repositorio de Git con el comando git init, luego con el comando git clone <HTTPS> se clono el repositorio de GitHub, se utilizo el comando git status para ver cuales eran los cambios correspondientes, luego con el comando git add se los "concidero" y por ultimo con el comando git commit con el flag -m para poner un comentario referente al cambio en un solo paso se agrego el cambio. Para pasar el repositorio a GitHub se creo uno y con el comando git git remote add origin <HTTPScorrespondiente al repositorio creado> se enviaron los archivos del repositorio inicializado pero para que sean visibles se utilizo el comando git push -u origin main. (Muy mal formulado ...)


Un archivo es una unidad de almacenamiento provista por el sistema operativo. Esta unidad de almacenamiento esta compuesta por una secuencia de bits definidos por el usuario. Los archivos se clasifican segun como estan estructurados, es decir, como se utilizan los bits para codificar informacion en un medio digital. Las extnciones estan relacionadas con el tipo de archivo y estas  permiten al usuario diferenciarlos de otros, y al sistema operativo que programa puede ejecutarlos, 


//La diferencia entre *.txt, *.md, *.doc es, los archivos con extencion txt no pueden tener un formato, es decir,plain text solo puede conter text, no pueden tener palabras en negrita, etc. por otro lado los terminados en md se les puede asignar un formato a travez de markdowns ('*'),..., y por ultimo los terminados en .doc nos permiten guardar imagenes, texto, informacion //de todo tipo. (Ampliar, releer y reescribir ...)  
Los archivos de text (*.txt*) 


**(Releer ... Medio Confuso...)**
Para escribir el codigo fuente del programa nombrado "examlpe.c" se utilizó el editor de texto vim. Para que la ejecucion de este programa sea posible se debe compilar para ello se implementó el comando gcc con el flag -o que permite renombrar el archivo ejecutable (gcc example.c -o example), por ultimo para ejecutarlo se implemento el siguiente path ./example. 
