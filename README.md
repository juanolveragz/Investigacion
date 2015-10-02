# Investigacion






	

















Trabajo de Investigación


Lenguajes y Paradigmas de Programación

Juan Carlos Olvera González 
151408











Variable Estatica

En informática una variable estática es una variable que ha sido ubicada estáticamente y cuyo tiempo de vida se extiende durante toda la ejecución del programa. Normalmente una variable estática tiene un ámbito más amplio que otras variables. Los valores de variables estáticas se pueden establecer una vez (durante el tiempo de ejecución) o se pueden cambiar en múltiples ocasiones durante la ejecución del programa. La terminología "variable estática" se basa en C y C++, pero también se usa en muchos lenguajes de programación derivados. En lenguajes de diferente origen el mismo concepto puede denominarse "variable global".

Ciclo de Vida de las Variables

Variables de instancia (u objeto): 
•	Estas son creadas cuando se crea el objeto que las contiene.
•	Se inicializan por defecto en caso de que estas no se inicializen de modo explicito. 
•	Son destruidas cuando el recolector de basura no encuentra referencias activas para el objeto.
Variables estaticas (o de clase):
•	Se crean cuando la variable es utilizada por primera vez.
•	Se inicializan por defecto en caso de que estas no se inicializen de modo explicito.
•	Suelen existir para el resto del programa (salvo que no esté cargado)
Variables locales (o de bloque):
•	Son creadas en la estancia en la que estan definidas.
•	No se inicializan por defecto tienen datos imprevisibles.
•	Se destruyen al salir del bloque.








Memoria Dinamica (lenguaje C)

Es memoria que se reserva en tiempo de ejecución. Su principal ventaja frente a la estática, es que su tamaño puede variar durante la ejecución del programa. (En C, el programador es encargado de liberar esta memoria cuando no la utilice más). El uso de memoria dinámica es necesario cuando a priori no conocemos el número de datos/elementos a tratar.

Clases

En informática, una clase es una plantilla para la creación de objetos de datos según un modelo predefinido. Las clases se utilizan para representar entidades o conceptos, como los sustantivos en el lenguaje. Cada clase es un modelo que define un conjunto de variables el estado, y métodos apropiados para operar con dichos datos el comportamiento. Cada objeto creado a partir de la clase se denomina instancia de la clase.

Objeto 

Un objeto es una unidad dentro de un programa de computadora que consta de un estado y de un comportamiento, que a su vez constan respectivamente de datos almacenados y de tareas realizables durante el tiempo de ejecución. Un objeto puede ser creado instanciando una clase, como ocurre en la programación orientada a objetos, o mediante escritura directa de código y la replicación otros objetos, como ocurre en la programación basada en prototipos.

Instanciación

Se refiere a una realización específica de una clase o prototipo determinados.
En general, cuando se ejecuta un programa en un computador, se dice que éste se instancia. En lenguajes que crean objetos a partir de clases, un objeto es una instancia de una clase. Esto es, un miembro de una clase que tiene atributos en lugar de variables. 



Herencia 
La herencia es, después de la agregación o composición, el mecanismo más utilizado para alcanzar algunos de los objetivos más preciados en el desarrollo de software como lo son la reutilización y la extensibilidad. A través de ella los diseñadores pueden crear nuevas clases partiendo de una clase o de una jerarquía de clases preexistente evitando con ello el rediseño, la modificación y verificación de la parte ya implementada. La herencia facilita la creación de objetos a partir de otros ya existentes e implica que una subclase obtiene todo el comportamiento (métodos) y eventualmente los atributos (variables) de su superclase.

Sobrecarga 

Sobrecarga es la capacidad de un lenguaje de programación, que permite nombrar con el mismo identificador diferentes variables u operaciones.
En programación orientada a objetos la sobrecarga se refiere a la posibilidad de tener dos o más funciones con el mismo nombre pero funcionalidad diferente. Es decir, dos o más funciones con el mismo nombre realizan acciones diferentes. El compilador usará una u otra dependiendo de los parámetros usados. A esto se llama también sobrecarga de funciones.

Shadowing

Se llama shadowing al hecho de que en una clase una variable miembro y una variable local definida en un método miembro, se llamen igual.
Básicamente, dado un objeto, no se llama la definición dada por su tipo intrínseco, sino por el aparente. En otras palabras, no hay polimorfismo.
