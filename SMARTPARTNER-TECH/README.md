# Informe de Análisis Tecnológico – SmartPartner Tech
## Integrantes del equipo

**1.** Aslhy Casteblanco 
**2.** Sarah Castro

## Introducción

El presente informe tiene como objetivo analizar la propuesta de servicios de SmartPartner Tech, una empresa enfocada en ofrecer asesoría tecnológica a PyMEs y corporaciones. Sus principales líneas de trabajo incluyen:<br>

**-** Mantenimiento preventivo y correctivo de equipos y redes.<br>
**-** Soluciones de ciberseguridad y respaldo de datos.<br>
**-** Consultoría estratégica en Tecnologías de la Información y Comunicación (TIC).<br>
**-** Gestión de infraestructura tecnológica y migración a la nube.<br>
**-** Implementación de software empresarial (ERP, CRM y herramientas de productividad.)<br>

El análisis se realiza desde una mirada tecnológica, proponiendo qué procesos pueden digitalizarse, qué herramientas de software y hardware serían necesarias, y justificando técnicamente la elección de las tecnologías más adecuadas para potenciar el proyecto.

## Descripción del Proyecto a Analizar

SmartPartner Tech busca convertirse en un aliado estratégico para la digitalización y modernización de empresas. Su propuesta se centra en cinco ejes principales: <br>

**1. Productividad continua:** minimizar tiempos de inactividad en equipos y redes.<br>
**2. Protección total:** soluciones de ciberseguridad con respaldo confiable de la información.<br>
**3. Inversión inteligente:** optimización de recursos mediante tecnologías escalables<br>
**4. Flexibilidad:** capacidad de adaptación de los sistemas y servicios según el crecimiento de la empresa.<br>
**5. Eficiencia operativa:** integración de herramientas que mejoren procesos internos y externos.<br>

Este informe pretende identificar las mejores soluciones tecnológicas para fortalecer esta propuesta de valor.

## Desarrollo del Análisis
### 1. Procesos que podrían digitalizarse y cómo

Dentro de la propuesta de SmartPartner Tech, se identifican varios procesos clave que pueden beneficiarse de la digitalización:<br>

#### 1. Gestión de mantenimiento preventivo y correctivo

**~** Digitalización mediante un sistema de tickets que registre incidencias, historial de equipos, programación de revisiones y métricas de desempeño.<br>
**~** Uso de paneles de control para seguimiento en tiempo real.<br>

#### 2. Consultoría estratégica en TIC

**~** Implementación de una plataforma colaborativa online (ej. intranet o portal web) que permita documentar diagnósticos, planes estratégicos y reportes de consultoría, con acceso para clientes y asesores.

#### Respaldo y ciberseguridad

**~** Automatización de respaldos en la nube y generación de alertas en tiempo real ante posibles vulnerabilidades.<br>
**~** Uso de dashboards para visualizar el estado de seguridad en la infraestructura tecnológica del cliente.<br>

#### Gestión de infraestructura y migración a la nube

**~** Creación de un sistema centralizado de monitoreo de servidores y recursos en la nube que genere métricas de consumo, disponibilidad y costos.<br>

#### Implementación de software empresarial (ERP y CRM)

**~** Digitalización de procesos contables, comerciales y de recursos humanos a través de módulos ERP y CRM integrados.<br>
**~** Registro y análisis de datos que permitan la toma de decisiones basadas en información.<br>

#### La digitalización se enfocaría en tres frentes principales:

**°** Automatización y control de tareas críticas.<br>
**°** Gestión de la información en tiempo real mediante plataformas en la nube.<br>
**°** Integración de sistemas para mejorar la productividad y la eficiencia.<br>

### 2. Software propuesto (arquitectura, tecnologías, frameworks o lenguajes)

Con el fin de apoyar la misión de **SmartPartner Tech**, se plantea la creación de una **Plataforma Integral de Gestión Tecnológica (PIGT)**.

La idea principal es ofrecer un espacio único en el que la empresa y sus clientes puedan interactuar de manera ágil para resolver problemas, planear mantenimientos y monitorear la seguridad de sus equipos y redes. Con esta herramienta se busca mejorar la comunicación, agilizar los procesos y garantizar que la tecnología de los clientes funcione de forma estable y segura.
### 2.1 Arquitectura Propuesta

La solución estará construida bajo una **arquitectura modular en capas**. Esto significa que cada parte del sistema tendrá una función clara y podrá crecer o adaptarse fácilmente en el futuro.

* **Capa de presentación**: Una página web moderna y adaptable, que también podría tener versión móvil.
* **Capa de lógica de negocio**: El “cerebro” del sistema, encargado de procesar la información y dar respuesta a lo que los usuarios solicitan.
* **Capa de datos**: Donde se guardará la información de tickets, mantenimientos, inventarios y reportes.
* **Infraestructura en la nube**: El sistema estará alojado en plataformas como AWS, Azure o Google Cloud, lo que permite alta disponibilidad y escalabilidad según la demanda.

### 2.2 Tecnologías Seleccionadas

**Frontend (interfaz de usuario)**

* **React con Next.js**: para construir una página web rápida y fluida.
* **Tailwind CSS**: para dar un diseño moderno y uniforme.
* **React Native**: posibilidad de crear una aplicación móvil en el futuro.

**Backend (servidor y lógica de negocio)**

* **Node.js con NestJS (TypeScript)**: permite desarrollar un sistema modular y fácil de mantener.
* **APIs REST/GraphQL**: facilitan la conexión con otros sistemas (ERP, CRM o herramientas de productividad).

**Base de Datos**

* **PostgreSQL**: donde se guardará la información estructurada de clientes, tickets y activos.
* **Redis**: para agilizar consultas rápidas, como el estado de un ticket en tiempo real.

**Seguridad y Autenticación**

* **OAuth 2.0 / OpenID Connect**: ingreso seguro con cuentas de Google o Microsoft.
* **JWT (tokens)**: manejo seguro de sesiones de usuario.
* **TLS/SSL y respaldos automáticos**: protección de la información en todo momento.

**Gestión y Despliegue**

* **Docker + Kubernetes**: empaquetar y administrar los servicios de forma ordenada.
* **CI/CD (GitHub Actions o GitLab CI)**: automatizar actualizaciones y mejoras sin interrumpir el servicio.
### 2.3 Funcionalidades Iniciales (MVP)

Para la primera versión de la plataforma se proponen funciones prácticas y fáciles de usar:

1. **Gestión de tickets**: Los clientes podrán reportar incidentes y darles seguimiento hasta su solución.
2. **Mantenimientos programados**: Un calendario que avise cuándo se harán las revisiones preventivas.
3. **Alertas básicas de ciberseguridad**: Notificaciones sobre respaldos o posibles problemas en la red.
4. **Inventario de activos tecnológicos**: Registro de equipos, licencias y configuraciones de cada cliente.
5. **Reportes ejecutivos**: Resúmenes claros con indicadores sobre disponibilidad, productividad y costos.

### 2.4 Escalabilidad y Futuras Integraciones

Gracias a su diseño modular, la plataforma podrá crecer y adaptarse a nuevas necesidades. Algunas evoluciones posibles son:

* **Integración con ERP/CRM** (ejemplo: Odoo, Zoho, Dynamics 365).
* **Conexión con Google Workspace o Microsoft 365** para centralizar la productividad.
* **Automatización de monitoreo avanzado** con sensores o alertas en tiempo real.
* **Migración de aplicaciones a la nube** para optimizar costos y rendimiento.


### 3. Hardware o IoT necesarios (dispositivos, integración y justificación)

En el desarrollo del proyecto, el grupo requiere la implementación de diferentes tipos de hardware que respalden su propuesta tecnológica. Dentro de estos se incluyen servidores y sistemas de almacenamiento para la gestión segura de la información, equipos de cómputo como estaciones de trabajo y laptops que faciliten la productividad del personal, así como periféricos de apoyo. De igual manera, necesitan dispositivos de red (routers, switches, firewalls y access points) que garanticen la conectividad estable y segura, además de sistemas de respaldo energético (UPS) y equipos de monitoreo ambiental que protejan la infraestructura frente a fallas o contingencias. Con este conjunto de hardware, el proyecto asegura una base sólida que, en conjunto con el software y los servicios planteados, permite alcanzar los objetivos de continuidad, seguridad y eficiencia operativa.

Servidores físicos y sistemas de almacenamiento

Función en la empresa:
Permiten alojar aplicaciones críticas (ERP, CRM, bases de datos, correo corporativo, etc.) y almacenar grandes volúmenes de información de forma centralizada.

Beneficio:
Garantizan acceso seguro, rápido y confiable a la información y servicios internos, evitando pérdida de datos y mejorando la continuidad del negocio.

 Estaciones de trabajo, laptops y periféricos

Función en la empresa:
Son las herramientas que usan los colaboradores en sus actividades diarias (ofimática, diseño, programación, análisis de datos, atención al cliente).

Beneficio:
Incrementan la productividad al adaptarse a las necesidades específicas de cada área (ejemplo: un diseñador requiere una workstation potente, mientras que un área administrativa puede trabajar con laptops más ligeras).

Equipos de red (routers, switches, firewalls y access points)

Función en la empresa:
Conectan a todos los dispositivos entre sí y con internet, organizan el tráfico de datos y protegen la red frente a ataques externos.

Beneficio:
Proveen conectividad estable, segmentación de la red, acceso seguro para usuarios y protección contra ciberamenazas.

Sistemas de respaldo energético (UPS) y monitoreo ambiental

Función en la empresa:
Mantienen los equipos funcionando ante cortes de energía y permiten vigilar variables como temperatura o humedad en salas de servidores.

Beneficio:
Protegen la infraestructura crítica contra apagones, sobrecargas o daños físicos, reduciendo riesgos de pérdida de datos y aumentando la vida útil de los equipos.
Daniela

### 4. Justificación técnica de las herramientas elegidas

## Conclusión

El análisis evidencia que la propuesta de SmartPartner Tech puede fortalecerse mediante la digitalización de procesos clave, la integración de plataformas de software empresarial, y el uso de tecnologías en la nube. Con ello, se garantiza un entorno de seguridad, escalabilidad y productividad que aporta valor tanto a PyMEs como a corporaciones.
<br>

La correcta elección de herramientas tecnológicas permitirá no solo responder a las necesidades actuales de las empresas, sino también anticiparse a futuros retos en ciberseguridad, infraestructura y gestión de la información.
