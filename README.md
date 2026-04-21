<br><br>

<div align="center" style="font-size: 23px";>

  <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" width="30%" alt="UPC Logo">

<b>Universidad Peruana de Ciencias Aplicadas</b><br><br>
Ingeniería de Software<br><br>
8vo Ciclo<br>

<b>Arquitecturas de Software Emergentes</b><br><br>
Sección: 11806<br>

Profesor: Christian Luis De Los Rios Fernandez<br>

<b>"INFORME DEL TRABAJO FINAL – TB1"</b>

Startup: <b>Oxaira</b><br><br>
Producto: <b>AirQ</b><br>

<b>Integrantes:</b>

<table style="margin-left:auto; margin-right:auto; border-collapse:collapse;">
<tr>
<th style="border:1px solid black; padding:8px;">Apellidos y Nombres</th>
<th style="border:1px solid black; padding:8px;">Código</th>
</tr>

<tr>
<td style="border:1px solid black; padding:8px;">Eduardo Eusebio Sihuar Ccotarma Ttito</td>
<td style="border:1px solid black; padding:8px;">UXXXXXXXX</td>
</tr>

<tr>
<td style="border:1px solid black; padding:8px;">Daniel Jhared Chávarri Zarzosa</td>
<td style="border:1px solid black; padding:8px;">U202211108</td>
</tr>

<tr>
<td style="border:1px solid black; padding:8px;">Marco Antonio Gongora Sanchez</td>
<td style="border:1px solid black; padding:8px;">U20211A085</td>
</tr>

<tr>
<td style="border:1px solid black; padding:8px;">Andres Fernando Rodriguez Zuluoeta</td>
<td style="border:1px solid black; padding:8px;">U20212421</td>
</tr>

<tr>
<td style="border:1px solid black; padding:8px;">Erick Armando Cueva Elera</td>
<td style="border:1px solid black; padding:8px;">UXXXXXXXX</td>
</tr>

</table>

<br><br>

Abril, 2026

</div>

# Contenido

## Tabla de Contenidos

### [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
### [Project Report Collaboration Insights](#project-report-collaboration-insights)
### [Contenido](#contenido)
### [Student Outcome](#student-outcome)

---

## [Capítulo I: Introducción](#capítulo-i-introducción)

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

---

## [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)

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
  - [2.3.3. Empathy Mapping](#233-empathy-mapping)
  - [2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)

- [2.4. Ubiquitous Language](#24-ubiquitous-language)

---

## [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)

- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

---

## [Capítulo IV: Strategic-Level Software Design](#capítulo-iv-strategic-level-software-design)

### [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
- [4.1.1. Design Purpose](#411-design-purpose)
- [4.1.2. Attribute-Driven Design Inputs](#412-attribute-driven-design-inputs)
  - [4.1.2.1. Primary Functionality](#4121-primary-functionality)
  - [4.1.2.2. Quality Attribute Scenarios](#4122-quality-attribute-scenarios)
  - [4.1.2.3. Constraints](#4123-constraints)
- [4.1.3. Architectural Drivers Backlog](#413-architectural-drivers-backlog)
- [4.1.4. Architectural Design Decisions](#414-architectural-design-decisions)
- [4.1.5. Quality Attribute Scenario Refinements](#415-quality-attribute-scenario-refinements)

### [4.2. Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)
- [4.2.1. EventStorming](#421-eventstorming)
- [4.2.2. Candidate Context Discovery](#422-candidate-context-discovery)
- [4.2.3. Domain Message Flows Modeling](#423-domain-message-flows-modeling)
- [4.2.4. Bounded Context Canvases](#424-bounded-context-canvases)
- [4.2.5. Context Mapping](#425-context-mapping)

### [4.3. Software Architecture](#43-software-architecture)
- [4.3.1. System Landscape Diagram](#431-system-landscape-diagram)
- [4.3.2. Context Level Diagrams](#432-context-level-diagrams)
- [4.3.3. Container Level Diagrams](#433-container-level-diagrams)
- [4.3.4. Deployment Diagrams](#434-deployment-diagrams)

---

## [Capítulo V: Tactical-Level Software Design](#capítulo-v-tactical-level-software-design)

- [5.X. Bounded Context](#5x-bounded-context)
  - [Domain Layer](#domain-layer)
  - [Interface Layer](#interface-layer)
  - [Application Layer](#application-layer)
  - [Infrastructure Layer](#infrastructure-layer)
  - [Component Diagrams](#component-diagrams)
  - [Code Level Diagrams](#code-level-diagrams)

---

## [Capítulo VI: Solution UX Design](#capítulo-vi-solution-ux-design)

- [6.1. Style Guidelines](#61-style-guidelines)
- [6.2. Information Architecture](#62-information-architecture)
- [6.3. Landing Page UI Design](#63-landing-page-ui-design)
- [6.4. Applications UX/UI Design](#64-applications-uxui-design)
- [6.5. Prototyping](#65-prototyping)

---

## [Capítulo VII: Product Implementation, Validation & Deployment](#capítulo-vii-product-implementation-validation--deployment)

- [7.1. Software Configuration Management](#71-software-configuration-management)
- [7.2. Solution Implementation](#72-solution-implementation)
- [7.3. Validation Interviews](#73-validation-interviews)
- [7.4. Video About-the-Product](#74-video-about-the-product)

---

## [Conclusiones](#conclusiones)
## [Bibliografía](#bibliografía)
## [Anexos](#anexos)
