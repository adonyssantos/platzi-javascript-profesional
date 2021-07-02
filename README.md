# Curso Profesional de JavaScript

## ¿Qué significa ser un profesional de JavaScript?

El camino para llegar a ser profesional es largo y duro, no es fácil. Todos necesitamos que nos guíen para saber qué hacer y qué no. Este camino es conocido como la ruta de pasar de Junior a Senior, este es un duro camino lleno de experiencia.

## ¿Qué forma a un profesional?

### Lista de cosas que lo forman:

‌- Conocimiento del lenguaje.

- Conocimiento de entornos de programación.
- Mejores prácticas.
- Versado en código.
- Herramientas.
- Ética / Profesionalismo.
- Experiencia.

**El lenguaje: JavaScript**‌

Debemos tener muy claro cuales son los fundamentos de JavaScript antes de comenzar con esto. Existen features muy raros y hay que estudiarlos. Tenemos que saber cómo funcionan las cosas en JavaScript.

‌**No fundamentos**
‌
Los no fundamentos" representan las siguientes características del lenguaje:

- _Promesas_ (nivel pro).
- _Getters_, setters: son formas de obtener valor de una variable sin tener que poner this.name.
- _Proxies:_ es un feature muy raro, pero que más adelante veremos a profundidad. Sirve para interceptar a una función antes de que se ejecute.
- _Generadores:_ esto es raro, pero vamos a ver que sí es eficiente.

**¿Cómo funciona?**
‌
Este lenguaje corre sobre un motor. JavaScript no contiene clases como otros lenguajes de programación, esto es algo que vuela mucho la cabeza, es muy difícil de entender. Otro feature muy cool que vamos a aprender es event loop, es lo que permite que pueda correr muchos procesos a la vez.

**Entornos de programación**
‌
Cuando estamos desarrollando lo hacemos para la WEB, para un celular, para seguidores. Existen diferentes entornos que nos ofrecen APIS, tenemos que conocer todo esto.

‌**Versado en código**‌

Esto quiere decir que tenemos que leer mucho código, un lugar hermoso para ponernos a leer código es GitHub. Debemos leer mucho y hacerlo de forma muy constante.

‌**Mejores prácticas**

No vamos a reinventar la rueda, hay muchas personas que ya han solucionado los problemas más comunes, tenemos que usar estas soluciones, a estas soluciones se les llama: patrones de diseño.

**Ética**‌

Esta es la parte más importante de ser un profesional. Un buen profesional cumple con los siguientes valores:

- Es responsable.
- Entrega a tiempo sus trabajos.
- Sabe decir que no.
- No hace daño.

**Experiencia**
‌
La experiencia no es algo que se pueda enseñar, tenemos que encontrarla nosotros mismos en el camino a ser profesionales. Todo está en nosotros, tenemos que estudiar y practicar mucho.

## ¿Cómo llega un script al navegador?

El **DOM** es la representación que hace el navegador de un documento HTML.

El navegador interpreta el archivo HTML y cuando termina de transformarlo al DOM se dispara el evento DOMContentLoaded lo que significa que todo el documento está disponible para ser manipulado.

_Todo script que carguemos en nuestra página tiene un llamado y una ejecución._

**Tanto con async como defer podemos hacer llamados asíncronos pero tiene sus diferencias:**

`*sync`, Con async podemos hacer la petición de forma asíncrona y no vamos a detener la carga del DOM hasta que se haga la ejecución del código.

`defer`, La petición es igual asíncrona como en el async pero va a diferir la ejecución del Javascript hasta el final de que se cargue todo el documento.

_Hay que tener en cuenta que cuando carga una página y se encuentra un script a ejecutar toda la carga se detiene. Por eso se recomienda agregar tus scripts justo antes de cerrar el body para que todo el documento esté disponible._
