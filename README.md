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
# Capítulo I: Introducción
## 1.1. Startup Profile (Cliente)
### Descripción de la empresa PyME
### Expectativas del cliente
## 1.2. Consultora de Ciberseguridad (Equipo)
### Descripción de la consultora
### Perfiles de los integrantes y roles Scrum
## 1.3. Solution Profile
### Antecedentes y problemática
### Objetivos del pentesting
## 1.4. Aceptación del Servicio de Pentesting


# Capítulo II: Metodología Ágil y de Pentesting
## 2.1. Marco de referencia
Para la ejecución de este proyecto de auditoría de seguridad para Law Connect, nuestro equipo ha adoptado un marco de trabajo ágil basado en Scrum con los estándares técnicos y las fases estructuradas de metodologías líderes en ciberseguridad.

**Scrum:** Utilizamos Scrum para gestionar el proyecto de pentesting como una serie de 5  sprints de corta duración. Cada Sprint se enfoca en un conjunto específico de objetivos de seguridad.

**PTES (Penetration Testing Execution Standard):** Las fases técnicas de nuestro trabajo siguen el estándar PTES, que divide el proceso en:

- Interacciones previas (Planificación)
- Recolección de Inteligencia (Reconocimiento)
- Modelado de Amenazas
- Análisis de Vulnerabilidades (Escaneo)
- Explotación
- Post-Explotación
- Reporte

**OWASP Top 10 (Open Worldwide Application Security Project):** Este recurso nos ayudara como una guia para reconocer las vulnerabilidades mas comunes dentro de una app web y sus servicios asi como sus posibles soluciones.

## 2.2. Backlog inicial

| ID     | Épica         | Historia de Usuario | Criterios de Aceptación |
|--------|---------------|---------------------|----------------------------------------|
| US-01  | Planificación | **Como** Product Owner, **quiero** definir y documentar el alcance autorizado (dominios, IPs) con "Law Connect", **para** asegurar que todas las pruebas se mantengan dentro de las Reglas de Compromiso. | **Given**: tenemos la reunión inicial con el cliente. **When**: se documentan los activos. **Then**: el cliente firma el documento de autorización. |
| US-02  | Reconocimiento | **Como** pentester externo, **quiero** recolectar información pública sobre "Law Connect", **para** identificar tecnologías, subdominios y empleados sin enviar tráfico directo. | **Given**: el nombre del dominio principal. **When**: utilizo técnicas de `Google Dorking`, `Shodan` y análisis de repositorios. **Then**: se genera un listado de subdominios, tecnologías y posibles correos de empleados. |
| US-03  | Escaneo       | **Como** pentester, **quiero** identificar todos los hosts vivos dentro del rango de IP autorizado, **para** mapear la infraestructura activa. | **Given**: el rango de IP del cliente. **When**: ejecuto un escaneo de descubrimiento `nmap -sn`. **Then**: se entrega una lista de IPs que respondieron al escaneo. |
| US-04  | Escaneo       | **Como** pentester, **quiero** escanear los puertos TCP/UDP abiertos en los hosts vivos, **para** enumerar los servicios y versiones expuestos. | **Given**: la lista de IPs activas. **When**: ejecuto un escaneo de puertos y servicios `nmap -sV -p-`. **Then**: se entrega un reporte detallando IP, Puerto, Servicio y Versión de cada servicio expuesto. |
| US-05  | Reconocimiento | **Como** pentester, **quiero** identificar los proveedores de servicios en la nube y posibles buckets de almacenamiento mal configurados, **para** buscar fugas de información. | **Given**: el dominio del cliente. **When**: utilizo herramientas de enumeración de cloud. **Then**: se documenta si existen buckets públicos o accesibles. |
| US-06  | Escaneo | **Como** pentester, **quiero** ejecutar un escaneo automatizado con `Nessus` contra los servicios expuestos **para** identificar rápidamente CVEs y fallos de configuración conocidos. | **Given**: los resultados del escaneo `Nmap` **When**: configuro y ejecuto un escaneo completo de `Nessus`, **Then**: se genera un reporte priorizado de vulnerabilidades de infraestructura |
| US-07  | Escaneo Web | **Como** pentester web, **quiero** realizar un escaneo automatizado con `OWASP ZAP` contra la aplicación web de "Law Connect", **para** identificar vulnerabilidades comunes del OWASP Top 10. | **Given**: la URL de la aplicación web. **When**: ejecuto el escáner activo de `ZAP`. **Then**: se genera un reporte inicial de hallazgos. |
| US-08  | Enumeración API | **Como** pentester de API, **quiero** enumerar todos los endpoints de la API REST de "Law Connect", **para** entender la superficie de ataque de la API. | **Given**: la URL base de la API. **When**: utilizo fuzzing de directorios y endpoints. **Then**: se entrega un listado de endpoints válidos y sus códigos de respuesta. |
| US-9  | Enumeración Web | **Como** pentester web, **quiero** mapear manualmente la aplicación web (login, perfiles, búsqueda de abogados, gestión de casos) usando Burp Suite, **para** entender el flujo de la aplicación. | **Given**: la URL de la aplicación y credenciales de prueba. **When**: navego por todas las funciones de cliente y abogado con el proxy interceptando. **Then**: se genera un Site Map en Burp Suite que identifica todas las funciones clave. |
| US-10  | Explotación Web | **Como** pentester, **quiero** explotar una vulnerabilidad de Inyección SQL en el "buscador de abogados", **para** obtener una Prueba de Concepto (PoC) de extracción de datos. | **Given**: un formulario de búsqueda sospechoso. **When**: ejecuto sqlmap para confirmar y explotar la inyección. **Then**: se obtiene una PoC. |
| US-11  | Explotación Web | **Como** pentester, **quiero** acceder a los casos legales del "Cliente X" manipulando los IDs en la URL (IDOR), **para** demostrar el control de acceso roto. | **Given**: estoy autenticado como "Cliente A" y conozco el ID de un caso del "Cliente X". **When**: intercepto la solicitud y la cambio por la del "Cliente X". **Then**: se obtiene una PoC mostrando el acceso exitoso a los datos ajenos. |
| US-12  | Explotación Web | **Como** pentester, **quiero** inyectar un script (XSS) en el perfil del abogado, **para** demostrar que puedo "robar" la cookie de sesión de un cliente que visite ese perfil. | **Given**: un campo vulnerable a XSS en el perfil. **When**: inyecto una carga útil de XSS. **Then**: el script se ejecuta exitosamente en el navegador de la víctima. |
| US-13  | Explotación Infra. | **Como** pentester, **quiero** explotar un servicio de red vulnerable en un servidor de "Law Connect", **para** obtener una shell inicial. | **Given**: una vulnerabilidad de infraestructura explotable, **When**: utilizo Metasploit para lanzar el exploit correspondiente. **Then**: se obtiene una captura de pantalla de la shell o sesión de Meterpreter. |


## 2.3. Planificación de sprints (Sprint Planning)

### Sprint 1: Reconocimiento & Escaneo inicial
### Sprint 2: Enumeración y vulnerabilidades preliminares
### Sprint 3: Explotación controlada (web, APIs)
### Sprint 4: Post-explotación y persistencia
### Sprint 5: Informe final y recomendaciones
## 2.4. Definición de Done (DoD):  
Para este proyecto, una historia de usuario de seguridad no se considera **"Done"** hasta que el equipo de consultoría haya validado el cumplimiento de los siguientes puntos clave:

- Evidencia Clara: Se debe adjuntar toda la evidencia técnica necesaria para sustentar el hallazgo dentro de este informe.
- Reproducibilidad: Se debe tener una documentacion clara y entendible tanto para el equipo de trabajo como para el cliente.
- Documentación de PoC (Prueba de Concepto): Para las historias de usuario de explotación, se debe incluir una Prueba de Concepto controlada, en donde se debe demostrar la explotabilidad de la vulnerabilidad y su impacto potencial, sin causar daños al entorno productivo del cliente.
- Análisis de Impacto: Cada hallazgo debe ir acompañado de un análisis de riesgo, incluido la asignación de un puntaje de severidad basado en el estándar CVSS y una descripción cualitativa del impacto potencial para el negocio.

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
