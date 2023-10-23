# Arquitectura de software

### ¿Que es la  Arquitectura de foftware?
- [Arquitectura de software](#arquitectura-de-software)
    - [¿Que es la  Arquitectura de foftware?](#que-es-la--arquitectura-de-foftware)
    - [¿Cómo funciona la arquitectura de software?](#cómo-funciona-la-arquitectura-de-software)
    - [Sus componentes](#sus-componentes)
    - [Patrones de arquitectura de software](#patrones-de-arquitectura-de-software)




🏛️ **La Arquitectura de Software en un Vistazo** 🏛️

La arquitectura de software es como los cimientos sólidos de un rascacielos 🏙️. 
Define cómo los diferentes componentes del software se relacionan entre sí, organizándolos de manera armoniosa. 
Esta estructura ofrece una vista panorámica de alto nivel del sistema, simplificando la comprensión de su diseño. 
Como el núcleo de la construcción, también facilita el proceso de desarrollo, mantenimiento y escalabilidad del software. 🚀

La arquitectura de software es la estructura fundamental o el marco de un sistema de software. 
Define la manera en que los diferentes componentes de un software interactúan entre sí, así como cómo se organizan y se relacionan.
Esta estructura proporciona una visión de alto nivel del sistema, lo que facilita la comprensión de su diseño y facilita el proceso de desarrollo, mantenimiento y escalabilidad del software.

📜 **Un Vistazo a la Historia de la Arquitectura de Software** 📜

La arquitectura de software, en el contexto del software, no es un concepto nuevo. Se originó en la década de los 60 y representa una planificación basada en modelos, patrones y abstracciones teóricas. Este enfoque es fundamental cuando se trata de desarrollar software de cierta complejidad, y sirve como paso previo a la implementación. Imagina la arquitectura como el plano maestro de una estructura impresionante. Proporciona una guía teórica detallada que nos ayuda a comprender cómo encajarán todas las piezas de nuestro producto o servicio, como piezas de un intrincado rompecabezas. 🌟

La noción de arquitectura de software brotó en la fecunda década de 1960, justo al compás del auge de la industria informática 🖥️ y la creciente complejidad de los sistemas de software 📈. La arquitectura de software emergió como una respuesta imperante a la necesidad de gestionar y comprender sistemas que se volvían, con cada latido de tiempo, más enigmáticos y desafiantes 🧩. Con el transcurrir de los años, esta disciplina ha evolucionado y se ha alzado como una piedra angular en el arte del desarrollo de software 🏗️.


### ¿Cómo funciona la arquitectura de software?

🛠️ **Funcionamiento de la Arquitectura de Software** 🛠️

La arquitectura de software es como el plano de una ciudad 🏙️. Se basa en una serie de decisiones de diseño que determinan cómo se construyen y gestionan los componentes del software. Estas decisiones abarcan la elección de lenguajes de programación 📚, la distribución de tareas 📊, la gestión de datos 📂, la comunicación entre componentes 🗣️ y la seguridad 🔐. La arquitectura actúa como un plan maestro 🗺️ que guía todo el ciclo de vida del software, desde la concepción 💡 hasta la implementación 🚀 y el mantenimiento 🧰.

**Problemas que resuelve la Arquitectura de software**

| Problemas que Resuelve la Arquitectura de Software | Descripción                                                                                                                                     |
| -------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Complejidad                                        | Permite descomponer sistemas complejos en componentes más pequeños y manejables, facilitando su desarrollo.                                     |
| Escalabilidad                                      | Define cómo un sistema puede crecer y adaptarse a las necesidades cambiantes sin requerir una reconstrucción completa.                          |
| Mantenimiento                                      | Facilita la identificación y corrección de problemas, así como la incorporación de nuevas funcionalidades sin afectar otras partes del sistema. |
| Reutilización                                      | Promueve la reutilización de componentes y módulos, ahorrando tiempo y recursos en el desarrollo de nuevos sistemas.                            |
| Rendimiento y Eficiencia                           | Permite optimizar el rendimiento del software al distribuir tareas y recursos de manera eficiente.                                              |

### Sus componentes

| Componentes de la Arquitectura de Software | Descripción                                                                                                                                   |
| ------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Componentes del Sistema                    | Estos son los módulos o partes del software que realizan tareas específicas.                                                                  |
| Interconexiones                            | Las formas en que los componentes se comunican entre sí, como llamadas a funciones, intercambio de datos o servicios web.                     |
| Patrones de Diseño                         | Soluciones probadas y estándar para problemas comunes de diseño de software, como el patrón MVC (Model-View-Controller) o el patrón de capas. |
| Consideraciones de Calidad                 | Factores como la seguridad, la escalabilidad, la eficiencia y la confiabilidad que deben tenerse en cuenta en el diseño.                      |




### Patrones de arquitectura de software

🏛️ **Patrones de Arquitectura de Software** 🏛️

La arquitectura de software se basa en una variedad de patrones para organizar y diseñar sistemas de software de manera efectiva. Aquí te presentamos algunos patrones de arquitectura comunes:

**1. Patrón Cliente-Servidor** 🤵🏻🤖

El patrón Cliente-Servidor es uno de los más fundamentales. En este modelo, un cliente (usuario o aplicación) solicita servicios o recursos a un servidor central. Es como un restaurante donde el cliente hace pedidos y el chef (servidor) prepara la comida. Este enfoque permite una clara separación de responsabilidades entre el cliente y el servidor.
- Ejemplo en la Rama llamada *Cliente-Servidor*

**2. Patrón de Capas** 🍰🍰
Como dice su nombre, este patrón de arquitectura de software divide la estructura del software en diferentes capas, que comúnmente se conocen como:

- Capa de presentación
- Capa Lógica
- Capa de Datos

El Patrón de Capas organiza un sistema en capas o niveles, donde cada capa tiene una función específica. Por ejemplo, en una aplicación web, puedes tener una capa de presentación (interfaz de usuario), una capa de lógica de negocios y una capa de acceso a datos. Esta estructura facilita la gestión y la escalabilidad.
Ejemplo en la Rama llamada *patron-de-capas*

**3. Patrón Master-Slave** 🎩🤵

El Patrón Master-Slave involucra dos roles: el "maestro" (master) y el "esclavo" (slave). El maestro coordina y dirige las tareas, mientras que los esclavos realizan las tareas asignadas. Este patrón es útil en sistemas distribuidos y paralelos, como una orquesta dirigida por un director.

**4. Patrón Modelo-Vista-Controlador (MVC)** 👩‍💼🖼️🎮

El Patrón Modelo-Vista-Controlador (MVC) es ampliamente utilizado en aplicaciones web y de software. Divide una aplicación en tres componentes: el Modelo (que maneja los datos), la Vista (que maneja la interfaz de usuario) y el Controlador (que gestiona la lógica de negocios). Es como una representación de un juego de roles en una obra de teatro.

**5. Patrón Broker** 🤝

El Patrón Broker actúa como intermediario entre componentes o servicios. Proporciona un punto centralizado para la comunicación y la gestión de servicios, lo que facilita la escalabilidad y la gestión de componentes distribuidos. Piensa en él como un conserje que te conecta con diferentes servicios en un hotel.

Estos patrones son solo algunos ejemplos de las numerosas estrategias utilizadas en la arquitectura de software para resolver desafíos específicos. La elección del patrón adecuado depende de las necesidades y objetivos de tu proyecto. 🛠️📚


