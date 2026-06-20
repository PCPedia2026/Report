<div align="center">

<br>

<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="UPC Logo" width="140"/>

# Universidad Peruana de Ciencias Aplicadas
### Facultad de Ingeniería · Ciclo 2026-10

<br>

# Informe de Proyecto - TB1

## Startup: EcatLeasing

## Producto: PCPedia

<br>

**Código del Curso:** 1ASI0732 &nbsp;|&nbsp; **Nombre del Curso:** Diseño de Experimentos de Ingeniería de Software

**NRC:** `16880`

**Profesor:** Julio Manuel Noriega Melendez

<br>

### Integrantes

`U20231D390` - `Bendezu Navarro Rúbens`

`U20231c996` - `Hernandez Poma Sebastian Eduardo`

`U20191B935` - `Carranza Tesén Joaquín Enrique`

`U202311469` - `Arroyo Gonzales, Emily Juliette`

### **2026**

</div>

---

<div align="center">

## Registro de Versiones del Informe

| Versión |   Fecha    |                                                                                Participantes                                                                                 | Descripción de modificación |
|:-------:|:----------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------|
| AV1 | 2026-05-02 | Bendezu Navarro, Rúbens <br> Hernandez Poma, Sebastian Eduardo <br> Carranza Tesén, Joaquín Enrique <br> Arroyo Gonzales, Emily Juliette  | || |            |                                                                                                                                                                              | |
| TB2 | 2026-06-20 | Bendezu Navarro, Rúbens | Incorporación del plan y diseño experimental de PcPedia: materia prima, preguntas experimentales, backlog priorizado, Experiment Cards e hipótesis. |

</div>

---

## Project Report Collaboration Insights

**URL del Repositorio:** [`https://github.com/PCPedia2026/Report`](https://github.com/PCPedia2026/Report)

*(Esta sección se irá expandiendo con cada entrega)*

---

## Tabla de Contenidos
#### [Contenido](#-tabla-de-contenidos)
#### [Student Outcome](#-student-outcome)

#### [Capítulo I: Introducción](#capítulo-i-introducción-1)
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
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

#### [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis-1)
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
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](#24-ubiquitous-language)

#### [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification-1)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Product Backlog](#33-product-backlog)
- [3.4. Impact Mapping](#34-impact-mapping)

#### [Capítulo IV: Product Design](#capítulo-iv-product-design-1)
- [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
    - [4.1.3. Mobile Style Guidelines](#413-mobile-style-guidelines)
      - [4.1.3.1. iOS Mobile Style Guidelines](#4131-ios-mobile-style-guidelines)
      - [4.1.3.2. Android Mobile Style Guidelines](#4132-android-mobile-style-guidelines)
- [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
- [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4. Mobile Applications UX/UI Design](#44-mobile-applications-uxui-design)
    - [4.4.1. Mobile Applications Wireframes](#441-mobile-applications-wireframes)
    - [4.4.2. Mobile Applications Wireflow Diagrams](#442-mobile-applications-wireflow-diagrams)
    - [4.4.3. Mobile Applications Mock-ups](#443-mobile-applications-mock-ups)
    - [4.4.4. Mobile Applications User Flow Diagrams](#444-mobile-applications-user-flow-diagrams)
- [4.5. Mobile Applications Prototyping](#45-mobile-applications-prototyping)
    - [4.5.1. Android Mobile Applications Prototyping](#451-android-mobile-applications-prototyping)
    - [4.5.2. iOS Mobile Applications Prototyping](#452-ios-mobile-applications-prototyping)
- [4.6. Web Applications UX/UI Design.](#46-web-applications-uxui-design)
    - [4.6.1. Web Applications Wireframes](#461-web-applications-wireframes)
    - [4.6.2. Web Applications Wireflow Diagrams](#461-web-applications-wireflow-diagrams)
    - [4.6.3. Web Applications Mock-ups](#463-web-applications-mockups)
    - [4.6.4. Web Applications User Flow Diagrams](#464-web-applications-user-flow-diagrams)
- [4.7. Web Applications Prototyping](#47-web-applications-prototyping)
- [4.8. Domain-Driven Software Architecture](#48-domain-driven-software-architecture)
    - [4.8.1. Software Architecture Context Diagram](#481-software-architecture-context-diagram)
    - [4.8.2. Software Architecture Container Diagrams](#482-software-architecture-container-diagrams)
    - [4.8.3. Software Architecture Components Diagrams](#483-software-architecture-components-diagrams)
- [4.9. Software Object-Oriented Design](#49-software-object-oriented-design)
    - [4.9.1. Class Diagrams](#491-class-diagrams)
    - [4.9.2. Class Dictionary](#492-class-dictionary)
- [4.10. Database Design](#410-database-design)
    - [4.10.1. Relational/Non-Relational Database Diagram](#4101-relationalnonrelational-database-diagram)
#### [Capítulo V: Product Implementation](#capítulo-v-product-implementation)
- [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Product Implementation & Deployment ](#52-product-implementation-deployment)
    - [5.2.1. Sprint Backlogs](#521-sprint-backlogs)
    - [5.2.2. Implemented Landing Page Evidence](#522-implemented-landingpage-evidence)
    - [5.2.3. Implemented Frontend-Web Application Evidence](#523-implemented-frontendweb-application-evidence)
    - [5.2.4. Acuerdo de Servicio - SaaS](#524-acuerdo-de-servicio-saas)
    - [5.2.5. Implemented Native-Mobile Application Evidence](#525-implemented-nativemobile-application-evidence)
    - [5.2.6. Implemented RESTful API and/or Serverless Backend Evidence](#526-implemented-restfulapi-andor-serverless-backend-evidence)
    - [5.2.7. RESTful API documentation](#527-restfulapi-documentation)
    - [5.2.8. Team Collaboration Insights](#528-team-collaboration-insights)
- [5.3. Video About-the-Product](#53-video-about-the-product)
#### [Capítulo VI: Product Verification & Validation](#capítulo-vi-product-verification--validation)
- [6.1. Testing Suites & Validation](#61-testing-suites--validation)
    - [6.1.1. Core Entities Unit Tests](#611-core-entities-unit-tests)
    - [6.1.2. Core Integration Tests](#612-core-integration-tests)
    - [6.1.3. Core Behavior-Driven Development](#613-core-behavior-driven-development)
    - [6.1.4. Core System Tests](#614-core-system-tests)
- [6.2. Static testing & Verification](#62-static-testing--verification)
    - [6.2.1. Static Code Analysis](#621-static-code-analysis)
        - [6.2.1.1. Coding standard & Code conventions](#6211-coding-standard--code-conventions)
        - [6.2.1.2. Code Quality & Code Security](#6212-code-quality--code-security)
    - [6.2.2. Reviews](#622-reviews)
#### [Capítulo VII: DevOps Practices](#capítulo-vii-devops-practices)
- [7.1. Continuous Integration](#71-continuous-integration)
  - [7.1.1. Tools and Practices.](#711-tools-and-practices)
  - [7.1.2. Build & Test Suite Pipeline Components.](#712-build--test-suite-pipeline-components)
- [7.2. Continuous Delivery](#72-continuous-delivery)
  - [7.2.1. Tools and Practices.](#721-tools-and-practices)
  - [7.2.2. Stages Deployment Pipeline Components.](#722-stages-deployment-pipeline-components)
- [7.3. Continuous Deployment](#73-continuous-deployment)
  - [7.3.1. Tools and Practices.](#731-tools-and-practices)
  - [7.3.2. Production Deployment Pipeline Components.](#732-production-deployment-pipeline-components)
- [7.4. Continuous Monitoring](#73-continuous-monitoring)
  - [7.4.1 ToolS and Practices.](#741-tools-and-practices)
  - [7.4.2. Monitoring Pipeline Components.](#742-monitoring-pipeline-components)
  - [7.4.3. Alerting Pipeline Components.](#743-alerting-pipeline-components)
  - [7.4.4. Notification Pipeline Components.](#744-notification-pipeline-components)
- [8.1. Experiment Planning](#81-experiment-planning)
  - [8.1.1 As-Is Summary.](#811-as-is-summary)
  - [8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims.](#812-raw-material-assumptions-knowledge-gaps-ideas-claims)
  - [8.1.3. Experiment-Ready Questions.](#813-experiment-ready-questions)
  - [8.1.4. Question Backlog.](#814-question-backlog)
  - [8.1.5. Experiment Cards.](#815-experiment-cards)
- [8.1. Experiment Planning](#81-experiment-planning)
  - [8.2 . Experiment Design](#82-experiment-design)
  - [8.2.1. Hypotheses](#821-hypotheses)
  - [8.2.2. Domain Business Metrics](#822-domain-business-metrics)
  - [8.2.3. Measures](#823-measures)
  - [8.2.4. Conditions](#824-conditions)
  - [8.2.5. Scale Calculations and Decisions.](#825-scale-calculations-and-decisions)
  - [8.2.6 Methods Selection.](#826-methods-selection)
  - [8.2.7. Data Analytics: Goals, KPIs and Metrics Selection.](#827-data-analytics-goals-kpi-and-metrics)
  - [8.2.8. Web and Mobile Tracking Plan](#828-web-and-mobile-tracking-plan)
- [8.3. Experimentation](#83-experiment-planning)
  - [8.3.1. To-Be User Stories.](#831-to-be-user-stories)
  - [8.3.2. To-Be Product Backlog](#832-to-be-product-backlog)


#### [Capítulo VIII: Experiment-Driven Development](#capítulo-viii-experiment-driven-development)
- [8.1. Experiment Planning](#81-experiment-planning)
  - [8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims](#812-raw-material-assumptions-knowledge-gaps-ideas-claims)
  - [8.1.3. Experiment-Ready Questions](#813-experiment-ready-questions)
  - [8.1.4. Question Backlog](#814-question-backlog)
  - [8.1.5. Experiment Cards](#815-experiment-cards)
- [8.2. Experiment Design](#82-experiment-design)
  - [8.2.1. Hypotheses](#821-hypotheses)

#### [Conclusiones](#conclusiones-1)

#### [Recomendaciones](#recomendaciones-1)

#### [Video App Validation](#video-app-validation)

#### [Video About-the-Team](#video-about-the-team-1)

#### [Bibliografía](#-bibliografía)

#### [Anexos](#anexos-1)

---

## Student Outcome

En Ingeniería de Software, el logro contribuye a alcanzar el:

ABET – EAC - Student Outcome 4: La capacidad de reconocer responsabilidades éticas y profesionales en situaciones de ingeniería y hacer juicios informados, que deben considerar el impacto de las soluciones de ingeniería en contextos globales, económicos, ambientales y sociales.

En el siguiente cuadro se describen las acciones realizadas y enunciados de conclusiones por parte del
grupo, que permiten sustentar el haber alcanzado el logro del ABET - EAC - Student Outcome 4.

| Criterio específico | Acciones realizadas                                                                                                                                                                                                  | Conclusiones |
|:---|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------|
| **Identifica y evalúa las implicancias éticas y profesionales en el desarrollo de soluciones de ingeniería.** | **Bendezu Navarro Rúbens** <br> **AV1:** <br><br> **TB2:** Diseñé el proceso experimental de PcPedia partiendo de supuestos, vacíos de conocimiento, ideas y afirmaciones que debían validarse antes de orientar nuevas decisiones del producto. Prioricé preguntas según su riesgo, impacto, interés y nivel de confianza, y definí Experiment Cards con criterios de éxito establecidos antes de recolectar datos. Asimismo, consideré el consentimiento informado, la minimización y anonimización de datos y la comunicación transparente de resultados favorables, desfavorables o inconclusos, evitando manipular evidencia para justificar decisiones previamente tomadas. <br><br> **Hernandez Poma Sebastian Eduardo** <br> **AV1:**  <br><br> **Carranza Tesén Joaquín Enrique** <br> **AV1:** Identifique que el desarrollo tecnológico conlleva una profunda responsabilidad ética y profesional vinculada directamente a la implementación, gestión de código y configuración del despliegue realizados. Al realizar la evaluación en el plano ético, determiné que el despliegue de las aplicaciones (Web, Móvil y API) bajo el Acuerdo de Servicio (SaaS) exige proteger la privacidad del usuario desde el backend y asegurar la transparencia de las funciones entregadas. Asimismo, al realizar el análisis en el ámbito profesional, se evidencia el compromiso de cumplir estrictamente con las guías de estilo, control de versiones y el flujo de los Sprint Backlogs, demostrando que la rigurosidad técnica y la colaboración del equipo son estándares críticos para mitigar errores en producción, garantizando un software mantenible, seguro y de alta calidad.  <br><br> **TP:** Identifique que el desarrollo de soluciones de ingeniería tecnológica conlleva una profunda responsabilidad ética y profesional que se vincula directamente con los procesos de diseño, validación y análisis heurístico realizados. Al realizar la evaluación en el plano ético, determiné que es imperativo garantizar la transparencia algorítmica en las herramientas de recomendación automatizadas (asegurando que respondan a la optimización real de costos del usuario y no a sesgos comerciales) y proteger con estricta confidencialidad los datos de infraestructura y presupuestos recopilados. Asimismo, al realizar el análisis en el ámbito profesional, se evidencia el compromiso de asegurar la continuidad operativa de los usuarios a través de flujos de despliegue y monitoreo robustos, entendiendo que corregir las fallas de usabilidad detectadas en las entrevistas y optimizar las interfaces (tanto web como móvil) no es un asunto estético, sino un estándar técnico crítico para mitigar riesgos, prevenir errores operativos y garantizar una gestión de recursos eficiente y segura. <br><br> **Arroyo Gonzales, Emily** <br> **AV1:** <br> | **AV1:** <br><br> **TB2:** El trabajo de Rúbens evidencia responsabilidad ética y profesional al convertir incertidumbres del producto en experimentos trazables, medibles y respetuosos de la privacidad. Definir previamente las métricas y condiciones reduce sesgos de confirmación y permite que las decisiones sobre PcPedia se fundamenten en evidencia verificable. |
| **Analiza el impacto de las soluciones de ingeniería en contextos sociales, económicos y ambientales para tomar decisiones informadas.** | **Bendezu Navarro Rúbens** <br> **AV1:** <br><br> **TB2:** Analicé mediante hipótesis falsables cómo la recomendación guiada de equipos, la comparación transparente de planes y el seguimiento de incidencias pueden afectar la experiencia de los usuarios. En el ámbito social, los experimentos evalúan si la solución reduce barreras para personas con distinto conocimiento técnico; en el económico, si disminuye el tiempo y la incertidumbre al seleccionar tecnología; y en el ambiental, si favorece elecciones ajustadas a la necesidad real y prolonga el ciclo de vida de los equipos, evitando adquisiciones innecesarias. <br><br> **Hernandez Poma Sebastian Eduardo** <br> **AV1:**  <br><br> **Carranza Tesén Joaquín Enrique** <br> **AV1:** Analice que el despliegue del producto —evidenciado en la Landing Page, las aplicaciones Web/Móvil y la API RESTful— genera un impacto multidimensional clave para la toma de decisiones informadas. Al realizar la evaluación en el contexto social, determiné que el uso de interfaces consistentes y guías de estilo estandarizadas reduce la brecha digital y democratiza el acceso técnico, mejorando la experiencia del usuario final en su entorno. En el plano económico, el análisis demuestra que una arquitectura modular y una correcta configuración de despliegue bajo el modelo SaaS reducen los costos de mantenimiento, optimizan el consumo de infraestructura en la nube y minimizan pérdidas financieras por fallas del sistema. Finalmente, al evaluar el impacto ambiental, se evidencia que la optimización del código fuente disminuye la carga de procesamiento en los servidores, reduciendo el consumo energético y la huella de carbono digital para lograr una solución sostenible. <br><br> **TP:** Analice que el desarrollo de soluciones de ingeniería tecnológica genera un impacto multidimensional que debe ser evaluado rigurosamente a partir del análisis heurístico y las validaciones con usuarios reales que hemos realizado. Al realizar la evaluación en el contexto social, determiné que optimizar la interfaz y corregir las fallas de usabilidad mitiga la frustración del usuario, reduce la brecha digital y democratiza el acceso eficiente a herramientas técnicas, promoviendo entornos laborales y educativos más productivos e inclusivos. En el plano económico, el análisis de los flujos operativos demuestra que una solución intuitiva minimiza los costos por errores de usuario, reduce los tiempos muertos de soporte técnico y optimiza la asignación de presupuestos mediante recomendaciones automatizadas y transparentes, garantizando un retorno de inversión sostenible. Finalmente, al evaluar el impacto ambiental, se evidencia que el monitoreo continuo de recursos y el correcto control del ciclo de vida de la infraestructura tecnológica contribuyen directamente a la reducción de la huella de carbono y previenen la obsolescencia acelerada, permitiendo tomar decisiones de ingeniería informadas que equilibran la eficiencia técnica con la responsabilidad social y la sostenibilidad del entorno.  <br><br> **Arroyo Gonzales, Emily** <br>**AV1:** <br>  | **AV1:** <br><br> **TB2:** El aporte permite tomar decisiones informadas sobre PcPedia al vincular cada propuesta de mejora con indicadores observables. La experimentación planteada ayuda a equilibrar accesibilidad, eficiencia económica y consumo tecnológico responsable antes de invertir en cambios de mayor alcance. |

---

<div align="center">

# Capítulo I: Introducción

</div>

---

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

ECAT Leasing es una startup dedicada a transformar la manera en que las organizaciones acceden y gestionan su tecnología. Nuestro producto principal, Smart Leasing, ofrece un modelo de arrendamiento inteligente que garantiza a empresas y al sector educativo contar siempre con equipos actualizados, evitando la carga de la obsolescencia tecnológica. A través de planes flexibles, brindamos no solo el acceso a hardware moderno, sino también un ecosistema de servicios de valor agregado que incluye soporte técnico especializado, mantenimiento preventivo y correctivo, gestión de garantías y atención ágil a incidencias.

Además, comprendemos que cada empresa tiene necesidades y presupuestos distintos. Por ello, incorporamos dentro de Smart Leasing el servicio que evalúa los recursos, procesos y objetivos de cada cliente para recomendar los equipos más eficientes y rentables, asegurando que inviertan solo en lo que realmente necesitan. De esta manera, ECAT Leasing se convierte en un socio estratégico que simplifica la gestión de TI, optimiza los costos y permite que nuestros clientes se concentren en lo más importante: el crecimiento de su negocio.

**Misión:** Facilitar la vida de las empresas haciéndonos cargo de sus activos de TI, brindando equipos siempre actualizados con nuestro servicio de Smart Leasing, junto con soporte, mantenimiento y gestión de garantías, para que nuestros clientes se concentren en crecer sin preocuparse por la tecnología.

**Visión:** Ser la empresa referente en Latinoamérica en servicios de arrendamiento tecnológico inteligente, simplificando la gestión de activos TI y ayudando a las organizaciones a enfocarse en su crecimiento, mientras nosotros garantizamos que su tecnología esté siempre actualizada, optimizada y respaldada.

---

###   1.1.2. Perfiles de integrantes del equipo

|                                      Miembro                                       |                                                                                                                                                                                                                                                                                                 Descripción                                                                                                                                                                                                                                                                                                  |
|:----------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|   <img src="docs/assets/img/chapter1/Perfil_Bendezu_Rubens.jpeg" width ="3000"/>   |                                                   **Bendezu Navarro Rúbens \- U20231D390** <br> Mi nombre es Rúbens Bendezu, soy estudiante de Ingeniería de Software. Me considero una persona motivada por el aprendizaje continuo y el trabajo en equipo, ya que compartir ideas y experiencias enriquece tanto el desarrollo personal como el profesional. Tengo conocimientos en tecnologías de desarrollo web y frameworks modernos, y me interesa especialmente el desarrollo de aplicaciones web que aporten soluciones innovadoras y de impacto.                                                    |
| <img src="docs/assets/img/chapter1/Perfil_Hernandez_Sebastian.png" width ="3000"/> | **Hernández Poma, Sebastián Eduardo \- U20231c996** <br> Tengo 21 años y estoy cursando la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Mi objetivo es seguir desarrollando mis competencias en programación y especializarme en el área de desarrollo de software y soluciones tecnológicas innovadoras. Me caracterizo por ser una persona perseverante, con mentalidad de crecimiento y compromiso con el trabajo en equipo, buscando siempre aprender nuevas herramientas que fortalezcan mi futuro profesional y me permitan alcanzar proyectos de mayor impacto. |
|  <img src="docs/assets/img/chapter1/Perfil_Carranza_Joaquin.jpg" width ="3000"/>   |                               **Carranza Tesén Joaquín Enrique \- U20191B935**  <br> Hola, soy Joaquín Carranza. Tengo 25 años y actualmente curso el septimo ciclo de la carrera de Ingeniería de Software. Me gusta la tecnología y la forma en que ayuda a las personas a resolver problemas de manera más rápida y eficiente. Me interesa especialmente el manejo de datos y la ciberseguridad. Siento que puedo aportar a mi equipo ideas desde otra perspectiva, ya que siempre me cuestiono cómo se podría mejorar el producto o hacia qué objetivo estamos apuntando.                                | 
|    <img src="docs/assets/img/chapter1/Perfil_Arroyo_Emily.png" width ="3000"/>     |                                                                                                                                                                                                                                                                           **Arroyo Gonzales Emily Juliette \- U202311469**  <br> Soy estudiante de la carrera de Ingeniería de Software, tengo 20 años, tengo experiencia en lenguajes como C++, MongoDB, en trabajos grupales me gusta aportar ideas que contribuyan a mi grupo y avanzar según lo asignado.                                                                                                                                                                                                                                                                            | 

---

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

Para realizar los antecedentes y problemáticas, se realizó con anticipación la técnica 5 ‘W’s & 2 ‘H’s:

**What:** El problema de la rápida obsolescencia tecnológica que enfrentan empresas y organizaciones, obligadas a invertir constantemente en nuevos equipos y a gestionar activos de TI de manera compleja y costosa.

**When:** Actualmente, en un contexto donde los ciclos de actualización tecnológica se reducen a 1–2 años y las aplicaciones requieren hardware cada vez más potente.

**Where:** En empresas de distintos tamaños (pequeñas, medianas y grandes) y en instituciones educativas, especialmente en el Perú y con proyección a Latinoamérica.

**Who:** Los principales afectados son las organizaciones que no cuentan con presupuestos flexibles ni con áreas de TI especializadas para gestionar correctamente la elección, uso y renovación de sus equipos.

**Why:** Porque la constante necesidad de actualización genera altos costos, dificulta la gestión de activos y provoca que muchas empresas gasten de más en equipos que no aprovechan, o compren dispositivos insuficientes para sus necesidades reales.

**How:** Las empresas suelen comprar equipos sin una evaluación estratégica, gestionando por sí mismas la garantía, el mantenimiento y la reposición, lo que aumenta el tiempo y los recursos dedicados a la administración de TI.

**How much:** El impacto se traduce en gastos significativos de capital (CapEx), sobrecostos en soporte y mantenimiento, pérdida de productividad y baja eficiencia en el aprovechamiento de la inversión tecnológica.

---

### 1.2.2. Lean UX Process

A continuacion se presentara la solucion al Lean UX que usaremos para poder desarrollar adecuadamente nuestro proyecto y ademas poder definir nuestro mercado objetivo.

---

### 1.2.2.1 Lean UX Problem Statements

**Problem Statement 1:**

Actualmente las empresas en el Peru y latinoamerica estan enfrentando una alta obsolescencia tecnologica, esto esta obligando a invertir rapidamente en actualizaciones, cambios y compras de nuevos equipos costosos y de mayor gama. Estas situaciones generan gastos altos de capital, reduce la productividad comprometiendo la competitividad, ya que muchas organizaciones adquieren dispositivos baratos sin cubrir verdaderamente sus necesidades actuales y a futuro, sin poder tener una escalabilidad correcta.

**Problem Statement 2:**

Una gran mayoria de organizaciones no ven necesario contar con un area TI especializada y de un modelo estrategico para poder administrar sus equipos. Esto genera a comprar equipos sin realmente cubrir sus necesidades, dificultades en la gestion de garantias y mantenimientos, asi como sobrecostos ocultos en soporte y reposicion de equipos, lo que distra a las empresas de su objetivo principal: crecer.

---

#### 1.2.2.2. Lean UX Assumptions

**Business Outcomes:**

- **Creemos que mis usuarios necesitan** gestionar correctamente sus activos de TI, contando con equipos actualizados sin hacer grandes inversiones iniciales y optimizar sus presupuestos de tecnolgia.


- **Estas necesidades se pueden resolver** ofreciendo un modelo de servicio Smart Leasing la cual incluye arrendamiento tecnologico inteligente, soportem mantenimiento y gestion de garantias en un solo servicio.


- **Nuestros clientes iniciales son** pequeñas y medianas empresas en Peru, las cuales carecen de n area de TI robusta, ademas de instituciones educativas que requieren actualizar equipos constantemente.


- **El valor #1 que un cliente requiere de nuestro servicio** es reducir cosotos de inversion en tecnologia logrando garantizar que sus equipos esten constantemente actualizados.


- **El cliente también puede obtener estos beneficios adicionales** como ahorro en tiempo y recursos de gestion de TI, soporte especializado, mantemiento preventivo y correctivo, optimizacion de productividad y flexibilidad para escalar su infraestructura tecnologica.


- **Adquiriremos a nuestros clientes a través del** marketing digital (LinkedIn, Google Ads, redes sociales), alianzas con proveedores de software y hardware, networking en eventos empresariales y referencias de clientes actuales.


- **Haremos dinero a través de** contratos de arrendamiento mensual de equipos (modelo SaaS/Leasing), servicios adicionales de soporte premium y acuerdos de mantenimiento extendido.


- **Nuestra competencia de mercado serán** empresas de leasing financiero, distribuidores tradicionales de hardware y proveedores de outsourcing de TI.


- **Los venceremos debido a que** ofreceremos servicios integrales enfocados en un valor estrategico, no solo entregando equipos, sino en la optimizacion de recursos, un soporte continuo y una festion completa del ciclo de vida tecnologico.


- **Nuestros mayores riesgos son** la falta de confianza inicial en el modelo de leasing tecnológico, la resistencia de empresas acostumbradas a comprar equipos, y la competencia de grandes proveedores nacionales e internacionales.


- **Resolveremos esto mediante** campañas educativas, casos de éxito, pruebas piloto con clientes, y diferenciación en servicio al cliente y soporte local personalizado.


- **Sabremos que hemos tenido éxito cuando uno de estos cambios en el comportamiento de nuestro cliente:**
  
  - Prefiera arrendar equipos en lugar de comprar.
  - Se reduzca sus costos de TI reinvirtiendo en crecimiento de su negocio.
  - Confie en PcPedia como socio estrategico de TI.


- **Qué otras suposiciones tenemos que, de probarse falsas pueden causar que nuestro proyecto fracase:**

   - Las empresas estén dispuestas a migrar de un modelo de compra a uno de leasing. 
   - Los beneficios de costo y productividad sean lo suficientemente evidentes. 
   - Podamos mantener alianzas sólidas con proveedores de hardware de calidad.

**User Outcomes:**

**¿Quiénes serán nuestros usuarios?**

Directores financieros, gerentes de operaciones, responsables de TI, y administradores de instituciones educativas que necesitan equipos actualizados sin grandes desembolsos.

**¿Dónde encaja nuestro producto en su vida o trabajo?**

En la planeación y gestión de su infraestructura tecnológica, ayudándoles a enfocarse en su negocio sin preocuparse por la obsolescencia ni la gestión de equipos.

**¿Qué problemas tiene nuestro producto y cómo se pueden resolver?**

**Problemas:**

 - Desconfianza en el modelo de arrendamiento.

 - Necesidad de flexibilidad contractual.

 - Adaptación a diferentes presupuestos.

**Soluciones:**

 - Casos de éxito, contratos transparentes y soporte personalizado.

 - Modelos de leasing flexibles según necesidad y tamaño de la empresa.

 - Planes escalables y ajustables en el tiempo.

**¿Cómo y cuándo es usado nuestro producto?**

En el ciclo operativo diario de las empresas: al adquirir nuevos equipos, al renovar tecnología obsoleta, y en la gestión continua de TI (mantenimiento, soporte, garantías).

**¿Qué características son importantes?**

 - Flexibilidad en planes de arrendamiento.
 - Gestión centralizada de soporte y garantías.
 - Reportes de costos y eficiencia tecnológica.
 - Equipos actualizados según necesidad real.

**¿Cómo debe verse y comportarse nuestro producto?**

Debe transmitir confianza, modernidad y simplicidad, con una interfaz clara (si es digital), y un servicio que se perciba ágil, transparente y estratégico.

**Features**

**Desde la cuenta de la empresa cliente:**

- Las empresas deben tener acceso a un panel donde visualicen todos los equipos arrendados, organizados por área o departamento. Esto les permitirá un control ordenado y evitar pérdidas o duplicidades.


- Un historial de mantenimiento y soporte estará disponible para cada equipo, lo que garantiza transparencia en las intervenciones técnicas y ayuda a tomar decisiones futuras


- Contarán con un sistema de alertas automáticas para notificar cuándo un equipo está próximo a su renovación o si requiere atención especial, evitando interrupciones en su productividad.


- El cliente podrá solicitar upgrades de hardware de forma ágil desde su cuenta, ajustando los recursos a sus necesidades reales en tiempo casi inmediato.


- Un dashboard de costos consolidado permitirá analizar el gasto mensual en TI y medir el ahorro frente a un modelo tradicional de compra.

**Desde la cuenta de administración de PcPedia:**

- Los administradores tendrán un sistema centralizado para monitorear en tiempo real todos los equipos en uso por los clientes, junto con su estado de garantía y mantenimientos programados.


- Contarán con herramientas de análisis predictivo para recomendar a cada cliente los equipos más rentables según su patrón de uso.


- Se dispondrá de un módulo para gestionar contratos y facturación de manera automatizada, evitando errores manuales.


- La plataforma permitirá registrar casos de soporte y asignar técnicos rápidamente, reduciendo los tiempos de respuesta.


- Un repositorio de métricas de clientes servirá para identificar patrones, generar reportes y mejorar continuamente el servicio de Smart Leasing.

---

#### 1.2.2.3. Lean UX Hypothesis Statements

<section style="display:flex; justify-content:center;">

 <table style="width:100%; max-width:900px; border-collapse:collapse; font-family:Arial, Helvetica, sans-serif; font-size:14px;">
    <thead>
      <tr>
        <th style="text-align:center; padding:10px; border:1px solid #e5e7eb;">Creemos que</th>
        <th style="text-align:center; padding:10px; border:1px solid #e5e7eb;">Sabremos que</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="vertical-align:top; padding:10px; border:1px solid #e5e7eb;">
          Las empresas y organizaciones que hoy compran equipos estarán dispuestas a migrar a un modelo de
          arrendamiento tecnológico inteligente si les demostramos ahorros en costos, equipos siempre actualizados
          y soporte especializado.
        </td>
        <td style="vertical-align:top; padding:10px; border:1px solid #e5e7eb;">
          Esto es cierto cuando reduzcan compras directas de hardware y firmen contratos de Smart Leasing,
          evidenciando crecimiento sostenido de la base de clientes.
        </td>
      </tr>
      <tr>
        <td style="vertical-align:top; padding:10px; border:1px solid #e5e7eb;">
          Nuestros usuarios valoran más la simplicidad en la gestión de TI: un servicio único que incluya
          arrendamiento, mantenimiento y gestión de garantías.
        </td>
        <td style="vertical-align:top; padding:10px; border:1px solid #e5e7eb;">
          Esto es cierto cuando usen con frecuencia el panel de control, soliciten upgrades desde la plataforma
          y reporten satisfacción por la reducción de tiempo y recursos en gestión de TI.
        </td>
      </tr>
      <tr>
        <td style="vertical-align:top; padding:10px; border:1px solid #e5e7eb;">
          La principal barrera de entrada es la desconfianza hacia el leasing tecnológico, pero podremos superarla
          con campañas educativas, casos de éxito y pruebas piloto.
        </td>
        <td style="vertical-align:top; padding:10px; border:1px solid #e5e7eb;">
          Esto es cierto cuando los participantes de pilotos escalen a contratos permanentes, compartan testimonios
          positivos y recomienden el servicio a otras empresas.
        </td>
      </tr>
    </tbody>
  </table>
</section>

---

#### 1.2.2.4. Lean UX Canvas

![lean_ux_canvas.png](docs/assets/img/chapter1/lean_ux_canvas.png)

---

## 1.3. Segmentos objetivo

1. **Empresas (pequeñas, medianas y grandes):** Cualquier organización que dependa de la tecnología para su funcionamiento, sin importar el sector al que pertenezca. Pueden ser entidades financieras, compañías de retail, industrias manufactureras, estudios contables, empresas de servicios o startups. En general, todas aquellas que requieren equipos tecnológicos para operar de forma eficiente en un mercado competitivo.


2. **Instituciones Educativas (universidades, colegios, escuelas, institutos):** Organizaciones dedicadas a la enseñanza, investigación o formación profesional que necesitan equipos tecnológicos para actividades académicas, administrativas y de apoyo a sus estudiantes y docentes. Incluye tanto instituciones de gran escala como universidades, así como colegios e institutos que buscan modernizar sus recursos tecnológicos.

---

<div align="center">

# Capítulo II: Requirements Elicitation & Analysis

</div>

---

## 2.1. Competidores

En esta sección se identifican y describen los principales competidores directos de la startup **Smart Leasing**, cuyo enfoque gira en torno al **arrendamiento inteligente de equipos tecnológicos con soporte y gestión de ciclo de vida**. Se han considerado empresas que ofrecen soluciones similares en el mercado peruano, tanto locales como internacionales.

Los competidores seleccionados son:

### **HardRental Perú**

Empresa peruana especializada en **renting informático** para empresas, con foco en **alquiler de laptops, PCs y periféricos**. Ofrece soporte técnico, _service desk_ y mantenimiento incluidos en los contratos. Su propuesta se centra en brindar flexibilidad a corto y mediano plazo, orientada principalmente a **empresas que buscan evitar la compra de hardware y reducir la inversión inicial**.

### **Thuntech**

Proveedor nacional que ofrece **leasing operativo de tecnología** con plazos que van de 24 a 60 meses. Su servicio incluye **alquiler de laptops, equipos de oficina y dispositivos especializados** para empresas, bajo un modelo de suscripción. Thuntech busca posicionarse como alternativa a la compra tradicional, enfocándose en **contratos a largo plazo y planes corporativos escalables**.

### **CSI Leasing Perú**

Filial de la multinacional **CSI Leasing**, con presencia en más de 30 países. En Perú ofrece **leasing tecnológico** con un fuerte componente de **gestión de activos (Asset Management)** a través de su plataforma _MyCSI_, que permite a las empresas tener trazabilidad completa del ciclo de vida de sus equipos. Su propuesta está orientada a **grandes corporaciones** que buscan eficiencia financiera, seguridad en datos y soporte global.

---

### 2.1.1. Análisis competitivo

El objetivo del presente análisis competitivo es responder a la pregunta:

**¿Cómo se posiciona Smart Leasing frente a sus principales competidores en términos de funcionalidades, estrategia de mercado y propuesta de valor?**

Para ello, se utiliza el modelo de análisis **Competitive Analysis Landscape**, estructurado en categorías y subcategorías.

<div align="center">

<table>
  <tr>
    <th colspan="6">Competitive Analysis Landscape</th>
  </tr>
  <tr>
    <td><b>¿Por qué llevar a cabo este análisis?</b></td>
    <td colspan="5">
      Identificar fortalezas, debilidades y oportunidades frente a competidores clave en el sector de leasing tecnológico en el Perú. <br>
      Comparar funcionalidades, posicionamiento y estrategia de Smart Leasing con otras plataformas similares en el mercado local e internacional.
    </td>
  </tr>
  <tr>
    <td colspan="2"></td>
    <td><b>Smart Leasing</b></td>
    <td><b>HardRental Perú</b></td>
    <td><b>Thuntech</b></td>
    <td><b>CSI Leasing Perú</b></td>
  </tr>
  <tr>
    <td rowspan="2"><b>Perfil</b></td>
    <td>Overview</td>
    <td>Startup peruana enfocada en el leasing tecnológico inteligente, que combina arrendamiento de equipos de TI con soporte, mantenimiento y gestión de ciclo de vida.</td>
    <td>Empresa local de renting informático especializada en alquiler de laptops y PCs con soporte incluido.</td>
    <td>Proveedor nacional que ofrece leasing operativo de tecnología con contratos de 24 a 60 meses.</td>
    <td>Filial peruana de la multinacional CSI Leasing, con experiencia en más de 30 países.</td>
  </tr>
  <tr>
    <td>Ventaja competitiva / Valor al cliente</td>
    <td>Flexibilidad en contratos, soporte integral y enfoque estratégico en reducción de costos de TI. Valor: equipos actualizados, menor inversión inicial y gestión centralizada de garantías.</td>
    <td>Rapidez en la entrega y planes flexibles. Valor: acceso inmediato sin compromisos ni inversión inicial.</td>
    <td>Estabilidad contractual y escalabilidad. Valor: acceso a tecnología con planes de leasing a largo plazo.</td>
    <td>Respaldo financiero internacional y plataforma MyCSI. Valor: control de ciclo de vida, seguridad y soporte global.</td>
  </tr>
  <tr>
    <td rowspan="2"><b>Perfil de Marketing</b></td>
    <td>Mercado objetivo</td>
    <td>Pymes e instituciones educativas en Perú y Latinoamérica.</td>
    <td>Empresas locales (principalmente en Lima) que requieren equipos temporales o ágiles.</td>
    <td>Empresas medianas y grandes con foco en estabilidad financiera.</td>
    <td>Grandes corporaciones, bancos y multinacionales en Perú.</td>
  </tr>
  <tr>
    <td>Estrategias de marketing</td>
    <td>Marketing digital (LinkedIn, Google Ads, redes sociales), alianzas con proveedores, networking.</td>
    <td>SEO local, catálogo web, captación rápida de clientes.</td>
    <td>Relaciones B2B, convenios corporativos, publicidad en entornos empresariales.</td>
    <td>Marketing corporativo global, relaciones con CIOs y CFOs.</td>
  </tr>
  <tr>
    <td rowspan="3"><b>Perfil de Producto</b></td>
    <td>Productos & Servicios</td>
    <td>Leasing de laptops, PCs, servidores, upgrades, soporte, mantenimiento y gestión de garantías.</td>
    <td>Alquiler de laptops, PCs y periféricos con soporte básico.</td>
    <td>Leasing operativo de laptops y equipos de oficina, upgrades opcionales.</td>
    <td>Leasing tecnológico con Asset Management, borrado seguro de datos, contratos internacionales.</td>
  </tr>
  <tr>
    <td>Precios & Costos</td>
    <td>Contratos mensuales flexibles tipo SaaS/Leasing, con servicios premium opcionales.</td>
    <td>Pago por equipo alquilado según tiempo de uso.</td>
    <td>Cuotas fijas mensuales de arrendamiento.</td>
    <td>Contratos internacionales con costos altos, orientados a corporativos.</td>
  </tr>
  <tr>
    <td>Canales de distribución (Web/Móvil)</td>
    <td>Plataforma web con panel de clientes y módulo administrativo interno.</td>
    <td>Página web y atención directa a empresas.</td>
    <td>Página web y acuerdos directos con empresas.</td>
    <td>Plataforma MyCSI (web) y acuerdos globales.</td>
  </tr>
  <tr>
    <td rowspan="4"><b>Análisis SWOT</b></td>
    <td>Fortalezas</td>
    <td>Flexibilidad, servicio integral, foco en educación y pymes.</td>
    <td>Rapidez de atención y flexibilidad de corto plazo.</td>
    <td>Contratos estables y experiencia en leasing corporativo.</td>
    <td>Respaldo global, gestión avanzada de activos, seguridad de datos.</td>
  </tr>
  <tr>
    <td>Debilidades</td>
    <td>Nueva en el mercado, poco reconocimiento de marca.</td>
    <td>Oferta limitada al simple alquiler de hardware.</td>
    <td>Poca flexibilidad y personalización en los contratos.</td>
    <td>Costos elevados, poco atractivo para pymes locales.</td>
  </tr>
  <tr>
    <td>Oportunidades</td>
    <td>Digitalización creciente en Perú, modernización tecnológica en educación y pymes.</td>
    <td>Ampliar servicios hacia educación y startups.</td>
    <td>Creciente digitalización del mercado peruano.</td>
    <td>Adaptar modelos más flexibles para pymes en Perú.</td>
  </tr>
  <tr>
    <td>Amenazas</td>
    <td>Competencia internacional consolidada, resistencia cultural al leasing.</td>
    <td>Competidores con propuestas más completas.</td>
    <td>Startups ágiles que ofrezcan leasing más flexible.</td>
    <td>Regulaciones locales y percepción de costos excesivos.</td>
  </tr>
</table>

</div>

---

### 2.1.2. Estrategias y tácticas frente a competidores

Para competir de manera efectiva en el mercado de leasing tecnológico en el Perú, Smart Leasing implementará una serie de **estrategias** y **tácticas** orientadas a consolidar su posicionamiento, maximizar su alcance y diferenciarse de sus principales competidores (**HardRental Perú, Thuntech y CSI Leasing Perú**).

### **Estrategias**

1. **Enfoque en Pymes y Educación**  
   Smart Leasing priorizará pequeñas y medianas empresas (Pymes) e instituciones educativas, sectores con alta necesidad de modernización tecnológica pero sin presupuestos robustos.


2. **Modelo Integral de Smart Leasing**  
   Leasing + soporte + mantenimiento + gestión de garantías + upgrades bajo demanda.


3. **Flexibilidad Contractual**  
   Contratos cortos y adaptables (desde 12 meses), frente a los plazos rígidos de otros competidores.


4. **Educación y Confianza en el Leasing**  
   Campañas educativas, webinars y casos de éxito para superar la resistencia cultural al modelo.


5. **Alianzas Estratégicas con Proveedores Locales**  
   Convenios con distribuidores de hardware, software y servicios TI para competir con el alcance internacional de CSI Leasing.

### **Tácticas**

- Pilotos gratuitos o con descuento para empresas interesadas.
- Contratos escalables (ej. empezar con 10 equipos y crecer).
- Panel digital con **dashboard financiero** para mostrar ahorros en tiempo real.
- Soporte técnico diferenciado **24/7**.
- Campañas digitales segmentadas en LinkedIn, Google Ads y redes sociales.
- Casos de éxito documentados en empresas y colegios peruanos.
- Garantía de **renovación tecnológica cada 18–24 meses**.

---

## 2.2. Entrevistas

---

### 2.2.1. Diseño de entrevistas

**Segmento objetivo 1: Empresas**

- **Gestión de contrato**

1. ¿Cómo llevan el control de los contratos de los equipos tecnológicos?


2. Actualmente ¿Qué herramientas usan para la gestión de los contratos?


3. ¿Como acceden a dicha información de los contratos? (Excel, docx, papel)

- **Verificación de procesos**

4. ¿Cómo verifican el cumplimiento de los servicios contratados? (Software, mantenimiento, upgrades, etc.)


5. ¿Con qué frecuencia revisa los términos del contrato? ¿Cuánta relevancia le da?


6. ¿Cómo conservan el historial de mantenimiento?


7. ¿Cuál es el proceso para pedir soporte técnico? ¿Cuánto demora?

- **Comunicación y presupuesto**

8. ¿Qué canales de comunicación usa para hacer los contratos y comunicarse con el contratista?


9. ¿Como manejan los presupuestos de sus equipos y servicios de mantenimiento?

- **Satisfacción**

10. ¿Qué tan satisfecho se encuentra con las medidas que actualmente usa para la gestión de los contratos?

**Segmento objetivo 2: Instituciones educativas**

- **Gestión de equipos y contratos**

1. ¿Cómo llevan registro del inventario de los equipos tecnológicos?


2. ¿Qué herramientas usa para controlar los contratos y ver su estado de vigencia?


3. ¿Qué dificultades enfrenta al momento de comprar un equipo?


4. Actualmente ¿Qué problemas presenta al buscar información de los contratos?


5. ¿Qué procesos tienen que pasar para la contratación, renovación o cancelación de los contratos?

- **Soporte y mantenimiento**

6. ¿Con qué frecuencia tienen problemas técnicos?


7. Cuando se presentan dichos problemas ¿Qué procesos suceden para solucionar el problema?


8. ¿Cómo se comunican con su proveedor de TI para coordinar reparaciones o mantenimientos de los equipos?

- **Respecto al presupuesto**

9. Actualmente ¿Qué medios usa para comunicarse y encontrar contratos?


10. ¿Cómo obtiene información sobre los costos de los equipos y servicios TI?


11. ¿Cómo controla las facturas y pagos al proveedor de los equipos de tecnología?

- **Satisfacción**

12. ¿Cuál es su nivel de satisfacción con los procesos actuales, respecto a la gestión de contratos y equipos TI?

---

### 2.2.2. Registro de entrevistas

Sector 1: Educativo

Entrevista 1: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231c996_upc_edu_pe/IQC4XWYg-TB1SpO-zzYgNPaeAcmyTPMB3r7ahoUacxpDBrY?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=NNo2S9

Entrevista 2: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231c996_upc_edu_pe/IQAPI9sRUfEfQYr8hHl6QTFxAeGVRCvvJ_XY2FSGBwO1zSo?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=VZuOWU

Entrevista 3: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231c996_upc_edu_pe/EdfTLQJ-tXxAu4BRPaYVbfQBzbuharjGDN5G7Dy5zj3Yrg?e=mc1hZj&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

Sector 2: Empresas

Entrevista 1: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231c996_upc_edu_pe/IQBsj6h8KvMrRZNDf0kPnzROAVxLYnTtdFOEnXi2yttZiCI?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=SQDydQ

Entrevista 2: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231c996_upc_edu_pe/IQB-iRoIylUaQ6kZxrEprhyNAQ5qeE5OcYFehLyYhm-CZ5I?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=FyPZkW

Entrevista 3: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231c996_upc_edu_pe/IQDX0y0CfrV8QLuAUT2mFW30AbC1Tm4KpZ9UpRg0BtICeGU?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=LE8bGZ

---

### 2.2.3. Análisis de entrevistas

<h3>Hallazgos principales</h3>
<ul>
<li><strong>Gestión de contratos y documentación:</strong> uso de OneDrive/Drive; aún se manejan copias físicas. Empresas grandes usan integraciones con SharePoint.</li>
<li><strong>Procesos y dificultades:</strong> microempresas con procesos lentos y desordenados; empresas grandes con procesos ágiles y claros.</li>
<li><strong>Soporte y mantenimiento:</strong> microempresas con demoras y mala comunicación; grandes con soporte interno y escalamiento eficiente.</li>
<li><strong>Comunicación con proveedores:</strong> correo, WhatsApp y llamadas; en microempresas predomina la informalidad.</li>
<li><strong>Nivel de satisfacción:</strong> alto en empresas grandes, bajo en microempresas.</li>
</ul>

<h2>3. Comparativo Educativo vs Empresarial</h2>
<table>
<thead>
<tr>
<th>Aspecto</th>
<th>Sector Educativo</th>
<th>Sector Empresarial</th>
</tr>
</thead>
<tbody>
<tr>
<td>Gestión de contratos</td>
<td>Dispersa (físico + digital). Uso de RPE, SharePoint, OneDrive.</td>
<td>Drive/OneDrive en microempresas; SharePoint en grandes.</td>
</tr>
<tr>
<td>Procesos</td>
<td>Burocráticos, lentos en compras y renovaciones.</td>
<td>Microempresas lentos/desordenados; grandes más ágiles.</td>
</tr>
<tr>
<td>Mantenimiento</td>
<td>Incidencias moderadas, gestionadas con tickets.</td>
<td>Microempresas con problemas de soporte; grandes con control interno.</td>
</tr>
<tr>
<td>Comunicación</td>
<td>Principalmente formal (correo, tickets).</td>
<td>Mixto: correo, WhatsApp, llamadas; informalidad en microempresas.</td>
</tr>
<tr>
<td>Satisfacción</td>
<td>Media: procesos funcionan pero con burocracia.</td>
<td>Alta en grandes, baja en microempresas.</td>
</tr>
</tbody>
</table>

<div class="conclusion">
<h3>Conclusiones y Oportunidades</h3>
<p>Existe una necesidad común de <strong>centralizar y digitalizar</strong> los procesos de inventario, contratos y soporte. En el sector educativo, se prioriza reducir la burocracia y agilizar compras. En el sector empresarial, las microempresas requieren soluciones básicas y fáciles de implementar, mientras que las grandes buscan mejorar la integración y eficiencia de sus sistemas ya existentes.</p>
</div>

---

## 2.3. Needfinding

A partir de las entrevistas realizadas en los sectores educativo y empresarial, se identificaron las siguientes necesidades principales:

Centralización de la información
Tanto en instituciones educativas como en empresas, la gestión de inventarios, contratos y mantenimientos se encuentra fragmentada entre documentos físicos, hojas de cálculo y repositorios digitales. Existe la necesidad de una plataforma unificada que integre inventario, contratos y soporte en un solo lugar.

Agilidad en los procesos de compras y renovaciones
El sector educativo resalta la burocracia y las demoras en aprobaciones de compras. Se requiere un sistema que reduzca tiempos de cotización y validación, agilizando las decisiones de adquisición o leasing de equipos.

Gestión más eficiente del mantenimiento
En el sector empresarial, especialmente en microempresas, los procesos de soporte son lentos, desordenados y poco confiables. Se necesita un mecanismo ágil para registrar incidencias, coordinar técnicos y dar seguimiento con trazabilidad clara.

Mejor comunicación con proveedores
Si bien se usan correos y WhatsApp, los entrevistados expresan la necesidad de contar con canales más formales, integrados a los sistemas de gestión, para garantizar rapidez y respaldo en la comunicación.

Optimización del presupuesto y control de gastos
Varias organizaciones reconocen que los imprevistos y la falta de herramientas para planificación generan sobrecostos. Se necesita un módulo de control presupuestal y de facturación que permita prever gastos y registrar pagos de manera ordenada.

Nivel de satisfacción y expectativas

En el sector educativo: satisfacción intermedia; los procesos funcionan, pero se busca mayor agilidad.

En microempresas: insatisfacción por la falta de control y eficiencia.

En empresas grandes: satisfacción alta, aunque esperan mayor integración tecnológica.

Conclusión del Needfinding:
Existe una necesidad transversal de digitalización integral y centralización de procesos, acompañada de funcionalidades que reduzcan burocracia, optimicen la comunicación con proveedores y brinden control financiero. La solución ideal debe adaptarse tanto a microempresas (simplicidad y facilidad de adopción) como a instituciones educativas y empresas grandes (integración avanzada y escalabilidad).

---

### 2.3.1 User Personas

**Segmento objetivo 1:** Empresas (pequeñas, medianas y grandes)

![user persona 1.png](docs/assets/img/chapter2/user_persona_1.png)

**Segmento objetivo 2:** Instituciones Educativas (universidades, colegios, escuelas, institutos)

![user persona 2.png](docs/assets/img/chapter2/user_persona_2.png)

---

### 2.3.2. User Task Matrix

<table>
  <thead>
    <tr>
      <th rowspan="2">Actividades</th>
      <th colspan="2">Rodrigo Zevallos (Empresas)</th>
      <th colspan="2">Carmen Paredes (Instituciones educativas)</th>
    </tr>
    <tr>
      <th>Frecuencia</th>
      <th>Importancia</th>
      <th>Frecuencia</th>
      <th>Importancia</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Registrar cuenta en la plataforma</td>
      <td>Una vez</td>
      <td>Muy alta</td>
      <td>Una vez</td>
      <td>Muy alta</td>
    </tr>
    <tr>
      <td>Conocer información de equipos</td>
      <td>Rara vez</td>
      <td>Muy alta</td>
      <td>Usualmente</td>
      <td>Muy alta</td>
    </tr>
    <tr>
      <td>Visualizar la disponibilidad de los equipos</td>
      <td>Rara vez</td>
      <td>Alta</td>
      <td>Rara vez</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Aprender del uso de la plataforma</td>
      <td>Rara vez</td>
      <td>Media</td>
      <td>Rara vez</td>
      <td>Media</td>
    </tr>
    <tr>
      <td>Escribir reseñas sobre el servicio</td>
      <td>Rara vez</td>
      <td>Baja</td>
      <td>Rara vez</td>
      <td>Baja</td>
    </tr>
    <tr>
      <td>Reportar inconvenientes con el servicio</td>
      <td>Rara vez</td>
      <td>Alta</td>
      <td>Usualmente</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Acordar de auditorías</td>
      <td>Una vez</td>
      <td>Alta</td>
      <td>Una vez</td>
      <td>Muy alta</td>
    </tr>
    <tr>
      <td>Solicitar servicio técnico</td>
      <td>Rara vez</td>
      <td>Alta</td>
      <td>Usualmente</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Realizar pago del servicio</td>
      <td>Siempre</td>
      <td>Muy alta</td>
      <td>Siempre</td>
      <td>Muy alta</td>
    </tr>
  </tbody>
</table>

---

### 2.3.3. User Journey Mapping

**Segmento objetivo 1:** Empresas (pequeñas, medianas y grandes)

![user journey_mapping_1.png](docs/assets/img/chapter2/user_journey_mapping_1.png)

**Segmento objetivo 2:** Instituciones Educativas (universidades, colegios, escuelas, institutos)

![user journey_mapping_2.png](docs/assets/img/chapter2/user_journey_mapping_2.png)

---

### 2.3.4. Empathy Mapping

**Segmento objetivo 1:** Empresas (pequeñas, medianas y grandes)

![empathy_mapping 1.png](docs/assets/img/chapter2/empathy_mapping_1.png)

**Segmento objetivo 2:** Instituciones Educativas (universidades, colegios, escuelas, institutos)

![empathy_mapping 2.png](docs/assets/img/chapter2/empathy_mapping_2.png)

---

### 2.3.5. As-is Scenario Mapping

Segmento 1: Empresas

<div align="center"> <table> <tr> <th>Phases</th> <th>Búsqueda de soluciones TI</th> <th>Evaluación de proveedores</th> <th>Comunicación con proveedor</th> <th>Implementación del servicio</th> </tr> <tr> <td><b>Doing</b></td> <td align="center">Investiga opciones de adquisición o leasing de equipos.<br>Consulta páginas web, referencias y contactos.<br>Evalúa costos y beneficios.</td> <td align="center">Revisa características, disponibilidad y precios.<br>Compara propuestas.<br>Analiza condiciones de contrato.</td> <td align="center">Se comunica por correo, llamadas o reuniones.<br>Consulta dudas técnicas y comerciales.<br>Solicita cotizaciones.</td> <td align="center">Coordina entrega e instalación.<br>Gestiona contratos.<br>Solicita soporte o mantenimiento.</td> </tr> <tr> <td><b>Thinking</b></td> <td align="center">“Necesito optimizar costos sin afectar la operación.”<br>“Quiero una solución confiable.”</td> <td align="center">“¿Cuál opción se adapta mejor?”<br>“¿Este proveedor es confiable?”</td> <td align="center">“Espero respuestas rápidas.”<br>“Necesito claridad.”</td> <td align="center">“Debe funcionar sin problemas.”<br>“Quiero continuidad.”</td> </tr> <tr> <td><b>Feeling</b></td> <td align="center">Preocupado por costos.<br>Inseguro por opciones.<br>Presionado.</td> <td align="center">Confundido.<br>Expectante.</td> <td align="center">Frustrado si es lento.<br>Confiado con buena atención.</td> <td align="center">Satisfecho si funciona.<br>Estresado si falla.</td> </tr> </table> </div>

---

Segmento 2: Instituciones educativas

<div align="center"> <table> <tr> <th>Phases</th> <th>Identificación de necesidades</th> <th>Evaluación de recursos tecnológicos</th> <th>Comunicación con proveedores</th> <th>Uso y gestión de equipos</th> </tr> <tr> <td><b>Doing</b></td> <td align="center">Identifica necesidades académicas y administrativas.<br>Evalúa infraestructura.<br>Define requerimientos.</td> <td align="center">Revisa opciones tecnológicas.<br>Analiza presupuesto.<br>Compara proveedores.</td> <td align="center">Contacta proveedores.<br>Solicita cotizaciones.<br>Realiza consultas.</td> <td align="center">Implementa equipos.<br>Da seguimiento.<br>Reporta incidencias.</td> </tr> <tr> <td><b>Thinking</b></td> <td align="center">“Necesitamos modernizarnos.”<br>“Debe ayudar a estudiantes.”</td> <td align="center">“¿Se ajusta al presupuesto?”<br>“¿Será útil?”</td> <td align="center">“Necesito asesoría clara.”</td> <td align="center">“Debe funcionar en clases.”</td> </tr> <tr> <td><b>Feeling</b></td> <td align="center">Preocupado por presupuesto.<br>Motivado.</td> <td align="center">Duda.<br>Interés.</td> <td align="center">Confundido o tranquilo según atención.</td> <td align="center">Satisfecho o frustrado según resultados.</td> </tr> </table> </div>

---

## 2.4. Ubiquitous Language

- Cliente: persona, empresa o institución que requiere de equipamiento TI.


- Contrato: documento digital que establece condiciones de arrendamiento o de compra.


- Equipo: objeto técnologico (computadora, servidor, IoT, etc.) que forma parte de nuestro inventario y que el cliente requiere


- Inventario: ubicación física donde los equipos son guardados hasta el proceso de venta o arrendamiento.


- Incidencia: problema o requerimiento técnico que tiene el cliente.


- Mantenimiento: acciones preventivas realizadas por el equipo de soporte y solicitada por el cliente.


- Equipo de negocio: grupo encargado de la gestión de negocio, desde administración de usuarios, equipo de ventas, equipo de logística y soporte al cliente.

---

<div align="center">

# Capítulo III: Requirements Specification

</div>

---

## 3.1. To-Be Scenario Mapping

El escenario To-Be describe el flujo esperado una vez implementada la solución Smart Leasing, desde el primer contacto del usuario hasta la contratación y gestión del servicio.

| Actor | Objetivo | Interacción esperada | Resultado esperado |
| --- | --- | --- | --- |
| Usuario visitante | Conocer la propuesta de valor | Revisa la landing page, los servicios, planes, casos de éxito y canales de contacto. | Comprende los beneficios del servicio y decide registrarse o solicitar información. |
| Usuario registrado | Acceder a servicios personalizados | Inicia sesión, revisa catálogo de equipos, compara alternativas y consulta disponibilidad. | Selecciona equipos o planes alineados a sus necesidades. |
| Cliente | Contratar y gestionar el servicio | Confirma un plan de leasing, descarga comprobantes y administra renovaciones, modificaciones o cancelaciones. | Mantiene control de sus servicios contratados desde la plataforma. |
| Soporte especializado | Atender dudas o incidencias | Recibe formularios, mensajes o reportes técnicos desde los canales de atención. | Brinda respuesta y seguimiento oportuno al cliente. |

---

## 3.2. User Stories

<h2>Epics</h2>
<table border="1" cellspacing="0" cellpadding="5">

<tr><th>ID de Epic</th><th>Título</th><th>Descripción</th></tr>
<tr><td>EP01</td><td>Gestión de cuenta</td><td>Como usuario deseo contar con una cuenta personal con la cual registrarme, iniciar y cerrar sesión en la plataforma.</td></tr>
<tr><td>EP02</td><td>Información del servicio</td><td>Como usuario deseo contar con un apartado en el cual conocer el funcionamiento, antecedentes y costo del servicio.</td></tr>
<tr><td>EP03</td><td>Atención y comunicación</td><td>Como usuario deseo contar con mecanismos de contacto, mensajería y servicio al cliente para resolver mis dudas o inconvenientes.</td></tr>
<tr><td>EP04</td><td>Auditoría y catálogo de equipos</td><td>Como usuario deseo conocer la disponibilidad, características y auditorías de los equipos, para validar si satisfacen mis necesidades.</td></tr>
<tr><td>EP05</td><td>Contratación y gestión del servicio</td><td>Como usuario deseo contar con un apartado para realizar la contratación del servicio y gestionar mis suscripciones.</td></tr>
</table><br>

<table border="1" cellspacing="0" cellpadding="5">
<tr><th>ID de HU</th><td>HU01</td><th>ID de Epic</th><td>EP01</td></tr>
<tr><th>Título</th><td>Registro de cuenta</td><th>Prioridad en el negocio</th><td>Alta</td></tr>
<tr><th>Descripción</th><td colspan="3"><b>Como</b> usuario <b>quiero</b> registrarme en la plataforma indicando mis datos <b>para</b> interactuar con los servicios de Smart Leasing.</td></tr>
<tr><th>Criterios de Aceptación</th><td colspan="3">
<b>Escenario:</b> Registro de usuario<br><br>
<b>Dado que</b> no poseo cuenta<br>
<b>Cuando</b> seleccione “Registrarme” e ingrese mis datos<br>
<b>Entonces</b> la aplicación creará mi cuenta de forma segura.
</td></tr>
</table><br>

<table border="1" cellspacing="0" cellpadding="5">
<tr><th>ID de HU</th><td>HU02</td><th>ID de Epic</th><td>EP01</td></tr>
<tr><th>Título</th><td>Inicio de sesión</td><th>Prioridad en el negocio</th><td>Alta</td></tr>
<tr><th>Descripción</th><td colspan="3"><b>Como</b> usuario <b>quiero</b> iniciar sesión con mis credenciales <b>para</b> acceder a mi perfil de forma segura.</td></tr>
<tr><th>Criterios de Aceptación</th><td colspan="3">
<b>Escenario:</b> Inicio de sesión<br><br>
<b>Dado que</b> poseo una cuenta<br>
<b>Cuando</b> ingrese usuario y contraseña válidos<br>
<b>Entonces</b> accederé a mi panel personal.
</td></tr>
</table><br>

<table border="1" cellspacing="0" cellpadding="5">
<tr><th>ID de HU</th><td>HU03</td><th>ID de Epic</th><td>EP01</td></tr>
<tr><th>Título</th><td>Cierre de sesión</td><th>Prioridad en el negocio</th><td>Media</td></tr>
<tr><th>Descripción</th><td colspan="3"><b>Como</b> usuario <b>quiero</b> cerrar sesión <b>para</b> garantizar la privacidad de mi información.</td></tr>
<tr><th>Criterios de Aceptación</th><td colspan="3">
<b>Escenario:</b> Cierre de sesión<br><br>
<b>Dado que</b> estoy logueado<br>
<b>Cuando</b> seleccione “Cerrar sesión”<br>
<b>Entonces</b> la aplicación finalizará la sesión y volverá al estado “Invitado”.
</td></tr>
</table><br>

<table border="1" cellspacing="0" cellpadding="5">
<tr><th>ID de HU</th><td>HU04</td><th>ID de Epic</th><td>EP02</td></tr>
<tr><th>Título</th><td>Descripción del servicio</td><th>Prioridad en el negocio</th><td>Alta</td></tr>
<tr><th>Descripción</th><td colspan="3"><b>Como</b> usuario <b>quiero</b> acceder a la descripción general de Smart Leasing <b>para</b> comprender sus beneficios.</td></tr>
<tr><th>Criterios de Aceptación</th><td colspan="3">
<b>Escenario:</b> Consulta de información<br><br>
<b>Dado que</b> accedo a la sección “Servicio”<br>
<b>Cuando</b> abra el apartado de información<br>
<b>Entonces</b> visualizaré la descripción general.
</td></tr>
</table><br>

<table border="1" cellspacing="0" cellpadding="5">
<tr><th>ID de HU</th><td>HU05</td><th>ID de Epic</th><td>EP02</td></tr>
<tr><th>Título</th><td>Consulta de planes y costos</td><th>Prioridad en el negocio</th><td>Alta</td></tr>
<tr><th>Descripción</th><td colspan="3"><b>Como</b> usuario <b>quiero</b> consultar los planes de arrendamiento y costos <b>para</b> elegir la opción que mejor se adapte a mis necesidades.</td></tr>
<tr><th>Criterios de Aceptación</th><td colspan="3">
<b>Escenario:</b> Visualizar planes<br><br>
<b>Dado que</b> accedo a la sección de “Planes”<br>
<b>Cuando</b> revise las opciones<br>
<b>Entonces</b> podré ver precios, características y condiciones.
</td></tr>
</table><br>

<table border="1" cellspacing="0" cellpadding="5">
<tr><th>ID de HU</th><td>HU06</td><th>ID de Epic</th><td>EP02</td></tr>
<tr><th>Título</th><td>Casos de éxito</td><th>Prioridad en el negocio</th><td>Media</td></tr>
<tr><th>Descripción</th><td colspan="3"><b>Como</b> usuario <b>quiero</b> conocer testimonios y casos de éxito <b>para</b> confiar en la experiencia de ECAT Leasing.</td></tr>
<tr><th>Criterios de Aceptación</th><td colspan="3">
<b>Escenario:</b> Revisión de testimonios<br><br>
<b>Dado que</b> estoy evaluando la empresa<br>
<b>Cuando</b> consulte la sección “Clientes”<br>
<b>Entonces</b> visualizaré testimonios y referencias.
</td></tr>
</table><br>

<table border="1" cellspacing="0" cellpadding="5">
<tr><th>ID de HU</th><td>HU07</td><th>ID de Epic</th><td>EP03</td></tr>
<tr><th>Título</th><td>Formulario de contacto</td><th>Prioridad en el negocio</th><td>Alta</td></tr>
<tr><th>Descripción</th><td colspan="3"><b>Como</b> usuario <b>quiero</b> enviar consultas mediante un formulario <b>para</b> comunicarme con el soporte técnico.</td></tr>
<tr><th>Criterios de Aceptación</th><td colspan="3">
<b>Escenario:</b> Envío de consulta<br><br>
<b>Dado que</b> tengo una duda<br>
<b>Cuando</b> complete y envíe el formulario<br>
<b>Entonces</b> el sistema registrará mi solicitud y enviaré confirmación.
</td></tr>
</table><br>

<table border="1" cellspacing="0" cellpadding="5">
<tr><th>ID de HU</th><td>HU08</td><th>ID de Epic</th><td>EP03</td></tr>
<tr><th>Título</th><td>Chat de mensajería rápida</td><th>Prioridad en el negocio</th><td>Media</td></tr>
<tr><th>Descripción</th><td colspan="3"><b>Como</b> usuario <b>quiero</b> disponer de un chat de mensajería rápida <b>para</b> resolver dudas de manera ágil.</td></tr>
<tr><th>Criterios de Aceptación</th><td colspan="3">
<b>Escenario:</b> Uso de chat<br><br>
<b>Dado que</b> necesito asistencia inmediata<br>
<b>Cuando</b> abra la sección de chat<br>
<b>Entonces</b> podré enviar y recibir mensajes.
</td></tr>
</table><br>

<table border="1" cellspacing="0" cellpadding="5">
<tr><th>ID de HU</th><td>HU09</td><th>ID de Epic</th><td>EP03</td></tr>
<tr><th>Título</th><td>Soporte especializado</td><th>Prioridad en el negocio</th><td>Alta</td></tr>
<tr><th>Descripción</th><td colspan="3"><b>Como</b> usuario <b>quiero</b> acceder a soporte especializado en incidencias técnicas <b>para</b> garantizar continuidad en mis operaciones.</td></tr>
<tr><th>Criterios de Aceptación</th><td colspan="3">
<b>Escenario:</b> Reporte de incidencia<br><br>
<b>Dado que</b> tengo un problema técnico<br>
<b>Cuando</b> reporte la incidencia en el sistema<br>
<b>Entonces</b> recibiré atención especializada en un tiempo razonable.
</td></tr>
</table><br>

<table border="1" cellspacing="0" cellpadding="5">
<tr><th>ID de HU</th><td>HU10</td><th>ID de Epic</th><td>EP04</td></tr>
<tr><th>Título</th><td>Catálogo de equipos</td><th>Prioridad en el negocio</th><td>Alta</td></tr>
<tr><th>Descripción</th><td colspan="3"><b>Como</b> usuario <b>quiero</b> visualizar un catálogo de equipos <b>para</b> elegir el que mejor se ajuste a mi empresa.</td></tr>
<tr><th>Criterios de Aceptación</th><td colspan="3">
<b>Escenario:</b> Consulta de catálogo<br><br>
<b>Dado que</b> accedo a la sección de equipos<br>
<b>Cuando</b> revise el listado<br>
<b>Entonces</b> visualizaré fotos, fichas técnicas y disponibilidad.
</td></tr>
</table><br>

<table border="1" cellspacing="0" cellpadding="5">
<tr><th>ID de HU</th><td>HU11</td><th>ID de Epic</th><td>EP04</td></tr>
<tr><th>Título</th><td>Comparación de equipos</td><th>Prioridad en el negocio</th><td>Media</td></tr>
<tr><th>Descripción</th><td colspan="3"><b>Como</b> usuario <b>quiero</b> filtrar y comparar equipos según criterios <b>para</b> tomar una decisión informada.</td></tr>
<tr><th>Criterios de Aceptación</th><td colspan="3">
<b>Escenario:</b> Comparación<br><br>
<b>Dado que</b> consulto el catálogo<br>
<b>Cuando</b> seleccione dos o más equipos<br>
<b>Entonces</b> la aplicación mostrará una tabla comparativa.
</td></tr>
</table><br>

<table border="1" cellspacing="0" cellpadding="5">
<tr><th>ID de HU</th><td>HU12</td><th>ID de Epic</th><td>EP04</td></tr>
<tr><th>Título</th><td>Historial de auditorías</td><th>Prioridad en el negocio</th><td>Media</td></tr>
<tr><th>Descripción</th><td colspan="3"><b>Como</b> usuario <b>quiero</b> consultar el historial de auditorías y mantenimientos <b>para</b> asegurar la confiabilidad del equipo.</td></tr>
<tr><th>Criterios de Aceptación</th><td colspan="3">
<b>Escenario:</b> Consulta de historial<br><br>
<b>Dado que</b> selecciono un equipo<br>
<b>Cuando</b> abra la ficha técnica<br>
<b>Entonces</b> visualizaré fechas de auditoría y resultados.
</td></tr>
</table><br>

<table border="1" cellspacing="0" cellpadding="5">
<tr><th>ID de HU</th><td>HU13</td><th>ID de Epic</th><td>EP05</td></tr>
<tr><th>Título</th><td>Contratación de plan</td><th>Prioridad en el negocio</th><td>Alta</td></tr>
<tr><th>Descripción</th><td colspan="3"><b>Como</b> usuario <b>quiero</b> contratar un plan de leasing en línea <b>para</b> evitar procesos manuales.</td></tr>
<tr><th>Criterios de Aceptación</th><td colspan="3">
<b>Escenario:</b> Contratación<br><br>
<b>Dado que</b> poseo una cuenta<br>
<b>Cuando</b> seleccione un plan<br>
<b>Entonces</b> podré confirmar la contratación con comprobante generado.
</td></tr>
</table><br>

<table border="1" cellspacing="0" cellpadding="5">
<tr><th>ID de HU</th><td>HU14</td><th>ID de Epic</th><td>EP05</td></tr>
<tr><th>Título</th><td>Gestión de servicios contratados</td><th>Prioridad en el negocio</th><td>Alta</td></tr>
<tr><th>Descripción</th><td colspan="3"><b>Como</b> usuario <b>quiero</b> renovar, modificar o cancelar mis servicios <b>para</b> tener control sobre mis suscripciones.</td></tr>
<tr><th>Criterios de Aceptación</th><td colspan="3">
<b>Escenario:</b> Gestión de plan<br><br>
<b>Dado que</b> tengo servicios activos<br>
<b>Cuando</b> acceda a la sección de gestión<br>
<b>Entonces</b> podré realizar cambios o cancelaciones.
</td></tr>
</table><br>

<table border="1" cellspacing="0" cellpadding="5">
<tr><th>ID de HU</th><td>HU15</td><th>ID de Epic</th><td>EP05</td></tr>
<tr><th>Título</th><td>Descarga de comprobantes</td><th>Prioridad en el negocio</th><td>Media</td></tr>
<tr><th>Descripción</th><td colspan="3"><b>Como</b> usuario <b>quiero</b> descargar comprobantes y contratos <b>para</b> llevar un registro formal de mis operaciones.</td></tr>
<tr><th>Criterios de Aceptación</th><td colspan="3">
<b>Escenario:</b> Descarga de documento<br><br>
<b>Dado que</b> contraté un servicio<br>
<b>Cuando</b> acceda a mis comprobantes<br>
<b>Entonces</b> podré descargar archivos en PDF.
</td></tr>
</table><br>

---

## 3.3. Product Backlog

<table>
  <thead>
    <tr>
      <th># Orden</th>
      <th>ID de HU</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Story Points (1 / 2 / 3 / 5 / 8) </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>HU01</td>
      <td>Registro de cuenta</td>
      <td><b>Como</b> usuario <b>quiero</b>  registrarme en la plataforma indicando mis datos <b>para</b> interactuar con las funciones de la misma.</td>
      <td>1</td>
    </tr>
    <tr>
      <td>2</td>
      <td>HU02</td>
      <td>Inicio y cierre de sesión</td>
      <td><b>Como</b> usuario <b>quiero</b> ser capaz ingresar y salir de mi cuenta <b>para</b> mantener la privacidad de los datos de la misma.</td>
      <td>1</td>
    </tr>
    <tr>
      <td>3</td>
      <td>HU03</td>
      <td>Descripción de la empresa</td>
      <td><b>Como</b> usuario <b>quiero</b> conocer más a detalle la misión y visión de la empresa <b>para</b> saber si satisface mi necesidad.</td>
      <td>1</td>
    </tr>
    <tr>
      <td>4</td>
      <td>HU04</td>
      <td>Modalidad de cobro</td>
      <td><b>Como</b> usuario <b>quiero</b> ser capaz de informarme del cómo se calcula el monto a pagar <b>para</b> corroborarlo con mi presupuesto.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>5</td>
      <td>HU05</td>
      <td>Antecedentes de servicio</td>
      <td><b>Como</b> usuario <b>quiero</b> conocer el trabajo ya realizado por la empresa <b>para</b> que mi nivel de confianza en ella incremente.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>6</td>
      <td>HU06</td>
      <td>Ubicación y número telefónico</td>
      <td><b>Como</b> usuario <b>quiero</b> conocer dónde se ubican las oficinas y cómo puedo contactar con ellas <b>para</b> contactar al personal.</td>
      <td>1</td>
    </tr>
    <tr>
      <td>7</td>
      <td>HU07</td>
      <td>Chatbot asesor</td>
      <td><b>Como</b> usuario <b>quiero</b> poder acceder a una chat de respuesta rápida <b>para</b> aclarar mis dudas.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>8</td>
      <td>HU08</td>
      <td>Formulario de quejas</td>
      <td><b>Como</b> usuario <b>quiero</b> poder presentar una queja <b>para</b> hacer llegar mi malestar a la empresa.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>9</td>
      <td>HU09</td>
      <td>Servicio al cliente</td>
      <td><b>Como</b> usuario <b>quiero</b> contar con un medio por el cual tener contacto con el personal <b>para</b> recibir ayuda.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>10</td>
      <td>HU10</td>
      <td>Información de equipos</td>
      <td><b>Como</b> usuario <b>quiero</b> poder conocer la función de los equipos <b>para</b> conocer cómo satisfacer mis necesidades.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>11</td>
      <td>HU11</td>
      <td>Disponibilidad de equipos</td>
      <td><b>Como</b> usuario <b>quiero</b> poder conocer la disponibilidad de un equipo <b>para</b> consultar por el mismo u otro.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>12</td>
      <td>HU12</td>
      <td>Acuerdo de auditorías</td>
      <td><b>Como</b> usuario <b>quiero</b> poder recibir una auditoría personalizada en el área correspondiente <b>para</b> recibir ayuda de acuerdo a mis necesidades y presupuesto.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>13</td>
      <td>HU13</td>
      <td>Modalidades de pago</td>
      <td><b>Como</b> usuario <b>quiero</b> conocer las modalidades de pago disponibles <b>para</b> decidir cuál es la de mi conveniencia.</td>
      <td>1</td>
    </tr>
    <tr>
      <td>14</td>
      <td>HU14</td>
      <td>Apartado de pago desde la plataforma</td>
      <td><b>Como</b> usuario <b>quiero</b> contar con un apartado de pagos desde la misma plataforma <b>para</b> una mayor comodidad.</td>
      <td>3</td>
    </tr>
  </tbody>
</table>

---

## 3.4. Impact Mapping

![impact_mapping.png](./assets/chapter3/impact_mapping.png)

---

<div align="center">

# Capítulo IV: Product Design

</div>

---

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

**Tipografía**

| Uso                  | Fuente                 | Ejemplo visual            |
| -------------------- | ---------------------- | ------------------------- |
| Encabezados (H1, H2) | **Anton**              | TÍTULO PRINCIPAL          |
| Subtítulos / Botones | **Antonio**            | Subtítulo / Acción        |
| Texto general        | Sans Serif del sistema | Texto de párrafo estándar |

**Paleta de Colores**

| Color            | Hex                   | Uso                                             |
| ---------------- | --------------------- | ----------------------------------------------- |
| Azul principal   | `#1A3458`             | Headers, barra de navegación, botones primarios |
| Azul base claro  | `#F2F6FF`             | Fondos generales, secciones amplias, cards      |
| Negro            | `#000000`             | Texto sobre fondos claros                       |
| Blanco           | `#FFFFFF`             | Texto sobre fondos oscuros, íconos              |
| Escala de grises | `#333333` ‒ `#DDDDDD` | Wireframes, bordes, placeholders                |

**Espaciado y consistencia**

- Márgenes y paddings en múltiplos de 8 px.
- Bordes redondeados de 8 px para botones y tarjetas.
- Sombras suaves (“box-shadow” ligero) para elementos elevados como cards o modales.

---

### 4.1.2. Web Style Guidelines

**Componentes principales**

| Componente          | Estilo visual                                                       |
| ------------------- | ------------------------------------------------------------------- |
| Botón primario      | Fondo `#1A3458`, texto `#FFFFFF`, borde redondeado 8 px             |
| Botón secundario    | Fondo `#F2F6FF`, texto `#1A3458`                                    |
| Enlace              | Texto `#1A3458`, subrayado al pasar el cursor                       |
| Tarjeta (Card)      | Fondo `#F2F6FF`, título en Anton, contenido en negro, sombra ligera |
| Barra de navegación | Fondo `#1A3458`, texto y logo en blanco                             |
| Footer              | Fondo gris oscuro (`#333333`), texto en blanco                      |

**Accesibilidad**

- Contraste de al menos **4.5:1** entre texto y fondo.
- Tipografía legible, tamaño mínimo 16px para textos largos.
- Asegurar buen contraste también en estados hover/focus.

---

### 4.1.3. Mobile Style Guidelines

Las interfaces móviles deben conservar la identidad visual definida para la web, adaptando la navegación, el espaciado y los componentes a pantallas pequeñas. Se prioriza una lectura clara, acciones visibles y flujos breves para registro, consulta, comparación y contratación.

- Botones y elementos interactivos con tamaño suficiente para interacción táctil.
- Navegación principal mediante menú compacto o barra inferior según la prioridad de las acciones.
- Formularios con campos simples, mensajes de validación claros y teclado adecuado al tipo de dato.
- Cards y listados con jerarquía visual clara para facilitar la comparación de equipos y planes.
- Estados de carga, error y confirmación visibles en operaciones de cuenta, contacto y contratación.

#### 4.1.3.1. iOS Mobile Style Guidelines

- Respetar safe areas, especialmente en pantallas con notch o Dynamic Island.
- Usar controles de navegación consistentes con patrones iOS, como barras superiores claras y acciones principales visibles.
- Mantener objetivos táctiles cercanos a 44 px como referencia mínima.

#### 4.1.3.2. Android Mobile Style Guidelines

- Respetar gestos de navegación del sistema y evitar controles ubicados en zonas difíciles de alcanzar.
- Usar patrones compatibles con Material Design para inputs, botones, estados y listas.
- Mantener objetivos táctiles cercanos a 48 dp como referencia mínima.

---

## 4.2. Information Architecture

### 4.2.1. Organization Systems

En esta sección se definen los sistemas de organización que permitirán estructurar y etiquetar el contenido de manera que resulte comprensible y fácil de encontrar para los usuarios. La organización de la información en _PcPedia_ busca adaptarse a las necesidades tanto de estudiantes de ingeniería, técnicos de soporte como de usuarios entusiastas de hardware.

**Jerarquía de contenido:**
Se aplica una jerarquía visual que da prioridad a los componentes principales que los usuarios buscan con mayor frecuencia. Las secciones destacadas en la interfaz incluyen categorías como Procesadores, Tarjetas Gráficas, Memorias RAM, Almacenamiento, Placas Base y Periféricos. Cada categoría cuenta con subcategorías; por ejemplo, dentro de Procesadores, se diferencian líneas como Intel Core i3, i5, i7 e i9, así como AMD Ryzen 5, 7 y 9. Esta jerarquía ayuda al usuario a identificar rápidamente dónde debe dirigirse según su necesidad.

**Organización secuencial:**
El flujo de interacción acompaña al usuario en pasos lógicos: buscar un componente, revisar sus especificaciones técnicas, compararlo con otro producto y finalmente visualizar recomendaciones relacionadas. Este proceso está diseñado para ser intuitivo, de manera que los usuarios puedan tomar decisiones rápidas sin perderse entre pantallas o exceso de información.

**Organización matricial:**
Se complementa con un menú y estructura de navegación que permiten combinar distintas dimensiones de filtrado. Por ejemplo, un usuario puede entrar a la categoría “Laptops”, aplicar un filtro por marca “ASUS” y luego ajustar por rango de precio. De esta forma, un mismo producto puede encontrarse a través de múltiples caminos, garantizando accesibilidad para diferentes perfiles de usuario.

---

### 4.2.2. Labeling Systems

En _PcPedia_, los sistemas de etiquetado son fundamentales para asegurar claridad y consistencia en la experiencia de navegación. Todas las secciones utilizan labels simples y familiares para la audiencia: “Procesadores”, “Tarjetas Gráficas”, “Almacenamiento” y “Comparador” se ubican en el menú superior, evitando términos técnicos confusos o redundantes.

Cada ficha de producto incluye etiquetas técnicas claras como “Frecuencia (GHz)”, “Número de núcleos”, “VRAM” o “Tipo de memoria”. Estas etiquetas permiten que tanto un usuario novato como un experto comprendan la información sin ambigüedades. Asimismo, los botones de acción presentan mensajes directos como “Comparar”, “Ver más” o “Agregar a favoritos”, reforzando la orientación en cada paso.

Gracias a este sistema, el usuario puede navegar de manera fluida y sin necesidad de decodificar terminología compleja.

---

### 4.2.3. SEO Tags and Meta Tags

La plataforma _PcPedia_ incorpora metaetiquetas que mejoran su posicionamiento en motores de búsqueda y aseguran que la información se interprete correctamente en navegadores.

- **Title:** cada página cuenta con un título descriptivo, por ejemplo: _“PcPedia – Comparador de Procesadores y Hardware de PC”_.
- **Codificación de caracteres:** se utiliza UTF-8 para mostrar adecuadamente caracteres especiales y símbolos técnicos.
- **Description:** cada página integra un resumen breve y atractivo, como _“Encuentra y compara procesadores Intel y AMD con especificaciones actualizadas y comparaciones en tiempo real”_.
- **Keywords:** se incluyen términos clave como “procesadores”, “tarjetas gráficas”, “comparador de hardware” para mejorar la indexación.
- **Author y Copyright:** detallan el equipo desarrollador y derechos reservados.

Estas prácticas garantizan que _PcPedia_ sea visible en búsquedas relevantes y transmita confianza a sus usuarios desde el primer contacto.

---

### 4.2.4. Searching Systems

Uno de los aspectos más relevantes de _PcPedia_ es la capacidad de localizar rápidamente componentes específicos dentro de un catálogo amplio. Para ello, se ha diseñado un sistema de búsqueda con varias funcionalidades:

- **Barra de búsqueda global:** permite ingresar directamente el nombre del componente (ej. “Ryzen 7 5800X”).
- **Autocompletado con sugerencias:** mientras el usuario escribe, se despliegan coincidencias relevantes como modelos y marcas.
- **Filtros dinámicos:** posibilitan refinar los resultados por precio, fabricante, fecha de lanzamiento o nivel de rendimiento.
- **Historial de búsqueda:** los usuarios registrados pueden guardar búsquedas previas y repetirlas con un solo clic.
- **Comparación directa:** desde la búsqueda, los resultados pueden enviarse al comparador sin necesidad de pasos adicionales.

Este sistema asegura que los usuarios no pierdan tiempo navegando por múltiples menús y puedan acceder a la información que necesitan de forma inmediata.

---

### 4.2.5. Navigation Systems

La navegación en _PcPedia_ está diseñada para ser clara, responsiva y adaptada a distintos dispositivos. El menú principal superior incluye accesos a las secciones más relevantes: Inicio, Categorías, Comparador, Noticias y Ayuda. Esta estructura permite un acceso rápido a las funciones esenciales sin saturar al usuario.

En categorías extensas, se incluyen **submenús desplegables** y **breadcrumbs (migas de pan)** que indican la ruta actual del usuario (ej. Inicio > Tarjetas Gráficas > NVIDIA). Esto ayuda a que siempre sepan dónde se encuentran dentro de la jerarquía.

Para dispositivos móviles se implementa un **menú hamburguesa**, donde las opciones aparecen en un panel lateral optimizado para pantallas pequeñas. En el footer se añaden accesos a contacto, políticas de privacidad, redes sociales y mapa del sitio, lo que refuerza la usabilidad.

Finalmente, los botones de acción (ej. “Comparar ahora”, “Agregar a favoritos”) se distribuyen en posiciones estratégicas para que la navegación no solo sea informativa, sino también orientada a la interacción constante del usuario.

---

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

Los wireframes son representaciones de baja fidelidad que muestran la estructura y disposición de los elementos principales de la aplicación web.

A continuación, presentaremos los wireframe de nuestra Landing Page como guía del diseño que haremos en los siguientes paso:

- Captura 1

![Wireframe1.png](./assets/chapter4/Wireframe-1.png)

- Captura 2

![Wireframe2.png](./assets/chapter4/Wireframe-2.png)

- Captura 3

![Wireframe3.png](./assets/chapter4/Wireframe-3.png)

- Captura 4

![Wireframe4.png](./assets/chapter4/Wireframe-4.png)

- Captura 5

![Wireframe5.png](./assets/chapter4/Wireframe-5.png)

Para más detalle, revisar el anexo 1.

### 4.3.2. Landing Page Mock-up.

El Mock-up de la Landing Page es una representación de alta fidelidad de la página de inicio, donde se aplican colores, tipografía, iconografía y estilos que transmiten la identidad visual corporativa. Este mock-up permite visualizar cómo se verán realmente los componentes descritos en el wireframe.

Este mock-up refleja la versión estilizada que un usuario final verá al ingresar, integrando la experiencia visual con la navegación lateral.

- Captura 1

![MockUp1.png](./assets/chapter4/Mock-up1.png)

- Captura 2

![MockUp2.png](./assets/chapter4/Mock-up2.png)

- Captura 3

![MockUp3.png](./assets/chapter4/Mock-up3.png)

- Captura 4

![MockUp4.png](./assets/chapter4/Mock-up4.png)

Para más detalle, revisar el anexo 1.

---

## 4.4. Mobile Applications UX/UI Design

### 4.4.1. Mobile Applications Wireframes

Anteriormente se mostraron los wireframes de la Landing Page del proyecto, ahora mostraremos el diseño de bajo nivel de fidelidad de la aplicación móvil de nuestro proyecto.

En primer lugar, mostraremos los elementos que se podran encontrar en nuestra aplicación móvil.

- Login, Usuario, Contraseña y Botón de acceso
- Pantalla de inicio de sesión con campos básicos de autenticación.
- Inicio Bienvenida Historia Servicios
- Landing de bienvenida con mensaje principal, historia y servicios.
- Dashboard Gráfico por modelo Gráfico por marca Exportar
- Panel de control con métricas de activos y opción de exportar.
- Contratos Tarjetas Estados
- Vista de contratos listados como tarjetas.
- Perfil Avatar Datos Configuración
- Página de perfil con información y opciones de configuración.
- Partners Novedades
- Sección de socios y novedades corporativas.

**Vista 1**

![WireframeWeb1.png](./assets/chapter4/WireframeWeb1.png)

**Vista 2**

![WireframeWeb2.png](./assets/chapter4/WireframeWeb2.png)

**Vista 3**

![WireframeWeb3.png](./assets/chapter4/WireframeWeb3.png)

**Vista 4**

![WireframeWeb4.png](./assets/chapter4/WireframeWeb4.png)

**Vista 5**

![WireframeWeb5.png](./assets/chapter4/WireframeWeb5.png)

**Vista 6**

![WireframeWeb6.png](./assets/chapter4/WireframeWeb6.png)

Para más detalle, revisar el anexo 1.

### 4.4.2. Mobile Applications Wireflow Diagrams

![WireframeWeb.png](./assets/chapter4/WireframeWeb.png)

### 4.4.3. Mobile Applications Mock-ups

Finalmente, presentamos el modelo de alta fidelidad de nuestra aplicación móvil:

**Vista 1**

![Mock-upWeb1.png](./assets/chapter4/Mock-upWeb1.png)

**Vista 2**

![Mock-upWeb2.png](./assets/chapter4/Mock-upWeb2.png)

**Vista 3**

![Mock-upWeb3.png](./assets/chapter4/Mock-upWeb3.png)

**Vista 4**

![Mock-upWeb4.png](./assets/chapter4/Mock-upWeb4.png)

**Vista 5**

![Mock-upWeb5.png](./assets/chapter4/Mock-upWeb5.png)

**Vista 6**

![Mock-upWeb6.png](./assets/chapter4/Mock-upWeb6.png)

**Vista 7**

![Mock-upWeb7.png](./assets/chapter4/Mock-upWeb7.png)

### 4.4.4. Mobile Applications User Flow Diagrams

![Mock-upWeb.png](./assets/chapter4/Mock-upWeb.png)

---

## 4.5. Mobile Applications Prototyping

El prototipo móvil representa la navegación principal de la aplicación para validar la experiencia en pantallas pequeñas antes de pasar a implementación. Este prototipo permite revisar el registro, inicio de sesión, consulta de servicios, comparación de equipos, contacto con soporte y gestión de contratación desde dispositivos móviles.

---

### 4.5.1. Android Mobile Applications Prototyping

Para Android, el prototipo considera patrones de interacción familiares para usuarios del sistema operativo: navegación inferior o menú compacto, formularios adaptados al teclado móvil, cards para información de equipos y botones táctiles con estados claros. El objetivo es validar que los flujos principales puedan completarse con pocas acciones y sin pérdida de contexto.

---

### 4.5.2. iOS Mobile Applications Prototyping

Para iOS, el prototipo contempla el uso de áreas seguras, navegación superior clara y controles táctiles consistentes con las guías de Apple. La experiencia prioriza legibilidad, jerarquía visual y continuidad entre pantallas para que los usuarios puedan explorar, comparar y contratar servicios de manera fluida.

---

## 4.6. Web Applications UX/UI Design

### 4.6.1. Web Applications Wireframes

Anteriormente se mostraron los wireframes de la Landing Page del proyecto, ahora mostraremos el diseño de bajo nivel de fidelidad de la web de nuestro proyecto.

En primer lugar, mostraremos los elementos que se podran encontrar en nuestra web.

- Login, Usuario, Contraseña y Botón de acceso
- Pantalla de inicio de sesión con campos básicos de autenticación.
- Inicio Bienvenida Historia Servicios
- Landing de bienvenida con mensaje principal, historia y servicios.
- Dashboard Gráfico por modelo Gráfico por marca Exportar
- Panel de control con métricas de activos y opción de exportar.
- Contratos Tarjetas Estados
- Vista de contratos listados como tarjetas.
- Perfil Avatar Datos Configuración
- Página de perfil con información y opciones de configuración.
- Partners Novedades
- Sección de socios y novedades corporativas.

**Vista 1**

![WireframeWeb1.png](./assets/chapter4/WireframeWeb1.png)

**Vista 2**

![WireframeWeb2.png](./assets/chapter4/WireframeWeb2.png)

**Vista 3**

![WireframeWeb3.png](./assets/chapter4/WireframeWeb3.png)

**Vista 4**

![WireframeWeb4.png](./assets/chapter4/WireframeWeb4.png)

**Vista 5**

![WireframeWeb5.png](./assets/chapter4/WireframeWeb5.png)

**Vista 6**

![WireframeWeb6.png](./assets/chapter4/WireframeWeb6.png)

Para más detalle, revisar el anexo 1.

### 4.6.2. Web Applications Wireflow Diagrams

![WireframeWeb.png](./assets/chapter4/WireframeWeb.png)

### 4.6.3. Web Applications Mock-ups

Finalmente, presentamos el modelo de alta fidelidad de nuestra pagina web:

**Vista 1**

![Mock-upWeb1.png](./assets/chapter4/Mock-upWeb1.png)

**Vista 2**

![Mock-upWeb2.png](./assets/chapter4/Mock-upWeb2.png)

**Vista 3**

![Mock-upWeb3.png](./assets/chapter4/Mock-upWeb3.png)

**Vista 4**

![Mock-upWeb4.png](./assets/chapter4/Mock-upWeb4.png)

**Vista 5**

![Mock-upWeb5.png](./assets/chapter4/Mock-upWeb5.png)

**Vista 6**

![Mock-upWeb6.png](./assets/chapter4/Mock-upWeb6.png)

**Vista 7**

![Mock-upWeb7.png](./assets/chapter4/Mock-upWeb7.png)

### 4.6.4. Web Applications User Flow Diagrams

![Mock-upWeb.png](./assets/chapter4/Mock-upWeb.png)

---

## 4.7. Web Applications Prototyping

El prototipo de la aplicación web adjunta la representación visual anteriomente mostrada y la vuelve interactiva, pero sin tener código real detrás.

Para este proyecto, usamos figma para hacer el prototipo de la aplicación web. Véase el anexo 2 para mayor información.

---

## 4.8. Domain-Driven Software Architecture

La arquitectura del producto se plantea desde una perspectiva Domain-Driven Design, separando responsabilidades y límites funcionales para organizar los módulos principales del sistema. Los siguientes diagramas muestran la relación del sistema con usuarios externos, contenedores y componentes internos.

---

### 4.8.1. Software Architecture Context Diagram

El diagrama de contexto es uno que trata en alto nivel, o sea de manera superficial el negocio. Por ejemplo, en nuestro caso, podemos ver las personas que interactuaran con nuestro sistema, el sistema y los sistemas externos que nos ayudaran a conseguir los objetivos del negocio.

![Diagram_C1.png](./assets/chapter4/Diagram_C1.png)

---

### 4.8.2. Software Architecture Container Diagrams

El diagrama de contenedores es similar al de contexto, pero descomponiendo nuestro sistema en los servicios que lo compondran. En este caso, nuestro sistema estara compuesto por 2 páginas web: Customer y Staff, separamos a los clientes de la web en la que se trabajará en el negocio.

![Diagram_C2.png](./assets/chapter4/Diagram_C2.png)

---

### 4.8.3. Software Architecture Components Diagrams

Finalmente, el diagrama de componentes nos ayuda a describir a los componentes internos, siendo el que decidimos elegir como el más importante el API.

Dentro podemos ver modulos o, interpretandolo con el DDD, bounded context donde se seguiria la misma logica mostrada en el Event Storming.

![Diagram_C3.png](./assets/chapter4/Diagram_C3.png)

---

## 4.9 Software Object-Oriented Design

El diseño orientado a objetos permite representar las entidades principales del dominio, sus atributos, responsabilidades y relaciones. Esta vista complementa la arquitectura de software al aterrizar los elementos de negocio en clases que pueden guiar la implementación.

---

### 4.9.1. Class Diagrams

Aquí se visualiza el diagrama de clases de ECAT Leasing. Este diagrama es una representación gráfica estática que muestra la estructura de un sistema de software, detallando las clases, sus atributos, operaciones y las relaciones existentes entre ellas.

![ClassDiagram.png](./assets/chapter4/Class_Diagram.png)

---

### 4.9.2. Class Dictionary

| Clase | Responsabilidad | Atributos principales |
| --- | --- | --- |
| Usuario | Representa a la persona que accede a la plataforma y utiliza los servicios disponibles. | id, nombre, correo, contraseña, rol, estado |
| Cliente | Representa al usuario que contrata o administra servicios de leasing. | idCliente, razonSocial, ruc, telefono, direccion |
| Equipo | Representa los activos tecnológicos disponibles para alquiler, compra o auditoría. | idEquipo, nombre, categoria, especificaciones, estado, disponibilidad |
| Contrato | Registra las condiciones de contratación del servicio. | idContrato, fechaInicio, fechaFin, monto, estado, tipoServicio |
| Incidente | Registra problemas técnicos o solicitudes de soporte del cliente. | idIncidente, descripcion, prioridad, estado, fechaRegistro |
| Mantenimiento | Representa acciones preventivas o correctivas sobre equipos tecnológicos. | idMantenimiento, tipo, fechaProgramada, resultado, estado |
| OrdenCompra | Registra operaciones de compra o contratación realizadas desde la plataforma. | idOrden, fecha, total, metodoPago, estado |
| Inventario | Gestiona la disponibilidad y ubicación de los equipos. | idInventario, ubicacion, stock, fechaActualizacion |

---

## 4.10 Database Design

El diseño de base de datos organiza la persistencia de la información necesaria para usuarios, equipos, contratos, incidencias, mantenimiento y operaciones comerciales. Esta estructura permite mantener trazabilidad sobre los servicios contratados y la disponibilidad de activos tecnológicos.

---

### 4.10.1. Relational/Non-Relational Database Diagram

Aquí se visualiza el diagrama de base de datos de ECAT Leasing. Este diagrama es una representación visual que muestra la estructura, las tablas, columnas y las relaciones entre ellos dentro de un sistema de base de datos, también se le conoce como esquema de base de datos.

![DataBaseDiagram.png](./assets/chapter4/Database_Diagram.png)

---

<div align="center">

# Capítulo V: Product Implementation

</div>

---

## 5.1. Software Configuration Management

En esta sección se describen las herramientas y configuraciones utilizadas para gestionar el desarrollo del software, incluyendo el entorno de desarrollo, el control de versiones, las convenciones de estilo de código y la configuración del despliegue.


### 5.1.1. Software Development Environment Configuration

En esta sección, se incluirá los productos de software que se usaron en el proyecto. Los enlaces a cada una de las herramientas se encuentran disponibles en los anexos.

#### Product UX/UI Design:

- Figma: Herramienta de diseño colaborativo para crear prototipos, wireframes y diseños de interfaces de usuario.
- Canva: Plataforma de diseño colaborativo de funcion múltiple.
- Visual Paradigm: Herramienta de modelado UML y diseño de software.
- PlantText: Herramienta de modela UML.

#### Software Development:

- WebStorm: IDE para desarrollo web, soporta HTML, CSS, JavaScript y frameworks modernos.
- GitHub: Plataforma de alojamiento de código fuente y control de versiones utilizando Git.
- Visual Studio Code: Editor utilizado únicamente para la exportación del reporte de formato markdown a PDF.
- GitHub Pages: Servicio de alojamiento web estático proporcionado por GitHub, ideal para desplegar sitios web y documentación.

### 5.1.2. Source Code Management

Para la gestion del código fuente se utilizó GitHub, una plataforma de alojamiento de código fuente y control de versiones utilizando Git. Se creó un repositorio en la organización de GitHub, donde se almacenó todo el código fuente del proyecto.

El repositorio se estructuró de la siguiente manera:

- Organización en Github: https://github.com/PCPedia2026
- Repositorio del informe final: https://github.com/PCPedia2026/Report

#### Conventional Commits

- `feat`: Para nuevas características o funcionalidades.
- `fix`: Para correcciones de errores.
- `docs`: Para cambios en la documentación.
- `refactor`: Para cambios en el código que no agregan ni corrigen funcionalidades.
- `add`: Para la adición de archivos, recursos o contenido nuevo (ej. imágenes, configs, assets).
- `update`: Para modificaciones o mejoras sobre algo ya existente (ej. actualizar imágenes, texto, librerías, dependencias).
- `chore`: Estructuración de contenido


### 5.1.3. Source Code Style Guide & Conventions

Se optó por seguir las siguientes guías y convenciones de estilo de código para asegurar la calidad y consistencia del código fuente, priorizando el uso del **inglés** cómo una buena práctica.

#### HTML:

- Archivos HTML deben tener la extensión `.html`.
- Se incluye `alt` en todas las imágenes.
- Usar comillas dobles para atributos.
- Usar etiquetas semánticas (`<header>`, `<nav>`, `<main>`, `<footer>`, etc.).
- Indentación de 2 espacios.

#### CSS:

- Archivos CSS deben tener la extensión `.css`.
- Usar guiones para nombres de clases y IDs (e.g., `.main-header`).
- Se agrupan estilos relacionados y se separan con comentarios.

#### JavaScript y TypeScript:

- Archivos JS deben tener la extensión `.js` y TS `.ts`.
- Usar camelCase para nombres de variables y funciones.
- Usar `PascalCase` para nombres de clases y componentes: `MyComponent`, `UserProfile`.
- Usar `const` y `let` en lugar de `var`.
- Usar funciones flecha y nombres explícitos.
- Los archivos deben tener una unica responsabilidad (Single Responsibility Principle).

### 5.1.4. Software Deployment Configuration

En esta sección se describen las configuraciones y herramientas utilizadas para el despliegue del software desarrollado. El objetivo es asegurar que el proceso de despliegue sea eficiente, automatizado y confiable.

#### Despliegue de la Landing Page:

La **Landing Page** fue desarrollada utilizando tecnologías web estándar como HTML, CSS y JavaScript. Y fue desplegada utilizando **GitHub Pages**, un servicio de alojamiento web estático proporcionado por GitHub.

**Repositorio de la Landing Page**: https://github.com/1ASI0729-7401-2520-EcatLeasing-PcPedia/Landing-Page-PcPedia

**Landing Page desplegada**: https://1asi0729-7401-2520-ecatleasing-pcpedia.github.io/Landing-Page-PcPedia/


## 5.2. Product Implementation & Deployment

---

### 5.2.1. Sprint Backlogs

<table align="center"  border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td>
            <b>Sprint #</b>
        </td>
        <td>
            <b>Sprint 3</b>           
        </td>
    </tr>
    <tr align="left">
        <td colspan="2">
            <b>Sprint Planning Background</b>
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Date</b>
        </td>
        <td>
            5/11/2025
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Time</b>
        </td>
        <td>
            10:00 PM
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Location</b>
        </td>
        <td>
            Modalidad virtual por Discord
        </td>
    </tr>
     </tr>
       <tr align="left">
        <td>
            <b>Prepared By</b>
        </td>
        <td>
            Integrantes de EcatLeasing
        </td>
    </tr>
    </tr>
       <tr align="left">
        <td>
            <b>Attendees (to planning meeting)</b>
        </td>
        <td>
            - Carranza Tesén, Joaquín Enrique <br/>
            - Bendezu Navarro, Rúbens <br/>
            - Hernandez Poma, Sebastian Eduardo <br/>
            - Arroyo Gonzales, Emily Juliette <br/>    
        </td>
    </tr>
      </tr>
       <tr align="left">
        <td>
            <b>Sprint n - 3</b>
            <b>Review Summary</b>
        </td>
        <td>
            Se complementó el desarrollo el frontend, así también se desarrolló el backend.
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sprint n - 3</b>
            <b>Retrospective Summary</b>
        </td>
        <td>
            Se aseguró de que los estudiantes conozcan sus respectivas tareas a desarrollar.
        </td>
    </tr>
     <tr align="left">
        <td colspan="2">
            <b>Sprint Goal & User Stories</b>
        </td>
    </tr>
      <tr align="left">
        <td>
            <b>Sprint 3 Goal</b>
        </td>
        <td>
            Nuestro objetivo en esta tercera entrega es la optimización del frontend anteriormente desarrollado y la creación del apartado backend. Durante este sprint, desplegaremos este último apartado aspirando a integrarlo con el frontend para así finalmente lograr una solución consistente. 
        </td>
      <tr align="left">
        <td>
            <b>Sprint 3 Velocity</b>
        </td>
        <td>
            5
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Sum of Story Points</b>
        </td>
        <td>
            5
        </td>
    </tr>
</table>

### 5.2.2. Implemented Landing Page Evidence

<p>La Landing Page fue desplegada en GitHub Pages, y está accesible a través del siguiente enlace: <a href="https://1asi0729-7401-2520-ecatleasing-pcpedia.github.io/Landing-Page-PcPedia/">Enlace a la Landing Page</a></p>

---

### 5.2.3. Implemented Frontend-Web Application Evidence

El frontend de PcPedia fue desplegado utilizando Netlify, una plataforma de despliegue optimizada para aplicaciones frontend.

**URL desplegada:** [PcPedia Front-end](https://dreamy-sunshine-e3be2b.netlify.app/)

![evidence_deployment_1.jpeg](./assets/chapter5/evidence_deployment_1.jpeg)
![evidence_deployment_2.jpeg](./assets/chapter5/evidence_deployment_2.jpeg)
![evidence_deployment_3.jpeg](./assets/chapter5/evidence_deployment_3.jpeg)
![evidence_deployment_4.jpeg](./assets/chapter5/evidence_deployment_4.jpeg)


### 5.2.4. Acuerdo de Servicio - SaaS

**Última actualización: 03/05/2026**

Este Acuerdo de Servicio regula los términos y condiciones bajo los cuales **ECAT Leasing** otorga el acceso al modelo de **Smart Leasing** y sus servicios asociados. Al suscribir una propuesta comercial o utilizar nuestros servicios, el Cliente acepta los términos aquí descritos.

---
**1. Definiciones**
- **“Smart Leasing”**: Modelo de arrendamiento inteligente de activos tecnológicos (hardware) con servicios de gestión integrados.
- **“Equipos”**: Hardware moderno (laptops, desktops, servidores, etc.) provisto por ECAT Leasing bajo la modalidad de arrendamiento.
- **“Cliente”**: Empresa o institución educativa que contrata los servicios de ECAT Leasing.
- **“Ecosistema de Servicios”**: Incluye soporte técnico, mantenimiento, gestión de garantías y consultoría de optimización de recursos.

---
**2. Objeto**
ECAT Leasing se compromete a proveer al Cliente el uso de equipos tecnológicos actualizados y la prestación de servicios de soporte, mantenimiento y gestión de TI, permitiendo al Cliente optimizar sus costos y evitar la obsolescencia tecnológica.

---
**3. Arrendamiento y Planes Flexibles**
- Los equipos se entregan en modalidad de arrendamiento operativo, manteniendo ECAT Leasing la propiedad de los activos.
- El Cliente podrá elegir planes según sus objetivos, con la posibilidad de actualizar el hardware según los periodos de renovación pactados.
- Está prohibido subarrendar los equipos a terceros sin autorización expresa de ECAT Leasing.

---
**4. Responsabilidades del Cliente**
El Usuario se compromete a:
1. Utilizar los equipos exclusivamente para los fines comerciales o educativos declarados.
2. Designar un contacto técnico para coordinar las visitas de mantenimiento y soporte.
3. Notificar de inmediato cualquier incidencia, daño, robo o pérdida de los activos.
4. Cumplir puntualmente con los pagos correspondientes al plan de Smart Leasing contratado.

---
**5. Responsabilidades de ECAT Leasing**
ECAT Leasing se compromete a:
- Entregar equipos en óptimas condiciones de funcionamiento y actualizados tecnológicamente.
- Brindar soporte técnico especializado y mantenimiento preventivo/correctivo según el nivel de servicio acordado.
- Gestionar las garantías con fabricantes y realizar la sustitución de equipos en caso de fallas no reparables en sitio.
- Realizar la evaluación de recursos para recomendar la configuración de hardware más eficiente para el Cliente.

---
**6. Pagos, Facturación y Renovación**
- Las tarifas se basan en el plan seleccionado y el volumen de activos gestionados.
- El incumplimiento en el pago facultará a ECAT Leasing a suspender el soporte técnico o retirar los activos previa notificación.
- La renovación es automática según el contrato marco, salvo notificación previa por el Cliente.

---
**7. Propiedad Intelectual**
- Todas las metodologías de gestión, software de monitoreo y la marca **ECAT Leasing** son propiedad exclusiva de la startup.
- El Cliente no adquiere derechos de propiedad sobre el hardware, solo una licencia de uso durante la vigencia del arrendamiento.

---
**8. Limitación de Responsabilidad**
ECAT Leasing no será responsable por:
- Pérdida de información o datos contenidos en los discos duros de los equipos.
- Lucro cesante derivado de fallas técnicas imprevistas, aunque se compromete a la sustitución ágil del hardware.
- Daños causados por uso indebido o manipulación por personal no autorizado.

---
**9. Suspensión y Terminación**
ECAT Leasing podrá suspender el servicio ante el incumplimiento de los pagos o por uso indebido de los activos, reservándose el derecho de retirar los equipos físicos de las instalaciones del Cliente.

---
**10. Modificaciones**
ECAT Leasing se reserva el derecho de modificar estos Términos en cualquier momento. Las modificaciones se notificarán por canales oficiales y se considerarán aceptadas al continuar con el uso del servicio.

---
**11. Legislación y Jurisdicción**
Este Acuerdo se rige por las leyes de la República del Perú. Cualquier controversia será sometida a los tribunales de Lima Metropolitana.

### 5.2.5. Implemented RESTful API and/or Serverless Backend Evidence

<p>Evidencias del despliegue:</p>

## Railway

![Railway](./assets/chapter5/sprint3_deployevidence1.png)

## Render

![Render1](./assets/chapter5/sprint3_deployevidence2.png)
![Render2](./assets/chapter5/sprint3_deployevidence3.png)

<ul>    
  <li><strong>Dockerfile implementado (multi-stage):</strong>
    <ul>
      <li>Stage builder basado en <code>eclipse-temurin:21-jdk</code></li>
      <li>Compilación con <code>./mvnw -q -B package -DskipTests</code></li>
      <li>Stage runtime con <code>eclipse-temurin:21-jre</code></li>
    </ul>
  </li>
    
  <ul>
    <li>Aplicación corriendo en contenedor Docker.</li>
    <li>Proovedor usado para deploy de BackEnd: Render</li>
    <li>Proovedor usado para Data Base: Railway</li>
    <li>URL pública: <strong>https://backendpcpedia.onrender.com</strong></li>
    <li>Acceso validado a rutas REST y Swagger durante el Sprint Review.</li>
  </ul>
</ul>

### 5.2.6. RESTful API documentation

### Arranque funcional
![Arranque funcional](./assets/chapter5/evidence_sprint3_1.png)

### Swagger funcional
![Swagger funcional](./assets/chapter5/evidence_sprint3_2.png)

### Validación visual del API
![Validación visual del API](./assets/chapter5/evidence_sprint3_3.png)
![Validación visual del API](./assets/chapter5/evidence_sprint3_4.png)

### 5.2.7. Team Collaboration Insights

<p>Durante este sprint, se mantuvo una comunicación constante entre los miembros del equipo mediante reuniones semanales. Se utilizó <strong>GitHub</strong> para la gestión del código fuente y el seguimiento de tareas, y <strong>Trello</strong> para organizar el avance del sprint. Las tareas fueron gestionadas y completadas según las estimaciones, y la colaboración entre los miembros del equipo fue eficiente.</p>


## 5.3. Video About-the-Product.

Como último artefacto del proyecto desarrollado, se ha desarrollado un video con orientación promocional e informativa, resumiendo el modelo de negocio, las características y beneficios del producto, incluyendo algunas escenas de interacción con el producto y al menos una opinión por cada segmento objetivo.  

![pcpedia_about_the_product_thumbnail.png](./assets/chapter5/pcpedia_about_the_product_thumbnail.png)  

**URL en OneDrive:** [OneDrive](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a553_upc_edu_pe/IQDMIq-ktRmmRInkCK2IRzV1AXCy8kQNCCH14S3BM6ZQaAw)  
**URL en YouTube:** [YouTube](https://youtu.be/2q87N3Umm0w)  



# Capítulo VI: Product Verification & Validation

## 6.1. Testing Suites & Validation

La verificación y validación de PcPedia se orientó a comprobar que los módulos principales del sistema respondan de forma consistente con las User Stories, los criterios de aceptación y la arquitectura propuesta. Para ello, se organizaron pruebas sobre el frontend desplegado en Netlify, el backend Java/Maven desplegado en Render, la base de datos alojada en Railway y la documentación REST expuesta mediante Swagger.

Las suites se agruparon en pruebas unitarias, integración, escenarios BDD y pruebas de sistema. Cada grupo permite revisar el producto desde un nivel distinto: reglas internas del dominio, comunicación entre componentes, comportamiento esperado por el usuario y validación funcional extremo a extremo.

### 6.1.1. Core Entities Unit Tests

Las pruebas unitarias se definieron para validar de manera aislada las entidades y reglas de negocio principales de PcPedia. Estas pruebas verifican que los objetos del dominio mantengan datos coherentes antes de interactuar con servicios externos, interfaz web o persistencia.

| ID | Entidad o módulo | Objetivo de validación | Resultado esperado |
| --- | --- | --- | --- |
| UT-01 | Usuario | Validar registro con nombre, correo, contraseña y rol requeridos. | El usuario se crea solo cuando los campos obligatorios son válidos. |
| UT-02 | Sesión | Validar credenciales de acceso y cierre de sesión. | El sistema acepta credenciales correctas y finaliza la sesión sin conservar acceso activo. |
| UT-03 | Equipo | Validar datos del equipo, categoría, especificaciones, estado y disponibilidad. | El equipo conserva información técnica completa y estados consistentes. |
| UT-04 | Contrato | Validar fechas, monto, tipo de servicio y estado del contrato. | El contrato solo se considera válido cuando sus fechas y condiciones son coherentes. |
| UT-05 | Incidente | Validar descripción, prioridad, estado y fecha de registro. | El incidente se registra con trazabilidad y puede pasar por estados controlados. |
| UT-06 | OrdenCompra | Validar total, método de pago, estado y comprobante asociado. | La orden mantiene montos consistentes y no avanza sin datos de pago válidos. |
| UT-07 | Inventario | Validar stock, ubicación y fecha de actualización. | La disponibilidad se actualiza sin generar valores negativos o inconsistentes. |

Estas pruebas cubren las reglas base de los módulos de autenticación, catálogo, contratación, soporte, pagos e inventario. Su propósito es reducir defectos tempranos antes de validar flujos completos en la aplicación web.

### 6.1.2. Core Integration Tests

Las pruebas de integración validan la comunicación entre el frontend web, los servicios REST del backend, Swagger como referencia funcional de endpoints y la base de datos desplegada en Railway. El objetivo es comprobar que las operaciones críticas no solo funcionen de forma aislada, sino también dentro del flujo real del sistema.

| ID | Flujo integrado | Componentes involucrados | Criterio de aceptación |
| --- | --- | --- | --- |
| IT-01 | Registro e inicio de sesión | Frontend, API de autenticación, base de datos | El usuario puede crear cuenta, iniciar sesión y visualizar su panel sin errores de sesión. |
| IT-02 | Consulta de catálogo de equipos | Frontend, API de equipos, inventario | El catálogo muestra equipos con ficha técnica, categoría, estado y disponibilidad actualizada. |
| IT-03 | Comparación de equipos | Frontend, API de equipos | El usuario selecciona equipos y visualiza diferencias técnicas relevantes para decidir. |
| IT-04 | Contratación de plan | Frontend, API de contratos, API de órdenes | El cliente selecciona un plan, confirma condiciones y genera una solicitud de contratación. |
| IT-05 | Gestión de contratos | Frontend, API de contratos, base de datos | El usuario consulta servicios activos, estados y documentos relacionados. |
| IT-06 | Registro de incidencias | Frontend, API de soporte, base de datos | La incidencia queda registrada con prioridad, descripción y estado inicial. |
| IT-07 | Pago o comprobante | Frontend, API de órdenes, almacenamiento de comprobantes | La orden registra método de pago, monto y comprobante asociado para revisión. |
| IT-08 | Documentación REST | Swagger, backend desplegado en Render | Los endpoints documentados responden según los contratos mostrados en Swagger. |

La integración se considera satisfactoria cuando el flujo conserva datos entre pantallas, servicios y persistencia, sin romper la navegación del usuario ni generar respuestas incompatibles con la interfaz.

### 6.1.3. Core Behavior-Driven Development

Los escenarios BDD se redactaron con la estructura Given-When-Then para expresar el comportamiento esperado desde la perspectiva del usuario final. Esto permite alinear pruebas, User Stories y validación funcional con un lenguaje comprensible para el equipo técnico y los stakeholders.

**HU01 - Registro de cuenta**

```gherkin
Scenario: Registro exitoso de usuario
  Given que el visitante no posee una cuenta en PcPedia
  When completa el formulario de registro con datos válidos
  Then el sistema crea la cuenta y permite acceder a las funciones de la plataforma
```

**HU02 - Inicio de sesión**

```gherkin
Scenario: Acceso con credenciales válidas
  Given que el usuario posee una cuenta registrada
  When ingresa correo y contraseña correctos
  Then el sistema inicia sesión y muestra el panel correspondiente
```

**HU10 - Consulta de catálogo de equipos**

```gherkin
Scenario: Visualización de equipos disponibles
  Given que el usuario ingresa al catálogo
  When consulta el listado de equipos
  Then visualiza fichas técnicas, estado y disponibilidad de cada equipo
```

**HU11 - Comparación de equipos**

```gherkin
Scenario: Comparación de alternativas tecnológicas
  Given que el usuario evalúa más de un equipo
  When selecciona equipos para comparar
  Then el sistema muestra una tabla comparativa con características relevantes
```

**HU13 - Contratación de plan**

```gherkin
Scenario: Solicitud de contratación de servicio
  Given que el usuario inició sesión y eligió un plan
  When confirma la contratación del servicio
  Then el sistema registra la solicitud y genera la información necesaria para seguimiento
```

**HU14 - Gestión de servicios contratados**

```gherkin
Scenario: Revisión de contratos activos
  Given que el cliente cuenta con servicios contratados
  When accede a la sección de gestión
  Then visualiza contratos, estados y opciones disponibles para administrarlos
```

**HU09 - Reporte de incidencia**

```gherkin
Scenario: Registro de ticket de soporte
  Given que el cliente presenta una incidencia técnica
  When completa el formulario de soporte
  Then el sistema registra el ticket con prioridad, descripción y estado inicial
```

**HU15 - Descarga de comprobantes**

```gherkin
Scenario: Consulta de comprobante de operación
  Given que el cliente realizó una contratación o pago
  When ingresa a la sección de comprobantes
  Then puede visualizar o descargar el documento asociado a la operación
```

### 6.1.4. Core System Tests

Las pruebas de sistema validan flujos completos sobre el producto integrado. Estas pruebas se plantean como recorridos manuales y funcionales que simulan el uso real de PcPedia por parte de clientes y personal administrativo.

| ID | Caso de sistema | Pasos principales | Resultado esperado | Estado |
| --- | --- | --- | --- | --- |
| ST-01 | Registro e inicio de sesión | Ingresar a la plataforma, registrar usuario, iniciar sesión y cerrar sesión. | El usuario accede al panel y puede finalizar sesión correctamente. | Validado |
| ST-02 | Consulta de catálogo | Abrir catálogo, revisar equipos, consultar ficha técnica y disponibilidad. | La información del equipo se muestra de forma clara y actualizada. | Validado |
| ST-03 | Comparación o evaluación de equipos | Seleccionar equipos o revisar alternativas recomendadas. | El usuario puede tomar una decisión informada según especificaciones y disponibilidad. | Validado |
| ST-04 | Contratación de plan | Seleccionar plan, confirmar condiciones y generar solicitud. | La contratación queda registrada para seguimiento del servicio. | Validado |
| ST-05 | Gestión de contratos | Ingresar al panel, consultar contratos activos y revisar estados. | Los contratos muestran estado, periodo y datos asociados al cliente. | Validado |
| ST-06 | Registro de ticket | Completar incidencia con descripción y prioridad. | El ticket se registra y queda disponible para atención. | Validado |
| ST-07 | Pago o comprobante | Registrar operación, adjuntar o consultar comprobante. | El sistema mantiene trazabilidad de la operación y el documento asociado. | Validado |
| ST-08 | Validación de API | Acceder a Swagger y revisar endpoints principales del backend. | La documentación REST permite validar rutas funcionales del servicio desplegado. | Validado |

El resultado de estas pruebas confirma que la solución web de PcPedia permite ejecutar los flujos principales de Smart Leasing: autenticación, consulta de equipos, contratación, soporte, pagos, documentación de API y operación integrada entre frontend y backend.

## 6.2. Static testing & Verification

La verificación estática se enfocó en revisar la calidad del código, la consistencia de convenciones, la seguridad básica y la mantenibilidad del proyecto sin ejecutar necesariamente los flujos funcionales. Este análisis complementa las pruebas dinámicas al detectar problemas de formato, estructura, duplicidad, dependencias y exposición de información sensible.

### 6.2.1. Static Code Analysis

El análisis estático se organiza por los principales frentes técnicos documentados en el proyecto: landing page, frontend web, backend Java/Maven, despliegue Docker y documentación de API.

| Frente | Elementos revisados | Criterio de verificación |
| --- | --- | --- |
| Landing Page | HTML, CSS, JavaScript, estructura semántica y enlaces. | El sitio mantiene navegación clara, estilos consistentes y enlaces funcionales. |
| Frontend Web | Componentes, rutas, consumo de API y manejo de sesión. | La interfaz separa responsabilidades y evita lógica duplicada en vistas. |
| Backend | Controladores, servicios, entidades, repositorios y DTOs. | La API mantiene capas diferenciadas y contratos consistentes con Swagger. |
| Base de datos | Modelos, relaciones y persistencia de datos críticos. | Los datos de usuarios, equipos, contratos, incidencias y órdenes conservan integridad. |
| Docker y despliegue | Dockerfile multi-stage, variables y servicios externos. | El despliegue no expone secretos y mantiene configuración reproducible. |
| Documentación REST | Swagger y evidencias de endpoints. | La documentación describe rutas, parámetros y respuestas esperadas. |

#### 6.2.1.1. Coding standard & Code conventions

Para mantener coherencia entre los distintos repositorios del producto, el equipo aplicó convenciones de nombrado, estructura y commits alineadas con lo documentado en el Capítulo V.

| Área | Convención aplicada |
| --- | --- |
| HTML | Uso de estructura semántica, etiquetas ordenadas y atributos descriptivos. |
| CSS | Nombres de clases claros, separación de estilos por responsabilidad y reutilización de reglas visuales. |
| JavaScript y TypeScript | Variables y funciones con nombres descriptivos, control de errores y separación entre vista y lógica. |
| Java/Maven | Organización por capas, nombres de clases representativos y responsabilidades acotadas. |
| Git | Uso de Conventional Commits para describir cambios de documentación, features, fixes y mejoras. |
| Documentación | Secciones numeradas, tablas consistentes y enlaces a evidencias desplegadas. |

Estas convenciones facilitan la revisión entre integrantes, reducen ambigüedades al integrar ramas y ayudan a que el proyecto mantenga una estructura entendible para futuras iteraciones.

#### 6.2.1.2. Code Quality & Code Security

La revisión de calidad y seguridad se centró en riesgos frecuentes de aplicaciones web con backend REST: validación de entradas, manejo de credenciales, consistencia de estados, exposición de datos y configuración de despliegue.

| Categoría | Riesgo revisado | Acción de verificación |
| --- | --- | --- |
| Validación de entradas | Datos incompletos o inválidos en registro, contratos, tickets y pagos. | Confirmar que formularios y API rechacen campos obligatorios vacíos o inconsistentes. |
| Autenticación | Acceso a vistas privadas sin sesión activa. | Validar protección de rutas y cierre de sesión correcto. |
| Manejo de datos sensibles | Exposición de contraseñas, tokens o credenciales de despliegue. | Revisar que no se documenten ni publiquen secretos en repositorios o capturas. |
| Estados de negocio | Contratos, órdenes o tickets en estados inválidos. | Verificar transiciones permitidas y trazabilidad de cambios. |
| API REST | Respuestas incompatibles con el frontend o Swagger. | Comparar contratos documentados con flujos reales de consumo. |
| Despliegue | Variables de entorno y configuración de servicios. | Confirmar separación entre configuración pública y privada. |

Como criterio de aceptación, ningún flujo crítico debe depender de datos hardcodeados sensibles, las rutas privadas deben requerir sesión y la documentación pública no debe exponer credenciales ni información interna del despliegue.

### 6.2.2. Reviews

Las revisiones del proyecto se realizaron mediante control de versiones en GitHub, integración de ramas de trabajo y validación cruzada del informe y los artefactos técnicos. Para evitar regresiones, cada revisión debe comprobar que los cambios agreguen valor sin eliminar evidencias, imágenes, enlaces ni secciones previas.

| Tipo de review | Objetivo | Criterios revisados |
| --- | --- | --- |
| Revisión de contenido | Asegurar que el informe represente correctamente el avance del producto. | Coherencia con PCPedia, numeración, redacción académica y uso correcto de evidencias. |
| Revisión técnica | Verificar consistencia entre arquitectura, implementación y despliegue. | Relación entre frontend, backend, base de datos, Swagger y proveedores usados. |
| Revisión de ramas | Integrar avances sin perder trabajo de otros integrantes. | Merge desde `develop`, resolución conservadora de conflictos y revisión del diff final. |
| Revisión de seguridad | Detectar exposición accidental de secretos o datos sensibles. | Ausencia de credenciales, tokens, datos privados o endpoints inseguros en documentación pública. |
| Revisión de trazabilidad | Relacionar User Stories, pruebas y módulos implementados. | Cada flujo crítico cuenta con caso de prueba o escenario BDD asociado. |

Con estas actividades, el equipo mantiene un proceso de validación incremental: se revisan documentos, artefactos, despliegues y flujos funcionales antes de consolidar cambios en el informe del proyecto.

---

## 6.3. Validation Interviews.

Este apartado se centra en examinar la experiencia del usuario a través de su interacción directa con la landing page y las aplicaciones del proyecto. El propósito principal es detectar fortalezas, así como áreas de mejora en términos de diseño, usabilidad y funcionalidad, recolectando el 'feedback' de un grupo representativo de nuestro público objetivo.

### 6.3.1. Diseño de Entrevistas.

Para que las pruebas reflejen con fidelidad cómo se comportará el usuario en el mundo real, esta sección describe la planificación detallada de las entrevistas. Aquí se definen los objetivos de la investigación, el perfil de los usuarios seleccionados y los flujos o temas clave que pondremos a prueba.

1. ¿La aplicación te permite identificar fácilmente el estado de tus contratos de leasing, los equipos asignados a tu organización y tus responsabilidades de pago o gestión?

2. ¿Te resulta claro cómo solicitar nuevos equipos, programar un mantenimiento preventivo/correctivo o reportar una incidencia técnica?

3. ¿El diseño visual (colores, íconos) te ayuda a entender rápidamente el estado de tus solicitudes (ej. Incidencia en atención, Mantenimiento programado, Evaluación de recursos completada)?

4. ¿Has tenido dificultades para navegar entre las secciones clave de la plataforma (Catálogo de hardware/Planes, Miembros/Sedes de la empresa, Reportes de costos/Rentabilidad, Notificaciones de mantenimiento)?

5. ¿Las palabras y etiquetas empleadas en la interfaz (ej. arrendamiento, obsolescencia, incidencia, mantenimiento preventivo, rentabilidad) son comprensibles y coherentes para tu perfil administrativo o de TI?

6. ¿Sientes que el flujo de acciones principales (crear una solicitud de soporte, cotizar un plan flexible, dar de baja un equipo o validar una renovación) es intuitivo?

7.¿Te resulta fácil identificar las respuestas del equipo de soporte especializado, el estado de las garantías o los comentarios dentro de un ticket de incidencia?

8. ¿La aplicación responde de manera clara mediante notificaciones o confirmaciones cuando realizas una acción crítica (ej. confirmar un plan de arrendamiento, reportar una falla de hardware o actualizar datos de facturación)?

9. ¿El diseño visual del panel de control y la gestión de incidencias se mantiene consistente si accedes desde la versión web o desde un dispositivo móvil?

10. ¿Qué mejorarías en la interfaz de gestión de Smart Leasing para que la toma de decisiones y el control de tus activos tecnológicos sea más claro o eficiente?

11. ¿Has encontrado algún elemento confuso o poco útil al momento de revisar la recomendación de equipos eficientes y rentables que el sistema sugiere para tu presupuesto?

12. ¿Consideras que el tiempo de respuesta de la plataforma es adecuado al interactuar con el catálogo de equipos, la carga de reportes de TI o la actualización de contratos?

13. ¿Te sientes cómodo utilizando la app desde tu dispositivo móvil para reportar incidencias en tiempo real o revisar alertas de mantenimiento técnico desde cualquier lugar de la empresa?

14. ¿La aplicación te proporciona la información y métricas financieras o técnicas que necesitas para verificar que estás optimizando los costos y evitando la obsolescencia tecnológica?

15. ¿Qué sensación general te deja el uso de la plataforma de ECAT Leasing en cuanto a la claridad para simplificar la gestión de tu TI, la organización de tus equipos y la facilidad de uso general?

### 6.3.2. Registro de Entrevistas.


| **Entrevista 1: Lider de Grupo** |      <img width="872" height="295" alt="image" src="https://github.com/user-attachments/assets/8c4f8186-2f91-45e5-bac1-1326d9d841c5" />                                                                                                                       |
|----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enlace de entrevista                 |     [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20191b935_upc_edu_pe/IQChHuiT1-8JSaoTC9wlJLdSAXJKJrRyMkud2BNbDADQBjM?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=pxN6XL](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20191b935_upc_edu_pe/IQChHuiT1-8JSaoTC9wlJLdSAXJKJrRyMkud2BNbDADQBjM?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=pxN6XL)                                                                                                                                                                                                                                                                 |
| Nombre de Entrevistado           | Emmanuel Ñahuiña                                                                                                                                                                                                                                                         |
| Edad                             | 23                                                                                                                                                                                                                                                                       |
| Profesión                        | Desarrollador frontend independiente                                                                                                                                                                                                                           |
| Distrito                         | Villa el salvador                                                                                                                                                                                                                                                                    |
| Duración de la Entrevista        | 00:00                                                                                                                                                                                                                                                                    |
| Minuto de inicio                 | 00:00                                                                                                                                                                                                                                                                    |
| **Análisis de la Entrevista**    |                                                                                                                                                                                                                                                                          |
|  Gestión de Equipos y Contratos             | Comenta que la visualización del catálogo de hardware y el estado de los planes de arrendamiento (Smart Leasing) es muy clara y limpia visualmente.                                                          |
| Soporte e Incidencias                | Considera sencillo reportar fallas de hardware y programar mantenimientos, pero sugiere agregar una leyenda o tooltip para identificar qué significa exactamente cada color en el estado del ticket (ej. si está "En atención" o "Pendiente de repuesto"). |
| Reportes y Optimización          | Argumenta que la sección de reportes de costos y rentabilidad es la más útil para él, ya que al trabajar independiente necesita justificar rápido que está optimizando el presupuesto y evitar la obsolescencia tecnológica.                |
| Solicitudes de Validación       | Menciona que la confirmación de contratos y renovación de planes está bien distribuida, pero añadiría un color de fondo sutil a las alertas críticas (como vencimientos de garantía) para que resalten más a primera vista.   |
| Navegación General               | Como desarrollador frontend, destaca que la interfaz es responsiva y se adapta bien al móvil para reportar incidencias en ruta. Siente que hay muchas opciones administrativas al inicio, pero la curva de aprendizaje es bastante corta e intuitiva.        |




<table> 
  <tbody> 
    <tr> 
      <td>Entrevista 2</td> 
      <td><img width="869" height="269" alt="image" src="https://github.com/user-attachments/assets/f10becdc-e9a4-4460-9186-e9f73ae1f457" />
</td>
    </tr> 
    <tr> 
      <td>Enlace a la entrevista</td> 
      <td> https://upcedupe-my.sharepoint.com/:v:/g/personal/u20191b935_upc_edu_pe/IQAFzHw2-eABQo0QQDoV1qO8AcrHQSFP35Mry2ZAaXNGOXc?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=f1QRnz </td>
    </tr> 
    <tr> 
      <td>Nombre Entrevistado</td> 
      <td>Oscar Román</td> 
    </tr> 
    <tr> 
      <td>Edad</td> 
      <td>24</td> 
    </tr> 
    <tr> 
      <td>Distrito</td> 
      <td>Chorrillos</td>
    </tr> 
    <tr> 
      <td>Ocupación</td> 
      <td>Estudiante de Ingeniería de Ciberseguridad</td> 
    </tr> 
    <tr> 
      <td>Duración Entrevista</td> 
      <td>06:12 minutos</td> 
    </tr> 
    <tr> 
      <td>Minuto de Inicio</td> 
      <td>0:00</td> 
    </tr> 
    <tr> 
      <td>Análisis</td> 
      <td>El entrevistado considera que la aplicación es <strong>segura, ordenada y de rápida respuesta</strong> para la gestión de activos tecnológicos. Destaca que la <strong>organización de contratos y control de hardware</strong> es altamente transparente, permitiendo mapear responsabilidades de TI sin complicaciones. Resalta que el <strong>diseño visual</strong> mediante colores e íconos facilita el reconocimiento inmediato de estados críticos en incidencias o mantenimientos preventivos. La <strong>navegación general</strong> entre el catálogo, los reportes financieros y las alertas le pareció fluida, valorando positivamente que los módulos de administración de sedes cuenten con una estructura limpia. Respecto a la consistencia, afirma que las confirmaciones ante acciones críticas (como la renovación de un plan) son claras y que la experiencia en la versión <strong>móvil es sólida</strong>, ideal para reportar incidencias de hardware en tiempo real. Como oportunidad de mejora desde su perspectiva técnica, propone <strong>fortalecer el feedback visual en las alertas críticas</strong> de garantías o vulnerabilidades de obsolescencia, utilizando notificaciones emergentes (pop-ups) más llamativas o colores de fondo de alta prioridad que obliguen a una atención inmediata del administrador. En conclusión, percibe la plataforma como un entorno <strong>confiable, robusto y muy amigable</strong> para mitigar riesgos logísticos y simplificar la gestión operativa de TI.</td> 
    </tr> 
  </tbody> 
</table>

### 6.3.3. Evaluaciones según heurísticas.

Esta sección analiza los hallazgos de las entrevistas aplicando los principios heurísticos de usabilidad. Permite identificar problemas y oportunidades de mejora en la experiencia del usuario.

**Aplicación para evaluar:** ECAT Leasing

**Tareas que evaluar:**
- Interpretar los colores y estados de los tickets de incidencia y mantenimiento técnico.
- Diferenciar entre el catálogo de "Hardware disponible" y las "Solicitudes de leasing activas".
- Configurar y cotizar un plan flexible según el presupuesto asignado.
- Navegar por la aplicación para acceder a contratos, sedes de la empresa, reportes y alertas.
- Comprender las métricas financieras de optimización de costos y obsolescencia tecnológica.
- Filtrar incidencias de hardware según estados específicos, incluyendo "Pendientes de repuesto" o "Garantías por vencer".
- Identificar claramente los mensajes de confirmación en acciones críticas (como dar de baja un equipo o renovar un contrato).
- Evaluar el contraste visual, legibilidad de etiquetas técnicas y visibilidad de alertas críticas de TI.
- Verificar la correcta adaptación del diseño responsivo en pantallas móviles para el reporte de incidencias in situ.
- Determinar la eficiencia del flujo de navegación y la reducción de pasos redundantes en la gestión operativa.

**Escala de severidad**

| Valor | Descripción   |
|-------|---------------|
| 1     | No tan grave  |
| 2     | Leve          |
| 3     | Moderado      |
| 4     | Grave         |
| 5     | Muy grave     |

**Tabla de resumen**

| #Orden | Problema                                                                                              | Escala de Severidad | Heurística / Principio violado(a)                                     |
|--------|-------------------------------------------------------------------------------------------------------|---------------------|-----------------------------------------------------------------------|
| 1      | Falta de leyenda explícita sobre el significado de los colores en el estado de incidencias y soporte. | 3                   | Visibilidad del estado del sistema                                    |
| 2      | Diferencia visual difusa entre la navegación de "Catálogo de Hardware" y "Solicitudes de Leasing".    | 4                   | Consistencia y estándares                                             |
| 3      | Desglose comercial poco técnico en las recomendaciones del cotizador inteligente de presupuesto.     | 2                   | Correspondencia entre el sistema y el mundo real                      |
| 4      | Interfaz inicial densa en opciones administrativas y ausencia de un onboarding o accesos rápidos.     | 3                   | Flexibilidad y eficiencia de uso / Ayuda y documentación              |
| 5      | Alertas críticas de soporte y vencimiento de garantías poco resaltadas en el dashboard.                | 4                   | Visibilidad del estado del sistema / Prevención de errores            |
| 6      | Falta de un filtro específico para equipos "Pendientes de validación de baja" o reemplazo.            | 3                   | Flexibilidad y eficiencia de uso / Visibilidad del estado del sistema |
| 7      | Formato visual del hilo de conversación con el soporte técnico poco diferenciado.                     | 2                   | Estética y diseño minimalista / Visibilidad del sistema               |
| 8      | Ausencia de un modal de confirmación con doble factor para la cancelación o baja definitiva de activos.| 3                   | Prevención de errores                                                 |
| 9      | Gráficos complejos de depreciación financiera con reducción extrema de legibilidad en móviles.        | 2                   | Diseño responsivo / Consistencia y estándares                         |
| 10     | Flujo de navegación extenso para registrar una incidencia urgente (demasiados clics previos).        | 3                   | Flexibilidad y eficiencia de uso                                      |

---

#### Problema #1: Falta de leyenda explícita sobre el significado de los colores en el estado de incidencias y soporte

**Heurística violada:** Visibilidad del estado del sistema.  

**Descripción del problema:** Varios entrevistados mencionan que los colores ayudan a interpretar estados y prioridades, pero no existe una leyenda explícita que explique qué significa cada color o umbral (por ejemplo, estados de tareas o niveles de desempeño). Esto obliga al usuario a “deducir” el significado y genera una pequeña curva de aprendizaje innecesaria.

**Recomendación:** Incorporar una leyenda fija (por ejemplo, en la parte superior derecha de la vista de tareas y de reportes) donde se explique el significado de cada color y estado. Además, añadir *tooltips* o ayudas contextuales que, al pasar el cursor o tocar un ícono de ayuda, muestren brevemente qué representa cada color y umbral de desempeño. Esto reduce la ambigüedad y mejora la comprensión inmediata del estado del sistema.

---

#### Problema #2: Diferencia visual difusa entre la navegación de "Catálogo de Hardware" y "Solicitudes de Leasing"

**Heurística violada:** Consistencia y estándares.  

**Descripción del problema:** Al menos un entrevistado reportó confusión inicial entre las secciones de “tareas” y “solicitudes”. Aunque ambas pantallas están ordenadas, la nomenclatura y el diseño visual no hacen suficientemente evidente que se trata de conceptos distintos (trabajo asignado vs. solicitudes de cambio, validaciones u otros tipos de requerimientos). Esto puede provocar errores de interpretación y uso.

**Recomendación:** Reforzar la diferenciación visual y textual entre “tareas” y “solicitudes”. Por ejemplo, usar íconos distintos, colores de fondo diferenciados y subtítulos breves en cada pantalla (p. ej. “Tareas: actividades pendientes que debes completar” y “Solicitudes: pedidos o validaciones que requieren tu respuesta”). También se recomienda incluir un mensaje introductorio corto la primera vez que el usuario ingresa a cada sección.

---

#### Problema #3: Desglose comercial poco técnico en las recomendaciones del cotizador inteligente de presupuesto

**Heurística violada:** Correspondencia entre el sistema y el mundo real.  

**Descripción del problema:** Un entrevistado indicó confusión respecto al código del grupo al visualizar los detalles; no era evidente que ese valor correspondía al código que se comparte para unirse al grupo. La falta de una etiqueta clara o subtítulo obliga al usuario a adivinar su propósito.

**Recomendación:** Añadir una etiqueta explícita como “Código del grupo (compártelo para que otros se unan)” junto al valor, y un pequeño ícono de copiar para facilitar su uso. Esto alinea mejor el lenguaje de la interfaz con el modelo mental del usuario y hace más clara la función de este elemento.

---

#### Problema #4: Interfaz inicial densa en opciones administrativas y ausencia de un onboarding o accesos rápidos

**Heurísticas violadas:** Flexibilidad y eficiencia de uso / Ayuda y documentación.  

**Descripción del problema:** Aunque los usuarios con algo de experiencia perciben la navegación como clara y concisa, se menciona que, para un usuario nuevo, la cantidad de pantallas y opciones puede sentirse un poco extensa al inicio. Actualmente no existe un onboarding breve ni ayudas contextuales que expliquen las secciones clave (grupos, tareas, solicitudes, desempeño, atajos). Esto genera una pequeña barrera de entrada antes de aprovechar plenamente las funcionalidades.

**Recomendación:** Implementar un recorrido guiado (*tour*) la primera vez que el usuario inicie sesión, destacando las secciones principales y su propósito. Complementar esto con breves textos “¿Qué puedes hacer aquí?” en las pantallas más importantes y con ayudas contextuales (íconos de “i” o “?”) que puedan consultarse en cualquier momento. De esta manera, se reduce la carga cognitiva inicial y se acelera la curva de aprendizaje.

---

#### Problema #5: Alertas críticas de soporte y vencimiento de garantías poco resaltadas en el dashboard

**Heurísticas violadas:** Visibilidad del estado del sistema / Prevención de errores.  

**Descripción del problema:** Los entrevistados reconocen que existen mensajes de confirmación cuando se crean, editan o eliminan elementos; sin embargo, señalan que podrían estar mejor resaltados para que el usuario los perceba con mayor claridad. Si la retroalimentación visual es sutil, es posible que algunos usuarios duden sobre si la acción se ejecutó correctamente.

**Recomendación:** Aumentar la visibilidad de las notificaciones de confirmación mediante el uso de *toasts* o banners más notorios (uso de íconos de éxito/error, tipografía ligeramente más grande y contraste adecuado). Para acciones críticas (como eliminar tareas o grupos), incluir además un cuadro de diálogo de confirmación claro, reduciendo así el riesgo de errores y mejorando la percepción de control sobre la plataforma.



---

<div align="center">

# Capítulo VII: DevOps Practices

</div>

---

## 7.1. Continuous Integration

El equipo de PCPedia adoptó Continuous Integration (CI) como práctica central del proceso de desarrollo, con el objetivo de detectar errores de integración de forma temprana y garantizar que cada cambio introducido en la rama principal produzca un artefacto compilable y desplegable. Dado que el sistema está compuesto por dos aplicaciones independientes —una API backend en Java y una SPA frontend en Angular—, el enfoque CI se implementó de forma diferenciada para cada capa, adaptando las herramientas al entorno tecnológico de cada una.

El backend emplea **GitHub Actions** como motor de CI/CD, con un workflow definido en `.github/workflows/main_pcpediaapi.yml` que se dispara automáticamente ante cada push a la rama `main` o manualmente mediante `workflow_dispatch`. El frontend delega el proceso de integración y despliegue a **Netlify**, plataforma que detecta automáticamente los cambios en el repositorio y ejecuta el proceso de build sin necesidad de configuración adicional de pipeline.

Ambas estrategias siguen el principio de integración continua basada en trunk, donde `main` es la rama de entrega y todo cambio fusionado en ella desencadena el proceso de verificación y despliegue.

---

### 7.1.1. Tools and Practices

#### Backend — PCPedia API

| Herramienta / Práctica | Rol en el pipeline |
|---|---|
| **GitHub Actions** | Motor de CI/CD. Orquesta los jobs de build y deploy. |
| **Java 21** (distribución Microsoft) | Entorno de ejecución configurado en el runner `ubuntu-latest` mediante `actions/setup-java@v4`. |
| **Apache Maven** | Herramienta de build. Ejecuta `mvn clean package` para compilar y empaquetar el proyecto como JAR ejecutable. |
| **GitHub Artifacts** (`actions/upload-artifact`) | Mecanismo de traspaso del JAR generado en el job `build` hacia el job `deploy`, garantizando inmutabilidad del artefacto. |
| **Trigger en `main`** | Todo push a la rama `main` activa el workflow, alineando CI con el flujo trunk-based. |

**Prácticas aplicadas:**

- **Build verification en cada integración:** el job `build` compila el proyecto completo con `mvn clean package`, asegurando que el código fusionado en `main` es siempre compilable.
- **Separación de jobs:** los jobs `build` y `deploy` están desacoplados y encadenados mediante dependencia explícita (`needs: build`), lo que permite identificar con precisión en qué etapa falla el pipeline.
- **Artefacto inmutable:** el JAR producido en build se sube como artifact y el job de deploy lo descarga, garantizando que lo que se compila es exactamente lo que se despliega.

> **Punto de mejora identificado:** actualmente el pipeline ejecuta `mvn clean package -DskipTests`, omitiendo la ejecución de tests en el proceso de CI. Como acción de mejora para TB2, el equipo tiene previsto habilitar la ejecución de tests y ampliar la suite de pruebas unitarias e de integración.

---

#### Frontend — PCPedia Web Application

| Herramienta / Práctica | Rol en el pipeline |
|---|---|
| **Netlify** | Plataforma CI/CD para el frontend. Detecta cambios en el repositorio y ejecuta el build automáticamente. |
| **Angular CLI / `ng build`** | Compilador del proyecto Angular. Invocado mediante `npm run build`, genera el bundle optimizado de producción. |
| **`netlify.toml`** | Archivo de configuración declarativa del pipeline: define el comando de build, el directorio de publicación y las reglas de redirección SPA. |
| **Node.js / npm** | Gestor de dependencias y entorno de ejecución para Angular. |

**Prácticas aplicadas:**

- **Build declarativo:** la configuración en `netlify.toml` documenta explícitamente el comando de build (`npm run build`) y el directorio de salida (`dist/pcpedia/browser`), haciendo el proceso reproducible y auditable.
- **SPA redirect:** la regla `/* → /index.html` garantiza que las rutas del router de Angular se resuelvan correctamente desde cualquier URL de acceso directo.
- **Deploy automático desde el repositorio:** Netlify monitorea el repositorio y dispara el pipeline sin intervención manual ante cada push a la rama principal.

---

### 7.1.2. Build & Test Suite Pipeline Components

#### Backend Pipeline — Diagrama de jobs

```
Push a main / workflow_dispatch
│
▼
┌─────────────────────────────────────────┐
│              JOB: build                  │
│  Runner: ubuntu-latest                   │
│                                          │
│  1. actions/checkout@v4                  │
│  2. actions/setup-java@v4 (Java 21,      │
│     distribución Microsoft)              │
│  3. mvn clean package -DskipTests        │
│     → Genera: target/*.jar               │
│  4. actions/upload-artifact              │
│     → Sube: .java-app/                  │
└─────────────────┬───────────────────────┘
                  │ needs: build
                  ▼
┌─────────────────────────────────────────┐
│              JOB: deploy                 │
│  Runner: ubuntu-latest                   │
│                                          │
│  1. actions/download-artifact            │
│     → Descarga: .java-app/              │
│  2. azure/login@v2                       │
│     (OIDC / Workload Identity            │
│      Federation)                         │
│  3. azure/webapps-deploy@v3             │
│     → App: pcpediaapi                   │
│     → Slot: Production                  │
└─────────────────────────────────────────┘
```

#### Backend — Test Suite (estado actual)

| Componente | Estado |
|---|---|
| Framework de testing | Spring Boot Test (JUnit 5, integrado via `spring-boot-starter-test`) |
| Archivo de test existente | `PcPediaApplicationTests.java` — verifica únicamente que el contexto de Spring carga correctamente (`contextLoads()`) |
| Tests unitarios | No implementados aún |
| Tests de integración | No implementados aún |
| Ejecución en CI | Deshabilitada (`-DskipTests`) |

#### Frontend Pipeline — Flujo Netlify

```
Push al repositorio
│
▼
┌─────────────────────────────────────────┐
│           Netlify Build Runner           │
│                                          │
│  1. Detección de cambios en el repo      │
│  2. Instalación de dependencias          │
│     → npm install                        │
│  3. Build de producción                  │
│     → npm run build (ng build)           │
│     → Output: dist/pcpedia/browser/      │
│  4. Publicación en CDN de Netlify        │
│  5. Aplicación de redirects SPA          │
│     /* → /index.html (HTTP 200)          │
└─────────────────────────────────────────┘
```

#### Frontend — Test Suite (estado actual)

| Componente | Estado |
|---|---|
| Framework de testing | Karma 6.4 + Jasmine 5.1 (configurado por Angular CLI) |
| Archivos `.spec.ts` | No implementados aún — stack instalado pero sin casos de prueba escritos |
| Ejecución en CI | No configurada |

---

## 7.2. Continuous Delivery

PCPedia implementa Continuous Delivery como extensión natural del pipeline de CI, asegurando que todo artefacto que supera el proceso de build en la rama `main` sea desplegado automáticamente en el entorno de producción, sin intervención manual adicional. Esta práctica garantiza que la versión disponible para los usuarios finales refleja siempre el estado más reciente y verificado del código.

El modelo de entrega continua del equipo opera sobre dos plataformas diferenciadas según la capa del sistema: **Azure App Service** para el backend y **Netlify** para el frontend, cada una integrada directamente con el repositorio de código fuente correspondiente.

---

### 7.2.1. Tools and Practices

#### Backend — Continuous Delivery a Azure App Service

| Herramienta / Práctica | Descripción |
|---|---|
| **Azure App Service** | Plataforma PaaS donde se ejecuta la API. La aplicación se denomina `pcpediaapi` y opera en el slot `Production`. |
| **`azure/webapps-deploy@v3`** | GitHub Action oficial de Microsoft para el despliegue de aplicaciones web en Azure. Recibe el JAR como input y lo publica en el App Service. |
| **OIDC / Workload Identity Federation** | Mecanismo de autenticación sin secretos de larga duración. El workflow se autentica en Azure mediante tres secrets (`AZUREAPPSERVICE_CLIENTID`, `AZUREAPPSERVICE_TENANTID`, `AZUREAPPSERVICE_SUBSCRIPTIONID`), siguiendo las mejores prácticas de seguridad en pipelines. |
| **`azure/login@v2`** | Action que gestiona el login federado con Azure antes del deploy. |
| **Despliegue de JAR directo** | El artefacto deployado es el JAR empaquetado por Maven. No se utiliza contenedorización; Azure App Service gestiona el entorno de ejecución Java nativo. |

**Prácticas de CD aplicadas:**

- **Despliegue automatizado sin intervención manual:** todo push a `main` que supere el job `build` desencadena automáticamente el job `deploy`, eliminando pasos manuales en el proceso de entrega.
- **Autenticación federada (OIDC):** el uso de Workload Identity Federation evita el almacenamiento de credenciales de larga duración en el repositorio, alineando el pipeline con las recomendaciones de seguridad de la industria (DevSecOps).
- **Artefacto único e inmutable:** el JAR producido en el job `build` es el mismo que se descarga y despliega en el job `deploy`, garantizando que el entorno de producción ejecuta exactamente lo que fue compilado y verificado.
- **Slot de producción directo:** el deploy apunta al slot `Production` del App Service, haciendo que los cambios sean inmediatamente visibles para los usuarios finales tras cada integración exitosa.

---

#### Frontend — Continuous Delivery a Netlify

| Herramienta / Práctica | Descripción |
|---|---|
| **Netlify** | Plataforma de hosting y CD para la SPA de Angular. Gestiona build, distribución en CDN global y configuración de dominios. |
| **Deploy automático desde repositorio** | Netlify monitorea el repositorio y desencadena el pipeline completo (build + deploy) sin pasos adicionales de configuración. |
| **CDN global** | El bundle de producción (`dist/pcpedia/browser`) se distribuye en la red de CDN de Netlify, garantizando baja latencia para usuarios en distintas ubicaciones geográficas. |
| **Configuración declarativa (`netlify.toml`)** | El archivo de configuración define de forma explícita y versionada el comando de build, el directorio de publicación y las reglas de redirección. |

**Prácticas de CD aplicadas:**

- **GitOps implícito:** el repositorio es la fuente de verdad del estado del entorno de producción. Cualquier cambio fusionado en la rama principal se refleja automáticamente en producción.
- **Configuración como código:** el `netlify.toml` versionado en el repositorio documenta el proceso de entrega de forma reproducible y auditable.
- **SPA routing en producción:** la regla de redirección `/* → /index.html` garantiza que el router de Angular funcione correctamente en producción para cualquier ruta de navegación directa.

---

#### Resumen del flujo completo CI/CD — PCPedia

```
Desarrollador hace push a main
│
├──────────────────────────────────────────────────────┐
│                                                        │
▼  (Backend)                                             ▼  (Frontend)
GitHub Actions dispara                                  Netlify detecta
workflow CI/CD                                          cambio en repo
│                                                        │
▼                                                        ▼
JOB: build                                             npm install
mvn clean package                                      npm run build
→ JAR generado                                         → dist/pcpedia/browser/
│                                                        │
▼                                                        ▼
JOB: deploy                                            Publicación en CDN
azure/webapps-deploy                                   Netlify (global)
→ Azure App Service                                             │
pcpediaapi / Production                                       ▼
│                                              Frontend disponible
▼                                              en producción
API disponible en
producción (Azure)
```

| Componente | Entorno | Plataforma | Trigger |
|---|---|---|---|
| PCPedia API (Backend) | Production | Azure App Service | Push a `main` (GitHub Actions) |
| PCPedia Web App (Frontend) | Production | Netlify (CDN global) | Push a `main` (Netlify auto-deploy) |

---

### 7.2.2. Stages Deployment Pipeline Components

- **Build Backend:** Compilación del proyecto Java con Maven mediante **mvn clean package**, generando el archivo JAR ejecutable.

- **Upload Backend Artifact:** Subida del JAR generado como artefacto mediante `actions/upload-artifact`, asegurando que el mismo archivo compilado sea usado en el despliegue.

- **Azure Login:** Autenticación segura en Azure mediante `azure/login@v2` usando OIDC / Workload Identity Federation.

- **Deploy Backend:** Despliegue automático del JAR en Azure App Service utilizando `azure/webapps-deploy@v3`, apuntando al servicio `pcpediaapi` en el slot Production.

- **Build Frontend:** Ejecución automática del build de Angular en Netlify mediante `npm install` y `npm run build`, generando el bundle en `dist/pcpedia/browser`.

- **Deploy Frontend:** Publicación automática del frontend en la CDN global de Netlify, aplicando las reglas de redirección SPA definidas en `netlify.toml`.

- **Production Validation:** Verificación de disponibilidad del backend en Azure y del frontend en Netlify después del despliegue exitoso.

### 7.3 Continuous deployment

#### 7.3.1 Tools and Practices

El despliegue continuo de PCPedia hacia producción se encuentra automatizado mediante plataformas cloud integradas con el repositorio principal, permitiendo publicar cambios de manera rápida, controlada y segura.

- **Backend:** Al realizar un merge hacia la rama `main`, GitHub Actions ejecuta automáticamente el pipeline de build y despliegue. El artefacto JAR generado es publicado directamente en Azure App Service (`pcpediaapi`) mediante `azure/webapps-deploy@v3`, dejando disponible la API en producción sin intervención manual.

- **Frontend:** Netlify monitorea continuamente el repositorio del frontend y, ante cada push a `main`, ejecuta automáticamente `npm install` y `npm run build`. Posteriormente, publica el bundle optimizado en su CDN global, actualizando la aplicación web en producción.

- **Production Environment:** Azure App Service gestiona el entorno de ejecución Java del backend, mientras que Netlify administra el hosting y distribución global del frontend Angular, garantizando disponibilidad y baja latencia.

- **Rollback:** En el backend, Azure App Service permite revertir rápidamente a una versión anterior del despliegue en caso de fallo crítico. En el frontend, Netlify mantiene un historial de deploys, permitiendo restaurar versiones previas de la aplicación de forma inmediata.

- **Continuous Monitoring:** Después de cada despliegue, el equipo valida el acceso a los endpoints REST mediante Swagger y verifica el correcto funcionamiento del frontend desplegado en producción.

#### 7.3.2 Production Deployment Pipeline Components.

- **Activator:** El pipeline de producción se activa cuando se realiza un push o merge hacia la rama `main`.

- **Backend Build:** GitHub Actions compila el backend Java con Maven usando `mvn clean package`, generando el archivo JAR ejecutable.

- **Backend Artifact:** El JAR generado se guarda como artefacto del pipeline para asegurar que el mismo archivo compilado sea utilizado en el despliegue.

- **Backend Deployment:** El artefacto del backend se despliega automáticamente en Azure App Service mediante `azure/webapps-deploy@v3`, actualizando la API `pcpediaapi` en producción.

- **Frontend Build:** Netlify detecta los cambios en el repositorio del frontend, instala dependencias con `npm install` y genera el build de producción con `npm run build`.

- **Frontend Deployment:** El bundle generado en `dist/pcpedia/browser` se publica automáticamente en la CDN global de Netlify.

- **Production Validation:** Luego del despliegue, se valida que el backend responda correctamente desde Swagger y que el frontend esté disponible en su URL de producción.
---

### 7.4 Continuous Monitoring

#### 7.4.1. Tools and Practices

Las herramientas y prácticas adoptadas para llevar a cabo un monitoreo continuo y eficaz en
PcPedia son las siguientes:
- **Monitoreo de disponibilidad y endpoints REST:** Swagger UI, accesible en la URL de producción de Azure, permite al equipo verificar en tiempo real que los endpoints del backend están respondiendo correctamente. Tras cada despliegue, se valida manualmente el acceso a las rutas principales del API.

- **Monitoreo de la experiencia del usuario:** Google Analytics puede integrarse en el frontend Angular para recopilar datos sobre la navegación, tiempos de carga y tasas de retención. Esto permite identificar secciones de la plataforma que generan fricción en el flujo de los usuarios (clientes y administradores de EcatLeasing).

- **Supervisión de infraestructura en la nube:** Azure App Service proporciona métricas nativas de uso de CPU, memoria, tiempo de respuesta y tasas de error del backend. Railway ofrece un panel de métricas básicas para la base de datos MySQL. Ambas plataformas permiten configurar alertas ante comportamientos anómalos.

- **Pruebas de disponibilidad y latencia:** Herramientas como Pingdom o UptimeRobot pueden utilizarse para monitorear la disponibilidad del frontend en Netlify y del backend en Azure,enviando notificaciones ante caídas o tiempos de respuesta superiores a umbrales definidos.

- **Auditorías de calidad web:** Google Lighthouse se emplea para auditar el frontend desplegado en Netlify, analizando rendimiento, accesibilidad, buenas prácticas y SEO. Esto asegura que la plataforma mantenga estándares de calidad consistentes entre despliegues.


#### 7.4.2. Monitoring Pipeline Components

Un pipeline de monitoreo constante integra diversas etapas que ayudan a mantener la calidad y el rendimiento de PcPedia en producción. Estas etapas incluyen la recopilación de datos, el almacenamiento, el análisis y la visualización. Herramientas como Google Lighthouse y Azure Monitor juegan un papel fundamental en este proceso, ofreciendo evaluaciones complementarias que permiten entender y mejorar la experiencia del usuario.

 Google Lighthouse es ideal para realizar auditorías de calidad en el frontend de PcPedia desplegado en Netlify, proporcionando análisis detallados de accesibilidad, buenas prácticas, SEO y rendimiento de la SPA Angular. Esta herramienta permite al equipo identificar problemas que impactan la experiencia del usuario, tales como tiempos de carga elevados, tamaño excesivo del bundle de producción y cambios de diseño inesperados entre despliegues. Su integración en el flujo post-deploy asegura que cada versión publicada cumpla con los estándares de calidad definidos por el equipo.
 
  Azure Monitor se especializa en el monitoreo del backend desplegado en Azure App Service, ofreciendo datos en tiempo real sobre la latencia de respuesta del servidor, el uso de CPU y memoria del contenedor Java, la tasa de errores HTTP y el rendimiento de las conexiones con la base de datos MySQL en Railway. Su enfoque en la supervisión continua de la infraestructura permite al equipo detectar y resolver problemas antes de que afecten al usuario final. Complementado con los logs del servicio pcpediaapi, Azure Monitor proporciona trazabilidad completa del comportamiento del sistema ante picos de carga o fallos en el pipeline de entrega.


#### 7.4.3. Alerting Pipeline Components

El sistema de alertas de PcPedia está diseñado para notificar al equipo de forma inmediata ante eventos críticos que puedan afectar la disponibilidad o el rendimiento del servicio Smart Leasing.

- **Azure Alerts:** Azure App Service permite configurar alertas basadas en umbrales de métricas clave, como tiempo de respuesta superior a 3 segundos, tasa de errores HTTP 5xx mayor al 5%, o uso de CPU por encima del 80%. Estas alertas pueden enrutarse hacia correo electrónico o canales de mensajería del equipo, garantizando una respuesta oportuna ante incidentes.

 - **Railway Notifications:** Railway puede configurarse para notificar al equipo cuando el uso de la base de datos supera los límites del plan o cuando se detectan fallas en la conexión. Esto es crítico dado que la persistencia de usuarios, equipos, contratos e incidencias depende directamente de la disponibilidad de MySQL. • Netlify Deploy Notifications: Netlify genera notificaciones automáticas ante fallos en el proceso de build del frontend. El equipo recibe alertas cuando un push a main produce un error de compilación Angular, evitando que una versión rota llegue a producción sin detección inmediata. 
 
 -  **UptimeRobot / Pingdom:** Configurados para verificar periódicamente (cada 5 minutos) la disponibilidad del frontend en Netlify y del endpoint base del backend en Azure. Ante una caída, el sistema envía alertas inmediatas al equipo, permitiendo iniciar el proceso de diagnóstico y rollback sin demora. 
 
 La integración de estas herramientas asegura que el equipo pueda detectar y responder proactivamente a incidentes, minimizando el tiempo de inactividad del servicio y preservando la experiencia del cliente.

#### 7.4.4. Notification Pipeline Components. 

El pipeline de notificaciones de PcPedia centraliza la comunicación automática sobre el estado de los despliegues, la disponibilidad del sistema y el resultado de las validaciones post-deploy, asegurando que todo el equipo esté informado ante cualquier evento relevante.

 - **GitHub Actions — Notificaciones de pipeline:** GitHub Actions notifica automáticamente al equipo cuando un workflow falla en cualquiera de sus etapas (build o deploy). Los miembros del repositorio reciben notificaciones por correo electrónico ante fallos en la rama main, lo que permite una respuesta inmediata para diagnosticar el error y aplicar una corrección. 
 
 - **Azure App Service — Notificaciones de despliegue:** El portal de Azure registra un historial detallado de cada despliegue del backend, incluyendo el estado (éxito o fallo), el tiempo de ejecución y los logs del contenedor. En caso de fallo, Azure puede configurarse para enviar notificaciones al equipo vía correo electrónico o webhooks hacia canales de mensajería como Microsoft Teams. 
 
 -  **Netlify — Build Notifications:** Netlify genera notificaciones automáticas al finalizar cada proceso de build del frontend, informando sobre el éxito o fallo de la compilación Angular. Estas notificaciones incluyen el tiempo de build y el enlace al deploy generado, facilitando la validación inmediata de la versión publicada.
 
 - **Protocolo interno de notificación:** El equipo mantiene un canal de comunicación en Discord donde se comparten los resultados de cada ciclo de despliegue, incluyendo capturas de la validación de Swagger, confirmación del acceso al frontend y cualquier incidencia detectada durante las pruebas manuales post-deploy. Este protocolo asegura trazabilidad y coordinación entre los integrantes durante el ciclo de entrega continua.

---


<div align="center">

# Capítulo VIII: Experiment-Driven Development

</div>

---

### 8.1  Experiment Planning

#### 8.1.1. As-Is Summary

Nuestra plataforma, está diseñada para gestionar servicios de arrendamiento tecnológico dirigidos a empresas e instituciones educativas. Actualmente, cuenta con funcionalidades como autenticación de usuarios, catálogo de equipos, administración de contratos, registro de incidencias, gestión de pagos y control de activos tecnológicos. Su interfaz frontend fue desarrollada en Angular y se encuentra alojada en Netlify, mientras que el backend utiliza Java con Spring Boot desplegado en Azure App Service, apoyándose en una base de datos MySQL alojada en Railway.

### Situación actual de la plataforma

La solución permite a los clientes consultar el catálogo de equipos disponibles, administrar sus contratos vigentes, reportar problemas técnicos y monitorear el estado de sus pagos. No obstante, se han identificado algunos aspectos susceptibles de mejora:

* **Desempeño:** Algunas secciones, especialmente aquellas relacionadas con reportes y visualización gráfica de activos, presentan tiempos de carga superiores a tres segundos en conexiones de baja velocidad, lo que impacta negativamente la experiencia del usuario.
* **Experiencia de usuario:** La plataforma carece de un proceso de introducción o guía interactiva para usuarios nuevos, dificultando la familiarización con módulos como Contratos, Informes y Perfil.
* **Atención de incidencias:** El proceso para registrar problemas técnicos implica varios pasos previos antes de acceder al formulario principal, lo que puede resultar poco práctico en situaciones que requieren atención inmediata.
* **Escasa personalización:** Actualmente no existen mecanismos de notificación automática que informen a los usuarios sobre vencimientos de contratos, renovaciones próximas o mantenimientos programados.
* **Análisis financiero limitado:** Los reportes muestran información básica sobre los activos, pero no incluyen indicadores comparativos que permitan evaluar los beneficios económicos del arrendamiento frente a la adquisición directa de equipos.

### Oportunidades de mejora

Con el fin de optimizar la plataforma y mejorar la satisfacción de los usuarios, se plantean los siguientes objetivos:

* Disminuir los tiempos de carga del módulo de reportes a menos de dos segundos mediante la optimización de consultas y la implementación de técnicas como lazy loading.
* Incorporar un sistema de notificaciones inteligentes que informe oportunamente sobre vencimientos contractuales y mantenimientos programados.
* Agilizar el proceso de reporte de incidencias reduciendo la cantidad de pasos requeridos para registrar solicitudes urgentes.
* Implementar un panel de control con indicadores comparativos que permitan visualizar el ahorro acumulado obtenido mediante el modelo de arrendamiento.
* Desarrollar un sistema de onboarding interactivo que facilite la adaptación y aprendizaje de los nuevos usuarios dentro de la plataforma.
---

<div align="center">

# Capítulo VIII: Experiment-Driven Development

</div>

---

## 8.1. Experiment Planning

La planificación experimental de PcPedia transforma incertidumbres sobre el comportamiento y las necesidades de los usuarios en preguntas que puedan responderse con evidencia. Para esta etapa se recopilan supuestos, vacíos de conocimiento, ideas y afirmaciones relacionados con tres oportunidades de mejora: la recomendación de equipos, la comparación transparente de planes y el seguimiento de incidencias.

### 8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims

La materia prima se obtuvo de los artefactos de requisitos, los flujos actuales del producto y los problemas observados durante la validación. Cada elemento se redactó sin asumir que representa un hecho comprobado.

| ID | Tipo | Materia prima | Oportunidad de aprendizaje |
|:---:|:---|:---|:---|
| RM01 | Assumption | Los usuarios con poco conocimiento técnico tardan más en elegir un equipo adecuado. | Comprobar si una recomendación guiada reduce el tiempo de selección. |
| RM02 | Assumption | Mostrar demasiadas especificaciones técnicas incrementa la carga cognitiva. | Identificar qué información es indispensable para decidir. |
| RM03 | Assumption | Los usuarios confían más en una recomendación cuando pueden conocer los criterios utilizados. | Evaluar la importancia de explicar el motivo de cada recomendación. |
| RM04 | Knowledge Gap | No se conoce cuánto tiempo necesita actualmente un usuario para seleccionar un equipo. | Establecer una línea base de tiempo y errores de selección. |
| RM05 | Knowledge Gap | No se sabe si los usuarios comprenden el costo total y las condiciones de cada plan. | Medir comprensión de precios, duración y servicios incluidos. |
| RM06 | Knowledge Gap | No se conoce con qué frecuencia un cliente contacta a soporte solo para consultar el estado de una incidencia. | Estimar consultas evitables y necesidades de seguimiento. |
| RM07 | Idea | Incorporar un asistente que recomiende equipos según presupuesto, uso y rendimiento esperado. | Comparar la selección guiada con la navegación convencional. |
| RM08 | Idea | Presentar una comparación resumida de planes con costo total, beneficios y restricciones. | Evaluar si la tabla facilita decisiones correctas y transparentes. |
| RM09 | Idea | Añadir una línea de tiempo de incidencias con estado, responsable y próxima actualización. | Evaluar si el seguimiento reduce incertidumbre y consultas repetitivas. |
| RM10 | Claim | La recomendación automatizada permitirá elegir equipos más rápido y con mayor confianza. | Cuantificar el cambio en tiempo y confianza percibida. |
| RM11 | Claim | Una comparación transparente aumentará la comprensión de los planes de leasing. | Medir respuestas correctas sobre costos y condiciones. |
| RM12 | Claim | Visualizar el avance de una incidencia reducirá los contactos de seguimiento a soporte. | Comparar la cantidad de consultas con y sin trazabilidad visible. |

### 8.1.3. Experiment-Ready Questions

Los elementos anteriores se convirtieron en preguntas mediante 5W+2H (What, Why, Who, Where, When, How y How much). Las preguntas se mantienen neutrales para evitar dirigir el resultado y se clasifican como exploratorias o basadas en una creencia previa.

| ID | Origen | Pregunta preparada para experimentar | Tipo | Valor de la respuesta |
|:---:|:---:|:---|:---:|:---|
| Q01 | RM01, RM04, RM07, RM10 | ¿Cómo cambia el tiempo que requieren los responsables de TI de pequeñas organizaciones para elegir un equipo cuando usan una recomendación guiada en PcPedia, frente al catálogo convencional, durante una tarea de selección con presupuesto limitado? | Belief-led | Determinar si se debe priorizar el asistente de recomendación. |
| Q02 | RM05, RM08, RM11 | ¿En qué medida una comparación que muestre costo total, duración, beneficios y restricciones mejora la comprensión de los planes de leasing durante la evaluación de alternativas? | Belief-led | Definir la presentación de precios y condiciones. |
| Q03 | RM06, RM09, RM12 | ¿Cuántas consultas de seguimiento a soporte podrían evitar los clientes si PcPedia mostrara el estado, responsable y próxima actualización de cada incidencia? | Belief-led | Decidir si la trazabilidad debe formar parte del flujo principal. |
| Q04 | RM02 | ¿Qué especificaciones consultan primero los usuarios y cuáles omiten cuando comparan equipos para una necesidad concreta? | Exploratory | Simplificar las fichas sin eliminar información relevante. |
| Q05 | RM03 | ¿Por qué y en qué momento los usuarios necesitan conocer los criterios que originaron una recomendación de equipo? | Exploratory | Diseñar explicaciones que generen confianza sin saturar la interfaz. |
| Q06 | RM04 | ¿Dónde se producen más abandonos o retrocesos durante el recorrido actual de búsqueda, comparación y selección? | Exploratory | Localizar los puntos de fricción del flujo vigente. |
| Q07 | RM05 | ¿Qué términos relacionados con leasing, costos y condiciones generan más interpretaciones incorrectas? | Exploratory | Mejorar etiquetas y contenido de ayuda contextual. |
| Q08 | RM06 | ¿Cuándo considera un cliente que ha esperado demasiado tiempo sin recibir información sobre una incidencia? | Exploratory | Establecer expectativas y frecuencia de notificaciones. |

### 8.1.4. Question Backlog

Las preguntas se priorizan en una escala de 1 a 5. Una puntuación mayor representa mayor respaldo preliminar de la creencia en **Confidence**, mayor exposición si la decisión resulta incorrecta en **Risk**, mayor efecto esperado en usuarios o negocio en **Impact**, y mayor valor de aprendizaje en **Interest**. El puntaje máximo es 20.

| Prioridad | ID | Confidence | Risk | Impact | Interest | Total | Estado |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| 1 | Q01 | 5 | 5 | 5 | 5 | 20 | Seleccionada |
| 2 | Q02 | 4 | 5 | 5 | 5 | 19 | Seleccionada |
| 3 | Q03 | 4 | 4 | 5 | 5 | 18 | Seleccionada |
| 4 | Q05 | 4 | 4 | 4 | 5 | 17 | Backlog |
| 5 | Q04 | 3 | 4 | 4 | 5 | 16 | Backlog |
| 6 | Q06 | 3 | 4 | 4 | 4 | 15 | Backlog |
| 7 | Q07 | 3 | 3 | 4 | 4 | 14 | Backlog |
| 8 | Q08 | 3 | 3 | 3 | 4 | 13 | Backlog |

### 8.1.5. Experiment Cards

Las tres preguntas con mayor puntuación se desarrollan mediante Experiment Cards. Los criterios de éxito se establecen antes de recopilar datos para evitar reinterpretar los resultados según las expectativas del equipo.

#### Experiment Card EC01: Recomendación guiada de equipos

| Campo | Definición |
|:---|:---|
| **Question** | ¿Cómo cambia el tiempo de selección cuando se utiliza una recomendación guiada en lugar del catálogo convencional? |
| **Why** | Una selección lenta o incorrecta puede ocasionar abandono, sobrecostos y adquisición de equipos que no responden a la necesidad real. |
| **Hypothesis** | La recomendación guiada reducirá al menos 20% la mediana del tiempo de selección respecto del catálogo convencional. |
| **Simplest useful thing / What** | Prototipo navegable que solicita presupuesto, tipo de uso y rendimiento, y devuelve tres alternativas justificadas. |
| **Method** | Prueba comparativa intra-sujeto: cada participante completa una tarea con el catálogo y otra equivalente con el asistente; el orden se asigna aleatoriamente. |
| **Measures** | Tiempo hasta seleccionar un equipo, cantidad de retrocesos, adecuación de la elección al escenario y confianza declarada de 1 a 5. |
| **Conditions** | Mismos escenarios, presupuesto, catálogo y dispositivo; instrucciones neutrales y sin ayuda del moderador durante la tarea. |
| **Scale** | 20 responsables o usuarios que participen en decisiones tecnológicas de pequeñas empresas o instituciones educativas. |
| **Decision rule** | Priorizar el asistente si reduce la mediana del tiempo al menos 20% sin disminuir la adecuación de la elección. |
| **Ethics** | Consentimiento informado, datos anonimizados y posibilidad de abandonar la prueba sin consecuencias. |

#### Experiment Card EC02: Comparación transparente de planes

| Campo | Definición |
|:---|:---|
| **Question** | ¿En qué medida una comparación detallada mejora la comprensión de los planes de leasing? |
| **Why** | Una interpretación equivocada del costo o las restricciones afecta la confianza y puede originar decisiones económicas inadecuadas. |
| **Hypothesis** | La nueva comparación incrementará en más de 15 puntos porcentuales la proporción de usuarios que identifica correctamente el costo total del plan. |
| **Simplest useful thing / What** | Dos variantes de una pantalla: presentación actual y tabla comparativa con costo total, duración, servicios, restricciones y ayuda contextual. |
| **Method** | Prueba A/B moderada con asignación aleatoria; cada participante responde el mismo cuestionario de comprensión después de revisar una variante. |
| **Measures** | Porcentaje de respuestas correctas, tiempo de decisión, dudas expresadas e intención de solicitar información. |
| **Conditions** | Mismos planes, precios, textos base, dispositivo y límite de tiempo; solo cambia la organización de la información. |
| **Scale** | 20 participantes, distribuidos equitativamente entre las variantes A y B. |
| **Decision rule** | Adoptar la tabla si la comprensión correcta aumenta más de 15 puntos porcentuales y el tiempo no empeora más de 10%. |
| **Ethics** | Usar precios ficticios claramente identificados y no recopilar datos financieros personales. |

#### Experiment Card EC03: Seguimiento visible de incidencias

| Campo | Definición |
|:---|:---|
| **Question** | ¿Cuántas consultas de seguimiento pueden evitarse al mostrar el avance de una incidencia? |
| **Why** | La falta de información genera incertidumbre para el cliente y carga operativa innecesaria para soporte. |
| **Hypothesis** | Una línea de tiempo visible reducirá al menos 25% la mediana de consultas de estado realizadas durante un escenario de soporte. |
| **Simplest useful thing / What** | Prototipo de detalle de incidencia con estado, responsable, historial, próxima actualización y opción de notificación. |
| **Method** | Simulación comparativa intra-sujeto con dos incidencias equivalentes: una con información básica y otra con trazabilidad completa. |
| **Measures** | Cantidad de intentos de contacto, tiempo para encontrar el estado, comprensión del siguiente paso y confianza percibida. |
| **Conditions** | Mismo tiempo de espera simulado, severidad y dispositivo; el orden de las variantes se contrabalancea. |
| **Scale** | 20 usuarios que hayan solicitado soporte técnico o gestionado incidencias tecnológicas. |
| **Decision rule** | Priorizar la trazabilidad si reduce las consultas al menos 25% y 80% de participantes identifica el estado en 30 segundos o menos. |
| **Ethics** | Casos ficticios, sin datos reales de tickets ni información identificable de clientes. |

## 8.2. Experiment Design

El diseño experimental convierte las tres preguntas priorizadas en proposiciones falsables. Cada hipótesis establece una variable independiente, una métrica principal y un umbral de decisión que permite confirmar o rechazar la expectativa del equipo con los datos obtenidos.

### 8.2.1. Hypotheses

#### H01: Recomendación guiada y tiempo de selección

- **Variable independiente:** flujo de selección utilizado (catálogo convencional o recomendación guiada).
- **Variable dependiente:** mediana del tiempo requerido para seleccionar un equipo adecuado.
- **Hipótesis nula (H0₁):** la mediana del tiempo con recomendación guiada es mayor o igual al 80% de la mediana obtenida con el catálogo convencional; por lo tanto, la reducción es menor al 20%.
- **Hipótesis alternativa (H1₁):** la mediana del tiempo con recomendación guiada es menor al 80% de la mediana obtenida con el catálogo convencional; por lo tanto, la reducción es de al menos 20%.

#### H02: Comparación de planes y comprensión del costo total

- **Variable independiente:** presentación de los planes (actual o tabla comparativa transparente).
- **Variable dependiente:** proporción de participantes que identifica correctamente el costo total del plan.
- **Hipótesis nula (H0₂):** la proporción de respuestas correctas con la tabla comparativa no supera en más de 15 puntos porcentuales la obtenida con la presentación actual.
- **Hipótesis alternativa (H1₂):** la proporción de respuestas correctas con la tabla comparativa supera en más de 15 puntos porcentuales la obtenida con la presentación actual.

#### H03: Trazabilidad de incidencias y consultas de seguimiento

- **Variable independiente:** nivel de información visible de la incidencia (información básica o línea de tiempo completa).
- **Variable dependiente:** mediana de intentos de contacto o consultas de estado durante el escenario.
- **Hipótesis nula (H0₃):** la mediana de consultas con trazabilidad completa es mayor o igual al 75% de la mediana registrada con información básica; por lo tanto, la reducción es menor al 25%.
- **Hipótesis alternativa (H1₃):** la mediana de consultas con trazabilidad completa es menor al 75% de la mediana registrada con información básica; por lo tanto, la reducción es de al menos 25%.

---

## Conclusiones

<p>
Durante el desarrollo del proyecto PcPedia, el equipo logró consolidar una solución web funcional que integra un frontend moderno y un backend robusto, implementados sobre una arquitectura modular basada en Domain-Driven Design (DDD). A lo largo de los sprints se definieron los contextos funcionales principales, se desarrollaron flujos críticos del negocio y se garantizó la comunicación efectiva entre los módulos de autenticación, catálogo, contratos, tickets, pagos, facturación e inventario.

En este último sprint, el equipo alcanzó un hito fundamental: la integración completa del frontend con los servicios del backend, habilitando funcionalidades reales como login, gestión de sesión, visualización de activos, panel administrativo, consulta de contratos, manejo de incidencias y navegación fluida entre los distintos módulos. Asimismo, se realizó el despliegue exitoso tanto del frontend como del backend, lo que permite validar la operación del sistema en un entorno real.

El trabajo colaborativo permitió reforzar las buenas prácticas de desarrollo: mensajes de commit consistentes, estructura clara de branches, revisión cruzada de código y un uso adecuado de herramientas ágiles para el seguimiento del progreso. La modularidad del sistema y la separación por contextos facilitaron la mantenibilidad del proyecto y permitieron que distintos miembros del equipo contribuyeran en paralelo sin afectar la estabilidad del código.

</p>

## Recomendaciones

<p>
    Se recomienda, para etapas posteriores, ampliar la cobertura de pruebas automáticas, optimizar la experiencia de usuario mediante iteraciones basadas en feedback real, reforzar la seguridad de los módulos críticos y continuar con la documentación técnica y funcional del sistema. Los aprendizajes obtenidos en este proyecto fortalecen la capacidad del equipo para abordar nuevas funcionalidades y consolidan una base sólida para futuras mejoras y escalamiento de PcPedia como una plataforma integral de arrendamiento y gestión de equipos tecnológicos.
</p>

## Video App Validation


## Video About-The-Team

**URL de video About-The-Team** [AboutTheTeam](https://youtu.be/qiV-ZW8_nnM)
---


##  Bibliografía

<ul>
  <li>Driessen, V. (2010). <em>A successful Git branching model</em>. Disponible en: <a href="https://nvie.com/posts/a-successful-git-branching-model/" target="_blank">https://nvie.com/posts/a-successful-git-branching-model/</a></li>
  <li>Cucumber. (s.f.). <em>Gherkin Reference</em>. Recuperado de: <a href="https://cucumber.io/docs/gherkin/" target="_blank">https://cucumber.io/docs/gherkin/</a></li>
  <li>Figma. (s.f.). <em>Figma: Collaborative Interface Design Tool</em>. Recuperado de: <a href="https://www.figma.com/" target="_blank">https://www.figma.com/</a></li>
  <li>Lucidchart. (s.f.). <em>Lucidchart: Diagramming & Visualization Software</em>. Recuperado de: <a href="https://www.lucidchart.com/" target="_blank">https://www.lucidchart.com/</a></li>
  <li>Mozilla Developer Network. (s.f.). <em>HTML, CSS y JavaScript</em>. Recuperado de: <a href="https://developer.mozilla.org/es/docs/Web" target="_blank">https://developer.mozilla.org/es/docs/Web</a></li>
  <li>GitHub. (s.f.). <em>GitHub: Where the world builds software</em>. Recuperado de: <a href="https://github.com/" target="_blank">https://github.com/</a></li>
  <li>Microsoft. (s.f.). <em>Visual Studio Code</em>. Recuperado de: <a href="https://code.visualstudio.com/" target="_blank">https://code.visualstudio.com/</a></li>
  <li>W3Schools. (s.f.). <em>HTML5 Syntax</em>. Recuperado de: <a href="https://www.w3schools.com/html/html5_syntax.asp" target="_blank">https://www.w3schools.com/html/html5_syntax.asp</a></li>
</ul>

---

## Anexos

<section id="anexos">
  <h3>1. Organización y Repositorios en GitHub</h3>
  <p>El proyecto PcPedia se encuentra alojado bajo la organización de GitHub del curso 1ASI0729-7401-2520-EcatLeasing-PcPedia. A continuación se detallan los repositorios principales utilizados:</p>
  <ul>
    <li><strong>Repositorio de la Organización:</strong> 
      <a href="https://github.com/1ASI0729-7401-2520-EcatLeasing-PcPedia" target="_blank">
        https://github.com/1ASI0729-7401-2520-EcatLeasing-PcPedia
      </a>
    </li>
    <li><strong>Repositorio del Informe Final:</strong> 
      <a href="https://github.com/1ASI0729-7401-2520-EcatLeasing-PcPedia/Report-PcPedia" target="_blank">
        https://github.com/1ASI0729-7401-2520-EcatLeasing-PcPedia/Report-PcPedia
      </a>
    </li>
    <li><strong>Repositorio de la Landing Page:</strong> 
      <a href="https://github.com/1ASI0729-7401-2520-EcatLeasing-PcPedia/Landing-Page-PcPedia" target="_blank">
        https://github.com/1ASI0729-7401-2520-EcatLeasing-PcPedia/Landing-Page-PcPedia
      </a>
    </li>
    <li><strong>Repositorio de el Frontend:</strong> 
      <a href="https://github.com/1ASI0729-7401-2520-EcatLeasing-PcPedia/Front-end-PcPedia" target="_blank">
        https://github.com/1ASI0729-7401-2520-EcatLeasing-PcPedia/Front-end-PcPedia
      </a>
    </li>
    <li><strong>Repositorio de el Backend:</strong> 
      <a href="https://github.com/1ASI0729-7401-2520-EcatLeasing-PcPedia/Back-end-PcPedia" target="_blank">
        https://github.com/1ASI0729-7401-2520-EcatLeasing-PcPedia/Back-end-PcPedia
      </a>
    </li>
  </ul>

  <h3>2. Despliegue de la Landing Page</h3>
  <p>La Landing Page fue desarrollada por Alessandro Ramiro Condori Lozano y desplegada utilizando GitHub Pages. Esta página sirve como presentación inicial del producto PcPedia.</p>
  <ul>
    <li><strong>Despliegue de la Landing Page en producción:</strong> 
      <a href="https://1asi0729-7401-2520-ecatleasing-pcpedia.github.io/Landing-Page-PcPedia/" target="_blank">
        https://1asi0729-7401-2520-ecatleasing-pcpedia.github.io/Landing-Page-PcPedia/
      </a>
    </li>
    <li><strong>Link del Mock-up en Figma:</strong> 
      <a href="https://www.figma.com/design/oiLz93LcaZJmdmEKi6h46I/FIGMA-PCPEDIA?node-id=1-15&t=wvrVBChCM91tnOsZ-1" target="_blank">
        https://www.figma.com/design/oiLz93LcaZJmdmEKi6h46I/FIGMA-PCPEDIA
      </a>
    </li>
  </ul>
  <h3>3. Despliegue de el Frontend</h3>
  <p>El Frontend fue desplegado utilizando Netlify. Esta página permite a los usuarios interactuar con la interfaz de manera satisfactoria.</p>
  <ul>
    <li><strong>Despliegue de el Frontend en producción:</strong> 
      <a href="https://pcpedia.netlify.app" target="_blank">
          https://pcpedia.netlify.app
      </a>
    </li>
  </ul>
  <h3>4. Despliegue de el Backend</h3>
  <p>El backend fue desplegado utilizando Render. Esta página contiene la lógica de negocio, el manejo de la base de datos y control de APIs.</p>
  <ul>
    <li><strong>Despliegue de el Backend:</strong> 
      <a href="https://pcpediaapi-egd4b8frh3bqcsde.canadacentral-01.azurewebsites.net/swagger-ui/index.html" target="_blank">
          https://pcpediaapi-egd4b8frh3bqcsde.canadacentral-01.azurewebsites.net/swagger-ui/index.html
      </a>
    </li>
  </ul>
  <h3>5. Exposicion del proyecto TF</h3>
  <p>https://youtu.be/jFJ_QsxzDIw</p>
</section>

---

<div align="center">

<br>

*PCPedia · Diseño de Experimentos de Ingeniería de Software · UPC 2026-10*

</div>
