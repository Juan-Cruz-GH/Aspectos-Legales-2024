<h1 align="center">Tema 7 - Licenciamiento de uso</h1>

## Licencia de uso

-   La licencia de uso es el contrato por el cual el titular de un software transfiere a la otra parte, la licenciataria, el uso y goce sobre ese software.
-   Esta licencia no crea derechos ni cambia la titularidad del software.
-   Hay 2 tipos principales de licencias: propietarias y de software libre o no propietarias.

## Licencias propietarias

-   Son las cuales no permiten al licenciatario ver ni modificar el código fuente. Para poder modificar un software se debe necesariamente poseer acceso al código fuente.
-   Pueden ser gratuitas u onerosas.
-   Las gratuitas son por ejemplo el "Freeware".
-   Un ejemplo es Microsoft.

## Licencias no propietarias

-   También conocidas como licencias de Software Libre o de Código Abierto.
-   El licenciatario tiene acceso al código fuente y puede modificar el mismo.
-   No implica dominio público.

## Diferencia entre software libre y código abierto

Aunque a menudo se usan como sinónimos, el software libre y el código abierto tienen diferencias técnicas, filosóficas y legales significativas.

El término "Software Libre" fue acuñado por Richard Stallman en 1986 con el Manifiesto GNU, donde abogaba por un sistema operativo alternativo a Unix y la creación de la licencia GPL. Esta licencia asegura la libertad de los usuarios para ejecutar, copiar, distribuir, estudiar, cambiar y mejorar el software, fundamentándose en la cooperación y la libertad de acceso a la información.

El movimiento del Software Libre enfrenta críticas de sectores económicos que consideran que sus principios van en contra de los derechos de los desarrolladores a obtener beneficios económicos. En respuesta a estas críticas, en 1997 Eric Raymond publicó "La Catedral y el Bazar", un ensayo que compara el desarrollo tradicional de software con el modelo colaborativo utilizado en el desarrollo del kernel de Linux. Raymond sostiene que la libertad de acceso al código fuente mejora la calidad del software y fomenta la participación comunitaria.

Raymond critica la licencia GPL por ser demasiado restrictiva y prefiere el término "código abierto" (open source), que pone más énfasis en aspectos técnicos que en los filosóficos y políticos del Software Libre.

**Así, mientras el Software Libre se enfoca en la libertad de los usuarios y la cooperación, el código abierto resalta la eficiencia y calidad del desarrollo colaborativo.**

## Licencia GPL

-   Es la forma de licenciamiento más popular del mundo.
-   Habilita a los usuarios a las siguientes libertades:
    1. Usar el programa
    2. Estudiar cómo funciona el programa y adaptarlo a las necesidades del usuario
    3. Distribuir copias
    4. Mejorar el programa y hacer públicas las mejoras
-   Formalmente, la GPL se divide en 3 elementos: **preámbulo**, **términos y condiciones**, **apéndice**.
-   El preámbulo funciona como una introducción, y deja en claro las intenciones de los términos **free software y copyleft**. En tal sentido, se explicita que el término free se relaciona con la **libertad** concedida al usuario para distribuir y modificar el programa y **no por el carácter gratuito del mismo**. Al mismo tiempo, establece el concepto de **copyleft**, como aquellas restricciones en cabeza del usuario creadas con el fin de asegurar la libre distribución de los programas licenciados.

### Términos y condiciones

#### 1. Ámbito de aplicación

El ámbito de aplicación de la licencia GPL se debe definir en 2 sentidos: la aceptación y los componentes de cada distribución que la licencia cubre.

La aceptación de la licencia se produce con la distribución del programa, ya sea en forma original o habiendo producido un trabajo derivado del mismo. Los usuarios no se encuentran obligados a aceptar la licencia para los casos en que su interacción con el programa distribuido se limite al uso del mismo o cuando la modificación del mismo no derive en una nueva distribución.

Excepcionalmente, la licencia permite la entrega material del programa a terceros siempre y cuando los mismos actúen por órdenes y en beneficio exclusivo del usuario.

El objeto de la licencia alcanza a todo el programa distribuido, pero excluye a los complementos que, si bien pueden interrelacionarse con el software, no se encuentran incluidos en el mismo en su propio diseño.

#### 2. Distribución del software

La licencia permite distribuir el programa siempre que se cumplan las condiciones establecidas en la misma. Esta distribución puede ser tanto digital como física.

La distribución sin modificaciones del programa original requiere que se cumplan 4 condiciones:

1. Se deje establecido el copyright original del programa, estableciendo los autores del mismo.
2. Se respete la forma de licenciamiento del programa a distribuir, así como las cláusulas adicionales permitidas por la GPL, si las hubiere.
3. Se explicite la inexistencia de garantías establecida por el punto 15 de la licencia.
4. Se acompaña una copia de la licencia junto con el programa.

El distribuidor puede cobrar por la distribución si quiere. La licencia no impone restricciones en cuanto a los montos o formas de pago, siempre que las mismas no limiten la posterior distribución del programa en los términos de la licencia.

La distribución del programa otorga al tercero receptor una licencia por parte de los autores originales del programa, y no del distribuidor.

#### 3. Modificación del software

La licencia permite a los licenciatarios modificar el programa, pero si quiere distribuir esta versión modificada, debe cumplir 3 condiciones:

1. Debe establecerse claramente que el trabajo es una distribución modificada del original, estableciendo la fecha de modificación.
2. Debe notificarse que el trabajo se encuentra distribuido bajo la licencia GPL, y debe explicitarse cualquier término adicional establecido.
3. En el caso de la existencia de interfaces interactivas debe dejarse en claro los términos de licenciamiento en las mismas.

El programa modificado debe distribuirse como un todo bajo la licencia GPL, incluso si el mismo se encuentra compuesto por elementos que se hayan licenciado bajo términos diferentes. Excepcionalmente, y en los casos que los componentes se encuentren distribuidos en una compilación pero manteniendo su independencia funcional, los mismo pueden ser licenciados bajo términos diferentes.

El programa modificado resultante constituye un trabajo derivado del original, en cuanto a propiedad intelectual se refiere. El autor del trabajo modificado obtiene el derecho de autor sobre éste pero no una exclusividad: no impide que otros terceros realicen sobre el trabajo original nuevas obras derivadas.

#### 4. Acceso al código fuente

La licencia define al código fuente como las instrucciones necesarias para generar, instalar y ejecutar el código objeto de un programa, pero no incluye librerías del sistema ni utilidades externas al programa que no hayan sido modificadas por el mismo.

La licencia establece además que una librería se considera parte del trabajo derivado solo si el programa está diseñado específicamente para funcionar con ella.

El código fuente debe estar disponible en los casos de distribución del ejecutable. En los casos de transmisiones de copias individuales, las mismas deben en principio acompañar el código fuente. Excepcionalmente y solo con fines no comerciales, es posible acompañar el código objeto con una oferta escrita de proporcionar el fuente correspondiente.

En los casos de distribución digital, el acceso al fuente puede hacerse en el mismo servidor o uno distinto, siempre y cuando las condiciones de acceso sean similares a las utilizadas para distribución.

##### 5. Copyleft

El copyleft es definido por la (Free Software Foundation) como el **método de lograr que un programa sea libre, requiriendo que todas sus distribuciones y trabajos derivados mantengan tal carácter.**

Un programa sujeto a Copyleft no puede modificarse ni distribuirse a menos que se haga bajo los términos y condiciones de la GPL, y cualquier modificación a los términos autorizados por esta última extinguirá los derechos surgidos de la licencia.

La existencia del copyleft marca la diferencia entre los programas que se encuentran en el dominio público y aquellos sometidos a la licencia de software libre. En estos últimos siguen persistiendo los derechos de autor, que quedan en manos del licenciatario original, quien renuncia a los derechos de explotación económica exclusiva de lo creado, sujeto a la condición que los trabajos derivados realicen una similar resignación.

Por lo tanto la vulneración de alguna de las cláusulas mencionadas, como ser el acto de añadir nuevas restricciones no previstas, conlleva la revocación de la autorización conferida, la que deja de ampararle al licenciatario y su trabajo derivado, el cual entonces resulta violatorio de los derechos del autor del trabajo original.

##### 6. Cláusulas adicionales

La versión 3 de la GPL agregó varias cláusulas nuevas. Su objetivo es impedir la creación de otras restricciones distintas a las establecidas por la licencia. Dicha enumeración tiene un carácter restrictivo, por lo que solo se permiten las siguientes estipulaciones:

1. Establecer garantías diferentes a las establecidas en el punto 15 de la licencia.
2. Requerir la preservación de los avisos legales o de autoría contenidos en el programa.
3. Solicitar que las diferencias respecto a la versión original sean señaladas de forma apropiada en las versiones modificadas
4. Limitar el uso de los nombres de los autores originales o licenciatarios para fines publicitarios.
5. Negarse a otorgar derechos afectados por la legislación de marcas comerciales.
6. Prever la indemnización de los autores o licenciatarios por las distribuciones del programa por parte de terceros que incluyan cláusulas contractuales que impliquen responsabilidad para los primeros.

##### 7. Patentes de software

La patente es un mecanismo de protección otorgado por el estado a un particular autor de una innovación tecnológica, por el cual se concede un derecho a la exclusividad a la explotación por un tiempo finito, a cambio de la publicidad de la misma.

La patente otorgada no protege el progama de computadora en si, sino el método tendiente a la obtención del resultado, por ejemplo, la forma de compresión de los datos en un archivo de video. Consecuencia de ello, la posibilidad de un software alternativo que cumpla la misma funcionalidad sin recaer en la ingeniería inversa, seria igualmente violatoria de la patente otorgada, toda vez que realizaría el mismo proceso, con prescindencia de que se haya o no apropiado del código fuente.

La aceptación de las patentes de software ha sido en los últimos años objeto de una fuerte polémica, no solo en los países que las han admitido sino incluso en aquellos en los que no. La mayoría de las objeciones se fundamentan en la concentración de las licencias en cabeza de las grandes corporaciones, en detrimento de las Pymes y programadores independientes, los que se verían impedidos de ingresar en el mercado, debido a los costos derivados del licenciamiento y los posibles riesgos judiciales.

La GPL versión 3, respecto a esto, establece una cesión de la patente expresa por parte de los licenciatarios. Significa que si un developer distribuye un programa bajo los términos de la licencia, otorga a los receptores una licencia no exclusiva de todas las patentes que, respecto al programa, pudiera ser titular.

En el mismo sentido, y en los casos en que el distribuidor haya celebrado un convenio de utilización de patentes que sean titularidad de un tercero deberá extender dicho beneficio a los usuarios posteriores o abstenerse de distribuir el trabajo derivado.

##### 8. Gestión de Derechos Digitales (DRM) y licencias GPL versión 3

Se denomina gestión de derechos digitales o DRM al conjunto de tecnologías que permiten restringir el uso de medios o contenidos digitales a aquellas actividades permitidas expresamente por el titular del copyright. Estas tecnologías pueden estar incluidas en el contenido mismo, en el OS, o incluso en el hardware usado para su reproducción.

Los DRM usan 2 métodos:

1. Aplicar un algoritmo criptográfico al contenido, evitando que los usuarios no autorizados accedan al mismo.
2. Aplicar un "sello de agua" al archivo de forma tal de poder comunicar al hardware que el contenido está protegido.

Ambos métodos son susceptibles al hacking.

La versión 3 de la GPL regula los DRM: la distribución de un software bajo esta licencia implica la renuncia a la persecución de la elusión de los métodos de control de contenido establecidos en el software licenciado.

##### 9. Compatibilidad con otras licencias GPL

La licencia GPL 3 no esta diseñada para reemplazar a las versiones anteriores, por lo que los distribuidores pueden optar por licenciar su código mediante la versión que quieran.

La mayoría de los programas licenciados bajo la versión 2 permiten a los usuarios la posibilidad de modificar los términos de licenciamiento, adoptando la versión 3 de así considerarlo conveniente. Sin embargo es de hacer notar que algunos proyectos limitan esta opción, obligando a permanecer bajo la licencia del año 1991. El caso más notable es el kernel Linux, cuyo autor, Linus Torvalds ha sido particularmente crítico de la nueva versión. Circunstancias ha llevado al fenómeno de que un mismo sistema operativo se encuentre distribuido mediante dos versiones diferentes de la misma licencia.

#### Otras licencias GPL

Además de la GPL, la Free Software Fundation promueve otras dos licencias: La denominada Lesser General Public License (LGPL) y la Affero General Public License (AGPL).

Las librerías dinámicas son archivos que contienen código que a menudo es usado por más de un programa simultáneamente, los cuales se limitan a llamar a las funciones de las mismas, sin incorporarlas a su texto.

La LGPL permite la distribución tanto de este tipo de librerías como del programa principal bajo términos independientes. Es decir, permite la distribución de un trabajo combinado que incluya librerías licenciadas con una licencia distinta a la del programa principal, siempre y cuando se cumplan las siguientes condiciones:

1. Se deje constancia de la existencia de las librerías y su forma de licenciamiento. Esta noticia debe repetirse en la interfaz de usuario en el caso de que la misma incluya notas de copyright.
2. Acompañar la distribución con una copia de la licencia así como de la GPL.

La AGPL es una licencia destinada a licenciar los programas que usan una estructura Cliente-Servidor. Es similar a GPL-3, con la inclusión de un párrafo que establece el derecho de los usuarios que interactúen mediante una red con el programa licenciado de obtener una copia del código fuente del mismo, la que debe ser puesta a disposición en un servidor libre de cargo alguno.

## Open Software Initiative: Programa de Certificación y Condiciones

A diferencia de los propulsores del software libre, los miembros de la Open Source Initiative no promueven una licencia única sino un programa de certificación de licencias de terceros, las cuales deben cumplir estos criterios:

1. Libre redistribución: la licencia no debe impedir a nadie la venta o entrega del software ni requerir derechos de autor u otros pagos por tal venta;
2. Código fuente: el programa debe incluir el código fuente, y la licencia permitir la distribución del programa tanto en su versión fuente como en su forma compilada;
3. Obras derivadas: la licencia debe permitir la realización de modificaciones u obras derivadas y su distribución bajo los mismos términos de la licencia original;
4. Integridad del código fuente del autor: la licencia puede impedir que el código fuente sea distribuido en su versión modificada sólo si permite la distribución de los “parches” (patch files) con el código fuente, con el propósito de modificar el programa en tiempo de construcción. Debe permitir la distribución de software sobre la base de código fuente modificado y puede exigir que las obras derivadas lleven un nombre o número de versión distinto al programa original;
5. No discriminación contra persona o grupos de personas;
6. No discriminación contra campos de aplicación: la licencia no puede, por ejemplo, impedir el uso del programa en negocios;
7. Distribución de la licencia: las facultades concedidas deben ser aplicadas a todas las personas a quienes se redistribuya el programa, sin necesidad de obtener una licencia adicional;
8. No especificidad de la licencia con relación a un producto: los derechos aplicados a un programa no deben depender de la distribución particular de software de la que forma parte;
9. No restricción de la licencia con relación a otro software: la licencia no debe imponer restricciones sobre otro software que es distribuido junto con el licenciado. Por ejemplo, la licencia no debe insistir en que todos los demás programas distribuidos en el mismo medio deben ser software de fuente abierta;
10. Neutralidad tecnológica de la licencia: ninguna de sus estipulaciones puede estar basada en un tipo de tecnología determinado o estilo de interfaz.

Una diferencia sustancial con la licencia GPL es la ausencia de Copyleft. En tal sentido, ni las condiciones de certificación ni ninguna de las licencias mencionadas en el párrafo anterior prohíbe al autor de un trabajo modificado la distribución del software bajo una licencia que establezca mayores restricciones, habilitando por tanto la posibilidad de comercializar el producto resultante como software propietario.

## Contratos Conexos: El contrato de mantenimiento y escrow de código fuente

En proyectos informáticos, se firman múltiples contratos para una única operación comercial, esto se conoce como contratos conexos.

Luego de un contrato de software o licencia de uso, es habitual que se celebre un contrato adicional, el de mantenimiento. Esto se debe a la complejidad de los sistemas y los múltiples riesgos (interrupciones, intrusiones no autorizadas, etc).

El contrato de escrow de código fuente surge para resolver el problema de dependencia del usuario con el proveedor propietario del código fuente. El dev entrega el fuente a un tercero **depositario**, quien lo custodia y lo entrega bajo condiciones específicas.

---

<h1 align="center">Tema 8 - Derecho de Internet</h1>

## La Internet

### Introducción

La Internet es una libre asociación de miles de redes y millones de computadoras alrededor del mundo que trabajan juntas para compartir información.

Originalmente el esquema usado por las redes informáticas era el de Mainframe, donde una computadora central alimentaba a las distintas terminales "tontas" que no podrían funcionar sin que el Mainframe les diga qué hacer. Debido a que este esquema posee un **_single point of failure_** se volvió obsoleto.

El esquema Mainframe fue reemplazado, en la Internet, por uno basado en una red descentralizada: cada uno de los nodos de la red actúa como un servidor y la información no está contenida toda en un solo lugar; y redundante: las conexiones entre los distintos elementos no son únicos si no que pueden ser reemplazados por otras rutas de conexión, y por ende la caída de uno o más servidores no impide necesariamente el acceso a la información.

### Internet vs World Wide Web

La Internet constituye una red global de computadoras de carácter descentralizado. La WWW, en cambio, es un subconjunto de la Internet que involucra a todos los documentos que trabajan utilizando HTTP.

## Efectos jurídicos de la Internet

### Introducción

Inicialmente, la Internet era un lugar basado en un modelo de cooperación e intercambio de información entre los distintos usuarios de la red, y era ausente de derecho. Sin embargo, esto cambió a través del tiempo y hoy en día hay infinidad de efectos jurídicos que se producen en Internet.

### Control sobre Internet: la Sociedad de Internet

La Sociedad de Internet es una organización no gubernamental, sin nacionalidad definida, sin fines de lucro y formada por organizaciones de 165 países. Se ocupa de elaborar políticas y prácticas para ser adoptadas en la red y supervisar el trabajo de las organizaciones, grupos de tareas, que trabjan en las decisiones políticas de la red.

Algunas de las organizaciones que forman parte de la Sociedad son:

1. IAB: Junta de Arquitectura de Internet
    1. IANA: Autoridad de Asignación de Numeros de Internet
    2. IEFT: Grupo de trabajo de Ingeniería de Internet
    3. IESG: Grupo de dirección de Ingeniería de Internet
2. IRFT: Grupo de Trabajo de Investigación de Internet
3. ISTF: Grupo de Trabajo Social de Internet

### Problema de la jurisdicción en Internet

Internet facilita el libre intercambio de información a nivel mundial. Sin embargo, la irrupción de emprendimientos comerciales y la masificación de la World Wide Web han generado una serie de problemas relacionados con actos ilícitos e incumplimientos contractuales en el entorno digital. Cualquier acto jurídico realizado en la red **puede involucrar a participantes ubicados en diferentes países**, y los servidores donde se realiza la interacción pueden estar situados en lugares distintos, lo que complica la determinación de la legislación y las leyes que deberían aplicarse.

Es común que los contratos celebrados por Internet incluyan cláusulas que definan la jurisdicción y la normativa aplicable. Sin embargo, estos contratos suelen ser de **adhesión**, lo que conlleva el riesgo de ser considerados nulos si se percibe un beneficio injustificado para una de las partes. Además, esta solución no aborda adecuadamente los casos de actos ilícitos. Por otro lado, considerar el domicilio del servidor para determinar la jurisdicción presenta problemas, como la posibilidad de crear "servidores de conveniencia" que trasladan la jurisdicción a territorios más favorables para el prestador del servicio.

Otorgar la jurisdicción al territorio del reclamante también tiene sus inconvenientes, ya que somete a empresas y particulares a riesgos de enfrentarse a regímenes jurídicos diversos sin posibilidad de control. En Argentina, los conflictos relacionados con Internet han sido mayormente sobre la titularidad de nombres de dominio, sin llegar a sentencias definitivas. En Estados Unidos, los tribunales han desarrollado la doctrina del "**Long Arm**" para abordar estos problemas, aunque no se ha alcanzado una solución definitiva.

La doctrina del "Long Arm" permite ejercer jurisdicción personal sobre no residentes que cometan actos delictivos fuera del estado causando daños dentro del estado. Un ejemplo ilustrativo es el caso "American Network Inc. C/Access America", donde un proveedor de Internet de Nueva York demandó a otro de Georgia por violación de marca. El tribunal de Nueva York aceptó la jurisdicción basándose en que el daño fue previsible y el demandado obtuvo beneficios de sus actividades en Nueva York. La regla del "Long Arm" establece que la Corte puede ejercer jurisdicción personal sobre cualquier no residente que cause daños dentro del estado si es previsible y obtiene un beneficio sustancial del comercio interestatal o internacional.

## Responsabilidad civil en Internet

### Introducción

Entre el emisor de un mensaje en internet y su receptor podemos encontrar muchos sujetos jurídicos intermediarios. Debido a esto, cuando existe algun problema legal, hay inconvenientes a la hora de determinar el grado y naturaleza de la responsabilidad de los intervinientes en el hecho. A continuación se analizan los distintos intervinientes en el proceso de envío y su responsabilidad.

### Proveedores de acceso a Internet

Los proveedores de acceso son los sujetos jurídicos que prestan la infraestructura técnica para que los proveedores del servicio de Internet ofrezcan su servicio.

En razón de su función, los proveedores **carecen de control y acceso a los contenidos que circulan por la web, por lo que no podría reputárselos responsables civiles de los mismos**. En este sentido, Pablo Bolotnikoff los asimila a las empresas prestatarias del servicio telefónico, ya que no tienen la culpa si se comete un crimen por medio de un teléfono.

### Servicios de Caching

El servicio de caching almacena en forma automática, provisional y temporaria cierta información con el único fin de que sea más eficaz la transmisión de la misma en pedidos subsecuentes.

**En principio carecen de control sobre el contenido de almacenado, por lo que se les debe eximir de responsabilidad**. Este es el principio establecido por artículo 13 de la Directiva Europea de Comercio Electrónico 200/31:

`Los Estados miembros garantizarán que, cuando se preste un servicio de la sociedad de la información consistente en transmitir por una red de comunicaciones datos facilitados por el destinatario del servicio, el prestador del servicio no pueda ser considerado responsable del almacenamiento automático, provisional y temporal de esta información, realizado con la única finalidad de hacer más eficaz la transmisión ulterior de la información a otros destinatarios del servicio`

Sin embargo, es posible que el proveedor de caching tenga acceso al contenido o capacidad para controlarlo o modificarlo. **En tales casos la eximente de responsabilidad desaparece**, criterio sustentado por las excepciones contendidas en la segunda parte del art. 13 de la directiva 2000/31.

### Proveedor de contenido

Un proveedor de contenido es alguien que pone archivos en la web para que los usuarios puedan acceder a ellos. Hay dos tipos de proveedores de contenido: los que crean su propio contenido y los que enlazan a contenido de otros. La responsabilidad del proveedor es clara cuando crean su propio contenido, ya que son los autores. Pero, cuando enlazan a contenido de otros, la cosa se complica.

Los proveedores pueden referir a material de terceros a través de hyperlinks que llevan a otras páginas web. Esas páginas, a su vez, pueden tener más links a otros sitios, creando una cadena de referencias. Así, hay contenido indirecto de primer nivel (el acceso directo desde la página original) y de segundo nivel (acceso desde la página enlazada).

En cuanto a la responsabilidad, los proveedores de contenido deben responder por los contenidos de primer nivel. Aunque no sean los autores, voluntariamente vinculan su sitio a ese contenido, permitiendo que otros accedan a él. Sin embargo, responsabilizarlos por contenidos de segundo nivel parece excesivo, ya que no tienen control o conocimiento directo sobre ellos.

### Proveedores de servicio de Internet

Un proveedor de servicio de Internet (ISP) es una entidad que permite a los usuarios acceder a Internet y, a menudo, ofrece servicios de hosting, lo que permite a los usuarios publicar contenido en la web. Es importante entender la naturaleza legal de esta actividad porque existen diferentes opiniones sobre la responsabilidad de los ISP por el contenido ilegal que a menudo se distribuye a través de sus servicios.

Una opinión sostiene que los ISP son como editores, ya que proporcionan el soporte necesario para que los autores publiquen contenido y tienen influencia en su producción. **Según esta visión, los ISP serían directamente responsables del contenido que publican**, al igual que los editores.

Otra perspectiva compara a los ISP con los dueños de librerías, señalando que es imposible controlar toda la información que los usuarios suben a los servidores. Esta última postura es la que prevalece en el derecho comparado. Por ejemplo, la Directiva Europea 2000/31 establece que los proveedores de hosting **no son responsables mientras no tengan conocimiento efectivo de actividad ilegal**. De manera similar, la Communications Decency Act de Estados Unidos **otorga inmunidad a los proveedores de hosting** en su sección 230, negando que sean considerados editores.

**Los tribunales han determinado que los ISP solo son responsables si, sabiendo de la actividad ilegal, no toman las medidas necesarias para detenerla**. Por ejemplo, la Corte Suprema del Estado de Nueva York encontró culpable a BUFFNET, un ISP en Búfalo, por no actuar tras ser notificado de que uno de sus newsgroups distribuía p**\***grafía infantil. Además, en el caso Fair Housing Council Of San Fernando Valley v Roommates.com, una corte federal de apelaciones responsabilizó a un sitio web por el contenido subido por sus usuarios, considerando que el sitio asumía el rol de editor y debía responder por los daños causados por la actividad ilegal de sus usuarios.

### Situación en Argentina: caso Jujuy.com

El primer antecedente de responsabilidad de un ISP fue dictado por Camara en lo Civil y Comercial de la provincia de Jujuy cuando la empresa Jujuy digital operaba el dominio Jujuy.com, en cuyo foro se publicó en forma anónima un mensaje respecto de la supuesta infidelidad de los actores. Este mensaje fue retirado luego de que el sitio recibiera intimación por carta documento, circunstancia que fue considerada un conducta omisiva por el tribunal y un reconocimiento de la actividad ilícita.

En sus considerandos el tribunal entendió que una vez demostrada la existencia del daño, la responsabilidad surgía en forma clara de la aplicación del art. 1113 del código civil. En esta inteligencia sostiene la analogía con la energía en cuanto al material riesgoso, considerando procedente la responsabilidad objetivo de los codemandados por los daños producidos.

El fallo merece una serie de críticas:

1. La aplicación de los criterios de responsabilidad objetiva aparecen apartados de la legislación y jurisprudencia comparada, creando un posible riesgo jurídico para las empresas que prestan servicios de hosting o simplemente permiten a los usuarios expresar una opinión.
2. La analogía utilizada no aparece como la más feliz. El análisis realizado establece un doble estándar de responsabilidad según si el mensaje fue realizado mediante un medio tradicional o vía web, ignorando el hecho que el daño se produce por la existencia del mensaje y no por la utilización de la herramienta informática.

### Caso Belén Rodriguez

El caso de Belén Rodríguez en Argentina estableció un precedente importante en cuanto a la responsabilidad de los buscadores de Internet. Los buscadores, como Google, pueden ser considerados responsables por la indexación y difusión de contenidos que resulten lesivos a la privacidad y honor de las personas.

Factores de Imputación: En la doctrina, hay dos enfoques principales sobre la responsabilidad de los buscadores:

-   Imputación Objetiva: Basada en el riesgo creado por el buscador al indexar y difundir contenidos. Este enfoque podría implicar una responsabilidad más estricta para los buscadores, independientemente de su intención o negligencia.
-   Responsabilidad Subjetiva: Basada en la negligencia del buscador en controlar o actuar sobre los contenidos lesivos. Este enfoque requiere demostrar que el buscador actuó de manera negligente al no remover contenidos perjudiciales tras recibir una solicitud.

Los buscadores tienen la obligación de actuar con diligencia para eliminar enlaces a contenidos dañinos, **especialmente cuando reciben una solicitud formal y específica de la persona afectada**. Este caso subraya la necesidad de que los buscadores equilibren el derecho a la libertad de expresión con la protección de la privacidad y el honor de las personas, actuando con rapidez para remover contenidos perjudiciales.

Además, este caso ha impulsado el debate sobre la regulación de la responsabilidad de intermediarios en el ámbito digital y ha sentado un precedente legal en Argentina para futuros casos similares.

## Firma digital

### Concepto

La firma digital es un método avanzado de autenticación que permite verificar la autoría e integridad de un documento digital. En el contexto del derecho, asegura la identidad del firmante y la inalterabilidad del mensaje, algo que tradicionalmente se lograba con la firma manuscrita.

### Aspectos técnicos

La firma digital utiliza métodos criptográficos para garantizar la autenticidad y seguridad de los documentos electrónicos. Los métodos técnicos más comunes para la autenticación de documentos digitales son:

1. **Código de ingreso (PIN)**: Un número de identificación personal utilizado junto con una tarjeta magnetizada.
2. **Métodos biométricos**: Utilizan características físicas únicas, como huellas digitales, retina o reconocimiento de voz, para identificar a una persona.
3. **Métodos criptográficos**: Utilizan algoritmos matemáticos para cifrar y descifrar mensajes, asegurando la identidad del remitente y la integridad del mensaje.

#### Criptografía

La criptografía es fundamental para la firma digital. A través de algoritmos matemáticos, permite cifrar un mensaje con una clave privada que solo el remitente conoce. Este mensaje cifrado puede ser verificado por el receptor utilizando la clave pública del remitente. Este proceso asegura que solo el poseedor de la clave privada pudo haber enviado el mensaje. Existen 2 tipos de criptografía:

1. **Criptografía simétrica**: Utiliza una sola clave para cifrar y descifrar el mensaje. Es menos segura porque la clave debe ser compartida entre emisor y receptor.
2. **Criptografía asimétrica**: Utiliza un par de claves, una pública y otra privada. La clave pública puede ser distribuida libremente, mientras que la privada se mantiene en secreto. Este método es más seguro porque no requiere que las claves se compartan.

#### Algoritmo de hash

El algoritmo de hash produce un número único a partir de un mensaje. Cualquier cambio en el mensaje resulta en un número de hash diferente, lo que permite detectar alteraciones. El hash se cifra con la clave privada del emisor y se envía junto con el mensaje. El receptor puede recalcular el hash del mensaje recibido y compararlo con el hash cifrado para verificar la integridad del mensaje.

### Firma digital en el ordenamiento argentino

En Argentina, la ley 25.506 regula la firma digital y electrónica. Define la firma digital como:

`Resultado de aplicar un procedimiento matemático a un documento digital que requiere información exclusiva del firmante y que está bajo su control absoluto.`

La firma digital debe ser verificable por terceros y debe permitir identificar al firmante y detectar cualquier alteración posterior al documento.

### Firma electrónica

La ley 25.506 también define la firma electrónica como un conjunto de datos electrónicos que identifican al firmante pero no cumplen todos los requisitos para ser considerados firma digital. La firma electrónica es menos segura que la firma digital, pero aún así puede ser utilizada para identificar a una persona en un mensaje electrónico.

### Validez jurídica

El artículo 3 de la ley 25.506 equipara la firma digital a la manuscrita en cuanto a su validez jurídica. Esto significa que cualquier documento firmado digitalmente tiene la misma validez legal que un documento firmado a mano, siempre y cuando se cumplan los requisitos establecidos por la ley.

### Documento digital

La ley define el documento digital como la representación digital de actos o hechos, independientemente del soporte utilizado para su fijación, almacenamiento o archivo. Los documentos digitales pueden ser considerados pruebas documentales siempre que su conservación y lectura sean accesibles y se pueda establecer su origen, destino, fecha y hora de recepción.

### Certificado digital

Es un documento digital emitido por un certificador licenciado que vincula los datos de verificación de firma a su titular. Es esencial para garantizar la identidad del remitente y la validez del mensaje. Los certificadores deben cumplir con una serie de requisitos y procedimientos para emitir y controlar certificados digitales, asegurando así la confianza en las firmas digitales.

### Certificadores licenciados

Son entidades autorizadas para emitir certificados digitales. Deben cumplir con los requisitos legales y técnicos establecidos por la ley y obtener una licencia para operar. Estos certificadores tienen la responsabilidad de emitir, controlar y, en caso necesario, revocar los certificados digitales.

### Conclusión

**La firma digital es una herramienta poderosa que asegura la autenticidad y la integridad de los documentos electrónicos, ofreciendo una alternativa segura a la firma manuscrita en el entorno digital. La legislación argentina, a través de la ley 25.506, establece un marco legal claro y detallado para su uso, diferenciando entre firma digital y firma electrónica y regulando los procedimientos para la emisión y control de certificados digitales.**

## Comercio electrónico

### Introducción

El Ministerio de Economía de la Nación, define al comercio electrónico como:

`Conjunto de transacciones comerciales y financieras realizadas por medios electrónicos. Esto es el procesamiento y la transmisión electrónica de datos, incluyendo texto, sonido e imagen.`

En función de la definición se incluirían dentro del concepto no solo las transacciones comerciales sino también cualquier negocio jurídico como la publicidad, edición o cualquier otro servicio.

Otros autores entienden que el concepto debe restringirse a aquellas hipótesis en donde las transacciones económicas se producen mediante la utilización de redes de computadoras abiertas o cerradas. En tal sentido, Luz Clara define al comercio electrónico como:

`Cualquier forma de transacción o intercambio de información comercial, basada en la transmisión de datos sobre redes de comunicación como Internet`

Por último, es posible restringir el concepto de comercio electrónico a **las operaciones comerciales llevadas a cabo mediante la Internet**.

### Contratos electrónicos

El contrato informático puede ser definido como todo contrato en el que la oferta y la aceptación se transmiten por medio de equipos electrónicos de tratamiento y almacenamiento de datos, conectados a una red de telecomunicaciones.

Estos contratos se pueden clasificar:

1. **Según los sujetos intervinientes**: business to business vs business to consumer
2. **Según el tracto contractual**: el contrato se lleva a cabo 100% por Internet vs mayoritariamente por Internet pero en ciertas etapas de forma presencial
3. **Según la forma de manifestación de voluntad**: simultaneidad en las oferta y la aceptación vs éstas se encuentran separadas por un período de tiempo.

### Competencia internacional y cláusulas de prórroga de competencia

La contratación electrónica plantea desafíos en la determinación de la competencia jurisdiccional para resolver conflictos contractuales. Este tipo de relación, establecida a través de medios electrónicos, no solo enfrenta el problema de la distancia física entre las partes, sino también la separación causada por la red distribuida que gestiona la expresión de voluntad en los servidores.

En cuanto a la jurisdicción en los contratos electrónicos, es común incluir cláusulas que favorecen a un tribunal específico, generalmente el del domicilio de la parte que estableció los términos del acuerdo. Sin embargo, si esto deja a la otra parte en desventaja legal, la cláusula puede ser considerada inválida en Argentina. La jurisprudencia argentina ha sido amplia en cuanto a aceptar la jurisdicción nacional en contratos internacionales, permitiendo que cualquier lugar donde se cumplan las obligaciones en Argentina sea suficiente para establecer la jurisdicción.

En cuanto a la ley aplicable, se usa el principio de autonomía de la voluntad, pero con excepciones importantes como fraude, orden público internacional y la protección de partes más débiles. Si no se establece una ley aplicable, se recurren a normas supletorias, como el lugar de cumplimiento del contrato o el lugar de celebración del contrato si no se puede determinar lo anterior.

La prórroga de competencia a favor de un tribunal específico es común, pero puede ser impugnada si se demuestra un abuso de poder por parte de la parte que redactó el acuerdo. Si no se acuerda una prórroga o si es declarada nula, la demanda puede ser presentada en Argentina si el deudor tiene domicilio en el país o si el contrato debe cumplirse en Argentina.

### Derecho comparado

En términos de derecho comparado, en algunos países como Estados Unidos y Canadá, los tribunales pueden rechazar la ley elegida por las partes si no tiene una relación razonable con el contrato. Esto refleja una tendencia a proteger a las partes más débiles y evitar fraudes​.

### Manifestación de volunta

Existen 2 formas principales de manifestación de voluntad en un contrato electrónico:

**Los Click and Warp Agreements**: la aceptación se realiza mediante un cuadro de diálogo donde el usuario debe aceptar los términos explícitamente y de forma user-friendly antes de acceder al servicio. La validez de estos acuerdos depende del conocimiento real del usuario sobre el contenido del contrato. Casos judiciales en EE.UU. han validado estos acuerdos si se demuestra que los usuarios pudieron leer los términos antes de aceptar​.

**Los Internet/Browser Agreements**: no es necesario una aceptación expresa, y la mera utilización del servicio implica la aceptación de los términos. Sin embargo, la legalidad de estos acuerdos es debatida, ya que los usuarios a menudo no leen los términos y condiciones antes de utilizar el servicio.

### Medios de pago

Los medios de pago electrónicos incluyen cualquier método que utilice una red de computadoras para realizar pagos. Aunque es posible realizar pagos tradicionales, estos son engorrosos para transacciones en línea.

Las tarjetas de crédito son comunes, pero presentan riesgos de seguridad y problemas de acreditación de pagos. Para solucionar estos problemas, se utilizan sistemas de seguridad como SSL y SET, que cifran las comunicaciones y protegen los datos financieros de los usuarios.

También es común hoy en día utilizar criptoactivos, que son una red autónoma basada en criptografía respaldada por consenso, pero sin respaldo real en ningún banco. Involucran anonimato y en ciertos casos lavado de dinero.

---

<h1 align="center">Tema 9 - Bancos de datos</h1>

## Regimen legal de los bancos de datos

### Concepto

Un dato es aquella porción de información destinada a su transmisión a los terceros. Además del papel, un dato se puede expresar mediante audio, video o información digital.

La digitalización de los bancos de datos mediante tecnologías informáticas permite no solo **el acceso de la propiedad de un banco de datos a personas que anteriormente no podían ser titulares de una**, sino, y lo que es más importante, **la explotación en forma económicamente rentable de dicha información**.

### Privacidad (artículo 19)

La Constitución Nacional de Argentina refleja el principio de privacidad en el artículo 19, que dice que `las acciones privadas de las personas están exentas de la autoridad del Estado, siempre que no perjudiquen a terceros ni ofendan la moral pública.` Este artículo busca limitar la intervención del Estado en la vida privada.

La Corte Suprema de Argentina ha interpretado este artículo en diversos casos:

1. Caso Bazterrica (1986): La Corte declaró inconstitucional la penalización del consumo personal de drogas en público, afirmando que no perjudicaba a terceros.
2. Caso Montalvo (1990): La Corte cambió su postura y penalizó el consumo de drogas en público, argumentando que el mero ejemplo podía dañar a terceros.
3. Caso Ponzetti de Balbin (1984): La Corte protegió la privacidad del líder político Ricardo Balbin al condenar la publicación de fotografías de sus últimos momentos de vida. Este caso amplió la protección del artículo 19 a acciones de particulares, no solo del Estado.

### Artículo 1071 bis

Este artículo protege contra la intromisión arbitraria en la vida privada, permitiendo acciones legales contra publicaciones no consentidas de imágenes, correspondencia, costumbres, etc.

### Habeas Data

La reforma constitucional de 1994 introdujo el "habeas data" en el artículo 43. Esta garantía permite a cualquier persona conocer, corregir o eliminar datos personales en registros públicos o privados destinados a proveer informes. Se diferencia del amparo en que no requiere el agotamiento de otros recursos legales previamente.

### Ley 25.326 de Protección de Datos Personales

-   La ley protege los datos personales en archivos, registros, bancos de datos, tanto públicos como privados, destinados a proveer informes.
-   Se refiere a cualquier actividad realizada sobre estos datos para evitar daños por mal uso de la información.
-   Incluye definiciones amplias y tecnológicamente neutrales para abarcar cualquier medio de almacenamiento y recuperación de datos.
-   Las Bases de datos de uso particular, periodísticas, datos disociados (imposibles de identificar), y ciertas bases de datos reguladas por leyes específicas están exentas de la ley.
-   La ley define al responsable del banco de datos como el titular del archivo o base de datos, aunque también considera a usuarios y cesionarios de datos como responsables.
-   Usuarios son personas o entidades que tratan datos a su arbitrio, como empresas tercerizadas. Cesionarios son terceros que reciben los datos del titular y son solidariamente responsables por los daños.
-   El beneficiario es el titular de los datos personales.
-   Aunque no se considera una relación de propiedad sobre los datos, la ley protege varios aspectos de la persona, incluyendo su nombre, identidad, imagen y prestigio.
-   El bien jurídico protegido es:
    -   Derecho de las personas a controlar la información sobre ellos mismos.
    -   La intimidad, la identidad, la imagen personal y el prestigio, con contenido económico y no solo la privacidad tradicional.

Los datos personales son información sobre personas físicas o jurídicas. Excluye datos meteorológicos o cosas que no tengan referencias a personas. Los datos personales se clasifican en 3 tipos:

1. **Datos de acceso público/datos mínimos de identificación**: son datos que no requieren consentimiento. Por ejemplo DNI, nombre, apellido, ocupación, etc.
2. **Datos de acceso restringido**: son datos que necesitan cumplir con los principios que establece la ley. Por ejemplo número de telefono o dirección de la propiedad.
3. **Datos sensibles**: son datos íntimos que pueden generar discriminación, por ende se prohibe su recopilación excepto ciertas excepciones que involucren el consentimiento. Por ejemplo origen racial, sexualidad, opiniones políticas, etc.

Los datos sensibles pueden ser recabados en ciertos casos especiales:

1. Registros policiales o de inteligencia.
2. Iglesias, partidos políticos, asociaciones sindicales.
3. Datos disociados (anónimos) con fines estadísticos.
4. Profesionales de la salud con restricciones legales y éticas.

### Principios generales de recolección y tratamiento de la información

#### Principio de licitud

La ley de bases de datos establece que la recolección de datos debe ser legal y justa. No se pueden usar métodos desleales o fraudulentos para recolectar datos. Además, los datos no pueden ser tratados sin el **consentimiento** expreso e informado del titular. Es obligatorio no solo pedir este consentimiento, sino también informar a los titulares sobre **cómo se tratarán sus datos**, incluyendo detalles sobre la base de datos, el propósito de la recolección y si los datos se compartirán con terceros.

#### Principio de calidad

El responsable de una base de datos debe asegurarse de que la información almacenada sea adecuada, actualizada y completa según los objetivos de la base de datos. Los datos deben ser **precisos y actualizados**, y es responsabilidad del titular de la base **corregir cualquier dato falso o desactualizado**. Además, los datos deben protegerse para que terceros puedan verificar el cumplimiento de las obligaciones legales.

#### Principio de pertinencia

La recolección de datos debe ser relevante y adecuada para el propósito declarado. **No se puede usar la información recolectada para fines diferentes a los expresados inicialmente**. Este principio está vinculado al requisito del consentimiento informado. La información proporcionada al titular de los datos debe ser vinculante para el recolector, es decir, **no se puede cambiar el propósito del uso de los datos después de haber sido recolectados**. La ley establece que los datos recolectados no pueden ser utilizados para fines diferentes a los que motivaron su obtención.

#### Principio de confidencialidad

El principio de confidencialidad obliga a mantener en **secreto** la información contenida en la base de datos, incluso aquella que se recibe durante el tratamiento documental. Todos los que participan en la explotación de los datos, independientemente de su función, deben mantener la confidencialidad si han tenido acceso a los datos. Sin embargo, este principio tiene **excepciones, como cuando hay una autorización judicial o razones de seguridad pública, defensa nacional o salud pública.**

#### Consentimiento

La ley regula el consentimiento tanto para el tratamiento de los datos como para su cesión. Es obligatorio obtener el **consentimiento del titular de los datos, el cual debe ser libre, expreso e informado**. Este consentimiento debe ser por escrito, claro y destacado, especialmente en contratos de adhesión. La ley también permite la autorización en forma digital, equiparando el documento digital al soporte papel. El titular de los datos debe conocer la finalidad de la base de datos, la identidad de los responsables y los posibles cesionarios, así como los derechos de control, rectificación y salida.

Excepciones a la necesidad de autorización previa incluyen datos de fuentes de acceso público, datos requeridos por una función estatal, datos mínimos de identidad (como nombre, domicilio, fecha de nacimiento, documento de identidad, ocupación e identificación tributaria), datos derivados de relaciones contractuales, científicas o profesionales anteriores, y operaciones de entidades financieras.

#### Cesión de datos a terceros

Para ceder datos a terceros, se deben cumplir una serie de requisitos. Tanto el cedente como el cesionario deben cumplir con los principios de legalidad, calidad y pertinencia. Se necesita un consentimiento específico para la cesión, el cual debe ser claro y por escrito. Excepciones a esta necesidad incluyen autorizaciones legales, cesiones entre organismos del estado dentro de sus competencias, datos relativos a la salud pública y datos disociados.

#### Obligación de inscripción

La ley exige que las bases de datos se inscriban en un registro estatal para posibilitar su control. La falta de inscripción es una violación sancionable. La información requerida para la inscripción incluye nombre y domicilio del responsable, características y finalidades del archivo, naturaleza de los datos, forma de recolección, destino de los datos, forma de tratamiento, medidas de seguridad, tiempo de conservación y formas de acceso y control por parte del titular de los datos.

La autoridad de aplicación tiene la obligación de actuar de oficio en casos de ilegalidad manifiesta y no puede autorizar bancos de datos que contradigan claramente la normativa. Sin embargo, esto no implica una autorización previa discrecional, sino una aplicación del principio de legalidad en la administración pública.

### Derechos del titular de los datos

1. **Derecho de información**: las personas deben dar su consentimiento sobre el uso de sus datos, y además tienen derecho a saber qué bancos de datos existen, con qué fines y quiénes son sus responsables.
2. **Derecho de acceso**: las personas deben poder pedir acceder a sus datos en un banco de datos, y si el administrador no responde en 10 días se puede iniciar una causa de violación de habeas data.
3. **Derecho de rectificación**: las personas deben poder pedir que se modifiquen datos falsos o erróneos, borrar datos inadecuados, actualizar datos viejos, y añadir información faltante. El titular tiene 5 días para responder.

## Responsabilidad por Banco de Datos

### Introducción

La gestión de un banco de datos y, en particular la violación de los principios contenidos en la ley, puede conllevar responsabilidades entres tres diferentes áreas: **administrativa, civil y penal**. Dichas responsabilidades pueden actuar en conjunto o por separado, de forma tal que un hecho determinado puede determinar la aplicación de sanciones en uno o todas las áreas mencionadas.

### Responsabilidad administrativa

La responsabilidad administrativa se refiere a las sanciones impuestas por autoridades de control cuando se incumplen las normativas sobre protección de datos personales. Estas normativas generalmente buscan asegurar la correcta recolección, almacenamiento, uso y transferencia de datos personales. Las infracciones administrativas pueden ser clasificadas según su gravedad en **leves, graves y muy graves**.

1. **Infracciones leves**: Pueden incluir el incumplimiento de obligaciones de información al titular de los datos o la falta de respuesta a solicitudes de acceso, rectificación o cancelación de datos dentro del plazo legal. Las sanciones suelen ser **apercibimientos o multas menores**.

2. **Infracciones graves**: Entre ellas se encuentran la recolección de datos sin el consentimiento adecuado del titular, la falta de medidas de seguridad apropiadas para proteger los datos, o el incumplimiento de las obligaciones de registro y notificación de los bancos de datos. Las sanciones pueden incluir **multas más altas, la suspensión temporal del banco de datos, o la prohibición de continuar con el tratamiento de los datos**.

3. **Infracciones muy graves**: Estas incluyen la transferencia internacional de datos a países que no proporcionan un nivel adecuado de protección sin la autorización correspondiente, el uso de datos personales para fines distintos a los autorizados, o la repetición de infracciones graves. Las sanciones pueden ser muy severas, incluyendo **multas significativas, la clausura definitiva del banco de datos, y la publicación de la infracción para informar al público**.

### Responsabilidad civil

La responsabilidad civil busca resarcir los daños causados a los titulares de los datos por el manejo indebido de sus datos personales. Se divide en responsabilidad contractual y extracontractual.

1. **Responsabilidad contractual**: Ocurre cuando existe un contrato entre el titular de los datos y el gestor del banco de datos. El gestor es responsable de cumplir con las obligaciones estipuladas en el contrato, como la protección de los datos y su uso adecuado. Si el gestor incumple estas obligaciones, y esto resulta en un daño al titular de los datos, puede ser obligado a indemnizar los daños. Ejemplos de incumplimiento contractual pueden incluir la divulgación no autorizada de datos o la falta de medidas de seguridad prometidas en el contrato.
2. **Responsabilidad extracontractual**: Se aplica cuando no existe un contrato directo entre las partes. Esta responsabilidad puede surgir de actos ilícitos que causen daño, como la recolección de datos sin consentimiento o la divulgación no autorizada de datos. En muchos sistemas legales, la responsabilidad extracontractual en el contexto de protección de datos tiende a ser objetiva, lo que significa que el gestor del banco de datos es responsable del daño causado, independientemente de la existencia de culpa o dolo, salvo que pueda demostrar la existencia de alguna causal eximente como fuerza mayor.

#### Rubros de la indemnización

-   Daño emergente → todos los gastos que se tuvieron que realizar por culpa del delito
-   Lucro cesante → dinero que se dejó de ganar por culpa del delito
-   Valor marca → daños a la imagen o reputación por culpa del delito
-   Daño moral → el más grave de todos. Incluye sufrimientos personales de la víctima por culpa del delito. La víctima puede pedir el monto $$$ que quiera al juez, y éste decide cuánto darle.

### Responsabilidad penal

La responsabilidad penal se refiere a las sanciones impuestas por el sistema judicial penal por conductas que constituyen delitos en el manejo de datos personales. Estas sanciones buscan castigar y disuadir conductas que atenten gravemente contra la privacidad y seguridad de los datos.

1. **Inserción de datos falsos**: Según el artículo 117 bis del Código Penal, se sanciona con prisión de **un mes a dos años** a quien inserte o haga insertar a sabiendas datos falsos en un archivo de datos personales. La pena puede aumentar si del hecho se deriva un perjuicio a alguna persona. Para funcionarios públicos, la pena incluye la inhabilitación para ejercer su cargo si cometen el delito en el ejercicio de sus funciones.
2. **Acceso ilegítimo y revelación de información**: El artículo 157 bis del Código Penal sanciona con prisión de un mes a dos años a quien acceda ilegítimamente a un banco de datos personales, o revele información que debe mantener en secreto por disposición legal. Este delito incluye la violación de sistemas de confidencialidad y seguridad, y es considerado un delito de peligro, lo que significa que no es necesario que se produzca un daño real para que exista responsabilidad penal.

---

<h1 align="center">Tema 10 - Delitos informáticos</h1>

## Ley de Delitos Informáticos en Argentina

### Introducción

Esta es una ley fundamental que se aprobó por ambas cámaras del congreso en el año 2007. Fue de alta importancia y relevancia debido al rápido incremento y gran variedad de delitos informáticos que fueron surgiendo a través del tiempo desde el nacimiento de las computadoras modernas y sobre todo Internet. Algunos de los más comunes: virus informáticos, estafas informáticas, ataques DDoS, pero hay muchos más.

Esta ley no es una ley especial, pero modifica al código penal. La Ley contempla una serie de delitos con sus respectivas penas:

### Acceso ilegítimo a un sistema informático (hacking)

Se sanciona a quien acceda, sin la debida autorización o excediendo la que posea, a un sistema o dato informático de acceso restringido.

Los pentesters están protegidos.

No incluye a la ingeniería inversa ni a la violación de DRM.

Prisión de **quince días a 6 meses** o de **1 mes a 1 año** si el acceso se realiza en perjuicio de un organismo público estatal, un proveedor de servicios públicos o financieros.

### Daño informático

Este delito abarca la destrucción, alteración, inutilización o supresión de datos, programas o sistemas informáticos.

Prisión de 6 meses a 4 años.

### Estafa informática

Se sanciona la alteración o manipulación de un sistema informático para defraudar o manipular a alguien, comunmente con el fin de ganar dinero.

Por ejemplo ingeniería social y phising.

Prisión de 1 mes a 6 años.

### Distribución de virus informáticos

Se refiere a la creación, difusión o introducción de programas maliciosos (virus, gusanos, etc.) que alteren el funcionamiento de sistemas informáticos.

Prisión de 1 mes a 3 años.

### Falsificación de documentos digitales

Incluye la creación, alteración o supresión de documentos electrónicos con el propósito de engañar.

Las penas varían según la gravedad del caso, pero son similares a las penas de falsificación de documentos tradicionales.

### Interrupción de correspondencia digital

Sanciona la intromisión, interceptación, divulgación o alteración de correos electrónicos y otras formas de comunicación digital sin el consentimiento del destinatario.

Prisión de 15 dias a 6 meses.

### Distribución de p\*\*\*\*grafía infantil

Penaliza la producción, distribución, difusión y almacenamiento de material p\*\*\*\*gráfico infantil.

La responsabilidad de atrapar a estos criminales son los ISP. Estos criminales suelen usar redes P2P y memoria caché.

Prisión de 6 meses a 4 años para distribución; 4 meses a 2 años para posesión; 1 mes a 3 años para facilitación del contenido a menores.

### Delitos sobre Bancos de Datos

Incluye acceder de forma no autorizada a un banco de datos, exponer la información del mismo a terceros, y agregar, borrar o modificar los registros de la base de datos.

Prisión de 1 mes a 2 años y además, si el culpable es funcionario público, pena de inhabilitación especial de 1 a 4 años.

---

<h1 align="center">Tema 11 - Pericias</h1>

## Estructura del Poder Judicial

Un régimen federal implica la existencia de un doble sistema judicial: **federal y local**. Sobre ambos se encuentra la Corte Suprema.

### Justicia Federal

Está fundamentada en los artículos 108, 116 y 117 de la Constitución Nacional.

Posee 3 características principales:

-   **Excepcional**: esta jurisdicción solo se usa en caso de ley o norma constitucional expresa.
-   **Excluyente**: los jueces provinciales no pueden actuar en estas causas.
-   **Improrrogable**: excepto en el caso de competencia en razón de personas.

Las **causas civiles** son aquellas regidas por el derecho privado. Las que involucran al derecho administrativo y derecho penal **no son causas civiles**.

La competencia federal nace en función de **el territorio**, **la materia** y las **personas involucradas**. Si alguna de cualquiera de las 3 condiciones se da, se habilita la competencia federal.

### Por el territorio

Se trata federalmente si los hechos de la causa acontecieron en territorios con jurisdicción federal, como por ejemplo las Universidades Nacionales.

#### Por la materia

Estas son las causas que versan sobre puntos regidos directamente por:

1. La Constitución Nacional
2. Las Leyes Federales
3. Los Tratados Internacionales

Si la causa no involucra ninguna de estas cosas, entonces la competencia es provincial y no federal.

#### Por las personas involucradas

En los casos de causa civil entre los distintos sujetos:

1. El Estado Federal es demandado o demandante
2. Conflictos entre provincias
3. Conflictos entre vecinos de distintas provincias

### Justicia Local

Es la justicia establecida por las provincias en función de sus constituciones y regida por sus procedimientos.

En la prov. de Buenos Aires se divide por **el lugar** y por **la materia**.

En razón del lugar: la provincia se divide en departamentos judiciales que abarcan varios partidos. Los hechos de un partido se discuten en tribunales de la ciudad sede del departamento judicial asignado a ese partido. **Esta competencia es prorrogable**.

En razón de la materia: dentro de cada departamento judicial, las causas se dividen en función de la especialización de los distintos juzgados. **Esta competencia es improrrogable**.

El orden judicial provincial es: Suprema Corte Provincial → Cámara de Apelaciones → Tribunal de 1° instancia

### Funcionarios del poder judicial

#### Jueces

Funcionario que juzga determinada clase de conflictos ya sea por su cuenta o teniendo en consideración lo resuelto por otros funcionarios previamente.

Poseen las siguientes **características**:

1. **Permanentes**: nadie puede ser juzgado por comisiones especiales, solo por un juez.
2. **Sedentarios**: el cargo está restringido territorialmente al departamento judicial del cargo.
3. **Inamovibles**: duran en su puesto hasta que son removidos por causa justificada.
4. **Letrados**: todos los jueces son abogados con título.

Poseen las siguientes **obligaciones**:

1. Obligación de resolver el caso, no pudiendose excusar de ninguna forma.
2. Obligación de asistir a las audiencias cuando lo marca la ley o lo piden las partes.
3. Obligación de justificar todas sus decisiones en el proceso judicial.
4. No puede decidir sobre temas no propuestos por las partes, ni tampoco dictar una sentencia mayor a lo solicitado por las partes.
5. Debe residir (domicilio) en el radio del juzgado.
6. Los jueces de primera instancia deben concurrir al juzgado todos los dias, los de cámara los dias que se firman las sentencias.

#### Ministerio público

Conjunto de funcionarios que defienden los intereses vinculados al orden público y social. Son independientes de los juzgados y a diferencia de los jueces, no deciden si no que se interponen ciertas pretensiones y controlan el cumplimiento de los requisitos legales.

Hay 3 clases, fiscal, pupilar y defensor de pobres y ausentes.

#### Secretario

Auxiliar judicial que ordena y custodia los expedientes. Deben ser Argentinos nacionalizados, ser abogados y no ser parientes del juez.

#### Ujier

Realiza las notificaciones y embargos correspondientes a los juzgados superiores (cámara y corte suprema).

### Proceso

El proceso judicial es el conjunto de actos que crean una norma individual destinada a regir la conducta de sujetos.

Se clasifican en Universales y Singulares. Los Singulares se dividen por su contenido en voluntarios y contenciosos, y por su finalidad en conocimiento, ejecución, cautelares.

1. **Procesos voluntarios**: procesos sin controversia, simples.
2. **Procesos contenciosos**: buscan resolver dos o más intereses en conflicto.
3. **Procesos de conocimiento**: buscan que el órgano jurisdiccional dilucide y declare el contenido y alcance de la situación jurídica existente entre las partes.
4. **Procesos de ejecución**: buscan que el órgano jurisdiccional modifique una situación de hecho, para que coincida con un mandato legal determinado.
5. **Procesos cautelares**: procesos instrumentales diseñados para asegurar el resultado de un procedimiento posterior.

### Prueba

Son modos u operaciones que, referidos a cosas o personas, son susceptibles de proporcionar un dato demostrativo de la existencia o inexistencia de uno o más hechos.

La prueba recae sobre los hechos y no sobre el derecho. Estos hechos deben ser controvertidos y/o conducentes.

La prueba la solicitan las partes, aunque a veces los jueces también.

### Peritos

Auxiliar del juez llamados a informar a éste sobre las consecuencias que, objetivamente y de acuerdo a su expertise, deben extraerse de los hechos.

| Testigo                                                       | Perito                                                                        |
| ------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| Cuenta lo que percibió con sus sentidos                       | Formula conclusiones derivadas de deducción                                   |
| Los hechos son anteriores al proceso e independientes de éste | Los hechos percibidos son posteriores al proceso y ocurren en función de éste |
| No necesita conocimientos especiales                          | Debe ser experto en la materia de la que informa                              |
| Es único e irremplazable                                      | Puede ser reemplazado por otro experto del mismo área                         |

#### Peritos informáticos

En Buenos Aires deben tener título habilitante. Además:

1. Deben anotarse en listados correspondientes en la Cámara de Apelaciones de cada departamento judicial.
2. Vivir en la ciudad del juzgado.
3. Cursar y aprobar los cursos que dicta la Suprema Corte Bonaerense.

## Pericias
