<!-- Carátula -->

<div align="center">
    <img src="images/logo-upc.png">
</div>

<div align="center">

# Universidad Peruana de Ciencias Aplicadas

## Carrera de Ingeniería de Software

</div>

<div align="center"> 

**Ciclo:** 2026 - 1  
**Curso:** Desarrollo de aplicaciones Open Source<br>
**NRC:** 11896<br>
**Docente:** Efraín Ricardo Bautista Ubillús

## "Informe del trabajo final"
**Startup:** GuandiAnts<br>
**Producto:** GOD's Tracker


## Relacion de integrantes:


| Código      | Nombre                              |
|-------------|-------------------------------------|
| U20221d382  | Poma Muñoz, Ariadna Geraldine       |
| U20241b962  | Navarro Aldoradin, Carolina Celeste |
| U202412903  | Lozano Quispe, Fabricio Jofred      |
| U202414356  | Vite Celis, Rodrigo Matias          |

<div style="font-weight: bold;"> Abril, 2026</div>

</div>

## Registro de Versiones del Informe

| Versión | Fecha    | Autor       | Descripción de Modificación            |
| ------- | -------- | ----------- | -------------------------------------- |
| 0.1     | 07/04/26 | Poma Muñoz, Ariadna Geraldine    | Desarrollo de la Estructura del informe |
| 0.1    | 07/04/26 | Navarro Aldoradin, Carolina Celeste | Desarrollo de la Estructura del informe|
| 0.1    | 07/04/26 | Lozano Quispe, Fabricio Jofred | Desarrollar de la estructura del informe |
| 0.1    | 07/04/26 | Vite Celis, Rodrigo Matias | Desarrollo de la Estructura del informe|



## Project Report Collaboration Insights

| URL de la organización del proyecto | URL del repositorio del reporte   |
| :------------------: | :---------------------------: | 
| https://github.com/upc-pre-202610-1asi0729-11896-guardiant | https://github.com/upc-pre-202610-1asi0729-11896-guardiant/guardiants-report |

| URL del repositorio de la landing page |
| :----------------------------: | 
| https://github.com/upc-pre-202610-1asi0729-11896-guardiant/guardiants-website | 



**URL LANDING PAGE DESPLEGADO**:


Commits del Report:

## CONTENIDO

### Tabla de contenido
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivos](#13-segmentos-objetivos)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.4. Big Picture Event Storming](#24-big-picture-event-storming)
  - [2.5. Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories](#31-user-stories)
  - [3.2. Impact Mapping](#32-impact-mapping)
  - [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
    - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagrams](#481-database-diagrams)
- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint n](#521-sprint-n)
      - [5.2.1.1. Sprint Planning n](#5211-sprint-planning-n)
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog n](#5213-sprint-backlog-n)
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)



# **Student Outcomes**



# Capítulo I: Introducción

## 1.1. Startup Profile

###  1.1.1. Descripción de la Startup
En una ciudad como Lima,  donde la inseguridad ciudadana y el robo de vehículos son problemas críticos que afectan la tranquilidad y el patrimonio de miles de personas, la protección convencional ya no es suficiente. Frente a esta realidad surge GuardiAnts, una startup impulsada por estudiantes de Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas (UPC). Reconocemos que la falta de control en tiempo real y la ausencia de datos precisos generan vulnerabilidad tanto en usuarios particulares como en empresas que dependen de su logística diaria. A través de nuestra plataforma de Telemetría e IoT, conectamos directamente al propietario con su activo en tiempo real. No nos limitamos al rastreo, sino que convertimos cada unidad en un centro de datos inteligente capaz de defenderse solo, optimizar sus rutas y analizar el comportamiento de manejo para maximizar la rentabilidad operativa. En GuardiAnts, trabajamos con la precisión y agilidad de un hormiguero organizado para que tú recuperes el control total. Protegemos tu inversión, potenciamos tu eficiencia.

**Misión:** Nuestra misión es transformar la seguridad vehicular mediante un sistema de monitoreo inteligente y telemetría avanzada, permitiendo que nuestros segmentos objetivos recuperen el control absoluto de sus unidades en tiempo real. Estamos comprometidos con resguardar el patrimonio de nuestros usuarios y potenciar la rentabilidad de sus activos, eliminando la incertidumbre mediante respuestas inmediatas y analíticas personalizadas que convierten a cada vehículo en una entidad protegida y eficiente.

**Visión:** Nuestra visión es consolidarnos como la plataforma líder en seguridad vehicular y gestión inteligente de activos mediante telemetría e IoT elevando el estándar de protección frente a la delincuencia tecnificada. Asimismo, aspiramos a que cada vehículo conectado a GuardiAnts opere como un sistema inteligente y autónomo capaz de anticipar riesgos, detectar interferencias, activar protocolos de resguardo y mantener al propietario o administrador siempre en control desde cualquier lugar. Con nuestro producto buscamos construir un ecosistema confiable, seguro y de alta disponibilidad que no solo incremente la recuperación y prevención de robos, sino que también impulse una movilidad más eficiente y rentable para personas y empresas convirtiendo los datos en decisiones rápidas, claras y accionables en tiempo real.



<div align="center">
  <img src="https://i.postimg.cc/d1jFXhfx/image(1).png'" width="20%">
</div>

<br>

### 1.1.2. Perfiles de integrantes del equipo

- ![fasfa](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSOZgWnkQmogCpq9bl6XEaB6CVhds8mXrWyoQ&s)
<div style="font-weight: bold"> Carolina Celeste Navarro Aldoradin</div> u20241b962 |
Ingeniería de Software
<div style="font-style: italic">Estudiante de 5to ciclo con conocimiento de IIoT, sistemas satelitales, lenguajes de programación como C++, Python, Javascript, Typescript y otros. </div> 

&nbsp;

- [![Foto-presentacion.jpg](https://i.postimg.cc/0QBLw8R2/Foto-presentacion.jpg)](https://postimg.cc/XG9HM6YT)
<div style="font-weight: bold">Ariadna Geraldine Poma Muñoz</div> u20221d382 | Ingeniería de Software <br>
<div style="font-style: italic"> Estudio la carrera de Ingeniería de Software, tengo 20 años y me considero una persona comprometida, curiosa y optimista, con pasión por el aprendizaje continuo en diversos temas relacionados con la tecnología y otros intereses personales. Cuento con una buena capacidad de adaptación al cambio constante, que se complementa con habilidades blandas como trabajo en equipo, resolución creativa de problemas y ser proactiva. Mi objetivo es aplicar lo aprendido para desarrollar soluciones innovadoras que aporten valor.</div> <br>


- <img width="234" height="250" alt="image" src="https://github.com/user-attachments/assets/29f5178a-4567-4093-8f58-be5d351aadd4" />
<div style="font-weight: bold">Fabricio Jofred Lozano Quispe</div> u202412903 | Ingeniería de Software <br>
<div style="font-style: italic"> Estudio la carrera de Ingeniería de Software, tengo 19 años. Me considero una persona responsable, persistente y con una gran disposición por aprender constantemente. Hasta el momento he aprendido C++, Java y he fortalecido mi lógica de programación, lo que ha despertado aún más mi interés por la programación. Me motiva seguir aprendiendo y desarrollando mis habilidades, con el propósito de crear una idea innovadora que me permita crecer como persona y profesional. Siempre busco dar lo mejor de mí en cada tarea que realizo y me gusta enfrentar retos, porque me ayudan a desarrollarme tanto en el ámbito académico como en el personal. En mis tiempos libres practico fútbol, un deporte que me gusta mucho.</div> <br>

- <img width="234" height="250" alt="image" src="https://github.com/user-attachments/assets/127f62d1-99b3-4dfb-8baa-df9c6642972d" />
<div style="font-weight: bold">Rodrigo Matias Vite Celis</div> u202414356 | Ingeniería de Software <br>
<div style="font-style: italic"> Estudio la carrera de Ingeniería de Software, tengo 18 años. Me destaco por mi disciplina y compromiso tanto en el estudio como en el deporte, lo que me ha enseñado a ser constante y trabajar con enfoque. Me gusta aprender de manera práctica y resolver problemas aplicando pensamiento lógico. Tengo conocimientos en programación orientada a objetos, estructuras de datos, algoritmos, y estoy familiarizado con metodologías ágiles como Scrum. Además, me esfuerzo por mejorar continuamente mi desempeño académico y mis habilidades sociales</div> <br>


## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática
### What (¿Qué?)

-¿Cuál es el problema? <br>
La vulnerabilidad de los vehículos frente a una delincuencia cada vez más tecnificada y la falta de control real sobre los activos, lo que resulta en robos exitosos mediante el uso de jammers, pérdida total de unidades y una gestión ineficiente basada en sistemas de rastreo pasivos que no previenen el incidente.

-¿Cuál es la relación con la persona en cuestión? <br>
La relación con los usuarios se basa en devolverles la tranquilidad y el control total de su patrimonio, ofreciendo una plataforma de inteligencia activa que transforma el vehículo de un objeto expuesto a un activo que se defiende solo.

### When (¿Cuándo?)

-¿Cuándo sucede el problema? <br>
El problema ocurre de manera latente durante cada trayecto o momento en que el vehículo queda estacionado, y se critica en el instante de un intento de robo, donde la ausencia de una respuesta automatizada impide la recuperación o el bloqueo efectivo de la unidad.

-¿Cuándo utiliza el cliente el producto? <br>
El usuario utiliza GuardiAnts en dos momentos clave: 1) En el monitoreo preventivo diario, para analizar el comportamiento de manejo y estado de la unidad, y 2) Durante una alerta o evento crítico, para ejecutar protocolos de seguridad y localización exacta en segundos.

### Where (¿Donde?)

-¿Dónde está el cliente cuando utiliza el producto? <br>
Desde cualquier lugar con acceso a su dispositivo móvil o computadora: su hogar, oficina, o incluso mientras se encuentra en tránsito.

-¿A dónde se dirige? <br>
El usuario o sus unidades se dirigen a rutas logísticas, zonas comerciales o áreas residenciales, muchas de ellas con altos índices de inseguridad o baja cobertura de vigilancia tradicional.

-¿Dónde surge el problema? <br>
El problema se origina en la brecha tecnológica que existe entre los métodos de robo modernos y los sistemas GPS convencionales. Si bien el impacto es físico (el robo del auto), el origen es la falta de una plataforma que procese telemetría avanzada y datos en tiempo real para anticipar y neutralizar amenazas antes de que el activo sea inalcanzable.

### Who (¿Quienes?)

-¿Quiénes están involucrados? <br>
Los principales involucrados son los propietarios de vehículos particulares, administradores de flotas comerciales, el equipo de soporte técnico de GuardiAnts y la infraestructura IoT que conecta las unidades con la plataforma de seguridad.

-¿A quiénes les sucede el problema? <br>
El problema afecta principalmente a dueños de vehículos y empresas de transporte que enfrentan la frustración y el impacto financiero de la inseguridad. También afecta a las aseguradoras, que ven incrementados sus costos operativos ante la baja tasa de recuperación de vehículos robados con sistemas tradicionales.

-¿Quién lo utiliza? <br>
La plataforma GuardiAnts será utilizada por personas que valoran la seguridad de su inversión y buscan herramientas de control avanzadas.
Why (¿Por qué?)

-¿Cuál es la causa del problema? <br>
La falta de una herramienta de seguridad activa que no solo "observe", sino que "actúe" mediante el procesamiento inteligente de variables como la desactivación de señales, cambios bruscos en la telemetría y patrones de conducción sospechosos.

### How (¿Cómo?)

-¿En qué condiciones nuestros clientes usan el producto? <br>
Los clientes usan GuardiAnts cuando necesitan garantizar que su vehículo esté protegido 24/7 y buscan minimizar el riesgo de pérdida total. Esto ocurre tanto en la supervisión rutinaria del activo como en situaciones de emergencia donde se requiere intervención inmediata.

-¿Cómo nos conocieron nuestros compradores? <br>
Los usuarios conocen GuardiAnts a través de marketing enfocado en seguridad patrimonial, recomendaciones de gremios de transporte, publicidad en redes sociales dirigida a entusiastas del sector automotriz y colaboraciones con empresas de tecnología y ciberseguridad.

-¿Cómo prefieren nuestros consumidores acceder a nuestro producto? <br>
Los usuarios accederán a GuardiAnts mediante una aplicación móvil de alta disponibilidad y un panel web robusto, complementado con notificaciones push instantáneas que informan sobre cualquier anomalía detectada por los sensores IoT.

-¿Qué llevó a la persona a esa situación? <br>
El aumento sostenido de la inseguridad vehicular y la ineficacia de las alarmas comunes llevan a los usuarios a buscar soluciones de "seguridad inteligente". La necesidad de proteger su inversión y la familia contra la violencia delictiva motiva la adopción de una plataforma que trabaje sin descanso, como un "hormiguero" digital.

### How much (¿Cuánto?)
En Lima, el robo de vehículos ha mostrado cifras alarmantes. Esta situación genera pérdidas económicas directas que superan los cientos de millones de soles anuales, sin contar el costo de las pólizas de seguro que suben debido a la alta siniestralidad. GuardiAnts busca reducir este impacto financiero al aumentar drásticamente las probabilidades de recuperación y prevención, minimizando el riesgo de pérdida total del activo y protegiendo la continuidad de las operaciones logísticas o personales del usuario.



### 1.2.2 Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
Nuestro servicio ofrece una aplicación web de telemetría e IoT que conecta directamente a propietarios de vehículos y administradores de flotas con sus activos en tiempo real, permitiendo a los usuarios monitorear, proteger y optimizar sus unidades mediante datos precisos de ubicación y comportamiento de manejo. Al mismo tiempo, brindamos a empresas y personas naturales herramientas de seguridad activa para ejecutar protocolos de respuesta inmediata, bloquear unidades ante intentos de robo y analizar métricas operativas de manera eficiente, promoviendo la protección del patrimonio y la rentabilidad de los activos. Hemos observado un factor crítico que afecta tanto a usuarios particulares como a empresas logísticas en Lima. Los propietarios enfrentan una vulnerabilidad extrema frente al alto índice de delincuencia y métodos de robo modernos, mientras que los sistemas de rastreo convencionales carecen de una capacidad de respuesta activa para prevenir el incidente. Esta desconexión genera frustración e inseguridad en los usuarios, que sufren la pérdida total de sus unidades, y limita el crecimiento de las empresas, que no logran neutralizar las amenazas ni optimizar sus rutas ante la falta de inteligencia en tiempo real. ¿Cómo podemos mejorar nuestra plataforma de telemetría y seguridad activa para que los propietarios de vehículos en Lima logren neutralizar intentos de robo de manera inmediata y optimizar su gestión operativa, basándonos en la reducción de pérdida total de unidades y el aumento de la eficiencia logística?


#### 1.2.2.2. Lean UX Assumptions
**User Assumptions**
- ¿Quién es mi usuario? <br>
  Nuestros usuarios son personas naturales que buscan proteger su patrimonio vehicular frente a la delincuencia en Lima, y empresas de logística o transporte que necesitan control total y optimización de sus flotas en tiempo real.
- ¿Dónde encaja nuestro producto en su trabajo o vida? <br>
  Para las personas, es una herramienta de tranquilidad diaria que protege su inversión; para las empresas, es el centro de control operativo que maximiza la rentabilidad y seguridad de sus activos.
- ¿Qué problemas tiene nuestro producto? ¿Resolver? <br>
  Resuelve la incapacidad de respuesta ante robos con tecnología de interferencia y la pérdida de control operativo por falta de datos en tiempo real sobre el estado y manejo de la unidad.
- ¿Cuándo y cómo es nuestro producto? ¿Usado? <br>
  Los usuarios lo utilizan diariamente para monitorear la ubicación y el estado de sus unidades. Además, en situaciones críticas, sirve para ejecutar protocolos de seguridad y realizar el bloqueo del vehículo en segundos.
- ¿Qué características son importantes? <br>
  Telemetría en tiempo real, bloqueo de motor remoto, detección de interferencias, reportes de comportamiento de manejo y alertas instantáneas mediante notificaciones push.
- ¿Cómo debe verse nuestro producto y cómo debe comportarse? <br>
Debe tener una interfaz limpia y profesional que facilite la lectura rápida bajo presión. Su comportamiento debe ser inmediato y de alta disponibilidad, garantizando que cada comando de seguridad se ejecute sin errores ni retrasos.
  
#### 1.2.2.3. Lean UX Hypothesis Statements
- **Creemos que** al implementar un sistema de detección de interferencias , los propietarios de vehículos reducirán el riesgo de pérdida total del activo.<br>
  **Sabremos que hemos tenido éxito** <br>
  **Cuando veamos** que el sistema ejecuta protocolos de bloqueo automático antes de perder la comunicación con la plataforma.<br>
- **Creemos que** la integración de notificaciones push de alta prioridad que ignoren el modo silencio garantizará que los usuarios actúen a tiempo ante eventos sospechosos. <br>
  **Sabremos que hemos tenido éxito** <br>
  **Cuando veamos** cuando veamos que el 90% de las alertas críticas son visualizadas por el usuario en menos de un minuto de haber sido emitidas. <br>
- **Creemos que** proporcionar analíticas de telemetría (ejemplo: hábitos de conducción) a las empresas de logística permitirá una reducción en sus costos operativos mensuales.<br>
  **Sabremos que hemos tenido éxito** <br> 
  **Cuando veamos** cuando veamos una disminución del 10% en el consumo de combustible y gastos de mantenimiento en las flotas que utilizan el panel de control.<br>
- **Creemos que** una interfaz de respuesta rápida con un solo toque reducirá los errores operativos del usuario bajo estrés.<br>
  **Sabremos que hemos tenido éxito** <br>
  **Cuando veamos** que los usuarios logran ejecutar el bloqueo de motor exitosamente al primer intento durante los simulacros de emergencia.<br>
  

#### 1.2.2.4. Lean UX Canvas

- [![LeanUxCanvas.png](https://i.postimg.cc/J4TpzPLr/Lean-UX-Canvas.png)](https://postimg.cc/bstx60rW)

## 1.3. Segmentos objetivos
**Segmento #1: Persona natural** <br>
Personas naturales que quieren proteger su vehículo, recibir alertas básicas y conocer la ubicación del vehículo en tiempo real.
- Aspectos demográficos:
   - Sexo: Masculino y femenino.
   - Edades: Entre 25 y 65 años.
   - Ubicación: Residentes de zonas urbanas con altos índices de robo vehicular en Lima Metropolitana.
- Aspectos psicográficos:
   - Motivaciones: Recuperar la sensación de seguridad, proteger su inversión económica, evitar la pérdida total del vehículo y garantizar asistencia inmediata ante emergencias.
   - Intereses: Seguridad inteligente, tecnología IoT, protección patrimonial y herramientas de monitoreo preventivo.
   - Comportamiento: Valoran soluciones que ofrezcan respuesta activa más que solo rastreo. Investigan dispositivos de seguridad, comparan planes de protección y prefieren aplicaciones móviles intuitivas que les permitan actuar rápidamente (bloqueo remoto) ante una alerta.

**Segmento #2: Empresas** <br>
Empresas de todos los sectores, especialmente los de transporte de carga pesada, empresas de logística, así como de transporte público, para un análisis más avanzado. 
- Aspectos demográficos:
  - Tipo de negocio: Micro, pequeñas y medianas empresas de logística, transporte de carga pesada, delivery y transporte de personal.
  - Ubicación: Empresas con almacenes o centros de despacho ubicados en zonas estratégicas de Lima Metropolitana
- Aspectos psicográficos:
  - Motivaciones: Reducir costos operativos (combustible y mantenimiento), prevenir el robo de mercadería, mejorar los tiempos de entrega y garantizar la seguridad de sus conductores.
  - Intereses: Telemetría avanzada, eficiencia operativa, optimización de rutas, innovación tecnológica y sostenibilidad del negocio.
  - Comportamiento: Buscan un software centralizado que les permita controlar todos sus vehículos desde una sola pantalla. Priorizan herramientas que generen reportes automáticos sobre cómo conducen sus choferes y que faciliten una respuesta rápida si un camión se sale de su ruta permitida o si alguien intenta manipular el GPS.

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores.
### 2.1.1. Análisis competitivo
  
**Objetivo del análisis:** Determinar cómo se posiciona nuestra solución de protección de carga mediante IoT frente a las alternativas existentes y definir un modelo de precios competitivo en el mercado de Latinoamérica.

| Característica | **Mi Startup (Propuesta)** | **SITRACK** | **Lojack México** | **Wialon (Gurtam)** | **Cloudtainer** | **IA27** |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Logo** | ![Logo Mi Startup](https://camo.githubusercontent.com/22d98d88fd2d8e4361a21300d16792e0c8d851570f2b14ab7ed47df53b2f604a/68747470733a2f2f692e706f7374696d672e63632f64316a46586866782f696d6167652831292e706e6727) | ![Logo Sitrack](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQUFCQhdFqfZe-uRO_UiDibl1J-vaaYP-9ljg&s) | ![Logo Lojack](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTAhlsJOrh8ZG76KAYcAP0pXcuJcVFqmnjQQQ&s) | ![Logo Wialon](https://play-lh.googleusercontent.com/yAlU8TWv8EoNur8XOB_wcom5FmDBez91BmxWis1OoWd2Rl6rK2EAALtRO0MxR3P8QQ) | ![Logo Cloudtainer](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRYk4kmzaC4-P5osVYbdlOaVtN8KmP6EABg_Q&s) | ![Logo IA27](https://i.ytimg.com/vi/1zcBylt8Jz8/mqdefault.jpg) |
| **Overview** | Empresa emergente enfocada en innovación y competitividad global mediante IoT. | Líder en telemática global con monitoreo satelital y control de combustible. | Especialista en recuperación vehicular con tecnología GPS + Radiofrecuencia. | Plataforma SaaS global masiva para gestión de flotas multimarca. | Startup de seguridad extrema con candados IoT y Blockchain. | Firma de seguridad 4.0 basada en IA predictiva antirrobos. |
| **Ventaja Competitiva** | Alineación con estándares BASC y ciberseguridad de punta. | Tecnología inteligente de sensores y geocercas para reducir pérdidas. | Recuperación garantizada y enlace directo con autoridades. | Alta personalización, escalabilidad y capacidad de integración API. | Trazabilidad inviolable, sellado digital y biometría. | Análisis de datos en tiempo real para generar rutas seguras. |
| **Mercado Objetivo** | Sector logística, carga pesada y organismos gubernamentales. | Grandes flotas (minería, construcción, petróleo) en LatAm. | Flotillas empresariales y particulares en México. | Empresas logísticas de todo tamaño y proveedores de marca blanca. | Exportadores de carga valiosa, aduanas y farmacéuticas. | Transportistas interesados en reducir siniestralidad mediante datos. |
| **Precios & Costos** | Modelo competitivo (Por definir: Suscripción/Pago por uso). | Estimado de $20-$30 USD por vehículo/mes (No público). | Planes desde ~$25 USD mensuales con contratos de 24 meses. | Licencia por unidad a través de revendedores (~$15-$40 USD). | Solución premium bajo cotización (Hardware + Suscripción). | Modelo por proyecto o licencia anual (Precios no públicos). |
| **Canales de Distribución** | Plataforma SaaS, App Móvil y alianzas estratégicas. | Portal web, Dashboard PC y App. Venta vía distribuidores. | Venta directa (Web/Teléfono) y App Lojack Connect. | Acceso vía Web, API pública y red global de socios locales. | Cloud, App para custodios y venta corporativa directa. | Integración directa con centrales de monitoreo de empresas. |
| **Fortalezas (SWOT)** | Agilidad tecnológica y enfoque en ciberseguridad. | Trayectoria internacional y plataforma madura. | Marca reconocida y respuesta rápida ante incidentes. | Software robusto con más de 4 millones de vehículos conectados. | Tecnología única e inviolable para carga crítica. | Enfoque único en analítica predictiva avanzada. |
| **Debilidades (SWOT)** | Etapa temprana de mercado y marca en construcción. | Enfoque muy amplio; poca transparencia en precios. | Presencia limitada principalmente al territorio mexicano. | Puede resultar complejo para usuarios o flotas pequeñas. | Costos elevados y barreras de adopción tecnológica. | Dependencia de la calidad de datos de dispositivos externos. |

## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas
**Primer segmento: Persona natural**

A continuación, se presentan las preguntas dirigidas al segmento de personas naturales, compuesto por individuos que buscan proteger su vehículo, conocer su ubicación en tiempo real y recibir alertas básicas de seguridad mediante una solución tecnológica como GOD’s Tracker.

**Preguntas principales**
1.	¿Te preocupa que puedan robar tu vehículo? ¿Por qué? 
2.	¿Has tenido alguna experiencia con robo o intento de robo? 
3.	¿Qué haces actualmente para proteger tu vehículo? 
4.	¿Te gustaría saber en todo momento dónde está tu vehículo? 
5.	¿Qué tan útil sería para ti recibir alertas en tu celular si algo pasa con tu vehículo? 
6.	¿Qué tipo de alertas te gustaría recibir? (movimiento, robo, ubicación, etc.) 
7.	¿Qué tan fácil te gustaría que sea usar una app para ver tu vehículo? 
8.	¿Confiarías en un sistema que usa GPS para rastrear tu vehículo? ¿Por qué? 
9.	¿Qué es lo más importante para ti en un sistema de seguridad vehicular?
10.	¿Qué te haría sentir más seguro usando este tipo de producto? 
11.	¿Usarías una aplicación para controlar tu vehículo desde el celular? 
12.	¿Recomendarías un sistema así a otras personas?

**Preguntas complementarias**

13.	¿Qué edad tienes?
14.	¿A qué te dedicas?
15.	¿Qué tipo de vehículo tienes?
16.	¿En qué distrito vives o sueles moverte más? 
17.	¿Qué tanto usas aplicaciones en tu celular? 
18.	¿Prefieres usar más el celular o la computadora?

**Segundo segmento: Empresas**

A continuación, se presentan las preguntas dirigidas al segmento empresarial, compuesto por empresas de transporte, logística y otros sectores que requieren monitoreo, control y análisis avanzado de sus flotas vehiculares.

**Preguntas principales**
1.	¿Te preocupa la seguridad de los vehículos o la carga con la que trabajas?
2. ¿Has vivido o visto problemas de robos o pérdidas en el trabajo?
3. ¿Cómo saben actualmente dónde están los vehículos durante el día?
4. ¿Te gustaría poder ver la ubicación de los vehículos en tiempo real?
5. ¿Qué tan útil sería recibir alertas si un vehículo se desvía o se detiene mucho tiempo?
6. ¿Qué información te ayudaría más en tu trabajo sobre los vehículos?
7. ¿Te serviría tener un historial de recorridos o rutas?
8. ¿Qué tan fácil debería ser usar una app o sistema de monitoreo?
9. ¿Qué es lo más importante para ti en un sistema de este tipo?
10. ¿Te ayudaría tener todo el control en una sola plataforma?
11. ¿Qué problemas te gustaría solucionar con una herramienta como esta?
12. ¿Crees que un sistema así mejoraría tu trabajo o el de tu empresa?
    
**Preguntas complementarias**

13. ¿Cuál es tu puesto o función dentro de la empresa?
14. ¿En qué tipo de empresa trabajas? (transporte, logística, etc.)
15. ¿Trabajas directamente con vehículos? ¿Cómo?
16. ¿En qué zonas sueles trabajar o movilizarte?
17. ¿Qué herramientas o apps usas en tu trabajo actualmente?
18. ¿Qué tan seguido usas celular o computadora en tu trabajo?

### 2.2.2. Registro de entrevistas
### Resumen de entrevistas segmento #1
## Segmento 1: Persona natural

<div align="center">

| Nº Entrevista | Datos del entrevistado | Resumen de la entrevista | Evidencia de entrevista |
|--------------|------------------------|--------------------------|--------------------------|
| 1 | **Nombre:** Luis Lopez <br> **Edad:** 25 <br> **Distrito:** San Borja <br> **Link:** colocar link | El entrevistado, trabajador en logística y usuario frecuente de su vehículo, muestra alta preocupación por el robo, reforzada por un intento previo.<br>Considera que las medidas actuales como la alarma y precaución son insuficientes, evidenciando la necesidad de una solución más completa.<br>Valora el monitoreo en tiempo real y las alertas inmediatas (movimiento sospechoso, intento de robo y ubicación), alineándose con la propuesta de GuardiAnts.<br>Prioriza una app simple, rápida y fácil de usar desde el celular, destacando la precisión y confiabilidad del GPS como factores clave.<br>Su perfil digital y disposición a recomendar la solución refuerzan el potencial de adopción del producto. | <p align="center"><img src="https://github.com/user-attachments/assets/3b1bf596-5fa1-444b-b4b2-4f658100e740" width="300"></p> |
| 2 | **Nombre:** Enrique Castillo <br> **Edad:** 22 <br> **Distrito:** Magdalena <br> **Link:** colocar link | Pendiente de completar. | <p align="center"><img src="https://github.com/user-attachments/assets/183f2f5b-dc91-49ad-b63d-acee24af1438" width="300"></p> |
| 3 | **Nombre:** Juana Quispe <br> **Edad:** 47 <br> **Distrito:** El Agustino <br> **Link:** colocar link | La entrevistada, comerciante independiente, evidencia una alta preocupación por la inseguridad vehicular debido al contexto actual de delincuencia en Lima y a experiencias previas de intento de robo y manipulación de su vehículo mientras realizaba sus actividades laborales.<br>Actualmente no cuenta con una medida de seguridad para su auto, pero considera que es insuficiente, ya que busca mayor control y seguimiento constante. Destaca la necesidad de conocer la ubicación de su vehículo en todo momento y recibir alertas inmediatas ante cualquier movimiento sospechoso.<br>Valora especialmente funciones como notificaciones en tiempo real, ubicación precisa y alertas por movimiento, priorizando un sistema que le permita reaccionar rápidamente ante posibles incidentes.<br>Busca una aplicación simple, fácil de usar y accesible desde el celular, que le brinde mayor tranquilidad y control. Además, muestra disposición a adoptar este tipo de tecnología y recomendarla a su entorno si demuestra ser confiable y efectiva. | <p align="center"><img src="https://github.com/user-attachments/assets/1cb0319f-426e-4d72-b3ff-bbfe19d0c88e" width="300"></p> |

</div>

### Resumen de entrevistas segmento #1
## Segmento 2: Empresas

<div align="center">

| Nº Entrevista | Datos del entrevistado | Resumen de la entrevista | Evidencia de entrevista |
|--------------|------------------------|--------------------------|--------------------------|
| 1 | **Nombre:** Jesus Alvites <br> **Edad:** 25 <br> **Distrito:** <br> **Link:** colocar link | El entrevistado, con experiencia como supervisor de tráfico, confirma que la inseguridad en rutas es frecuente, especialmente en zonas como el Callao o durante paradas donde ocurren robos de carga.<br>Destaca que el monitoreo en tiempo real mediante GPS es indispensable, aunque presenta limitaciones como pérdida de conexión y falta de integración de información.<br>Valora alertas de desvíos o detenciones, acceso a historiales y comunicación con conductores.<br>Busca una solución simple, accesible desde el celular y centralizada que mejore el control, la toma de decisiones y reduzca riesgos operativos. | <p align="center"><img src="https://github.com/user-attachments/assets/1730e97a-50ab-4394-8428-e1933c7a8fe1" width="600"></p> |
| 2 | **Nombre:** Juan Velasquez <br> **Edad:** 25 <br> **Distrito:** <br> **Link:** colocar link | Juan revela una necesidad crítica de seguridad y visibilidad operativa, ya que actualmente depende de métodos manuales e ineficientes como llamadas y WhatsApp para gestionar su flota en un entorno de alto riesgo por robos y desvíos. La implementación de un sistema de telemetría se percibe como una inversión estratégica para obtener paz mental mediante el monitoreo en tiempo real y alertas automáticas, buscando no solo proteger el patrimonio y la carga, sino también optimizar costos de combustible y tiempos de entrega a través de una plataforma centralizada y extremadamente sencilla de usar. El interés principal no radica en la tecnología por sí misma, sino en su capacidad de transformar la incertidumbre actual en un control total que garantice la rentabilidad y la profesionalización del servicio frente al cliente. | <p align="center"><img src="https://github.com/user-attachments/assets/d7cb4ad5-a771-4f21-880c-fc4bbc068698" width="600"></p> |
| 3 | **Nombre:** Matias Diaz <br> **Edad:** 25 <br> **Distrito:** San Juan de Lurigancho <br> **Link:** colocar link | Matias Diaz, quien se desempeña como supervisor de seguridad en una empresa de distribución, destaca que su rol se centra en la prevención de riesgos y el cumplimiento de protocolos durante el traslado de vehículos y carga. Señala que la inseguridad en rutas de Lima Metropolitana es constante, especialmente en zonas de alto riesgo, donde ha presenciado robos y pérdidas operativas.<br>Utiliza herramientas como GPS, radios y reportes manuales, pero considera que estas no son suficientes, ya que requieren complementar información de varias fuentes. Por ello, enfatiza la necesidad de un sistema más completo que muestre la ubicación y el nivel de riesgo de las zonas.<br>Valora especialmente funciones como monitoreo en tiempo real, alertas por desvíos, paradas prolongadas, exceso de velocidad y acceso a historiales de rutas para identificar patrones de riesgo.<br>Busca una plataforma centralizada, rápida y confiable, que le permita reaccionar de inmediato ante emergencias, mejorar el control operativo y reducir tanto riesgos de seguridad como pérdidas económicas en la empresa. | <p align="center"><img src="https://github.com/user-attachments/assets/99b6cbe6-25da-44cd-b540-f0eca42d50c4" width="600"></p> |

</div>

### Resumen de entrevistas segmento #2

A partir de las entrevistas, se puede ver que todos los participantes trabajan en entornos donde la inseguridad en rutas es un problema constante, especialmente por robos y desvíos que afectan directamente sus operaciones. Actualmente dependen de herramientas básicas como GPS, llamadas o WhatsApp, lo que hace que el seguimiento de los vehículos sea poco eficiente y muy manual, generando incertidumbre y dificultando la toma de decisiones rápidas. En general, coinciden en que necesitan tener mayor control y visibilidad en tiempo real, valorando mucho funciones como alertas automáticas ante situaciones sospechosas y el acceso a historiales de rutas para entender mejor lo que ocurre. También buscan una solución que sea simple, accesible desde el celular y que centralice toda la información en un solo lugar. Más allá de la tecnología, lo que realmente esperan es poder trabajar con mayor tranquilidad, reducir riesgos y mejorar la eficiencia de sus operaciones.

### 2.2.3. Análisis de entrevistas.

**Segmento Objetivo: Persona natural**

**Segmento Objetivo: Empresas**
A partir de las 3 entrevistas realizadas a profesionales vinculados a la supervisión de flotas y seguridad vehicular, se identificaron patrones comunes tanto en características objetivas como subjetivas.

#### Características objetivas

- El 100% de los entrevistados trabaja directamente con vehículos o gestión de flotas (supervisor de tráfico, operaciones o seguridad).
- El 100% utiliza herramientas básicas como GPS, llamadas telefónicas o WhatsApp para el seguimiento de unidades.
- El 100% se desempeña en contextos urbanos con alta incidencia de robos, especialmente en rutas de Lima Metropolitana.
- El 100% requiere monitoreo en tiempo real para el control de vehículos.

#### Características subjetivas
- El 100% manifiesta alta preocupación por la inseguridad en rutas, mencionando robos, pérdidas de carga o incidentes operativos.
- El 100% considera que las soluciones actuales son insuficientes debido a:
  - Falta de integración de información  
  - Dependencia de procesos manuales  
  - Limitaciones del GPS tradicional  

- El 100% valora funcionalidades clave como:
  - Monitoreo en tiempo real  
  - Alertas automáticas (desvíos, paradas, velocidad)  
  - Historial de rutas  

- El 100% busca una plataforma centralizada que integre toda la información en un solo sistema.

- El 67% enfatiza la necesidad de:
  - Reducir costos operativos  
  - Optimizar tiempos de entrega  
  - Mejorar la rentabilidad  

- El 100% prioriza la facilidad de uso, indicando que el sistema debe ser:
  - Rápido  
  - Accesible desde el celular  
  - Intuitivo  

- El 100% asocia el uso de estas soluciones con mayor control y tranquilidad, destacando que el valor principal no radica en la tecnología en sí, sino en la reducción de la incertidumbre operativa.

## 2.3. Needfinding
### 2.3.1. User Personas
En esta sección vamos a detallar las tareas que realizan los diferentes segmentos de usuarios representados por los User Personas de nuestra aplicación GOD's Tracker

>Segmento 1: Persona Natural <br> <br> <img width="1920" height="1080" alt="SEGMENTO 1" src="https://github.com/user-attachments/assets/a569abe5-f47a-438e-82da-3622653efe6c" />

>Segmento 2: Empresas <br> <br> <img width="1920" height="1080" alt="SEGMENTO 2" src="https://github.com/user-attachments/assets/8e1f5799-c54c-469a-bc42-9b531393523a" />

### 2.3.2. User Task Matrix  

>Segmento 1: Persona Natural

| Tarea                                      | Frecuencia     | Importancia |
|-------------------------------------------|---------------|-------------|
| Ver ubicación del vehículo en tiempo real | Often         | High        |
| Recibir alertas de robo                   | Occasionally  | High        |
| Detectar movimientos sospechosos          | Occasionally  | High        |
| Usar la app de forma fácil y rápida       | Often         | High        |
| Confiar en la precisión del GPS           | Often         | High        |
| Revisar estado general del vehículo       | Sometimes     | Medium      |

>Segmento 2: Empresas

| Tarea                                      | Frecuencia     | Importancia |
|-------------------------------------------|---------------|-------------|
| Monitorear ubicación de la flota          | Often         | High        |
| Recibir alertas de desvíos o paradas      | Occasionally  | High        |
| Centralizar información en una plataforma | Often         | High        |
| Comunicarse con conductores               | Often         | High        |
| Analizar historial de rutas               | Occasionally  | Medium      |
| Reducir costos operativos                 | Sometimes     | High        |

### 2.3.3. User Journey Mapping  

## Segmento 1: Personas Naturales
<img width="1019" height="980" alt="Customer Journey by XO Projects" src="https://github.com/user-attachments/assets/4a33507b-6343-49e2-8b18-9aa3ae2dcfa8" />

## Segmento 2: Empresas
<img width="1040" height="961" alt="Customer Journey by XO Projects (1)" src="https://github.com/user-attachments/assets/b1a01fa0-3338-466c-aeb6-9ab502af8164" />

### 2.3.4. Empathy Mapping    

## Segmento 1
<img width="1024" height="768" alt="Copia de Brainstorming Mapa de Empatia Usuario Simple Blanco Y Negro (1)" src="https://github.com/user-attachments/assets/7c91f64a-7758-4fca-8770-f2e65b57d504" />

## Segmento 2
<img width="1024" height="768" alt="Copia de Brainstorming Mapa de Empatia Usuario Simple Blanco Y Negro" src="https://github.com/user-attachments/assets/1f3f3285-8c41-4b8d-b3d7-517f35bc68e2" />

### 2.3.5. As-Is Scenario Mapping  
> Segmento 1: Personas Naturales
<img width="1431" height="698" alt="Scenario Mapping (1)" src="https://github.com/user-attachments/assets/8de8fb15-8ca0-4da1-816b-56fca0e48258" />


> Segmento 2: Empresas
<img width="1431" height="698" alt="Scenario Mapping (2)" src="https://github.com/user-attachments/assets/f8ff4b92-9fee-4e2c-909f-da15267447f2" />

## 2.4. Ubiquitous Language  

| Término | Definición |
|--------|-----------|
| Asset (Activo) | Vehículo o carga que es monitoreado y protegido dentro del sistema. |
| Active Defense Protocol (Protocolo de Defensa Activa) | Conjunto de acciones automáticas (como bloqueo de motor) ejecutadas ante una amenaza detectada. |
| Interference Detection (Detección de Interferencias) | Identificación de intentos de bloqueo de señal (jammers) que afectan el rastreo del vehículo. |
| Live Tracking (Seguimiento en tiempo real) | Visualización continua de la ubicación y estado del vehículo en la plataforma. |
| Driving Behavior (Comportamiento de Manejo) | Análisis del estilo de conducción basado en datos como aceleración, frenado y velocidad. |
| Geofence (Geocerca) | Área virtual definida en el mapa que permite detectar entradas o salidas del vehículo. |
| Health Check (Verificación de Estado) | Confirmación periódica de que el sistema y los dispositivos se encuentran conectados y operativos. |
| Security Alert (Alerta de Seguridad) | Notificación de alta prioridad ante eventos críticos como robo o manipulación del sistema. |
| Operational Performance (Rendimiento Operativo) | Medición de la eficiencia del uso del vehículo basada en datos de operación y rutas. |


# Capítulo III: Requirements Specifications

## 3.1. User Stories

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con |
|----------------|--------|-------------|--------------------------|-----------------| 
| US01 | Visualizar ubicación del vehículo en tiempo real | Como persona natural, deseo ver la ubicación actual de mi vehículo en el mapa del dashboard para mantener control sobre su seguridad. | **Given** que el vehículo está registrado y conectado <br> **When** accede al inicio o a "Estado en Vivo" <br> **Then** el sistema muestra la ubicación actual del vehículo en el mapa con la etiqueta "Actualizado hace X seg" <br><br> **Given** que el vehículo pierde señal <br> **When** consulta la ubicación <br> **Then** se muestra la última ubicación disponible y el estado de señal GPS | Epic 01, Epic 07 |
| US02 | Consultar estado general del vehículo | Como persona natural, deseo revisar el estado general del vehículo desde la pantalla de inicio para saber si está activo, seguro y conectado. | **Given** que el vehículo está vinculado <br> **When** accede al dashboard de inicio <br> **Then** se muestra la tarjeta con "Vehículo: Activo", ubicación, batería del dispositivo y estado de seguridad <br><br> **Given** cambios recientes en el estado <br> **When** se actualiza el sistema <br> **Then** refleja el cambio más reciente con timestamp | Epic 01, Epic 07 |
| US03 | Revisar historial de rutas | Como persona natural, deseo consultar rutas pasadas filtrando por fecha para revisar los trayectos realizados por mi vehículo. | **Given** que existen rutas registradas <br> **When** accede a "Historial de Rutas" y selecciona una fecha <br> **Then** muestra el mapa con el trayecto, puntos de inicio y fin, hora, distancia parcial y total, duración y total de recorridos <br><br> **Given** rutas con eventos <br> **When** visualiza el historial <br> **Then** muestra fecha, hora, trayecto y distancia total del día | Epic 01 |
| US04 | Configurar geocerca | Como persona natural, deseo definir una geocerca desde la sección de configuración para recibir alertas si mi vehículo sale del perímetro. | **Given** que el usuario define un perímetro en el mapa <br> **When** el vehículo sale del área <br> **Then** genera alerta visible en "Alertas de Seguridad" con tipo y ubicación <br><br> **Given** que la geocerca ya está activa <br> **When** se modifica el área <br> **Then** el sistema guarda los cambios y aplica la nueva geocerca | Epic 02 |
| US05 | Recibir alerta de seguridad | Como persona natural, deseo recibir alertas categorizadas en la sección "Alertas de Seguridad" para reaccionar ante eventos como movimiento sospechoso o GPS manipulado. | **Given** que se detecta actividad sospechosa <br> **When** el sistema la procesa <br> **Then** aparece en la lista de alertas con tipo (movimiento sospechoso, GPS manipulado, velocidad excedida), ubicación y hora <br><br> **Given** que una alerta fue emitida <br> **When** revisa el panel <br> **Then** muestra filtros por "Todas", "No leídas" y "Urgentes" y permite ver detalle | Epic 02 |
| US06 | Activar defensa automática | Como persona natural, deseo que el sistema ejecute acciones automáticas ante amenazas confirmadas como activar el "Modo seguro auto" desde configuración. | **Given** que el modo seguro automático está habilitado en Configuración > Seguridad <br> **When** se detecta una amenaza confirmada <br> **Then** el sistema ejecuta la acción de defensa (bloqueo de motor u otra) <br><br> **Given** que la defensa fue ejecutada <br> **When** revisa el historial de eventos <br> **Then** registra resultado, tipo de acción y hora | Epic 02 |
| US07 | Bloquear vehículo remotamente | Como persona natural, deseo bloquear el motor de mi vehículo desde el botón "Bloquear Vehículo" en el dashboard o desde "Acciones Rápidas" para actuar ante una emergencia. | **Given** que el vehículo está conectado <br> **When** presiona "Bloquear Vehículo" en el inicio o en Estado en Vivo <br> **Then** el sistema envía el comando de bloqueo al dispositivo IoT y confirma la ejecución <br><br> **Given** que el bloqueo fue enviado <br> **When** el dispositivo lo recibe <br> **Then** actualiza el estado del vehículo a bloqueado en el panel | Epic 02 |
| US08 | Reportar robo desde la app | Como persona natural, deseo reportar el robo de mi vehículo desde la acción rápida "Reportar robo" para activar el protocolo de emergencia de forma inmediata. | **Given** que el usuario selecciona "Reportar robo" en Acciones Rápidas <br> **When** confirma la acción <br> **Then** el sistema registra el reporte, activa alertas prioritarias y notifica <br><br> **Given** que el reporte fue generado <br> **When** consulta el panel <br> **Then** muestra el incidente activo con estado y hora | Epic 02 |
| US09 | Compartir ubicación del vehículo | Como persona natural, deseo compartir la ubicación en tiempo real de mi vehículo desde "Acciones Rápidas" para coordinación con terceros o autoridades. | **Given** que el usuario selecciona "Compartir ubicación" <br> **When** confirma <br> **Then** genera un enlace o notificación con la ubicación actual del vehículo <br><br> **Given** que la ubicación fue compartida <br> **When** el destinatario accede <br> **Then** ve la posición actualizada del vehículo | Epic 02 |
| US10 | Visualizar flota completa | Como supervisor, deseo ver todos los vehículos de la flota desde el panel web para tener una visión general del estado de cada unidad. | **Given** que existen múltiples vehículos registrados <br> **When** accede al panel de flota <br> **Then** muestra todas las unidades con estado, ubicación y última actualización <br><br> **Given** que una unidad cambia de estado <br> **When** se actualiza <br> **Then** refleja el cambio en tiempo real en la vista de flota | Epic 03 |
| US11 | Monitorear vehículos en tiempo real | Como supervisor, deseo ver las ubicaciones actuales de todos los vehículos en un mapa para gestionar operaciones de forma eficiente. | **Given** que los vehículos están conectados <br> **When** accede al mapa de monitoreo <br> **Then** muestra las ubicaciones actuales de todos los vehículos <br><br> **Given** que un vehículo pierde conexión <br> **When** el supervisor revisa <br> **Then** muestra la última ubicación conocida con indicador de sin señal | Epic 03, Epic 07 |
| US12 | Detectar desvíos de ruta | Como supervisor, deseo recibir alertas cuando un vehículo se desvíe de la ruta asignada para tomar acción inmediata. | **Given** que una ruta fue definida para el vehículo <br> **When** el vehículo se desvía del trayecto <br> **Then** genera alerta de desvío con ubicación y hora <br><br> **Given** que el vehículo continúa fuera de ruta <br> **When** el supervisor monitorea <br> **Then** registra el incidente como evento activo | Epic 03 |
| US13 | Recibir alertas de paradas prolongadas | Como supervisor, deseo detectar paradas largas no programadas para identificar incidentes operativos o de seguridad. | **Given** que un vehículo permanece detenido más tiempo del umbral configurado <br> **When** el sistema lo detecta <br> **Then** genera alerta de parada prolongada con ubicación y duración <br><br> **Given** que el vehículo retoma el movimiento <br> **When** ocurre <br> **Then** actualiza el estado y cierra la alerta de parada | Epic 03 |
| US14 | Analizar comportamiento de manejo | Como supervisor, deseo analizar el comportamiento de conducción de cada vehículo para identificar patrones riesgosos y generar reportes de hábitos. | **Given** que existen datos de telemetría disponibles <br> **When** accede al módulo de analítica <br> **Then** muestra métricas de velocidad, frenadas, aceleración y score de conducción <br><br> **Given** que se detectan patrones riesgosos <br> **When** el sistema los procesa <br> **Then** registra los eventos y los incluye en el reporte de hábitos | Epic 03, Epic 09 |
| US15 | Consultar reportes operativos | Como supervisor, deseo ver reportes históricos de operaciones para tomar decisiones basadas en datos de la flota. | **Given** que existen datos históricos registrados <br> **When** solicita un reporte con rango de fechas <br> **Then** genera reporte con rutas, alertas, distancias y comportamiento de conductores <br><br> **Given** que el reporte está listo <br> **When** consulta <br> **Then** muestra los datos estructurados exportables | Epic 03, Epic 09 |
| US16 | Gestionar vehículos de la flota | Como supervisor, deseo agregar, editar o desactivar vehículos dentro de la plataforma para mantener actualizado el inventario de la flota. | **Given** que el supervisor ingresa los datos del vehículo (placa, modelo, flota asignada) <br> **When** guarda el registro <br> **Then** el vehículo aparece disponible en el panel de flota <br><br> **Given** que desea desactivar una unidad <br> **When** cambia su estado <br> **Then** la unidad deja de aparecer en el monitoreo activo | Epic 03 |
| US17 | Asignar dispositivo IoT a vehículo | Como supervisor, deseo asignar un dispositivo IoT a un vehículo de la flota para activar el monitoreo de telemetría. | **Given** que el dispositivo IoT tiene un número serial registrado <br> **When** el supervisor lo asigna a un vehículo <br> **Then** el sistema vincula el dispositivo y comienza a recibir telemetría <br><br> **Given** que el dispositivo ya está asignado a otro vehículo <br> **When** intenta reasignarlo <br> **Then** muestra advertencia y solicita confirmación | Epic 03, Epic 08 |
| US18 | Configurar reglas de alerta para flota | Como supervisor, deseo definir reglas de alerta personalizadas por tipo (geocerca, velocidad, interferencia GPS) para adaptar la detección a las necesidades operativas. | **Given** que el supervisor accede al módulo de reglas de alerta <br> **When** define el tipo de regla, umbral y vehículos afectados <br> **Then** el sistema guarda la regla y la aplica en tiempo real <br><br> **Given** que una regla ya existe <br> **When** se modifica o deshabilita <br> **Then** los cambios se aplican sin afectar otras reglas activas | Epic 03 |
| US19 | Bloquear motor de vehículo de flota remotamente | Como supervisor, deseo enviar un comando de bloqueo de motor a cualquier unidad de la flota desde el panel web ante una emergencia confirmada. | **Given** que el supervisor selecciona un vehículo y ejecuta "Bloquear Motor" <br> **When** el comando es enviado <br> **Then** el Telemetry Gateway entrega la orden al dispositivo IoT y confirma la ejecución <br><br> **Given** que el comando fue ejecutado <br> **When** revisa el registro <br> **Then** aparece el comando con estado, resultado y hora | Epic 03 |
| US20 | Navegación por la landing page | Como visitante, deseo navegar por las secciones de la landing page (Home, About Us, How does it work, FAQs, Contact) para conocer el producto antes de registrarme. | **Given** que el visitante accede a la landing page <br> **When** navega por el menú de navegación <br> **Then** cada sección carga correctamente mostrando su contenido sin recargar la página <br><br> **Given** que el visitante cambia de sección <br> **When** hace scroll o usa el menú <br> **Then** mantiene continuidad visual y navegación fluida | Epic 04 |
| US21 | Acceder a la aplicación desde la landing page | Como visitante, deseo ingresar a la aplicación desde los botones "Login" o "Get Started" de la landing page para comenzar a usar el servicio. | **Given** que el visitante está en la landing page <br> **When** selecciona "Login" o "Get Started" <br> **Then** es redirigido a la pantalla de acceso o registro de la aplicación <br><br> **Given** que el visitante completa el acceso <br> **When** autentica correctamente <br> **Then** es llevado al dashboard principal | Epic 04 |
| US22 | Registrarse en la plataforma | Como visitante, deseo registrarme como nuevo usuario seleccionando mi tipo de perfil (Persona Natural, Empresa, Gobierno) para acceder a las funcionalidades correspondientes. | **Given** que el visitante completa el formulario con datos válidos y selecciona tipo de usuario <br> **When** envía el registro <br> **Then** el sistema crea la cuenta y redirige al dashboard correspondiente <br><br> **Given** que los datos son inválidos o el correo ya existe <br> **When** procesa el formulario <br> **Then** muestra error de validación específico por campo | Epic 04, Epic 10 |
| US23 | Contactar al equipo desde la landing page | Como visitante, deseo enviar un mensaje al equipo de soporte desde el formulario de contacto de la landing page para resolver dudas antes de suscribirme. | **Given** que el visitante completa el formulario (nombre, teléfono, email, tipo de usuario, mensaje) <br> **When** presiona "Send Message" <br> **Then** el sistema registra la solicitud y muestra confirmación de envío <br><br> **Given** que hay datos faltantes o formato inválido <br> **When** envía <br> **Then** muestra error de validación por campo | Epic 04 |
| US24 | Ver sección "How does it work" en landing page | Como visitante, deseo ver la explicación de cómo funciona GOD's Tracker para cada segmento (Persona Natural, Empresas, Entidades Gubernamentales) para entender el valor del producto. | **Given** que el visitante accede a la sección "How does it work" <br> **When** la página carga <br> **Then** muestra los tres segmentos con descripción de beneficios diferenciados <br><br> **Given** que navega entre segmentos <br> **When** interactúa <br> **Then** el contenido relevante se muestra sin recargar la página | Epic 04 |
| US25 | Ver sección de preguntas frecuentes (FAQs) | Como visitante, deseo acceder a la sección de preguntas frecuentes para resolver dudas comunes sobre GOD's Tracker antes de registrarme. | **Given** que el visitante accede a la sección FAQs <br> **When** selecciona una pregunta del acordeón <br> **Then** se despliega la respuesta correspondiente <br><br> **Given** que el visitante ya visualizó una respuesta <br> **When** selecciona otra pregunta <br> **Then** colapsa la anterior y expande la nueva | Epic 04 |
| US26 | Ver resumen de alertas del día en dashboard | Como persona natural, deseo ver en el dashboard el contador de alertas del día, recorridos realizados, señal GPS y nivel de batería del dispositivo para tener un resumen rápido del estado. | **Given** que el usuario accede al inicio <br> **When** la pantalla carga <br> **Then** muestra las 4 tarjetas de resumen: "Alertas hoy", "Recorridos", "Señal GPS" y "Batería" con valores actuales <br><br> **Given** que los datos cambian durante el día <br> **When** se actualizan <br> **Then** los contadores reflejan los valores más recientes automáticamente | Epic 01, Epic 07, Epic 09 |
| US27 | Filtrar alertas de seguridad por categoría y período | Como persona natural, deseo filtrar las alertas en la sección "Alertas de Seguridad" por tipo (Todas, No leídas, Urgentes) y período (Última hora, Hoy, 7 días, 30 días) para revisar solo las relevantes. | **Given** que existen alertas registradas <br> **When** selecciona un filtro de tipo o período <br> **Then** la lista se actualiza mostrando solo las alertas que coinciden con los criterios <br><br> **Given** que no hay alertas en el filtro seleccionado <br> **When** aplica el filtro <br> **Then** muestra mensaje de "Sin alertas en este período" | Epic 02 |
| US28 | Ver detalle de alerta de seguridad | Como persona natural, deseo ver el detalle de una alerta de seguridad (tipo, ubicación, descripción, hora) para decidir si bloquear el vehículo o ignorarla. | **Given** que existe una alerta en la lista <br> **When** presiona "Ver Detalle" <br> **Then** muestra tipo de alerta, ubicación exacta, descripción del evento y hora de ocurrencia <br><br> **Given** que la alerta tiene acción disponible <br> **When** visualiza el detalle <br> **Then** ofrece botón de "Bloquear Vehículo" directamente desde el detalle | Epic 02 |
| US29 | Gestionar configuración de notificaciones | Como persona natural, deseo activar o desactivar notificaciones (alertas de seguridad, ubicación en tiempo real, recordatorios de mantenimiento) desde la sección de Configuración para personalizar mis avisos. | **Given** que el usuario accede a Configuración > Notificaciones <br> **When** activa o desactiva un toggle <br> **Then** el sistema guarda la preferencia y aplica el cambio inmediatamente <br><br> **Given** que la notificación está desactivada <br> **When** ocurre el evento correspondiente <br> **Then** el sistema no genera push para ese tipo | Epic 06 |
| US30 | Configurar opciones de seguridad del dispositivo | Como persona natural, deseo activar o desactivar opciones de seguridad (movimiento sospechoso, apaga motor, modo seguro auto) desde Configuración > Seguridad para definir cómo reacciona el sistema ante amenazas. | **Given** que el usuario accede a Configuración > Seguridad <br> **When** activa un toggle de seguridad (ej. "Modo seguro auto") <br> **Then** el sistema guarda la regla y la aplica en el monitoreo <br><br> **Given** que la opción "Apaga Motor" está activa <br> **When** se confirma una amenaza <br> **Then** el sistema envía el comando de bloqueo al dispositivo IoT automáticamente | Epic 02, Epic 06 |
| US31 | Editar perfil y cambiar contraseña | Como persona natural, deseo editar mi perfil (nombre, email) y cambiar mi contraseña desde la sección Configuración > Cuenta para mantener mis datos actualizados. | **Given** que el usuario accede a Configuración > Cuenta <br> **When** presiona "Editar perfil" <br> **Then** puede modificar nombre y email y guardar los cambios <br><br> **Given** que presiona "Cambiar contraseña" <br> **When** ingresa la contraseña actual y la nueva <br> **Then** el sistema actualiza la contraseña y solicita reautenticación | Epic 06, Epic 10 |
| US32 | Cambiar idioma y tema de la aplicación | Como persona natural, deseo cambiar el idioma (ES/EN) y el tema (Claro/Oscuro) desde Configuración > Otros para adaptar la app a mis preferencias. | **Given** que el usuario accede a Configuración > Otros <br> **When** cambia el idioma o el tema <br> **Then** la aplicación aplica el cambio de forma inmediata en toda la interfaz <br><br> **Given** que reinicia la aplicación <br> **When** vuelve a ingresar <br> **Then** mantiene las preferencias guardadas | Epic 06 |
| US33 | Ver información del dispositivo IoT vinculado | Como persona natural, deseo ver la información del dispositivo IoT vinculado a mi vehículo (estado, modelo, IMEI) desde Configuración > Dispositivo para verificar que está operativo. | **Given** que el dispositivo está asignado al vehículo <br> **When** accede a Configuración > Dispositivo <br> **Then** muestra estado (Activo/Inactivo), modelo y IMEI del dispositivo <br><br> **Given** que el dispositivo está desconectado <br> **When** consulta <br> **Then** muestra estado "Inactivo" con última fecha de conexión | Epic 06, Epic 08 |
| US34 | Reiniciar dispositivo IoT remotamente | Como persona natural, deseo reiniciar el dispositivo IoT vinculado a mi vehículo desde Configuración > Dispositivo para resolver problemas de conectividad sin intervención presencial. | **Given** que el dispositivo está vinculado y activo <br> **When** presiona "Reiniciar Dispositivo" y confirma <br> **Then** el sistema envía el comando de reinicio al dispositivo IoT <br><br> **Given** que el reinicio se completa <br> **When** el dispositivo se reconecta <br> **Then** actualiza su estado a "Activo" en la configuración | Epic 02, Epic 08 |
| US35 | Buscar vehículo por nombre o placa | Como persona natural o supervisor, deseo buscar un vehículo usando la barra de búsqueda en la parte superior de la app para localizarlo rápidamente entre múltiples unidades. | **Given** que el usuario escribe en la barra "Buscar Vehículo" <br> **When** ingresa nombre o placa <br> **Then** el sistema filtra y muestra los vehículos que coinciden con el criterio <br><br> **Given** que no existe coincidencia <br> **When** realiza la búsqueda <br> **Then** muestra mensaje de "Ningún vehículo encontrado" | Epic 01, Epic 07 |
| US36 | Ver plan y estado de suscripción | Como persona natural, deseo ver mi plan actual (Básico, Pro, etc.) y el estado de mi dispositivo (Conectado/Desconectado) desde el panel lateral para saber qué funcionalidades tengo disponibles. | **Given** que el usuario accede a la app <br> **When** visualiza el panel lateral inferior <br> **Then** muestra nombre de usuario, plan activo y estado del dispositivo <br><br> **Given** que el plan ha expirado o cambiado <br> **When** consulta <br> **Then** muestra el plan actualizado con opción de mejora | Epic 04, Epic 10 |
| US37 | Cerrar sesión de la aplicación | Como persona natural o supervisor, deseo cerrar sesión desde el menú lateral de la app o desde Configuración > Cuenta para proteger el acceso en dispositivos compartidos. | **Given** que el usuario presiona "Cerrar Sesión" en el menú lateral o en configuración <br> **When** confirma la acción <br> **Then** el sistema invalida la sesión y redirige a la pantalla de login <br><br> **Given** que la sesión expiró por inactividad <br> **When** intenta usar la app <br> **Then** redirige automáticamente al login con mensaje de sesión expirada | Epic 06, Epic 07, Epic 10 |
| TS38 | Registrar evento de telemetría mediante API | Como developer, deseo registrar eventos de telemetría vía API para almacenar datos GPS/IoT del dispositivo en el Telemetry Store. | **Given** que el payload enviado es válido <br> **When** se realiza POST a /telemetry <br> **Then** el sistema registra el evento en el Telemetry Store <br><br> **Given** que el payload es inválido <br> **When** se procesa la solicitud <br> **Then** devuelve error de validación con detalle | Epic 05, Epic 08 |
| TS39 | Obtener datos de ubicación mediante API | Como developer, deseo consultar la ubicación de un vehículo vía API para integraciones y visualizaciones externas. | **Given** que el vehículo existe y está registrado <br> **When** se realiza GET /vehicles/{id}/location <br> **Then** devuelve lat, lng, velocidad, timestamp y calidad de señal <br><br> **Given** que el vehículo no existe <br> **When** se consulta <br> **Then** devuelve error controlado 404 | Epic 05, Epic 08 |
| TS40 | Procesar envío de alertas mediante API | Como developer, deseo procesar y disparar alertas vía API para que el sistema de notificaciones pueda entregarlas en tiempo real. | **Given** que ocurre un evento crítico (interferencia GPS, velocidad excedida, desvío) <br> **When** se realiza POST /alerts <br> **Then** el sistema procesa la alerta y la encola para notificación push <br><br> **Given** que la solicitud es inválida <br> **When** se procesa <br> **Then** devuelve error controlado con detalle | Epic 05 |
| TS41 | Autenticación de usuarios mediante API | Como developer, deseo implementar autenticación JWT para controlar el acceso a los endpoints protegidos de la plataforma. | **Given** que el usuario envía credenciales válidas <br> **When** realiza POST /auth/login <br> **Then** el sistema devuelve token JWT con rol y permisos <br><br> **Given** que las credenciales son incorrectas <br> **When** se procesa la solicitud <br> **Then** rechaza el acceso con error 401 | Epic 05, Epic 10 |
| TS42 | Manejo de errores en el sistema | Como developer, deseo que el sistema gestione errores internos de forma controlada para garantizar disponibilidad y trazabilidad. | **Given** que ocurre un error interno en el backend <br> **When** se produce la falla <br> **Then** el sistema registra el error con trazabilidad en los logs <br><br> **Given** que el error afecta la respuesta al cliente <br> **When** devuelve la respuesta <br> **Then** incluye mensaje de error controlado sin exponer datos sensibles | Epic 05, Epic 10 |
| TS43 | Cambiar idioma de la landing page | Como developer, deseo implementar el cambio de idioma (ES/EN) en la landing page para servir a usuarios en diferentes idiomas. | **Given** que la landing soporta múltiples idiomas <br> **When** el visitante cambia el idioma desde el selector ES/EN <br> **Then** toda la landing carga en el idioma seleccionado <br><br> **Given** que el idioma solicitado no está disponible <br> **When** se solicita <br> **Then** mantiene el idioma por defecto (ES) | Epic 04 |
| TS44 | Gestionar asignación de dispositivos IoT mediante API | Como developer, deseo implementar los endpoints de asignación y desasignación de dispositivos IoT a vehículos para gestionar el ciclo de vida de los trackers. | **Given** que se envía un serial de dispositivo válido y un vehicle_id existente <br> **When** se realiza POST /devices/assign <br> **Then** el sistema crea el registro en device_assignments con fecha de asignación <br><br> **Given** que se desasigna el dispositivo <br> **When** se realiza DELETE /devices/assign/{id} <br> **Then** el sistema registra la fecha de unassigned_at y libera el dispositivo | Epic 05, Epic 08 |
| TS45 | Consultar reportes de conducción mediante API | Como developer, deseo exponer un endpoint para consultar driving_reports por vehículo y período para que el frontend pueda renderizar los análisis de comportamiento. | **Given** que el vehículo tiene reportes de conducción generados <br> **When** se realiza GET /vehicles/{id}/driving-reports con rango de fechas <br> **Then** devuelve lista de reportes con period_start, period_end, driving_score, summary y metrics_json <br><br> **Given** que no existen reportes en el período <br> **When** se consulta <br> **Then** devuelve lista vacía con código 200 | Epic 05, Epic 08, Epic 09 |

## Relación de Epics y User Stories

## Relación de Epics y User Stories

### Epic 01: Monitoreo y control del vehículo personal

| Story ID | Título |
|----------|--------|
| US01 | Visualizar ubicación del vehículo en tiempo real |
| US02 | Consultar estado general del vehículo |
| US03 | Revisar historial de rutas |
| US26 | Ver resumen de alertas del día en dashboard |
| US35 | Buscar vehículo por nombre o placa |

---

### Epic 02: Seguridad activa y alertas

| Story ID | Título |
|----------|--------|
| US04 | Configurar geocerca |
| US05 | Recibir alerta de seguridad |
| US06 | Activar defensa automática |
| US07 | Bloquear vehículo remotamente |
| US08 | Reportar robo desde la app |
| US09 | Compartir ubicación del vehículo |
| US27 | Filtrar alertas de seguridad por categoría y período |
| US28 | Ver detalle de alerta de seguridad |
| US30 | Configurar opciones de seguridad del dispositivo |
| US34 | Reiniciar dispositivo IoT remotamente |

---

### Epic 03: Gestión de flotas empresariales

| Story ID | Título |
|----------|--------|
| US10 | Visualizar flota completa |
| US11 | Monitorear vehículos en tiempo real |
| US12 | Detectar desvíos de ruta |
| US13 | Recibir alertas de paradas prolongadas |
| US14 | Analizar comportamiento de manejo |
| US15 | Consultar reportes operativos |
| US16 | Gestionar vehículos de la flota |
| US17 | Asignar dispositivo IoT a vehículo |
| US18 | Configurar reglas de alerta para flota |
| US19 | Bloquear motor de vehículo de flota remotamente |

---

### Epic 04: Adquisición y acceso de usuarios (Landing Page)

| Story ID | Título |
|----------|--------|
| US20 | Navegación por la landing page |
| US21 | Acceder a la aplicación desde la landing page |
| US22 | Registrarse en la plataforma |
| US23 | Contactar al equipo desde la landing page |
| US24 | Ver sección "How does it work" en landing page |
| US25 | Ver sección de preguntas frecuentes (FAQs) |
| US36 | Ver plan y estado de suscripción |
| TS43 | Cambiar idioma de la landing page |

---

### Epic 05: Integraciones técnicas y API RESTful

| Story ID | Título |
|----------|--------|
| TS38 | Registrar evento de telemetría mediante API |
| TS39 | Obtener datos de ubicación mediante API |
| TS40 | Procesar envío de alertas mediante API |
| TS41 | Autenticación de usuarios mediante API |
| TS42 | Manejo de errores en el sistema |
| TS44 | Gestionar asignación de dispositivos IoT mediante API |
| TS45 | Consultar reportes de conducción mediante API |

---

### Epic 06: Configuración y personalización de cuenta

| Story ID | Título |
|----------|--------|
| US29 | Gestionar configuración de notificaciones |
| US31 | Editar perfil y cambiar contraseña |
| US32 | Cambiar idioma y tema de la aplicación |
| US33 | Ver información del dispositivo IoT vinculado |
| US37 | Cerrar sesión de la aplicación |

---

### Epic 07: Experiencia de usuario y navegación de la app

| Story ID | Título |
|----------|--------|
| US01 | Visualizar ubicación del vehículo en tiempo real |
| US02 | Consultar estado general del vehículo |
| US11 | Monitorear vehículos en tiempo real |
| US26 | Ver resumen de alertas del día en dashboard |
| US35 | Buscar vehículo por nombre o placa |
| US37 | Cerrar sesión de la aplicación |

---

### Epic 08: Dispositivos IoT y telemetría

| Story ID | Título |
|----------|--------|
| US17 | Asignar dispositivo IoT a vehículo |
| US33 | Ver información del dispositivo IoT vinculado |
| US34 | Reiniciar dispositivo IoT remotamente |
| TS38 | Registrar evento de telemetría mediante API |
| TS39 | Obtener datos de ubicación mediante API |
| TS44 | Gestionar asignación de dispositivos IoT mediante API |
| TS45 | Consultar reportes de conducción mediante API |

---

### Epic 09: Analítica y reportes operativos

| Story ID | Título |
|----------|--------|
| US14 | Analizar comportamiento de manejo |
| US15 | Consultar reportes operativos |
| US26 | Ver resumen de alertas del día en dashboard |
| TS45 | Consultar reportes de conducción mediante API |

---

### Epic 10: Seguridad de acceso e identidad

| Story ID | Título |
|----------|--------|
| US22 | Registrarse en la plataforma |
| US31 | Editar perfil y cambiar contraseña |
| US36 | Ver plan y estado de suscripción |
| US37 | Cerrar sesión de la aplicación |
| TS41 | Autenticación de usuarios mediante API |
| TS42 | Manejo de errores en el sistema |

## 3.2. Impact Mapping
El Impact Mapping es una metodología visual y ágil que permite a las organizaciones enfocar el desarrollo de productos y servicios en función de sus metas estratégicas. Esta técnica facilita la identificación de una relación directa entre los objetivos del negocio, las acciones esperadas de los usuarios clave y las soluciones o funcionalidades que deben implementarse para lograr dichos objetivos.

Impact Map - Segmento 1:
<img width="1744" height="919" alt="image" src="https://github.com/user-attachments/assets/75074afa-1108-42a7-8c6b-407b54725963" />

<img width="1913" height="931" alt="image" src="https://github.com/user-attachments/assets/b6047f02-5516-468d-962a-c4472cc678b7" />

Impact Map - Segmento 2:
<img width="1499" height="931" alt="image" src="https://github.com/user-attachments/assets/f87c9994-dc23-4afc-be77-7566141df9ae" />

<img width="1881" height="662" alt="image" src="https://github.com/user-attachments/assets/99299826-e3e2-46f6-9ca4-eb213985b234" />

<img width="1859" height="923" alt="image" src="https://github.com/user-attachments/assets/09b4f017-823e-4926-a390-5c8100d6d7ba" />

<img width="1892" height="658" alt="image" src="https://github.com/user-attachments/assets/0ada81af-cdaa-45ea-a1ed-c8039b30192e" />


## 3.3 Product Backlog

| #Orden | User Story Id | Título | Descripción | Story Points |
|--------|---------------|--------|------------|--------------|
| 1 | US15 | Navegación por la landing page | Como usuario, quiero navegar por la landing page para conocer el producto. | 2 |
| 2 | US16 | Acceso a la aplicación | Como usuario, quiero acceder a la aplicación desde la web para comenzar a usar el sistema. | 2 |
| 3 | US17 | Registro en la plataforma | Como usuario, quiero registrarme para acceder a las funcionalidades del sistema. | 3 |
| 4 | US01 | Visualizar ubicación en tiempo real | Como usuario, quiero ver la ubicación de mi vehículo en tiempo real para mantener control constante. | 5 |
| 5 | US02 | Consultar estado del vehículo | Como usuario, quiero consultar el estado general de mi vehículo para entender su situación. | 3 |
| 6 | US03 | Revisar historial de rutas | Como usuario, quiero revisar el historial de rutas para analizar recorridos. | 3 |
| 7 | US08 | Visualizar flota completa | Como supervisor, quiero visualizar todos los vehículos en un solo panel para tener control total. | 5 |
| 8 | US09 | Monitorear flota en tiempo real | Como supervisor, quiero monitorear vehículos en tiempo real para supervisar la operación. | 8 |
| 9 | US10 | Detectar desvíos de ruta | Como supervisor, quiero detectar desvíos de ruta para actuar ante incidentes. | 5 |
| 10 | US11 | Alertas de paradas prolongadas | Como supervisor, quiero recibir alertas de paradas prolongadas para identificar riesgos. | 5 |
| 11 | US12 | Analizar comportamiento de manejo | Como supervisor, quiero analizar el comportamiento de manejo para mejorar eficiencia. | 5 |
| 12 | US13 | Visualizar reportes operativos | Como supervisor, quiero visualizar reportes para mejorar la toma de decisiones. | 5 |
| 13 | US04 | Configurar geocercas | Como usuario, quiero configurar geocercas para proteger mi vehículo en zonas específicas. | 5 |
| 14 | US05 | Recibir alertas de seguridad | Como usuario, quiero recibir alertas ante eventos sospechosos para actuar rápidamente. | 5 |
| 15 | US06 | Activar defensa automática | Como usuario, quiero que el sistema active defensa automática para proteger mi vehículo. | 8 |
| 16 | TS21 | Autenticación de usuarios | Como developer, quiero autenticar usuarios mediante API para permitir el acceso seguro al sistema. | 5 |
| 17 | TS14 | Obtener ubicación vía API | Como developer, quiero obtener datos de ubicación mediante API para mostrar información en tiempo real. | 5 |
| 18 | TS07 | Registrar telemetría | Como developer, quiero registrar datos de telemetría para monitorear el vehículo. | 5 |
| 19 | TS20 | Procesar envío de alertas | Como developer, quiero procesar alertas mediante API para notificar eventos críticos. | 5 |
| 20 | TS18 | Cambio de idioma | Como developer, quiero permitir cambiar el idioma para mejorar la accesibilidad. | 2 |
| 21 | TS19 | Contacto con soporte | Como usuario, quiero contactar al soporte para resolver dudas sobre el sistema. | 2 |
| 22 | TS22 | Manejo de errores del sistema | Como developer, quiero gestionar errores para garantizar la estabilidad del sistema. | 3 |



# Capítulo IV: Product Design
## 4.1. Style Guidelines
Una Style Guidelines es un conjunto de lineamientos y criterios que establecen la forma en que deben redactarse, diseñarse o presentar documentos, contenido web, software u otros tipos de trabajos creativos. A continuación, se describen las especificaciones de los parámetros aplicados en la estructura del proyecto.

### 4.1.1. General Style Guidelines. 
__Branding:__

__Typography:__ 
Para la tipografía de God's Tracker, se ha seleccionado una fuente moderna, clara y fácil de leer, ideal para pantallas y aplicaciones móviles. La tipografía principal es Inter, una fuente limpia que refuerza el carácter profesional y funcional de nuestra plataforma. Para títulos y encabezados, se pueden emplear sus diferentes grosores para organizar mejor la información visual y facilitar la lectura de los datos de los vehículos.

<img width="710" height="319" alt="image" src="https://github.com/user-attachments/assets/5a362bd2-8518-4fdd-85ce-877de3ca357f" /> <br>

__Colors:__
La paleta de colores de God's Tracker se compone de tonos que evocan precisión, seguridad y control. Los colores seleccionados son neutros pero funcionales, lo cual permite captar la atención del usuario en los datos críticos sin saturar visualmente la interfaz. A continuación, se presentan los colores seleccionados para God's Tracker:

<img width="644" height="331" alt="image" src="https://github.com/user-attachments/assets/f3a64136-ac0d-451e-8523-fbe3dcce1e1c" /> <br>

__Spacing:__
El espaciado es un elemento clave en el diseño de God's Tracker, ya que permite mantener una interfaz ordenada, limpia y fácil de navegar. Se ha utilizado un espaciado preciso y coherente entre elementos, lo cual mejora la legibilidad de los datos y crea una sensación de equilibrio visual necesaria para el monitoreo vehicular. El uso uniforme del espacio contribuye a una experiencia de usuario fluida y eficiente, facilitando la gestión de información tanto en dispositivos móviles como en escritorio.

<img width="1024" height="452" alt="image" src="https://github.com/user-attachments/assets/695b3718-1760-4e20-917a-926695bd0ddb" /> <br>

### 4.1.2. Web Style Guidelines
La interfaz web de God's Tracker está diseñada con un estilo moderno, sólido y totalmente adaptable a distintos dispositivos, asegurando un control operativo fluido tanto en móviles como en pantallas de escritorio. Se emplea una paleta de colores neutros con acentos técnicos que proyectan seguridad, la tipografía Inter para una lectura precisa de datos, y componentes visuales funcionales como botones de acción clara e íconos intuitivos para la gestión de vehículos.

Además, se prioriza la eficiencia del usuario mediante una navegación directa, menús simplificados para el monitoreo en tiempo real, tarjetas de estado detalladas y transiciones rápidas. Todo el diseño responde a criterios de accesibilidad y alto contraste, garantizando una legibilidad óptima de la información crítica y una respuesta inmediata ante cualquier alerta del sistema.


## 4.2. Information Architecture
La arquitectura de información de God's Tracker está diseñada para optimizar la gestión y el monitoreo de vehículos, facilitando el acceso rápido a datos críticos tanto para administradores como para conductores. La plataforma permite rastrear la ubicación en tiempo real, visualizar rutas y gestionar alertas de seguridad. La estructura de la información facilita la exploración del contenido, mejora la accesibilidad a las funciones principales y permite una experiencia fluida e intuitiva, asegurando así una respuesta eficiente ante cualquier evento operativo.


### 4.2.1 Organization Systems. 

God's Tracker aplica distintos tipos de organización para gestionar la complejidad de los datos de telemetría y asegurar que la respuesta ante emergencias sea inmediata:

**Organización jerárquica visual:** <br/>
Para una navegación intuitiva, tanto para persona natural, empresas y organismos gubernamentales cuentan con accesos laterales clave en la pantalla principal. Las personas naturales disponen de "Estado en Vivo" para monitoreo GPS en tiempo real, "Alertas de Seguridad" para gestionar notificaciones críticas, "Historial de Rutas" para reconstrucción cronológica de recorridos y "Configuración del Dispositivo" para ejecutar el bloqueo remoto. Por otro lado, las empresas acceden a "Panel de Activos" para el control centralizado de la flota, "Analíticas de Rendimiento" para evaluar el consumo de combustible, "Gestión de Conductores" para monitorear comportamientos de manejo y "Reportes Operativos" para la descarga de métricas de rentabilidad. Finalmente, los organismos gubernamentales cuentan con "Mapa de Calor de Incidentes" para identificar zonas de alto riesgo criminal, "Unidades en Emergencia" para una respuesta táctica inmediata ante robos confirmados y "Centro de Coordinación" para la gestión interinstitucional y almacenamiento seguro de datos.

**Organización secuencial:** <br>
En la ejecución del protocolo de seguridad activa para usuarios, la secuencia comienza con la detección de una alerta de movimiento sospechoso, seguida por la validación de identidad del propietario y la selección del comando de acción, culminando con la confirmación del bloqueo remoto del motor. De manera similar, el registro de una nueva unidad por parte de las empresas sigue este orden: vinculación del ID del dispositivo IoT, configuración de los parámetros de telemetría, asignación de un conductor responsable y, finalmente, la activación del monitoreo en el panel centralizado.

**Organización matricial:** <br>
En la sección de analítica avanzada y reportes, los usuarios refinan la información mediante filtros combinables que permiten cruzar datos de distintas categorías. Por ejemplo, los administradores de flotas pueden filtrar simultáneamente por unidad vehicular, rango de fechas, comportamiento de manejo y consumo de combustible. Los resultados se actualizan dinámicamente en una cuadrícula interactiva, permitiendo identificar correlaciones directas entre el estilo de conducción y la eficiencia operativa del activo.

**Sistemas de categorización:**

- **Por tópicos:** Estado en vivo, alertas de seguridad, historial de rutas, gestión de activos, analíticas de rendimiento y protocolos de emergencia.

- **Cronológica:** Registro de eventos por milisegundos y ordenamiento de reportes operativos según fechas específicas (día, semana o mes).

- **Alfabética:** Búsqueda y ordenamiento por nombre del conductor, ID del dispositivo IoT, nombre de la sede logística o placa del vehículo.

- **Por audiencia:** Se presentan interfaces diferenciadas para Personas Naturales (protección y bloqueo), Empresas (gestión de flotas) y Organismos Gubernamentales (gestión de incidentes).

### 4.2.2. Labeling Systems. 
Para garantizar una experiencia intuitiva y sin confusiones, las etiquetas empleadas en God's Tracker han sido diseñadas con base en principios de simplicidad, claridad y consistencia técnica.

**Etiquetas para la navegación principal (menú lateral):**

* **Estado en vivo:** Acceso al monitoreo GPS y telemetría de las unidades en tiempo real.
* **Alertas:** Sección dedicada a la gestión de notificaciones críticas y eventos de seguridad.
* **Historial:** Espacio para la reconstrucción cronológica de rutas y eventos pasados.
* **Panel de control:** Acceso a la configuración del dispositivo, gestión de usuarios y perfiles.

**Etiquetas para acciones:**

* **Bloquear motor:** Acción de seguridad de alta prioridad para inmovilizar la unidad de forma remota.
* **Vincular dispositivo:** Entrada para registrar un nuevo hardware IoT mediante ID o código QR.
* **Generar reporte:** Acción para extraer métricas de rendimiento o incidencias en formato PDF/Excel.
* **Confirmar identidad:** Validación necesaria para ejecutar comandos críticos de seguridad.

**Etiquetas asociativas para categorías:**

* **Críticas, Preventivas, Informativas:** Categorías que agrupan las alertas según su nivel de urgencia.
* **En ruta, Estacionado, Fuera de zona:** Estados operativos que agrupan las unidades según su actividad actual.
* **Combustible, Velocidad, Conducción:** Agrupaciones de métricas para el análisis de rendimiento de flotas.

### 4.2.3. SEO Tags and Meta Tags 

### 4.2.4. Searching Systems.

### 4.2.5. Navigation Systems. 

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe
La navegación principal está compuesta por secciones clave: Home, About Us, Benefits, How Does It Work?, FAQs, Contact, complementadas por botones visibles de Login y Sign Up, ubicados estratégicamente para facilitar el acceso de los usuarios según su necesidad. La estructura de la landing page fue pensada para acompañar al visitante de forma progresiva, desde entender la propuesta de valor en seguridad vehicular hasta generar confianza e impulsar la acción de registro.

**Desktop Web Browser** 
Se presentan las siguientes secciones: 

+ Navbar: Fijo en la parte superior con acceso directo a todas las secciones del sitio y botones a la derecha para iniciar sesión o registrarse.
+ Hero Section: Espacio destacado con un eslogan potente y un botón de llamada a la acción que invita al usuario a proteger su vehículo de inmediato.
+ About Us: Breve sección que detalla la misión de God's Tracker: transformar la seguridad vehicular mediante tecnología inteligente.
+ Benefits: Cards visuales que muestran las ventajas competitivas de la plataforma, como rastreo en tiempo real, alertas de seguridad y optimización de rutas, usando íconos claros.
+ How Does It Work?: Sección paso a paso que explica el flujo de uso de la plataforma, desde la instalación del sistema hasta la visualización de datos en el panel de control.
+ FAQs: Preguntas frecuentes en formato acordeón, enfocadas en resolver dudas sobre la instalación, precisión del rastreo y seguridad de la información.
+ Contact: Formulario básico para consultas técnicas o soporte, junto con información de contacto directa y ubicación.
+ Footer: Enlaces a redes sociales, información legal y accesos rápidos a secciones institucionales.


<div align="center">
<img src="images/WIREFRAMES_1.png">
</div>

### 4.3.2. Landing Page Mock-up

<div align="center">
<img src="images/MOCKUP_1.png">
</div>

## 4.4. Web Applications UX/UI Design
La propuesta de wireframes fue desarrollada aplicando los principios de diseño centrado en el usuario, accesibilidad, jerarquía visual y usabilidad. Se busca asegurar una navegación clara y coherente, adaptando la estructura y contenido de la interfaz según el tipo de usuario, optimizando la experiencia en situaciones que requieren monitoreo y respuesta rápida. 

Estructura General:
La interfaz cuenta con una barra de navegación lateral que permite acceder de forma rápida a las funcionalidades principales del sistema. Las secciones están organizadas estratégicamente para priorizar el monitoreo en tiempo real, la gestión de alertas y el control del vehículo.

**Para persona natural**  
Se divide en Inicio, Estado en Vivo, Alertas de Seguridad, Historial de Rutas y Configuración, donde el usuario puede monitorear su vehículo, recibir notificaciones y ejecutar acciones de seguridad de manera inmediata.

**Inicio**  

Esta sección presenta un resumen general del estado del vehículo, permitiendo al usuario obtener información rápida sin necesidad de navegar por otras vistas.

<div align="center">
    <img src="images/FRAME 1_FRONTEND_WIREFRAME.png">
</div>

**Estado en Vivo** 

Esta sección permite visualizar la ubicación del vehículo en tiempo real mediante un mapa interactivo, mostrando información actualizada constantemente. 

<div align="center">
    <img src="images/FRAME 2_FRONTEND_WIREFRAME.png">
</div>

**Alertas de Seguridad** 

Esta sección permite gestionar las notificaciones relacionadas con eventos de riesgo o actividad sospechosa. 

<div align="center">
    <img src="images/FRAME 3_FRONTEND_WIREFRAME.png">
</div>

**Historial de Rutas**

Permite visualizar los recorridos realizados por el vehículo en fechas específicas. 

<div align="center">
    <img src="images/FRAME 4_FRONTEND_WIREFRAME.png">
</div>

**Configuración** 

Esta sección permite gestionar los ajustes del dispositivo y preferencias del usuario, presentándose como una vista independiente. 

<div align="center">
    <img src="images/FRAME 5_FRONTEND_WIREFRAME.png">
</div>

### 4.4.1. Web Applications Wireframes

### 4.4.2. Web Applications Wireflow Diagrams

### 4.4.3. Web Applications Mock-ups

### 4.4.4. Web Applications User Flow Diagrams

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level Event Storming

### 4.6.2. Software Architecture Context Diagram

<div align="center">
    <img src="images/01-SystemContext.png">
</div>

### 4.6.3. Software Architecture Container Diagrams

<div align="center">
    <img src="images/02-Containers.png">
</div>

### 4.6.4. Software Architecture Components Diagrams

<div align="center">
    <img src="images/03-BC1-IdentityAccess.png">
</div>

<div align="center">
    <img src="images/04-BC2-FleetsVehicles.png">
</div>

<div align="center">
    <img src="images/05-BC3-DevicesTelemetry.png">
</div>

<div align="center">
    <img src="images/06-BC4-Alerting.png">
</div>

<div align="center">
    <img src="images/07-BC5-SecurityCommands.png">
</div>


## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

<div align="center">
    <img src="images/Diagrama de clases.png">
</div>

## 4.8. Database Design
### 4.8.1. Database Diagrams

<div align="center">
    <img src="images/Diagrama de base de datos.png">
</div>

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

### 5.1.2. Source Code Management

### 5.1.3. Source Code Style Guide & Conventions

### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

<table>
  <caption>Sprint #1</caption>
  <thead>
    <tr>
      <th colspan="2">Sprint Planning Backlog</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Fecha</td>
      <td></td>
    </tr>
    <tr>
      <td>Hora</td>
      <td></td>
    </tr>
    <tr>
      <td>Ubicación</td>
      <td></td>
    </tr>
    <tr>
      <td>Preparado por</td>
      <td>Integrantes de </td>
    </tr>
    <tr>
      <td>Asistentes (a la reunión de planificación)</td>
      <td>Todos los miembros de </td>
    </tr>
    <tr>
      <td>
        <strong>Sprint 1 Review</strong>
      </td>
      <td>
        .
      </td>
    </tr>
    <tr>
      <td>
        <strong>Sprint 1 Retrospective</strong>
      </td>
      <td>
        .
      </td>
    </tr>
    <tr>
      <td colspan="2">
        <strong>Sprint Goal and User Stories</strong>
      </td>
    </tr>
    <tr>
      <td>
        <strong>Sprint 1 Goal</strong>
      </td>
      <td>
        .
      </td>
    </tr>
    <tr>
      <td><strong>Sprint 1 Velocity</strong></td>
      <td></td>
    </tr>
    <tr>
      <td><strong>Sum of Story Points</strong></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### 5.2.1.2. Aspect Leaders and Collaborators
#### 5.2.1.3. Sprint Backlog 1

<table align="center" border="1" width="90%" style="text-align:center">
    <tr>
       <td colspan="1"><b>Sprint #</b></td>
       <td colspan="7"><b>Sprint 1</b></td>
     </tr>
     <tr>
       <td colspan="2"><b>User Story</b></td>
       <td colspan="6"><b>Work-Item / Task</b></td>
     </tr>
     <tr>
       <td><b>Id</b></td>
       <td><b>Title</b></td>
       <td><b>Id</b></td>
       <td><b>Title</b></td>
       <td><b>Description</b></td>
       <td><b>Estimation(Hours)</b></td>
       <td><b>Assigned To</b></td>
       <td><b>Status(To-do/ In-Process/ To-Review/ Done)</b></td>
     </tr>
     <tr>
       <td rowspan="1">US</td>
       <td rowspan="1"></td>
       <td>T01</td>
       <td></td>
       <td> </td>
       <td></td>
       <td></td>
       <td></td>
    </tr>
    </tr>
        <tr>
       <td rowspan="1">US</td>
       <td rowspan="1"></td>
       <td>T02</td>
       <td></td>
       <td></td>
       <td></td>
    </tr>
    <tr>
       <td rowspan="1">US</td>
       <td rowspan="1"></td>
       <td>T03</td>
       <td></td>
       <td></td>
       <td></td>
       <td> </td>
       <td></td>
    </tr>
</table>

#### 5.2.1.4. Development Evidence for Sprint Review

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Commited On (Date) |
|------------|--------|-----------|----------------|---------------------|--------------------|
| |  |  |  |
| |  |  |  |  |  |
| |  |  |  |  |  |
| |  |  |  |  |  |
| |  |  |  |  |  |

#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint

## 5.3. Validation Interviews

### 5.3.1. Diseño de Entrevistas

### 5.3.2. Registro de Entrevistas

### 5.3.3. Evaluaciones según heurísticas

## 5.4. Video About-the-Product

# Conclusiones 
# Bibliografía
# Anexos
