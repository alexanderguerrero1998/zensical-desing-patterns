# Introducción

> En esta sección respondemos a la pregunta candente: *«¿Por qué demonios metieron esto en un libro de patrones de diseño?»*

## Para quién es este libro

Si puedes responder «sí» a todas estas preguntas:

1. ¿Conoces Java (no hace falta ser un gurú) o conoces bien otro lenguaje orientado a objetos?
2. ¿Quieres aprender, comprender, recordar y aplicar los patrones de diseño, incluidos los principios de diseño OO sobre los que se sustentan?
3. ¿Prefieres una conversación estimulante en una cena a unas aburridas y secas clases académicas?

**Este libro es para ti.**

## Quién debería alejarse de este libro

Si puedes responder «sí» a alguna de estas:

1. ¿Eres totalmente nuevo en la programación orientada a objetos?
2. ¿Eres un diseñador/desarrollador orientado a objetos pizcador de culos y andas buscando un libro de referencia?
3. ¿Eres un arquitecto que busca patrones de diseño empresarial?
4. ¿Tienes miedo a probar algo diferente? ¿Preferirías que te hicieran un empaste antes que combinar rayas con cuadros? ¿Crees que un libro técnico no puede ser serio si los conceptos orientados a objetos están personificados?

**Este libro no es para ti.**

!!! note "Nota del departamento de marketing"
    Este libro es para cualquiera que tenga una tarjeta de crédito.

## Sabemos lo que estás pensando

«¿Cómo puede ser este un libro serio de programación?»

«¿Qué pasa con todos esos dibujos?»

«¿De verdad se puede aprender así?»

**Tu cerebro piensa que ESTO es importante.**

## Y sabemos lo que piensa tu cerebro

Tu cerebro ansía la novedad. Siempre está buscando, escaneando, esperando algo inusual. Fue construido así, y eso te ayuda a seguir con vida. Hoy en día es menos probable que termines siendo el almuerzo de un tigre. Pero tu cerebro sigue buscando. Nunca se sabe.

Entonces, ¿qué hace tu cerebro con todas las cosas rutinarias, ordinarias y normales que encuentras? Todo lo posible para impedir que interfieran con el verdadero trabajo del cerebro: registrar las cosas que importan. No se molesta en guardar las cosas aburridas; nunca pasan el filtro de «esto evidentemente no es importante».

¿Cómo sabe tu cerebro lo que es importante? Supongamos que sales a dar un paseo y un tigre salta delante de ti. ¿Qué ocurre dentro de tu cabeza y de tu cuerpo?

Las neuronas se disparan. Las emociones se aceleran. Las sustancias químicas se desatan.

**¡Esto debe de ser importante! ¡No lo olvides!**

Y así es como tu cerebro sabe...

Pero imagina que estás en casa o en la biblioteca. Es una zona segura, cálida y libre de tigres. Estás estudiando. Preparándote para un examen. O intentando aprender algún tema técnico difícil que tu jefe cree que te llevará una semana, diez días como mucho.

Con un único problema: tu cerebro está intentando hacerte un gran favor. Intenta asegurarse de que este contenido evidentemente poco importante no abarrote los escasos recursos. Recursos que están mejor empleados en almacenar las cosas realmente grandes. Como los tigres. Como el peligro del fuego. Como el hecho de que nunca más deberías hacer snowboard en pantalones cortos.

Y no hay una forma sencilla de decirle a tu cerebro: «Oye, cerebro, muchísimas gracias, pero por muy aburrido que sea este libro, y por poco que me esté registrando en la escala de Richter emocional en este momento, de verdad quiero que guardes todo esto».

## Pensamos en un lector de Head First como en un alumno

Entonces, ¿qué hace falta para aprender algo? Primero, tienes que pillarlo; después, asegurarte de no olvidarlo. No se trata de meter datos a presión en tu cabeza. Según las últimas investigaciones en ciencia cognitiva, neurobiología y psicología educativa, aprender requiere mucho más que texto en una página. Sabemos qué es lo que activa tu cerebro.

### Algunos de los principios de aprendizaje de Head First

1. **Hazlo visual.** Las imágenes son mucho más memorables que las palabras solas y hacen el aprendizaje mucho más eficaz (hasta un 89 % de mejora en los estudios de recuerdo y de transferencia). Además, hacen que las cosas sean más comprensibles. Pon las palabras dentro o cerca de los gráficos a los que se refieren, en lugar de al pie o en otra página, y los alumnos tendrán hasta el doble de probabilidades de resolver problemas relacionados con el contenido.
2. **Usa un estilo conversacional y personalizado.** En los estudios, los estudiantes obtuvieron hasta un 40 % mejores resultados en las pruebas posteriores al aprendizaje si el contenido les hablaba directamente, usando un estilo conversacional en primera persona en lugar de un tono formal. Cuenta historias en lugar de dar lecciones magistrales. Usa un lenguaje natural. No te tomes demasiado en serio. ¿A qué prestarías más atención: a un acompañante estimulante en una cena o a una conferencia?
3. **Haz que el alumno piense más a fondo.** En otras palabras, a menos que flexiones activamente tus neuronas, no ocurre gran cosa en tu cabeza. Un lector tiene que estar motivado, comprometido, curioso e inspirado para resolver problemas, sacar conclusiones y generar conocimiento nuevo. Y para eso necesitas retos, ejercicios, preguntas que inviten a pensar, actividades que involucren ambos hemisferios del cerebro y múltiples sentidos.
4. **Capta y retén la atención del lector.** Todos hemos vivido esa experiencia de «de verdad quiero aprender esto, pero no consigo mantenerme despierto más allá de la página uno». Tu cerebro presta atención a las cosas que son fuera de lo común, interesantes, extrañas, llamativas e inesperadas. Aprender un tema técnico nuevo y difícil no tiene por qué ser aburrido. Tu cerebro aprenderá mucho más deprisa si no lo es.
5. **Llega a sus emociones.** Ahora sabemos que tu capacidad para recordar algo depende en gran medida de su contenido emocional. Recuerdas lo que te importa. Recuerdas cuando sientes algo. No, no hablamos de historias desgarradoras sobre un niño y su perro. Hablamos de emociones como la sorpresa, la curiosidad, la diversión, el «¿qué coño...?» y la sensación de «¡mola!» que llega cuando resuelves un puzle, aprendes algo que todo el mundo cree difícil o te das cuenta de que ya sabes algo que ese tal Bob de ingeniería, más técnico que tú, no sabe.

!!! note "Piensa en ello"
    ¿Tiene sentido decir que una bañera es una habitación de baño? ¿O que la habitación de baño es una bañera? ¿O es una relación «tiene-un» (HAS-A)?

!!! note "No tiene método"
    Da muy mala vida ser un método abstracto: no tienes cuerpo.

```java
abstract void roam();
```

!!! note "Piénsalo bien"
    Termínalo con un punto y coma.

## Metacognición: pensar en el pensamiento

Si de verdad quieres aprender, y quieres aprender más deprisa y más a fondo, presta atención a cómo prestas atención. Piensa sobre cómo piensas. Aprende cómo aprendes.

La mayoría de nosotros no hizo cursos de metacognición ni de teoría del aprendizaje mientras crecíamos. Se esperaba que aprendiéramos, pero rara vez se nos enseñó a aprender.

Pero damos por hecho que si tienes este libro en las manos, quieres aprender de verdad los patrones de diseño. Y probablemente no quieras emplear mucho tiempo. Y quieres recordar lo que lees y poder aplicarlo. Y para eso tienes que comprenderlo. Para sacar el máximo partido a este libro, o a cualquier libro o experiencia de aprendizaje, hazte responsable de tu cerebro. De tu cerebro con este contenido.

El truco está en conseguir que tu cerebro vea el material nuevo que estás aprendiendo como Realmente Importante. Crucial para tu bienestar. Tan importante como un tigre. De lo contrario, te espera una batalla constante, con tu cerebro haciendo todo lo posible por evitar que el contenido nuevo se quede.

**¿Cómo consigues que tu cerebro piense que los patrones de diseño son tan importantes como un tigre?**

Existe la forma lenta y tediosa, y la forma más rápida y más eficaz. La forma lenta es la repetición pura y dura. Obviamente sabes que eres capaz de aprender y recordar incluso los temas más aburridos si machacas siempre sobre lo mismo. Con la suficiente repetición, tu cerebro dice: «A él no le parece importante, pero no deja de mirar lo mismo una y otra vez, así que supongo que debe de serlo».

La forma más rápida es hacer cualquier cosa que aumente la actividad cerebral, sobre todo distintos tipos de actividad cerebral. Las cosas de la página anterior son una parte importante de la solución, y todas ellas han demostrado que ayudan a que tu cerebro trabaje a tu favor. Por ejemplo, los estudios muestran que poner las palabras dentro de las imágenes que describen (en lugar de en otro lugar de la página, como en un pie de foto o en el cuerpo del texto) hace que tu cerebro intente dar sentido a cómo se relacionan las palabras y la imagen, y eso hace que se disparen más neuronas. Más neuronas disparándose = más posibilidades de que tu cerebro capte que esto merece la pena atender, y quizá registrar.

El estilo conversacional ayuda porque la gente tiende a prestar más atención cuando percibe que está en una conversación, ya que se espera que sigan la conversación y pongan de su parte. Lo asombroso es que a tu cerebro no le importa necesariamente que la «conversación» sea entre tú y un libro. En cambio, si el estilo de escritura es formal y seco, tu cerebro lo percibe como cuando te dan una charla sentado en una sala llena de oyentes pasivos. No hay necesidad de mantenerse despierto.

Pero las imágenes y el estilo conversacional son solo el principio.

## Esto es lo que hicimos nosotros

Usamos imágenes porque tu cerebro está afinado para lo visual, y no para el texto. En lo que respecta a tu cerebro, una imagen vale de verdad 1.024 palabras. Y cuando el texto y las imágenes trabajan juntos, incrustamos el texto dentro de las imágenes, porque tu cerebro trabaja con más eficacia cuando el texto está dentro de aquello a lo que se refiere, en lugar de en un pie de foto o enterrado en otro sitio.

!!! abstract "Relación de uno a muchos"
    [El objeto que guarda el estado] --notifica automáticamente--> [Objetos dependientes (observadores)]

Usamos la redundancia, diciendo lo mismo de formas distintas y con tipos de medios diferentes, y con varios sentidos, para aumentar la probabilidad de que el contenido se codifique en más de una zona de tu cerebro.

Usamos conceptos e imágenes de formas inesperadas porque tu cerebro está afinado para la novedad, y usamos imágenes e ideas con, al menos, algo de contenido emocional, porque tu cerebro está afinado para prestar atención a la bioquímica de las emociones. Lo que te hace sentir algo tiene más probabilidades de recordarse, aunque ese sentimiento no sea más que un poco de humor, sorpresa o interés.

Usamos un estilo personalizado y conversacional, porque tu cerebro está afinado para prestar más atención cuando cree que está en una conversación que cuando cree que está escuchando pasivamente una presentación. Tu cerebro hace esto incluso cuando lees.

Incluimos más de 90 actividades, porque tu cerebro está afinado para aprender y recordar más cuando haces cosas que cuando lees sobre ellas. Y pusimos los ejercicios al nivel de desafiantes-pero-viables, porque eso es lo que la mayoría de la gente prefiere.

Usamos múltiples estilos de aprendizaje, porque puedes preferir los procedimientos paso a paso, mientras que otra persona quiere comprender primero el panorama general, y otra solo quiere ver un ejemplo de código. Pero al margen de tu preferencia de aprendizaje, todo el mundo se beneficia de ver el mismo contenido representado de varias formas.

Incluimos contenido para los dos hemisferios de tu cerebro, porque cuanto más involucres tu cerebro, más probable es que aprendas y recuerdes, y más tiempo podrás mantener la concentración. Como trabajar un hemisferio suele significar darle al otro la oportunidad de descansar, puedes ser más productivo aprendiendo durante más tiempo.

Y añadimos historias y ejercicios que presentan más de un punto de vista, porque tu cerebro está afinado para aprender más a fondo cuando se ve obligado a hacer evaluaciones y emitir juicios.

Incluimos retos, tanto con ejercicios como planteando preguntas que no siempre tienen una respuesta directa, porque tu cerebro está afinado para aprender y recordar cuando tiene que esforzarse en algo. Piénsalo: no puedes ponerte en forma solo con ver a la gente del gimnasio. Pero hicimos todo lo posible por asegurarnos de que, cuando te esfuerzas, lo haces en las cosas correctas. Que no gastes ni una dendrita de más en procesar un ejemplo difícil de entender, ni en descifrar un texto cargado de jerga o excesivamente lacónico.

Usamos personas. En historias, ejemplos, imágenes, etc., porque, bueno, porque tú eres una persona. Y tu cerebro presta más atención a las personas que a las cosas.

Usamos un enfoque 80/20. Damos por hecho que si vas a por un doctorado en diseño de software, este no será tu único libro. Así que no hablamos de todo. Solo de lo que de verdad vas a necesitar.

## Lo que TÚ puedes hacer para domar tu cerebro

Nosotros ya hemos hecho nuestra parte. El resto depende de ti. Estos consejos son un punto de partida; escucha a tu cerebro y averigua qué te funciona y qué no. Prueba cosas nuevas.

!!! tip "Recorta esta página y pégala en la nevera."

1. **Ve más despacio.** Cuanto más comprendas, menos tendrás que memorizar. No te limites a leer. Para y piensa. Cuando el libro te haga una pregunta, no saltes directamente a la respuesta. Imagina que alguien te está haciendo la pregunta de verdad. Cuanto más a fondo fuerces a tu cerebro a pensar, más posibilidades tendrás de aprender y recordar.
2. **Haz los ejercicios. Escribe tus propias notas.** Los pusimos por algo, pero si los hiciéramos por ti, sería como si otra persona entrenara en tu lugar. Y no te limites a mirar los ejercicios. Usa un lápiz. Hay muchas evidencias de que la actividad física durante el aprendizaje puede aumentar el aprendizaje.
3. **Lee las secciones «No hay preguntas tontas».** Todas. No son apartados opcionales: son parte del contenido central. No te las saltes.
4. **Que este sea lo último que leas antes de acostarte.** O, al menos, lo último desafiante. Parte del aprendizaje (en especial la transferencia a la memoria a largo plazo) ocurre después de dejar el libro. Tu cerebro necesita tiempo a solas para seguir procesando. Si metes algo nuevo durante ese tiempo de procesamiento, parte de lo que acabas de aprender se perderá.
5. **Bebe agua. Mucha.** Tu cerebro funciona mejor en un buen baño de líquido. La deshidratación (que puede ocurrir antes de que sientas sed) disminuye la función cognitiva.
6. **Háblalo. En voz alta.** Hablar activa una parte diferente del cerebro. Si intentas comprender algo, o aumentar tus posibilidades de recordarlo más tarde, dilo en voz alta. Mejor aún, intenta explicarlo en voz alta a otra persona. Aprenderás más deprisa y puede que descubras ideas que no sabías que estaban ahí cuando lo leías.
7. **Escucha a tu cerebro.** Presta atención a si tu cerebro se está sobrecargando. Si empiezas a pasar de puntillas por la superficie o a olvidar lo que acabas de leer, es hora de un descanso. Cuando pasas de cierto punto, no aprenderás más deprisa por meter más cosas, y podrías incluso perjudicar el proceso.
8. **Siente algo.** Tu cerebro necesita saber que esto importa. Métete en las historias. Inventa tus propios pies de foto para las fotografías. Quejarte de un mal chiste sigue siendo mejor que no sentir nada en absoluto.
9. **Diseña algo.** Aplica esto a algo nuevo que estés diseñando, o refactoriza un proyecto antiguo. Haz algo para conseguir experiencia más allá de los ejercicios y las actividades de este libro. Solo necesitas un lápiz y un problema que resolver… un problema que podría beneficiarse de uno o más patrones de diseño.

## Léeme

Esto es una experiencia de aprendizaje, no un libro de referencia. Eliminamos deliberadamente todo lo que pudiera estorbar el aprendizaje de aquello en lo que estamos trabajando en cada punto del libro. Y en la primera lectura necesitas empezar por el principio, porque el libro da por hecho lo que ya has visto y aprendido.

- **Usamos diagramas sencillos de estilo UML.** Aunque hay bastantes probabilidades de que te hayas topado con UML, no se explica en el libro ni es un prerrequisito para él. Si nunca has visto UML, no te preocupes: te daremos algunas pistas por el camino. En otras palabras, no tendrás que preocuparte de aprender patrones de diseño y UML a la vez. Nuestros diagramas son «de estilo UML»: aunque intentamos ser fieles a UML, hay veces en las que doblamos un poco las reglas, por lo general por nuestros propios motivos artísticos egoístas.
- **No cubrimos todos y cada uno de los patrones de diseño jamás creados.** Hay muchísimos patrones de diseño: los patrones fundacionales originales (conocidos como los patrones GoF), los patrones Java empresariales, los patrones arquitectónicos, los patrones de diseño de videojuegos y muchos más. Pero nuestro objetivo era asegurarnos de que el libro pesara menos que la persona que lo lee, así que no los cubrimos todos aquí. Nos centramos en los patrones centrales que importan de los patrones orientados a objetos originales del GoF, y en asegurarnos de que comprendes de verdad, en serio y en profundidad, cómo y cuándo usarlos. Encontrarás una breve ojeada a algunos de los otros patrones (los que es muchísimo menos probable que uses) en el apéndice. En cualquier caso, cuando termines con *Head First Design Patterns*, podrás coger cualquier catálogo de patrones y ponerte al día rápidamente.
- **Las actividades NO son opcionales.** Los ejercicios y las actividades no son complementos; son parte del contenido central del libro. Algunos ayudan con la memoria, otros con la comprensión y otros a aplicar lo aprendido. No te saltes los ejercicios. Los crucigramas son lo único que no tienes obligación de hacer, pero resultan buenos para darle a tu cerebro la oportunidad de pensar en las palabras desde un contexto diferente.
- **Usamos la palabra «composición» en el sentido OO general, que es más flexible que el uso estricto de «composición» en UML.** Cuando decimos que «un objeto está compuesto con otro objeto» queremos decir que están relacionados por una relación «tiene-un» (HAS-A). Nuestro uso refleja el uso tradicional del término y es el que emplea el texto del GoF (aprenderás qué es eso más adelante). Más recientemente, UML ha refinado este término en varios tipos de composición. Si eres un experto en UML, igualmente podrás leer el libro y deberías ser capaz de mapear con facilidad el uso de la composición a términos más refinados mientras lees.
- **La redundancia es intencionada e importante.** Una diferencia distintiva de un libro Head First es que queremos que lo pilles de verdad. Y queremos que termines el libro recordando lo que has aprendido. La mayoría de los libros de referencia no tienen la retención y el recuerdo como objetivo, pero este libro trata sobre el aprendizaje, así que verás algunos de los mismos conceptos aparecer más de una vez.
- **Los ejemplos de código son lo más concisos posible.** Nuestros lectores nos dicen que es frustrante bucear entre 200 líneas de código buscando las dos que necesitan comprender. La mayoría de los ejemplos de este libro se muestran en el contexto más pequeño posible, para que la parte que intentas aprender sea clara y sencilla. No esperes que todo el código sea robusto, ni siquiera completo: los ejemplos están escritos específicamente para el aprendizaje y no siempre son totalmente funcionales. En algunos casos no hemos incluido todas las sentencias `import` necesarias, pero damos por hecho que si eres un programador Java sabes, por ejemplo, que `ArrayList` está en `java.util`. Si los `import` no formaban parte de la API JSE de núcleo normal, lo mencionamos. También hemos colgado todo el código fuente en la web para que puedas descargarlo. Lo encontrarás en `http://wickedlysmart.com/head-first-design-patterns`. Además, para centrarnos en el lado de aprendizaje del código, no pusimos nuestras clases en paquetes (es decir, todas están en el paquete por defecto de Java). No recomendamos esto en el mundo real, y cuando descargues los ejemplos de código de este libro verás que todas las clases están en paquetes.
- **Los ejercicios de Brain Power no tienen respuestas.** En algunos no hay una respuesta correcta, y en otros parte de la experiencia de aprendizaje de las actividades de Brain Power es que decidas tú si tus respuestas son correctas y cuándo. En algunos ejercicios de Brain Power encontrarás pistas que te indiquen la dirección correcta.

## Revisores técnicos

- Mark Spritzler
- Jason Menard
- Dirk Schreckmann
- Barney Marispini — líder intrépido del equipo de revisión extrema del HFDP
- Johannes deJong
- Jef Cumps
- Ike Van Atta
- Valentin Crettaz

!!! note "En memoria de Philippe Maquet, 1960-2004"
    Tu asombrosa experiencia técnica, tu entusiasmo incansable y tu profunda preocupación por quien aprende nos inspirarán siempre.

## Revisores técnicos de la 2.ª edición

- David Powers
- George Heineman — MVP de los revisores de la 2.ª edición
- Trisha Gee
- Julian Setiawan

## Agradecimientos

### De la primera edición

*En O'Reilly:* nuestro agradecimiento más grande a Mike Loukides, en O'Reilly, por empezarlo todo y ayudar a dar forma al concepto Head First hasta convertirlo en una serie. Y una gran gracias a la fuerza impulsora detrás de Head First, Tim O'Reilly. Gracias a la ingeniosa «mamá de la serie» Kyle Hart, al «rey del diseño» Ron Bilodeau, a la estrella del rock-and-roll Ellie Volkhausen por su inspirado diseño de portada, a Melanie Yarbrough por capitanear la producción, a Colleen Gorman y Rachel Monaghan por sus intransigentes correcciones de estilo, y a Bob Pfahler por un índice muchísimo mejor. Por último, gracias a Mike Hendrickson y Meghan Blanchette por defender este libro y formar el equipo.

*Nuestros intrépidos revisores:* estamos enormemente agradecidos a nuestro director de revisión técnica, Johannes deJong. Eres nuestro héroe, Johannes. Y valoramos en lo más profundo las contribuciones del fallecido Philippe Maquet, cogestor del equipo de revisión de Javaranch. Has alegrado la vida de miles de desarrolladores por ti solo, y el impacto que has tenido en sus vidas (y en las nuestras) es eterno. Jef Cumps es espeluznantemente bueno encontrando problemas en nuestros borradores de capítulos, y una vez más supuso una gran diferencia para el libro. ¡Gracias, Jef! Valentin Cretazz (el tipo del AOP), que ha estado con nosotros desde el primer libro Head First, demostró (como siempre) cuánto necesitamos realmente de su experiencia técnica y su perspicacia. Eres un fenómeno, Valentin (pero quítate la corbata).

Dos recién llegados al equipo de revisión del HFDP, Barney Marispini e Ike Van Atta, hicieron un trabajo de matrícula con el libro: nos disteis comentarios realmente cruciales. Gracias por uniros al equipo.

También recibimos una excelente ayuda técnica de los moderadores/gurús de Javaranch Mark Spritzler, Jason Menard, Dirk Schreckmann, Thomas Paul y Margarita Isaeva. Y como siempre, gracias en especial al dueño del local de javaranch.com, Paul Wheaton.

Gracias a los finalistas del concurso de Javaranch «Elige la portada de Head First Design Patterns». El ganador, Si Brewster, presentó el ensayo ganador que nos convenció para elegir a la mujer que ves en nuestra portada. Otros finalistas fueron Andrew Esse, Gian Franco Casula, Helen Crosbie, Pho Tek, Helen Thomas, Sateesh Kommineni y Jeff Fisher.

Para la actualización de 2014 del libro, estamos muy agradecidos a los siguientes revisores técnicos: George Hoffer, Ted Hill, Todd Bartoszkiewicz, Sylvain Tenier, Scott Davidson, Kevin Ryan, Rich Ward, Mark Francis Jaeger, Mark Masse, Glenn Ray, Bayard Fetler, Paul Higgins, Matt Carpenter, Julia Williams, Matt McCullough y Mary Ann Belarmino.

## Agradecimientos

### De la segunda edición

*En O'Reilly:* ante todo, Mary Treseler es la superpoderosa que hace que todo suceda, y le estamos eternamente agradecidos por todo lo que hace por O'Reilly, por Head First y por los autores. Melissa Duffield y Michele Cronin despejaron muchos caminos que hicieron posible esta segunda edición. Rachel Monaghan hizo una corrección de estilo asombrosa, dándole un brillo nuevo a nuestro texto. Kristen Brown hizo que el libro se viera precioso, tanto en línea como en papel. Ellie Volckhausen hizo su magia y diseñó una portada nueva y brillante para la segunda edición. ¡Gracias a todos!

*Nuestros revisores de la 2.ª edición:* estamos agradecidos a nuestros revisores técnicos de la 2.ª edición por retomar el trabajo 15 años después. David Powers es nuestro revisor de cabecera (es nuestro; ni se te ocurra pedirle que revise tu libro) porque no se le escapa nada. George Heineman fue más allá con sus comentarios, sugerencias y comentarios detallados, y se llevó el premio MVP técnico de esta edición. Trisha Gee y Julian Setiawan aportaron el saber de Java tan valioso que necesitábamos para evitar esos penosos errores de Java que dan vergüenza ajena. ¡Gracias a todos!

### Un agradecimiento muy especial

Un agradecimiento muy especial a Erich Gamma, que fue muchísimo más allá del deber en su revisión de este libro (incluso se llevó un borrador de vacaciones). Erich, tu interés en este libro nos inspiró, y tu exhaustiva revisión técnica lo mejoró inconmensurablemente. Gracias también a todo el cuarteto de la Banda de los Cuatro (GoF) por su apoyo e interés, y por hacer una aparición especial en Objectville. También estamos en deuda con Ward Cunningham y con la comunidad de patrones, creadores del Portland Pattern Repository, un recurso indispensable para nosotros a la hora de escribir este libro.

Un enorme agradecimiento a Mike Loukides, Mike Hendrickson y Meghan Blanchette. Mike L. estuvo con nosotros en cada paso del camino. Mike, tus perspicaces comentarios ayudaron a dar forma al libro, y tu ánimo nos mantuvo avanzando. Mike H., gracias por tu persistencia durante cinco años intentando que escribiéramos un libro de patrones; por fin lo hicimos, y nos alegra haber esperado a Head First.

Hace falta un pueblo entero para escribir un libro técnico: Bill Pugh y Ken Arnold nos dieron consejo de experto sobre Singleton. Joshua Marinacci nos aportó trucos y consejos de Swing de rock. El artículo de John Brewer «Why a Duck?» inspiró SimUDuck (y nos alegra que a él también le gusten los patos). Dan Friedman inspiró el ejemplo del pequeño Singleton. Daniel Steinberg actuó como nuestro «enlace técnico» y como nuestra red de apoyo emocional. Gracias al James Dempsey de Apple por permitirnos usar su canción del MVC. Y gracias a Richard Warburton, que se aseguró de que nuestras actualizaciones de código de Java 8 estuvieran a la altura en esta edición actualizada del libro.

Por último, un agradecimiento personal al equipo de revisión de Javaranch por sus reseñas de primera y su caluroso apoyo. Hay más de vosotros en este libro de lo que creéis.

Escribir un libro Head First es una aventura salvaje con dos guías turísticos asombrosos: Kathy Sierra y Bert Bates. Con Kathy y Bert tiras por la borda toda la convención de escribir libros y entras en un mundo lleno de historias, teoría del aprendizaje, ciencia cognitiva y cultura pop, donde siempre manda el lector.