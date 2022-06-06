### prototype 
Los prototype son un mecanismo mediante el cual los obejtos en JS heredean caracteristicas entre si.
Js esta basado en prototipos, es decir los objetos pueden tener objetos prototipos que actua como plantilla del objeto y le da metodos y propiedades.
Los objetos prototipos pueden tener otro objeto prototipo del cual heredar propiedades.
Los metodos y propiedades son definidos en la propiedad prototype que reside en la funcion constructora del objeto y no en su instancia.

### Constructor 
Es un metodo especial de las clases para crear e inicializar un objeto de esa clase, este te permite tener una base de inicio que debe ser construida antes de que algun otro metodo deba ser llamado en una instancia. Si no se genera el constructor se tendra un constructor vacio en la clase. Solo puede haber un metodo con el nombre constructor si hay mas la consola mostrara un error.