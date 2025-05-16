
<h1 align="center">
  <strong style="font-size:25px;">Universidad Informe de Trabajo Final</strong>
</h1>

---

<p align="center"><strong>Universidad Peruana de Ciencias Aplicadas</strong></p>

<p align="center">
  <img src="assets/images/Logos/LogoUPC.png" width="180" />
</p>

<p align="center">Ingenieria de Software</p>
<p align="center">5to ciclo</p>

---

<p align="center"><strong>Código: </strong>1ASI0730</p>
<p align="center"><strong>Curso:</strong> Aplicaciones Web</p>
<p align="center"><strong>Sección:</strong> 4374</p>

<p align="center"><strong>Docente:</strong> Alberto Wilmer Sanchez Seña</p>

<p align="center"><strong>StartUp: </strong>Cuys TM</p>
<p align="center"><strong>Proyecto:</strong> SafeCycle</p>



## Integrantes:
<div align="center">

| Nombres y Apellidos                  | Codigo     |
| ------------------------------------ | ---------- |
| Sanchez Gonzales                     | U202310609 |
| Mora Blas,  Diego Alonzo             | U20231c069 |
| Castañeda Guimas, Giancarlo Santiago | U202310601 |
| Gonzales Valverde, Carlos Matthew  | U202314130 |
| Jonseck Choque, Oliver | U202312912 |


</div>


<p align="center">Abril 2025</p>

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
| :---- | :---- | :---- | :---- |
| 1.0 | 01/04/2025 | Sanchez, Mora, Castañeda, Jonseck, Gonzales | Creación del documento Markdown |
| 1.1 | 01/04/2025 | Castañeda | Redacción del startup profile y antecedentes y problemáticas. |
| 1.2 | 02/04/2025 | Sanchez, Mora | Redacción de Lean UX process y preguntas para el diseño de entrevistas |
| 1.3 | 03/04/2025 | Castañeda, Sanchez | Redacción de segmentos objetivos. Redacción de user personas y user task matrix. |

# Project Report Collaboration Insights

## **TP1**

Para el desarrollo de la TP1 nos hemos dividido como equipo diferentes tareas para cada seccion del informe.

| Integrante | Tareas Asignadas |
| :---- | :---- |
| Sanchez Gonzales | Lean UX Problem Statements, Lean UX Hypothesis Statements, Lean UX Canvas, Análisis competitivo, Diseño de entrevistas, User Personas, User Task Matrix, As-is Scenario Mapping, General Style Guidelines, Web Style Guidelines, Landing Page UI Design, Web Applications Wireframes, Web Applications Mock-ups, Web Applications User Flow Diagrams, Sprint Backlog 1, Video About-the-Product |
| Mora Blas, Diego Alonzo | Lean UX Assumptions, Análisis de entrevistas, Epics & User Stories, Impact Mapping, Searching Systems, Navigation Systems, Software Architecture Context Diagram, Software Architecture Components Diagrams, Class Diagrams, Class Dictionary, Aspect Leaders and Collaborators, Development Evidence for Sprint Review, Registro de Entrevista, Evaluaciones según heurísticas |
| Castañeda Guimas, Giancarlo Santiago | Descripción de la Startup, Segmentos objetivo, Registro de entrevistas, Ubiquitous Language, To-Be Scenario Mapping, Software Architecture Context Diagram, Software Development Environment Configuration, Sprint Planning 1 |
| Gonzales Valverde, Carlos Matthew	 | Estrategias y tácticas frente a competidores, Registro de entrevistas, User Journey Mapping, Product Backlog, SEO Tags and Meta Tags, Source Code Management, Software Deployment Configuration, Execution Evidence for Sprint Review. Services Documentation Evidence for Sprint Review, Software Deployment, Evidence for Sprint Review |
| Jonseck Choque, Oliver | Análisis de entrevistas, Empathy Mapping, Epics & User Stories, Organization Systems, Labeling Systems, Web Applications Wireflow Diagrams, Software Architecture Context Diagrams, Software Architecture Container Diagrams, Class Diagrams, Database Diagram, Source Code Style Guide & Conventions, Team Collaboration Insights during Sprint, Conclusiones, Recomendaciones |

# Tabla de contenidos


[Capítulo I: Introducción](#capítulo-i-introducción)
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
  - [**TP1**](#tp1)
- [Tabla de contenidos](#tabla-de-contenidos)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
      - [1.1.2.1 Gabriel Sánchez Gonzales](#1121-gabriel-sánchez-gonzales)
      - [1.1.2.2 Giancarlo Santiago Castañeda Guimas](#1122-giancarlo-santiago-castañeda-guimas)
      - [1.1.2.3 Diego Alonzo Mora Blas](#1123-diego-alonzo-mora-blas)
      - [1.1.2.4 Gonzales Valverde Carlos Matthew](#1124-gonzales-valverde-carlos-matthew)
      - [1.1.2.5 Oliver Jonseck Choque](#1125-oliver-jonseck-choque)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)
  - [1.3 Segmentos objetivo.](#13-segmentos-objetivo)
    - [1.3.1 Segmento objetivo 1: Estudiantes pregrado](#131-segmento-objetivo-1-estudiantes-pregrado)
    - [1.3.2. Segmento Objetivo 2: Turistas](#132-segmento-objetivo-2-turistas)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1 Competidores.](#21-competidores)
    - [2.1.1 Análisis competitivo.](#211-análisis-competitivo)
    - [2.1.2 Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2 Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2 Registro de entrevistas.](#222-registro-de-entrevistas)
    - [2.2.3 Análisis de entrevistas.](#223-análisis-de-entrevistas)
  - [2.3 Needfinding](#23-needfinding)
  - [2.3.1 User Personas.](#231-user-personas)
    - [**Estudiante**:](#estudiante)
    - [**Turista**:](#turista)
  - [2.3.2 User Task Matrix.](#232-user-task-matrix)
    - [**Estudiantes**](#estudiantes)
    - [**Turistas**](#turistas)
  - [2.3.3 User Journey Mapping.](#233-user-journey-mapping)
  - [2.3.4 Empathy Mapping.](#234-empathy-mapping)
  - [2.3.5 As-is Scenario Mapping.](#235-as-is-scenario-mapping)
  - [2.4 Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services \& Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)

# Student Outcome

| Criterio Especifico | Acciones Realizadas | Conclusiones |
| :---- | :---- | :---- |
| Trabaja en equipo para proporcionar liderazgo en forma conjunta | **Sanchez Gonzales: *TB1*** Dentro de esta entrega me enfoque en avanzar con La redacción del Lean UX Problem Statements, Hypothesis Statements y Canvas. También desarrolle preguntas para el diseño de entrevistas, los user personas y user task matrix. Finalmente, Realice el análisis competitivo, diseño de entrevistas y As-is Scenario Mapping, Style Guidelines, Landing Page UI Design y Web Applications UX/UI Design <br> **Giancarlo Santiago:*TB1*** ...| Como equipo logramos tener un liderazgo de forma conjunto, puesto que, siempre discutimos acerca de las ideas con el fin de encontrar la mejor solución viable. Todos colaboramos en dar nuestras opiniones e ideas, logrando así un trabajo en conjunto exitoso. |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. | **Sanchez Gonzales: *TB1*** Dentro de esta entrega me enfoque en avanzar con La redacción del Lean UX Problem Statements, Hypothesis Statements y Canvas. También desarrolle preguntas para el diseño de entrevistas, los user personas y user task matrix. Finalmente, Realice el análisis competitivo, diseño de entrevistas y As-is Scenario Mapping, Style Guidelines, Landing Page UI Design y Web Applications UX/UI Design <br> **Giancarlo Santiago:*TB1*** ...| Como equipo logramos establecernos metas y tareas, creemos que al autoimponerse fechas para terminar de realizar ciertas secciones dentro del capítulo, nos ayudó a planificar y avanzar en conjunto. |

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup
Nuestra Startup “Cuys ™” ofrece una aplicación innovadora de préstamos de bicicletas “Safecycle” enfocadas a ayudar a estudiantes y turistas brindando una alternativa sostenible, accesible y segura para llegar a su destino. Ofrecemos una solución independiente al ofrecer las bicicletas como producto principal y contaremos con un modelo de negocio basado en los pagos que se realizarán en la aplicación por el préstamo de las bicicletas. Para ello investigaremos cómo cumplir con esta meta recolectando fuentes sobre modelos de negocios similares y planificamos el diseño y la codificación de nuestra solución.


### 1.1.2. Perfiles de integrantes del equipo

#### 1.1.2.1 Gabriel Sánchez Gonzales

Soy estudiante en la Universidad Peruana de Ciencias Aplicadas (UPC) cursando el 5to ciclo de la carrera de Ingeniería de Software. Soy una persona comprometida con mi desarrollo académico y profesional. Con esa responsabilidad, aspiro a proveer soluciones tecnológicas a aquellos que las requieran para facilitar su área de trabajo. Junto con mi equipo de trabajo tendré la oportunidad de poner mis conocimientos y habilidades en uso con el proyecto “Safecycle” con el fin de disminuir la problemática identificada. 

<img src="assets/images/profile-pictures/sanchez gonzales.png" width="180" />


#### 1.1.2.2 Giancarlo Santiago Castañeda Guimas
Estudiante de la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas cursando el 5to ciclo. Me considero una persona activa y que siempre busca terminar las cosas bien y de ser posible rápidamente. También me gusta la responsabilidad y el buen ambiente entre mis compañeros de grupo. 

<img src="assets/images/profile-pictures/Giancarlo Castañeda.jpg" width="180" />

#### 1.1.2.3 Diego Alonzo Mora Blas
Estudiante de la carrera de ingeniería de software en la UPC, cuento con habilidades como el aprendizaje rápido el cual me ha llevado a practicar y conocer diversas áreas como lo son la programación, la ciberseguridad y redes. Tengo el honor de trabajar con mi equipo el cual estoy seguro que nos aseguraremos de presentar un trabajo al nivel.

<img src="assets/images/profile-pictures/DiegoMora.PNG"  width="180" />

#### 1.1.2.4 Gonzales Valverde Carlos Matthew
Estudiante de la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas, me destaco en poder trabajar bajo a presion, tener una
escucha activa y apoyar a mis compañeros cuando mas lo necesiten, esto tambien me ayudo a explorar mas el mundo de la programacion y ahora la ciberseguridad
que quiero especializarme en ello. Agradezco a todo el grupo porque tenemos un ambiente adecuado y estoy seguro que podremos presentar un excelente trabajo.

<img src="assets/images/profile-pictures/Carlos Gonzales.png" width="180" />

#### 1.1.2.5 Oliver Jonseck Choque
Estudiante de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas, actualmente en el quinto ciclo. Me destaco por ser proactivo y enfocado en cumplir con mis responsabilidades de manera eficiente. Valoro el trabajo bien hecho y disfruto colaborar en entornos donde reina el respeto y la buena comunicación entre compañeros.

<img src="assets/images/profile-pictures/OliverJonseck.PNG" width="180" />

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática


 1. What? **(¿Cuál es el problema?)**

El problema es que las personas que se movilizan por Lima metropolitana no pueden realizar esta acción con facilidad, un tráfico inmenso en la ciudad. Esto causa que diversos individuos no puedan llegar a sus destinos a tiempo, e ir en vehículos personales cómo automóviles llega a ser muy caro o demanda la misma cantidad de tiempo. Consecuentemente diversas personas tienen que despertarse más temprano o incluso recurrir a utilizar opciones más caras cómo taxis.

 2. When? **(¿Cuándo sucede el problema?)**

Sucede cuando una persona tiene que llegar a un lugar a una hora designada y la gran mayoría de personas salen al mismo tiempo, generando una congestión, una ocurrencia muy común hoy en día vista en el país. Según un estudio realizado por la Asociación Automotriz del Perú en 2024, Lima es la ciudad con mayor congestión vehicular en América Latina.

 3. Where? **(¿Dónde surge el problema?)**

Surge en Lima metropolitana por zonas de alta concurrencia vehicular cómo calles principales, mercados, centros educativos y centros turísticos.

4. Who?  **(¿Quiénes están involucrados?)**

Los principales afectados son los habitantes y la gente que se traslada por Lima Metropolitana. Por ejemplo, los estudiantes, trabajadores y turistas.

5. Why **(¿Por qué ocurre el problema?)**

El problema ocurre debido a una estructura de transporte que no pudo evolucionar al mismo ritmo del aumento de necesidades de las personas. La baja cobertura del transporte público y alta urgencia que genera no logra cubrir la demanda de forma eficiente, obligando al uso de transporte particular, empeorando así la congestión vehicular, que en consecuencia termina en personas no llegando a tiempo a ciertos eventos o lugares e incluso con fatiga y molestia.

6. How **(¿Cómo se lleva a cabo el problema?)**

El problema se lleva a cabo cuando miles de personas en Lima metropolitana intentan movilizarse a una hora popular por vías congestionadas, generando embotellamientos y rutas vehiculares saturadas. La falta de un transporte accesible y económico incentiva a esta problemática, puesto que la gente que se traslada por Lima tiene que elegir entre un transporte público como son los buses o uno particular y poco económico como son los taxis o carros

7. How much **(¿Cuál es la magnitud del problema?)**

Medimos la magnitud del problema a través de entrevistas realizadas a un público de 30 personas que transitan diariamente en Lima Metropolitana

<img src="/assets/images/charts/1.png" width=800>

<img src="/assets/images/charts/2.png" width=800>

<img src="/assets/images/charts/3.png" width=800>

<img src="/assets/images/charts/4.png" width=800>

<img src="/assets/images/charts/5.png" width=800>

[Link a encuesta enviada](https://docs.google.com/forms/d/e/1FAIpQLSeA6pLs-rQHjfQKjtP-qf2gnkVFpHTSa95WKuD-IgsjbufGUw/viewform?usp=dialog)

[Link a resultados de encuesta](https://docs.google.com/spreadsheets/d/1tCFJkLHdxL313atSLzJCLOHC-6f2ujesVNoaYFEerGg/edit?usp=sharing)

Gracias a las encuestas realizadas se observó que un 86.7% no cuenta con un transporte fijo de transporte, un 63.3% cree que siempre tiene retrasos por el tráfico, un 93.3% se sentiría cómodo con el uso de una bicicleta como medio de transporte segura, económica y fácil de usar. Además, cuentan con una preferencia hacia los precios accesibles y seguridad de servicio en un 96.7% y 90% respectivamente. Finalmente el 80% de los encuestados piensan que una aplicación de alquiler de bicicletas les ayudaría a moverse mejor alrededor de la ciudad. Con esto podemos concluir que en efecto esta problemática es verdadera y concurrente dentro de Lima Metropolitana. La demanda es clara: los usuarios necesitan una alternativa confiable, segura y eficiente frente al actual caos del transporte urbano.

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements
Nuestra solución busca proveer un aplicativo que conecte a los estudiantes y turistas que no tengan un método de traslado fijo  con un medio de transporte eco amigable, rápido y accesible, como lo es la bicicleta, con el fin de que puedan desplazarse de un lugar a otro a través de esta misma. Asimismo, al garantizar la seguridad de los usuarios de estas bicicletas a través de bloqueos en casos un uso excesivo o por bloqueo del propio rentador, evitamos posibles robos y mal usos de las bicicletas.
Hemos observado que al no tener un transporte fijo tanto los estudiantes como turistas no pueden llegar a sus destinos propuestos a tiempo. El tráfico en Lima metropolitana y el acumulamiento de gente dentro de servicios de transporte público hacen la tarea de desplazamiento casi imposible, y tanto los estudiantes como los turistas no tienen una necesidad para comprarse un transporte personal para poder movilizarse. 
¿Cómo podemos ofrecer un transporte fiable y organizado, que los ayude a llegar a su destino?
Notamos que los estudiantes y turistas no desean pagar por un medio de transporte como son los taxis, puesto que las tarifas pueden llegar a exceder su presupuesto, pero tampoco se sienten cómodos al usar el transporte público, pues este es muy incomodo o los deja con mucha caminata hacia su destino final lo que termina generando una pérdida de tiempo. Esto repercusiona en que no pueden llegar a los destinos que desean a tiempo y terminan gastando más tiempo en el recorrido que en el propio lugar.
¿Cómo puede nuestra plataforma proveer a nuestro público con una manera más eficiente de transporte y movilización?


#### 1.2.2.2. Lean UX Assumptions

Creemos que los estudiantes y turistas en Lima enfrentan una falta de transporte fiable y económico, lo que genera retrasos e incomodidad, al ofrecer bicicletas accesibles mediante una app, creemos firmemente que  resolveremos esta necesidad. Nuestros segmentos objetivos priorizan el ahorro, prefiriendo nuestro servicio frente a taxis o transporte público costoso,además percibirán las bicicletas como una opción más cómoda al evitar el tráfico.La seguridad será clave, por lo que el sistema de bloqueo automático reducirá el miedo a robos, aumentando la confianza. Asumimos que la app será adoptada fácilmente ya que es intuitiva y garantiza transacciones seguras. 


#### 1.2.2.3. Lean UX Hypothesis Statements
Creemos que la eficacia con la que se movilizan los estudiantes y turistas aumentaría en un 80% debido a que se les proporcionará con una herramienta de transporte de acceso libre , como son las bicicletas, a través de un pago mínimo. Sabremos que estamos en lo correcto cuando se visualice un aumento de puntualidad hacia ciertos eventos.
Creemos que los estudiantes y turistas podrán viajar más cómodamente hacia sus destinos, proporcionándoles una mejor experiencia en general. Sabremos que estamos en lo correcto cuando a través de encuestas a usuarios se menciona seguidamente que la comodidad de sus viajes ha mejorado, concluyendo con más de un 70% de aprobación en cuanto a comodidad.
Creemos que nuestro servicio será 30% más económico que otros medios de transporte de la ciudad para los estudiantes y turistas. Sabremos que estamos en lo correcto al comparar la media de dinero que gastaban antes los usuarios en comparación con lo que gastan usando nuestro servicio.
Creemos que la implementación de este sistema de préstamo de bicicletas puede reducir hasta un 20% la congestión vehicular que se presencia en zonas de rutas universitarias y rutas turísticas. Sabremos que estamos en lo correcto cuando se visualice un cambio en las paradas de transporte público, mostrando que más personas pueden entrar en los buses y menos personas recurren a los taxis.
Creemos que los usuarios se sentirán más seguros usando las bicicletas sabiendo que estas tienen un sistema de bloqueo automático que solo se activa solo cuando el tiempo de préstamo se sobrepasa o si la bicicleta es reportada como robada. Sabremos que estamos en lo correcto a través de entrevistas a los usuarios acerca de la confianza que le tienen a las bicicletas.

#### 1.2.2.4. Lean UX Canvas.

| Business Problem | Solution Ideas | Business Outcomes |
| :---- | :---- | :---- |
| Nuestra solución busca proveer un aplicativo que conecte a los estudiantes y turistas que no tengan un método de traslado fijo  con un medio de transporte eco amigable, rápido y accesible, como lo es la bicicleta, con el fin de que puedan desplazarse de un lugar a otro a través de esta misma. Asimismo, al garantizar la seguridad de los usuarios de estas bicicletas a través de bloqueos en casos un uso excesivo o por bloqueo del propio rentador, evitamos posibles robos y mal usos de las bicicletas. Hemos observado que al no tener un transporte fijo tanto los estudiantes como turistas no pueden llegar a sus destinos propuestos a tiempo. El tráfico en Lima metropolitana y el acumulamiento de gente dentro de servicios de transporte público hacen la tarea de desplazamiento casi imposible. Además, tanto los estudiantes como los turistas no tienen la necesidad de comprarse un transporte personal para poder movilizarse.  ¿Cómo podemos ofrecer un transporte fiable y organizado, que los ayude a llegar a su destino? Notamos que los estudiantes y turistas no desean pagar por un medio de transporte como son los taxis, puesto que las tarifas pueden llegar a exceder su presupuesto, pero tampoco se sienten cómodos al usar el transporte público, pues este es muy incomodo o los deja aun con mucha caminata hacia su destino, generando una pérdida de tiempo. Esto repercusiona en que no pueden llegar a los destinos que desean de forma puntual y terminan gastando más tiempo en el recorrido que en el propio lugar. ¿Cómo puede nuestra plataforma proveer a nuestro público con una manera más eficiente de transporte y movilización? | Brindar un préstamo de bicicleta para que los estudiantes o turistas puedan movilizarse por un costo. Integrar un sistema de bloqueo automático para evitar un mal uso de las bicicletas. Contar con un sistema de recojo y devolución a través de diferentes estaciones | Los estudiantes usarán más nuestra plataforma que el transporte público habitual en un 30%. Control adecuado a las bicicletas gracias a su sistema de seguridad, reduciendo en un 20% de probabilidades de mal uso Retención de usuarios en un 50% después del primer mes Aumento de visibilidad de la plataforma en un 40% por los usuarios que la comparten |
| Hypothesis | Users & Customers | User Benefits |
| Creemos que la eficacia con la que se movilizan los estudiantes y turistas aumentaría en un 80% debido a que se les proporcionará con una herramienta de transporte de acceso libre, como son las bicicletas, a través de un pago mínimo. Sabremos que estamos en lo correcto cuando se visualice un aumento de puntualidad hacia ciertos eventos. Creemos que los estudiantes y turistas podrán viajar más cómodamente hacia sus destinos, proporcionándoles una mejor experiencia en general. Sabremos que estamos en lo correcto cuando a través de encuestas a usuarios se menciona seguidamente que la comodidad de sus viajes ha mejorado, concluyendo con más de un 70% de aprobación en cuanto a comodidad. Creemos que nuestro servicio será 30% más económico que otros medios de transporte de la ciudad para los estudiantes y turistas. Sabremos que estamos en lo correcto al comparar la media de dinero que gastaban antes los usuarios en comparación con lo que gastan usando nuestro servicio. Creemos que la implementación de este sistema de préstamo de bicicletas puede reducir hasta un 20% la congestión vehicular que se presencia en zonas de rutas universitarias y rutas turísticas. Sabremos que estamos en lo correcto cuando se visualice un cambio en las paradas de transporte público, mostrando que más personas pueden entrar en los buses y menos personas recurren a los taxis. Creemos que los usuarios se sentirán más seguros usando las bicicletas sabiendo que estas tienen un sistema de bloqueo automático que solo se activa solo cuando el tiempo de préstamo se sobrepasa o si la bicicleta es reportada como robada. Sabremos que estamos en lo correcto a través de entrevistas a los usuarios acerca de la confianza que le tienen a las bicicletas. | Estudiantes universitarios de pregrado que deseen llegar a su destino rápidamente y evitar el tráfico. Turistas que requieran un transporte personal temporal sin la necesidad de rentar un automóvil. | Tener acceso a un transporte personal económico, amigable con el medio ambiente y disponible en cualquier momento Movilizarse rápida y eficazmente alrededor de la ciudad. Llegar más puntuales a diferentes eventos o lugares, proporcionando un mayor tiempo en el lugar y menos tiempo de movilización. Reducir sus gastos de transporte gracias a su precio accesible. Contribuir a una mejora en el medio ambiente al usar un medio de transporte ecoamigable  |
|  | What’s the most important thing we need to learn first?  | What’s the least amount of work we need to learn the next most important thing?    |
|  | Determinar si los estudiantes y turistas están dispuestos a pagar por el servicio propuesto. Verificar que los usuarios de estas bicicletas no les den un mal uso a las mismas. | Diseñar entrevista con preguntas concretas a una estadística Desplegar una versión de prueba con pocas bicicletas en puntos estratégicos para detectar posibles problemas iniciales |

## 1.3 Segmentos objetivo.
### 1.3.1 Segmento objetivo 1: Estudiantes pregrado
**Descripción:** 
Los estudiantes tienen una vida agitada, una rutina dinámica y ajustada a horarios específicos. Por las mañanas muchos deben desplazarse desde sus residencias hacia sus centros de educación en poco tiempo, además del agobiante tráfico y algunos teniendo que lidiar con el transporte público.
**Caracteristicas:**
- Edad: 18 a 30 años 
- Ubicación: Zonas urbanas, suelen vivir cerca de sus centros de educación 
- Nivel socioeconomico: Clase Media	    
### 1.3.2. Segmento Objetivo 2: Turistas
**Descripción:** 
Los turistas buscan maximizar su tiempo explorando nuevas partes de la ciudad de una manera cómoda y accesible, ya sean centros turísticos como museos, atracciones o centros históricos. Para ello requiere gastar e invertir un buen capital, además considerando el tráfico en el Perú esto no puede ser tanto del agrado del turista. 
**Caracteristicas:**
- Edad: 18 a 50 años 
- Ubicación: Zonas urbanas con alto índice de turismo, puntos de intereses históricos o culturales
- Nivel socioeconomico: Clase Media - Alta

# Capítulo II: Requirements Elicitation & Analysis
## 2.1 Competidores.
### 2.1.1 Análisis competitivo.

| **Competitive Analysis Landscape** | **Escriba en el recuadro la pregunta que busca responder o el objetivo de este análisis.** |
| :---- | :---- |
| ¿Por qué llevar a cabo este análisis?  | Deseamos analizar a nuestros competidores para buscar en qué puntos podemos mejorar, contra que nos estamos enfrentando en el mercado y como nos distinguimos de estos |

|  |  | ![Logo Safe Cycle](/assets/images/Logos/LogoSafeCycle.png)  Safecycle | ![Logo City Bike Lima](/assets/images/Logos/CityBikeLimaLogo.png) CityBikeLima | ![Logo Barranco Bikes](/assets/images/Logos/BarrancoBikesLogo.jpg) Barrancobikes | ![Logo Mira Bici](/assets/images/Logos/MiraBiciLogo.png) Mirabiciperu |
| :---- | :---- | ----- | :---- | :---- | :---- |
| Perfil | Overview Ventaja competitiva  | Plataforma direccionada hacia la renta por minuto de las bicicletas, las cuales se pueden reservar desde la aplicación y posteriormente. | Servicio presencial en el cual se rentan bicicletas por un tiempo de 30 minutos gratis a través de pases mensuales, anuales o diarios y pagados por la pantalla de la bicicleta. | Una plataforma en la que puedes pagar por una bicicleta por horas, días o semanas alrededor de Barranco | Plataforma que ofrece una reservas de bicicletas a través de rutas turísticas |
|  | ¿Qué valor ofrece a los clientes? | • Devolución de bicicletas en cualquier estación. <br>• Cobro por minuto. <br>• Seguro automatico. <br>• Paquetes de descuento a estudiantes <br>• Planes por horas | • Tarjeta con pases anuales <br>• Desbloqueo de bicicleta con código o tarjeta <br>• Devolución de bicicletas en cualquier estación. <br>• Servicio de pausa de la bicicleta | • Renta de bicicletas por horas, días y semanas <br>• Proporciona elementos de seguridad Delivery de bicicleta | • 3 rutas de turismo  <br>• Ofrece una renta de bicicleta por duración de tour  |
| Perfil de Marketing | Mercado objetivo  | • Estudiantes de pregrado Turistas | • Residentes de San Isidro | • Residentes de Barranco Turistas | • Turistas |
|  | Estrategias de marketing | • Códigos de referencia por parte de otros usuarios para descuentos <br>• Descuentos hacia los estudiantes <br>• Tutoriales acerca de uso | • Registro a través de pases y tarjetas 30 primeros minutos gratis <br>• Tutoriales acerca de uso | • Añade un descuento de consumo a un restaurante afiliado | • Tours en grupo <br>• Opiniones de otros usuario en la misma página web |
| Perfil de Producto | • Productos & Servicios  | • Renta de Bicicleta | • Tarjeta de pago para bici <br>• Renta de Bicicleta | • Casco y cadena incluido con la renta <br>• Renta de Bicicleta | • Tours en zonas culturales, con explicación en bicicleta <br>• Servicios técnico y de repuesto |
|  | Precios & Costos  | • **Estudiantes:**  S/. 0.035 / minuto <br>• **Tarifa General:**  S/. 0.045 / minuto <br>• **Tarifa Inicial:**  S/. 1.00 / minuto | • **Minuto 0 al 30:** Sin costo <br>•**31 al 120:**  S/ 2.00 cada 30 minutos o fracción <br>• **121 a más:**  S/ 7.00 cada hora o fracción | • **02 horas:**  S/. 25.00 <br>• **03 horas:**  S/ 30.00 <br>• **05 horas:**  S/ 45.00 <br>• **Más de 05 horas:**  S/ 55.00 | • **Ruta 1:** USD 35 S/. 133 <br>• **Ruta 2:** USD 25 S/. 95 <br>• **Ruta 3:** USD 35 S/. 133 |
|  | Canales de distribución (Web y/o Móvil)  | Web y Móvil | Presencial Web y Móvil | Web | Web |
| Análisis SWOT | Fortalezas | • Tarifa accessible Adaptable a otros dispositivos | Diferentes formas de renta <br>• Prueba gratuita para atraer clientes <br>•  Tarifa accessible | • Delivery a la puerta de tu casa <br>• Elementos extra proporcionados  | • Tours con guia turistico. <br>• Función para rentar en grupo |
|  | Debilidades | • Dependencia a internet Dependencia a disponibilidad <br>• Riesgo de vandalismo <br>• Bajo conocimiento de marca inicial. | • Riesgo de vandalismo <br>• Dificultad de uso para personas sin mucho conocimiento tecnológico <br>• Reubicación de bicicletas por congestión | • Dependencia a disponibilidad Bajo conocimiento de marca inicial. | • Dependencia a disponibilidad <br>• Falta de confianza de usuario |
|  | Oportunidades | • Alianzas con centros educativos o cadenas de turismo Subvención gubernamental por negocio eco-friendly <br>• Incorporar nuevos tipos de transporte | • Incorporar nuevos tipos de transporte <br>• Expansión de distritos disponibles | • Expansión de distritos disponibles | • Mayor cantidad de tours disponibles <br>• Alianza con hoteles |
|  | Amenazas | • Competencia en el mercado alta<br>• Robo o hackeos | • Problemas por clima o infraestructura | • Quejas por demora de renta | • Cambios de normativas de rutas <br>• Poca retención de usuarios |

### 2.1.2 Estrategias y tácticas frente a competidores
## 2.2 Entrevistas
### 2.2.1 Diseño de entrevistas
Como se mencionó anteriormente, nuestros segmentos objetivos están conformados por estudiantes universitarios de pregrado, principalmente aquellos que viven en cercanías de la universidad y turistas.

Después de solicitarles sus datos personales básicos como nombres, apellidos, edad y distrito de estadía, se les preguntará lo siguiente a los entrevistados.

**Preguntas a realizar:**

**Generales:**

¿Cuál es tu nombre y apellidos?

¿Cuántos años tienes?

¿Cuál es tu lugar de nacimiento?

**Estudiantes:**

- ¿Cómo te transportas habitualmente en tu día a día?

- ¿Cuánto tiempo te demora normalmente para llegar a tu destino?

- ¿Has usado bicicletas anteriormente como medio de transporte antes? ¿Cuál fue la razón?

- ¿Cuáles son las principales dificultades que enfrentas al moverte alrededor de la ciudad?

- ¿Qué tan cómodo es ir en el transporte que usas actualmente para llegar a tu destino?

- En una escala del 1 al 5, ¿Qué tan dispuesto estarías a usar un servicio de préstamo de bicicletas?

- ¿Cuanto estas pagando actualmente en tus servicios de transporte semanalmente?

- ¿Cuánto estarías dispuesto a pagar por un servicio de alquiler de bicicletas?

- ¿Te sentirías más seguro y confiado acerca del sistema sabiendo que la bicicleta se bloquea automáticamente si excedes el tiempo del préstamo o se detecta como robada?

- ¿Has usado anteriormente algún servicio de préstamo de bicicletas? ¿Qué te llamó la atención y que no?

**Turistas:**

- ¿Cómo te transportas habitualmente en tu estadía?

- ¿Cuánto tiempo te demora normalmente para llegar a tu destino?

- ¿Has usado bicicletas anteriormente como medio de transporte antes? ¿Cuál fue la razón?

- ¿Cuáles son las principales dificultades que enfrentas al moverte alrededor de la ciudad?

- ¿Qué tan cómodo es ir en el transporte que usas actualmente para llegar a tu destino?

- En una escala del 1 al 5, ¿Qué tan dispuesto estarías a usar un servicio de préstamo de bicicletas?

- ¿Cuanto estas pagando actualmente en tus servicios de transporte semanalmente?

- ¿Cuánto estarías dispuesto a pagar por un servicio de alquiler de bicicletas?

- ¿Te sentirías más seguro y confiado acerca del sistema sabiendo que la bicicleta se bloquea automáticamente si excedes el tiempo del préstamo o se detecta como robada?

- ¿Has usado anteriormente algún servicio de préstamo de bicicletas? ¿Qué te llamó la atención y que no?
### 2.2.2 Registro de entrevistas.
### 2.2.3 Análisis de entrevistas.
## 2.3 Needfinding
## 2.3.1 User Personas.
### **Estudiante**: 
![User Persona Anne Guillen](/assets/images/user-personas/Anne%20Guillen%20(2).png)
[Link a UXpresia de Anne Guillen](https://uxpressia.com/w/2JtXc/p/tbFfu)
<br>
### **Turista**: 
![User Persona Mateo Smith](/assets/images/user-personas/Mateo%20Smith.png)
[Link a UXpresia de Mateo Smith](https://uxpressia.com/w/2JtXc/p/Wfgtx)
## 2.3.2 User Task Matrix.
### **Estudiantes**

| Actividades | Frecuencia | Importancia |
| ----- | ----- | ----- |
| Buscar entre opciones de transporte accesibles y económicas al bolsillo | Media | Alta |
| Determinar el tiempo que tomará el viaje hacia su destino | Alta | Alta |
| Planificar el costo del viaje a realizar | Media | Alta |
| Ajustar horarios para llegar puntualmente a los eventos | Alta | Alta |
| Evaluar si usar un transporte público o invertir en un taxi | Baja | Media |

### **Turistas**

| Actividades | Frecuencia | Importancia |
| ----- | ----- | ----- |
| Buscar entre opciones de transporte accesibles y económicas al bolsillo | Media | Alta |
| Determinar el tiempo que tomará el viaje hacia su destino | Alta | Alta |
| Planificar el costo del viaje a realizar | Media | Alta |
| Ajustar horarios para llegar puntualmente a los eventos | Alta | Alta |
| Evaluar si usar un transporte público o invertir en un taxi | Baja | Media |
| Programar visitas y turismo evitando las horas más congestionadas del tráfico | Baja | Media |
## 2.3.3 User Journey Mapping.
## 2.3.4 Empathy Mapping.
## 2.3.5 As-is Scenario Mapping.
## 2.4 Ubiquitous Language

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration  

Esta sección establece el listado oficial del software, herramientas y plataformas que los miembros del equipo de la startup usaron para garantizar coherencia, colaboración y eficiencia en la construcción y mantenimiento de la web application

| Actividad | Producto | Proposito | Ruta de referencia |
| :---- | :---- | :---- | :---- |
| Project Management | Trello | Planificación, seguimiento y gestión de tareas ágiles. (Sprints, Product Backlog, etc.) | [https://trello.com](https://trello.com/) |
| Product UX/UI Design | Figma | Diseño de interfaces de usuario, landing page y prototipado | [https://figma.com](https://figma.com) |
| Software Development | Visual Studio Code | Edición y desarrollo de código para interfaces web y móvil | [https://code.visualstudio.com/](https://code.visualstudio.com/) |
| Software Deployment | Github Pages | Despliegue de la landing Page | [https://pages.github.com/](https://pages.github.com/) |
| Software Documentation | Markdown \+ StackEdit.io | Redacción y despliegue de documentación técnica. | [https://stackedit.io](https://stackedit.io) |
| Version Control | GIT (Github) | Control de versiones y revisiones de código | [https://github.com](https://github.com) |

### 5.1.2. Source Code Management  

La administración y estructuración de las múltiples modificaciones se realizaron mediante la creación de un repositorio en GitHub para el proyecto. Nuestra organización se estructuró de la siguiente manera:

* **Organización**

| Producto | Repositorio | URL |
| :---- | :---- | :---- |
| Repositorio en Github | SafeCycle | [https://github.com/orgs/1ASI0730-2510-4374-G1-SafeCycle/repositories](https://github.com/orgs/1ASI0730-2510-4374-G1-SafeCycle/repositories) |
| Landing Page | SafeCycle-Landing-Page | [https://github.com/1ASI0730-2510-4374-G1-SafeCycle/landing\_page](https://github.com/1ASI0730-2510-4374-G1-SafeCycle/landing_page) |


* **Ramas Principales:** 

Se usara el flujo de trabajo GitFlow para tener nuestras ramas correctamente estructuradas y usar buenas prácticas de GIT

Para ello se crearán:

- Una rama de producción.  
- Una rama de pruebas.  
- Una rama de features a implementar.

Teniendo en cuenta la información anterior lo usaremos para crear un tipo de organización para las branches: 

- Main branch: Esta rama está destinada a la producción de la aplicación, cada cambio deberá tener autorización de un compañero de equipo para evitar cambios sin verificar.  
- Develop branch: Esta rama está destinada a las constantes implementaciones en caliente de los features  
- Features branch: Cada feature poseerá su respectiva rama, una vez que se encuentre correctamente implementada será fusionada con Develop branch.

### 5.1.3. Source Code Style Guide & Conventions  

 Usaremos buenas prácticas en cuanto al código de manera que sea coherente y sostenible.

  **HTML:**

- Cada etiqueta, id, nombre y clase será nombrada usando Lowercase.  
- Utilizar UTF-8  
- Redacción en inglés.  
- En cada referencia a un archivo, colocar el tipo de archivo (.css, .js).  
- Terminar cada etiqueta con /\>.

  **Etiquetas de HTML usadas:** 

  Se usó diferentes etiquetas para conformar la estructura del Landing Page del producto

- .header: Esta etiqueta define todo el contenido introductorio de la página web, como por ejemplo la barra de búsquedas  
- .nav: Define las secciones de la página que estarán dedicadas a la navegación en la página  
- div: Esta etiqueta permite la separación de diferentes objetos dentro de nuestra página, esto nos permitió poder aplicar hojas de estilo específicas para cada parte de los objetos  
- .img: Esta etiqueta permite la inserción de imágenes en la página web, se usó en diversas ocasiones dentro de la página  
- ul: Esta etiqueta sirve para definir una lista desordenada, mayor mente se usó para la elaboración del menú interactivo de la página  
- .li: Sirve para definir los elementos de las listas que se implementaron en la página, más específico en la barra de búsqueda y el blog  
- .a: También llamado “Anchor”, se usó para definir hipervínculos para mover a los usuarios a través de las diferentes secciones de la página  
- .p: Definen los párrafos de texto, separándolos del resto de contenido.button: Declaran un botón interactivo modificable que permite a los usuarios realizar una acción en específico  
- h1 \- h4: Definen los diferentes títulos y subtítulos de la página siendo h1 el mayor nivel y h4 el más bajo

  **CSS:**

- En cuanto a las imágenes, especificar el ancho (Width) de acuerdo a la etiqueta padre.  
- Cada etiqueta, nombre y clase será nombrada de acuerdo al propósito y clasificación del elemento  
- Separación de palabras con un guión "-"  
- Margin y padding en "\*" con valor de 0

### 5.1.4. Software Deployment Configuration  

Consideraciones que se tuvo antes del despliegue:
Archivos HTML, CSS y JS Asegúrese que todos los archivos de la página web sean implementados en HTML, CSS y JS para un correcto funcionamiento de la página. En el caso de la imágenes tuvimos que corregir algunos hipervínculos los cuales funcionaban correctamente en un live server pero al momento del deploy no funcionaban bien
Publicación de archivos Debido al funcionamiento del servicio de Github Pages, todos los archivos correspondientes al funcionamiento de nuestra aplicación será subidos al repositorio compartido de Github para poder trabajar de manera simultánea entre los integrantes del grupo
Creamos un repositorio en la organización de nuestro equipo en GitHub, donde subimos los archivos necesarios para desplegar la landing page. El despliegue se realizó mediante GitHub Pages. 
1. Subimos los archivos requeridos al repositorio correspondiente.
2. Luego, accedemos a Settings y localizamos la opción Pages. En el apartado de Branch, seleccionamos la rama main y guardamos los cambios. 
3. Tras unos minutos, GitHub genera el enlace de acceso a nuestra página web. 


## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1  
#### 5.2.1.1. Sprint Planning 1  

| Sprint \# | 1 |
| :---- | :---- |
| Sprint Planning Background |  |
| Date | 2025-22-04 |
| Time | 12:00 PM |
| Location | Discord |
| Prepared by | Giancarlo Castañeda |
| Attendees (to planning meeting) | Carlos Gonzales, Oliver Jonseck, Diego Mora, Sanchez Gonzales  |
| Sprint n – 1 Review Summary | Se realizó la landing page implementada con css y html, a raíz de los mockups y wireframes del diseño del landing page |
| Sprint n – 1 Retrospective Summary | Mejorar la puntualidad en la entrega de artefactos. |
| Sprint Goal & User Stories |  |
| Sprint 1 Goal | Nuestro enfoque para este sprint es implementar la landing page de nuestro producto. Creemos que esto brindará una correcta presentación de nuestro producto hacia los visitantes. Esto se confirmará cuando todas las secciones de nuestra página web sean visitadas por cada visitante. |
| Sprint 1 Velocity | Para este sprint nuestro equipo puende aceptar hasta 50 story points |
| Sum of Story Points | Para este sprint haremos 49 story points |

#### 5.2.1.2. Aspect Leaders and Collaborators 

| Team Member (Last Name, First Name)  | GitHub Username | Aspect Diseño UX/UI y Prototipado (L/C) | Aspect Programación de la Landing Page (L/C) | Aspect Arquitectura de Información y Sistemas de Organización/Navegación (L/C) |
| ------------------------------------ | --------------- | --------------------------------------- | -------------------------------------------- | --------------------------------------------------------------------------------------------- |
| Sanchez Gonzales                     | yigabriel       | L                                       | L                                            | C                                                                                             |
| Mora Blas, Diego Alonzo              | diegoalonzomora | C                                       | L                                            | L                                                                                             |
| Castañeda Guimas, Giancarlo Santiago | Darksens01      | C                                       | C                                            | C                                                                                             |
| Jonseck Choque, Oliver               | Olizzy-upc      | C                                       | C                                            | L                                                                                             |
| Gonzales Valverde, Carlos Matthew    | Carlos12324     | C                                       | C                                            | C                                                                                             |

#### 5.2.1.3. Sprint Backlog 1  

| Id | Title | Id | Title | Description | Estimation (Hours)  | Assigned To | Status (To-do / InProcess / ToReview / Done) |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| US233 | Navigation Bar | T1 | Header o Navigation Bar  | Crear un header con botones hipervínculos a diferentes secciones de la landing page | 5 | Diego Mora | Done |
| US05 2 | Acceder a la página inicio de sesión desde el botón “Iniciar sesión” | T2 | Boton Call-to-Action de header | Añadir botón call-to-action en la navbar para que pueda ser usado para redireccionar al usuario a una página de inicio de sesión | 4 | Diego Mora | Done |
| US01 1 | Ver el nombre, logo y eslogan de la aplicación | T3 | Hero sección | Crear la sección Hero de la landing page | 5 | Gabriel Sanchez | Done |
| US04 1 | Ver un botón destacado “Empieza ahora” en la sección principal del landing | T4 | Boton Call-to-Action de Hero  | Añadir botón call-to-action en el Hero Section para que pueda ser usado para redireccionar al usuario a una página de registro | 4 | Gabriel Sanchez | Done |
| US02 3 | Visualizar principales funciones | T5 | Que ofrecemos sección | Añadir sección donde se visualiza lo que ofrece la aplicación | 5 | Gabriel Sanchez | Done |
| US06 5 | Acceder a la página de registro de estudiante a través de botón “Aplicar para tarifa estudiante” | T7 | Botón Call-to-Action para los estudiantes de Planes | Añadir botón call-to-action en la sección de planes para que pueda ser usado para redireccionar al estudiante a una página de registro | 4 | Gabriel Sanchez | Done |
| US07 2 | Acceder a la página de registro de turista a través de botón “Empezar como turista” | T8 | Botón Call-to-Action para los turistas de Planes | Añadir botón call-to-action en la sección de planes para que pueda ser usado para redireccionar al turista a una página de registro | 4 | Gabriel Sanchez | Done |
| US03 5 | Visualizar precios y tarifas | T9 | Tarifas sección | Añadir sección donde se visualiza los precios de la aplicación | 5 | Gabriel Sanchez | Done |
| US24 3 | Sección How does it work | T10 | Cómo funciona sección | Añadir sección donde se visualiza el funcionamiento de la aplicación | 5 | Gabriel Sanchez | Done |
| US25 5 | Sección Porque Nosotros | T11 | Porque nosotros sección | Añadir sección donde se visualiza el porque elegir usar la aplicación | 5 | Gabriel Sanchez | Done |
| US26 1 | Footer | T12 | Sección footer | Añadir sección donde se visualiza los métodos de contacto de SafeCycle | 4 | Gabriel Sanchez | Done |
| US27 2 | Cambio de lenguaje a ingles y español en Landing Page  | T13 | Opciones de cambio de lenguaje | Añadir botones de cambio de idioma y lógica de elección de lenguaje default | 6 | Gabriel Sanchez | Done |
| US28 5 | Atributos Aria | T14 | Implementar atributos Aria | Añadir atributos aria a los elementos para que puedan ser leídos por lectores de pantalla | 4 | Gabriel Sanchez | Done |
| US31 8 | Acceder a Landing page desde cualquier dispositivo | T15 | Anadir elementos responsive | Implementar código para que la landing page sea responsive a los diferentes tamaños de pantalla | 4 | Giancarlo Castañeda, Carlos Gonzales | Done |
#### 5.2.1.4. Development Evidence for Sprint Review  

A continuación se muestran los commits realizados por los integrantes del equipo, se obviaron los merges y commits incorrectos por razones de mejor visualización acerca de los commits correctamente desarrollados e implementados:

| Repository  | Branch  | Commit Id  | Commit Message  | Commit Message Body  | Commited on (Date) |
| :---- | :---- | :---- | :---- | :---- | :---- |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/hyperlinks | 065ed9a | fix: fix social hiperlinks for deploying | \* No aplica | 24/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/responsive | 3c9e7a3 | feat: add responsive to the footer | \* No aplica | 23/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/responsive | 3b43b16 | feat: add responsive to the whyus section | \* No aplica | 23/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/responsive | add0215 | feat: add responsive to the steps | \* No aplica | 23/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/responsive | b517f61 | feat: add responsive to the fees | \* No aplica | 23/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/responsive | a066373 | feat: add responsive to the plans | \* No aplica | 23/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/responsive | c023614 | feat: add responsive to the whatweoffer section | \* No aplica | 23/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/responsive | f9765d1 | feat: add responsive to the stadistics | \* No aplica | 23/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/responsive | ad8fbbd | feat: add responsive to the introduction | \* No aplica | 23/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/responsive | 29df595 | fix: expand banner on desktop view | \* No aplica | 18/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/language | b75eca9 | feat: add JSON file languages | \* No aplica | 18/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/language | a11e895 | feat: add JS file for translation | \* No aplica | 18/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/language | bc34ca8 | feat: modify CSS for translation | \* No aplica | 18/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/language | 29f87d5 | feat: modify HTML for translation | \* No aplica | 18/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/aria | cf9130a | feat: add ARIA attributes HTML | \* No aplica | 15/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/hyperlinks | 87a9a6f | feat: add HTML hyperlinks | \* No aplica | 15/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/footer | 92b80a2 | feath: add CSS footer section | \* No aplica | 15/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/footer | 1cb80f1 | feat: add HTML footer section | \* No aplica | 15/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/WhyUs | 30c0ded | feat: add CSS WhyUs section | \* No aplica | 15/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/WhyUs | a04e48d | feat: add HTML Why Us section | \* No aplica | 15/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/howdoesitwork | ff48898 | feat: add CSS how does it work section | \* No aplica | 15/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/howdoesitwork | 3cc8e79 | feat: add HTML how does it work section | \* No aplica | 15/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/plans | b7cfec6 | feat: add CSS buttons transitions | \* No aplica | 15/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/plans | f9d0170 | feat: add CSS plans section | \* No aplica | 14/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/plans | 69bf2b3 | feat: add HTML plans section | \* No aplica | 14/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/whatweoffer | f64a897 | feat: add html what we offer section | \* No aplica | 14/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/whatweoffer | e576e1f | feat: add css what we offer section | \* No aplica | 14/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/stadistics | 602d737 | feat: add stadistics html | \* No aplica | 14/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/stadistics | 1dd94f2 | feat: add stadistics css | \* No aplica | 14/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/navbar | ac685dc | fix: navbar css | fixed navbar | 14/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/navbar | f3676c2 | chore: add index.html | \* No aplica | 12/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/navbar | 279ea09 | chore: add style.css | \* No aplica | 12/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/navbar | 18f7c4d | chore: add logo.png in assets/images | \* No aplica | 12/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/navbar | b75a55f | feat: add initial HTML structure with navbar | \* No aplica | 12/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/navbar | 33cffed | feat: add initial styles for navbar and layout | \* No aplica | 12/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/navbar | 232327e | feat: add assets for landing page | \* No aplica | 12/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/navbar | 4831484 | chore: delete assets/images/logo.png | \* No aplica | 12/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/navbar | 7ea9b37 | chore: update logo image source | \* No aplica | 12/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/navbar | 0db56e1 | style: add active state to login button | \* No aplica | 12/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/navbar | d5f4265 | fix: change to content of navbar | \* No aplica | 12/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/introduction | 2eb73eb | feat: add HTML introduction section to landing page | \* No aplica | 12/04/2025 |
| 1ASI0730-2510-4374-G1-SafeCycle landing\_page | feature/introduction | b2bef10 | feat: add CSS introduction section to landing page | \* No aplica | 12/04/2025 |

| \* No aplica | No se presento una descripción para estos commits |
| :---- | :---- |

#### 5.2.1.5. Execution Evidence for Sprint Review  

<img src="assets/images/collabEvidence/1.png" width=600>
<img src="assets/images/collabEvidence/2.1.png" width=600>
<img src="assets/images/collabEvidence/2.png" width=600>
<img src="assets/images/collabEvidence/land5.png" width=800>

<img src="assets/images/collabEvidence/lannd.png" width=800>
<img src="assets/images/collabEvidence/land2.png" width=800>
<img src="assets/images/collabEvidence/land3.png" width=800>
<img src="assets/images/collabEvidence/land4.png" width=800>

#### 5.2.1.6. Services Documentation Evidence for Sprint Review  

Dentro de este primer sprint no se contempló el uso de servicios


#### 5.2.1.7. Software Deployment Evidence for Sprint Review 

Para la entrega de este Sprint número 1, se desplegó el landing page parcialmente completo. Los hipervínculos a botones que lleven a la aplicación web y otros importantes se implementaran en posteriores entregas. Los bugs relacionados al responsive tambien se arreglaran en próximas entregas.


#### 5.2.1.8. Team Collaboration Insights during Sprint  

| Participante | Actividades de implementación |
| :---- | :---- |
| Sanchez Gonzales | Navigation bar, Hero Section, Statistics, WhatweOffer, Plans, Fees, HowdoesitWork, WhyUs, Footer |
| Mora Blas,  Diego Alonzo | Navigation bar, Hero Section, Responsive features |
| Gonzales Valverde, Carlos Matthew, Castañeda Guimas, Giancarlo Santiago | Responsive features |

<img src="assets/images/collaboration-insights/insightsc1.png" width=800>
<img src="assets/images/collaboration-insights/insightsc2.png" width=800>

### 5.2.2. Sprint 2

#### 5.2.2.1 Sprint planning 2

| Sprint \# | 2 |
| :---- | :---- |
| Sprint Planning Background |  |
| Date | 2025-13-05 |
| Time | 12:00 PM |
| Location | Discord |
| Prepared by | Giancarlo Castañeda |
| Attendees (to planning meeting) | Carlos Gonzales, Oliver Jonseck, Diego Mora, Sanchez Gonzales  |
| Sprint n – 2 Review Summary | Se realizó las correcciones correspondientes observadas por el profesor, ademas de la creación y deployamiento de la Web App |
| Sprint n – 2 Retrospective Summary | Creemos que hay oportunidad de hacer una mejor planificación de tiempos para la integraciones y revisiones  |
| Sprint Goal & User Stories |  |
| Sprint 2 Goal | El objetivo de este sprint fue la implementación de de la web app, implementando funcionalidades core como también diseñando y gestionando sus servicios de una manera más eficiente.  |
| Sprint 2 Velocity | Para este sprint nuestro equipo puende aceptar hasta 30 story points |
| Sum of Story Points | Para este sprint haremos 27 story points |


#### 5.2.2.2. Sprint Aspect Leaders and Collaborators

#### 5.2.2.3. Sprint Backlog 2

#### 5.2.2.4. Development Evidence for Sprint Review

#### 5.2.2.5. Execution Evidence for Sprint Review

<img src="assets/images/collabEvidence/Commits-May-7-2025  & April-26-2025-Part 1.png" width=800>
<img src="assets/images/collabEvidence/Commits-April-26-2025-Part 2.png" width=800>
<img src="assets/images/collabEvidence/Commits-April-26-2025-Part 3.png" width=800>
<img src="assets/images/collabEvidence/Commits-April-26-2025-Part 4.png" width=800>

<img src="assets/images/collabEvidence/Landing-page-Sign In.png" width=800>
<img src="assets/images/collabEvidence/Landing-page-Sign In-student.png" width=800>
<img src="assets/images/collabEvidence/Landing-page-Sign In-tourist.png" width=800>
<img src="assets/images/collabEvidence/Landing-page-Rent.png" width=800>
<img src="assets/images/collabEvidence/Landing-page-Booking.png" width=800>
<img src="assets/images/collabEvidence/Landing-page-Touring.png" width=800>

#### 5.2.2.6. Services Documentation Evidence for Sprint Review 

Dentro de este sprint se utilizo una maquina virtual de Microsoft Azure para desplegar la pagina.

#### 5.2.2.7. Software Deployment Evidence for Sprint Review 

#### 5.2.2.8. Team Collaboration Insights during Sprint  

## Conclusiones y recomendaciones
**1.  Conclusión 1: Proporcionar una solución eficiente ante el problema.**
    

Logramos que las historias de usuarios y el empathy mapping, podemos ver que nuestra propuesta cumple con las necesidades de nuestro grupo de interés. Proporcionando así una solución fácil, barata, eco amigable y accesible.

**2.  Conclusión 2: Diseño creado para una experiencia más grata:**
    

Con la landing page logramos que fuera creado con la idea de proporcionar una interacción simple y fluida para el cliente, para se utilizaron funciones cómo un mapa virtual que ayuda al cliente y diferentes idiomas de los cuales escoger.

**3. Conclusión 3: Coherencia y diseños expertos:**
    

Concluimos que los diversos colores, tipografía y formas de la landing page fueron seleccionados para poseer una identidad visual concreta. Además nos permite poseer una apariencia experta.

**4.  Conclusión 4: Accesibilidad en mente**
    

La página fue creada con la idea de ser utilizable por cualquier persona independientemente de su conocimiento sobre tecnología. Obtuvimos con la plataforma, una manera de instruir al usuario paso a paso para que pueda realizar cualquier acción con facilidad, lo que permite tener un enfoque inclusivo.

**5.  Conclusión 5: Beneficios para ciertos usuarios**
    

Concluimos que la página y el sistema fueron creados con la idea de beneficiar en especial a nuestro segmento objetivo ofreciendo descuentos y ayuda especial, ofreciendo una experiencia de usuario personalizada.

**6.  Conclusión 6: Compromiso con la visión integral del proyecto:**
    

Este proyecto también busca crear un impacto positivo a los ciudadanos y el ambiente de la ciudad en general. Con esto concluimos que conseguimos realizar una planificación estratégica clara y estructurada.

**2.  Recomendaciones**
    

Posterior a la entrega de este trabajo, para el funcionamiento y mejora de la plataforma, recomendamos realizar las siguientes acciones:

-   Incluir una opción para que el cliente pueda dejar una comentario acerca de cualquier problema por el que pudo pasar, mejorando de esta manera la comunicación con el cliente, la confianza y la plataforma a largo plazo.
    
-   Incluir descuentos dentro de la aplicación para poder incrementar la cantidad de usuarios que lo utilizan. Esto nos permite incrementar la posibilidad de que un usuario utilice la aplicación a corto y largo plazo.
    
-   Es recomendable añadir una página donde se pueda ver a mayor detalle cada uno de los tipos de pagos y maneras en las que se pueda alquilar una bicicleta. Una calculadora de precios sería de gran ayuda.
    
-   Ofrecer una suscripción a la página que sirve como un seguro para la bicicleta, permitirá al cliente utilizar el servicio sin preocupaciones de robo o daño.
## Bibliografia
- Estudios Económicos y Estadística, G. (2024). Lima es la ciudad con mayor congestión vehicular en América Latina. https://aap.org.pe/observatorio-aap/ranking-de-congestion-vehicular-enero2024/ranking-de-congestion-vehicular-enero2024.pdf
- BIG Hacks. (2020). Estructura de una página web y tipos de estructuras web. Recuperado de https://bighacks.agency/blog/estructura-de-una-pagina-web
- Hidalgo, D., & Huizenga, C. (2013). Implementation of sustainable urban transport in Latin America. Research in Transportation Economics, 40(1), 66–77. https://doi.org/10.1016/j.retrec.2012.06.034
- Götschi, T., Garrard, J., & Giles-Corti, B. (2016). Cycling as a part of daily life: A review of health perspectives. Transport Reviews, 36(1), 45–71. https://doi.org/10.1080/01441647.2015.1057877

## Anexos
Link a Figma:
- Figma: https://www.figma.com/design/XUOywJac5xiviLZTzQRXVC/Aplicaciones-Web---SafeCycle?node-id=13-501&t=miLetXSzBwb9VPw5-1
- Link a encuesta enviada para How much de 5W2H: https://docs.google.com/forms/d/e/1FAIpQLSeA6pLs-rQHjfQKjtP-qf2gnkVFpHTSa95WKuD-IgsjbufGUw/viewform?usp=dialog
- Link a resultados de encuesta How much de 5W2H: Encuesta sobre movilidad urbana (Responses)
- Link a Github Pages: https://1asi0730-2510-4374-g1-safecycle.github.io/landing_page/

