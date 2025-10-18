<p align="center">
  <img src="assets/upc_logo.png" alt="Logo" width="200"/>
</p>

<h3 align="center"> Universidad Peruana de Ciencias Aplicadas</h3>
<h3 align="center"> Ingeniería de Software  </h3>
<h3 align="center"> Informe de Trabajo Final – Anti-Hacking y Nuevas Tendencias de Seguridad</h3>
<h3 align="center"> NRC: 14423</h3>
<h3 align="center"> Docente: David Carlos Vera Olivera </h3>
<h3 align="center"> Nombre de la consultora: BlueLock Security</h3>

#### Integrantes
- Chero Eme, Eduardo Andre - u20201f282
- Estrada Cajamune, Abraham Andres - u202112164
- Pariona Lucas, José Manuel - u202119257
- Calle Huayanca, Adrian Alonso - u202011657
- Burga, Anaely - u202118264


<h4 align="center"> Octubre, 2025</h4>

___

# Registro de versiones del informe

| Versión | Fecha      | Autor             | Descripción de modificación                                                                           |
|---------|------------|-------------------|-------------------------------------------------------------------------------------------------------|
| 1.0     | 14/10/25   | Eduardo Chero     | Creación del archivo base en Markdown para el desarrollo del Final Project                            |
| 1.1     | 17/10/25   | Eduardo Chero     | Desarrollo del capitulo 1                           |

# Project Report Collaboration Insights
<img src="assets\ProyectReportCollaborationInsights\Insights_Report.PNG">

# Contenido

1.  [Student Outcome](#student-outcome)
2.  [Capítulo I: Introducción](#capítulo-i-introducción)
    1.  [1.1. Startup Profile (Cliente)](#11-startup-profile-cliente)
        -   [Descripción de la empresa PyME](#descripción-de-la-empresa-pyme)
        -   [Expectativas del cliente](#expectativas-del-cliente)
    2.  [1.2. Consultora de Ciberseguridad (Equipo)](#12-consultora-de-ciberseguridad-equipo)
        -   [Descripción de la consultora](#descripción-de-la-consultora)
        -   [Perfiles de los integrantes y roles Scrum](#perfiles-de-los-integrantes-y-roles-scrum)
    3.  [1.3. Solution Profile](#13-solution-profile)
        -   [Antecedentes y problemática](#antecedentes-y-problemática)
        -   [Objetivos del pentesting](#objetivos-del-pentesting)
    4.  [1.4. Aceptación del Servicio de Pentesting](#14-aceptación-del-servicio-de-pentesting)
3.  [Capítulo II: Metodología Ágil y de Pentesting](#capítulo-ii-metodología-ágil-y-de-pentesting)
    1.  [2.1. Marco de referencia](#21-marco-de-referencia)
    2.  [2.2. Backlog inicial](#22-backlog-inicial)
    3.  [2.3. Planificación de sprints (Sprint Planning)](#23-planificación-de-sprints-sprint-planning)
        -   [Sprint 1: Reconocimiento & Escaneo inicial](#sprint-1-reconocimiento--escaneo-inicial)
        -   [Sprint 2: Enumeración y vulnerabilidades preliminares](#sprint-2-enumeración-y-vulnerabilidades-preliminares)
        -   [Sprint 3: Explotación controlada (web, APIs)](#sprint-3-explotación-controlada-web-apis)
        -   [Sprint 4: Post-explotación y persistencia](#sprint-4-post-explotación-y-persistencia)
        -   [Sprint 5: Informe final y recomendaciones](#sprint-5-informe-final-y-recomendaciones)
    4.  [2.4. Definición de Done (DoD)](#24-definición-de-done-dod)
    5.  [2.5. Herramientas](#25-herramientas)
4.  [Capítulo III: Desarrollo del Proyecto por Sprints](#capítulo-iii-desarrollo-del-proyecto-por-sprints)
    1.  [Sprint 1 – Reconocimiento y Escaneo](#sprint-1--reconocimiento-y-escaneo)
    2.  [Sprint 2 – Enumeración y Vulnerabilidades](#sprint-2--enumeración-y-vulnerabilidades)
    3.  [Sprint 3 – Explotación](#sprint-3--explotación)
    4.  [Sprint 4 – Post-explotación y Persistencia](#sprint-4--post-explotación-y-persistencia)
    5.  [Sprint 5 – Informe Final y Recomendaciones](#sprint-5--informe-final-y-recomendaciones)
5.  [Capítulo IV: Resultados Consolidados](#capítulo-iv-resultados-consolidados)
    1.  [4.1. Matriz de vulnerabilidades](#41-matriz-de-vulnerabilidades)
    2.  [4.2. Evidencias técnicas](#42-evidencias-técnicas)
    3.  [4.3. Impacto en el negocio](#43-impacto-en-el-negocio)
6.  [Capítulo V: Recomendaciones y Plan de Mitigación](#capítulo-v-recomendaciones-y-plan-de-mitigación)
    1.  [5.1. Recomendaciones técnicas](#51-recomendaciones-técnicas)
    2.  [5.2. Recomendaciones organizacionales](#52-recomendaciones-organizacionales)
    3.  [5.3. Priorización por impacto/urgencia](#53-priorización-por-impactourgencia)
7.  [Capítulo VI: Conclusiones y Recomendaciones](#capítulo-vi-conclusiones-y-recomendaciones)
    -   [Conclusiones y recomendaciones del equipo](#conclusiones-y-recomendaciones-del-equipo)
    -   [Lecciones aprendidas en metodología ágil](#lecciones-aprendidas-en-metodología-ágil)
    -   [Relación con Student Outcome 2](#relación-con-student-outcome-2)
    -   [Video “About-the-Team”](#video-about-the-team)
8.  [Bibliografía](#bibliografía)


# Student Outcome
| Criterio específico | Acciones realizadas | Conclusiones |
|---|---|---|
|La capacidad de aplicar el diseño de ingeniería para producir soluciones que satisfagan necesidades específicas con consideración de salud pública, seguridad y bienestar, así como factores globales, culturales, sociales, ambientales y económicos.|||

# Capítulo I: Introducción
## 1.1. Startup Profile (Cliente)
### Descripción de la empresa PyME
Law Connect es un marketplace digital que sirve como nexo entre personas que requieren asesoría legal y abogados profesionales, facilitando un intercambio de servicios. La misión de la empresa es descentralizar el mercado legal en Perú y democratizar el acceso a abogados calificados, basándose en las valoraciones de los propios usuarios.


La plataforma utiliza herramientas tecnológicas como videollamadas, chat en vivo y la posibilidad de agendar reuniones presenciales, permitiéndole tener alcance nacional. Además, Law Connect busca ser una solución al desempleo en el sector legal, conectando abogados con clientes potenciales . Su objetivo principal es asegurar que todos tengan acceso a asesoría legal de calidad.

### Expectativas del cliente
**Confidencialidad e Integridad de Datos:** Asegurar que la información sensible de los clientes y de los abogados esté protegida contra accesos no autorizados.

**Disponibilidad del Servicio:** Garantizar que la plataforma (aplicación web, APIs, móviles)  se mantenga operativa y no sea susceptible a ataques de denegación de servicio.

**Gestión de Identidad:** Verificar la robustez de los módulos de autenticación, registro  y gestión de sesiones.

**Reporte de Vulnerabilidades:** Recibir un informe claro que identifique y priorice las vulnerabilidades encontradas para poder mitigarlas eficientemente

### Descripción de la consultora
BlueLock Security es una consultora de ciberseguridad formada por integrantes del curso enfocados en la investigación, detección y análisis de vulnerabilidades en aplicaciones y servicios de empresas que confian en nosotros para asegurarles que estos no tengan problemas ni generen riesgos de seguridad tanto para estas empresas como para los usuarios.

### Perfiles de los integrantes y roles Scrum
| Integrante | Rol | Código | Carrera | Perfil |
|---|---|---:|---|---|
| Estrada Cajamune, Abraham Andres <br> ![Abraham Perfil](assets/chapter1/members/abraham.jpg) | Scrum Master |  | Ingeniería de Software |  |
| Pariona Lucas, José Manuel <br> ![José Perfil](assets/chapter1/members/jose.jpg) | Product Owner |  | Ingeniería de Software | |
| Chero Eme, Eduardo Andre <br> ![Eduardo Perfil](assets/chapter1/members/eduardo.jpg) | Pentester Lead | U20201F282 | Ingeniería de Software | Estudiante de insgenieria de software con conocimientos en ciberseguridad Experiencia en backend y frontend (Spring Boot, Angular). |
| Calle Huayanca, Adrian Alonso <br> ![Adrian Perfil](assets/chapter1/members/adrian.jpg) | Pentester | U20201F282 | Ingeniería de Software |  |
| Burga, Anaely <br> ![Anaely Perfil](assets/chapter1/members/anaely.jpg) | Pentester | U20201F282 | Ingeniería de Software | |

## 1.3. Solution Profile
### Antecedentes y problemática
El cliente, Law Connect, opera un marketplace digital que maneja un alto volumen de información personal identificable (PII) y datos confidenciales relacionados con casos legales. La problemática de seguridad radica en que, al ser una plataforma que conecta múltiples usuarios (clientes y abogados) y que busca facilitar la búsqueda de asesoría, expone una superficie de ataque considerable.

Las principales preocupaciones de seguridad incluyen:

**Fuga de Datos:** El riesgo de exposición de datos personales de clientes y abogados, o detalles de casos legales confidenciales.

**Acceso No Autorizado:** La posibilidad de que un atacante suplante la identidad de un usuario o abogado, o escale privilegios dentro de la aplicación.

**Manipulación de Datos:** El riesgo de que se alteren las calificaciones de los abogados o los detalles de los contratos.

**Interrupción del Servicio:** Un ataque exitoso podría dejar la plataforma inoperativa, afectando el negocio principal de la startup.

### Objetivos del pentesting

**Objetivo General:** Evaluar el estado actual de la seguridad de los activos digitales de Law Connect (Aplicación Web, APIs) mediante la ejecución de pruebas de penetración controladas, siguiendo las fases de un hacking ético.

**Objetivos Específicos:**
- Identificar y explotar vulnerabilidades del OWASP Top 10 en la aplicación web.
- Evaluar la seguridad de los endpoints de las APIs utilizadas por la plataforma.
- Realizar escaneos de red y servidores para identificar servicios expuestos y vulnerabilidades conocidas.
- Priorizar los hallazgos utilizando el estándar CVSS.
- Elaborar un informe técnico y ejecutivo que incluya un plan de mitigación detallado. 

## 1.4. Aceptación del Servicio de Pentesting


# Capítulo II: Metodología Ágil y de Pentesting
## 2.1. Marco de referencia
## 2.2. Backlog inicial
## 2.3. Planificación de sprints (Sprint Planning)
### Sprint 1: Reconocimiento & Escaneo inicial
### Sprint 2: Enumeración y vulnerabilidades preliminares
### Sprint 3: Explotación controlada (web, APIs)
### Sprint 4: Post-explotación y persistencia
### Sprint 5: Informe final y recomendaciones
## 2.4. Definición de Done (DoD):  
## 2.5. Herramientas: 


# Capítulo III: Desarrollo del Proyecto por Sprints
## Sprint 1 – Reconocimiento y Escaneo
### Objetivos del sprint
### Historias de usuario atendidas
### Actividades realizadas
### Resultados y evidencias
### Retrospectiva del sprint
## Sprint 2 – Enumeración y Vulnerabilidades
### Historias de usuario atendidas
### Actividades
### Resultados y evidencias
### Retrospectiva
## Sprint 3 – Explotación
### Historias de usuario atendidas
### Actividades
### Resultados y PoC
### Retrospectiva
## Sprint 4 – Post-explotación y Persistencia
### Historias de usuario atendidas
### Actividades
### Evidencias
### Retrospectiva
## Sprint 5 – Informe Final y Recomendaciones
### Historias de usuario atendidas
### Consolidación de hallazgos y plan de mitigación
### Preparación de la presentación ejecutiva
### Retrospectiva global


# Capítulo IV: Resultados Consolidados
## 4.1. Matriz de vulnerabilidades
## 4.2. Evidencias técnicas
## 4.3. Impacto en el negocio


# Capítulo V: Recomendaciones y Plan de Mitigación
## 5.1. Recomendaciones técnicas 
## 5.2. Recomendaciones organizacionales 
## 5.3. Priorización por impacto/urgencia


# Capítulo VI: Conclusiones y Recomendaciones
## Conclusiones y recomendaciones del equipo
## Lecciones aprendidas en metodología ágil
## Relación con Student Outcome 2
## Video “About-the-Team”


# Bibliografía
