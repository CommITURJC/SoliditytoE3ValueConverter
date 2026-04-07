# Metamodelo e3value

**e3value** es una notación para la elaboración de modelos de negocio que se centra en representar los intercambios de valor que tienen lugar entre los actores que interactúan en la provisión de un servicio o similar. La Figura muestra el metamodelo de la notación **e3value**:

![Metamodelo e3value](https://raw.githubusercontent.com/CommITURJC/SoliditytoE3ValueConverter/main/metamodelo/e3valueMetamodel.png)

Los principales elementos del modelo son:

**Actor**: los participantes que interactúan, intercambiando objetos de valor. Si fuera una asociación conjunta de varios de ellos, se representa con un elemento Market Segment, como los Listeners o los Advertisers del ejemplo.

**Value Object**: aquello que se intercambia entre los actores y que tiene valor desde la perspectiva del negocio. Debido a su naturaleza, puede ser representado de diferentes formas: un servicio, tokens, un derecho, un bien tangible, etc. En el ejemplo, los suscriptores o Listeners abonan una cuota de suscripción (suscription fee) y a cambio reciben acceso a la oferta musical de la plataforma (music access).

**Value Interface**: el conjunto de puertos que encapsulan lo que un actor ofrece/recibe en un intercambio de valor. Estas interfaces permiten expresar que los intercambios ocurren como parte de una “oferta” o “contraprestación”.

**Value Port**: cada punto de entrada o salida a través del cual se entrega o recibe un objeto de valor. En el ejemplo cada actor tiene un único value interface y cada uno incluye un value port de entrada y uno de salida.

**Value Exchange**: la relación que conecta dos puertos y representa el intercambio de un objeto de valor entre actores. Se visualiza como una línea con el nombre del objeto de valor que circula por esa conexión.

**Start/End Stimulus**: permiten delimitar el inicio y fin de un escenario de valor, aportando contexto sobre qué eventos disparan el intercambio
