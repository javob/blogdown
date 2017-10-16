---
title: Comportamiento legislativo en Guatemala según registros de votación
author: Javier Brolo
date: '2015-02-18'
slug: comportamiento-legislativo-en-guatemala-segun-registros-de-votacion
categories: []
tags: []
header:
  caption: ''
  image: ''
---

_El presente artículo es una adaptación del publicado en: [Brolo, J. (2015). El comportamiento legislativo en Guatemala según registros de votación. Actualidad Política, 9: 18-29. ](http://reneesposito.com/asiesnew/wp-content/books/revista-no9_actualidad-politica_17_02_2015.pdf)La base de datos utilizada puede descargarse en: _[Votaciones nominales por Diputado durante la 7a Legislatura de Guatemala](http://www.paywithatweet.com/pay?id=6f5b192e-c286-4491-9623-765488131b2c).

Por Javier Brolo [1]

El presente documento cumple dos objetivos. En primer lugar, se ofrece una breve introducción a las bases de datos con los registros de votaciones nominales del 7º Congreso de la República de Guatemala desde 1985. En segundo lugar, se presenta un análisis preliminar de los patrones en el comportamiento de los diputados guatemaltecos según votaciones y se sugiere una agenda de investigación de los mismos.

Los registros de votación son de gran utilidad para descubrir e identificar patrones en el comportamiento de los legisladores. Por ejemplo, las votaciones permiten evaluar la disciplina partidaria, reconocer la existencia de alianzas o estimar la coherencia ideológica. Conocer el comportamiento legislativo sirve a los ciudadanos que desean fiscalizar a sus representantes, a los académicos que buscan evidencia para verificar modelos teóricos y a los partidos políticos que necesitan tomar decisiones estratégicas.

Herramientas informáticas como "WNOMINATE" (K. Poole, Lewis, Lo, & Carroll, 2007) han facilitado y extendido el análisis de las votaciones nominales alrededor del mundo, especialmente en Estados Unidos (K. T. Poole, 2005). Sin embargo, son pocos los estudios sistemáticos del comportamiento legislativo en Guatemala entre los cuales destacan estudios elaborados por Javier Fortín (2010) y Gustavo Herrarte (2012).

Quizás la principal dificultad para estudiar las votaciones nominales en Guatemala sea la falta de información en un formato práctico de analizar. Antes de la aprobación del tablero electrónico, en abril del 2011 (Cereser, 2011), era necesario consultar el texto de las actas de sesión para saber cómo votó un diputado. Ahora es posible consultar las votaciones en la página web del Congreso de la República de Guatemala (2015). Sin embargo, no es posible descargar los datos de forma directa para su análisis.

El alto costo de recabar y preparar información ha representado un obstáculo para analizar el comportamiento legislativo y proponer mejoras a su desempeño. Para disminuir esta limitación, el Departamento de Investigaciones Sociopolíticas de ASIES ha compilado las bases de datos con los registros de votaciones del 7º Congreso de la República de Guatemala y las ha puesto a disposición del público: "[votoscongreso.xlsx](http://www.paywithatweet.com/pay?id=6f5b192e-c286-4491-9623-765488131b2c)".

Los datos incluyen registros de todas las votaciones desde el 14 de enero del 2012 hasta el 20 de enero del 2015. Estos se obtuvieron mediante el paquete de análisis estadístico R (R Core Team, 2014) utilizado para sistematizar la información disponible en la página web del Congreso.

## **Una agenda legislativa dominada por el oficialismo**

Después de contabilizar los registros de votación, puede observarse (ver Figura 1) que los diputados han votado un total de 2114 veces desde el inicio de la legislatura en el 2012, de las cuales 389 veces la votación no se aprobó, 916 veces la votación se aprobó con mayoría simple, y 809 la votación se aprobó con mayoría calificada.

Es importante notar que la mayoría de veces cuando el tema tratado en la votación no se aprobó, éste se refería a los candidatos a magistrados de las Cortes de Apelaciones, Corte Suprema de Justicia y Tribunal Supremo Electoral que no fueron seleccionados. Por consiguiente, se infiere que el control de la agenda legislativa, a cargo del oficialismo, ha sido efectivo. Es decir, los temas que han llegado a discusión del pleno son, casi en su totalidad, aprobados. Por otro lado, el gran número de votaciones aprobadas por mayoría calificada sugiere que la intensidad del control sobre la agenda legislativa ha sido alto, dado que no solo los temas fueron aprobados, sino fueron aprobados con contundencia.

La Figura 2 refuerza la percepción de un control oficialista sobre la agenda, ya que los diputados con mayor porcentaje de votaciones a favor pertenecen al partido PP[2]. Esto implica que, los temas discutidos en el pleno eran los que interesaban aprobar al PP. Asimismo, la Figura 3 muestra que la principal oposición a la agenda legislativa corresponde al partido LIDER.

![Figura 1. La mayoría de votaciones en cada sesión fueron aprobadas](https://javierbrolo.files.wordpress.com/2015/02/figura-1.png)

<p class="caption">Figura 1. La mayoría de votaciones en cada sesión fueron aprobadas</p>

[caption id="attachment_1490" align="alignnone" width="261"]![Figura 2. Diputados con mayor porcentaje de votaciones a favor](https://javierbrolo.files.wordpress.com/2015/02/screen-shot-2015-01-25-at-4-39-43-pm.png) Figura 2. Diputados con mayor porcentaje
de votaciones a favor[/caption]

![Figura 3. Diputados con mayor porcentaje de  votaciones en contra](https://javierbrolo.files.wordpress.com/2015/02/screen-shot-2015-01-25-at-4-40-03-pm.png)

<p class="caption">Figura 3. Diputados con mayor porcentaje de votaciones en contra</p>

![Figura 4. Diputados con mayor porcentaje de ausencias ](https://javierbrolo.files.wordpress.com/2015/02/screen-shot-2015-01-25-at-4-18-35-pm.png)

<p class="caption">Figura 4. Diputados con mayor porcentaje de ausencias</p>

Respecto a los diputados con el mayor porcentaje de ausencias, mostrados en la Figura 4, las votaciones por sí solas no son suficientes para interpretar su significado. Existen al menos tres posibles explicaciones. Primero, los diputados a la vez que se ausentan a modo de protesta para manifestar su rechazo, evitan ser objeto de represalia por el grupo que promueve la votación. Segundo, la ausencia es una muestra tácita de apoyo, que permite se tome una decisión e impide el costo político de promover explícitamente la aprobación de una medida. Tercero, la ausencia de los diputados puede deducirse como indiferencia respecto a si una votación se aprueba o no. Es necesario recabar más datos de cada votación para determinar cuál es el motivo predominante.

La base de datos "[votoscongreso.xlsx](http://www.paywithatweet.com/pay?id=6f5b192e-c286-4491-9623-765488131b2c)" contiene las descripciones de cada votación para explorar con mayor profundidad las implicaciones de un voto a favor, en contra o ausente e incluye las siguientes variables:

### Tabla 1. Variables en la base de datos: descripciones

<table >
<tbody >
<tr >

<td width="83" >**Variable**
</td>

<td width="392" >**Descripción**** **
</td>
</tr>
<tr >

<td width="83" >vote.id
</td>

<td width="392" >Identificación única para cada votación. Consta de dos dígitos: X.Y. X indica el correlativo de la sesión legislativa e Y indica el correlativo de la votación dentro de la sesión.
</td>
</tr>
<tr >

<td width="83" >Ausente
</td>

<td width="392" >El número de diputados ausentes
</td>
</tr>
<tr >

<td width="83" >Favor
</td>

<td width="392" >El número de diputados que votó a favor
</td>
</tr>
<tr >

<td width="83" >SUM
</td>

<td width="392" >El total de diputados
</td>
</tr>
<tr >

<td width="83" >Date
</td>

<td width="392" >La fecha en que inicio de la sesión de la cual forma parte la votación. Tomar nota que algunas sesiones se extendieron por varios días, semanas, e incluso meses después de dar inicio. Por consiguiente la fecha de inicio de la sesión no siempre coincide con la fecha exacta en la que ocurrió la votación.
</td>
</tr>
<tr >

<td width="83" >Asunto
</td>

<td width="392" >Asunto de la votación
</td>
</tr>
<tr >

<td width="83" >Tema
</td>

<td width="392" >Tema de la votación
</td>
</tr>
<tr >

<td width="83" >Subtema
</td>

<td width="392" >Subtema de la votación
</td>
</tr>
</tbody>
</table>
La base de datos "[votoscongreso.xlsx](http://www.paywithatweet.com/pay?id=6f5b192e-c286-4491-9623-765488131b2c)" también incluye la forma en que los diputados votaron en cada votación y permite indagar sobre su comportamiento individual.

### Tabla 2. Variables en la base de datos: votos

<table >
<tbody >
<tr >

<td width="85" >**Variable**
</td>

<td width="392" >**Descripción**
</td>
</tr>
<tr >

<td width="85" >legis
</td>

<td width="392" >Información abreviada de cada diputado. Incluye primer nombre, primer apellido, distrito y bancada más reciente con la cual votó.
</td>
</tr>
<tr >

<td width="85" >Diputado
</td>

<td width="392" >Apellidos completos de cada diputado seguido de sus nombres completos separados por coma.
</td>
</tr>
<tr >

<td width="85" >Bancada.2.1
</td>

<td width="392" >Bancada con la que cada diputado votó en la votación número 2.1, correspondiente a la primera votación del 7º Congreso. Las letras NA sirven para señalar aquellos diputados que entraron al Congreso posteriormente, en sustitución de otro diputado.
</td>
</tr>
<tr >

<td width="85" >Bancada.62.64
</td>

<td width="392" >Bancada con la que cada diputado votó en la votación número 62.64. Esta votación corresponde a la votación más reciente del 7º Congreso. Las letras NA sirven para señalar aquellos diputados que salieron del Congreso.
</td>
</tr>
<tr >

<td width="85" >Distrito
</td>

<td width="392" >Distrito en donde el diputado fue electo.
</td>
</tr>
<tr >

<td width="85" >Voto.2.1 – Voto.62.65
</td>

<td width="392" >Forma en que cada diputado votó en la respectiva votación: 1 = A Favor; -1 = En Contra; 0 = Ausente. Los nombres de las columnas corresponden a los valores de la identificación única para cada votación (voto.id) de la base de datos "descripciones".
</td>
</tr>
</tbody>
</table>

## **Los tres grupos de legisladores: (1) PP; (2) LIDER; y (3) UNE/TODOS/CREO**

Uno de los patrones que puede analizarse a partir de las votaciones nominales es la "ideología" de los diputados. Independientemente de los contenidos programáticos o significados sustantivos de alguna "ideología" particular, una forma aceptada para observar las ideologías se basa en la idea de "constraint" (restricción) planteada por Converse (1964). Para Converse, la ideología es un "sistema de creencias", el cual pone límites al repertorio de opiniones que una persona tiene sobre diversos temas. Por ejemplo, una persona "conservadora" (Quinton, 2007) tiende a priorizar su seguridad, es escéptica al cambio y valora la tradición. Entonces, es posible observar la ideología conservadora en una persona que consistentemente opina dentro de los límites de ese sistema de creencias; por ejemplo, oponiéndose a la inmigración o condenando la investigación en células madre.

Armstrong et al. (2014) muestran como analizar la "ideología" de los diputados a partir de sus votaciones. De acuerdo a la teoría espacial, las restricciones impuestas por un sistema de creencias pueden representarse geométricamente utilizando dimensiones abstractas. Este modelo asume que cada diputado ocupa una posición ideal en el espacio ideológico. Además, asume que los diputados votan a favor o en contra de un tema en función de acercarse lo más posible a su punto ideal. Esto permite utilizar las votaciones de cada diputado para estimar sus puntos ideales.

Si bien se cuestiona que las ideologías de los diputados guatemaltecos correspondan a una conceptualización teórica explícita (p. ej. conservador, liberal o social demócrata), esto no excluye la posibilidad de que sí cuenten con un sistema de creencias propio que oriente sus decisiones. Las dimensiones abstractas de dichos sistemas de creencias pueden corresponder a diversos criterios políticos, sociales, económicos, étnicos, religiosos, territoriales, estéticos, entre otros. Determinar el contenido programático de los sistemas de creencias de los diputados actuales escapa a los alcances del presente análisis preliminar. Sin embargo, es posible estimar los puntos ideales en el espacio ideológico para cada diputado utilizando todas sus votaciones desde el inicio de la legislatura como lo muestra la Figura 5.

En la Figura 5 se observan tres grupos de legisladores de acuerdo a la posición ideológica que refleja sus votaciones. Por un lado se identifica a los diputados del partido en el gobierno: PP. Este grupo, del cual Juan Porras es representativo, muestra alta disciplina partidaria, ya que la concentración de puntos indica que los diputados votan de forma similar para acercarse a un punto ideal en común. Por otro lado se encuentran los diputados del partido LIDER. Este grupo, identificado con Roberto Villate, comparte su distancia con el PP; sin embargo, se dispersan respecto a la segunda dimensión. Finalmente, existe otro grupo de diputados pertenecientes a distintas bancadas quienes en unas ocasiones votan con el oficialismo y en otras ocasiones con la oposición, sin compartir un punto ideal entre sí.

![Figura 5. Coordenadas en el espacio ideológico: puntos ideales estimados para cada diputado del 7º Congreso de la República de Guatemala](https://javierbrolo.files.wordpress.com/2015/02/figura-5.png)

<p class="caption">Figura 5. Coordenadas en el espacio ideológico: puntos ideales estimados para cada diputado del 7º Congreso de la República de Guatemala</p>

Conocer el comportamiento legislativo abre la puerta a numerosas discusiones sobre sus implicaciones. Por ejemplo, si el oficialismo controla la agenda legislativa, aún sin contar con mayoría por sí mismo, puede hacer concesiones para la aprobación de propuestas de interés a uno de los otros dos grupos. También, el gráfico muestra que es bastante probable que el PP vote "en bloque", lo cual hace predecibles sus votaciones, mientras que las otras bancadas no han mostrado comportarse como bloque con la misma consistencia.

Sin duda existe un sinnúmero de interrogantes que este análisis preliminar no resuelve. Precisamente, el propósito de poner los datos a disposición del público es el de facilitar información que contribuya a transparentar la labor legislativa.

Como una propuesta de agenda de investigación se sugieren las siguientes inquietudes: ¿Qué tipos de votación generan la mayor polarización y por qué? ¿Qué votaciones delimitan las fronteras de cada posición ideológica: aquellas relacionadas al control de la agenda, a la distribución de recursos, a la elección de órganos de control, a las prerrogativas de actores de poder, al diseño institucional, u otros? ¿Hay diferencia entre el comportamiento de algunos diputados distintivos como los jefes de bancada, de la junta directiva, del listado nacional, u otro? ¿Por qué sucede el transfuguismo? ¿Existen redes de influencia en el Congreso y qué diputados las controlan? Responder estas inquietudes ofrece la posibilidad de ir deduciendo cada vez mayor responsabilidad de la participación que cada diputado tiene en los procesos legislativos.

### **Referencias**

Armstrong II, D. A., Bakker, R., Carroll, R., Hare, C., Poole, K. T., & Rosenthal, H. (2014). _Analyzing Spatial Models of Choice and Judgment with R_. Boca Raton, FL: CRC Press.

Cereser, L. (2011, April 6). Congreso aprueba el voto electrónico. _Prensa Libre_. Guatemala. Retrieved from http://www.prensalibre.com/noticias/Congreso-aprueba-voto-electronico_0_457754241.html

Congreso de la República de Guatemala. (2015). Consulta de eventos de votación. Retrieved from http://stats.congreso.gob.gt/hemiciclo/graphs/v_container.asp

Converse, P. E. (1964). The Nature of Belief Systems in Mass Publics. In D. E. Apter (Ed.), _Ideology and Discontent_ (pp. 206–262). New York: The Free Press of Glencoe.

Fortin, J. (2010). Transfuguismo parlamentario en Guatemala: Un caso de altos costos de asociación, monopolio partidario y bajos costos de transacción. _América Latina Hoy_, _54_, 141–166.

Herrarte, G. (2012, September 4). El voto indígena en el Congreso en el 13 B'ak'tun: ¿un nuevo inicio o más de lo mismo? Guatemala. Retrieved from http://www.plazapublica.com.gt/content/el-voto-indigena-en-el-congreso-en-el-13-baktun-un-nuevo-inicio-o-mas-de-lo-mismo

Poole, K., Lewis, J., Lo, J., & Carroll, R. (2007). Scaling Roll Call Votes with wnominate in R. _Journal Of Statistical Software_, _22_(1), 1–23.

Poole, K. T. (2005). _Spatial Models of Parliamentary Voting_. Cambridge, UK: Cambridge University Press.

Quinton, A. (2007). Conservatism. In R. E. Goodin, P. Pettit, & T. Pogge (Eds.), _A Companion to Contemporary Political Philosophy_ (2nd ed., pp. 285–311). Oxford, UK: Blackwell Publishing.

R Core Team (2014). _R: A language and environment for statistical computing._ R Foundation for Statistical Computing, Vienna, Austria. URL <http://www.R-project.org/>.

[1] MSc. Javier Brolo ([jbrolo@asies.org.gt](mailto:jbrolo@asies.org.gt)) es investigador del Departamento de Investigaciones Sociopolíticas de ASIES. Obtuvo un MSc en Ciencia Política con honores de la Universidad de Essex, Reino Unido, gracias a la beca Chevenig. Sus intereses incluyen la formalización de modelos teóricos sobre el fortalecimiento de instituciones y su verificación utilizando métodos cuantificables.

[2] Las listas de diputados muestran la bancada a la que pertenecía cada diputado en su votación más reciente.
