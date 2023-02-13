# ¿Que es especificación de requisitos?

### **Qué es la especificación de requisitos: definición, mejores herramientas y técnicas**&#x20;

La especificación de requisitos es una parte crítica del proceso de ingeniería de requisitos. Es la tercera fase, después de la Captura y Análisis de Requerimientos. El objetivo es crear un documento, o Especificación de Requisitos, con el nivel de detalle correspondiente. Este documento contendrá todos los requisitos que se van a imponer en el diseño y verificación del producto. También contendrá otra información relacionada necesaria para el diseño, verificación y mantenimiento del producto.

<figure><img src=".gitbook/assets/requerimientos.jpg" alt=""><figcaption></figcaption></figure>

### **¿Qué es la especificación de requisitos?**

La especificación de requisitos, también conocida como documentación, es un proceso de anotar todos los requisitos del sistema y del usuario en forma de documento. Estos requisitos deben ser claros, completos, completos y coherentes.&#x20;

Durante la actividad de captura, recopilamos todos los requisitos de varias fuentes. Durante las actividades de análisis y negociación, analizamos y entendemos esos requisitos. Ahora, debemos preparar un documento formal que explique esos requisitos. Esa es la especificación de requisitos. Para ser precisos, es el proceso de documentar todas las necesidades y restricciones del usuario y del sistema de manera clara y precisa.

### **¿Qué es un requisito del sistema?**

Los requisitos del sistema se pueden llamar la versión ampliada de los requisitos del usuario. Los requisitos del sistema actúan como punto de partida para cualquier nuevo diseño de sistema. Estos requisitos son una descripción detallada de los requisitos del usuario que el sistema debe satisfacer.

<figure><img src=".gitbook/assets/Traceability-Main.png" alt=""><figcaption></figcaption></figure>

### **¿Qué es un requisito de usuario?**

El requisito del usuario es una combinación de requisitos funcionales y no funcionales. Estos requisitos de usuario deben diseñarse de tal manera que sean fácilmente comprensibles para los usuarios que no tienen ningún tipo de conocimiento técnico. Por lo tanto, deben estar escritos en lenguaje natural utilizando tablas, formularios y diagramas simples. Además, asegúrese de que el documento no tenga detalles sobre el diseño del sistema, el software o las anotaciones formales.&#x20;

<figure><img src=".gitbook/assets/Review-Main-1.png" alt=""><figcaption></figcaption></figure>

**Características de un buen SRS (Software Requirements Specification) especificación de requerimientos de software**

La **especificación de requisitos de software** (**SRS**) es una descripción completa del comportamiento del sistema que se va a desarrollar. Incluye un conjunto de casos de uso que describe todas las interacciones que tendrán los usuarios con el software. Los casos de uso también son conocidos como requisitos funcionales. Además de los casos de uso, la ERS también contiene requisitos no funcionales (complementarios). Los requisitos no funcionales son requisitos que imponen restricciones en el diseño o la implementación, como, por ejemplo, restricciones en el diseño o estándares de calidad.

Está dirigida tanto al cliente como al equipo de desarrollo. El lenguaje utilizado para su redacción debe ser informal, de forma que sea fácilmente comprensible para todas las partes involucradas en el desarrollo.

Las características de un **buen SRS** son:

* **Sin ambigüedades**
* **Completa**
* **Verificable**
* **Coherente**
* **Modificable**
* **Trazable**
* **Utilizable durante la fase explotación y mantenimiento**

Cada característica se aborda con mayor detalle a continuación:

**Sin ambigüedad.** Una SRS es inequívoca si- y solo si- cada requisito en ella tiene una única interpretación.

* Como mínimo, esto requiere que cada característica del producto final se describa utilizando un único termino.
* En los casos en los que un término utilizado en un contexto particular pueda tener múltiples significados, el termino debe incluirse en un glosario donde se especifique su significado.

**Completa.** Un SRS es completo si posee las siguientes cualidades:

* Inclusión de todos los requisitos significativo, ya sean relativos a la funcionalidad, el rendimiento, las limitaciones de diseño, los atributos o las interrelaciones externas.
* Definición de las respuestas de software a todas las clases realizables de datos de entrada en todas las clases realizables de situaciones. Obsérvese que es importante especificar la respuesta a los valores de entrada válidos y no validados.
* Conformidad con cualquier norma del SRS que le sea aplicable. Si una sección particular de la norma no es aplicable, el SRS debe incluir el número de sección y una explicación de porque no es aplicable.

**Verificable.** Un SRS es verificable si, y solo si, todos los requisitos establecidos en el son verificables. Un requisito es verificable si y solo si existe algún proceso finito y rentable con el que una persona o máquina pueda comprobar que el producto de software cumple con el requisito.

* Ejemplos de requisitos no verificables, estas son declaraciones como: **a)**El producto debe funcionar bien, o el producto debe tener una buena interfaz humana. Estos requisitos no pueden verificarse porque es imposible definir los términos bueno o bien. **b)**El programa nunca debe entrar en un bucle infinito. Este requisito no es verificable porque la comprobación de esta cualidad es teóricamente imposible.

**Coherente.** Un buen SRS es consistente si y solo si ningún conjunto de requisitos individuales descritos en ella entra en conflicto. Hay tres tipos de conflictos principales en un SRS:

* Dos o más requisitos pueden describir el mismo objeto del mundo real, pero utilizar termino diferentes para ese objeto. Por ejemplo, la solicitud de una entrada de usuarios por parte de un programa puede denominarse **“prompt”** en un requisito y **“cue”** en otro.
* Las características especificadas de los objetos del mundo real pueden entrar en conflicto. Por ejemplo: **1)**El formato de un informe de salida puede describirse en un requisito como «tabular” pero en otro como “textual” **2)** Un requisito puede establecer que todas las luces deben ser verdes mientras que otro establece que todas las luces deben ser azules. **3)** Puede haber un conflicto lógico o temporal entre dos acciones específicas. Por ejemplo; **a)** Un requisito podría especificar que el programa sumará dos entradas y otro especificar que el programa las multiplicará. **b)** Un requisito puede establecer que A debe seguir a B, mientras que otros requieren que A y B ocurran simultáneamente.

**Modificable.** Un SRS es modificable si su estructura y estilo son tales que cualquier cambio necesario en el requisito puede realizarse de forma fácil, completa y coherente. Los cambios en un SRS generalmente requieren:

* Tener una organización coherente y fácil de usar, con un índice y referencias cruzada explicitas.
* No ser redundante; es decir, el mismo requisito no debe aparecer en otras partes en el SRS.
