---
icon: lucide/book-open
---

# Head First Design Patterns

Traducción al español de *Head First Design Patterns: Building Extensible and
Maintainable Object-Oriented Software*, de Eric Freeman y Elisabeth Robson con
Elizabeth Robson y Kuth Hyoung Oh (Head First Books / O'Reilly, 2.ª edición).

!!! info "Sobre esta edición"
    Los diagramas del original se han reconstruido con **Mermaid** y el código
    se conserva en Java tal como aparece en el libro, para que los ejemplos
    sigan siendo ejecutables. La prosa, las notas marginales, los cuestionarios
    y las explicaciones están traducidos al español.

    Los nombres de clases, interfaces y métodos se mantienen en inglés por
    coherencia con el código; el término equivalente en español aparece la
    primera vez que se introduce cada concepto.

## Índice

| # | Capítulo | Págs. | Estado |
| --- | --- | --- | --- |
| — | [Introducción — quién es este libro para ti, metacognición y lectores técnicos](introduccion/index.md) | 27-38 | Completo |
| 1 | [Introducción a los patrones de diseño](capitulo-1/index.md) — el problema de los patos, los tres principios de diseño y el patrón Strategy | 39-74 | Completo |
| 2 | [El patrón Observer](capitulo-2/index.md) — mantener tus objetos al tanto | 75-116 | Completo |
| 3 | [El patrón Decorator](capitulo-3/index.md) — decorar objetos | 117-146 | Completo |
| 4 | [El patrón Factory](capitulo-4/index.md) — hornear con la magia OO | 147-206 | Completo |
| 5 | [El patrón Singleton](capitulo-5/index.md) — objetos únicos | 207-228 | Completo |
| 6 | [El patrón Command](capitulo-6/index.md) — encapsular la invocación | 229-274 | Completo |
| 7 | [Los patrones Adapter y Facade](capitulo-7/index.md) — ser adaptable | 275-314 | Completo |
| 8 | [El patrón Template Method](capitulo-8/index.md) — encapsular algoritmos | 315-354 | Completo |
| 9 | [Los patrones Iterator y Composite](capitulo-9/index.md) — colecciones bien gestionadas | 355-418 | Completo |
| 10 | [El patrón State](capitulo-10/index.md) — el estado de las cosas | 419-462 | Completo |
| 11 | [El patrón Proxy](capitulo-11/index.md) — controlar el acceso a objetos | 463-530 | Completo |
| 12 | [Patrones compuestos](capitulo-12/index.md) — patrones de patrones, MVC | 531-600 | Completo |
| 13 | [Mejor vivir con patrones](capitulo-13/index.md) — patrones en el mundo real, anti-patrones | 601-634 | Completo |
| 14 | [Apéndice: patrones restantes](capitulo-14/index.md) — Bridge, Builder, Chain of Responsibility, Flyweight, Interpreter, Mediator, Memento, Prototype, Visitor | 635-654 | Completo |

## Patrones que cubre el libro

| Patrón | Capítulo | Para qué sirve |
| --- | --- | --- |
| Strategy | 1 | Define una familia de algoritmos intercambiables. |
| Observer | 2 | Notifica cambios a los objetos interesados. |
| Decorator | 3 | Añade responsabilidades dinámicamente sin herencia. |
| Factory Method | 4 | Decide qué subclase concreta instanciar. |
| Abstract Factory | 4 | Crea familias de objetos relacionados. |
| Singleton | 5 | Garantiza una única instancia. |
| Command | 6 | Encapsula una petición como un objeto. |
| Adapter | 7 | Adapta la interfaz de una clase a la que espera el cliente. |
| Facade | 7 | Simplifica el acceso a un subsistema complejo. |
| Template Method | 8 | Delega los pasos variables a las subclases. |
| Iterator | 9 | Recorre una colección sin exponer su representación. |
| Composite | 9 | Trata objetos individuales y compuestos de forma uniforme. |
| State | 10 | Cambia el comportamiento según el estado interno. |
| Proxy | 11 | Controla el acceso a otro objeto. |
| MVC | 12 | Patrón compuesto de Observer, Strategy y Composite. |
| Bridge | 14 | Separa abstracción de implementación. |
| Builder | 14 | Construye objetos complejos paso a paso. |
| Chain of Responsibility | 14 | Delega una petición a una cadena de manejadores. |
| Flyweight | 14 | Comparte estado para ahorrar memoria. |
| Interpreter | 14 | Define una gramática y un intérprete. |
| Mediator | 14 | Encapsula la interacción entre objetos. |
| Memento | 14 | Captura y restaura el estado de un objeto. |
| Prototype | 14 | Clona objetos existentes. |
| Visitor | 14 | Añade operaciones sin modificar las clases. |
