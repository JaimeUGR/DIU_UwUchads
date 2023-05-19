# DIU23
Prácticas Diseño Interfaces de Usuario 2022-23 (Tema: Tours por Granada) 

Grupo: DIU2_UwUchads  Curso: 2022/23 
Updated: 08/03/2023

Proyecto: 
**Conecta Granada**

Descripción: 

Nuestra proyecto se basa en la creación de una aplicación donde no sólo se puedan realizar tours, sino que se puedan realizar todo tipo de actividades 
por Granada. Así, surge nuestra propuesta, que priorizará la accesibilidad de los usuarios a todas las actividades culturales que Granada puede ofrecer.

Además, la colaboración con las pequeñas empresas será uno de los incentivos para fomentar la creación y mejora de nuevas actividades culturales.

Logotipo: 
>>> Opcionalmente si diseña un logotipo para su producto en la práctica 3 pongalo aqui

Miembros
 * :bust_in_silhouette: [Jaime Pérez García](https://github.com/JaimeUGR) :octocat:     
 * :bust_in_silhouette: [Francisco Expósito Carmona](https://github.com/francx11) :octocat:

----- 

# Proceso de Diseño 

## Paso 1. UX Desk Research & Analisis 

![Método UX](img/Competitive.png) 1.a Competitive Analysis
-----

Hemos hecho una comparación entre los principales resultados al buscar por Internet Tours gratis por Granada. La comparación se ha realizado entre:
- [FreeTour](https://freetour-granada.com/)
- [BuendiaTours](https://buendiatours.com/es/granada)
- [WalkInGranada](https://walkingranada.com/)

De la comparación hemos sacado como conclusión que FreeTour está muy por detrás de los competidores y que, si lo que buscas es un tour por Granada,
la mejor opción es [BuendiaTours](https://buendiatours.com/es/granada), tanto por la calidad de la página web como por las actividades ofrecidas.

Si quieres observar el análisis de una forma más gráfica te recomendamos que hagas click en el siguiente enlace: [Competitor Analysis](./P1/CompetitorAnalysis.png)

![Método UX](img/Persona.png) 1.b Persona
-----

Para poder probar la accesibilidad que tiene la página de [FreeTour](https://freetour-granada.com/), hemos decidido elegir a dos personas que representan a dos colectivos distintos.

### Josefina
Josefina es una persona mayor, residente en Granada, que está jubilada y, ahora que tiene más tiempo libre, quiere disfrutar una experiencia
nueva. Por ese motivo, ha decicido reservar para participar en un tour, ya que ella siempre ha estado interesada en este tipo de actividades.

Puedes apreciar más detalles sobre su biografía así como sus gustos y habilidades haciendo click en el siguiente enlace: [Descripción de Josefina](./P1/Persona_Josefina.png)

### Manuel
Manuel es una persona que no vive en Granada, sino en Tarragona, Çataluña. Quiere sorprender a su familia con un pequeño viaje para conocer un lugar
turístico, por lo que está intentando reservar un tour a través de Internet.
Sin embargo, debido a la discapacidad motora de Manuel, es muy importante conocer de antemano si podrá realizar el tour.

Puedes apreciar más detalles sobre su biografía así como sus gustos y habilidades haciendo click en el siguiente enlace: [Descripción de Manuel](./P1/Persona_Manuel.png)

![Método UX](img/JourneyMap.png) 1.c User Journey Map
----

### Josefina
La experiencia de Josefina es la más cercana a la que cualquier persona mayor que acceda a esta página tendrá que sufrir.

Puedes observar un cómo se va sintiendo Josefina y los problemas que le surgen a lo largo de su experiencia con la página web en el siguiente enlace: [Journey Map de Josefina](./P1/Journey_Josefina.png)



### Manuel
La experiencia de Manuel es muy cercana a la que experimentará:
- Una persona que debido a su discapacidad no sabe si puede realizar el Tour
- Una persona que no es de Granada

En el siguiente enlace: [Journey Map de Manuel](./P1/Journey_Manuel.png) , podrás comprobar cómo afecta a Manuel el hecho de ser una persona discapacitada a la hora de utilizar la página web.


![Método UX](img/usabilityReview.png) 1.d Usability Review
----
Un punto muy importante dentro del análisis de una página web es su usabilidad. Para poder describir este aspecto hemos utilizado una plantilla con todos los puntos clave con los que debería contar una
página web y hemos sacado nuestras propias conclusiones acerca de [FreeTour](https://freetour-granada.com/)

Los principales factores negativos son:
- El rendimiento de la página es horrible
- Las múltiples redirecciones durante el proceso de reserva hacen que te pierdas
- No hay información detallada sobre los tours
- En dispositivos móviles la página web tiene problemas

Todo esto ha resultado en una valoración de 46 (sobre 100), que implica que la mayor parte de usuarios tendrán una experiencia negativa en esta página,
al igual que nosotros la hemos tenido.


## Paso 2. UX Design  


![Método UX](img/feedback-capture-grid.png) 2.a Feedback Capture Grid / EMpathy map / POV
----

Para comenzar nuestro proyecto, hemos creado una malla receptora de información, en la que hemos observado cuatro aspectos clave:

- "Like" (Gustos): En esta sección, hemos recopilado todas las ideas y características que nos han gustado de la competencia y que creemos que deben estar presentes en nuestro proyecto.
- "Wishes" (Deseos): Aquí hemos incluido todas las críticas que tenemos sobre la competencia y las áreas que creemos que se pueden mejorar o solucionar.
- "Questions" (Preguntas): En esta parte, hemos recopilado las preguntas que las personas ficticias se han hecho mientras utilizaban las aplicaciones de la  competencia.
- "Ideas" (Ideas): Basándonos en todo lo anterior, hemos incluido en esta sección las ideas que podemos implementar para hacer mejoras en nuestro proyecto.

En [Feedback Capture Grid](./P2/FeedbackCaptureGrid.png) encontrarás una imagen que deja de forma clara y visual los anteriores aspectos.



![Método UX](img/ScopeCanvas.png) 2.b ScopeCanvas
----

Nuestra propuesta se trata de una aplicación sencilla, que agrupa todo tipo de actividades culturales en Granada. De esta forma, tanto el proceso de búsqueda
como de reserva estarán simplificados, ya que el usuario no tendrá que recurrir a agencias o buscar en miles de páginas.
Por otro lado, creemos que la capacidad de interacción entre los usuarios es fundamental, por lo que dentro de la propia aplicación podrás compartir tanto las actividades que más te gusten como fotos y vídeos tuyos realizándolas.
También, la facilidad para encontrar actividades afines a nuestros gustos es una tarea pendiente en nuestros competidores, que nosotros, resolveremos mediante un sistema de recomendación personalizado (a partir de un algoritmo).

Escuchando a nuestros usuarios (Manuel y Josefina), hemos visto que los dos principales problemas son:
- Falta de información acerca de los tours
- Dificultad en el proceso de reserva

Estos problemas los solucionaremos en conjunto, es decir, facilitaremos el proceso de reserva unificándolo con la página donde se encuentra la información de la actividad. Además, dicha información incluirá descripciones **detalladas** de la actividad, imágenes, vídeos, requisitos, preguntas frecuentes... junto a datos relacionados con el terreno, la dificultad y datos necesarios para personas con cualquier tipo de discapacidad.

Para gestionar nuestra propuesta, hemos hecho un roadmap, donde hemos especificado una serie de objetivos a corto, medio y largo plazo. Dichos objetivos se resumen en:
- A corto plazo nos gustaría tener una aplicación móvil integrada con la aplicación, ya que, de esta forma, facilitaríamos la expansión en múltiples plataformas al mismo tiempo. Por otro lado, el sistema de recomendaciones personalizadas y el perfil de usuario son fundamentales para lograr la interacción e implicación que buscamos entre los usuarios. También, la realización de actividades únicas (tales como eventos), ayudarán a atraer nuevos usuarios.
- A medio plazo nos gustaría incorporar un servicio de ayuda automático en nuestra aplicación, que sea capaz de guiarte si te has perdido.
- A largo plazo nos gustaría realizar contratos y colaboraciones con grandes marcas y empresas, de forma que podamos expandir el rango de nuestras actividades de Granada a un ámbito nacional e internacional.

Puedes observar todo lo descrito anteriormente y más en el siguiente enlace: [Scope Canvas](./P2/ScopeCanvas)

![Método UX](img/Sitemap.png) 2.b Tasks analysis 
-----

Para analizar las tareas de nuestros usuarios, hemos decidido crear una Task Matrix. Esto consiste en una matriz donde ordenamos las tareas que se realizarán en nuestra aplicación según momentos temporales, para poder saber qué acciones son las que se realizan con mayor frecuencia.

De esta forma, hemos representado las acciones principales que todo tipo de usuario tendrá, categorizado en 4 grupos:
- Usuario buscando una actividad: estos usuarios pueden estar o no registrados, siendo su principal interés el encontrar una actividad que realizar.
- Usuario antes de realizar una actividad: estos usuarios ya han reservado una actividad (o están en proceso), siendo su principal interés informarse y compartirla con sus amigos.
- Usuario durante la realización de una actividad: estos usuarios están realizando una actividad, siendo su principal interés compartir lo que están haciendo.
- Usuario tras la realización de una actividad: estos usuarios han terminado una actividad, siendo su principal interés encontrar nuevas actividades que realizar, utilizando los buscadores y mirando las recomendaciones.

En [Task Matrix](./P2/TaskMatrix.png) encontrarás de una forma muy clara y visual cómo se ordenan las acciones según su frecuencia de uso en la aplicación.

De esta forma, hemos conseguido localizar las actividades más importantes (subrayadas en negrita), que formarán parte del uso habitual de los usuarios.

![Método UX](img/labelling.png) 2.c IA: Sitemap + Labelling 
----
#### Sitemap
Con un Sitemap, y en concreto con el nuestro, queremos mostrar la funcionalidad general de nuestra aplicación, dividida en varios apartaddos para que el usuario tenga opción de elegir el apartado más conveniente para su uso. Además, la parte relacionada con el contacto y la gestión del perfil están reservadas para sus apartados correspondientes.

En [Sitemap](./P2/Sitemap.png) se muestra de forma muy clara la estructura general de nuestra aplicación.

Este diseño lo hemos orientado de forma que el usuario tenga la mayor facilidad posible para:
- Buscar las actividades que quiere
- Sumergirse en el catálogo buscando actividades
- Reservar rápidamente
- Gestionar su perfil de forma cómoda y sencilla

#### Labelling
Con el Labelling, queremos conseguir etiquetar y describir cada uno de los apartados que aparecen en el esquema general del Sitemap, para que quede claro a qué se refiere cada uno.

Si accedes a [Labelling](./P2/Labelling.png), podrás encontrar una tabla que describe cada uno de los aspectos anteriormente mencionados.

![Método UX](img/Wireframes.png) 2.d Wireframes
-----

Hemos creado una serie de bocetos Lo-Fi, que nos han permitido esquematizar el diseño de la página web, donde hemos destacado las partes más importantes:
- Home (Landing Page)
- Catálogo
- Lista de actividades de una categoría específica
- Información actividad + Reserva

Cabe destacar que estos bocetos son puramente ilustrativos y no pretenden mostrar el estilo final de la página. Además, los colores utilizados son para seccionar la página, facilitando su posterior refinamiento.

#### Home
Puedes encontrar cómo se vería la página principal en: [Home](./P2/BocetoHome.png)

#### Catálogo General
Puedes encontrar cómo se vería el catálogo general donde están las distintas categorías de actividades en: [Catálogo General](./P2/BocetoCatalogo.png)

#### Catálogo de Tours
Para ver los distintos tours que se encunetran disponibles puedes apreciar cómo se verían en: [Catálogo de tours](./P2/BocetoCatalogoTours.png)

#### Reserva de Tour
Puedes encontrar un esquema de cómo se realizaría la reserva de un tour en: [Reserva de tour](./P2/BocetoReservaTour.png)


## Paso 3. Mi UX-Case Study (diseño)


![Método UX](img/moodboard.png) 3.a Moodboard
-----


>>> Plantear Diseño visual con una guía de estilos visual (moodboard) 
>>> Incluir Logotipo
>>> Si diseña un logotipo, explique la herramienta utilizada y la resolución empleada. ¿Puede usar esta imagen como cabecera de Twitter, por ejemplo, o necesita otra?


![Método UX](img/landing-page.png)  3.b Landing Page
----


>>> Plantear Landing Page 

![Método UX](img/guidelines.png) 3.c Guidelines
----

>>> Estudio de Guidelines y Patrones IU a usar 
>>> Tras documentarse, muestre las deciones tomadas sobre Patrones IU a usar para la fase siguiente de prototipado. 

![Método UX](img/mockup.png)  3.d Mockup
----

>>> Layout: Mockup / prototipo HTML  (que permita simular tareas con estilo de IU seleccionado)


![Método UX](img/caseStudy.png) 3.e ¿My UX-Case Study?
-----


>>> Publicar my Case Study en Github..
>>> Documente y resuma el diseño de su producto en forma de video de 90 segundos aprox


## Paso 4. Evaluación 


![Método UX](img/ABtesting.png) 4.a Caso asignado
----


>>> Breve descripción del caso asignado con enlace a  su repositorio Github


![Método UX](img/usability-testing.png) 4.b User Testing
----

>>> Seleccione 4 personas ficticias. Exprese las ideas de posibles situaciones conflictivas de esa persona en las propuestas evaluadas. Asigne dos a Caso A y 2 al caso B
 

| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | TestA/B
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| User1's name  | H / 18   | Estudiante  | Media       | Introvertido | Web.       | A 
| User2's name  | H / 18   | Estudiante  | Media       | Timido       | Web        | A 
| User3's name  | M / 35   | Abogado     | Baja        | Emocional    | móvil      | B 
| User4's name  | H / 18   | Estudiante  | Media       | Racional     | Web        | B 


![Método UX](img/Survey.png). 4.c Cuestionario SUS
----

>>> Usaremos el **Cuestionario SUS** para valorar la satisfacción de cada usuario con el diseño (A/B) realizado. Para ello usamos la [hoja de cálculo](https://github.com/mgea/DIU19/blob/master/Cuestionario%20SUS%20DIU.xlsx) para calcular resultados sigiendo las pautas para usar la escala SUS e interpretar los resultados
http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
Para más información, consultar aquí sobre la [metodología SUS](https://cui.unige.ch/isi/icle-wiki/_media/ipm:test-suschapt.pdf)

>>> Adjuntar captura de imagen con los resultados + Valoración personal 


![Método UX](img/usability-report.png) 4.d Usability Report
----

>> Añadir report de usabilidad para práctica B (la de los compañeros)



>>> Valoración personal 


>>> ## Paso 5. Evaluación de Accesibilidad  (no necesaria)


>>> ![Método UX](img/Accesibility.png)  5.a Accesibility evaluation Report 
>>>> ----

>>> Indica qué pretendes evaluar (de accesibilidad) sobre qué APP y qué resultados has obtenido 

>>> 5.a) Evaluación de la Accesibilidad (con simuladores o verificación de WACG) 
>>> 5.b) Uso de simuladores de accesibilidad 

>>> (uso de tabla de datos, indicar herramientas usadas) 

>>> 5.c Breve resumen del estudio de accesibilidad (de práctica 1) y puntos fuertes y de mejora de los criterios de accesibilidad de tu diseño propuesto en Práctica 4.



## Conclusión final / Valoración de las prácticas


>>> (90-150 palabras) Opinión del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos  













