#### Iván Santiago Valencia Hernández - 2220231056
#### Jesus Maria Vargas Logreira - 2220231023
#### Felipe Cordoba Fernández - 2220231083
------------
## Pruebas de Software
Las pruebas de software son un conjunto de actividades y procesos realizados durante el desarrollo y mantenimiento del software para evaluar su calidad, identificar defectos y garantizar el cumplimiento de los requisitos especificados. Estas pruebas se realizan para encontrar errores, verificar el correcto funcionamiento del software y comprobar que cumple con los deseos y necesidades de los usuarios. Las pruebas de software pueden cubrir varios aspectos de un sistema, incluida su funcionalidad, rendimiento, seguridad, facilidad de uso y compatibilidad. Las pruebas de software son una parte esencial del ciclo de vida del desarrollo de software que ayuda a garantizar la calidad y la confiabilidad del producto final.
### Principales tipos de pruebas de software
#### Pruebas unitarias o unit testing
Verifican que cada una de las piezas o unidades más pequeñas del software en el que funciona funciona correctamente.
Para hacer esto, es necesario resaltar estas unidades que pueden ser fragmentos del código para verificar su comportamiento. Al trabajar con unidades tan pequeñas, puede verificar el proyecto en partes, sin la necesidad de completarse.
#### Pruebas de integración
El propósito de estas pruebas es asegurarse de que varios componentes funcionen bien juntos. A veces sucede que el módulo que funcionó perfectamente de forma aislada, después de que se integra con el resto, causa algún tipo de rechazo en el sistema, por lo que es necesario controlar esta integración para obtener los mejores resultados.
#### Pruebas funcionales
Se consideran pruebas de caja negra porque se confirma si todo funciona tal y como está establecido en el documento Software Requirement Specification (SRS).
#### Pruebas de aceptación
Antes de comenzar a trabajar, el equipo responsable del proyecto debe determinar cuáles son los criterios de aceptación.
Durante las unidades y las pruebas de integración, se realizarán pruebas de aceptación para confirmar que todo el sistema funciona, como se esperaba.
#### Pruebas de rendimiento
Se trata de verificar la respuesta del software a varias cargas de trabajo y en condiciones reales. Sirven para determinar problemas como la estabilidad o la velocidad de la aplicación de software, y están directamente relacionados con la experiencia del usuario y el coeficiente de conversión.
#### Pruebas de estrés
Antes de completar el proceso de desarrollo de software, es necesario verificar cuánta tensión puede admitir antes de cualquier error.
#### Pruebas de regresión
A veces, el desarrollador decide cambiar alguna funcionalidad en el sistema. Este tipo de pruebas tiene como objetivo verificar que los cambios en el componente del software no causen reacciones o fallas indeseables en otros elementos no modificados.
#### Pruebas de humo
Estas son pruebas funcionales que ayudan a determinar si el conjunto de software funciona bien y si está listo para someterse a pruebas más exhaustivas.
Las pruebas de software contribuyen al aumento de la confianza del usuario, ya que el producto presentado ofrece una garantía para ser probada en todas las etapas de su desarrollo.

------------
## Patrones de Diseño GOF
El objetivo principal de los patrones es facilitar la reutilización de diseños y arquitecturas software que han tenido éxito capturando la experiencia y haciéndola accesible a los no expertos.
Dentro de los patrones clásicos tenemos los GoF (Gang of Four). Estudiados por Erich Gamma, Richard Helm, Ralph Johnson y John Vlissides en su mítico libro Design Patterns se contemplan 3 tipos de patrones:

- Patrones de creación: tratan de la inicialización y configuración de clases y objetos

- Patrones estructurales: Tratan de desacoplar interfaz e implementación de clases y objetos

- Patrones de comportamiento tratan de las interacciones dinámicas entre sociedades de clases y objetos

#### Patrones de creación

- Abstract Factory. Proporciona una interfaz para crear familias de objetos o que dependen entre sí, sin especificar sus clases concretas.

- Builder. Separa la construcción de un objeto complejo de su representación, de forma que el mismo proceso de construcción pueda crear diferentes representaciones.

- Factory Method. Define una interfaz para crear un objeto, pero deja que sean las subclases quienes decidan qué clase instanciar. Permite que una clase delegue en sus subclases la creación de objetos.

- Prototype. Especifica los tipos de objetos a crear por medio de una instancia prototípica, y crear nuevos objetos copiando este prototipo.

- Singleton. Garantiza que una clase sólo tenga una instancia, y proporciona un punto de acceso global a ella.

#### Patrones estructurales

- Adapter. Convierte la interfaz de una clase en otra distinta que es la que esperan los clientes. Permiten que cooperen clases que de otra manera no podrían por tener interfaces incompatibles.

- Bridge. Desvincula una abstracción de su implementación, de manera que ambas puedan variar de forma independiente.

- Composite. Combina objetos en estructuras de árbol para representar jerarquías de parte-todo. Permite que los clientes traten de manera uniforme a los objetos individuales y a los compuestos.

· Decorator. Añade dinámicamente nuevas responsabilidades a un objeto, proporcionando una alternativa flexible a la herencia para extender la funcionalidad.

· Facade. Proporciona una interfaz unificada para un conjunto de interfaces de un subsistema. Define una interfaz de alto nivel que hace que el subsistema se más fácil de usar.

#### Patrones de comportamiento

- Chain of Responsibility. Evita acoplar el emisor de una petición a su receptor, al dar a más de un objeto la posibilidad de responder a la petición. Crea una cadena con los objetos receptores y pasa la petición a través de la cadena hasta que esta sea tratada por algún objeto.

- Command. Encapsula una petición en un objeto, permitiendo así parametrizar a los clientes con distintas peticiones, encolar o llevar un registro de las peticiones y poder deshacer la operaciones.

- Interpreter. Dado un lenguaje, define una representación de su gramática junto con un intérprete que usa dicha representación para interpretar las sentencias del lenguaje.

- Iterator. Proporciona un modo de acceder secuencialmente a los elementos de un objeto agregado sin exponer su representación interna.

- State. Permite que un objeto modifique su comportamiento cada vez que cambia su estado interno. Parecerá que cambia la clase del objeto.

- Strategy. Define una familia de algoritmos, encapsula uno de ellos y los hace intercambiables. Permite que un algoritmo varíe independientemente de los clientes que lo usan.

- Visitor. Representa una operación sobre los elementos de una estructura de objetos. Permite definir una nueva operación sin cambiar las clases de los elementos sobre los que opera.