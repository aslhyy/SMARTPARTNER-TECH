# Informe de Análisis Tecnológico – SmartPartner Tech
## Integrantes del equipo

**1.** Aslhy Casteblanco <br>
**2.** Sarah Castro<br>
**3.** Daniela Arcila<br>
**4.** Mafe Rojas

## Introducción

El presente informe tiene como objetivo analizar la propuesta de servicios de SmartPartner Tech, una empresa enfocada en ofrecer asesoría tecnológica a PyMEs y corporaciones. Sus principales líneas de trabajo incluyen:<br>

* Mantenimiento preventivo y correctivo de equipos y redes.<br>
* Soluciones de ciberseguridad y respaldo de datos.<br>
* Consultoría estratégica en Tecnologías de la Información y Comunicación (TIC).<br>
* Gestión de infraestructura tecnológica y migración a la nube.<br>
* Implementación de software empresarial (ERP, CRM y herramientas de productividad.)<br>

El análisis se realiza desde una mirada tecnológica, proponiendo qué procesos pueden digitalizarse, qué herramientas de software y hardware serían necesarias, y justificando técnicamente la elección de las tecnologías más adecuadas para potenciar el proyecto.

## Descripción del Proyecto a Analizar

SmartPartner Tech de Jesus Campo y Eduardo Vega, busca convertirse en un aliado estratégico para la digitalización y modernización de empresas. Su propuesta se centra en cinco ejes principales: <br>

**1. Productividad continua:** minimizar tiempos de inactividad en equipos y redes.<br>
**2. Protección total:** soluciones de ciberseguridad con respaldo confiable de la información.<br>
**3. Inversión inteligente:** optimización de recursos mediante tecnologías escalables<br>
**4. Flexibilidad:** capacidad de adaptación de los sistemas y servicios según el crecimiento de la empresa.<br>
**5. Eficiencia operativa:** integración de herramientas que mejoren procesos internos y externos.<br>

Este informe pretende identificar las mejores soluciones tecnológicas para fortalecer esta propuesta de valor.

# Desarrollo del Análisis
## 1. Procesos que podrían digitalizarse y cómo

Dentro de la propuesta de SmartPartner Tech, se identifican varios procesos clave que pueden beneficiarse de la digitalización:<br>

### 1.1 Gestión de mantenimiento preventivo y correctivo

* Digitalización mediante un sistema de tickets que registre incidencias, historial de equipos, programación de revisiones y métricas de desempeño.<br>
* Uso de paneles de control para seguimiento en tiempo real.<br>

### 1.2 Consultoría estratégica en TIC

* Implementación de una plataforma colaborativa online (ej. intranet o portal web) que permita documentar diagnósticos, planes estratégicos y reportes de consultoría, con acceso para clientes y asesores.

### 1.3 Respaldo y ciberseguridad

* Automatización de respaldos en la nube y generación de alertas en tiempo real ante posibles vulnerabilidades.<br>
* Uso de dashboards para visualizar el estado de seguridad en la infraestructura tecnológica del cliente.<br>

### 1.4 Gestión de infraestructura y migración a la nube

* Creación de un sistema centralizado de monitoreo de servidores y recursos en la nube que genere métricas de consumo, disponibilidad y costos.<br>

### 1.5 Implementación de software empresarial (ERP y CRM)

* Digitalización de procesos contables, comerciales y de recursos humanos a través de módulos ERP y CRM integrados.<br>
* Registro y análisis de datos que permitan la toma de decisiones basadas en información.<br>

#### La digitalización se enfocaría en tres frentes principales:

**~** Automatización y control de tareas críticas.<br>
**~** Gestión de la información en tiempo real mediante plataformas en la nube.<br>
**~** Integración de sistemas para mejorar la productividad y la eficiencia.<br>

## 2. Software propuesto (arquitectura, tecnologías, frameworks o lenguajes)

Con el fin de apoyar la misión de SmartPartner Tech, se plantea la creación de una Plataforma Integral de Gestión Tecnológica (PIGT).

La idea principal es ofrecer un espacio único en el que la empresa y sus clientes puedan interactuar de manera ágil para resolver problemas, planear mantenimientos y monitorear la seguridad de sus equipos y redes. Con esta herramienta se busca mejorar la comunicación, agilizar los procesos y garantizar que la tecnología de los clientes funcione de forma estable y segura.

### 2.1 Arquitectura Propuesta

La solución estará construida bajo una arquitectura modular en capas. Esto significa que cada parte del sistema tendrá una función clara y podrá crecer o adaptarse fácilmente en el futuro.

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

**1. Gestión de tickets**: Los clientes podrán reportar incidentes y darles seguimiento hasta su solución.<br>
**2. Mantenimientos programados**: Un calendario que avise cuándo se harán las revisiones preventivas.<br>
**3. Alertas básicas de ciberseguridad**: Notificaciones sobre respaldos o posibles problemas en la red.<br>
**4. Inventario de activos tecnológicos**: Registro de equipos, licencias y configuraciones de cada cliente.<br>
**5. Reportes ejecutivos**: Resúmenes claros con indicadores sobre disponibilidad, productividad y costos.

### 2.4 Escalabilidad y Futuras Integraciones

Gracias a su diseño modular, la plataforma podrá crecer y adaptarse a nuevas necesidades. Algunas evoluciones posibles son:

* **Integración con ERP/CRM** (ejemplo: Odoo, Zoho, Dynamics 365).
* **Conexión con Google Workspace o Microsoft 365** para centralizar la productividad.
* **Automatización de monitoreo avanzado** con sensores o alertas en tiempo real.
* **Migración de aplicaciones a la nube** para optimizar costos y rendimiento.


## 3. Hardware o IoT necesarios (dispositivos, integración y justificación)

En el desarrollo del proyecto, el grupo requiere la implementación de diferentes tipos de hardware que respalden su propuesta tecnológica. Dentro de estos se incluyen servidores y sistemas de almacenamiento para la gestión segura de la información, equipos de cómputo como estaciones de trabajo y laptops que faciliten la productividad del personal, así como periféricos de apoyo. 

De igual manera, necesitan dispositivos de red (routers, switches, firewalls y access points) que garanticen la conectividad estable y segura, además de sistemas de respaldo energético (UPS) y equipos de monitoreo ambiental que protejan la infraestructura frente a fallas o contingencias. 

Con este conjunto de hardware, el proyecto asegura una base sólida que, en conjunto con el software y los servicios planteados, permite alcanzar los objetivos de continuidad, seguridad y eficiencia operativa.

### 3.1 Servidores físicos y sistemas de almacenamiento

* **Función en la empresa:**
Permiten alojar aplicaciones críticas (ERP, CRM, bases de datos, correo corporativo, etc.) y almacenar grandes volúmenes de información de forma centralizada.

* **Beneficio:**
Garantizan acceso seguro, rápido y confiable a la información y servicios internos, evitando pérdida de datos y mejorando la continuidad del negocio.

### 3.2 Estaciones de trabajo, laptops y periféricos

* **Función en la empresa:**
Son las herramientas que usan los colaboradores en sus actividades diarias (ofimática, diseño, programación, análisis de datos, atención al cliente).

* **Beneficio:**
Incrementan la productividad al adaptarse a las necesidades específicas de cada área (ejemplo: un diseñador requiere una workstation potente, mientras que un área administrativa puede trabajar con laptops más ligeras).

### 3.3 Equipos de red (routers, switches, firewalls y access points)

* **Función en la empresa:**
Conectan a todos los dispositivos entre sí y con internet, organizan el tráfico de datos y protegen la red frente a ataques externos.

* **Beneficio:**
Proveen conectividad estable, segmentación de la red, acceso seguro para usuarios y protección contra ciberamenazas.

### 3.4 Sistemas de respaldo energético (UPS) y monitoreo ambiental

* **Función en la empresa:**
Mantienen los equipos funcionando ante cortes de energía y permiten vigilar variables como temperatura o humedad en salas de servidores.

* **Beneficio:**
Protegen la infraestructura crítica contra apagones, sobrecargas o daños físicos, reduciendo riesgos de pérdida de datos y aumentando la vida útil de los equipos.
Daniela

## 4. Justificación técnica de las herramientas elegidas
La propuesta tecnológica de SmartPartner Tech combina de manera estratégica soluciones de software, servicios en la nube e infraestructura de hardware, asegurando una plataforma robusta, escalable y segura que responde a las necesidades de las PyMEs y corporaciones.

### 4.1 Infraestructura de Hardware

* **Servidores y sistemas de almacenamiento:** proporcionan capacidad de cómputo y resguardo confiable de la información, garantizando disponibilidad y seguridad de los datos.

* **Estaciones de trabajo y laptops:** permiten la productividad del equipo técnico y administrativo, facilitando la operación diaria y el soporte ágil a los clientes.

* **Dispositivos de red (routers, switches, firewalls, access points):** aseguran conectividad estable, segmentación adecuada y protección frente a accesos no autorizados.

* **UPS y sistemas de respaldo energético:** mantienen la continuidad de los servicios ante fallas eléctricas.

* **Equipos de monitoreo ambiental:** protegen la infraestructura física al detectar condiciones críticas (temperatura, humedad, fallos en la energía).

### 4.2 Plataforma Integral de Gestión Tecnológica (PIGT)

* **Arquitectura modular en capas:** facilita la escalabilidad y adaptación futura.

* **Frontend (React, Next.js, Tailwind, React Native):** garantiza una experiencia de usuario moderna, rápida y adaptable a web y móvil.

* **Backend (Node.js con NestJS, APIs REST/GraphQL):** ofrece un sistema estable, mantenible e integrable con otras soluciones empresariales (ERP, CRM, productividad).

* **Bases de datos (PostgreSQL, Redis):** optimizan el manejo de datos estructurados y las consultas en tiempo real.

* **Seguridad (OAuth 2.0, OpenID Connect, JWT, TLS/SSL, respaldos automáticos):** protegen la información sensible y fortalecen la confianza de los clientes.

* **Gestión y despliegue (Docker, Kubernetes, CI/CD):** aseguran actualizaciones continuas sin afectar la operación y permiten una administración eficiente en la nube.

### 4.3 Alineación con los objetivos del proyecto

La integración de hardware y software asegura:

* **Continuidad operativa:** gracias a la redundancia energética, la nube y los mantenimientos programados.

* **Seguridad integral:** con protección física (hardware), digital (ciberseguridad) y lógica (autenticación y respaldos).

* **Eficiencia y productividad:** al combinar herramientas de gestión, reportes ejecutivos y equipos de alto rendimiento.

* **Escalabilidad y flexibilidad:** tanto la infraestructura como la plataforma pueden crecer según la demanda del negocio.

En conjunto, estas herramientas son las más adecuadas porque construyen una base tecnológica sólida y confiable, potenciando la misión de SmartPartner Tech de ofrecer productividad continua, protección total, inversión inteligente y eficiencia operativa a sus clientes.

## 5. Despliegue de la solución tecnológica

El despliegue de la propuesta de SmartPartner Tech se plantea utilizando servicios en la nube confiables y escalables, para garantizar disponibilidad, seguridad y facilidad de mantenimiento.

### 5.1 Hosting y servidores

* **Frontend (Vercel o Netlify):** <br>
Estos servicios están optimizados para frameworks modernos como React, Next.js, Angular o Vue. Permiten despliegue continuo desde GitHub, es decir, cada vez que el equipo actualiza el repositorio, la página se actualiza automáticamente sin necesidad de configuraciones complejas. Además, incluyen certificados SSL y CDN integrados, lo que mejora la seguridad y velocidad de la web.

* **Backend (Heroku o AWS Elastic Beanstalk):** <br>
Heroku es ideal para PyMEs que buscan simplicidad y rapidez, ya que permite desplegar APIs y microservicios con pocos pasos.
<br><br>
AWS Elastic Beanstalk es más robusto y permite escalar automáticamente cuando la demanda de usuarios crece, algo esencial si SmartPartner Tech crece en número de clientes.

### 5.2 Bases de datos y almacenamiento

* **PostgreSQL en AWS RDS o Azure SQL Database:**<br>
Son bases de datos relacionales seguras, con respaldo automático, alta disponibilidad y soporte empresarial. Son perfectas para manejar los datos estructurados de ERP y CRM.

* **MongoDB Atlas:**<br>
Adecuado para almacenar información no estructurada como registros de actividad, logs de sistemas y datos en tiempo real. Ofrece escalado flexible sin preocuparse por servidores físicos.

* **Amazon S3 o Google Cloud Storage:**<br>
Solución de almacenamiento de bajo costo y alta disponibilidad. Permite guardar respaldos automáticos de la información de los clientes y cumplir con políticas de seguridad.

### 5.3 Ciberseguridad y acceso

* **Let’s Encrypt (SSL):**<br>
Permite habilitar HTTPS gratis, asegurando que las comunicaciones entre cliente y servidor estén cifradas.

* **Cloudflare:**<br>
Protege contra ataques DDoS, optimiza el rendimiento mediante una red de distribución de contenido (CDN) y ofrece firewall inteligente.

* **Auth0 o Firebase Authentication:**<br>
Simplifican la gestión de usuarios y roles, permitiendo login seguro con correo, redes sociales o sistemas empresariales (SSO). Garantizan cumplimiento de buenas prácticas en autenticación.

### 4.4 Monitoreo y gestión

* **Grafana + Prometheus:** <br>
Herramientas open-source que permiten visualizar métricas en tiempo real del sistema, como uso de CPU, memoria o disponibilidad de servicios. Esto asegura una operación estable y permite anticiparse a fallos.

* **Datadog:** <br>
Servicio más completo y empresarial que centraliza logs, métricas y alertas. Ideal si se necesita monitoreo avanzado con notificaciones automáticas al equipo técnico.

### 4.5 Dominios y branding corporativo

* **Namecheap o Google Domains:**
Plataformas sencillas y confiables para adquirir y gestionar dominios corporativos (ej. smartpartnertech.com).

* **Cloudflare (DNS y CDN):**
Se recomienda usarlo no solo por seguridad, sino también para mejorar la velocidad de carga de la página en diferentes países, lo cual es clave si SmartPartner Tech apunta a clientes internacionales.

## Conclusión

El análisis evidencia que la propuesta de SmartPartner Tech puede fortalecerse mediante la digitalización de procesos clave, la integración de plataformas de software empresarial, y el uso de tecnologías en la nube. Con ello, se garantiza un entorno de seguridad, escalabilidad y productividad que aporta valor tanto a PyMEs como a corporaciones.
<br><br>
La correcta elección de herramientas tecnológicas permitirá no solo responder a las necesidades actuales de las empresas, sino también anticiparse a futuros retos en ciberseguridad, infraestructura y gestión de la información.
