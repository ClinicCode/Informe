
# COURSE PROJECT

---

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas (UPC)</strong><br>    
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Carrera de Ingeniería de Software - Ciclo V</strong><br><br>
    <strong>DISEÑO - 4370</strong><br>
    <br><strong>Profesor:Juan Tinoco Licas </strong><br>
    <br><strong>INFORME DEL TRABAJO FINAL</strong><br>
</p>

<p align="center">
    <strong>Startup del Proyecto:ClinicCode </strong><br>
    <strong>Producto:Dentify </strong><br>
</p>

<div>
    <h3 align="center">Team Members:</h3>
</div>

<div>
    <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Aponte Cruzado, Andrea Marielena</td>
            <td>U202224135</td>
        </tr>
        <tr>
            <td>Belahonia Miranda, Fabrisio  </td>
            <td>U202220219</td>
        </tr>
        <tr>
            <td>Bohorquez Lerzundi	Gerardo Sebastian</td>
            <td>U202224149</td>
        </tr>
        <tr>
            <td>Cutiri Agüero	Fabrizio Alexander</td>
            <td>U201914181</td>
        </tr>
        <tr>
            <td>Berrocal Ramirez	Omar Christian</td>
            <td>U20201B529</td>
        </tr>
    </table>
    </div>

<p align="center">
<br><strong>2025-02</strong></p>
<br>

---

# Registro de Versiones del Informe

El objetivo de esta sección es resumir las modificaciones relevantes que se realizan al informe durante el ciclo de vida del proyecto. Esta sección inicia en una página nueva y se incluye un cuadro con la siguiente estructura:

| Versión | Fecha | Autor | Descripción de modificación |
|---------|-------|-------|-----------------------------|
| TB1 | 24/04/2025 | Belahonia Miranda, Fabrisio  | Realización de:<br>- Capítulo I: Presentación<br>- Capítulo II: Requirements Elicitation & Analysis<br>- Capítulo III: Requirements Specification<br>- Capítulo IV: Solution Software Design |

# Project Report Collaboration Insights
---

URL del repositorio para el reporte del proyecto: https://github.com/ClinicCode/Informe

TB1:
![githubu.png](Img/githuub.png)

Para el desarrollo del informe perteneciente a la entrega TB1, se dividió la implementación de secciones de la siguiente forma para cada integrante del equipo:

| Integrante | Tareas Asignadas |
|------------|-----------------|
| Aponte Cruzado, Andrea Marielena | Analisis Competitivo y User Stories |
| Belahonia Miranda, Fabrisio | Entrevistas, Análisis de entrevistas y Needfinding, As to Be escenario, Elaboración de PPT |
| Bohorquez Lerzundi, Gerardo Sebastian | Lean UX, Entrevistas, Análisis de entrevistas y Needfinding, Impact Map |
| Cutiri Agüero, Fabrizio Alexander | Lean UX, User Stories, NeedFinding, Elaboración de PPT |
| Berrocal Ramirez, Omar Christian | Antecedentes y problemática, User and Technical Stories, Product Backlog, Capítulo IV: Solution Software Design, Elaboración de primera versión del BackEnd |

# GitHub Collaboration Insights

GitHub también presenta un timeline de las ramas principales y los procesos de merge a los que se han sometido. Todas las ramas se crearon tomando en cuenta el diseño de GitFlow para una buena organización cuando se usa un software de control de versiones.

Los integrantes son:

- Aponte Cruzado, Andrea Marielena(iconicmiau)
- Belahonia Miranda, Fabrisio(devfab17)
- Bohorquez Lerzundi, Gerardo Sebastian(Sebasbl562)
- Cutiri Agüero, Fabrizio Alexander(FabrizioCutiri)
- Berrocal Ramirez, Omar Christian(OmBRz)

# Contenido
## Tabla de contenidos
- [COURSE PROJECT](#course-project)
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [GitHub Collaboration Insights](#github-collaboration-insights)
- [Contenido](#contenido)
  - [Tabla de contenidos](#tabla-de-contenidos)
- [Student Outcome](#student-outcome)
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
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Product Backlog](#33-product-backlog)
  - [3.4. Impact Mapping](#34-impact-mapping)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
    - [4.1.3. Mobile Style Guidelines](#413-mobile-style-guidelines)
      - [4.1.3.1. iOS Mobile Style Guidelines](#4131-ios-mobile-style-guidelines)
      - [4.1.3.2. Android Mobile Style Guidelines](#4132-android-mobile-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
      - [Categorización del Contenido](#categorización-del-contenido)
      - [Secuencia de Contenidos](#secuencia-de-contenidos)
      - [Agrupación de Funcionalidades](#agrupación-de-funcionalidades)
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
  - [4.6. Web Applications UX/UI Design](#46-web-applications-uxui-design)
    - [4.6.1. Web Applications Wireframes](#461-web-applications-wireframes)
    - [4.6.2. Web Applications Wireflow Diagrams](#462-web-applications-wireflow-diagrams)
    - [4.6.3. Web Applications Mock-ups](#463-web-applications-mock-ups)
    - [4.6.4. Web Applications User Flow Diagrams](#464-web-applications-user-flow-diagrams)
  - [4.8. Domain-Driven Software Architecture](#48-domain-driven-software-architecture)
    - [4.8.1. Software Architecture Context Diagram](#481-software-architecture-context-diagram)
    - [4.8.2. Software Architecture Container Diagrams](#482-software-architecture-container-diagrams)
    - [4.8.3. Software Architecture Components Diagrams](#483-software-architecture-components-diagrams)
  - [4.9. Software Object-Oriented Design](#49-software-object-oriented-design)
    - [4.9.1. Class Diagrams](#491-class-diagrams)
    - [4.9.2. Class Dictionary](#492-class-dictionary)
  - [4.10. Database Design](#410-database-design)
    - [4.10.1. Relational/Non-Relational Database Diagram](#4101-relationalnon-relational-database-diagram)
- [Capítulo V: Product Implementation](#capítulo-v-product-implementation)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Product Implementation \& Deployment](#52-product-implementation--deployment)
    - [5.2.1. Sprint Backlogs](#521-sprint-backlogs)
    - [5.2.2. Implemented Landing Page Evidence](#522-implemented-landing-page-evidence)
    - [5.2.3. Implemented Frontend-Web Application Evidence](#523-implemented-frontend-web-application-evidence)
    - [5.2.4. Implemented Native-Mobile Application Evidence](#524-implemented-native-mobile-application-evidence)
    - [5.2.5. Implemented RESTful API and/or Serverless Backend Evidence](#525-implemented-restful-api-andor-serverless-backend-evidence)
    - [5.2.6. RESTful API documentation](#526-restful-api-documentation)
    - [5.2.7. Team Collaboration Insights](#527-team-collaboration-insights)
  - [5.3. Video About-the-Product](#53-video-about-the-product)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)


    
# Student Outcome

| Criterio específico | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Conclusiones |
|----|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----|
|4.c.1 Reconoce responsabilidad ética y profesional en situaciones de ingeniería de software | **Aponte Cruzado, Andrea Marielena**<br>**TB1:** Fui parte de la realización de las entrevistas al segmento objetivo y parte de la experimentación para adecuar el diseño gráfico a la web acorde con lo descrito por nuestros usuarios en las entrevistas.<br>**Belahonia Miranda, Fabrisio**<br>**TB1:** Como líder del equipo asumí la responsabilidad ética y profesional en el desarrollo del proyecto, asegurando el respeto a la privacidad de los usuarios, la accesibilidad en el diseño UX/UI y la transparencia en cada etapa del Lean UX. Guié al equipo con roles claros, fomentando la colaboración y el compromiso técnico para garantizar un producto de calidad y confiable. <br>**Bohorquez Lerzundi, Gerardo Sebastian**<br>**Cutiri Agüero, Fabrizio Alexander**<br>**TB1** <br><br> Redacté historias de usuario claras y realistas, asegurando que respondan a las necesidades de los usuarios finales, quienes son los odontólogos. <br><br>**Berrocal Ramirez, Omar Christian**<br/>**TB1**<br/>Procuré adaptar el diseño del landing page, la apliación web y mobile acorde a las necesidades de los usuarios finales para que se reflejen nuestras intenciones de manejar el proyecto de la forma más profesional posible.                                                                                                                                 | **TB1:** El proyecto se desarrolló bajo principios de responsabilidad ética y profesional, priorizando la privacidad y seguridad de los datos, la accesibilidad en el diseño UX/UI y la transparencia en los procesos mediante Lean UX. Además, se garantizó un trabajo organizado y colaborativo dentro del equipo, con roles claros y compromiso técnico, lo que permitió asegurar la calidad del producto y el respeto hacia los futuros usuarios de la aplicación. |
|4.c.2 Emite juicios informados considerando el impacto de las soluciones de ingeniería de software en contextos globales, económicos, ambientales y sociales| **Aponte Cruzado, Andrea Marielena**<br> **TB1:** Participé en el análisis de las entrevistas, de manera que podamos adquirir los conocimientos necesarios para el desarrollo de las características de la aplicación web, integrando características importantes para concretar un proyecto más ordenado. <br> **Belahonia Miranda, Fabrisio**<br>**TB1:** Como líder del equipo tomé decisiones considerando impactos sociales, económicos, globales y ambientales. Busqué que la solución generara beneficios reales para los usuarios, fuera sostenible y escalable económicamente, cumpliera estándares internacionales de diseño y contribuyera a reducir el uso de recursos físicos mediante procesos digitales, promoviendo así un desarrollo más responsable y con menor huella ambiental.<br>**Bohorquez Lerzundi, Gerardo Sebastian**<br><br>**Cutiri Agüero, Fabrizio Alexander**<br><br>**TB1** <br><br>  Organicé el product backlog de manera que se entreguen primero las funcionalidades de mayor impacto para los odontólogos. Para ello, me apoye de las entrevistas realizadas, con el objetivo de tomar desiciones bien informadas <br><br>**Berrocal Ramirez, Omar Christian**<br/>**TB1**<br/>Investigué los antecedente de la problemática para  plantear una solución acorde a nuestro entorno local. Para ello tuve que ver como se comporta el publico objetivo en un contexto global y un contexto local. | **TB1:** Las decisiones del proyecto se tomaron considerando impactos sociales, económicos, globales y ambientales. La solución busca mejorar la calidad de vida de los usuarios, promover la sostenibilidad y escalabilidad del modelo de negocio, cumplir con estándares internacionales de diseño y accesibilidad, y contribuir a la reducción de recursos físicos mediante la digitalización de procesos. De este modo, se asegura un desarrollo responsable que responde a las necesidades actuales y futuras de distintos contextos.|

# Capítulo I: Introducción

## 1.1. Startup Profile

En esta sección se presenta la descripción del startup y los perfiles de los miembros del equipo.

### 1.1.1. Descripción de la Startup

**ClinicCode**: es una startup tecnológica enfocada en revolucionar la forma en que los consultorios dentales administran sus actividades diarias. Su producto Dentify es una aplicación móvil completa, creada específicamente para cubrir todas las necesidades de gestión en el ámbito odontológico.

**Misión**: Simplificar y optimizar la administración de los consultorios dentales, permitiendo que los profesionales se enfoquen en lo más importante: la salud y el bienestar de sus pacientes.

**Visión**: Ser la plataforma de referencia en la gestión de consultorios dentales en Lima, liderando el proceso de digitalización en el sector odontológico.

**Valores**:

* Compromiso con la calidad y la excelencia

*  Innovación continua

* Responsabilidad social

### 1.1.2. Perfiles de integrantes del equipo

|                           Photo                           | Description                                                                                                                                                                                                                                                                                                                                                                                                                 |
|:---------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|        ![Andrea](Img/foto-andrea.jpeg)        | **Nombre y Apellido:** Andrea Aponte Cruzado  <br> **Carrera:** Ingeniería de Software (6to ciclo) <br> **Acerca de:** Estoy cursando el sexto ciclo de la carrera y me considero una persona apasionada por los proyectos tecnológicos y a gran escala. Tengo experiencia en algunos lenguajes de programación y la realización de prpuyectos ágiles.                                                                                                                                                                                |
|                ![Fabrisio](Img/fafa.jpeg)                 | **Nombre y Apellido:** Fabrisio Belahonia Miranda <br> **Carrera:** Ingeniería de Software (7mo ciclo) <br> **Acerca de:** Voy cursando el 7to ciclo de mi carrera, y me considero una persona responsable, ordenado, empático. Me interesa el área de Ciberseguridad y tengo experiencia con Linux, Redes, Cloud, etc** .                                                                                                  |
| ![foto-fabrizio-cutiri.png](Img/foto-fabrizio-cutiri.png) | **Nombre y Apellido:** Fabrizio Alexander Cutiri Agüero  <br> **Carrera:** Ingeniería de Software (8to ciclo) <br> **Acerca de:** Me considero una persona responsable, puntual y capaz de adaptarse a diferentes situaciones. Elegí esta carrera porque me apasiona la tecnología y disfruto diseñar y desarrollar aplicaciones innovadoras que ayuden a las personas y empresas a solucionar sus problemas.               |
|    ![Sebastian](Img/Sebastian.png)     | **Nombre y Apellido:** Sebastian Bohorquez Lerzundi <br> **Carrera:** Ingeniería de Software  <br> **Acerca de:** Me considero una persona responsable y organizada al trabajar en proyectos. Suelo colaborar activamente con mi grupo, aportando ideas y apoyando en lo que se necesite. Me adapto con facilidad y mantengo una actitud comprometida para alcanzar los objetivos en conjunto.                                                                                                                                                                                                                                                                                                 |
|             ![Omar](Img/Omar-integrante.jpg)              | **Nombre y Apellido:** Omar Christian Berrocal Ramirez <br> **Carrera:** Ingeniería de Software <br> **Acerca de:** Me considero una persona capaz de lograr sus metas y objetivos con el enfoque correcto y mucha disciplina. Elegí esta carrera porque desde la infancia tuve intección con la tecnología y me gusta descubrir nuevas cosas respecto a esta. |

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

**Antecedentes:**

La adopción de tecnologías digitales ha transformado significativamente la gestión de pacientes en los consultorios dentales, mejorando procesos como la programación de citas, la actualización de historiales clínicos y la comunicación entre profesionales y pacientes. En el Perú, la salud digital aún no está plenamente consolidada, aunque muestra un avance sostenido.

De acuerdo con el INEI (2022), el 72.7 % de la población tenía acceso a internet en 2022, frente al 64.5 % en 2020. Este incremento refleja un escenario favorable para impulsar la digitalización en los consultorios dentales, facilitando una gestión más ágil, accesible y alineada con las necesidades actuales de los pacientes.

Por su parte, Osiptel (2022) indica que el uso de dispositivos móviles creció alrededor de un 10 % en 2021, considerando que en 2016 el 78 % de la población ya contaba con teléfono móvil. Estos datos evidencian una clara tendencia hacia la digitalización en la sociedad peruana y refuerzan la conexión entre el uso de dispositivos móviles y el acceso a internet.

**Problemática**

Pese a estos avances, muchos consultorios y clínicas dentales —sobre todo los más pequeños— continúan gestionando sus operaciones con métodos manuales o sistemas obsoletos. Esto provoca errores en la programación de citas, pérdida de información clínica y una experiencia deficiente para los pacientes. Además, la falta de capacitación en el uso de herramientas digitales y la percepción de que son costosas y difíciles de implementar limitan su adopción. Como resultado, la eficiencia operativa y la calidad del servicio se ven comprometidas.


**Análisis del problema (5W + 2H)**


**WHAT (Qué):**
El problema principal es la gestión ineficiente de los consultorios dentales, lo que ocasiona fallas en la programación de citas, pérdida de historiales médicos, extravío de documentos financieros y demoras en la atención, afectando la experiencia del paciente.

**WHEN (Cuándo):**
Este problema ocurre en todas las etapas de la atención, desde la reserva de la cita hasta el seguimiento posterior al tratamiento, siendo más crítico en periodos de alta demanda o con múltiples pacientes simultáneos.

**WHERE (Dónde):**
Surge en los consultorios dentales que aún dependen de procesos manuales o sistemas desactualizados para manejar la información y las operaciones diarias.

**WHO (Quién):**
Afecta a odontólogos y personal administrativo —que en muchos casos son los propios dueños—, quienes enfrentan dificultades en la organización y gestión de datos. Indirectamente impacta también a los pacientes, al recibir un servicio desordenado y poco eficiente.

**WHY (Por qué):**
La causa principal es la baja adopción de soluciones digitales modernas, motivada por la percepción de altos costos, la falta de capacitación y la resistencia al cambio de algunos profesionales.

**HOW (Cómo):**
La dependencia de métodos tradicionales, junto con la escasa inversión en tecnología y formación, ha dejado a muchos consultorios sin la capacidad de responder adecuadamente a las demandas actuales del sector.

**HOW MUCH (Cuánto):**
El impacto es significativo: disminuye la eficiencia operativa, reduce la satisfacción del paciente y afecta la rentabilidad del negocio. Los consultorios que operan con sistemas poco efectivos corren el riesgo de perder pacientes, reputación y asumir mayores costos derivados de errores y procesos ineficientes.


### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

Hoy en día, los consultorios dentales enfrentan el desafío de administrar de forma centralizada y eficiente sus operaciones cotidianas, como la programación de citas, la gestión de historiales clínicos y la implementación de pagos en línea. Este reto cobra mayor relevancia en un escenario donde la digitalización se ha convertido en un factor esencial para mejorar la experiencia del paciente y optimizar tanto el tiempo como los recursos de los profesionales odontológicos.

Sin embargo, gran parte de los consultorios continúa utilizando métodos tradicionales y desarticulados para organizar sus procesos, lo que provoca ineficiencias que afectan tanto a pacientes como a especialistas. La falta de una solución digital integral complica la coordinación de citas, el acceso rápido a historiales clínicos y la automatización de los pagos, generando un impacto negativo en la satisfacción del paciente y en la productividad del consultorio.

Ante ello, surge la pregunta: **¿Cómo diseñar una plataforma web integral, intuitiva y fácil de usar que optimice la gestión de los consultorios dentales, permitiendo a los profesionales enfocarse en brindar una atención de calidad mientras se eleva la experiencia del paciente gracias a la digitalización y automatización de tareas clave?**

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions**

Consideramos que nuestros clientes necesitan una solución más eficiente para la gestión de citas, historiales clínicos y pagos en línea.
Estas necesidades pueden atenderse mediante una aplicación móvil integral que permita administrar pacientes, registrar historiales clínicos, reservar citas y verificar pagos de manera centralizada.

Nuestros principales clientes son odontólogos que gestionan sus propios consultorios y que buscan ofrecer un servicio moderno, eficiente y cómodo a sus pacientes.
El valor fundamental que esperan de nuestro servicio es la efectividad en la gestión de su consultorio, utilizando herramientas que optimicen su experiencia.

Además, podrán acceder a beneficios adicionales a través de planes de suscripción con soporte continuo y especializado, que incluirán funciones avanzadas como el modo offline para mayor flexibilidad.

La captación de clientes se realizará principalmente mediante estrategias de marketing digital y alianzas estratégicas con asociaciones de odontólogos, lo que nos permitirá ampliar nuestra red de contactos y aumentar la visibilidad de la aplicación.

El modelo de negocio estará basado en suscripciones, que ofrecerán a los clientes mayores facilidades para organizar su consultorio de manera eficiente.

Nuestra competencia directa son otras aplicaciones móviles para la gestión de consultorios dentales; sin embargo, muchas de ellas carecen de integración completa o presentan interfaces poco intuitivas.
Superaremos a la competencia gracias al uso de tecnologías modernas, un enfoque en la mejora continua de la experiencia del usuario (dentistas y pacientes) y un servicio de soporte constante.

El principal riesgo identificado es la resistencia al cambio de parte de algunos dentistas que prefieren mantener métodos tradicionales de gestión.
Para mitigar este riesgo, ofreceremos demostraciones del software y un soporte cercano y personalizado, facilitando así una rápida adaptación a la plataforma.

**Assumptions Worksheet**

* **¿Quién es el usuario?** Dentistas que administran sus propios consultorios y buscan una aplicación moderna y eficiente para optimizar su gestión diaria.

* **¿Dónde encaja nuestro producto en su trabajo o vida?** La aplicación móvil se integra en la rutina de los odontólogos, permitiéndoles organizar citas, acceder a historiales clínicos y gestionar pagos. Además, ofrece la función offline, útil en situaciones sin conexión a internet.

* **¿Qué problemas tiene nuestro producto que debe resolver?** La principal dificultad es la adopción de nuevas tecnologías, ya que algunos profesionales muestran resistencia al uso de plataformas digitales para la gestión de información.

* **¿Cuándo y cómo se usa el producto?** Su uso es diario, en actividades como la programación de citas, la revisión de historiales médicos y la facturación de pagos.

* **¿Qué características son importantes?**

    * Accesibilidad desde distintos dispositivos móviles.

    * Integración con sistemas de pago.

    * Interfaz amigable e intuitiva.

* **¿Cómo debe verse y comportarse el producto?** La aplicación debe transmitir una imagen profesional, limpia y confiable, alineada con el sector salud. Además, debe ser rápida, intuitiva y sencilla de navegar, garantizando una experiencia fluida para el usuario.


#### 1.2.2.3. Lean UX Hypothesis Statements

* Creemos que, al incorporar nuevas herramientas para la gestión de citas, historiales clínicos y pagos en línea, se incrementará la eficiencia de los consultorios y mejorará la experiencia de los pacientes. Sabremos que hemos alcanzado este objetivo cuando logremos evidenciar una mejor organización en la programación de citas y en la facturación de pagos.

* Creemos que, al implementar la generación automática de facturas, el proceso de facturación será más ágil y sencillo. Sabremos que estamos cumpliendo con este propósito cuando logremos reducir en más de un 80 % el tiempo destinado a la emisión de facturas.

* Creemos que, al añadir un modo offline, se facilitará el uso de la aplicación para la visualización de estadísticas y la gestión de citas sin necesidad de conexión a internet. Sabremos que alcanzamos este objetivo cuando se reduzcan significativamente los problemas de conectividad, especialmente en zonas con acceso limitado a la red.

#### 1.2.2.4. Lean UX Canvas

<img src="Img/Lean-UX-Canvas.jpg">



## 1.3. Segmentos objetivo

En esta sección se describen los perfiles específicos del público objetivo de nuestro producto. Estos grupos comparten características demográficas, conductuales y motivacionales que los diferencian de otros segmentos del mercado, lo que permite diseñar estrategias más precisas para atender sus necesidades.

* **Segmento demográfico**: Odontólogos con ingresos medios, con la capacidad de invertir en herramientas y sistemas que optimicen la gestión de sus pacientes.

* **Segmento geográfico**: Profesionales que ejercen en zonas urbanas y cuentan con una base considerable de pacientes.

* **Segmento psicográfico**: Dentistas interesados en modernizar sus prácticas y ofrecer un servicio de mayor calidad a sus pacientes.

* **Segmento conductual**: Profesionales que buscan soluciones digitales que les permitan optimizar la programación y gestión de citas.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

El objetivo de esta sección es identificar a los principales competidores directos que cuentan con modelos de negocio basados en productos digitales similares, así como a los competidores indirectos que brindan soluciones parcialmente comparables.

### 2.1.1. Análisis competitivo


<table border="1px">
        <thead>
            <th colspan="11">Competitive Analysis Landscepe</th>
        </thead>
        <tbody>
            <tr>
                <td rowspan="2" colspan="2">¿Por qué llevar a
                    cabo este análisis?</td>
                <td colspan="9">Escriba en el recuadro la pregunta que busca responder o el objetivo de
                    este análisis.</td>
            </tr>
            <tr>
                <td colspan="9">El objetivo de este análisis es comprender el funcionamiento y las características que presentan los productos de nuestros competidores, para posteriormente planificar estrategias y tácticas para aprovechar las fortalezas de nuestro producto y las debilidades de nuestros competidores.   </td> 
            </tr>
            <tr>
                <tr>
                    <td colspan="3">(En la cabecera colocar por cada competidor nombre y logo)</td>
                    <td colspan="2"><img src="/Img/Dentify-logo.png" style="width: 60px; height: auto;"><br>Dentify</td>
                    <td colspan="2"><img src="/Img/identist.png" style="width: 60px; height: auto;"><br>iDentins</td>
                    <td colspan="2"><img src="/Img/my-dental-clinic.png" style="width: 60px; height: auto;"><br>My Dental Clinic</td>
                    <td colspan="2"><img src="/Img/cusp-software-dental.png" style="width: 60px; height: auto;"><br>Cusp Software Dental</td>
                </tr>
            </tr>
            <tr>
                <td rowspan="2" colspan="1">Perfil</td>
                <td colspan="2">Overview</td>
                <td colspan="2">App móvil para dentistas que facilita citas, pagos y seguimiento de pacientes en tiempo real.</td>
                <td colspan="2">App móvil para clínicas dentales con enfoque en automatización desde dispositivos móviles.</td>
                <td colspan="2">App móvil que digitaliza procesos clínicos y administrativos de forma simple.</td>
                <td colspan="2">App móvil con herramientas digitales enfocadas en tratamiento y contabilidad para clínicas dentales.</td>
            </tr>
            <tr>
                <td colspan="2"> Ventaja competitiva <br></br> ¿Qué valor ofrece a los clientes?</td>
                <td colspan="2">Gestión total del consultorio desde el móvil, con notificaciones push e interfaz optimizada para smartphones.</td>
                <td colspan="2">Multiplataforma (iOS, Android, Windows), modo offline, control de ingresos y gastos.</td>
                <td colspan="2">Facilidad de uso, integración con calendario y soporte multilenguaje.</td>
                <td colspan="2">Buen balance entre funciones clínicas y contables, acceso en múltiples dispositivos.</td>
            </tr>
            <tr>
                <td rowspan="2" colspan="1">Perfil de Marketing</td>
                <td colspan="2">Mercado Objetivo</td>
                <td colspan="2">Clínicas pequeñas y medianas en zonas urbanas del Perú.</td>
                <td colspan="2">Clínicas modernas que trabajan desde dispositivos móviles.</td>
                <td colspan="2">Consultorios que quieren digitalizar sin complicaciones técnicas.</td>
                <td colspan="2">Clínicas que quieren seguimiento visual y contable de tratamientos.</td>
            </tr>
            <tr>
                <td colspan="2">Estrategia de Marketing</td>
                <td colspan="2">Presencia digital, publicidad en redes, alianzas con gremios dentales.</td>
                <td colspan="2">App Store, Play Store, redes sociales, enfoque en movilidad y facilidad.</td>
                <td colspan="2">Enfocada en App Stores, recomendaciones y facilidad de uso.</td>
                <td colspan="2">Uso de redes sociales, beneficios de digitalización rápida y clara.</td>
            </tr>
            <tr>
                <td rowspan="3" colspan="1">Perfil de Producto</td>
                <td colspan="2">Producto & Servicio</td>
                <td colspan="2">Citas, historial, pagos, métricas, backup, dashboard, recordatorios, soporte técnico.</td>
                <td colspan="2">Citas, pacientes, diagnósticos, pagos, imágenes, gastos, recordatorios SMS, modo oscuro.</td>
                <td colspan="2">Citas, historial, notas dentales, gráficos dentales, imágenes, PDF, pagos. </td>
                <td colspan="2">Citas, pacientes, pagos, odontogramas, contabilidad, gráficos, historial, recordatorios SMS.</td>
            </tr>
            <tr>
                <td colspan="2">Precio & Costos  </td>
                <td colspan="2">Precio accesible mensual con prueba gratuita.</td>
                <td colspan="2">Plan de pago mensual/anual (varía según plataforma).</td>
                <td colspan="2">Costos bajos, con versiones gratuitas limitadas y planes premium.</td>
                <td colspan="2">Plan de pago mensual con acceso completo desde el inicio.</td>
            </tr>
            <tr>
                <td colspan="2">Canales de distribucion (web y/o Movil)</td>
                <td colspan="2">Aplicación web y Móvil</td>
                <td colspan="2">Móvil</td>
                <td colspan="2">Móvil</td>
                <td colspan="2">Móvil</td>
            </tr>
            <tr>
                <td rowspan="5">Analisis SWOT</td>
                <td colspan="10">Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus
                    oportunidades y contribuir a lo que ustedes definen como su posible ventaja
                    competitiva</td>
            </tr>
            <tr>
                <td colspan="2">Fortalezas</td>
                <td colspan="2">Solución local con soporte completo, adaptable y segura.</td>
                <td colspan="2"> Automatización, compatibilidad, almacenamiento en la nube.</td>
                <td colspan="2"> Facilidad, conexión con calendario, interfaz amigable.</td>
                <td colspan="2"> Funciones clínicas novedosas, sincronización entre dispositivos.</td>
            </tr>
            <tr>
                <td colspan="2">Debilidades</td>
                <td colspan="2">Nuevo en el mercado, falta de confianza inicial.</td>
                <td colspan="2">Puede no cubrir necesidades avanzadas de grandes clínicas.</td>
                <td colspan="2">Limitado a móviles, poco robusto para clínicas grandes.</td>
                <td colspan="2">Falta de personalización en algunos módulos, riesgo de estancamiento.</td>
            </tr>
            <tr>
                <td colspan="2">Oportunidades</td>
                <td colspan="2">Alta demanda de digitalización en clínicas del Perú.</td>
                <td colspan="2">Aumento de uso de móviles en el rubro médico.</td>
                <td colspan="2">Gran adopción de móviles en regiones con bajo acceso a PCs.</td>
                <td colspan="2">Interés en herramientas visuales y simples para contabilidad.</td>
            </tr>
            <tr>
                <td colspan="2">Amenazas</td>
                <td colspan="2">Al ser una aplicación nueva, si hay poca oferta o demanda en la aplicación, los usuarios no tendrán motivos para permanecer activos.</td>
                <td colspan="2">Introducción o demanda de soluciones personalizadas y necesidades más avanzadas al mercado. Podrían perder clientes.</td>
                <td colspan="2">Perdidas de grandes contratos por falta de integración con un sistema mayor.</td>
                <td colspan="2">Inclinación del público por aspectos más personalizados. </td>
            </tr>
        </tbody>
    </table>


### 2.1.2. Estrategias y tácticas frente a competidores

- Proporcionaremos una interfaz intuitiva que facilite el uso del software, con una navegación fluida y rápida, además de soporte personalizado para garantizar una adopción eficiente y una alta satisfacción del usuario.

- Ofreceremos planes de suscripción flexibles y escalonados, diseñados para ajustarse a distintos presupuestos y necesidades. Desde opciones básicas hasta funciones avanzadas, cada plan estará orientado a diferentes tipos de consultorios.

- Incorporaremos testimonios de clientes satisfechos en nuestra estrategia de marketing para reforzar la credibilidad. Estos testimonios serán resaltados en nuestro sitio web y materiales promocionales, contribuyendo a atraer nuevos usuarios y fortalecer la confianza en nuestra plataforma.

## 2.2. Entrevistas

Esta sección recopila la información obtenida a partir de entrevistas realizadas a odontólogos que gestionan sus propios consultorios. Se incluyen las preguntas formuladas, las entrevistas realizadas y un análisis comparativo. El objetivo es comprender sus necesidades y hábitos actuales para fundamentar el desarrollo de una solución digital adecuada a su entorno real.

### 2.2.1. Diseño de entrevistas

**Preguntas para los odontólogos independientes**

1. ¿Cuál es tu nombre?
2. ¿Qué edad tienes?
3. ¿A qué te dedicas actualmente?
4. ¿En qué lugar vives o trabajas?
5. ¿Podrías contarme un poco sobre ti? Por ejemplo, ¿cuántos pacientes sueles atender semanalmente?
6. ¿Dónde está ubicado tu consultorio?
7. ¿Cuánto tiempo lleva funcionando tu consultorio?
8. ¿Utilizas alguna app o software para organizar las tareas diarias en tu clínica? Si es así, ¿podrías contarme cómo funciona y qué te parece?
9. ¿Qué tan necesario es para ti que esa aplicación funcione sin conexión a internet (modo offline)?
10. ¿Qué dificultades enfrentas al organizar tu agenda y las citas de tus pacientes?
11. ¿Cómo manejas la comunicación con los pacientes, especialmente cuando hay cancelaciones o cambios en las citas?
12. Si pudieras añadir nuevas funciones al software que usas, ¿cuáles agregarías y por qué?
13. ¿Qué marcas, dispositivos o plataformas digitales prefieres para trabajar y mantenerte al día?
14. ¿Cómo organizas tu jornada diaria para asegurarte de que todas las citas se realicen sin inconvenientes?
15. ¿Qué tan complicado te resulta mantener actualizados los registros y tratamientos de tus pacientes? ¿Qué métodos usas para llevar el control de las historias clínicas?
16. ¿Cómo controlas los ingresos del consultorio y haces seguimiento de los pagos pendientes?
17. ¿Qué tan relevante es para ti recibir opiniones de tus pacientes? ¿Cómo sabes si recomiendan tus servicios?
18. ¿Qué tan importante es para ti que la información del consultorio esté segura y bien respaldada?
19. ¿Estarías dispuesto(a) a pagar por una aplicación que te ayude a gestionar tu consultorio? ¿Qué precio te parecería razonable?

### 2.2.2. Registro de entrevistas

**Segmento Objetivo:** Odontólogos

**Entrevista 1: Samuel Mendoza**

![entrevista-fabrizio-cutiri.png](Img/entrevista-fabrizio-cutiri.png)

**Datos del entrevistado**
* **Nombre:** Samuel Mendoza
* **Edad:** 60 años
* **Distrito de Residencia:** Breña
* **Duración de la entrevista:** 15:20 min

**Resumen de la entrevista:**

El doctor Samuel Mendoza tiene 60 años, vive en Breña y trabaja en Chorrillos, donde cuenta con un consultorio en la Av. Huaylas que funciona desde hace 10 años. Atiende en promedio a 50 pacientes por semana y en su práctica diaria utiliza laptop, computadora y celular para revisar estadísticas y mantenerse al día con los datos de sus pacientes.

Actualmente emplea una aplicación básica que le permite registrar los procedimientos realizados a cada paciente, anotar lo que se hará en la siguiente cita y confirmar asistencia o inasistencia. Sin embargo, considera que esta herramienta es limitada, ya que carece de funciones importantes como la gestión de inventario, el manejo digital de historias clínicas y una mayor seguridad en los datos.

La solicitud de las citas en su consultorio se realiza tanto de manera presencial como por teléfono, a través de un personal encargado. No obstante, enfrenta dificultades frecuentes: pacientes que llegan tarde, que no asisten o que exigen citas inmediatas. Cuando hay cancelaciones o cambios, su equipo se comunica con los pacientes mediante llamadas, generalmente un día antes o, de ser el caso, el mismo día por la mañana.

El manejo de las historias clínicas todavía se realiza de forma manual y por escrito, lo que representa una tarea tediosa que desearía digitalizar por completo. En cuanto a los pagos, estos se gestionan en caja, con la posibilidad de hacerlo en efectivo o con tarjeta de débito o crédito.

El odontólogo también destaca la importancia de recibir críticas y recomendaciones de los pacientes, ya sean positivas o negativas, ya que considera que estas le permiten mejorar la gestión y el trato brindado en su consultorio. Asimismo, subraya que la seguridad de la información es un aspecto crucial, pues se trata de datos personales sensibles que deberían estar protegidos mediante filtros de acceso en cualquier software de gestión.

Finalmente, señala estar dispuesto a pagar por un sistema de gestión completo que le permita mejorar la administración de su consultorio. Aunque no tiene un rango de precio definido, menciona que en Estados Unidos conoce softwares que cuestan alrededor de 2000 dólares y ofrecen soluciones completas. Reconoce que en Perú todavía no es común el uso de estas herramientas, pero considera que deberían estar más extendidas en todos los consultorios.

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

Es una técnica de diseño centrado en el usuario que busca descubrir necesidades reales de las personas, incluso aquellas que no expresan explícitamente. A través de entrevistas, observaciones y análisis del comportamiento, se identifican problemas, frustraciones, deseos y oportunidades que pueden guiar el desarrollo de soluciones más útiles y significativas.

### 2.3.1. User Personas

<img src="Img/Carlos Hijar Santa Maria.png" alt="Imagen_User" style="margin-bottom: 5px;" width="800"/>

### 2.3.2. User Task Matrix

A continuación, se presenta una matriz de tareas enfocada en el odontólogo independiente Carlos Hijar Santa María. Esta herramienta permite identificar y clasificar las actividades clave que realiza en su día a día, considerando la frecuencia con la que las lleva a cabo y el nivel de importancia que representan dentro de su práctica profesional.</br></br>

<table border="1">
  <thead>
    <tr>
      <th rowspan="2">Tarea</th>
      <th colspan="2">Carlos Hijar Santa María</th>
    </tr>
    <tr>
      <th>Frecuencia</th>
      <th>Importancia</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Agendar citas</td>
      <td>Alta</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Registrar historia clínica</td>
      <td>Media</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Hacer seguimiento de tratamientos</td>
      <td>Alta</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Revisar y gestionar ingresos</td>
      <td>Alta</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Revisar insumos y equipo</td>
      <td>Media</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Recordar tratamientos periódicos</td>
      <td>Baja</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Comunicarse con pacientes</td>
      <td>Alta</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Revisar estado general del consultorio</td>
      <td>Baja</td>
      <td>Media</td>
    </tr>
  </tbody>
</table>


Del análisis de la matriz de tareas de Carlos Hijar Santa María, se destaca que las actividades más frecuentes y de mayor importancia están relacionadas directamente con la atención al paciente y la gestión financiera: agendar citas, hacer seguimiento de tratamientos, revisar ingresos y comunicarse con los pacientes. Estas tareas son claves en su rutina diaria y representan puntos críticos que una solución digital debe priorizar. Asimismo, aunque tareas como recordar tratamientos periódicos, revisar insumos y equipos, y revisar estado general del consultorio no se realizan con tanta frecuencia, sí tienen un nivel de importancia alto, lo que indica oportunidades para automatización o recordatorios que aumenten la eficiencia y reduzcan errores.


### 2.3.3. User Journey Mapping

<img src="Img/User-Journey-Mapping-1.png" alt="JS" style="margin-bottom: 5px;" width="700"/>

### 2.3.4. Empathy Mapping

Utilizaremos esta herramienta visual que nos ayudará a comprender mejor a los usuarios que hemos escogido viendo desde una perspectiva más humana y emocional, en este caso para los odontólogos independientes.

<img src="Img/Emphaty-Map.png" width="800">

### 2.3.5. As-is Scenario Mapping

El As-Is Scenario Mapping muestra cómo los odontólogos gestionan actualmente su consultorio sin una solución digital integrada. A partir de entrevistas realizadas, se identificaron procesos, herramientas, pensamientos y emociones relacionados con tareas clave como citas, pagos, historias clínicas e inventario. Esta información permite detectar puntos de mejora y fundamentar el desarrollo de una solución más eficiente y centrada en sus necesidades.

<img src="Img/as-is-scenario-mapping.jpg" width="800">

## 2.4. Ubiquitous Language

**Patient Record (Historia clínica):**
Conjunto estructurado de documentos e información relacionada con la salud del paciente, que incluye antecedentes médicos, diagnósticos, tratamientos realizados y procedimientos llevados a cabo en el consultorio dental.

**Appointment Scheduling (Programación de citas):**
Proceso mediante el cual se asigna una fecha y hora determinadas para que el paciente acuda al consultorio dental a recibir atención.

**Dental Charting (Odontograma):**
Representación gráfica detallada del estado bucodental del paciente, que registra las condiciones de los dientes y encías.

**Billing (Facturación):**
Procedimiento administrativo orientado a la elaboración y emisión de facturas dirigidas a los pacientes o a sus aseguradoras, detallando los costos asociados a los tratamientos y procedimientos realizados.

**Electronic Health Record – EHR (Registro Electrónico de Salud):**
Sistema digital que almacena y organiza la información médica del paciente, permitiendo un acceso ágil, seguro y centralizado a sus antecedentes, resultados de exámenes y tratamientos previos.

**Oral Hygiene Education (Educación en higiene oral):**
Estrategia de orientación dirigida a los pacientes, centrada en promover prácticas adecuadas de cuidado dental —como el cepillado correcto y el uso de hilo dental— con el fin de prevenir enfermedades y mantener una buena salud bucal.

**Radiographic Imaging (Imágenes radiográficas):**
Técnica diagnóstica basada en el uso de radiografías (rayos X) para visualizar las estructuras internas de la cavidad oral, como dientes, raíces y huesos maxilares.

**Patient Portal (Portal del paciente):**
Plataforma digital segura que permite al paciente interactuar con el consultorio dental, facilitando el acceso a su información clínica, la programación de citas, el pago de facturas y la comunicación con el profesional de salud.

**Revenue Cycle Management – RCM (Gestión del ciclo de ingresos):**
Proceso integral de gestión financiera que abarca desde la programación de citas hasta la facturación y el cobro, con el objetivo de optimizar los ingresos y reducir los costos operativos del consultorio.

**Compliance (Cumplimiento):**
Adopción y seguimiento riguroso de normativas legales, reglamentarias y éticas establecidas por organismos gubernamentales y profesionales que regulan el ejercicio de la odontología.

**Dental Practice Management Software (Software de gestión de consultorios dentales):**
Solución digital diseñada para asistir en la administración diaria del consultorio, incluyendo la gestión de citas, historiales clínicos, pagos, inventario y comunicaciones internas.

**Continuing Education (Educación continua):**
Programas formativos y cursos especializados orientados a que los profesionales odontológicos actualicen y amplíen sus conocimientos, asegurando la aplicación de técnicas modernas y el uso de tecnologías actuales en su práctica clínica.


# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

El To-Be Scenario Mapping muestra cómo los odontólogos podrán administrar su consultorio de manera más eficiente mediante aplicación web como aplicación móvil. Basándose en el As-Is Scenario Mapping, que permitió reconocer sus métodos de trabajo actuales y las dificultades que enfrentan, se planteó un escenario futuro optimizado. Esta comparación facilitó la identificación de oportunidades de mejora en procesos como la gestión de citas, pagos, historiales clínicos e inventario, y permitió diseñar una solución práctica, ajustada a sus necesidades y fácil de utilizar.

![to-be-scenario-mapping.png](Img/to-be-scenario-mapping.png)

## 3.2. User Stories

**Epics**

| Epic ID | Title                   | Description                                                                                    |
|---------|-------------------------|------------------------------------------------------------------------------------------------|
| EP01    | Autenticación y Usuario | Gestiona el acceso seguro de los usuarios al sistema mediante inicio de sesión y logout.       |
| EP02    | Gestión de Citas        | Permite crear, modificar, eliminar y gestionar recordatorios de citas de manera eficiente.     |
| EP03    | Gestión de Pacientes    | Controla el registro, modificación, visualización y eliminación de pacientes e historiales.    |
| EP04    | Gestión de Inventario   | Administra los objetos médicos, registrando entradas, salidas, ajustes e identificación.       |
| EP05    | Pagos                   | Gestiona el registro, historial y control de los pagos relacionados con tratamientos dentales. |
| EP06    | Landing Page            | Componentes relacionados al Landing Page                                                       |

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US01</td>
    <td>Odontólogo</td>
    <td>Baja</td>
    <td>EP01</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Registrar usuario</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como odontólogo, <br>quiero registrarme en la aplicación <br>para acceder a los servicios.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
    Escenario 1: Odontólogo se registra en la aplicación<br><br>
Dado que el odontólogo se ha registrado en la aplicación<br>
Cuando esté en registro<br>
Y complete los datos solicitados en el formulario de registro<br>
Y seleccione el botón Registrarme<br>
Entonces la aplicación redirigirá al personal odontológico a la pantalla de inicio.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US02</td>
    <td>Odontólogo</td>
    <td>Baja</td>
    <td>EP01</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Iniciar Sesión</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como Odontólogo, <br>quiero iniciar sesión en la aplicación <br>para acceder a las funcionalidades.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Odontólogo inicia sesión correctamente<br><br>
Dado que el personal del consultorio ya se encuentra registrado en la aplicación<br>
Cuando ingrese su correo y contraseña en el formulario de inicio de sesión<br>
Y seleccione el botón Iniciar Sesión<br>
Entonces la aplicación lo redirigirá a la pantalla de inicio con acceso a sus funcionalidades.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US03</td>
    <td>Odontólogo</td>
    <td>Medio</td>
    <td>EP02</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Mostrar citas</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como odontólogo, <br>quiero visualizar todas las citas registradas <br>para poder gestionar los horarios de atención.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Visualización de citas registradas<br><br>
Dado que el odontólogo ha iniciado sesión<br>
Y accede a la sección de citas<br>
Cuando se cargue la pantalla de citas<br>
Entonces la aplicación mostrará una lista con todas las citas registradas, incluyendo la información del paciente, fecha y hora.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US04</td>
    <td>Odontólogo</td>
    <td>Media</td>
    <td>EP02</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Editar Cita</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como odontólogo, <br>quiero poder editar la información de una cita ya registrada <br>para corregir errores o adaptarla a cambios de disponibilidad.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Modificación exitosa de una cita<br><br>
Dado que el odontólogo visualiza una cita futura<br>
Cuando edite los campos permitidos (fecha, hora, tratamiento, profesional)<br>
Entonces la información se actualizará correctamente en el sistema.<br>
Escenario 2: Cita pasada no editable<br><br>
Dado que una cita ya ha pasado<br>
Cuando el asistente intente editarla<br>
Entonces el sistema mostrará un mensaje indicando que no puede ser modificada.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US05</td>
    <td>Odontólogo</td>
    <td>Alta</td>
    <td>EP02</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Añadir citas</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">	Como odontólogo, <br>quiero registrar nuevas citas <br>para poder agendar la atención de los pacientes.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Registro de una nueva cita<br><br>
Dado que el odontólogo ha iniciado sesión<br>
Y se encuentra en la sección de citas<br>
Cuando seleccione la opción para añadir nueva cita<br>
Y complete los campos requeridos como paciente, fecha y hora<br>
Y confirme el registro<br>
Entonces la aplicación guardará la nueva cita y la mostrará en la lista de citas registradas.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US06</td>
    <td>Odontólogo</td>
    <td>Alta</td>
    <td>EP02</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Eliminar Cita</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como odontólogo, <br>quiero eliminar una cita del sistema <br>para evitar confusiones si un paciente cancela o reprograma.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Eliminación confirmada de cita futura<br><br>
Dado que el odontólogo accede a la lista de citas<br>
Cuando seleccione una cita futura y confirme la eliminación<br>
Entonces la cita será eliminada del sistema y se notificará al paciente.<br><br>
Escenario 2: Intento de eliminar cita pasada<br><br>
Dado que la cita ya ocurrió<br>
Cuando se intente eliminar<br>
Entonces el sistema impedirá la acción y mostrará un mensaje de restricción.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US07</td>
    <td>Odontólogo</td>
    <td>Media</td>
    <td>EP02</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Buscar Citas</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como personal del consultorio, <br>quiero buscar citas por fecha o mediante filtros <br>para localizar rápidamente una cita específica.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
Escenario 1: Búsqueda de cita por fecha<br><br>
Dado que el odontólogo se encuentra en la sección de citas<br>
Cuando ingrese una fecha en el campo de búsqueda<br>
Y seleccione el botón Buscar<br>
Entonces la aplicación mostrará las citas programadas para esa fecha.<br><br>
Escenario 2: Busqueda de citas por DNI<br>
Dado que el odontólogo se encuentra en la sección de citas<br>
Cuando ingrese el DNI de un paciente en el campo de busqueda<br>
Y seleccione el boton Buscar<br>
Entonces la aplicación mostrará las citas que coincidan con el DNI correspondiente.<br></td>
  </tr>
</table>
<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US08</td>
    <td>Odontólogo</td>
    <td>Media</td>
    <td>EP02</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Gestionar horarios de atención</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como odontólogo, <br>quisiera gestionar los horarios de atención de mi consultorio con las citas ya agendadas <br>para poder optimizar la disponibilidad de los especialistas.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Ver horarios de atención con citas agendadas<br><br>
Dado que soy un odontólogo autenticado en el sistema<br>
Cuando accedo a la sección de gestión de horarios de atención<br>
Entonces debo poder ver los horarios disponibles y ocupados, con las citas agendadas reflejadas en la agenda.<br><br>
Escenario 2: Editar horarios de atención<br><br>
Dado que soy un odontólogo autenticado en el sistema<br>
Cuando modifico los horarios de atención de un especialista<br>
Entonces el sistema debe actualizar automáticamente la disponibilidad y bloquear esos horarios para nuevas reservas si ya están ocupados por citas.<br>  
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US09</td>
    <td>Odontólogo</td>
    <td>Media</td>
    <td>EP05</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Pagar tratamiento</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como paciente, <br>quiero pagar mi tratamiento desde la plataforma <br>para mayor comodidad y rapidez en el proceso de atención.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Pago exitoso desde la plataforma<br><br>
Dado que el paciente ha iniciado sesión y tiene un tratamiento pendiente de pago<br>
Cuando acceda a la sección de pagos y complete los datos de su tarjeta<br>
Entonces el sistema procesará el pago y mostrará una confirmación.<br><br>
Escenario 2: Error en el pago<br><br>
Dado que el paciente intenta pagar<br>
Cuando ocurra un error en la transacción (fondos insuficientes, datos inválidos, etc.)<br>
Entonces el sistema mostrará un mensaje de error y permitirá reintentar el pago.<br><br>
Escenario 3: Ver historial de pagos<br><br>
Dado que el paciente ha realizado pagos anteriores<br>
Cuando acceda a la sección de historial<br>
Entonces podrá visualizar el detalle de los pagos realizados y sus estados.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US10</td>
    <td>Odontólogo</td>
    <td>Media</td>
    <td>EP05</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Historial de pagos</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como personal del consultorio, <br>quiero visualizar el historial de pagos realizados <br>para tener un control financiero detallado.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Visualización de historial de pagos<br><br>
Dado que el personal accede al módulo de pagos
Cuando seleccione la opción "Historial de pagos"
Entonces la aplicación mostrará una lista de todos los pagos registrados con su fecha, monto y paciente asociado.
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US11</td>
    <td>Odontólogo</td>
    <td>Alta</td>
    <td>EP03</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Mostrar pacientes</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como personal del consultorio, <br>quiero visualizar la lista de pacientes registrados <br>para consultar y gestionar sus datos.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Visualización de pacientes registrados<br><br>
Dado que el personal ha iniciado sesión en la aplicación
Y accede a la sección de pacientes
Cuando se cargue la pantalla
Entonces la aplicación mostrará una lista con los datos de todos los pacientes registrados.
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US12</td>
    <td>Odontólogo</td>
    <td>Alta</td>
    <td>EP03</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Añadir pacientes</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como personal del consultorio, <br>quiero registrar nuevos pacientes <br>para poder gestionarlos en las citas y tratamientos.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Registro de paciente<br><br>
Dado que el personal accede a la sección de pacientes
Cuando complete el formulario con los datos del nuevo paciente
Y presione "Guardar"
Entonces la aplicación registrará al paciente y lo mostrará en la lista.
    </td>

  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US13</td>
    <td>Odontólogo</td>
    <td>Alta</td>
    <td>EP03</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Editar paciente</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como personal del consultorio, <br>quiero modificar los datos de un paciente <br>para mantener su información actualizada.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Edición de datos exitosa<br><br>
Dado que el personal accede a la sección de pacientes
Y selecciona a un paciente de la lista
Cuando actualice los datos en el formulario
Y presione el botón "Guardar cambios"
Entonces el sistema actualizará la información del paciente correctamente.
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US14</td>
    <td>Odontólogo</td>
    <td>Media</td>
    <td>EP03</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Eliminar pacientes</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como personal del consultorio, <br>quiero eliminar un paciente inactivo o registrado por error <br>para mantener limpia la base de datos.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Eliminación de paciente<br><br>
Dado que el personal accede a la lista de pacientes
Cuando seleccione un paciente
Y elija la opción de eliminar
Y confirme la acción
Entonces la aplicación eliminará dicho registro de la base de datos.
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US15</td>
    <td>Odontólogo</td>
    <td>Media</td>
    <td>EP03</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Buscar Pacientes</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como personal del consultorio, <br>quiero buscar pacientes por DNI <br>para encontrarlos rápidamente en el sistema.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Búsqueda exitosa por DNI<br><br>
Dado que existen pacientes registrados
Cuando el personal ingrese un número de DNI en el campo de búsqueda
Y seleccione el botón de buscar
Entonces la aplicación mostrará al paciente correspondiente en los resultados.
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US16</td>
    <td>Odontólog</td>
    <td>Alta</td>
    <td>EP03</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Añadir historial clínico</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como personal del consultorio, <br>quiero registrar un nuevo historial clínico <br>para tener un seguimiento detallado del paciente.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Registro de historial clínico<br><br>
Dado que el personal accede al perfil de un paciente
Cuando seleccione "Añadir historial clínico"
Y complete los campos requeridos
Y presione "Guardar"
Entonces la aplicación almacenará el nuevo historial vinculado al paciente.
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US17</td>
    <td>Odontólogo</td>
    <td>Media</td>
    <td>EP03</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Eliminar historial clínico</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como personal del consultorio, <br>quiero eliminar un historial clínico <br>para mantener la información actualizada y precisa.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Eliminación de historial clínico<br><br>
Dado que el personal accede al historial clínico de un paciente
Cuando seleccione la opción de eliminar historial
Y confirme la acción
Entonces la aplicación eliminará dicho historial y actualizará la vista.
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US18</td>
    <td>Odontólogo</td>
    <td>Media</td>
    <td>EP03</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Mostrar historial clínico</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como personal del consultorio, <br>quiero visualizar el historial clínico de un paciente <br>para revisar sus antecedentes y tratamientos.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Visualización del historial clínico<br><br>
Dado que el personal accede al perfil de un paciente
Cuando seleccione "Ver historial clínico"
Entonces la aplicación mostrará todos los registros clínicos asociados a dicho paciente.
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US19</td>
    <td>Odontólogo</td>
    <td>Alta</td>
    <td>EP04</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Visualizar Inventario</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como personal del consultorio, <br>quiero acceder al inventario general <br>para revisar la disponibilidad de materiales y equipos.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Visualización del inventario<br><br>
Dado que el personal se encuentra correctamente logueado en la apliacion.
Cuando acceda al módulo de inventario
Entonces la aplicación mostrará la lista de todos los objetos registrados con su stock disponible.
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US20</td>
    <td>Odontólogo</td>
    <td>Alta</td>
    <td>EP04</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Añadir objeto al inventario</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como personal del consultorio, <br>quiero añadir nuevos objetos al inventario <br>para mantener actualizado el stock disponible.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Registro de nuevo objeto<br><br>
Dado que el personal accede al módulo de inventario
Cuando seleccione "Añadir objeto"
Y complete los campos requeridos (nombre, tipo, cantidad)
Entonces la aplicación registrará el objeto en el inventario.
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US21</td>
    <td>Odontólogo</td>
    <td>Alta</td>
    <td>EP03</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Editar objeto de inventario</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como personal del consultorio, <br>quiero modificar los datos de un objeto del inventario <br>para reflejar información correcta y actualizada.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Modificación de objeto del inventario<br><br>
Dado que el personal accede a la sección de inventario
Cuando seleccione un objeto de la lista
Y actualice su información
Y presione "Guardar cambios"
Entonces la aplicación guardará la información modificada del objeto.
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US22</td>
    <td>Odontólogo</td>
    <td>Alta</td>
    <td>EP04</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Eliminar objeto de inventario</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como personal del consultorio, <br>quiero eliminar objetos del inventario. <br>para mantener mis registros actualizados</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Eliminación de objeto<br><br>
Dado que el personal accede a la lista del inventario
Cuando seleccione un objeto
Y presione "Eliminar"
Y confirme la acción
Entonces la aplicación eliminará el objeto seleccionado.
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US23</td>
    <td>Odontólogo</td>
    <td>Media</td>
    <td>EP04</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Dashboard de inventario</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como personal del consultorio, <br>quiero visualizar un resumen del inventario <br>para tomar decisiones sobre abastecimiento.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Visualización del dashboard<br><br>
Dado que el personal accede a la seccion de inventario
Cuando seleccione la opción de "Dashboard"
Entonces la aplicación mostrará gráficos y métricas de stock, consumo y disponibilidad.
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US24</td>
    <td>Odontólogo</td>
    <td>Media</td>
    <td>EP04</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Guardar fecha de ajuste</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como personal del consultorio, <br>quiero que se guarde la fecha del ajuste del inventario <br>para poder llevar un seguimiento de movimientos.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Registro de fecha de ajuste<br><br>
Dado que se está registrando una acción de consumo o edición en el inventario
Cuando se complete el proceso
Entonces la aplicación registrará automáticamente la fecha del ajuste en el historial.
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US25</td>
    <td>Odontólogo</td>
    <td>Alta</td>
    <td>EP04</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Registrar cantidad consumida de ítems</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como personal del consultorio, <br>quiero registrar la cantidad de objetos usados en cada tratamiento <br>para llevar un control detallado de insumos.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">Escenario 1: Registro de consumo de objetos<br><br>
Dado que se realiza una facturación asociada a un tratamiento
Cuando se especifique la cantidad utilizada de cada objeto
Entonces el sistema almacenará dicha cantidad como parte del historial de consumo.</td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US26</td>
    <td>Odontólogo</td>
    <td>Baja</td>
    <td>EP01</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Gestión del Perfil</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como personal del consultorio, <br>quiero acceder y editar mi perfil <br>para mantener mi información personal actualizada.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Visualización y edición del perfil<br><br>
Dado que el personal ha iniciado sesión
Cuando acceda a la sección de perfil
Entonces podrá visualizar su información registrada
Y si edita sus datos y guarda los cambios
Entonces la aplicación actualizará su perfil correctamente.
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US27</td>
    <td>Visitante</td>
    <td>Baja</td>
    <td>EP06</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Visualización del menú principal</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como visitante del sitio, <br>quiero ver un menú principal en la parte superior de la página <br>para acceder fácilmente a otras secciones.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 01: Menu visualizado
Dado que estoy en la landing page,
Cuando se carga el sitio,
Entonces el menú principal debe estar visible en la parte superior y mostrar enlaces a About Us, Services, Contact Us y Formulario.
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US28</td>
    <td>Visitante</td>
    <td>Baja</td>
    <td>EP06</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Navegación por la barra principal</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como visitante del sitio, <br>quiero poder hacer clic en los elementos del menú <br>para navegar a las secciones correspondientes de la misma página.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
       Escenario 01: Navegación sencilla
Dado que estoy en la landing page,
Cuando hago clic en "About Us",
Entonces la vista debe desplazarse suavemente a la sección "About Us".
Y lo mismo debe suceder con "Services", "Contact Us" y "Formulario".
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US29</td>
    <td>Visitante</td>
    <td>Baja</td>
    <td>EP06</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Sección About Us</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como visitante del sitio, <br>quiero ver información sobre la empresa en la sección About Us <br>para conocer su misión y valores.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">Escenario 01: Contenido about us<br><br>
Dado que he navegado a la sección About Us,
Entonces debo ver texto con información clara sobre la empresa,
Y un diseño consistente con el resto de la página.</td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US30</td>
    <td>Visitante</td>
    <td>Baja</td>
    <td>EP06</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Sección de Servicios</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como visitante del sitio, <br>quiero conocer los servicios ofrecidos <br>para saber si se ajustan a mis necesidades.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 01: Visualizar información de servicios<br><br>
Dado que estoy en la sección de Servicios,
Entonces debo ver una lista o tarjetas con los servicios ofrecidos,
Y cada servicio debe tener un título y una breve descripción.
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US31</td>
    <td>Visitante</td>
    <td>Baja</td>
    <td>EP06</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Sección Contact Us</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como visitante del sitio, <br>quiero tener acceso a datos de contacto <br>para poder comunicarme con la empresa.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">Escenario 01: Visualizar datos de contacto
Dado que estoy en la sección de Contact Us,
Entonces debo ver una dirección, número de teléfono y correo electrónico válidos,
Y deben estar visibles y legibles
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US32</td>
    <td>Visitante</td>
    <td>Baja</td>
    <td>EP06</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Formulario de contacto</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como visitante del sitio,<br> quiero poder enviar un formulario de contacto con mis datos <br>para recibir más información.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 01: Envio de datos de contacto
Dado que estoy en la sección del formulario,
Cuando completo mis datos (nombre, email, mensaje),
Y presiono el botón enviar,
Entonces el sistema debe confirmar que el mensaje fue enviado correctamente o mostrar un mensaje de error en caso contrario.
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>US33</td>
    <td>Visitante</td>
    <td>Baja</td>
    <td>EP06</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Footer informativo</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como visitante del sitio,<br> quiero ver información adicional en el pie de página <br>para acceder a datos legales o complementarios.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 01: Ver contenido del footer
      Dado que estoy al final de la página,
      Entonces debo ver un footer con información como derechos de autor,
      Y enlaces a redes sociales o políticas del sitio si están disponibles.
    </td>
  </tr>
</table>

**Technical Stories**

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS01</td>
    <td>Desarrollador</td>
    <td>Alta</td>
    <td>EP04</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para crear un ítem de inventario</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint POST /api/v1/items<br>
Para que los usuarios puedan registrar nuevos ítems en el inventario.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1:Creación exitosa<br><br>
      Dado que el cuerpo de la solicitud contiene datos válidos<br>
      Cuando se consuma POST /api/v1/items<br>
      Entonces el sistema debe responder con 201 Created y devolver el ítem creado en formato JSON.<br><br>
      Escenario 2:Error de validación<br><br>
      Dado que el cuerpo de la solicitud contiene datos inválidos o incompletos<br>
      Cuando se consuma POST /api/v1/items<br>
      Entonces el sistema debe responder con 400 Bad Request.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS02</td>
    <td>Desarrollador</td>
    <td>Alta</td>
    <td>EP04</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para actualizar un ítem de inventario</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint PUT /api/v1/items/{id}<br>
Para que se pueda modificar un ítem existente del inventario</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Actualización exitosa:<br><br>
      Dado que el ID corresponde a un ítem existente<br>
      Y el cuerpo de la solicitud contiene datos válidos<br>
      Cuando se consuma PUT /api/v1/items/{id}<br>
      Entonces el sistema debe responder con 200 OK y devolver los datos actualizados.<br><br>
      Escenario 2 – Error de validación:<br><br>
      Dado que el cuerpo de la solicitud contiene datos inválidos o faltantes<br>
      Cuando se consuma PUT /api/v1/items/{id}<br>
      Entonces el sistema debe responder con 400 Bad Request.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS03</td>
    <td>Desarrollador</td>
    <td>Alta</td>
    <td>EP04</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para eliminar un ítem de inventario</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint DELETE /api/v1/items/{id}<br>
Para que se pueda eliminar un ítem del inventario mediante su identificador.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Eliminación exitosa:<br><br>
      Dado que el ID corresponde a un ítem existente<br>
      Cuando se consuma DELETE /api/v1/items/{id}<br>
      Entonces el sistema debe responder con 204 No Content.<br><br>
      Escenario 2 – Error en la eliminación:<br><br>
      Dado que el ID es inválido o el ítem no puede eliminarse<br>
      Cuando se consuma DELETE /api/v1/items/{id}<br>
      Entonces el sistema debe responder con 400 Bad Request.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS04</td>
    <td>Desarrollador</td>
    <td>Alta</td>
    <td>EP04</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para obtener un ítem de inventario por ID </td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint GET /api/v1/items/{id}<br>
Para que se pueda recuperar un ítem específico del inventario mediante su ID.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Ítem encontrado:<br><br>
      Dado que existe un ítem con un ID válido en la base de datos<br>
      Cuando se consuma GET /api/v1/items/{id}<br>
      Entonces el sistema debe responder con 200 OK y devolver el objeto en formato JSON.<br><br>
      Escenario 2 – Ítem no encontrado:<br><br>
      Dado que el ID no corresponde a ningún registro<br>
      Cuando se consuma GET /api/v1/items/{id}<br>
      Entonces el sistema debe responder con 404 Not Found.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS05</td>
    <td>Desarrollador</td>
    <td>Alta</td>
    <td>EP04</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para obtener todos los ítems de inventario de un usuario</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint GET /api/v1/items<br>
Para que se puedan recuperar todos los ítems de inventario registrados por un usuario.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Inventario encontrado:<br><br>
      Dado que el usuario tiene ítems registrados en el sistema<br>
      Cuando se consuma GET /api/v1/items con un parámetro de usuario válido<br>
      Entonces el sistema debe responder con 200 OK y devolver la lista de ítems en formato JSON.<br><br>
      Escenario 2 – Inventario vacío:<br><br>
      Dado que el usuario no tiene ítems registrados<br>
      Cuando se consuma GET /api/v1/items<br>
      Entonces el sistema debe responder con 404 Not Found.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS06</td>
    <td>Desarrollador</td>
    <td>Alta</td>
    <td>EP03</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para crear un paciente</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint POST /api/v1/patients<br>
Para permitir el registro de nuevos pacientes en el sistema.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1: Creación exitosa:<br><br>
Dado que el cuerpo de la solicitud contiene datos válidos<br>
Cuando se consuma POST /api/v1/patients<br>
Entonces el sistema debe responder con 201 Created y devolver el paciente registrado en formato JSON.<br><br>
Escenario 2: Error de validación:<br><br>
Dado que el cuerpo de la solicitud contiene datos inválidos o incompletos<br>
Cuando se consuma POST /api/v1/patients<br>
Entonces el sistema debe responder con 400 Bad Request.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS07</td>
    <td>Desarrollador</td>
    <td>Alta</td>
    <td>EP03</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para actualizar un paciente</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint PUT /api/v1/patients/{id}<br>
Para que se pueda modificar la información de un paciente existente.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Actualización exitosa:<br><br>
Dado que el ID corresponde a un paciente existente<br>
Y el cuerpo de la solicitud contiene datos válidos<br>
Cuando se consuma PUT /api/v1/patients/{id}<br>
Entonces el sistema debe responder con 200 OK y devolver los datos actualizados.<br><br>
Escenario 2 – Error de validación:<br><br>
Dado que el cuerpo de la solicitud contiene datos inválidos o faltantes<br>
Cuando se consuma PUT /api/v1/patients/{id}<br>
Entonces el sistema debe responder con 400 Bad Request.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS08</td>
    <td>Desarrollador</td>
    <td>Media</td>
    <td>EP03</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para eliminar un paciente</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint DELETE /api/v1/patients/{id}<br>
Para que se pueda eliminar un paciente del sistema mediante su identificador.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Eliminación exitosa:<br><br>
Dado que el ID corresponde a un paciente existente<br>
Cuando se consuma DELETE /api/v1/patients/{id}<br>
Entonces el sistema debe responder con 204 No Content.<br><br>
Escenario 2 – Error en la eliminación:<br><br>
Dado que el ID es inválido o el paciente no puede eliminarse<br>
Cuando se consuma DELETE /api/v1/patients/{id}<br>
Entonces el sistema debe responder con 400 Bad Request.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS09</td>
    <td>Desarrollador</td>
    <td>Media</td>
    <td>EP03</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para obtener un paciente por ID</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint GET /api/v1/patients/{id}<br>
Para recuperar la información de un paciente mediante su identificador único.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Paciente encontrado:<br><br>
Dado que existe un paciente con un ID válido en la base de datos<br>
Cuando se consuma GET /api/v1/patients/{id}<br>
Entonces el sistema debe responder con 200 OK <br>
Y devolver la información del paciente en formato JSON.<br><br>
Escenario 2 – Paciente no encontrado:<br><br>
Dado que el ID no corresponde a ningún paciente registrado<br>
Cuando se consuma GET /api/v1/patients/{id}<br>
Entonces el sistema debe responder con 404 Not Found.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS10</td>
    <td>Desarrollador</td>
    <td>Media</td>
    <td>EP03</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para obtener todos los pacientes de un usuario autenticado</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint GET /api/v1/patients<br>
Para recuperar la lista de pacientes vinculados al usuario autenticado.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Pacientes encontrados:<br><br>
      Dado que el usuario tiene pacientes registrados<br>
      Cuando se consuma GET /api/v1/patients<br>
      Entonces el sistema debe responder con 200 OK<br> 
      Y devolver la lista de pacientes en formato JSON.<br><br>
      Escenario 2 – Ningún paciente encontrado:<br><br>
      Dado que el usuario autenticado no tiene pacientes registrados<br>
      Cuando se consuma GET /api/v1/patients<br>
      Entonces el sistema debe responder con 404 Not Found.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS11</td>
    <td>Desarrollador</td>
    <td>Alta</td>
    <td>EP03</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para añadir una historia clínica a un paciente</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint POST /api/v1/patients/{patientId}/medical-histories<br>
Para registrar una nueva historia clínica vinculada a un paciente específico.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Creación exitosa:<br><br>
Dado que el patientId corresponde a un paciente existente<br>
Y el cuerpo de la solicitud contiene datos válidos<br>
Cuando se consuma POST /api/v1/patients/{patientId}/medical-histories<br>
Entonces el sistema debe responder con 201 Created y devolver la historia clínica creada.<br><br>
Escenario 2 – Error de validación:<br><br>
Dado que el cuerpo de la solicitud contiene datos inválidos o incompletos<br>
Cuando se consuma POST /api/v1/patients/{patientId}/medical-histories<br>
Entonces el sistema debe responder con 400 Bad Request.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS12</td>
    <td>Desarrollador</td>
    <td>Alta</td>
    <td>EP04</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para obtener historias clínicas por ID de paciente</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint GET /api/v1/patients/{patientId}/medical-histories<br>
Para recuperar todas las historias clínicas registradas para un paciente específico.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Historias clínicas encontradas:<br><br>
      Dado que el paciente con ID válido tiene historias clínicas registradas<br>
      Cuando se consuma GET /api/v1/patients/{patientId}/medical-histories<br>
      Entonces el sistema debe responder con 200 OK<br> 
      Y devolver la lista de historias en formato JSON.<br><br>
      Escenario 2 – Ninguna historia clínica encontrada:<br><br>
      Dado que el paciente no tiene historias clínicas registradas<br>
      Cuando se consuma GET /api/v1/patients/{patientId}/medical-histories<br>
      Entonces el sistema debe responder con 404 Not Found.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS13</td>
    <td>Desarrollador</td>
    <td>Alta</td>
    <td>EP02</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para crear una cita</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint POST /api/v1/appointments<br>
Para permitir el registro de nuevas citas médicas.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Creación exitosa:<br><br>
Dado que el cuerpo de la solicitud contiene datos válidos<br>
Cuando se consuma POST /api/v1/appointments<br>
Entonces el sistema debe responder con 201 Created y devolver la cita registrada.<br><br>
Escenario 2 – Error de validación:<br><br>
Dado que el cuerpo de la solicitud contiene datos inválidos o incompletos<br>
Cuando se consuma POST /api/v1/appointments<br>
Entonces el sistema debe responder con 400 Bad Request.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS14</td>
    <td>Desarrollador</td>
    <td>Alta</td>
    <td>EP02</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para actualizar una cita</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint PUT /api/v1/appointments/{appointmentId}<br>
Para que se pueda modificar una cita existente.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Actualización exitosa:<br><br>
Dado que el appointmentId corresponde a una cita existente<br>
Y el cuerpo de la solicitud contiene datos válidos<br>
Cuando se consuma PUT /api/v1/appointments/{appointmentId}<br>
Entonces el sistema debe responder con 200 OK y devolver los datos actualizados de la cita.<br><br>
Escenario 2 – Error de validación:<br><br>
Dado que el cuerpo de la solicitud contiene datos inválidos o incompletos<br>
Cuando se consuma PUT /api/v1/appointments/{appointmentId}<br>
Entonces el sistema debe responder con 400 Bad Request.<br><br>
Escenario 3 – Cita no encontrada:<br><br>
Dado que el appointmentId no corresponde a ninguna cita registrada<br>
Cuando se consuma PUT /api/v1/appointments/{appointmentId}<br>
Entonces el sistema debe responder con 404 Not Found.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS15</td>
    <td>Desarrollador</td>
    <td>Alta</td>
    <td>EP02</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para eliminar una cita</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint DELETE /api/v1/appointments/{appointmentId}<br>
Para que se pueda eliminar una cita registrada.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Eliminación exitosa:<br><br>
Dado que el appointmentId corresponde a una cita existente<br>
Cuando se consuma DELETE /api/v1/appointments/{appointmentId}<br>
Entonces el sistema debe responder con 200 OK confirmando la eliminación.<br><br>
Escenario 2 – Cita no encontrada:<br><br>
Dado que el appointmentId no corresponde a ninguna cita registrada<br>
Cuando se consuma DELETE /api/v1/appointments/{appointmentId}<br>
Entonces el sistema debe responder con 404 Not Found.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS16</td>
    <td>Desarrollador</td>
    <td>Media</td>
    <td>EP02</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para obtener todas las citas del usuario autenticado</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint GET /api/v1/appointments<br>
Para recuperar todas las citas médicas asociadas al usuario autenticado.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Citas encontradas:<br><br>
Dado que el usuario autenticado tiene citas registradas<br>
Cuando se consuma GET /api/v1/appointments<br>
Entonces el sistema debe responder con 200 OK y devolver la lista de citas en formato JSON.<br><br>
Escenario 2 – Ninguna cita encontrada:<br><br>
Dado que el usuario autenticado no tiene citas registradas<br>
Cuando se consuma GET /api/v1/appointments<br>
Entonces el sistema debe responder con 404 Not Found.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS17</td>
    <td>Desarrollador</td>
    <td>Media</td>
    <td>EP02</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para obtener todas las citas de un paciente</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint GET /api/v1/appointments/{patientId}<br>
Para recuperar todas las citas asociadas a un paciente específico del usuario autenticado.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Citas encontradas:<br><br>
Dado que el paciente con patientId válido tiene citas registradas<br>
Cuando se consuma GET /api/v1/appointments/{patientId}<br>
Entonces el sistema debe responder con 200 OK y devolver la lista de citas.<br><br>
Escenario 2 – Ninguna cita encontrada:<br><br>
Dado que el paciente con patientId no tiene citas registradas<br>
Cuando se consuma GET /api/v1/appointments/{patientId}<br>
Entonces el sistema debe responder con 404 Not Found.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS18</td>
    <td>Desarrollador</td>
    <td>Alta</td>
    <td>EP02</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para obtener una cita por ID</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint GET /api/v1/appointments/appointment/{id}<br>
Para recuperar los detalles de una cita específica del usuario autenticado.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Cita encontrada:<br><br>
      Dado que existe una cita con el id proporcionado para el usuario autenticado<br>
      Cuando se consuma GET /api/v1/appointments/appointment/{id}<br>
      Entonces el sistema debe responder con 200 OK y devolver los detalles de la cita.<br><br>
      Escenario 2 – Cita no encontrada:<br><br>
      Dado que el id no corresponde a ninguna cita registrada del usuario autenticado<br>
      Cuando se consuma GET /api/v1/appointments/appointment/{id}<br>
      Entonces el sistema debe responder con 404 Not Found.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS19</td>
    <td>Desarrollador</td>
    <td>Media</td>
    <td>EP05</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para crear una factura</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint POST /api/v1/invoices<br>
Para permitir la creación de nuevas facturas en el sistema.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Creación exitosa:<br><br>
Dado que el cuerpo de la solicitud contiene datos válidos<br>
Cuando se consuma POST /api/v1/invoices<br>
Entonces el sistema debe responder con 201 Created y devolver la factura registrada en formato JSON.<br><br>
Escenario 2 – Error de validación:<br><br>
Dado que el cuerpo de la solicitud contiene datos inválidos o incompletos<br>
Cuando se consuma POST /api/v1/invoices<br>
Entonces el sistema debe responder con 400 Bad Request.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS20</td>
    <td>Desarrollador</td>
    <td>Media</td>
    <td>EP05</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para obtener todas las facturas del usuario autenticado</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint GET /api/v1/invoices<br>
Para recuperar todas las facturas asociadas al usuario autenticado.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Facturas encontradas:<br><br>
Dado que el usuario autenticado tiene facturas registradas<br>
Cuando se consuma GET /api/v1/invoices<br>
Entonces el sistema debe responder con 200 OK y devolver la lista de facturas en formato JSON.<br>
Escenario 2 – Ninguna factura encontrada:<br><br>
Dado que el usuario autenticado no tiene facturas registradas<br>
Cuando se consuma GET /api/v1/invoices<br>
Entonces el sistema debe responder con 404 Not Found.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS21</td>
    <td>Desarrollador</td>
    <td>Media</td>
    <td>EP05</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para obtener una factura por ID de cita</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint GET /api/v1/invoices/{appointmentId}<br>
Para recuperar la factura asociada a una cita específica.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Factura encontrada:<br><br>
      Dado que existe una factura registrada para el appointmentId proporcionado<br>
      Cuando se consuma GET /api/v1/invoices/{appointmentId}<br>
      Entonces el sistema debe responder con 200 OK y devolver la factura en formato JSON.<br><br>
      Escenario 2 – Factura no encontrada:<br><br>
      Dado que el appointmentId no tiene facturas asociadas<br>
      Cuando se consuma GET /api/v1/invoices/{appointmentId}<br>
      Entonces el sistema debe responder con 404 Not Found.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS22</td>
    <td>Desarrollador</td>
    <td>Baja</td>
    <td>EP01</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para registrar un usuario</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint POST /api/auth/register<br>
Para que los nuevos usuarios puedan registrarse en el sistema.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Registro exitoso:<br><br>
Dado que el cuerpo de la solicitud contiene datos válidos (ej. nombre, correo, contraseña)<br>
Cuando se consuma POST /api/auth/register<br>
Entonces el sistema debe responder con 200 OK y registrar al nuevo usuario.<br><br>
Escenario 2 – Error de validación:<br><br>
Dado que el cuerpo de la solicitud contiene datos inválidos, incompletos o un correo ya registrado<br>
Cuando se consuma POST /api/auth/register<br>
Entonces el sistema debe responder con 400 Bad Request.<br>
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>TS23</td>
    <td>Desarrollador</td>
    <td>Baja</td>
    <td>EP01</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Implementar endpoint para iniciar sesión</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero implementar el endpoint POST /api/auth/login<br>
Para que los usuarios registrados puedan autenticarse en el sistema.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Inicio de sesión exitoso:<br><br>
Dado que las credenciales proporcionadas (correo y contraseña) son válidas<br>
Cuando se consuma POST /api/auth/login<br>
Entonces el sistema debe responder con 200 OK y devolver el token de autenticación.<br><br>
Escenario 2 – Usuario no encontrado o credenciales inválidas:<br><br>
Dado que las credenciales no corresponden a ningún usuario registrado<br>
Cuando se consuma POST /api/auth/login<br>
Entonces el sistema debe responder con 404 Not Found.<br>
    </td>
  </tr>
</table>

**Spike Stories**

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>SS01</td>
    <td>Desarrollador</td>
    <td>Alta</td>
    <td>EP02</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Investigar uso de Mockito para pruebas unitarias</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador<br>
Quiero investigar cómo integrar y usar Mockito en el proyecto<br>
Para facilitar la creación de pruebas unitarias más efectivas.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Configuración de entorno:<br><br>
Dado que el proyecto tiene un módulo de pruebas unitarias<br>
Cuando se agregue la librería de Mockito a la configuración del build (Maven)<br>
Entonces el entorno debe permitir la creación de mocks en las clases de prueba.<br><br>
Escenario 2 – Verificación de un mock:<br><br>
Dado que existe un servicio con dependencias<br>
Cuando se escriba una prueba unitaria usando Mockito<br>
Entonces debe ser posible simular la respuesta de la dependencia<br> 
Y validar la lógica del servicio sin llamar a implementaciones reales.
    </td>
  </tr>
</table>

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td><b>Story ID</b></td>
    <td><b>User</b></td>
    <td><b>Priority</b></td>
    <td><b>Epic</b></td>
  </tr>
  <tr>
    <td>SS02</td>
    <td>Desarrollador</td>
    <td>Baja</td>
    <td>EP02</td>
  </tr>
  <tr>
    <td><b>Title</b></td>
    <td colspan="3">Investigar el uso de Selenium para pruebas automatizadas</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Description</b></td>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador
Quiero investigar cómo implementar pruebas automatizadas con Selenium
Para validar el correcto funcionamiento de la interfaz de usuario y los flujos principales de la aplicación.</td>
  </tr>
  <tr>
    <td colspan="4" align="center"><b>Acceptance Criteria</b></td>
  </tr>
  <tr>
    <td colspan="4">
      Escenario 1 – Configuración de Selenium:<br><br>
Dado que se prepara un entorno de pruebas funcionales<br>
Cuando se agregue Selenium WebDriver a la configuración del proyecto<br>
Entonces se debe poder lanzar un navegador automatizado y abrir la aplicación.<br><br>
Escenario 2 – Prueba de flujo básico:<br><br>
Dado que un usuario ficticio accede a la aplicación<br>
Cuando el script de Selenium simule el login con credenciales válidas<br>
Entonces el sistema debe mostrar la página principal de la aplicación, validando que el flujo funciona correctamente.<br>
    </td>
  </tr>
</table>

## 3.3. Product Backlog

| #Orden | ID   | User Story                                                                      | Story Points |
|:-------|:-----|:--------------------------------------------------------------------------------|:-------------|
| 01     | SS01 | Investigar uso de Mockito para pruebas unitarias                                | 8            |
| 02     | SS02 | Investigar el uso de Selenium para pruebas automatizadas                        | 8            |
| 03     | US05 | Añadir citas                                                                    | 8            |
| 04     | US04 | Editar Citas                                                                    | 8            |
| 05     | US06 | Eliminar Cita                                                                   | 8            |
| 06     | US11 | Mostrar Pacientes                                                               | 8            |
| 07     | US12 | Añadir Pacientes                                                                | 8            |
| 08     | US13 | Editar Pacientes                                                                | 8            |
| 09     | US16 | Añadir Historial Clínico                                                        | 8            |
| 10     | US19 | Visualizar Inventario                                                           | 8            |
| 11     | US20 | Añadir objeto al inventario                                                     | 8            |
| 12     | US21 | Editar objeto del inventario                                                    | 8            |
| 13     | US22 | Eliminar objeto del inventario                                                  | 8            |
| 14     | US25 | Registrar cantidad consumida de ítems                                           | 8            |
| 15     | TS01 | Implementar endpoint para crear un ítem de inventario                           | 8            |
| 16     | TS02 | Implementar endpoint para actualizar un ítem de inventario                      | 8            |
| 17     | TS03 | Implementar endpoint para eliminar un ítem de inventario                        | 8            |
| 18     | TS04 | Implementar endpoint para obtener un ítem de inventario por ID                  | 8            |
| 19     | TS05 | Implementar endpoint para obtener todos los ítems de inventario de un usuario   | 8            |
| 20     | TS06 | Implementar endpoint para crear un paciente                                     | 8            |
| 21     | TS07 | Implementar endpoint para actualizar un paciente                                | 8            |
| 22     | TS08 | Implementar endpoint para eliminar un paciente                                  | 8            |
| 23     | TS11 | Implementar endpoint para añadir una historia clínica a un paciente             | 8            |
| 24     | TS12 | Implementar endpoint para obtener historias clínicas por ID de paciente         | 8            |
| 25     | TS13 | Implementar endpoint para crear una cita                                        | 8            |
| 26     | TS14 | Implementar endpoint para actualizar una cita                                   | 8            |
| 27     | TS15 | Implementar endpoint para eliminar una cita                                     | 8            |
| 28     | TS18 | Implementar endpoint para obtener una cita por ID                               | 8            |
| 29     | US03 | Mostrar Citas                                                                   | 5            |
| 30     | US07 | Buscar Citas                                                                    | 5            |
| 31     | US08 | Gestionar horarios de atención                                                  | 5            |
| 32     | US09 | Pagar tratamiento                                                               | 5            |
| 33     | US10 | Historial de pagos                                                              | 5            |
| 34     | US14 | Eliminar Pacientes                                                              | 5            |
| 35     | US15 | Buscar Pacientes                                                                | 5            |
| 36     | US17 | Eliminar historial clínico                                                      | 5            |
| 37     | US18 | Mostrar historial clínico                                                       | 5            |
| 38     | US23 | Dashboard de inventario                                                         | 5            |
| 39     | US24 | Guardar fecha de ajuste de inventario                                           | 5            |
| 40     | TS09 | Implementar endpoint para obtener un paciente por ID                            |              |
| 41     | TS10 | Implementar endpoint para obtener todos los pacientes de un usuario autenticado |              |
| 42     | TS16 | Implementar endpoint para obtener todas las citas del usuario autenticado       |              |
| 43     | TS17 | Implementar endpoint para obtener todas las citas de un paciente                |              |
| 44     | TS19 | Implementar endpoint para crear una factura                                     |              |
| 45     | TS20 | Implementar endpoint para obtener todas las facturas del usuario autenticado    |              |
| 46     | TS21 | Implementar endpoint para obtener una factura por ID de cita                    |              |
| 47     | US26 | Gestión del Perfil                                                              | 3            |
| 48     | US27 | Visualización del menú principal                                                | 3            |
| 49     | US28 | Navegación por la barra principal                                               | 3            |
| 50     | US29 | Sección About Us                                                                | 3            |
| 51     | US30 | Sección de Servicios                                                            | 3            |
| 52     | US31 | Sección Contact Us                                                              | 3            |
| 53     | US32 | Formulario de contacto                                                          | 3            |
| 54     | US33 | Footer informativo                                                              | 3            |
| 55     | US01 | Registrar Usuarios                                                              | 3            |
| 56     | US02 | Iniciar Sesión                                                                  | 3            |
| 57     | TS22 | Implementar endpoint para registrar un usuario                                  | 3            |
| 58     | TS23 | Implementar endpoint para iniciar sesión                                        | 3            |

## 3.4. Impact Mapping

El Impact Mapping es una técnica visual que permite conectar los objetivos del proyecto con las necesidades y expectativas de los principales actores involucrados. En este caso, ayuda a comprender cómo cada decisión de diseño impacta tanto en la experiencia de los odontólogos como en la de sus pacientes. A través de este mapa se identifican los resultados que se esperan alcanzar, los comportamientos que se desean fomentar y las funcionalidades que aportan valor real al consultorio.

![impact-mapping.png](Img/impact-mapping.png)

# Capítulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

**Nombre y Logotipo**

El nombre de la aplicación, Dentify, transmite innovación, profesionalismo y un enfoque claro en la gestión de consultorios odontológicos. El logotipo de Dentify está compuesto únicamente por un ícono de un diente sin acompañamiento de texto. Este símbolo representa de forma clara y directa el enfoque odontológico de la aplicación, transmitiendo profesionalismo, salud y confianza. Su diseño limpio y minimalista asegura una fácil identificación

![Logo](Img/Dentify-logo.png)

**Tono de comunicación**

Para el tono de comunicación se optó por uno con un efoque profesional, consiso, claro y que transmita confianza sin perder calidez. El lenguaje técnico será evitado en su mayoría y se priorizará expresiones accesibles para facilitar la comprensión.

**Colors**

La paleta de colores se basa en tonos de celeste y azul, que transmiten confianza, profesionalismo y tranquilidad, ideales para el entorno de la salud dental. Como colores secundarios se utilizan blanco, negro y gris, que aportan equilibrio visual, legibilidad y una estética limpia y moderna. Esta combinación refuerza una imagen clara, ordenada y amigable para los usuarios.

![colores](Img/paleta-de-colores.png)

**Typography**

La tipografía que se usará principalmente, dada su legibilidad, estilo y versatilidad, es Roboto.

![tipography](Img/tipografía.png)


### 4.1.2. Web Style Guidelines

**Spacing**

En nuestra aplicación web, se utilizarán márgenes de 19.5px entre las secciones principales para mantener una separación adecuada, padding interno de 18px en botones y componentes para mejorar la interacción, y un interlineado de 1.5x en textos extensos que facilita la lectura en pantalla. Esta consistencia en el diseño contribuye a reforzar la identidad visual de la plataforma y mejora la experiencia del usuario en entornos web.

**Íconos de la aplicación**

La aplicación utilizará íconos seleccionados para la mejor experiencia de usuario. Cada ícono cumple una función clara y está alineado con la identidad de la marca.

![iconos](Img/íconos-web.png)

**Lenguaje aplicado**

Para el desarrollo de la aplicación web “Dentify” y su correspondiente landing page, se ha adoptado un lenguaje formal, serio y respetuoso, alineado con el propósito y los objetivos del producto. En el diseño y construcción tanto de la aplicación web como de la landing page, se han aplicado los principios fundamentales del diseño visual.

**Consistencia**
Mantenemos una estructura y estilo uniformes en todo el producto digital. Esto incluye el uso coherente de elementos de diseño como tipografías, tamaños de fuente, paleta de colores y patrones de interacción, permitiendo que el usuario se adapte fácilmente a la interfaz y navegue con mayor facilidad.

**Simplicidad**
Eliminamos los elementos innecesarios o que pueden complicar la interfaz con el fin de que los usuarios puedan realizar sus tareas de manera más sencilla y rápida.

**Comunicación**
Hemos incorporado confirmaciones visuales que se presentan cuando los usuarios realizan alguna acción. Este tipo de retroalimentación les permite identificar su ubicación dentro del proceso y, sobre todo, verificar que sus acciones se han llevado a cabo correctamente.

### 4.1.3. Mobile Style Guidelines

#### 4.1.3.1. iOS Mobile Style Guidelines

**Nombre y Logotipo**

El nombre Dentify comunica innovación y profesionalismo, con un enfoque específico en la gestión de clínicas odontológicas. El logotipo, representado únicamente por un ícono de diente sin texto, transmite de forma directa el propósito de la app. Su diseño limpio y minimalista está optimizado para entornos iOS, facilitando su reconocimiento en interfaces móviles y reforzando la confianza del usuario.

![Logo](Img/Dentify-logo.png)

**Tono de Comunicación en la App Móvil**

La aplicación utiliza un tono profesional, claro y confiable, manteniendo una comunicación cálida y accesible. Se evita el uso excesivo de lenguaje técnico, priorizando expresiones simples que se adapten al estilo directo y fluido de iOS, facilitando la comprensión en pantallas pequeñas.


**Spacing**

Se aplica un sistema de espaciado coherente para mantener la interfaz ordenada:
- 19.5px entre secciones principales
- 18px de padding en botones y componentes
- Interlineado de 1.5x en textos extensos 

Este diseño mejora la legibilidad y la navegación en dispositivos iOS, respetando las guías de accesibilidad de Apple


**Íconos**

Los íconos están diseñados para cumplir funciones específicas y se alinean con la identidad visual de Dentify. Su estilo es simple y claro, optimizado para pantallas Retina, asegurando una experiencia fluida y coherente en iOS.

![iconos](Img/íconos.png)


**Consistencia**

Se mantiene una estructura uniforme en toda la app: tipografías, tamaños, colores y patrones de interacción se aplican de forma coherente, permitiendo que el usuario se familiarice rápidamente con la interfaz.

**Simplicidad**

Se eliminan elementos innecesarios para que la interfaz sea clara y funcional, permitiendo que los usuarios completen sus tareas de forma rápida y sin distracciones, en línea con el principio de “menos es más” de Apple

**Comunicación**

La app incorpora confirmaciones visuales tras cada acción del usuario, ofreciendo retroalimentación inmediata y clara, lo que mejora la experiencia y refuerza la confianza en el uso de la aplicación.

#### 4.1.3.2. Android Mobile Style Guidelines

**Nombre y Logotipo**

El nombre Dentify comunica innovación, profesionalismo y un enfoque especializado en la gestión de consultorios odontológicos. Su logotipo, compuesto únicamente por un ícono de diente sin texto, representa de forma directa el ámbito odontológico. El diseño minimalista y limpio facilita su reconocimiento en entornos móviles, transmitiendo confianza y salud.

![Logo](Img/Dentify-logo.png)

**Tono de Comunicación en la App Móvil**
Se ha definido un tono profesional, claro y confiable, manteniendo cercanía con el usuario. Se evita el uso excesivo de lenguaje técnico, priorizando expresiones accesibles que faciliten la comprensión en dispositivos móviles, donde la lectura debe ser rápida y efectiva.


**Spacing**
En la app móvil se aplica un sistema de espaciado coherente:

**Íconos**
La aplicación incorpora íconos funcionales y alineados con la identidad de marca. Cada ícono tiene un propósito específico, facilitando la navegación y mejorando la experiencia del usuario en pantallas pequeñas.

![iconos](Img/íconos.png)

**Lenguaje**
Tanto en la app como en su landing page, se utiliza un lenguaje serio y respetuoso, alineado con los objetivos del producto. Se prioriza la claridad para facilitar la interacción en dispositivos móviles.

**Consistencia**
Se mantiene una estructura uniforme en toda la app: tipografías, tamaños, colores y patrones de interacción se aplican de forma coherente, ayudando al usuario a adaptarse rápidamente a la interfaz.

**Simplicidad**
Se eliminan elementos innecesarios para que la interfaz sea clara y funcional, permitiendo que los usuarios completen sus tareas de forma rápida y sin distracciones.

**Comunicación**
Se incluyen confirmaciones visuales tras cada acción del usuario, brindando retroalimentación clara sobre el estado del proceso y asegurando que sus acciones se han realizado correctamente.


## 4.2. Information Architecture

### 4.2.1. Organization Systems

**App Móvil (Dentify)**
La interfaz de Dentify organiza sus secciones principales —como “Reserva de Citas”, “Pagar Tratamiento” y “Historial”— mediante títulos visibles, botones destacados y elementos interactivos que guían al usuario de forma intuitiva. Por ejemplo, “Reservar Citas” se ubica en una posición prioritaria dentro de la pantalla principal o como botón flotante, lo que permite un acceso rápido y directo.

**Landing Page (ClinicCode)**
Las secciones como “Nosotros”, “Servicios”, “Información” y “Contáctenos” se presentan con encabezados grandes y llamados a la acción claros, facilitando la navegación del visitante. En “Servicios”, se utilizan íconos representativos y botones que conducen a más detalles sobre soluciones destacadas como Dentify.

#### Categorización del Contenido
**App Móvil (Dentify)**
Las funcionalidades están organizadas en categorías intuitivas como “Citas”, “Pagos” y “Historial”, lo que permite al usuario encontrar rápidamente lo que necesita. Por ejemplo, funciones específicas como “Gestión de Inventario” se agrupan en una sección administrativa, accesible únicamente para usuarios premium.

**Landing Page (ClinicCode)**
El contenido se distribuye en secciones informativas bien definidas. “Nosotros” reúne la historia y el equipo; “Servicios” detalla las soluciones ofrecidas; y en “Información”, los temas están organizados por áreas como eficiencia clínica o gestión de citas, lo que facilita su exploración.

#### Secuencia de Contenidos
**App Móvil (Dentify)**
La experiencia de uso sigue una secuencia lógica: tras iniciar sesión, el usuario accede al menú principal y luego a funciones frecuentes como reservas o consultas. Por ejemplo, al ingresar, se muestra en primer plano la opción “Reserva de Citas”, lo que permite una navegación fluida y enfocada.

**Landing Page (ClinicCode)**
La estructura del sitio sigue un orden progresivo: comienza con la presentación de la empresa, continúa con los servicios y finaliza en la sección de contacto. Esto permite que el visitante conozca primero las soluciones disponibles, luego acceda a información detallada y finalmente encuentre cómo comunicarse.

#### Agrupación de Funcionalidades
**App Móvil (Dentify)**
Las funciones están agrupadas por áreas de uso para mejorar la experiencia. Por ejemplo, “Perfil” incluye configuraciones personales; “Citas” reúne programación, recordatorios y seguimiento. Los métodos de pago y facturación se integran en “Pagos”, mientras que la información médica del paciente se organiza dentro de “Historial”.

**Landing Page (ClinicCode)**
Las secciones funcionales están estructuradas para facilitar la navegación. “Servicios” agrupa todas las soluciones que ofrece la empresa, y “Contáctenos” centraliza los medios de comunicación. Dentro de “Servicios”, se puede destacar una subsección dedicada a Dentify como propuesta innovadora.

### 4.2.2. Labeling Systems

**Aplicación Móvil (Dentify)**
Se han utilizado etiquetas claras y precisas que describen directamente la función de cada sección, lo que permite a los usuarios identificar fácilmente las acciones disponibles dentro de la app. Por ejemplo, en el menú principal se emplean términos como “Reservar Cita”, “Historial” y “Pagos”, que comunican de forma directa lo que el usuario encontrará al ingresar. En la sección “Perfil”, opciones como “Editar Información Personal” y “Modificar Contraseña” están nombradas de manera específica, lo que ayuda a guiar al usuario sin generar confusión.

**Landing Page (ClinicCode)**
Las secciones del sitio están etiquetadas con términos comprensibles y directos, como “Servicios” o “Información”, lo que facilita la navegación desde cualquier dispositivo. Un ejemplo claro se encuentra en la sección “Contáctenos”, donde se diferencian las vías de comunicación mediante etiquetas como “Formulario de Consulta”, “Llamada Telefónica” y “Atención por Chat”, permitiendo al usuario elegir fácilmente el canal que prefiera.

### 4.2.3. SEO Tags and Meta Tags

Se han aplicado estrategias de posicionamiento en tiendas de aplicaciones mediante técnicas de ASO (App Store Optimization), con el objetivo de que Dentify sea fácilmente encontrada por profesionales del área odontológica que buscan soluciones móviles para la gestión de sus consultorios.

Se han definido elementos clave como:

- **Título de la App:**
“Dentify - Gestión Dental Móvil por ClinicCode”

- **Descripción de la App:**
“Organiza tus citas, tratamientos y pacientes desde una sola app. Dentify optimiza la administración de tu consultorio dental desde cualquier lugar.”

- **Palabras Clave:**
“app dental, gestión de citas, consultorio móvil, odontología digital, Dentify ClinicCode”

### 4.2.4. Searching Systems

**Aplicación Móvil (Dentify)**

Se ha integrado una función de búsqueda optimizada que permite a los usuarios encontrar rápidamente información relevante dentro de la app, como citas programadas, registros de pacientes o tratamientos específicos.
Por ejemplo, la búsqueda incluye filtros por fecha, profesional de salud o tipo de procedimiento, lo que facilita el acceso ágil a los datos desde cualquier sección, incluso en dispositivos con pantallas pequeñas.

**Landing Page (ClinicCode)**

Se ha implementado una barra de búsqueda sencilla que ayuda a los visitantes a localizar contenidos específicos, como artículos informativos o detalles sobre los servicios ofrecidos.
Un ejemplo se encuentra en la sección “Información”, donde los usuarios pueden buscar temas concretos como “automatización de citas” o “eficiencia administrativa en consultorios dentales”.

### 4.2.5. Navigation Systems

Menú Principal:

**Aplicación Móvil (Dentify)**
- El menú principal ha sido diseñado para ser intuitivo y accesible desde cualquier pantalla mediante un botón desplegable (hamburger menu), que ofrece acceso directo a funciones clave como “Citas”, “Pagos” e “Historial”. Este menú se adapta a pantallas pequeñas y prioriza la facilidad de uso en movimiento.
- Ejemplo: Los usuarios premium pueden acceder rápidamente al soporte técnico desde cualquier sección, ya sea mediante un ícono fijo en el menú o accesos rápidos en la pantalla principal.

**Landing Page (ClinicCode)**
- Se utiliza un menú superior fijo que permanece visible al hacer scroll, con enlaces a las secciones principales del sitio. Está optimizado para dispositivos móviles, con íconos representativos y un diseño compacto.
- Ejemplo: En la vista móvil, el menú muestra íconos claros para acceder a “Nosotros”, “Servicios” y al chat de ayuda, mejorando la navegación desde smartphones.

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe
Nosotros

![Nosotros](Img/Nosotros.png)

Servicios
![Servicios](Img/Servicios.png)

Contáctenos
![Contáctenos](Img/Contactanos.png)

![contactenos2](Img/Contactanos2.png)

### 4.3.2. Landing Page Mock-up

Nosotros
![Nosotros](Img/m-Nosotros.png)

Servicios
![Servicios](Img/m-Servicios.png)

Contáctenos
![Contáctenos](Img/m-Contactanos.png)
![contactenos2](Img/m-Contactanos2.png)

## 4.4. Mobile Applications UX/UI Design

### 4.4.1. Mobile Applications Wireframes



**Autenticación**
<div align="center">
  <img src="Img/login_wm.png" width="300">
  <img src="Img/register_wm.png" width="300">
</div>

<div align="center">
  <img src="Img/perfil_wm.png" width="300">
</div>

**Menú principal**
<div align="center">
  <img src="Img/menu_wm.png" width="300">
  <img src="Img/dashboard_wm.png" width="300">
</div>

**Gestión de citas**
<div align="center">
  <img src="Img/lista_citas_wm.png" width="300">
  <img src="Img/anadir_cita_wm.png" width="300">
</div>

<div align="center">
  <img src="Img/ghorario_wm.png" width="300">
</div>

**Gestión de pacientes**
<div align="center">
  <img src="Img/lista_pacientes_wm.png" width="300">
  <img src="Img/añadir_pacientes_wm.png" width="300">
</div>

<div align="center">
  <img src="Img/historial_pacientes_wm.png" width="300">
</div>

**Inventario**
<div align="center">
  <img src="Img/lista_inventario_wm.png" width="300">
  <img src="Img/añadir_inventario_wm.png" width="300">
</div>

**Pagos**
<div align="center">
  <img src="Img/registrar_pagos_wm.png" width="300">
  <img src="Img/facturas_pagos_wm.png" width="300">
</div>

<div align="center">
  <img src="Img/lista_pagos_wm.png" width="300">
</div>





### 4.4.2. Mobile Applications Wireflow Diagrams

**Enlace Figma**:https://www.figma.com/design/WRThFO0TXiuoNfXCPJvR26/Dise%C3%B1o-web?node-id=0-1&p=f&t=gM1Z07iNNkLSpL0t-0



**User Goal: Autentificación**
![Autentificación](Img/autentificacion_wf.png)  

**User Goal: Gestión de Citas**
![Gestión de Citas](Img/gestion_citas_wf.png)  

**User Goal: Gestión de Pacientes**
![Gestión de Pacientes](Img/gestion_pacientes_wf.png) 

**User Goal: Gestión de Inventario**
![Gestión de Inventario](Img/gestion_inventario_wf.png)  

**User Goal: Perfil**
![Perfil](Img/perfil_wf.png)  

**User Goal: Gestión de pagos**
![Gestión de Pagos](Img/pagos_wf.png)  



### 4.4.3. Mobile Applications Mock-ups


**Autenticación**
<div align="center">
  <img src="Img/Login.png" width="250">
  <img src="Img/Register.png" width="250">
  <img src="Img/Perfil.png" width="250">
</div>

<div align="center">
  <img src="Img/Editar perfil.png" width="250">
  <img src="Img/Editar contraseña.png" width="250">
</div>

**Menú principal**
<div align="center">
  <img src="Img/Menu-inicio.png" width="250">
</div>

**Gestión de Citas**
<div align="center">
  <img src="Img/Gestión de Citas1.png" width="250">
  <img src="Img/Gestión de Citas2.png" width="250">
  <img src="Img/Gestión de Citas3.png" width="250">
</div>
<div align="center">
  <img src="Img/Gestión de Citas4.png" width="250">
  <img src="Img/Gestión de Citas5.png" width="250">
  <img src="Img/Gestión de Citas6.png" width="250">
</div>
<div align="center">
  <img src="Img/Gestión de Citas7.png" width="250">
  <img src="Img/Gestión de Citas8.png" width="250">
  <img src="Img/Gestión de Citas9.png" width="250">
</div>
<div align="center">
  <img src="Img/Gestión de Citas10.png" width="250">
</div>

**Gestión de Pacientes**
<div align="center">
  <img src="Img/Gestión de Pacientes1.png" width="250">
  <img src="Img/Gestión de Pacientes2.png" width="250">
  <img src="Img/Gestión de Pacientes3.png" width="250">
</div>
<div align="center">
  <img src="Img/Gestión de Pacientes4.png" width="250">
  <img src="Img/Gestión de Pacientes5.png" width="250">
  <img src="Img/Gestión de Pacientes6.png" width="250">
</div>
<div align="center">
  <img src="Img/Gestión de Pacientes7.png" width="250">
  <img src="Img/Gestión de Pacientes8.png" width="250">
  <img src="Img/Gestión de Pacientes9.png" width="250">
</div>

**Gestión de Inventario**
<div align="center">
  <img src="Img/Gestión de Inventario1.png" width="250">
  <img src="Img/Gestión de Inventario2.png" width="250">
  <img src="Img/Gestión de Inventario3.png" width="250">
</div>
<div align="center">
  <img src="Img/Gestión de Inventario4.png" width="250">
  <img src="Img/Gestión de Inventario5.png" width="250">
</div>

**Pagos**
<div align="center">
  <img src="Img/Pagos1.png" width="250">
  <img src="Img/Pagos2.png" width="250">
  <img src="Img/Pagos3.png" width="250">
</div>
<div align="center">
  <img src="Img/Pagos4.png" width="250">
  <img src="Img/Pagos5.png" width="250">
  <img src="Img/Pagos6.png" width="250">
</div>
<div align="center">
  <img src="Img/Pagos7.png" width="250">
  <img src="Img/Pagos8.png" width="250">
</div>




### 4.4.4. Mobile Applications User Flow Diagrams

**Enlace Figma:**https://www.figma.com/design/WRThFO0TXiuoNfXCPJvR26/Dise%C3%B1o-web?node-id=0-1&p=f&t=gM1Z07iNNkLSpL0t-0


**User Goal: Actualizar datos**
Cuando el usuario accede a Dentify, primero debe iniciar sesión. Una vez autenticado, puede ingresar a su perfil y modificar su información personal. Esto incluye actualizar nombre, correo electrónico o contraseña, así como añadir o editar datos adicionales como teléfono o dirección.  

![Actualizar datos](Img/Actualizar_datos.png)

---

**User Goal: Cita**
Dentro de la aplicación, el usuario tiene acceso a la sección de citas. Allí puede revisar las citas programadas, registrar nuevas o modificar las ya existentes. También cuenta con la opción de cancelar citas en caso necesario.  

![Cita](Img/Cita.png)

---

**User Goal: Inventario**
El usuario puede entrar a la sección de inventario para gestionar los productos de la clínica. Desde este apartado, es posible consultar el stock, añadir nuevos artículos, actualizarlos o eliminarlos cuando dejen de ser necesarios.  

![Inventario](Img/Inventario.png)

---

**User Goal: Paciente**
En la sección de pacientes, el usuario puede visualizar la lista de pacientes registrados, incorporar nuevos registros o editar la información de los existentes. Además, es posible eliminar aquellos pacientes que ya no deban estar en la base de datos.  

![Paciente](Img/Paciente.png)

---

**User Goal: Pagos**
La sección de pagos permite al usuario visualizar las citas pendientes de cobro, registrar abonos y emitir facturas de manera sencilla. Asimismo, se puede acceder al historial completo de pagos realizados.  

![Pagos](Img/Pagos.png)

---

**User Goal: Registro**
Si el usuario no cuenta con una cuenta, puede registrarse proporcionando información básica como nombre, correo electrónico y contraseña. Una vez completado este proceso, podrá iniciar sesión y acceder a todas las funcionalidades de Dentify.  

![Registro](Img/Registro.png)


## 4.5. Mobile Applications Prototyping

Para los prototipos de interfaz móvil seguimos tres principios: claridad, diseño mobile-first adaptable y presentación de información esencial. Priorizamos flujos cortos para registrar procesos y consultar reportes, navegación inferior y cuidamos legibilidad, manteniendo la experiencia rápida y consistente en distintos tamaños de pantalla.

### 4.5.1. Android Mobile Applications Prototyping

![Prototype_and](Img/proto_and.jpeg)


enlace video: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202220219_upc_edu_pe/EbJoZdhwlExGrvIfSN5N46EBJRw4FjQdlb-FgEm34LfOlg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=7cCrz3


### 4.5.2. iOS Mobile Applications Prototyping

![Prototype_ios](Img/proto_ios.jpeg)


enlace video: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202220219_upc_edu_pe/Ec_n0eCxhQVEkZFIHxqYhx0BZZof_YXNNdaZhlLz4DeuTQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=WrSRqG

## 4.6. Web Applications UX/UI Design

### 4.6.1. Web Applications Wireframes

**Autenticación**
<div align="center">
  <img src="Img/Registro-W.png" width="600" />
  <img src="Img/Inicio-sesión-W.png" width="600" />
</div>

**Dashboard (inicio)**
<div align="center">
  <img src="Img/Dashboard.png" width="800" />
</div>

**Inventario**
<div align="center">
  <img src="Img/Inventario-W.png" width="800" />
</div>
<div align="center">
  <img src="Img/Inventario-producto-seleccionado-W.png" width="600" />
  <img src="Img/Inventario-producto-seleccionado-2-W.png" width="600" />
</div>
<div align="center">
  <img src="Img/Inventario-producto-modificado-W.png" width="800" />
</div>
<div align="center">
  <img src="Img/inventario-producto-seleccionado-confirmado-W.png" width="800" />
</div>

**Configuración & Perfil**
<div align="center">
  <img src="Img/Perfil-W.png" width="600" />
  <img src="Img/Perfil-2-W.png" width="600" />
</div>
<div align="center">
  <img src="Img/Perfil-editar-información-personal-W.png" width="600" />
  <img src="Img/Perfil-cambiar-contraseña-W.png" width="600" />
</div>

**Pagos & Facturación**
<div align="center">
  <img src="Img/Pagos-citas-a-pagar-W.png" width="600" />
  <img src="Img/Pagos-citas-a-pagar-2-W.png" width="600" />
</div>
<div align="center">
  <img src="Img/Pagos-seleccionar-pagos-W.png" width="600" />
  <img src="Img/Pagos-filtros-para-buscar-facturas-W.png" width="600" />
</div>
<div align="center">
  <img src="Img/Pagos-pagar-cita-W.png" width="600" />
  <img src="Img/Pagos-pago-exitoso-W.png" width="600" />
</div>
<div align="center">
  <img src="Img/Pagos-vista-de-una-factura-W.png" width="800" />
</div>

**Gestión de Citas de pacientes**
<div align="center">
  <img src="Img/Reserva-de-citas-W.png" width="800" />
</div>
<div align="center">
  <img src="Img/Modificar-citas-W.png" width="600" />
  <img src="Img/Modificar-citas-2-W.png" width="600" />
</div>
<div align="center">
  <img src="Img/Eliminar-citas-W.png" width="600" />
  <img src="Img/Eliminar-citas-2-W.png" width="600" />
</div>

**Notificaciones**
<div align="center">
  <img src="Img/Notificaciones-W.png" width="800" />
</div>


### 4.6.2. Web Applications Wireflow Diagrams

**Enlace Figma:** <https://www.figma.com/design/WRThFO0TXiuoNfXCPJvR26/Dise%C3%B1o-web?node-id=0-1&p=f&t=gM1Z07iNNkLSpL0t-0>

**User Goal: Autenticación & Perfil**
<div align="center">
  <img src="Img/registro-y-autenticación.png" alt="User Flow: Registro y Autenticación" width="800" />
</div>
<div align="center">
  <img src="Img/actualizar-datos.png" alt="User Flow: Actualizar datos de perfil" width="800" />
</div>

**User Goal: Gestión de Citas (programar / modificar / cancelar)**
<div align="center">
  <img src="Img/gestion-de-citas.png" alt="User Flow: Gestión de Citas (programar, modificar, cancelar)" width="800" />
</div>

**User Goal: Gestión de Pacientes (listar / crear / editar / eliminar)**
<div align="center">
  <img src="Img/gestion-de-pacientes.png" alt="User Flow: Gestión de Pacientes (listar, crear, editar, eliminar)" width="800" />
</div>

**User Goal: Pagos & Facturación**
<div align="center">
  <img src="Img/gestion-de-pagos.png" alt="User Flow: Pagos y Facturación" width="600" />
</div>

**User Goal: Gestión de Inventario**
<div align="center">
  <img src="Img/inventario-wireflow.png" alt="User Flow: Gestión de Inventario" width="800" />
</div>

### 4.6.3. Web Applications Mock-ups

**Autenticación**
<div align="center">
  <img src="Img/Inicio-de-sesion-M.png" alt="Mockup: Inicio de sesión" width="600" />
  <img src="Img/Registro-M.png" alt="Mockup: Registro" width="600" />
</div>

**Dashboard (inicio)**
<div align="center">
  <img src="Img/Dashboard-M.png" alt="Mockup: Dashboard" width="800" />
</div>

**Perfil**
<div align="center">
  <img src="Img/Perfil-M.png" alt="Mockup: Perfil" width="600" />
  <img src="Img/Perfil-editar-información-personal-M.png" alt="Mockup: Editar información personal" width="600" />
</div>
<div align="center">
  <img src="Img/Perfil-editar-información-personal-2-M.png" alt="Mockup: Editar información personal (variante)" width="600" />
  <img src="Img/Perfil-cambiar-contraseña-M.png" alt="Mockup: Cambiar contraseña" width="600" />
</div>
<div align="center">
  <img src="Img/Perfil-cambiar-contraseña-2-M.png" alt="Mockup: Cambiar contraseña (variante)" width="800" />
</div>

**Gestión de Citas**
<div align="center">
  <img src="Img/Reserva-de-citas-M.png" alt="Mockup: Reservar cita" width="600" />
  <img src="Img/Modificar-citas-M.png" alt="Mockup: Modificar cita" width="600" />
</div>
<div align="center">
  <img src="Img/Modificar-citas-2-M.png" alt="Mockup: Modificar cita (paso 2)" width="600" />
  <img src="Img/Eliminar-citas-M.png" alt="Mockup: Eliminar cita" width="600" />
</div>
<div align="center">
  <img src="Img/Eliminar-citas-2-M.png" alt="Mockup: Eliminar cita (confirmación)" width="600" />
  <img src="Img/Historial-de-citas-M.png" alt="Mockup: Historial de citas" width="600" />
</div>

**Pagos & Facturación**
<div align="center">
  <img src="Img/Pagos-citas-a-pagar-M.png" alt="Mockup: Citas a pagar" width="600" />
  <img src="Img/Pagos-seleccionar-cita-M.png" alt="Mockup: Seleccionar cita a pagar" width="600" />
</div>
<div align="center">
  <img src="Img/Pagos-filtros-para-buscar-facturas-M.png" alt="Mockup: Filtros para buscar facturas" width="600" />
  <img src="Img/Pagos-pagar-cita-M.png" alt="Mockup: Pagar cita" width="600" />
</div>
<div align="center">
  <img src="Img/Pagos-pago-exitoso-M.png" alt="Mockup: Pago exitoso" width="600" />
  <img src="Img/Pagos-vista-de-una-factura-M.png" alt="Mockup: Vista de factura" width="600" />
</div>
<div align="center">
  <img src="Img/Pagos-facturas-M.png" alt="Mockup: Facturas" width="800" />
</div>

**Inventario**
<div align="center">
  <img src="Img/Inventario-M.png" alt="Mockup: Inventario (listado)" width="800" />
</div>
<div align="center">
  <img src="Img/Inventario-producto-seleccionado-M.png" alt="Mockup: Producto seleccionado" width="600" />
  <img src="Img/Inventario-nuevo-producto-M.png" alt="Mockup: Nuevo producto" width="600" />
</div>
<div align="center">
  <img src="Img/Inventario-modificar-producto-M.png" alt="Mockup: Modificar producto" width="600" />
  <img src="Img/Inventario-eliminar-producto-M.png" alt="Mockup: Eliminar producto" width="600" />
</div>

### 4.6.4. Web Applications User Flow Diagrams

**Enlace Figma:** <https://www.figma.com/design/WRThFO0TXiuoNfXCPJvR26/Dise%C3%B1o-web?node-id=0-1&p=f&t=gM1Z07iNNkLSpL0t-0>

**User Goal: Actualizar datos**
Cuando el usuario accede a la app, inicia sesión y va a Perfil para modificar su información personal. Puede actualizar nombre, correo y contraseña, así como agregar o editar teléfono y dirección.  
![Actualizar datos](Img/actualizar-datos-mockups.png)

---

**User Goal: Cita**
El usuario ingresa a Citas para revisar, crear o modificar citas existentes. También puede cancelar una cita si es necesario.  
![Gestión de Citas](Img/gestion-de-citas-mockups.png)

---

**User Goal: Inventario**
Desde Inventario, el usuario consulta stock, añade nuevos productos, los actualiza o elimina cuando corresponde.  
![Inventario](Img/inventario-mockup.png)

---

**User Goal: Paciente**
En **Pacientes**, el usuario visualiza la lista, registra nuevos pacientes o edita la información de los existentes; además, puede eliminarlos si ya no deben permanecer en el sistema.  
![Gestión del Paciente](Img/gestion-del-paciente.png)

---

**User Goal: Pagos**
En **Pagos**, el usuario ve citas pendientes de cobro, selecciona ítems, registra el pago y puede emitir/consultar facturas e historial.  
![Gestión de Pagos](Img/gestion-de-pagos-mockups.png)

---

**User Goal: Registro**
Si aún no tiene cuenta, el usuario se registra ingresando nombre, correo y contraseña; luego podrá iniciar sesión y acceder a todas las funciones.  
![Registro y Autenticación](Img/registro-y-autentizacion.png)


**4.7. Web Applications Prototyping**

Para los prototipos de interfaz web en escritorio seguimos tres principios: claridad, eficiencia y diseño adaptable. Utilizamos layouts de grilla y paneles que organizan funciones clave (registro de procesos y reportes), tablas filtrables y una jerarquía tipográfica limpia para comprender de inmediato. Aseguramos consistencia entre resoluciones, soporte de accesibilidad (navegación por teclado, estados de foco visibles) y mostramos solo los datos críticos para cada perfil, reduciendo ruido visual y mejorando la productividad.

![Prototipo Web](Img/proto_web.png)

## 4.8. Domain-Driven Software Architecture

### 4.8.1. Software Architecture Context Diagram

En nuestro diagrama de contexto se puede visualizar a nuestro Actor, que representa a nuestro segmento objetivo.

Dentify es una plataforma de gestión clínica odontológica que centraliza la administración de citas, pacientes, facturación, inventario e identidad de usuarios, accedida por el personal clínico desde la aplicación móvil.

<div align="center">
<img src="Img/ContextDiagram.png" alt="Context-Diagram">
</div>


### 4.8.2. Software Architecture Container Diagrams

El diagrama de contenedores de Dentify representa los principales componentes del sistema y cómo interactúan entre sí. Este nivel de abstracción permite visualizar cómo se organiza la aplicación en distintos contenedores (como aplicaciones web, móviles, backend y base de datos), mostrando tanto la tecnología empleada como las relaciones entre ellos. El objetivo es ofrecer una visión clara de la arquitectura técnica y de las responsabilidades de cada parte del sistema desde una perspectiva de alto nivel.<br><br>

<div align="center">
<img src="Img/ContainerDiagram.png" alt="Container-Diagram">
</div>

**Dentify - Containers Overview:**

| Container        | Propósito                                                             | Tecnología         | Interacciones clave                                                                                    |
| ---------------- | --------------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------ |
| **Landing Page** | Proporciona información general sobre la app móvil                    | React.js           | - Los usuarios la visitan para conocer la app <br> - Redirige a los usuarios a la aplicación móvil     |
| **Mobile App**   | Ofrece experiencia nativa para odontólogos en Android e iOS           | Kotlin & Flutter   | - Los usuarios acceden directamente o desde la landing page <br> - Se comunica con el backend por HTTP |
| **API Backend**  | Implementa lógica de negocio y servicios vía API REST                 | Java y Spring MVC  | - Recibe solicitudes de la app móvil <br> - Lee y escribe datos en la base de datos                    |
| **Database**     | Almacena datos personales, citas, pacientes, facturación e inventario | MySQL (relacional) | - Gestiona consultas y actualizaciones desde el backend                                                |

### 4.8.3. Software Architecture Components Diagrams

Los diagramas de componentes de arquitectura de software son representaciones visuales que muestran cómo se organiza un sistema de software en términos de sus componentes o módulos. Estos diagramas son esenciales para comprender la estructura interna de un sistema y cómo interactúan los diferentes componentes entre sí.

**Diagrama de componentes de la API de Dentify:**

En esta presente imagen se detalla la descripción y funcionalidad de los componentes clave dentro de la arquitectura del sistema Dentify, un software que permite a los dentistas gestionar su clínica. Los componentes son partes fundamentales de la solución, y cada uno juega un papel crucial en el sistema global.

---

<div align="center">
<img src="Img/ComponentDiagram.png" alt="Component-Diagram">
</div>

---

 1. **BillingService (Servicio de Facturación)**

- **Descripción**: Este componente maneja todo lo relacionado con la facturación dentro del sistema. Procesa las facturas generadas en función de los servicios prestados en la clínica dental.
- **Responsabilidades**:
  - Procesar las facturas generadas por los tratamientos y servicios realizados.
  - Actualizar el stock de productos en el inventario luego de que se registre una factura.
  - Escribir los datos de la factura en la base de datos.
- **Interacciones**:
  - Interactúa con el **InventoryService** para actualizar el stock después de generar una factura.
  - Comunica los datos a la **Database** para almacenamiento de la información.
  - Registra las acciones de consumo en el **LogInventoryService**.

---

 2. **InventoryService (Servicio de Inventario)**

- **Descripción**: Este componente administra el inventario de la clínica dental, controlando los productos y su disponibilidad.
- **Responsabilidades**:
  - Gestionar los artículos en el inventario de la clínica (agregar, eliminar y modificar productos).
  - Mantener el estado actualizado del stock de productos.
  - Escribir y leer información relacionada con el inventario en la base de datos.
- **Interacciones**:
  - Comunica con la **Database** para leer y escribir datos sobre el inventario.
  - Envía datos al **LogInventoryService** para registrar los cambios en el inventario debido a consumos o ventas.

---

 3. **IAMService (Servicio de Gestión de Autenticación e Identidad)**

- **Descripción**: El componente IAMService gestiona la autenticación y autorización de usuarios dentro de la plataforma.
- **Responsabilidades**:
  - Verificar la identidad del usuario y autorizar el acceso a la aplicación.
  - Gestionar la creación, actualización y validación de cuentas de usuario.
- **Interacciones**:
  - Interactúa con la **Database** para validar y verificar las credenciales del usuario.
  - Proporciona servicios de autenticación a los **iamController** para procesar solicitudes de autenticación de los usuarios.

---

 4. **ManagementService (Servicio de Gestión de Pacientes y Citas)**

- **Descripción**: Este componente gestiona los datos de las citas y pacientes dentro de la clínica dental.
- **Responsabilidades**:
  - Gestionar la creación, actualización y eliminación de citas de pacientes.
  - Gestionar la información personal de los pacientes.
  - Escribir y leer datos de citas y pacientes en la base de datos.
- **Interacciones**:
  - Se comunica con la **Database** para manejar datos relacionados con citas y pacientes.

---

 5. **LogInventoryService (Servicio de Registro de Inventario)**

- **Descripción**: Este componente registra las acciones que afectan el inventario, tales como la venta de productos o el consumo dentro de la clínica.
- **Responsabilidades**:
  - Registrar cada cambio de inventario en el sistema.
  - Proporcionar un historial completo de los movimientos de inventario, para auditar y analizar las tendencias.
  - Escribir los registros en la base de datos.
- **Interacciones**:
  - Se comunica con el **InventoryController** para proporcionar datos relacionados con los cambios en el inventario.
  - Envía datos a la **Database** para registrar la información de los movimientos de inventario.

---

 6. **InventoryController (Controlador de Inventario)**

- **Descripción**: Este componente expone los puntos finales (endpoints) de la API REST relacionados con el inventario.
- **Responsabilidades**:
  - Proporcionar acceso a los datos del inventario a través de la API.
  - Exponer servicios para consultar y actualizar el inventario.
- **Interacciones**:
  - Se comunica con el **InventoryService** para obtener datos del inventario.
  - Usa el **LogInventoryService** para registrar los movimientos del inventario.

---

 7. **ManagementController (Controlador de Gestión de Pacientes y Citas)**

- **Descripción**: Este componente expone los puntos finales (endpoints) de la API REST relacionados con la gestión de citas y pacientes.
- **Responsabilidades**:
  - Proporcionar acceso a los datos de citas y pacientes a través de la API.
  - Permitir la creación, actualización y consulta de citas y pacientes.
- **Interacciones**:
  - Se comunica con el **ManagementService** para gestionar las operaciones sobre pacientes y citas.

---

 8. **IAMController (Controlador de Gestión de Autenticación)**

- **Descripción**: Este componente expone los puntos finales (endpoints) de la API REST responsables de la autenticación y registro de usuarios.
- **Responsabilidades**:
  - Gestionar las solicitudes de autenticación y registro de nuevos usuarios.
  - Verificar las credenciales de usuario y permitir el acceso a la aplicación.
- **Interacciones**:
  - Se comunica con el **IAMService** para procesar las solicitudes de autenticación.
  - Interactúa con la **Database** para validar las credenciales de los usuarios.

---

 9. **BillingController (Controlador de Facturación)**

- **Descripción**: Este componente expone los puntos finales (endpoints) de la API REST relacionados con la facturación.
- **Responsabilidades**:
  - Proveer los servicios para la creación y consulta de facturas.
  - Gestionar la interacción entre el frontend y el servicio de facturación.
- **Interacciones**:
  - Se comunica con el **BillingService** para procesar las solicitudes de facturación.
    <br>

## 4.9. Software Object-Oriented Design

### 4.9.1. Class Diagrams

<div align="center">
<img src="Img/diagrama-clase.png" alt="Diagrama de clase">
</div>

### 4.9.2. Class Dictionary

| Clase                  | Descripción                                   | Atributos principales |
|-------------------------|-----------------------------------------------|-----------------------|
| **BillingController**   | Expone endpoints de facturación.              | Métodos: `createInvoice()`, `getInvoice()` |
| **InventoryController** | Maneja endpoints de inventario.               | Métodos: `getInventory()`, `updateInventory()` |
| **ManagementController**| Endpoints para pacientes y citas.             | Métodos: `createAppointment()`, `managePatients()` |
| **IAMController**       | Controlador para autenticación.               | Métodos: `login()`, `register()` |
| **BillingService**      | Lógica de facturación.                        | Métodos: `processInvoice()`, `updateStock()` |
| **InventoryService**    | Lógica de inventario.                         | Métodos: `manageProducts()`, `updateStock()` |
| **ManagementService**   | Manejo de pacientes y citas.                  | Métodos: `manageAppointments()`, `managePatients()` |
| **IAMService**          | Autenticación y usuarios.                     | Métodos: `authenticateUser()`, `manageAccounts()` |
| **LogInventoryService** | Registro de movimientos de inventario.        | Métodos: `registerChange()`, `getLog()` |
| **Invoice**             | Representa una factura.                       | `id`, `date`, `total` |
| **Patient**             | Representa un paciente.                       | `id`, `name`, `email`, `phone` |
| **Appointment**         | Representa una cita.                          | `id`, `date`, `status` |
| **Product**             | Producto de inventario.                       | `id`, `name`, `stock`, `price` |
| **User**                | Usuario autenticado.                          | `id`, `name`, `email`, `password` |
| **LogInventory**        | Registro de inventario.                       | `id`, `action`, `date` |


## 4.10. Database Design
### 4.10.1. Relational/Non-Relational Database Diagram

<div align="center">
<img src="Img/digrama-relacional.png" alt="Diagrama de clase">
</div>

# Capítulo V: Product Implementation

## 5.1. Software Configuration Management

Con el fin de garantizar la consistencia, trazabilidad y calidad a lo largo del ciclo de vida de Dentify, en todos sus productos software, el equipo ha definido un conjunto de decisiones y convenciones orientadas a la gestión de configuraciones. Esta sección describe los mecanismos adoptados para controlar el código fuente, configurar los entornos de desarrollo y definir el proceso de despliegue de la aplicación web.

Estas prácticas permiten asegurar que las versiones del software se mantengan estables, que el trabajo colaborativo sea eficiente y que las implementaciones sean controladas y reproducibles.

### 5.1.1. Software Development Environment Configuration

Para asegurar una colaboración eficiente y mantener la calidad en el desarrollo de Eventify, se ha definido un entorno de desarrollo común para todos los miembros del equipo. A continuación, se listan los productos de software utilizados en las distintas etapas del ciclo de vida del producto digital, indicando su propósito y su enlace de referencia o descarga correspondiente.

**Requirements Management:**

**UxPressia:** Utilizamos esta herramienta para elaborar los distintos artefactos de Needfinding como son el User persona, Journey Map, Empathy Map e Impact Maps. 

Referencia: [https://uxpressia.com](https://uxpressia.com)

<img src="Img/uxpressia-icon.png" alt="UxPressia" height="150"/>

**Miro:** Esta plataforma en línea nos ayudó a desarrollar los cuadros de As-Is y To-Be Scenary Map 

Referencia: [https://miro.com/es/](https://miro.com/es/)

<img src="Img/miro-icon.png" alt="Miro" height="150"/>


**Product UX/UI Design**

**Figma:** Se empleó para la creación de wireframes, mock-ups y prototipos de la aplicación web.

Referencia: [https://www.figma.com/es-es/](https://www.figma.com/es-es/)

<img src="Img/figma-icon.png" alt="Figma" height="150"/>

**Software Development**

**WebStorm:** (Instalación local): Utilizado como entorno de desarrollo para trabajar con HTML, CSS y JavaScript. 

Referencia: [https://www.jetbrains.com/es-es/webstorm/](https://www.jetbrains.com/es-es/webstorm/)

<img src="Img/webstorm-icon.png" alt="WebStorm" height="150"/>

**IntelliJ:** Este es un IDE de Jetbrains para desarrollar aplicaciones con Java. Para este proyecto lo utilizamos para desarrollar el backend de la aplicación

Referencia: [https://www.jetbrains.com/idea](https://www.jetbrains.com/idea)

<img src="Img/intellij-icon.png" alt="IntelliJ" height="150"/>

**Android Studio:** Es un IDE oficial para el desarrollo de aplicaciones Android. Dicho software es gratuito y está basado en IntelliJ IDEA. Esta herramienta nos permite desarrollar la aplicación móvil planteada.

Referencia: [https://developer.android.com](https://developer.android.com)

<img src="Img/android-studio-icon.png" alt="Android Studio" height="150"/>

**Visual Studio Code:** Este es un editor de código usado para desarrollo de software, ya sea con HTML, CSS y Javascript, asi como con frameworks (Vue, Angular, React, etc.)

Referencia: [https://code.visualstudio.com](https://code.visualstudio.com)

<img src="Img/visual-studio-icon.png" alt="Visual Studio Code" height="150"/>

**Project Management and Collaboration**

En la gestión de proyectos y colaboración del equipo se utilizaron:

**Jira:** Esta es una plataforma especializada en la gestión de proyecto, la cual utilizamos para asignar tareas a realizar por cada integrante del equipo. 

Referencia: [https://www.atlassian.com/es/software/jira](https://www.atlassian.com/es/software/jira)

<img src="Img/jira-icon.png" alt="Jira" height="150"/>

**GitHub:** Plataforma de repositorio remoto para la gestión de versiones del código, implementando el flujo GitFlow para garantizar un desarrollo organizado.

Referencia: [https://github.com/](https://github.com/)

<img src="Img/github-icon.png" alt="GitHub" height="150"/>

**Git (Instalación local):** Empleado para gestionar los cambios de código de manera local mediante commits y ramas.

Referencia: [https://git-scm.com/](https://git-scm.com/)

<img src="Img/git-icon.png" alt="Git" height="150"/>



**Software Documentation**

**GitHub:** Esta plataforma tambien fue utilizada para el desarrollo del informe mediante archivos MarkDown(.md) 

Referencia: [https://github.com/](https://github.com/)

<img src="Img/github-icon.png" alt="GitHub" height="150"/>

**Vertabelo:** Herramienta utilizada para el diseño, creación y documentación colaborativa de bases de datos. 

Referencia: [https://vertabelo.com/](https://vertabelo.com/)

<img src="Img/vertabelo-icon.png" alt="Vertabelo" height="150"/>

**Structurizr:** Herramienta usada para modelar la arquitectura de software mediante diagramas C4.

Referencia: [https://structurizr.com/](https://structurizr.com/)

<img src="Img/structurizr-icon.png" alt="Structurizr" height="150"/>

**Software Deployment**

**Firebase:** Esta es una plataforma de Google para desarrollo de aplicaciones. Para este caso lo utilizamos para desplegar la aplicación móvil

Referencia: [https://firebase.google.com/?hl=es-419](https://firebase.google.com/?hl=es-419)

<img src="Img/firebase-icon.png" alt="Firebase" height="150"/>

**Azure:** Este es un servicio en la nube de Microsoft, el cual usamos para desplegar el backend junto con la documentación en Swagger 

Referencia: [https://azure.microsoft.com/es-es](https://azure.microsoft.com/es-es)

<img src="Img/azure-icon.png" alt="Azure" height="150"/>

**GithubPages:** Esta es una herramienta de GitHub para alojar sitios web estáticos. Lo utilizamos para desplegar el landing page. 

Referencia: [https://docs.github.com/es/pages](https://docs.github.com/es/pages)

<img src="Img/github-pages-icon.png" alt="GitHub Pages" height="150"/>

### 5.1.2. Source Code Management

La gestión del código fuente es una parte fundamental en el desarrollo colaborativo de software, ya que permite un control eficiente sobre las modificaciones realizadas en el proyecto a lo largo de su ciclo de vida. En esta sección, se describe el sistema de control de versiones implementado en el proyecto Dentify, utilizando GitHub como plataforma principal. Además, se detallan las convenciones de trabajo adoptadas por el equipo, como el modelo GitFlow, el versionado semántico (Semantic Versioning) y las convenciones de commit mediante Conventional Commits. Estas prácticas aseguran un desarrollo ordenado y una integración continua efectiva entre los miembros del equipo.

**URL de los Repositorios:**
- Organización: [https://github.com/ClinicCode](https://github.com/ClinicCode)
- Reporte: [https://github.com/ClinicCode/Informe](https://github.com/ClinicCode/Informe)
- Landing Page: [https://github.com/ClinicCode/dentify-landing-page](https://github.com/ClinicCode/dentify-landing-page)
- FrontEnd: [https://github.com/ClinicCode/dentify-app-web](https://github.com/ClinicCode/dentify-app-web)
- Backend: [https://github.com/ClinicCode/dentify-backend](https://github.com/ClinicCode/dentify-backend)
- Mobile App: [https://github.com/ClinicCode/dentify-app-mobile](https://github.com/ClinicCode/dentify-app-mobile)

**Estructura de Ramas:**

Para mantener un flujo organizado en el desarrollo y facilitar la colaboración, se ha implementado el modelo GitFlow, creando las siguientes ramas:

- Master Branch: Rama principal (main) que contiene las versiones estables del proyecto. Todas las demás ramas derivan de esta.
- Develop: Rama secundaria donde se integran todas las características nuevas antes de fusionarse a la rama main.
- Feature Branches: Se crean a partir de develop para trabajar en nuevas funcionalidades específicas
- Release Branches: Se crean desde develop para preparar una nueva versión.
- Hotfix Branches: Se crean desde main para solucionar errores críticos detectados en producción.

**Convenciones de commits:**

Para la escritura de commits, se sigue la convención 'Conventional Commits', el cual cuenta con un formato estándar para facilitar la lectura y entendimiento del historial de cambios dentro del proyecto.
```
    <type>[optional scope]: <description>
    
    [optional body]
    
    [optional footer(s)]
```
- Type:
  - feat: Añadir una nueva característica.
  - fix: Correción de errores.
  - docs: Modificaciones en la documentación.
  - style: Cambios que no afectan la lógica del código.
  - refactor: Modificaciones que no añaden características y/o errores.
  - test: Adición/Modificación de pruebas.


- Scope: Brinda información extra acerca del área del código afectado.
```
   feat(auth): add register functionality.
```
**Ejemplos básicos de commits:**
```
   feat(login): add organizer authentication module.
```
```
   fix(payment): resolve payment security issue.
```
```
   docs(README): update index instructions.
```

### 5.1.3. Source Code Style Guide & Conventions

Para el desarrollo de Dentify se emplearon distintos lenguajes y frameworks, aplicando convenciones de codificación y buenas prácticas en cada caso:

**HTML**

En la implementación de HTML se siguieron las Convenciones de Codificación correspondientes. Los aspectos más relevantes fueron:

Uso de etiquetas semánticas: Se incorporaron elementos como header, nav, main y footer para mejorar tanto la accesibilidad como la interpretación del documento.

Indentación y consistencia: Aunque HTML admite mayúsculas y minúsculas en elementos y atributos, se optó exclusivamente por el uso de minúsculas con la convención kebab-case, priorizando la legibilidad y el orden.

**CSS**

El código CSS se desarrolló bajo la convención BEM y lineamientos de estilo para mantener claridad y organización. Algunos puntos destacados:

* Clases descriptivas y en inglés, siempre en formato kebab-case, lo que facilita su comprensión.

* Transiciones en botones, añadiendo efectos suaves que enriquecen la experiencia del usuario.

* Fuentes personalizadas, integradas mediante @font-face siguiendo las recomendaciones para la gestión tipográfica en CSS.

**JavaScript**

Para la interactividad y los componentes dinámicos de la interfaz se utilizó Bootstrap, incluyendo únicamente sus archivos oficiales. Esto permitió aprovechar sus funcionalidades avanzadas sin necesidad de programar desde cero.

**Bootstrap**

En el uso de Bootstrap se respetaron las buenas prácticas, empleando clases predefinidas para garantizar un diseño responsive. Además, se realizaron personalizaciones sin modificar directamente el código base, asegurando compatibilidad y facilidad de actualización.

**Java (Spring Boot)**

En la construcción de la API Restful se siguió la convención Google Java Style Guide.

**Nomenclatura:** Se aplicó PascalCase en clases y métodos, y lowerCamelCase en atributos.

**Estructura del proyecto:** Se adoptaron los principios de Clean Architecture y Domain Driven Design, organizando el sistema por Bounded Contexts y capas (Aplicación, Infraestructura, Dominio e Interfaces).

**Kotlin (Android Studio)**

Para la aplicación móvil se empleó la guía de estilo oficial de Kotlin (Google Kotlin Style Guide).

**Nomenclatura:** Clases y métodos en PascalCase, atributos en lowerCamelCase.

**Arquitectura:** Se aplicaron Clean Architecture y Domain Driven Design, estructurando el proyecto en Repositorios, UI, Casos de Uso y Dominios.

### 5.1.4. Software Deployment Configuration

**Landing Page**

El despliegue del landing page se realizó en GitHub Pages, siguiendo los siguientes pasos:

1. **Dirigirse a Settings:** Una vez todos los cambios realizados esten en la rama **main**, debemos dirigirnos a la sección **Settings**

![deploy-landing-page-step-1.png](Img/deploy-landing-page-step-1.png)

2. **Dirigirse a la opción Pages:** Dentro de **Settings** buscamos la opción **Pages**

![deploy-landing-page-step-2.png](Img/deploy-landing-page-step-2.png)

3. **Seleccinar la rama y carpeta para el despliegue:** Por último, seleccionar la rama main y la carpeta por defecto **(root)** para realizar el despliegue. 

![deploy-landing-page-step-3.png](Img/deploy-landing-page-step-3.png)

## 5.2. Product Implementation & Deployment

### 5.2.1. Sprint Backlogs

El objetivo principal de este Sprint es desarrollar la primera versión funcional de Dentify, priorizando la implementación del Landing Page, la estructura inicial del Frontend Web y Mobile Apps, y la integración básica del Backend. Este Sprint busca validar las funcionalidades esenciales, garantizar la consistencia del diseño UX/UI y establecer la base para iteraciones futuras.


| ID   | Tipo       | User Story / Task                               | Description                                         | Estimación (Horas) | Assigned To                           | Status |
| ---- | ---------- | ----------------------------------------------- | --------------------------------------------------- | ------------------ | ------------------------------------- | ------ |
| SS01 | Spike      | Investigar uso de Mockito                       | Integrar Mockito para pruebas unitarias             | 8                  | Aponte Cruzado, Andrea Marielena      | Done  |
| SS02 | Spike      | Investigar uso de Selenium                      | Pruebas automatizadas con Selenium                  | 8                  | Belahonia Miranda, Fabrisio           | Done |
| US05 | User Story | Añadir Citas                                    | Registrar nuevas citas en el sistema                | 8                  | Bohorquez Lerzundi, Gerardo Sebastian | Done |
| US04 | User Story | Editar Citas                                    | Modificar información de una cita existente         | 8                  | Cutiri Agüero, Fabrizio Alexander     | Done  |
| US06 | User Story | Eliminar Cita                                   | Eliminar citas del sistema                          | 8                  | Berrocal Ramirez, Omar Christian      | Done  |
| US11 | User Story | Mostrar Pacientes                               | Visualizar lista de pacientes                       | 8                  | Aponte Cruzado, Andrea Marielena      | Done  |
| US12 | User Story | Añadir Pacientes                                | Registrar nuevos pacientes                          | 8                  | Belahonia Miranda, Fabrisio           | Done |
| US13 | User Story | Editar Pacientes                                | Modificar datos de pacientes                        | 8                  | Bohorquez Lerzundi, Gerardo Sebastian | Done  |
| US16 | User Story | Añadir Historial Clínico                        | Registrar historial clínico de pacientes            | 8                  | Cutiri Agüero, Fabrizio Alexander     | Done  |
| US19 | User Story | Visualizar Inventario                           | Ver inventario general                              | 8                  | Berrocal Ramirez, Omar Christian      |    Done  |
| US20 | User Story | Añadir objeto al inventario                     | Registrar nuevos objetos en inventario              | 8                  | Aponte Cruzado, Andrea Marielena      | Done   |
| US21 | User Story | Editar objeto del inventario                    | Modificar datos de objetos en inventario            | 8                  | Belahonia Miranda, Fabrisio           | Done   |
| US22 | User Story | Eliminar objeto del inventario                  | Eliminar objetos del inventario                     | 8                  | Bohorquez Lerzundi, Gerardo Sebastian | Done   |
| US25 | User Story | Registrar cantidad consumida de ítems           | Registrar insumos usados por tratamiento            | 8                  | Cutiri Agüero, Fabrizio Alexander     | Done   |
| TS01 | Technical  | Endpoint crear ítem inventario                  | POST /api/v1/items                                  | 8                  | Berrocal Ramirez, Omar Christian      | Done   |
| TS02 | Technical  | Endpoint actualizar ítem inventario             | PUT /api/v1/items/{id}                              | 8                  | Aponte Cruzado, Andrea Marielena      | Done   |
| TS03 | Technical  | Endpoint eliminar ítem inventario               | DELETE /api/v1/items/{id}                           | 8                  | Belahonia Miranda, Fabrisio           | Done   |
| TS04 | Technical  | Endpoint obtener ítem por ID                    | GET /api/v1/items/{id}                              | 8                  | Bohorquez Lerzundi, Gerardo Sebastian | Done   |
| TS05 | Technical  | Endpoint obtener todos ítems de usuario         | GET /api/v1/items                                   | 8                  | Cutiri Agüero, Fabrizio Alexander     | Done   |
| TS06 | Technical  | Endpoint crear paciente                         | POST /api/v1/patients                               | 8                  | Berrocal Ramirez, Omar Christian      | Done   |
| TS07 | Technical  | Endpoint actualizar paciente                    | PUT /api/v1/patients/{id}                           | 8                  | Aponte Cruzado, Andrea Marielena      | Done   |
| TS08 | Technical  | Endpoint eliminar paciente                      | DELETE /api/v1/patients/{id}                        | 8                  | Belahonia Miranda, Fabrisio           | Done   |
| TS11 | Technical  | Endpoint añadir historial clínico               | POST /api/v1/patients/{patientId}/medical-histories | 8                  | Bohorquez Lerzundi, Gerardo Sebastian | To-do  |
| TS12 | Technical  | Endpoint obtener historial clínico por paciente | GET /api/v1/patients/{patientId}/medical-histories  | 8                  | Cutiri Agüero, Fabrizio Alexander     | Done   |
| TS13 | Technical  | Endpoint crear cita                             | POST /api/v1/appointments                           | 8                  | Berrocal Ramirez, Omar Christian      | Done   |
| TS14 | Technical  | Endpoint actualizar cita                        | PUT /api/v1/appointments/{appointmentId}            | 8                  | Aponte Cruzado, Andrea Marielena      | Done   |
| TS15 | Technical  | Endpoint eliminar cita                          | DELETE /api/v1/appointments/{appointmentId}         | 8                  | Belahonia Miranda, Fabrisio           | Done   |
| TS18 | Technical  | Endpoint obtener cita por ID                    | GET /api/v1/appointments/appointment/{id}           | 8                  | Bohorquez Lerzundi, Gerardo Sebastian | Done   |
| US03 | User Story | Mostrar Citas                                   | Visualizar todas las citas registradas              | 5                  | Cutiri Agüero, Fabrizio Alexander     | Done   |
| US07 | User Story | Buscar Citas                                    | Buscar citas por fecha o DNI                        | 5                  | Berrocal Ramirez, Omar Christian      | Done   |
| US08 | User Story | Gestionar horarios de atención                  | Ver y editar horarios de atención                   | 5                  | Aponte Cruzado, Andrea Marielena      | Done   |
| US09 | User Story | Pagar tratamiento                               | Procesar pagos de tratamientos                      | 5                  | Belahonia Miranda, Fabrisio           | Done   |
| US10 | User Story | Historial de pagos                              | Visualizar historial de pagos                       | 5                  | Bohorquez Lerzundi, Gerardo Sebastian | To-do  |
| US14 | User Story | Eliminar Pacientes                              | Eliminar pacientes inactivos                        | 5                  | Cutiri Agüero, Fabrizio Alexander     | Done   |
| US15 | User Story | Buscar Pacientes                                | Buscar pacientes por DNI                            | 5                  | Berrocal Ramirez, Omar Christian      | Done   |
| US17 | User Story | Eliminar historial clínico                      | Eliminar historial clínico de paciente              | 5                  | Aponte Cruzado, Andrea Marielena      | Done   |
| US18 | User Story | Mostrar historial clínico                       | Visualizar historial clínico                        | 5                  | Belahonia Miranda, Fabrisio           | Done   |
| US23 | User Story | Dashboard de inventario                         | Visualizar métricas de inventario                   | 5                  | Bohorquez Lerzundi, Gerardo Sebastian | Done   |
| US24 | User Story | Guardar fecha de ajuste de inventario           | Registrar fecha de movimientos en inventario        | 5                  | Cutiri Agüero, Fabrizio Alexander     | Done   |
| TS09 | Technical  | Endpoint obtener paciente por ID                | GET /api/v1/patients/{id}                           | 5                  | Berrocal Ramirez, Omar Christian      | Done   |
| TS10 | Technical  | Endpoint obtener todos pacientes de usuario     | GET /api/v1/patients                                | 5                  | Aponte Cruzado, Andrea Marielena      | Done   |
| TS16 | Technical  | Endpoint obtener todas citas de usuario         | GET /api/v1/appointments                            | 5                  | Belahonia Miranda, Fabrisio           | Done   |
| TS17 | Technical  | Endpoint obtener todas citas de paciente        | GET /api/v1/appointments/{patientId}                | 5                  | Bohorquez Lerzundi, Gerardo Sebastian | Done   |
| TS19 | Technical  | Endpoint crear factura                          | POST /api/v1/invoices                               | 5                  | Cutiri Agüero, Fabrizio Alexander     | Done   |
| TS20 | Technical  | Endpoint obtener todas facturas de usuario      | GET /api/v1/invoices                                | 5                  | Berrocal Ramirez, Omar Christian      | Done   |
| TS21 | Technical  | Endpoint obtener factura por ID de cita         | GET /api/v1/invoices/{appointmentId}                | 5                  | Aponte Cruzado, Andrea Marielena      | Done   |
| US26 | User Story | Gestión del Perfil                              | Visualizar y editar perfil                          | 3                  | Belahonia Miranda, Fabrisio           | Done   |
| US27 | User Story | Visualización del menú principal                | Ver menú del landing page                           | 3                  | Bohorquez Lerzundi, Gerardo Sebastian | Done   |
| US28 | User Story | Navegación por la barra principal               | Navegar entre secciones                             | 3                  | Cutiri Agüero, Fabrizio Alexander     | Done   |
| US29 | User Story | Sección About Us                                | Ver información sobre la empresa                    | 3                  | Berrocal Ramirez, Omar Christian      | Done   |
| US30 | User Story | Sección de Servicios                            | Visualizar servicios ofrecidos                      | 3                  | Aponte Cruzado, Andrea Marielena      | Done   |
| US31 | User Story | Sección Contact Us                              | Visualizar datos de contacto                        | 3                  | Belahonia Miranda, Fabrisio           | Done   |
| US32 | User Story | Formulario de contacto                          | Enviar formulario de contacto                       | 3                  | Bohorquez Lerzundi, Gerardo Sebastian | Done   |
| US33 | User Story | Footer informativo                              | Ver información legal/complementaria                | 3                  | Cutiri Agüero, Fabrizio Alexander     | Done   |
| US01 | User Story | Registrar Usuarios                              | Registro de usuarios en la app                      | 3                  | Berrocal Ramirez, Omar Christian      | Done   |
| US02 | User Story | Iniciar Sesión                                  | Login de usuarios                                   | 3                  | Aponte Cruzado, Andrea Marielena      | Done   |
| TS22 | Technical  | Endpoint registrar usuario                      | POST /api/auth/register                             | 3                  | Belahonia Miranda, Fabrisio           | Done   |
| TS23 | Technical  | Endpoint iniciar sesión                         | POST /api/auth/login                                | 3                  | Bohorquez Lerzundi, Gerardo Sebastian |  Done  |


### 5.2.2. Implemented Landing Page Evidence

En esta sección mostraremos evidencias del landing page desplegado.

**Link de Landing Page:** https://cliniccode.github.io/dentify-landing-page

![landing-page-evidence-1.png](Img/landing-page-evidence-1.png)

![landing-page-evidence-2.png](Img/landing-page-evidence-2.png)

![landing-page-evidence-3.png](Img/landing-page-evidence-3.png)

![landing-page-evidence-4.png](Img/landing-page-evidence-4.png)

### 5.2.3. Implemented Frontend-Web Application Evidence

En esta sección mostraremos evidencias del Frontend desplegado.


**Link del Frontend:** https://dentify-frontend.web.app/login

![des_front.png](Img/des_front.png)  



### 5.2.4. Implemented Native-Mobile Application Evidence

En esta sección mostraremos evidencias del Mobile Application desplegado.

**Evidencias:**  
![mov_des.png](Img/mov_des.png)  
![Mobile_evidence.jpg](Img/Mobile_evidence.jpg) 

### 5.2.5. Implemented RESTful API and/or Serverless Backend Evidence

En esta sección mostraremos evidencias del Mobile Application desplegado.

**Link del Backend:** https://dentify-f0gdbubtaafmdfg9.canadacentral-01.azurewebsites.net/swagger-ui/index.html

**Evidencias:**  
![REST_BACK.png](Img/REST_BACK.png)  
![REST_BACK2.png](Img/REST_BACK2.png)  
![REST_BACK3.png](Img/REST_BACK3.png)  
![REST_BACK4.png](Img/REST_BACK4.png)  
![REST_BACK5.png](Img/REST_BACK5.png) 


### 5.2.6. RESTful API documentation

En esta sección se incluyen capturas de la **documentación de la API RESTful**.  

**Evidencias:**  
![doc1.png](Img/doc1.png)  
![doc2.png](Img/doc2.png) 


### 5.2.7. Team Collaboration Insights


| Alumno                              | Actividad                                                                                       |
|-------------------------------------|-------------------------------------------------------------------------------------------------|
| Aponte Cruzado, Andrea Marielena    | Capítulo I: Startup Profile (1.1, 1.2 y 1.3).                                                   |
| Belahonia Miranda, Fabrisio         | Capítulo II: Requirements Elicitation & Analysis (2.1 – 2.4).                                   |
| Bohorquez Lerzundi, Gerardo Sebastian | Capítulo IV: Product Design (Documentación y elaboración de Landing Page y Mobile Applications UX/UI Design). |
| Cutiri Agüero, Fabrizio Alexander   | Capítulo V: Product Implementation & Deployment (5.1 – 5.2).                                    |
| Berrocal Ramirez, Omar Christian    | Capítulo IV: Domain-Driven Software Architecture y Database Design (4.8 – 4.10).                |

# Conclusiones

En conclusión, este proyecto resalta la importancia de aplicar diferentes enfoques de arquitectura y el uso de Domain-Driven Design (DDD), lo cual contribuyó a una mejor organización, escalabilidad y mantenibilidad del sistema. La implementación de una aplicación móvil desarrollada en Flutter para Android e iOS, junto con una versión nativa para Android, y respaldada por un backend sólido en Spring Boot con Java 17, permitió consolidar una base tecnológica moderna y eficiente. Asimismo, el énfasis en el diseño UX/UI garantizó una experiencia de usuario clara, atractiva e intuitiva. Finalmente, la utilización de control de versiones con Git y la estrategia de ramificación GitFlow favorecieron una gestión colaborativa y ordenada del desarrollo, manteniendo la trazabilidad y calidad del código durante todo el proceso.

# Bibliografía

Osiptel. (2022). Los servicios de telecomunicaciones en los hogares peruanos: Encuesta Residencial de Servicios de Telecomunicaciones – ERESTEL 2021. https://www.osiptel.gob.pe/media/dujjruwd/erestel-2021.pdf

# Anexos

## Recursos del Proyecto

| Descripción                          | Enlace                                                                 |
|--------------------------------------|------------------------------------------------------------------------|
| Repositorio de Aplicación Móvil      | [GitHub - MobileApp](https://github.com/ClinicCode/dentify-app-mobile) |
| Repositorio de Landing Page          | [GitHub - LandingPage](https://github.com/ClinicCode/dentify-landing-page) |
| Despliegue de Landing Page           | [Landing Page Deploy](s) |
| Repositorio de Web Service           | [GitHub - BackEnd](https://github.com/ClinicCode/dentify-backend) |
| Despliegue de Web Service            | [Swagger UI](https://dentify-f0gdbubtaafmdfg9.canadacentral-01.azurewebsites.net/swagger-ui/index.html)|
| Organización de GitHub               | [TF-AplicacionesMoviles](https://github.com/ClinicCode) |


---

## Evidencias en Video

| Sección                    | Características del video                                                                                                                                          | Enlace                     |
|----------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------|
| *Needfinding Interviews* | *Cantidad de videos:* 1 <br> *Nomenclatura:* upc-pre-202520-1asi0732-14651-ClinicCode-needfinding-sprint-1 <br> *Formato:* mp4 <br> *Duración:* 34:28 | [Ver Video](https://shorturl.at/P0n32) |

