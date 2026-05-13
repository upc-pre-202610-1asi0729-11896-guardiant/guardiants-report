<!-- Carátula -->

<div align="center">
    <img src="./logo-upc.png">
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
| U202410211  | Manosalva Tovar, Miroslav Oscar     |
| U202414356  | Vite Celis, Rodrigo Matias          |

<div style="font-weight: bold;"> Abril, 2026</div>

</div>

## Registro de Versiones del Informe

| Versión | Fecha    | Autor       | Descripción de Modificación            |
| ------- | -------- | ----------- | -------------------------------------- |
| 0.1     | 07/04/26 | Poma Muñoz, Ariadna Geraldine    | Desarrollo de la Estructura del informe |
| 0.1    | 00/04/26 | Navarro Aldoradin, Carolina Celeste | Desarrollo de la Estructura del informe|
| 0.1    | 00/04/26 | Lozano Quispe, Fabricio Jofred | Desarrollar de la estructura del informe |
| 0.1    | 00/04/26 | Vite Celis, Rodrigo Matias | Desarrollo de la Estructura del informe|



## Project Report Collaboration Insights

| URL de la organización del proyecto | URL del repositorio del reporte   |
| :------------------: | :---------------------------: | 
|  |  |

| URL del repositorio de la landing page |
| :----------------------------: | 
|  | 



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
<div style="font-weight: bold"> Carolina Celeste Navarro Aldoradin</div> u20241b962
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
<div style="font-weight: bold">Rodrigo Matias Vite Celis</div> u202412903 | Ingeniería de Software <br>
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

**Segmento #3: Organismos Gubernamentales** <br> 
Organismos del estado como la policía y otros interesados del Ministerio del interior para proteger los activos y personas de manera segura y confiable. Se considera la ubicación de los servidores para ese segmento en sus ubicaciones designadas.
- Aspectos demográficos:
  - Tipo de entidad: Policía Nacional, Ministerios (MININTER), municipalidades (Serenazgo) y entidades de respuesta a emergencias.
  - Ubicación: Jurisdicciones distritales, regionales y nacionales que requieren servidores en ubicaciones designadas.
- Aspectos psicográficos:
  - Motivaciones: Reducir los índices de criminalidad, mejorar la tasa de recuperación de vehículos robados y contar con datos precisos para inteligencia criminal.
  - Intereses: Seguridad y privacidad de la información, control absoluto sobre el almacenamiento de los datos en servidores locales, comunicación fluida entre diferentes unidades de vigilancia y la digitalización de sus procesos de seguridad ciudadana.
  - Comportamiento: Priorizan la seguridad de la información y la estabilidad de los sistemas. Prefieren soluciones que se integren con sus centros de monitoreo existentes y que permitan la gestión masiva de datos en tiempo real bajo estrictos protocolos de acceso.
  

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores.
### 2.1.1. Análisis competitivo
  
**Objetivo del análisis:** Determinar cómo se posiciona nuestra solución de protección de carga mediante IoT frente a las alternativas existentes y definir un modelo de precios competitivo en el mercado de Latinoamérica.

| Característica | **Mi Startup (Propuesta)** | **SITRACK** | **Lojack México** | **Wialon (Gurtam)** | **Cloudtainer** | **IA27** |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Logo** | ![Logo Mi Startup](url_imagen) | ![Logo Sitrack](url_imagen) | ![Logo Lojack](url_imagen) | ![Logo Wialon](url_imagen) | ![Logo Cloudtainer](url_imagen) | ![Logo IA27](url_imagen) |
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
1.	¿Les preocupa la seguridad de sus vehículos o carga? 
2.	¿Han tenido problemas de robos o pérdidas? 
3.	¿Cómo hacen actualmente para saber dónde están sus vehículos? 
4.	¿Les gustaría ver la ubicación de todos sus vehículos en tiempo real? 
5.	¿Qué tan útil sería recibir alertas si un vehículo sale de ruta o se detiene mucho tiempo? 
6.	¿Qué tipo de información necesitan sobre sus vehículos (ubicación, rutas, paradas)? 
7.	¿Les ayudaría tener reportes automáticos sobre el uso de sus vehículos? 
8.	¿Qué tan fácil debería ser usar una plataforma de monitoreo para su equipo? 
9.	¿Qué es lo más importante en un sistema como este? 
10.	¿Usarían una sola plataforma para controlar toda su flota? 
11.	¿Qué problemas les gustaría solucionar con una herramienta como esta? 
12.	¿Recomendarían este tipo de solución a otras empresas?
    
**Preguntas complementarias**

13.	¿A qué se dedica su empresa? 
14.	¿Cuántos vehículos manejan aproximadamente? 
15.	¿Cuál es su cargo dentro de la empresa? 
16.	¿En qué ciudades o zonas operan? 
17.	¿Qué herramientas digitales usan actualmente? 
18.	¿Qué tan seguido usan computadoras o apps para el trabajo? 

**Tercer segmento: Organismos gubernamentales**

A continuación, se presentan las preguntas dirigidas al segmento de organismos gubernamentales, compuesto por entidades del Estado como fuerzas policiales y organismos del Ministerio del Interior, interesados en la seguridad, monitoreo y gestión eficiente de activos vehiculares.

**Preguntas principales**
1.	¿Les preocupa la seguridad de sus vehículos o unidades? 
2.	¿Qué problemas han tenido con el control de sus vehículos? 
3.	¿Les gustaría saber en tiempo real dónde están todas sus unidades? 
4.	¿Qué tan útil sería recibir alertas si un vehículo se mueve sin autorización? 
5.	¿Qué tipo de alertas les ayudarían más en su trabajo? 
6.	¿Qué información necesitan para tomar decisiones rápidas en campo? 
7.	¿Les ayudaría tener todo el monitoreo en una sola plataforma? 
8.	¿Qué tan importante es que el sistema sea fácil de usar? 
9.	¿Qué es lo más importante en una solución de este tipo? 
10.	¿Les daría más confianza un sistema seguro que proteja bien la información? 
11.	¿Qué problemas actuales les gustaría resolver con una herramienta como esta? 
12.	¿Usarían una solución como GOD’s Tracker en su institución?

**Preguntas complementarias**

13.	¿En qué institución trabaja? 
14.	¿Cuál es su cargo? 
15.	¿Qué tipo de vehículos o unidades manejan? 
16.	¿En qué zona realizan sus operaciones? 
17.	¿Qué herramientas tecnológicas usan actualmente? 
18.	¿Qué tan familiarizado está con el uso de apps o sistemas digitales?

### 2.2.2. Registro de entrevistas
> Segmento 1: Persona naturale
<div align="center">

| Nº Entrevista | Datos del entrevistado                                                                                                                                                                | Resumen de la entrevista                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | Evidencia de entrevista                          |
|---------------|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------|
| 1             | - **Nombre:** ------ <br> - **Edad:** 00 <br> - **Distrito:**  <br> - **Link:** colocar link |                                                                                                           | imagenn aca |
| 2             | - **Nombre:** ------ <br> - **Edad:** 00 <br> - **Distrito:**  <br> - **Link:** colocar link |                                                                                                           | imagenn aca |                                                                                                                 |  |
| 3             | - **Nombre:** ------ <br> - **Edad:** 00 <br> - **Distrito:**  <br> - **Link:** colocar link |                                                                                                           | imagenn aca |

</div>

### Resumen de entrevistas segmento #1

> Segmento 2: Empresas
<div align="center">

| Nº Entrevista | Datos del entrevistado                                                                                                                                                                | Resumen de la entrevista                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | Evidencia de entrevista                          |
|---------------|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------|
| 1             | - **Nombre:** ------ <br> - **Edad:** 00 <br> - **Distrito:**  <br> - **Link:** colocar link |                                                                                                           | imagenn aca |
| 2             | - **Nombre:** ------ <br> - **Edad:** 00 <br> - **Distrito:**  <br> - **Link:** colocar link |                                                                                                           | imagenn aca |                                                                                                                 |  |
| 3             | - **Nombre:** ------ <br> - **Edad:** 00 <br> - **Distrito:**  <br> - **Link:** colocar link |                                                                                                           | imagenn aca |

</div>

### Resumen de entrevistas segmento #2

> Segmento 3: Organismos Gubernamentales
<div align="center">

| Nº Entrevista | Datos del entrevistado                                                                                                                                                                | Resumen de la entrevista                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | Evidencia de entrevista                          |
|---------------|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------|
| 1             | - **Nombre:** ------ <br> - **Edad:** 00 <br> - **Distrito:**  <br> - **Link:** colocar link |                                                                                                           | imagenn aca |
| 2             | - **Nombre:** ------ <br> - **Edad:** 00 <br> - **Distrito:**  <br> - **Link:** colocar link |                                                                                                           | imagenn aca |                                                                                                                 |  |
| 3             | - **Nombre:** ------ <br> - **Edad:** 00 <br> - **Distrito:**  <br> - **Link:** colocar link |                                                                                                           | imagenn aca |

</div>

### Resumen de entrevistas segmento #3


### 2.2.3. Análisis de entrevistas.

**Segmento Objetivo: Persona natural**

**Segmento Objetivo: Empresas**

**Segmento Objetivo: Organismos Gubernamentales**

## 2.3. Needfinding
### 2.3.1. User Personas

En esta sección vamos a detallar las tareas que realizan los diferentes segmentos de usuarios representados por los User Personas de nuestra aplicación GOD's Tracker

>Segmento 1: Persona Natural

>Segmento 2: Empresas

>Segmento 3: Organismos Gubernamentales

### 2.3.2. User Task Matrix  

>Segmento 1: Persona Natural

|Tarea| Frecuencia| Importancia|
|-----|-----------|-------------|
|----| Often|	High|
|-----|	Often|	High|
-----|	Often|	High|
------|	Occasionally	|High|
-----	|Sometimes	|Medium|
-----	|Occasionally	|Medium|

>Segmento 2: Empresas

|Tarea| Frecuencia| Importancia|
|-----|-----------|-------------|
------	|Often	|High|
------- |	Often	|High|
------	|Often	|High|
------	|Sometimes|	Medium|
-----	|Occasionally	|Medium|
-----	|Occasionally	|Medium|
-----	|Rarely	|Medium|  

>Segmento 3: Organismos Gubernamentales

|Tarea| Frecuencia| Importancia|
|-----|-----------|-------------|
------	|Often	|High|
------- |	Often	|High|
------	|Often	|High|
------	|Sometimes|	Medium|
-----	|Occasionally	|Medium|
-----	|Occasionally	|Medium|
-----	|Rarely	|Medium|  

### 2.3.3. User Journey Mapping  

### 2.3.4. Empathy Mapping    

### 2.3.5. As-Is Scenario Mapping  


## 2.4. Ubiquitous Language  

| Término | Definición |
| ------- | ------- |
|  |  | 
|  | | 
|  |  | 
|  |  | 
|  |  | 
| |  | 
|  |  | 
|  |  | 
|  |  | 


# Capítulo III: Requirements Specifications
### 3.1 To-Be Scenario Mapping

>Segmento 1: Persona Natural

>Segmento 2: Empresas

>Segmento 3: Organismos Gubernamentales

## 3.2. User Stories

<table>
    <thead>
        <tr style="text-align:center">
            <th>ID</th>
            <th>Nombre</th>
            <th>Descripción</th>
            <th>Criterios de aceptación</th>
            <th>Épica</th>
        </tr>
    </thead>
    <tbody>
        <tr style="text-align:center">
            <td>US01</td>
            <td></td>
            <td></td>
            <td></td>
            <td>EP01</td>
        </tr>
        <tr style="text-align:center">
            <td>US02</td>
            <td></td>
            <td></td>
            <td></td>
            <td>EP02</td>
        </tr>
    </tbody>
</table>

## 3.3. Impact Mapping
El Impact Mapping es una metodología visual y ágil que permite a las organizaciones enfocar el desarrollo de productos y servicios en función de sus metas estratégicas. Esta técnica facilita la identificación de una relación directa entre los objetivos del negocio, las acciones esperadas de los usuarios clave y las soluciones o funcionalidades que deben implementarse para lograr dichos objetivos.

Impact Map - Segmento 1:

Impact Map - Segmento 2:

Impact Map - Segmento 3:

## 3.4. Product Backlog

| #Orden | User Story Id | Título             | Descripción                                      | Story Points |
|--------|---------------|--------------------|--------------------------------------------------|--------------|
| 1      | US01          |     |      |             |
| 2      | US02          |     |      |             |
| 3      | US03          |     |      |             |




# Capítulo IV: Product Design
## 4.1. Style Guidelines
Una Style Guidelines es un conjunto de lineamientos y criterios que establecen la forma en que deben redactarse, diseñarse o presentar documentos, contenido web, software u otros tipos de trabajos creativos. A continuación, se describen las especificaciones de los parámetros aplicados en la estructura del proyecto.

### 4.1.1. General Style Guidelines. 

### 4.1.2. Web Style Guidelines

## 4.2. Information Architecture

### 4.2.1 Organization Systems. 

### 4.2.2. Labeling Systems. 

### 4.2.3. SEO Tags and Meta Tags 

### 4.2.4. Searching Systems.

### 4.2.5. Navigation Systems. 

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

### 4.3.2. Landing Page Mock-up

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes

### 4.4.2. Web Applications Wireflow Diagrams

### 4.4.3. Web Applications Mock-ups

### 4.4.4. Web Applications User Flow Diagrams

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level Event Storming

### 4.6.2. Software Architecture Context Diagram

### 4.6.3. Software Architecture Container Diagrams

### 4.6.4. Software Architecture Components Diagrams

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

## 4.8. Database Design

### 4.8.1. Database Diagrams


# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration
<!-- Nombres de productos, el
propósito de uso en el proyecto, la ruta de referencia de los productos de software que deben utilizar los miembros del equipo para colaborar en el ciclo de vida del producto
digital, considerando todos los tipos de actividades como Project Management,
Requirements Management, Product UX/UI Design, Software Development,
Software Deployment, Software Documentation, respetando las restricciones
indicadas sobre productos de software y herramientas que se pueden utilizar.-->


**Project Management**

| Producto | Propósito | Ruta |
|----------|-----------|------|
| GitHub Projects | Planificación y seguimiento de issues, user stories y tareas del equipo mediante tableros Kanban. | https://github.com |
| WhatsApp | Comunicación rápida, coordinación de tareas mediante encuestas en el chat grupal y seguimiento de avances diarios. | https://www.whatsapp.com/ |
| Discord | Reuniones de equipo en voz y video para sesiones de planificación, revisión y retrospectiva de sprints. | https://discord.com/ |

---

**Requirements Management**

| Producto | Propósito | Ruta |
|----------|-----------|------|
| GitHub | Gestión de requerimientos mediante Issues y documentación versionada del proyecto. | https://github.com |
| UXPressia | Creación de artefactos de needfinding: User Personas, User Journey Maps y Empathy Maps para comprender las necesidades de los segmentos objetivo. | https://uxpressia.com/ |
| Miro | Desarrollo de Event Storming (Big Picture y Design Level) para el modelado de procesos y definición del dominio del sistema. | https://miro.com/ |
| Gherkin | Definición de criterios de aceptación y escenarios de prueba en formato Given–When–Then. | https://plugins.jetbrains.com/plugin/9164-gherkin |
| Markdown | Documentación estructurada de requerimientos dentro del repositorio del proyecto. | Integrado en GitHub |

---

**Product UX/UI Design**

| Producto | Propósito | Ruta |
|----------|-----------|------|
| Figma | Diseño de wireframes, mockups y prototipos interactivos de la interfaz, tanto para la Landing Page como para la Web Application. | https://www.figma.com/ |
| LucidChart | Elaboración de wireflows, user flows y diagramas de arquitectura complementarios. | https://www.lucidchart.com/ |

---

**Software Development**

| Producto | Propósito | Ruta |
|----------|-----------|------|
| Visual Studio Code | IDE principal para la programación del frontend (Landing Page y Web Application). | https://code.visualstudio.com/ |
| WebStorm | Entorno de desarrollo especializado para aplicaciones JavaScript y TypeScript. IDE complementario a VSCode. | https://www.jetbrains.com/webstorm/ |
| IntelliJ IDEA | IDE para el desarrollo del backend con Spring Boot y Java. | https://www.jetbrains.com/idea/ |
| Angular Framework | Desarrollo de la Web Application interactiva con TypeScript, HTML5 y CSS3. | https://angular.io/ |
| Spring Boot | Desarrollo de la lógica del servidor y la RESTful API bajo arquitectura orientada a servicios. | https://spring.io/projects/spring-boot |
| HTML5 / CSS3 / JavaScript | Tecnologías base para el desarrollo del Landing Page estático. | https://developer.mozilla.org/ |
| GitHub | Control de versiones y trabajo colaborativo mediante repositorios, commits y branches. | https://github.com |

---

**Software Deployment**

| Producto | Propósito | Ruta |
|----------|-----------|------|
| GitHub Pages | Despliegue del Landing Page estático de GuardiAnts directamente desde el repositorio. | https://pages.github.com/ |

---

**Software Documentation**

| Producto | Propósito | Ruta |
|----------|-----------|------|
| Structurizr | Elaboración de diagramas de arquitectura de software utilizando el modelo C4 (contexto, contenedor, componentes). | https://structurizr.com/ |
| OpenAPI / Swagger | Documentación de los endpoints del RESTful API de GuardiAnts. | https://swagger.io/ |
| Markdown | Documentación técnica del proyecto, desde el reporte hasta las user stories, licencias y otros artefactos. | Integrado en GitHub |

---

### Estrategia de Trabajo: GitFlow

El equipo ha implementado el modelo de trabajo **GitFlow**, propuesto por Vincent Driessen. Bajo este esquema se mantienen dos ramas permanentes: **main** (código estable y listo para producción) y **develop** (rama de integración para el desarrollo activo).

- **Feature Branches:** Cada funcionalidad se trabaja en ramas aisladas bajo la nomenclatura `feature/<nombre-de-sección>` (ej. `feature/gps-monitoring`, `feature/alert-system`).
- **Release Branches:** Al aproximarse una entrega, se genera una rama `release/vX.Y.Z` desde `develop` para ajustes finales, aplicando **Semantic Versioning**.
- **Integración Final:** Una vez validada, la rama de lanzamiento se fusiona tanto en `main` como en `develop`.
- **Hotfixes:** Las correcciones críticas se resuelven mediante ramas `hotfix/vX.Y.Z` integradas directamente tras su validación.

---

### Conventional Commits

Todos los mensajes de commit siguen la especificación de **Conventional Commits** para mantener un historial de cambios legible y profesional.

**Tipos utilizados:**
- `feat:` incorporación de nuevas funcionalidades
- `fix:` corrección de errores
- `docs:` modificaciones en la documentación
- `style:` cambios de formato o estilo sin impacto en la lógica
- `refactor:` mejoras internas sin añadir funcionalidades
- `test:` creación o modificación de pruebas
- `chore:` tareas de configuración o mantenimiento

**Ejemplos aplicados en el proyecto:**
- `feat(monitoring): add real-time GPS tracking endpoint`
- `fix(alerts): correct timestamp offset in security alerts`
- `docs(chapter-02): add interview analysis and user personas`
- `chore(deps): upgrade Angular Material to latest version`
- `docs(chapter-04): add C4 context and container diagrams`

### Evidencias de Repositorios

**Repositorios en la organización**
<img src="./captura-repos.png">

### 5.1.3. Source Code Style Guide & Conventions
### Regla General
Todos los identificadores (archivos, clases, IDs, variables, etc.) deben estar en **inglés**.

### 1. HTML

*   **Estructura Semántica:** Usar etiquetas semánticas de HTML5 (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`) en lugar de `<div>` genéricos siempre que sea posible.
*   **Etiquetas y atributos en minúsculas:**
    `<section id="home" class="hero"></section>`
*   **Atributos de accesibilidad (A11y) obligatorios:** Incluir siempre `aria-label`, `aria-controls`, `aria-expanded` o `aria-hidden` en elementos interactivos o decorativos.
    `<button class="btn-menu" aria-expanded="false" aria-controls="primaryNav">`
*   **Internacionalización (i18n):** Todo el texto visible por el usuario debe estar vinculado a una clave de traducción mediante el atributo `data-i18n`.
    `<h1 class="hero-title" data-i18n="heroSection.slogan">...</h1>`
*   **Optimización y manejo de imágenes:** 
    *   Cerrar siempre los elementos (`<img ... />`).
    *   Incluir atributo `alt`.
    *   Añadir `loading="lazy"` para imágenes fuera de la primera vista (below the fold) y manejar errores de carga.
    `<img src="assets/vision.png" alt="Vision" loading="lazy" onerror="this.style.display='none'" />`
*   **Comillas dobles:** Usar siempre comillas dobles para los valores de los atributos.
*   **Sangría:** 4 espacios para anidar elementos de forma clara.

### 2. CSS

*   **Variables Globales:** Utilizar la pseudo-clase `:root` para definir la paleta de colores, sombras y otros valores reutilizables.
    `var(--text)`, `var(--bg)`
*   **Convención de Nombres (Clases e IDs):** 
    *   Usar `kebab-case` para nombres de clases. Ej: `.site-header`, `.hero-inner`.
    *   Usar `camelCase` para los IDs que se manipularán con JavaScript. Ej: `#menuToggle`, `#primaryNav`.
*   **Metodología BEM (Bloque, Elemento, Modificador):** Aplicar BEM para variaciones de componentes usando doble guion (`--`) para los modificadores.
    `.section--white { ... }`
    `.split--reverse { ... }`
*   **Diseño Responsivo (Desktop-First):** Seguir la estructura de media queries basada en `max-width` descendente para adaptar el diseño:
    *   Tablets y menores: `@media (max-width: 980px)`
    *   Móviles grandes: `@media (max-width: 720px)`
    *   Móviles pequeños: `@media (max-width: 480px)`
*   **Omitir unidades en valores cero:**
    `margin: 0;` (No `margin: 0px;`)
*   **Separación visual:** Separar los selectores de bloques diferentes con una línea en blanco para mayor legibilidad.

### 3. JavaScript (Integración para el Frontend)

*   **Nomenclatura:** `camelCase` para variables, funciones y referencias al DOM.
    `const menuToggle = document.getElementById('menuToggle');`
*   **Declaración de variables:** Usar `const` por defecto y `let` solo si el valor va a reasignarse. Prohibido el uso de `var`.
*   **Manejo de Eventos del DOM:** Separar la lógica de manipulación del DOM (como abrir/cerrar el menú de navegación o cambiar el idioma) en funciones pequeñas y modulares.
*   **Manipulación de Clases:** Usar `classList.toggle()`, `classList.add()`, y `classList.remove()` para manejar los estados de la UI (ej. `.nav-open`).
    `siteHeader.classList.toggle('nav-open');`
*   **Sintaxis ES6+:** Preferir *arrow functions* para los *event listeners* y *callbacks*.

### 4. Gestión de Archivos y Recursos (Assets)

*   **Nomenclatura de archivos:** Todo en minúsculas y `kebab-case`.
    `logo-guardiants-short.png`, `how-natural-person.png`
*   **Organización:** Mantener las imágenes organizadas dentro de un directorio `/assets/`.
### 5.1.4. Software Deployment Configuration
- Creación de la Landing Page:
1. Se crea un repositorio (guardiants-website) desde upc-pre-202610-1asi0729-11896-guardiant organization
![deployment1-screenshoot](guardiants-website.png)


2. Agregamos a los miembros del equipo

3. Habilitamos GitHub Pages en branch main y ruta "/(root)".


## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

En esta sección se documenta el Sprint Planning Meeting del Sprint 1, en el que el equipo GuardiAnts estableció el objetivo del sprint, definió el alcance de trabajo y distribuyó las tareas entre los integrantes para lograr la primera versión desplegada de la Landing Page de GOD's Tracker.

| Sprint # | Sprint 1 |
|---|---|
| **Sprint Planning Background** | |
| Date | 2026-04-01 |
| Time | 10:00 AM |
| Location | Reunión virtual vía Discord |
| Prepared By | Poma Muñoz, Ariadna Geraldine |
| Attendees (to planning meeting) | Poma Muñoz, Ariadna Geraldine / Navarro Aldoradin, Carolina Celeste / Lozano Quispe, Fabricio Jofred / Vite Celis, Rodrigo Matias |
| Sprint 1 – 1 Review Summary | Al ser el primer sprint, no existe sprint anterior que revisar. El equipo partió de los artefactos definidos en los capítulos I al IV: User Stories, Product Backlog, Style Guidelines, Wireframes y Mockups del Landing Page. |
| Sprint 1 – 1 Retrospective Summary | Al ser el primer sprint, no existe retrospectiva previa. El equipo acordó mantener comunicación continua vía Discord, realizar revisiones de código mediante Pull Requests y respetar las convenciones de código definidas en la sección 5.1.3. |
| **Sprint Goal & User Stories** | |
| Sprint 1 Goal | Our focus is on delivering a fully deployed Landing Page that communicates GuardiAnts' value proposition to potential users. We believe it delivers the first professional touchpoint of the GOD's Tracker product to vehicle owners and fleet managers. This will be confirmed when visitors can navigate all sections of the Landing Page, understand the product's features, view the pricing plans, and access the registration call-to-action from a deployed public URL. |
| Sprint 1 Velocity | 28 Story Points |
| Sum of Story Points | 28 Story Points |


#### 5.2.1.2. Aspect Leaders and Collaborators

Para este Sprint 1, el alcance se centra íntegramente en el desarrollo y despliegue de la Landing Page. Los aspectos identificados corresponden a las secciones funcionales del sitio estático, organizadas de manera que cada integrante asuma liderazgo sobre un aspecto mientras colabora en los demás.

| Team Member (Last Name, First Name) | GitHub Username | Hero & Navbar (L/C) | Features & About (L/C) | Pricing & Testimonials (L/C) | Contact & Footer (L/C) | Deployment & i18n (L/C) |
|---|---|---|---|---|---|---|
| Poma Muñoz, Ariadna Geraldine | InAsui | L | C | C | C | C |
| Navarro Aldoradin, Carolina Celeste | genixmvp | C | L | C | C | L |
| Lozano Quispe, Fabricio Jofred | FabricioZz15 | C | C | L | C | C |
| Vite Celis, Rodrigo Matias | rodriznnn | C | C | C | L | C |


#### 5.2.1.3. Sprint Backlog 1

El objetivo principal del Sprint 1 es desplegar la primera versión funcional de la Landing Page de GuardiAnts (GOD's Tracker), que comunique la propuesta de valor a los segmentos objetivo e incluya los call-to-action correspondientes hacia la Web Application.

| Sprint # | Sprint 1 | | | | | | |
|---|---|---|---|---|---|---|---|
| **User Story** | | **Work-Item / Task** | | | | | |
| Id | Title | Id | Title | Description | Estimation (Hours) | Assigned To | Status |
| US01 | Visualizar landing page | T01 | Estructura HTML base del Landing Page | Crear el archivo `index.html` con la estructura semántica completa (header, main, sections, footer) | 3 | Poma Muñoz, Ariadna | Done |
| US01 | Visualizar landing page | T02 | Estilos globales y variables CSS | Definir variables de color, tipografía y espaciado en `:root` siguiendo el Design System de GuardiAnts | 2 | Poma Muñoz, Ariadna | Done |
| US01 | Visualizar landing page | T03 | Sección Hero y barra de navegación | Implementar el hero section con headline, subheadline, CTAs y la navbar con menú responsive | 4 | Poma Muñoz, Ariadna | Done |
| US02 | Visualizar características del producto | T04 | Sección Features del sistema GPS/IoT | Implementar la sección de características clave: monitoreo en tiempo real, alertas, bloqueo remoto | 3 | Navarro Aldoradin, Carolina | Done |
| US03 | Visualizar información del equipo | T05 | Sección About / Equipo GuardiAnts | Implementar la sección que presenta al startup con descripción de misión y visión | 3 | Navarro Aldoradin, Carolina | Done |
| US04 | Ver planes y precios | T06 | Sección Pricing con planes de suscripción | Implementar tarjetas comparativas de planes para personas naturales y empresas con CTAs | 4 | Lozano Quispe, Fabricio | Done |
| US05 | Visualizar testimonios | T07 | Sección Testimonials | Implementar cuadrícula de testimonios de los entrevistados del proceso de needfinding | 3 | Lozano Quispe, Fabricio | Done |
| US06 | Contactar desde la landing page | T08 | Sección Contact / Footer | Implementar el formulario de contacto y el footer con enlaces legales y redes sociales | 3 | Vite Celis, Rodrigo | Done |
| US01 | Visualizar landing page | T09 | Responsividad completa (Mobile & Desktop) | Aplicar media queries para correcta visualización en dispositivos móviles y desktop | 3 | Vite Celis, Rodrigo | Done |
| US01 | Visualizar landing page | T10 | Soporte multi-idioma (i18n en/es) | Implementar soporte de internacionalización con archivos JSON de traducción | 4 | Navarro Aldoradin, Carolina | Done |
| US01 | Visualizar landing page | T11 | Despliegue en GitHub Pages | Configurar GitHub Pages sobre la rama `main`, verificar despliegue y validar todos los assets | 2 | Navarro Aldoradin, Carolina | Done |


#### 5.2.1.4. Development Evidence for Sprint Review

Durante el Sprint 1, el equipo trabajó de forma colaborativa en el repositorio de la Landing Page, aplicando GitFlow con ramas por feature y mensajes de commit siguiendo Conventional Commits. A continuación se presentan los commits más relevantes relacionados con la implementación.

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Commited On (Date) |
|---|---|---|---|---|---|
| guardiants-website | main | `feat:responsive` | feat: responsive view added | Improved mobile experience for landing page sections. | Apr 22, 2026 |
| guardiants-website | main | `feat:i18n` | feature: i18n foundation | Added JSON processors for en/es translation support. | Apr 21, 2026 |
| guardiants-website | main | `feat:hero` | feat(hero): add hero section with CTA buttons | Hero section with GPS tracking value proposition. | Apr 19, 2026 |
| guardiants-website | main | `feat:pricing` | feat(pricing): add subscription plans section | Plans for persona natural and empresa segments. | Apr 18, 2026 |
| guardiants-report | main | `docs:cap4` | docs(chapter4): add diagrams | Added C4 context, container and component diagrams. | Apr 19, 2026 |
| guardiants-report | main | `docs:ux` | docs(chapter-02): add user personas | Documentation of user profiles for both segments. | Apr 18, 2026 |
| guardiants-report | main | `docs:startup` | docs: update startup description | Detailed profile of GuardiAnts startup and product. | Apr 08, 2026 |


#### 5.2.1.5. Execution Evidence for Sprint Review

Al concluir el Sprint 1, el equipo logró desplegar la primera versión funcional de la Landing Page de GuardiAnts en un entorno público accesible mediante GitHub Pages. La página presenta la propuesta de valor del producto GOD's Tracker de forma clara y estructurada, cubriendo todas las secciones planificadas: Hero, Navbar, Features, About, Pricing, Testimonials, Contact y Footer. La experiencia es consistente tanto en desktop como en dispositivos móviles, e incluye soporte para cambio de idioma (español/inglés).

<div align="center">
<img width="1056" height="3856" alt="image" src="https://github.com/user-attachments/assets/0ce05803-f19d-4f65-b0e6-1017466b2a57" />
</div>

Video de navegación del Sprint 1:

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

Se ha completado la documentación de arquitectura en el repositorio de Report, detallando:
*   Diagramas de Contexto, Contenedor y Componentes (C4 Model).
*   Diagrama de Entidad-Relación para la persistencia de datos.
*   Especificación de estilos y lineamientos de diseño (Capítulo IV).

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

El despliegue de la Landing Page se llevó a cabo mediante **GitHub Pages**. Los pasos realizados fueron:

1. Se creó el repositorio `guardiants-website` en la organización del proyecto.
2. Se desarrolló el sitio estático con HTML5, CSS3 y JavaScript con soporte i18n.
3. Se configuró GitHub Pages en **Settings > Pages**, seleccionando la rama `main` y la ruta `/(root)`.
4. GitHub Pages publicó automáticamente el sitio al detectar el `index.html` en la raíz del repositorio.
5. Se verificó el correcto funcionamiento de todos los enlaces, imágenes y el selector de idioma en el entorno de producción.

#### 5.2.1.8. Team Collaboration Insights during Sprint

Durante el Sprint 1, los cuatro integrantes del equipo GuardiAnts participaron activamente en la implementación de la Landing Page. Cada miembro lideró el aspecto asignado según la Leadership-and-Collaboration Matrix, realizando commits desde sus cuentas de GitHub hacia sus ramas feature correspondientes, y luego integrando mediante Pull Requests hacia `main`.

Se aplicó GitFlow de forma consistente: se crearon ramas con la convención `feature/<nombre-de-sección>` (ej. `feature/hero-section`, `feature/pricing`, `feature/i18n`) y se realizó el merge únicamente tras revisión del código por al menos un integrante del equipo.

## 5.2.2. Sprint 2 

#### 5.2.2.1. Sprint Planning 2

En esta sección se documenta el Sprint Planning Meeting del Sprint 2, en el que el equipo GuardiAnts definió el objetivo de implementar las funcionalidades esenciales de la plataforma web, incluyendo autenticación, monitoreo GPS en tiempo real, alertas de seguridad, gestión de vehículos y configuración del sistema.

| Sprint # | Sprint 2 |
|---|---|
| **Sprint Planning Background** | |
| Date | 2026-05-13 |
| Time | 12:00 PM |
| Location | Reunión virtual vía Discord / Google Meet |
| Prepared By | Poma Muñoz, Ariadna Geraldine |
| Attendees (to planning meeting) | Poma Muñoz, Ariadna Geraldine / Navarro Aldoradin, Carolina Celeste / Lozano Quispe, Fabricio Jofred / Vite Celis, Rodrigo Matias |
| Sprint 1 Review Summary | Durante la revisión del Sprint 1, se validó correctamente la estructura inicial de la Landing Page, la documentación del proyecto y la integración de internacionalización (i18n). La Landing Page fue desplegada exitosamente en GitHub Pages con las secciones Hero, Features, Pricing, Testimonials, Contact y Footer. Los capítulos I al IV del reporte quedaron consolidados con los artefactos de diseño y arquitectura. |
| Sprint 1 Retrospective Summary | En la retrospectiva del Sprint 1, el equipo identificó como puntos fuertes la buena comunicación y coordinación. Como áreas de mejora, se señaló la necesidad de mejorar la gestión del tiempo en la documentación y la resolución de rutas de imágenes en el reporte de Markdown para evitar enlaces rotos. |
| **Sprint Goal & User Stories** | |
| Sprint 2 Goal | Our focus is on developing and deploying the essential functionalities of the GuardiAnts platform related to user authentication, real-time GPS monitoring, vehicle asset management, security alerts, route history and system configuration. We believe it delivers a solid foundation for intelligent vehicle control and allows users to supervise their assets securely and centrally. This will be confirmed when users can register and log in successfully, visualize the location and status of their vehicles, receive security alerts, consult relevant system information, and use the main functionalities from the web platform. |
| Sprint 2 Velocity | 35 Story Points |
| Sum of Story Points | 35 Story Points |

---

#### 5.2.2.2. Aspect Leaders and Collaborators

Para este Sprint 2, el alcance se centra en el desarrollo de la Web Application (guardiants-webapp) con las funcionalidades core del sistema de monitoreo GOD's Tracker.

| Team Member (Last Name, First Name) | GitHub Username | Autenticación (Login / Register) | Monitoreo GPS en tiempo real | Alertas de seguridad | Historial de rutas | Configuración del sistema |
|---|---|---|---|---|---|---|
| Poma Muñoz, Ariadna Geraldine | InAsui | C | C | L | L | C |
| Navarro Aldoradin, Carolina Celeste | genixmvp | C | L | C | C | C |
| Lozano Quispe, Fabricio Jofred | FabricioZz15 | C | L | C | C | L |
| Vite Celis, Rodrigo Matias | rodriznnn | L | C | C | C | C |

---

#### 5.2.2.3. Sprint Backlog 2

El objetivo principal del Sprint 2 es implementar las funcionalidades esenciales de la Web Application de GuardiAnts, cubriendo los procesos core del sistema de monitoreo vehicular inteligente GOD's Tracker.

| Sprint # | Sprint 2 | | | | | | |
|---|---|---|---|---|---|---|---|
| **User Story** | | **Work-Item / Task** | | | | | |
| Id | Title | Id | Title | Description | Estimation (Hours) | Assigned To | Status |
| US07 | Registro de usuario | T12 | Formulario de registro y validación | Implementar vista de registro con campos de nombre, email, contraseña y tipo de cuenta (personal/empresa) | 4 | Vite Celis, Rodrigo | In Process |
| US08 | Inicio de sesión | T13 | Vista de login y autenticación | Implementar vista de login con validación de credenciales y redirección al dashboard | 3 | Vite Celis, Rodrigo | In Process |
| US09 | Dashboard de monitoreo GPS | T14 | Mapa de monitoreo en tiempo real | Integrar mapa interactivo con visualización de ubicación de vehículos en tiempo real mediante API de mapas | 8 | Navarro Aldoradin, Carolina / Lozano Quispe, Fabricio | To-do |
| US09 | Dashboard de monitoreo GPS | T15 | Panel de estado del vehículo | Mostrar indicadores de estado: conectado/desconectado, velocidad actual, batería del dispositivo | 4 | Navarro Aldoradin, Carolina | To-do |
| US10 | Gestión de alertas de seguridad | T16 | Lista de alertas con clasificación | Implementar vista de alertas con clasificación por tipo (movimiento sospechoso, jammer detectado, geocerca) y severidad | 5 | Poma Muñoz, Ariadna | To-do |
| US10 | Gestión de alertas de seguridad | T17 | Notificaciones push en tiempo real | Configurar sistema de notificaciones para alertas críticas de seguridad en la plataforma web | 4 | Poma Muñoz, Ariadna | To-do |
| US11 | Historial de rutas | T18 | Vista de historial de recorridos | Implementar vista de historial de rutas con filtros por fecha, vehículo y tipo de evento | 4 | Poma Muñoz, Ariadna | To-do |
| US12 | Configuración del sistema | T19 | Panel de configuración de cuenta y vehículo | Implementar vistas de configuración de perfil de usuario, datos del vehículo y preferencias de alertas | 3 | Lozano Quispe, Fabricio | To-do |

---

#### 5.2.2.4. Development Evidence for Sprint Review

Durante el Sprint 2, el equipo inició el desarrollo de la Web Application (guardiants-webapp) utilizando Angular Framework. A continuación se presentan los commits más relevantes realizados durante este sprint.

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Commited On (Date) |
|---|---|---|---|---|---|
| guardiants-webapp | develop | `feat:auth` | feat(auth): add login and register views | Authentication views with form validation implemented. | May 10, 2026 |
| guardiants-webapp | develop | `feat:dashboard` | feat(dashboard): add vehicle monitoring dashboard | Base dashboard structure with map container added. | May 11, 2026 |
| guardiants-webapp | develop | `feat:routing` | feat(routing): configure angular routing module | Routes for dashboard, alerts, history and settings configured. | May 09, 2026 |
| guardiants-webapp | develop | `chore:setup` | chore: initial Angular project setup | Angular project scaffolded with Angular Material components. | May 07, 2026 |
| guardiants-platform | develop | `feat:api` | feat(api): initial Spring Boot project setup | Base project with package structure by bounded context. | May 08, 2026 |
| guardiants-website | main | `fix:nav` | fix(nav): correct mobile navigation menu | Fixed hamburger menu display on small devices. | May 05, 2026 |

---

#### 5.2.2.5. Execution Evidence for Sprint Review

Al concluir el Sprint 2, el equipo logró implementar la estructura base de la Web Application de GuardiAnts con las vistas principales del sistema de monitoreo GOD's Tracker. Se completaron las vistas de autenticación (login y registro) y se avanzó en el desarrollo del dashboard de monitoreo GPS. La aplicación está estructurada siguiendo la arquitectura de componentes de Angular con Material Design como sistema de diseño.

Las principales vistas implementadas durante este sprint incluyen:

- **Vista de Login:** Formulario de inicio de sesión con validación de campos, integrado con el flujo de navegación hacia el dashboard principal.
- **Vista de Registro:** Formulario de creación de cuenta con selección de tipo de usuario (persona natural / empresa).
- **Dashboard de Monitoreo:** Estructura base del panel principal con mapa interactivo para visualización GPS y panel de estado de vehículos.
- **Vista de Alertas de Seguridad:** Lista de alertas clasificadas por tipo y severidad (en proceso de integración con el backend).
<div align="center">
<img width="1190" height="570" alt="image" src="https://github.com/user-attachments/assets/3b31b62b-d473-4c35-81df-e9f93b9f8e7f" />
</div>

<div align="center">
<img width="1288" height="811" alt="image" src="https://github.com/user-attachments/assets/64f4c1ca-b89f-4217-969f-ff155bbed726" />
</div>

<div align="center">
<img width="767" height="515" alt="image" src="https://github.com/user-attachments/assets/300a4c36-ef3e-41b2-ab24-1d2ee8e32953" />
</div>

<div align="center">
<img width="810" height="551" alt="image" src="https://github.com/user-attachments/assets/2d699827-c21e-4aae-b4a7-f2e4163f06b9" />
</div>

**Video de navegación del Sprint 2:**


#### 5.2.2.6. Services Documentation Evidence for Sprint Review

Durante el Sprint 2, el equipo inició el desarrollo del RESTful API en el repositorio `guardiants-platform` utilizando Spring Boot. Se definió la estructura base del proyecto con los bounded contexts principales y se configuró Swagger/OpenAPI para la documentación de endpoints.

Los bounded contexts definidos en este sprint son:
- **Identity & Access:** Gestión de autenticación y autorización de usuarios.
- **Vehicle Monitoring:** Endpoints para recepción y consulta de datos GPS en tiempo real.
- **Alert Management:** Endpoints para generación y consulta de alertas de seguridad.
- **Fleet Management:** Gestión de vehículos registrados por usuario o empresa.

#### 5.2.2.7. Software Deployment Evidence for Sprint Review

Durante el Sprint 2 se realizaron las siguientes actividades de despliegue:

- Se actualizó la Landing Page con una nueva versión que incluye correcciones de navegación móvil y mejoras en la sección de testimonios.
- Se inició la configuración del entorno de despliegue para la Web Application (guardiants-webapp) en preparación para el Sprint 3.
- Se configuró el proyecto Spring Boot (guardiants-platform) con las dependencias necesarias para el despliegue en un entorno cloud.

#### 5.2.2.8. Team Collaboration Insights during Sprint

Durante el Sprint 2, los cuatro integrantes del equipo participaron activamente en el desarrollo de la Web Application y el backend de GuardiAnts. Se mantuvo el uso de GitFlow con ramas feature por funcionalidad y la integración mediante Pull Requests revisados por al menos un compañero antes del merge a `develop`.

La comunicación del equipo se realizó a través de Discord para reuniones de sincronización diaria y WhatsApp para coordinación rápida de tareas. Se utilizó GitHub Projects como tablero de seguimiento de tareas del sprint.

## 5.3. Validation Interviews

### 5.3.1. Diseño de Entrevistas
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
1.	¿Les preocupa la seguridad de sus vehículos o carga? 
2.	¿Han tenido problemas de robos o pérdidas? 
3.	¿Cómo hacen actualmente para saber dónde están sus vehículos? 
4.	¿Les gustaría ver la ubicación de todos sus vehículos en tiempo real? 
5.	¿Qué tan útil sería recibir alertas si un vehículo sale de ruta o se detiene mucho tiempo? 
6.	¿Qué tipo de información necesitan sobre sus vehículos (ubicación, rutas, paradas)? 
7.	¿Les ayudaría tener reportes automáticos sobre el uso de sus vehículos? 
8.	¿Qué tan fácil debería ser usar una plataforma de monitoreo para su equipo? 
9.	¿Qué es lo más importante en un sistema como este? 
10.	¿Usarían una sola plataforma para controlar toda su flota? 
11.	¿Qué problemas les gustaría solucionar con una herramienta como esta? 
12.	¿Recomendarían este tipo de solución a otras empresas?
    
**Preguntas complementarias**

13.	¿A qué se dedica su empresa? 
14.	¿Cuántos vehículos manejan aproximadamente? 
15.	¿Cuál es su cargo dentro de la empresa? 
16.	¿En qué ciudades o zonas operan? 
17.	¿Qué herramientas digitales usan actualmente? 
18.	¿Qué tan seguido usan computadoras o apps para el trabajo? 

### 5.3.2. Registro de Entrevistas
## Segmento 1: Persona natural

<div align="center">

| Nº Entrevista | Datos del entrevistado | Resumen de la entrevista | Evidencia de entrevista |
|--------------|------------------------|--------------------------|--------------------------|
| 1 | **Nombre:** Luis Lopez <br> **Edad:** 25 <br> **Distrito:** San Borja <br> **Link:** [link ](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221d382_upc_edu_pe/IQB1t_JXO08-ToO-FehysAJ_Afw6wmSxswLWOmdzimUAfKc?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=sQzaON) <br> Minutos: 0:00 - 3:58|  El entrevistado, trabajador en logística y usuario frecuente de su vehículo, muestra alta preocupación por el robo, reforzada por un intento previo.<br>Considera que las medidas actuales como la alarma y precaución son insuficientes, evidenciando la necesidad de una solución más completa.<br>Valora el monitoreo en tiempo real y las alertas inmediatas (movimiento sospechoso, intento de robo y ubicación), alineándose con la propuesta de GuardiAnts.<br>Prioriza una app simple, rápida y fácil de usar desde el celular, destacando la precisión y confiabilidad del GPS como factores clave.<br>Su perfil digital y disposición a recomendar la solución refuerzan el potencial de adopción del producto. | <p align="center"><img src="https://github.com/user-attachments/assets/3b1bf596-5fa1-444b-b4b2-4f658100e740" width="300"></p> |
| 2 | **Nombre:** Juana Quispe <br> **Edad:** 47 <br> **Distrito:** El Agustino <br> **Link:** [link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221d382_upc_edu_pe/IQB1t_JXO08-ToO-FehysAJ_Afw6wmSxswLWOmdzimUAfKc?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=sQzaON) <br> Minutos: 3:59 - 7:51| La entrevistada, comerciante independiente, evidencia una alta preocupación por la inseguridad vehicular debido al contexto actual de delincuencia en Lima y a experiencias previas de intento de robo y manipulación de su vehículo mientras realizaba sus actividades laborales.<br>Actualmente no cuenta con una medida de seguridad para su auto, pero considera que es insuficiente, ya que busca mayor control y seguimiento constante. Destaca la necesidad de conocer la ubicación de su vehículo en todo momento y recibir alertas inmediatas ante cualquier movimiento sospechoso.<br>Valora especialmente funciones como notificaciones en tiempo real, ubicación precisa y alertas por movimiento, priorizando un sistema que le permita reaccionar rápidamente ante posibles incidentes.<br>Busca una aplicación simple, fácil de usar y accesible desde el celular, que le brinde mayor tranquilidad y control. Además, muestra disposición a adoptar este tipo de tecnología y recomendarla a su entorno si demuestra ser confiable y efectiva. | <p align="center"><img src="https://github.com/user-attachments/assets/1cb0319f-426e-4d72-b3ff-bbfe19d0c88e" width="300"></p> |
| 3 | **Nombre:** Enrique Castillo <br> **Edad:** 22 <br> **Distrito:** Magdalena <br> **Link:** [link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221d382_upc_edu_pe/IQB1t_JXO08-ToO-FehysAJ_Afw6wmSxswLWOmdzimUAfKc?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=sQzaON) <br> Minutos: 7:52 - 12:53| Enrique, un estudiante de 22 años que se mueve por varias zonas de Lima, considera que sí usaría una app de seguridad vehicular sencilla que le permita ver la ubicación de su auto en tiempo real y recibir alertas ante situaciones sospechosas, especialmente por experiencias cercanas de intento de robo. | <p align="center"><img src="https://github.com/user-attachments/assets/183f2f5b-dc91-49ad-b63d-acee24af1438" width="300"></p> |

</div>

### Resumen de entrevistas segmento #1

A partir de las entrevistas, se observa que todos los participantes comparten una fuerte preocupación por la inseguridad vehicular en Lima, influenciada tanto por el contexto actual como por experiencias cercanas o personales de intento de robo. Aunque algunos cuentan con medidas básicas como alarmas o simplemente toman precauciones, coinciden en que estas resultan insuficientes frente a los riesgos actuales, lo que genera una sensación constante de vulnerabilidad. En general, valoran mucho la posibilidad de monitorear su vehículo en tiempo real, recibir alertas inmediatas ante movimientos sospechosos y contar con una ubicación precisa, ya que esto les permitiría reaccionar rápidamente ante cualquier incidente. Además, destacan la importancia de que la solución sea fácil de usar, accesible desde el celular y confiable en términos de funcionamiento. Más allá de las funcionalidades, lo que realmente buscan es sentirse más tranquilos, tener mayor control sobre su vehículo y reducir la incertidumbre en su día a día, mostrando también una buena disposición a adoptar y recomendar una herramienta que cumpla con estas expectativas.

## Segmento 2: Empresas

<div align="center">

| Nº Entrevista | Datos del entrevistado | Resumen de la entrevista | Evidencia de entrevista |
|--------------|------------------------|--------------------------|--------------------------|
| 1 | **Nombre:** Jesus Alvites <br> **Edad:** 25 <br> **Distrito:** <br>  **Link:** [link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221d382_upc_edu_pe/IQB1t_JXO08-ToO-FehysAJ_Afw6wmSxswLWOmdzimUAfKc?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=sQzaON) <br> Minutos: 12:54 - 18:30| El entrevistado, con experiencia como supervisor de tráfico, confirma que la inseguridad en rutas es frecuente, especialmente en zonas como el Callao o durante paradas donde ocurren robos de carga.<br>Destaca que el monitoreo en tiempo real mediante GPS es indispensable, aunque presenta limitaciones como pérdida de conexión y falta de integración de información.<br>Valora alertas de desvíos o detenciones, acceso a historiales y comunicación con conductores.<br>Busca una solución simple, accesible desde el celular y centralizada que mejore el control, la toma de decisiones y reduzca riesgos operativos. | <p align="center"><img src="https://github.com/user-attachments/assets/1730e97a-50ab-4394-8428-e1933c7a8fe1" width="600"></p> |
| 2 | **Nombre:** Matias Diaz <br> **Edad:** 25 <br> **Distrito:** San Juan de Lurigancho <br>  **Link:** [link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221d382_upc_edu_pe/IQB1t_JXO08-ToO-FehysAJ_Afw6wmSxswLWOmdzimUAfKc?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=sQzaON) <br> Minutos: 18:31 - 22:48| Matias Diaz, quien se desempeña como supervisor de seguridad en una empresa de distribución, destaca que su rol se centra en la prevención de riesgos y el cumplimiento de protocolos durante el traslado de vehículos y carga. Señala que la inseguridad en rutas de Lima Metropolitana es constante, especialmente en zonas de alto riesgo, donde ha presenciado robos y pérdidas operativas.<br>Utiliza herramientas como GPS, radios y reportes manuales, pero considera que estas no son suficientes, ya que requieren complementar información de varias fuentes. Por ello, enfatiza la necesidad de un sistema más completo que muestre la ubicación y el nivel de riesgo de las zonas.<br>Valora especialmente funciones como monitoreo en tiempo real, alertas por desvíos, paradas prolongadas, exceso de velocidad y acceso a historiales de rutas para identificar patrones de riesgo.<br>Busca una plataforma centralizada, rápida y confiable, que le permita reaccionar de inmediato ante emergencias, mejorar el control operativo y reducir tanto riesgos de seguridad como pérdidas económicas en la empresa. | <p align="center"><img src="https://github.com/user-attachments/assets/99b6cbe6-25da-44cd-b540-f0eca42d50c4" width="600"></p> |
| 3 | **Nombre:** Juan Velasquez <br> **Edad:** 25 <br> **Distrito:** <br>  **Link:** [link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221d382_upc_edu_pe/IQB1t_JXO08-ToO-FehysAJ_Afw6wmSxswLWOmdzimUAfKc?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=sQzaON) <br> Minutos: 22:49 - 27:48| Juan revela una necesidad crítica de seguridad y visibilidad operativa, ya que actualmente depende de métodos manuales e ineficientes como llamadas y WhatsApp para gestionar su flota en un entorno de alto riesgo por robos y desvíos. La implementación de un sistema de telemetría se percibe como una inversión estratégica para obtener paz mental mediante el monitoreo en tiempo real y alertas automáticas, buscando no solo proteger el patrimonio y la carga, sino también optimizar costos de combustible y tiempos de entrega a través de una plataforma centralizada y extremadamente sencilla de usar. El interés principal no radica en la tecnología por sí misma, sino en su capacidad de transformar la incertidumbre actual en un control total que garantice la rentabilidad y la profesionalización del servicio frente al cliente. | <p align="center"><img src="https://github.com/user-attachments/assets/d7cb4ad5-a771-4f21-880c-fc4bbc068698" width="600"></p> |


</div>

### Resumen de entrevistas segmento #2

A partir de las entrevistas, se puede ver que todos los participantes trabajan en entornos donde la inseguridad en rutas es un problema constante, especialmente por robos y desvíos que afectan directamente sus operaciones. Actualmente dependen de herramientas básicas como GPS, llamadas o WhatsApp, lo que hace que el seguimiento de los vehículos sea poco eficiente y muy manual, generando incertidumbre y dificultando la toma de decisiones rápidas. En general, coinciden en que necesitan tener mayor control y visibilidad en tiempo real, valorando mucho funciones como alertas automáticas ante situaciones sospechosas y el acceso a historiales de rutas para entender mejor lo que ocurre. También buscan una solución que sea simple, accesible desde el celular y que centralice toda la información en un solo lugar. Más allá de la tecnología, lo que realmente esperan es poder trabajar con mayor tranquilidad, reducir riesgos y mejorar la eficiencia de sus operaciones.

### 5.3.3. Evaluaciones según heurísticas
**UX Heuristics & Principles Evaluation**
*Usability – Inclusive Design – Information Architecture*

| Campo | Detalle |
|---|---|
| **CARRERA** | Ingeniería de Software |
| **CURSO** | Desarrollo de Aplicaciones Open Source – 1ASI0729 |
| **SECCIÓN** | NRC 11896 |
| **PROFESORES** | Bautista Ubillús, Efraín Ricardo; Flores Moroco, Juan Antonio; Mori Paiva, Hugo Allan; Robles Fernández, Iván; Velásquez Núñez, Ángel Augusto |
| **AUDITOR** | GuardiAnts – Equipo GOD's Tracker |
| **CLIENTE(S)** | Luis Lopez, Juana Quispe, Enrique Castillo, Jesus Alvites, Matias Diaz, Juan Velasquez |

---

**SITE o APP A EVALUAR:** GOD's Tracker – Landing Page y Web Application de GuardiAnts

---

**TAREAS A EVALUAR:**

El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:

1. Registro de un nuevo usuario (persona natural o empresa)
2. Inicio de sesión en la plataforma
3. Visualización de la ubicación del vehículo en el mapa de monitoreo en tiempo real
4. Recepción y consulta de alertas de seguridad
5. Configuración de geocercas y zonas de monitoreo
6. Revisión del historial de rutas
7. Configuración del perfil y datos del vehículo
8. Navegación general del Landing Page
9. Selección de un plan de suscripción desde el Landing Page

No están incluidas en esta versión de la evaluación las siguientes tareas:

1. Integración con sistemas de bloqueo remoto del motor
2. Gestión de múltiples conductores por vehículo
3. Exportación de reportes en PDF para gerencia
4. Módulo de administración de usuarios (back-office)

---

**ESCALA DE SEVERIDAD:**

| Nivel | Descripción |
|:---:|---|
| 1 | Problema superficial: puede ser fácilmente superado por el usuario u ocurre con muy poca frecuencia. No necesita ser corregido a menos que exista disponibilidad de tiempo. |
| 2 | Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar. Se le debe asignar prioridad baja para el siguiente release. |
| 3 | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlo. Es importante corregirlo y se le debe asignar prioridad alta. |
| 4 | Problema muy grave: impide al usuario continuar usando la herramienta. Es imperativo corregirlo antes del lanzamiento. |

---

**TABLA RESUMEN:**

| # | Problema | Escala de Severidad | Heurística / Principio violado |
|:---:|---|:---:|---|
| 1 | El menú hamburguesa en la versión móvil del Landing Page no es fácilmente identificable por usuarios con menor familiaridad digital. | 2 | Usability: Consistencia y estándares |
| 2 | No existe un tutorial de inicio o guía interactiva para nuevos usuarios al ingresar por primera vez a la Web Application. | 3 | Usability: Ayuda y documentación |
| 3 | Las alertas de seguridad en pantallas pequeñas tienen iconos demasiado pequeños, dificultando su lectura rápida. | 2 | Usability: Flexibilidad y eficiencia de uso |
| 4 | El botón de call-to-action en la sección Hero del Landing Page no contrasta suficientemente con el fondo en modo claro. | 2 | Usability: Visibilidad del estado del sistema |
| 5 | Las geocercas configuradas por el usuario no se muestran visualmente sobre el mapa del dashboard de monitoreo. | 3 | Usability: Control y libertad del usuario |
| 6 | No existe un filtro de alertas por vehículo o conductor específico; el usuario debe revisar manualmente la lista completa. | 3 | Usability: Control y libertad del usuario |
| 7 | Algunas imágenes del Landing Page no cuentan con atributo `alt` descriptivo para lectores de pantalla. | 3 | Inclusive Design: Proporciona experiencias comparables |
| 8 | La sección de características en la versión móvil presenta bloques de texto extensos sin jerarquía visual clara. | 2 | Information Architecture: Is it usable? |
| 9 | No se indica el período de prueba gratuita en la sección de pricing, generando incertidumbre en usuarios que no quieren comprometerse sin probar el servicio. | 2 | Information Architecture: Is it findable? |
| 10 | El proceso de configuración del primer vehículo no tiene indicación de cuántos pasos quedan (ausencia de stepper o barra de progreso). | 3 | Usability: Visibilidad del estado del sistema |

---

**DESCRIPCIÓN DE PROBLEMAS:**

---

**PROBLEMA #1:** El menú hamburguesa en mobile no es fácilmente identificable

**Severidad:** 2

**Heurística violada:** Usability – Consistencia y estándares

**Problema:** Durante la sesión de validación, Juana Quispe (47 años, segmento persona natural) tuvo dificultades para identificar el menú de navegación en su dispositivo móvil. El ícono utilizado no fue reconocido de inmediato como menú de navegación, lo que generó fricción en los primeros segundos de interacción con el Landing Page.

**Recomendación:** Usar el ícono estándar de tres líneas horizontales (≡) ampliamente reconocido, y añadir una etiqueta de texto "Menú" debajo del ícono para usuarios con menor experiencia digital. Adicionalmente, considerar que el menú se mantenga fijo (sticky) durante el scroll para mejorar la accesibilidad permanente a la navegación.

---

**PROBLEMA #2:** Ausencia de tutorial de inicio o guía interactiva para nuevos usuarios

**Severidad:** 3

**Heurística violada:** Usability – Ayuda y documentación

**Problema:** Enrique Castillo y Jesus Alvites coincidieron en que al ingresar por primera vez a la Web Application no existía ningún elemento que los orientara sobre cómo comenzar a usar el sistema: cómo agregar un vehículo, cómo configurar alertas o cómo interpretar el mapa de monitoreo. Esto generó exploración no guiada e incrementó el tiempo para completar tareas básicas.

**Recomendación:** Implementar un flujo de onboarding con pasos guiados (stepper interactivo o tooltips de bienvenida) que oriente al usuario nuevo en las primeras acciones clave: agregar vehículo → configurar geocerca → activar alertas. Este flujo debe poder omitirse para usuarios que ya conocen la plataforma.

---

**PROBLEMA #3:** Iconos de alertas demasiado pequeños en pantallas móviles

**Severidad:** 2

**Heurística violada:** Usability – Flexibilidad y eficiencia de uso

**Problema:** Juana Quispe indicó que en su celular los iconos de clasificación de alertas (movimiento sospechoso, jammer detectado, geocerca) son difíciles de distinguir a primera vista. La falta de tamaño adecuado reduce la velocidad de lectura en situaciones de emergencia, que son precisamente los momentos en que el usuario más necesita responder rápido.

**Recomendación:** Aumentar el tamaño de los iconos de alertas en la vista móvil a un mínimo de 24x24px con etiqueta de texto descriptiva visible. Aplicar diferenciación por color además del ícono para reforzar la clasificación por tipo y severidad.

---

**PROBLEMA #5:** Las geocercas no se muestran visualmente sobre el mapa del dashboard

**Severidad:** 3

**Heurística violada:** Usability – Control y libertad del usuario

**Problema:** Matias Diaz, supervisor de seguridad, señaló que configuró una geocerca en la sección de ajustes pero no pudo verla superpuesta sobre el mapa de monitoreo del dashboard. Esto genera incertidumbre sobre si la configuración fue guardada correctamente y limita el control visual del usuario sobre las zonas definidas.

**Recomendación:** Mostrar las geocercas configuradas como polígonos o círculos superpuestos directamente sobre el mapa del dashboard de monitoreo, con opción de editar o eliminar desde el propio mapa. Añadir un indicador visual que confirme que la geocerca está activa.

---

**PROBLEMA #7:** Imágenes sin texto alternativo en el Landing Page

**Severidad:** 3

**Heurística violada:** Inclusive Design – Proporciona experiencias comparables

**Problema:** Varias imágenes del Landing Page, incluyendo íconos de características y la imagen del producto en la sección Hero, no cuentan con atributos `alt` descriptivos. Esto impide que usuarios que dependen de lectores de pantalla accedan al contenido de forma equivalente, vulnerando los principios de diseño inclusivo y los estándares de accesibilidad WCAG 2.1.

**Recomendación:** Revisar todas las imágenes del Landing Page y la Web Application para agregar atributos `alt` con descripciones significativas. Las imágenes decorativas deben incluir `alt=""` para que los lectores de pantalla las ignoren. Incorporar esta práctica como parte del checklist de revisión de código en cada sprint.

---

**PROBLEMA #10:** Ausencia de barra de progreso en la configuración del primer vehículo

**Severidad:** 3

**Heurística violada:** Usability – Visibilidad del estado del sistema

**Problema:** Juan Velasquez, al intentar configurar su primer vehículo en la plataforma, no encontró ningún indicador de cuántos pasos restaban para completar el proceso. La ausencia de un stepper o barra de progreso generó incertidumbre sobre si el proceso era corto o extenso, afectando la decisión de continuarlo.

**Recomendación:** Implementar un componente stepper visible (ej. "Paso 2 de 3: Datos del vehículo") en el flujo de configuración inicial. El stepper debe mostrar claramente los pasos completados, el actual y los pendientes, reduciendo la incertidumbre y aumentando la tasa de finalización del onboarding.

## 5.4. Video About-the-Product

# Conclusiones 

-  *Conclusiones preliminares*
    - Eficiencia en la Gestión de Versiones: La implementación del modelo GitFlow y el uso de la organización en GitHub han permitido una colaboración estructurada y sin conflictos críticos entre los miembros del equipo. La adopción de Conventional Commits ha sido fundamental para mantener un historial de cambios legible, lo que facilita la trazabilidad de cada funcionalidad desarrollada en la Landing Page y la documentación del Reporte.

    - Solidez Arquitectónica: El desarrollo de los diagramas C4 (Contexto, Contenedor y Componentes) y el diseño de la base de datos han proporcionado una hoja de ruta clara para el desarrollo técnico. Esta planificación previa asegura que la plataforma GuardiAnts sea escalable y que cada integrante comprenda la interacción entre el Frontend (Web App) y el Backend (Platform) antes de iniciar la codificación pesada.

    - Presencia Digital y Accesibilidad: El despliegue de la Landing Page no solo cumple con los requisitos de diseño responsivo, sino que, mediante la integración de la internacionalización (i18n), garantiza que la propuesta de valor de GuardiAnts sea accesible para una audiencia global. El uso de tecnologías estándar (HTML/CSS/JS) bajo una arquitectura limpia asegura un mantenimiento simplificado a largo plazo.

    - Validación del Enfoque en el Usuario: El proceso de entrevistas y el mapeo de User Personas realizados en los primeros capítulos han validado la necesidad del mercado por una solución de monitoreo y seguridad. Estas conclusiones iniciales han permitido refinar el Product Backlog, asegurando que los siguientes Sprints se enfoquen en funcionalidades que realmente resuelvan los puntos de dolor identificados en los segmentos de objetivo.

    - Compromiso con la Calidad Documental: La consolidación de un reporte técnico detallado, que incluye desde el Lean UX Canvas hasta especificaciones de diseño UI/UX, establece un estándar de calidad alto para el proyecto. Esto garantiza que cualquier stakeholder o futuro desarrollador pueda comprender la lógica de negocio y las decisiones técnicas detrás de GuardiAnts.
# Bibliografía


*   **Conventional Commits.** (s.f.). *A specification for adding human and machine readable meaning to commit messages*. Recuperado de [https://www.conventionalcommits.org/en/v1.0.0/](https://www.conventionalcommits.org/en/v1.0.0/)
*   **Driessen, V. (2010).** *A successful Git branching model*. nvie.com. Recuperado de [https://nvie.com/posts/a-successful-git-branching-model/](https://nvie.com/posts/a-successful-git-branching-model/)
*   **Preston-Werner, T. (s.f.).** *Semantic Versioning 2.0.0*. Recuperado de [https://semver.org/](https://semver.org/)
*   **Schwaber, K., & Sutherland, J. (2020).** *The Scrum Guide: The Definitive Guide to Scrum: The Rules of the Game*. Scrum.org. Recuperado de [https://scrumguides.org/scrum-guide.html](https://scrumguides.org/scrum-guide.html)



*   **Gibbons, J. (2018).** *UX Mapping Methods: Study Guide*. Nielsen Norman Group. Recuperado de [https://www.nngroup.com/articles/ux-mapping-methods-study-guide/](https://www.nngroup.com/articles/ux-mapping-methods-study-guide/)
*   **Gothelf, J., & Seiden, J. (2016).** *Lean UX: Designing Great Products with Agile Teams*. O'Reilly Media.
*   **Norman, D. (2013).** *The Design of Everyday Things*. Basic Books.

*   **Brown, S. (2018).** *The C4 model for visualizing software architecture*. Leanpub. Recuperado de [https://c4model.com/](https://c4model.com/)
*   **Fowler, M. (2003).** *Patterns of Enterprise Application Architecture*. Addison-Wesley Professional.
*   **Object Management Group (OMG).** (2017). *Unified Modeling Language (UML) Specification*. Recuperado de [https://www.omg.org/spec/UML/](https://www.omg.org/spec/UML/)

*   **GitHub Docs.** (2024). *GitHub Pages Documentation*. Recuperado de [https://docs.github.com/en/pages](https://docs.github.com/en/pages)
*   **Google Developers.** (s.f.). *Web Fundamentals: Responsive Web Design*. Recuperado de [https://developers.google.com/web/fundamentals/design-and-ux/responsive](https://developers.google.com/web/fundamentals/design-and-ux/responsive)
*   **Mozilla Contributors.** (2024). *MDN Web Docs: HTML, CSS and JavaScript guides*. Recuperado de [https://developer.mozilla.org/](https://developer.mozilla.org/)

# Anexos
[https://www.figma.com/design/BcC9KfySVs24zbhSwAFPmY/wireframe?node-id=0-1&t=hWPZs22fqyjzSmab-1](https://www.figma.com/design/BcC9KfySVs24zbhSwAFPmY/wireframe?node-id=0-1&t=hWPZs22fqyjzSmab-1)
