# Curso_profesional_de_javascript



## Tipos de Scope en JavaScript

El Scope o ámbito es lo que define el tiempo de vida de una variable, en que partes de nuestro código pueden ser usadas.

# Global Scope

Variables disponibles de forma global se usa la palabra var, son accesibles por todos los scripts que se cargan en la página. Aquí hay mucho riesgo de sobreescritura.

# Function Scope

Variables declaradas dentro de una función sólo visibles dentro de ella misma (incluyendo los argumentos que se pasan a la función).

# Block Scope

Variables definidas dentro de un bloque, por ejemplo variables declaradas dentro un loop while o for. Se usa let y const para declarar este tipo de variables.


# Module Scope

Cuando se denota un script de tipo module con el atributo type="module las variables son limitadas al archivo en el que están declaradas.

## THIS
# Global Scope o Function Scope
Cuando llamamos a this en el Global Scope o Function Scope, se hace referencia al objeto window. A excepción de cuando estamos en strict mode que nos regresará undefined.
# Objeto
Cuando llamamos a this desde una función que está contenida en un objeto, this se hace referencia a ese objeto.

# “clase”
Cuando llamamos a this desde una “clase”, se hace referencia a la instancia generada por el constructor.


# Patrones de diseño
 
➡️Creacionales
Proveen diferentes mecanismos para crear objetos.

    Abstract Factory
    Builder
    Factory Method
    Prototype
    Singleton
     
    ➡️Estructurales
    Describen formas de componer objetos para formar nuevas estructuras flexibles y eficientes.
    Adapter
    Bridge
    Composite
    Decorator
    Facade
    Flyweight
    Proxy
     
    ➡️Comportamiento
    Gestionan algoritmos y responsabilidades entre objetos.
    Chain of Responsibility
    Command
    Interpreter
    Iterator
    Mediator
    Memento
    Observer
    State
    Strategy
    Template Method
    Visitor


