# Los Luminoso - Report

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="LogoUPC">
</p>

# Universdiad Peruana de Ciencias Aplicadas

# INGENIERÍA DE SISTEMAS DE SOFTWARE
### Ciclo: 5
## CURSO: SI729 Desarrollo de Aplicaciones Open Source | SECCIÓN SW57
 Profesor: Velazquez Nuñez, Angel Augusto
 
# Proyecto de curso
## Informe del TF
#### StartUp: Los Luminosos
#### Producto: MedSystem

### Integrantes:
| Integrantes | Codigo |
|-------------|--------|
| Altamirano Saenz, Jorge Armando  | U202215888 |
| Flores Manrique, Sebastian Enrique | U201611430 |
| Guimaraes Escalante, Carlos Eduardo | U202210364 |
| Gutierrez Zumaeta, Manuel Alonso | U201611430 |
| Montes Figueroa, Juan Eduardo | U202210775 |

#### Ciclo 2024-01
##### Abril, 2024
- - -
# Registro de Versiones del informe
| Version | Fecha | Autor | Descripcion de Modificacion |
| ----------- | ----------- | ----------- | ----------- |
| 0.0 | 28/03/2024 |Grupo 1 |Se crea el documento |
- - -
# Project Report Collaboration Insights
[URL del repositorio](https://github.com/LosLuminosos-SW57/FinalProject.git)

(Imagenes de los commits cada entrega)
- - -
# Contenido

[Student Outcome](#student-outcome)

[Capítulo I: Introducción](#capítulo-i-introducción)

[1.1 Startup Profile](#11-startup-profile)  
[1.1.1. Descripción de la Startup](#111-descripción-de-la-startup) 

[1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)  

[1.2. Solution Profile](#12-solution-profile)  
[1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)  
[1.2.2 Lean UX Process.](#122-lean-ux-process)  
[1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)  
[1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)  
[1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)  
[1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)  

[1.3. Segmentos objetivo.](#13-segmentos-objetivo)  

[Capítulo II: Requirements Elicitation & Analysi](#capítulo-ii-requirements-elicitation--analysis)  

[2.1. Competidores](#21-competidores)  
[2.1.1. Análisis competitivo]()  
[2.1.2. Estrategias y tácticas frente a competidores](#211-análisis-competitivo)  

[2.2. Entrevistas](#22-entrevistas)  
[2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)    
[2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)  

[2.3. Needfinding](#23-needfinding)  
[2.3.1. User Personas](#231-user-personas)  
[2.3.2. User Task Matrix](#232-user-task-matrix)  
[2.3.3. User Journey Mapping](#233-user-journey-mapping)  
[2.3.4. Empathy Mapping](#234-empathy-mapping)  
[2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping) 

[2.4. Ubiquitous Language](#24-ubiquitous-language)  

[Capítulo III: Requirements Specificatio](#capítulo-iii-requirements-specification)  

[3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)  

[3.2. User Stories](#32-user-stories)  

[3.3. Impact Mapping](#33-impact-mapping)  

[3.4. Product Backlog](#34-product-backlog)  

[Capítulo IV: Product Design](#capítulo-iv-product-design)  

[4.1. Style Guidelines](#41-style-guidelines)  
[4.1.1. General Style Guidelines](#411-general-style-guidelines)  
[4.1.2. Web Style Guidelines](#412-web-style-guidelines)  

[4.2. Information Architecture](#42-information-architecture)  
[4.2.1. Organization Systems](#421-organization-systems)  
[4.2.2. Labeling Systems](#422-labeling-systems)  
[4.2.3. SEO Tags and Meta Tag](#423-seo-tags-and-meta-tags)  
[4.2.4. Searching Systems](#424-searching-systems)   
[4.2.5. Navigation Systems](#425-navigation-systems)  

[4.3. Landing Page UI Design](#43-landing-page-ui-design)   
[4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)  
[4.3.2. Landing Page Mock-up](#432-landing-page-mock-up) 

[4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)  
[4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)  
[4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)  
[4.4.2. Web Applications Mock-ups](#442-web-applications-mock-ups)   
[4.4.3. Web Applications User Flow Diagrams](#443-web-applications-user-flow-diagrams)  

[4.5. Web Applications Prototyping](#45-web-applications-prototyping)  

[4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)  
[4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)  
[4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)  
[4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)  

[4.7. Software Object-Oriented Design](#47-software-object-oriented-design)  
[4.7.1. Class Diagrams](#471-class-diagrams)  
[4.7.2. Class Dictionary](#472-class-dictionary)  

[4.8. Database Design](#48-database-design)  
[4.8.1. Database Diagram](#481-database-diagram)  

[Capítulo V: Product Implementation, Validation & Deploymen](#capítulo-v-product-implementation-validation--deployment)  

[5.1. Software Configuration Management](#51-software-configuration-management)  
[5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)  
[5.1.2. Source Code Management](#512-source-code-management)  
[5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)  
[5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)  

[5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)  
[5.2.X. Sprint ](#52x-sprint-n)  
[5.2.X.1. Sprint Planning n](#52x1-sprint-planning-n)  
[5.2.X.2. Sprint Backlog n](#52x2-sprint-backlog-n)  
[5.2.X.3. Development Evidence for Sprint Review](#52x3-development-evidence-for-sprint-review)  
[5.2.X.4. Testing Suite Evidence for Sprint Review](#52x4-testing-suite-evidence-for-sprint-review)  
[5.2.X.5. Execution Evidence for Sprint Review](#52x5-execution-evidence-for-sprint-review)  
[5.2.X.6. Services Documentation Evidence for Sprint Review](#52x6-services-documentation-evidence-for-sprint-review)  
[5.2.X.7. Software Deployment Evidence for Sprint Review](#52x7-software-deployment-evidence-for-sprint-review)  
[5.2.X.8. Team Collaboration Insights during Sprint](#52x8-team-collaboration-insights-during-sprint)  

[5.3. Validation Interviews](#53-validation-interviews)  
[5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)  
[5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)  
[5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)  

[5.4. Video About-the-Product](#54-video-about-the-product)  

[Conclusiones](#conclusiones)  

[Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)  

[Video About-the-Team](#video-about-the-team)  

[Bibliografía](#bibliografía)  

[Anexos](#anexos)  

- - -
# Student Outcome

Criterio: Capacidad de comunicarse efectivamente con un rango de audiencias.
En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 3

| Criterio específico                                                                                                                                                                    	| Acciones realizadas 	| Conclusiones 	|
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|---------------------	|--------------	|
| Comunica oralmente sus ideas y/o resultados con objetividad a públicos de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto de ingeniería.    	|                     	|              	|
| Comunica en forma escrita ideas y/o resultados con objetividad a públicos de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto de ingeniería. 	|                     	|              	|



- - -
# Capitulo 1
## 1.1 StartUp Profile
### 1.1.1 Descripcion de la startup
(Nombre de la startup) es una startup creada por estudiantes de la Facultad de Ingeniería de la carrera de Ingeniería de Software. Esta empresa tiene el propósito de desarrollar una solución web con el uso de tecnologías modernas para la ayuda de los procesos que se tienen presente en una consultoría de traumatología. Con la página (nombre de la página) se logrará satisfacer estas necesidad por parte de los especialistas de traumatología y los clientes.

| **Misión**                                                                                                                                                                                                                                    | **Visión**                                                                                                                                                                                                                                                                  |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| La misión de Los Luminosos es facilitar la atención médica en la especialización de traumatología a través de MedSystem para mejorar los procesos de una consultoría y la experiencia de los especialistas o doctores y de los pacientes. | Nuestra visión es ser reconocidos por nuestra capacidad de mejorar la atención médica por medio de soluciones tecnológicas que mejoren la eficiencia de los distintos servicios que ofrece el área de traumatología, además de mejorar el servicio hacia los pacientes. |

---
### 1.1.1 Perfiles de integrantes del equipo
|   | Miembros del equipo                 | Código de estudiante | Carrera                | Conocimientos/Habilidades                                                                                                                                                                                                                                                                               |
|---|-------------------------------------|----------------------|------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="../members-profile/manuel.jpg" width="50%" alt="Imagen del compañero">  | Gutierrez Zumaeta Manuel Alonso     | u202112353           | Ingeniería de Software | Soy un estudiante de la carrera de ingeniería de software de la UPC, tengo 20 años. Tengo experiencia usando lenguajes de programación como C++, Python y JS. Además puedo ayudar al equipo en todas las tareas que se realicen para lograr un resultado óptimo.                                        |
|  <img src="../members-profile/Carlos.png" width="50%" alt="Imagen del compañero"> | Guimaraes Escalante, Carlos Eduardo | u202210364           | Ingeniería de Software |   Soy estudiante de la carrera de Ingeniería de Software, estoy cursando el tercer ciclo de mi carrera y tengo 17 años. Soy una persona responsable y puntual, por lo que me gusta terminar y presentar los trabajos en los tiempos establecidos. Siempre me ha gustado la innovación y la creación de nuevas ideas. Estoy capacitado en algunos temas de edición de videos, y me considero bueno en programación. Voy a aportar al grupo de manera proactiva e intentaré aportar ideas que ayuden a mejorar el trabajo, siempre intentando mantener un ambiente positivo dentro del área de trabajo. |
| <img src="../members-profile/altamirano.jpg" width="50%" alt="Imagen del compañero">  | Altamirano Saenz, Jorge Armando     | u202215888           | Ingeniería de Software |  Me llamo Jorge Altamirano, tengo 19 años. Tengo conocimientos en programación en los lenguajes de C++, Python, Java y C# básico. Me considero una persona responsable e investigadora y creo que puedo aportar con ideas propias al equipo. |                                                                                                                                                                                                                                                                                                       |
|  <img src="../members-profile/Juan.JPG" width="50%" alt="Imagen del compañero"> | Montes Figueroa, Juan Eduardo       | u202210775           | Ingeniería de Software | Mi nombre es Juan Montes, tengo 19 años, tengo conocimientos en C++, asimismo poseo conocimientos básicos en Java y también en diseño de imágenes tanto en aplicaciones complicadas como Photoshop hasta páginas webs que te dan funciones similares. Puedo aportar en el equipo con ideas, confianza y atención a los detalles. |                                                                                                                                                                                                                                                                                                        |
|  <img src="../members-profile/sebastian.jpeg" width="50%" alt="Imagen del compañero">  | Flores Manrique, Sebastian Enrique  | u201611430           | Ingeniería de Software | Soy estudiante de la carrera de Ingeniería de software. Actualmente cursando el quinto ciclo de la carrera. Me considero una persona responsable y dispuesto a ayudar en lo que haga falta. Tengo conocimientos en lenguaje de programación de C++, Python y un poco de conocimiento en desarrollo web. |

## 1.2 Solution Profile
### 1.2.1. Antecedentes y problemática
Muchos pacientes necesitan atención que requiere una toma de decisiones conjunta entre múltiples actores y/o servicios. La evaluación de interconsultas es tediosa e ineficaz debido a la estructura actual de atención en la mayoría de los consultorios y clínicas. Los pacientes con diabetes de pie que están hospitalizados en los pabellones de medicina son un ejemplo típico en el que la demora en los procedimientos o intervenciones quirúrgicas realizadas por los servicios de traumatología puede resultar en complicaciones graves e incluso en la muerte del paciente.

La Encuesta Nacional de Hogares (ENAHO) de 2022 revela que 7 de cada 10 personas que necesitaron atención médica no la obtuvieron . El 35 % de ellos mencionó demoras como la razón principal, mientras que razones como distancia y falta de seguro solo fueron citadas por el 13 % y el 3 %, respectivamente.

La situación actual enfatiza la importancia de una solución tecnológica que facilite la comunicación entre pacientes y especialistas, optimice el seguimiento de tratamientos, centralice el almacenamiento de historias clínicas y simplifique la gestión de citas. Además, se vuelve necesario incorporar consultas virtuales y recordatorios automáticos de citas para mejorar la accesibilidad y la eficiencia de la atención médica en el campo de la traumatología.

Se aplica la técnica 5W-2H que permite analizar las necesidades de nuestros usuarios al realizar una reflexión de las características principales de la situación general. Presentamos la información obtenida de las respuestas a las preguntas planteadas en la técnica. 

- **What(¿Qué?)**

  El problema radica en la falta de un sistema integral y automatizado en el área de traumatología, lo que resulta en largos tiempos de espera para programar consultas, cirugías y exámenes. Esto afecta la experiencia del paciente y puede obstaculizar su recuperación. 
- **When(¿Cuándo?)**
  
  El problema ocurre cuando los pacientes necesitan atención médica en el área de traumatología y enfrentan dificultades para programar consultas, cirugías y exámenes. Los pacientes utilizan el producto para gestionar sus citas y seguimientos de tratamiento.
- **Where(¿Dónde?)**
  
  Los pacientes pueden encontrarse en sus hogares, trabajos u otros lugares cuando utilizan el sistema para gestionar sus citas y seguimientos de tratamiento. El problema surge principalmente en consultorios médicos y clínicas de traumatología.
- **Who(¿Quién?)**
  
  Los pacientes que necesitan atención médica en traumatología, así como los especialistas médicos y el personal administrativo de consultorios y clínicas, están involucrados en el problema. Los pacientes y los especialistas médicos utilizarán el sistema propuesto.
- **Why(¿Por qué?)**

  La falta de un sistema integral y automatizado en el área de traumatología conduce a largos tiempos de espera y a una gestión ineficiente de las citas y tratamientos. La dispersión de información médica y la comunicación limitada entre médicos y pacientes agravan la situación.
- **How(¿Cómo?)**
  
  Los clientes utilizan el producto en condiciones de necesidad médica, cuando requieren atención en traumatología y deben programar citas, cirugías y exámenes. La situación ha llevado a la necesidad de una solución tecnológica que simplifique la gestión de citas y mejore la comunicación entre pacientes y especialistas.
- **How much(¿Cuánto?)**

  La Encuesta Nacional de Hogares (ENAHO) de 2022 revela que 7 de cada 10 personas que necesitaron atención médica no la obtuvieron, lo que indica que una gran cantidad de personas son afectadas por problemas de acceso y gestión en el área de salud, aunque no todos se refieren específicamente a traumatología. Sin embargo, la problemática específicamente en traumatología también puede afectar a una gran cantidad de pacientes que enfrenta demoras en el proceso de atención.
  
### 1.2.2. Lean UX Process	
###   1.2.2.1. Lean UX Problem Statements	
* Lo que ofrece nuestra aplicación es un sistema que mejora la  comunicación entre los especialistas dentro de una consultoría, como por ejemplo al momento de compartir las historias clínicas de un paciente y los procesos a los que se les somete. Y así poder evitar demoras y confusiones de datos como en algunos casos pasa. ¿Cómo podríamos hacer que esta comunicación sea rápida y eficaz?.
* Nuestra aplicación ofrece también un sistema para la programación de citas por parte de los pacientes , haciendo que estas no tengan que esperar por mucho tiempo y además también que se pueda dar una cita con ciertas especificación del paciente. ¿Cómo brindar un buen sistema de citas para los clientes donde podrán tener citas de acuerdo a sus necesidades?
###   1.2.2.2. Lean UX Assumptions
- **Business outcomes:**

  1. El usuario necesita optimizar la gestión de citas y procesos en el área de traumatología de manera eficiente.
  2. Las necesidades del usuario se resolverán a través de una aplicación web integrada en línea que permite programar citas, cirugías, exámenes y seguimiento de tratamientos.
  3. Los usuarios son pacientes que buscan atención en el área de traumatología y profesionales médicos especializados en el tratamiento.
  4. El usuario desea una interfaz fácil de usar para reservar citas, acceder a los registros médicos y comunicarse con los proveedores de atención médica.
  5. A través de nuestro servicio, los usuarios también pueden obtener consultas virtuales, recordatorios automáticos de citas y análisis de datos para mejorar los procesos.
  6. Ganaré dinero cobrando a los proveedores de atención médica tarifas de suscripción por el uso de la plataforma y posiblemente ofreciendo características premium por un cargo adicional.
  7. Mi competencia principal es el software de programación de citas independientes y los sistemas de gestión hospitalaria actuales.
  8. Con una solución más completa y específicamente diseñada para la atención traumatológica, que incluye características como consultas virtuales y recordatorios automáticos, venceremos a la competencia.
  9. Mi mayor riesgo es la resistencia de los proveedores de atención médica a adoptar nuevas tecnologías o integrarlas en sus sistemas existentes.
  10. Mediante la capacitación y el soporte extensivos al personal de atención médica durante el proceso de incorporación y la demostración de los claros beneficios del uso de la plataforma, reduciremos el riesgo.

- **User Assumptions:**

  - **¿Quién es el usuario?**

    Pacientes que necesitan atención traumatológica y médicos especializados en el área.
    
  - **¿Dónde encaja nuestro producto en su trabajo o vida?**

    El producto servirá como un lugar central para administrar citas traumatológicas, registros médicos y comunicación entre pacientes y proveedores de atención médica.
    
  - **¿Qué problema tiene nuestro producto? ¿Cómo se resuelve?**

    Reduce los tiempos de espera, facilita la programación de citas, centraliza los registros médicos para una toma de decisiones informada y permite consultas virtuales para mayor comodidad.
    
  - **¿Cuándo y cómo es usado nuestro producto?**

    Los usuarios pueden acceder a la plataforma desde una variedad de dispositivos, como computadoras de escritorio y teléfonos inteligentes, para reservar citas, revisar registros médicos y comunicarse con proveedores de atención médica desde casa, el trabajo o en movimiento.
    
  - **¿Qué características son importantes?**

    La programación de citas, el acceso a los registros médicos, las consultas virtuales y los recordatorios automáticos de citas mejoran la experiencia del paciente y el proceso de atención traumatológica.
    
  - **¿Cómo debe verse nuestro producto y comportarse?**

    El producto debe tener una interfaz limpia e intuitiva, ser fácil de navegar e integrarse perfectamente con los sistemas de atención médica actuales para los proveedores de atención médica. Además, debe ser fácil de usar y accesible para pacientes de todos los grupos demográficos.
    
###   1.2.2.3. Lean UX Hypothesis Statements	
* Creemos que los tiempos de espera se reducirán significativamente si los pacientes puede programar citas de manera rápida y eficiente a través de una plataforma en línea
* Creemos que la comunicación entre especialistas mejorará si se implementa un sistema para compartir historias clínicas y procesos médicos de manera rápida y efectiva
* Creemos que la experiencia del paciente mejorará si se ofrecen consultas virtuales y recordatorios automáticos de citas
###   1.2.2.4. Lean UX Canvas
<img src="../solution-profile/LeanUXCanvas.jpg" alt="Lean Ux Canvas">

###   1.3. Segmento Ojetivo
Nuestros segmentos objetivos en este se dividen en tres grupos fundamentales. Como primer segmento contamos con los pacientes que son los que han sufrido algún tipo de accidente y requieren una atención en el área de traumatología. En segundo lugar serían los médicos especialistas en el área de traumatología que requerirán de nuestro sistema para la gestión de sus citas y establecer una buena comunicación entre sus demás colegas de profesión, o laboratorios para una correcta coordinación de algún proceso que se lleve a cabo con el paciente. Por último están las consultorías o laboratorios quienes recibirán la información del paciente, brindada por los doctores, incluyendo procedimientos que requiera el paciente ya sea un tratamiento o algún tipo de examen.




