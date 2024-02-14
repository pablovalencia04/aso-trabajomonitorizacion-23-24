# ASO_TrabajoMonitorizacion

# 1  Las herramientas de monitorización de servidores.
       
## 1.1  Introducción general.
La monitorización de sistemas y estructuras de Tecnologías de la Información (TI) es un proceso fundamental para supervisar y analizar continuamente los componentes de una infraestructura informática, con el fin de detectar problemas y errores en tiempo real y poder resolverlos de manera efectiva. Esta práctica se lleva a cabo mediante el uso de herramientas y software especializado, que permiten recopilar, visualizar, analizar, correlacionar y alertar sobre datos de rendimiento del servidor, lo que facilita la detección y resolución efectiva de problemas. La monitorización de servidores es esencial para garantizar la disponibilidad, el rendimiento y la seguridad de los sistemas informáticos.

La monitorización de servidores abarca varios procesos fundamentales que se llevan a cabo a través de herramientas especializadas. Estos procesos incluyen la recopilación de datos, su visualización, análisis, correlación y generación de alertas. La recopilación de datos implica la obtención de información relevante desde distintas fuentes, que luego se almacena para su posterior análisis. Una vez recopilados, estos datos se visualizan y analizan para crear información útil en forma de métricas o indicadores clave de rendimiento (KPIs). La correlación de datos permite identificar relaciones entre diferentes eventos o parámetros, mientras que las alertas se generan cuando los valores obtenidos no se encuentran entre los límites correctos o no cumplen con los umbrales establecidos

Es importante tener un plan de monitorización bien definido en el que se especifiquen los objetivos, metas y parámetros a medir (KPIs), así como los umbrales de alerta a utilizar. Una vez establecido un plan de monitorización, se pueden seleccionar e implementar las herramientas adecuadas para recopilar y analizar datos sobre el rendimiento del servidor. La elección de las herramientas de monitorización adecuadas depende del tamaño del entorno a monitorear, los recursos disponibles y las necesidades específicas

La combinación de estas herramientas y un plan de monitorización eficaz es crucial para mantener un control en tiempo real sobre los sistemas y redes, lo que permite mitigar o solucionar problemas de manera efectiva. La detección temprana de problemas a través de la monitorización puede prevenir interrupciones en el servicio, pérdida de datos o vulnerabilidades en la seguridad. Por ejemplo, la detección anticipada de un aumento inusual en el uso del disco puede permitir tomar medidas preventivas antes de que se agote el espacio en disco, evitando así posibles interrupciones en el servicio

## 1.2  Las herramientas  a estudiar: ICINGA

 Icinga es una plataforma de monitoreo de código abierto que se utiliza para supervisar la disponibilidad y el rendimiento de los recursos informáticos, como servidores, redes, servicios y aplicaciones. Su nombre, Icinga, es una palabra zulú que significa "busca", "navega" o "examina" y se pronuncia con un chasquido consonántico.

Esta plataforma ofrece una flexibilidad, escalabilidad y capacidades avanzadas, que la ha convertido en una herramienta madura y ampliamente utilizada por administradores de sistemas y profesionales de TI. Sus características incluyen la generación de informes detallados, un sistema de alertas altamente personalizable y la capacidad de adaptarse a entornos diversos. Icinga es conocida por su capacidad para escalar desde implementaciones simples hasta despliegues complejos con miles de dispositivos monitoreados, lo que la hace atractiva para una amplia gama de usuarios en diversos sectores.          

 # 2  La herramienta XXX
 ## 2.1  Historia

Ichinga nacio el 6 de Mayo 2009, cuando un grupo de  miembros del anterior consejo asesor de la comunidad de Nagios, desarrolladores de numerosas extensiones de Nagios y personas de NETWAYS, el organizador de la Conferencia de Monitoreo de Nagios y proveedor de la plataforma MonitoringExchange (anteriormente NagiosExchange), anunciaron Icinga, como una nueva bifurcación del código, como respuesta a su descontento por el cuello de botella existente en ese momento en el desarrollo del software de Nagios, y su deseo de abrir su desarrollo a una base más amplia. 
En su primer año, los desarrolladores de Icinga lanzaron versiones separadas del núcleo, API e interfaz web, y celebraron su descarga número 10,000. En 2010, el proyecto Icinga lanzó un núcleo e interfaz web unificados y estables; añadió soporte para la transición de IPv4 a IPv6, optimizó la conectividad de la base de datos y renovó la interfaz de usuario con su "Icinga Web", e integró varios complementos de la comunidad (PNP4Nagios, LConf, Heatmap y Business Process Addon) logrando más de 100,000 descargas y aumentado a 23 la cantidad de miembros del equipo. 

Esta buena trayectoria como su potencial fueron respaldados con la inclusión por parte Jeffrey Hammond, de la empresa Forrester Research, en la lista de proyectos de código abierto "creciente" (en contraposición a "menguante"). 

En octubre de 2012, el proyecto Icinga presentó un avance tecnológico significativo: Icinga 2. Este fue un desarrollo paralelo y un reemplazo del marco de trabajo del núcleo original. Los desarrolladores de Icinga expresaron su intención de reescribir el núcleo para abordar problemas como la configuración complicada y las limitaciones de escalabilidad en implementaciones de gran tamaño. El proyecto también anunció planes para desarrollar el núcleo de Icinga 2 principalmente en lenguaje C++, diseñar una nueva arquitectura de cargador de componentes y remodelar el proceso de ejecución de las verificaciones de monitorización, pero esto no ocurrió hasta el 2014, cuando se lanzó la primera versión estable de Icinga 2, que incluía características como un agente y una API, que estaban programadas para ser lanzadas en el futuro y desarrolladas principalmente en lenguaje C++. Además, presentó una nueva arquitectura de cargador de componentes, así como una remodelación del proceso de ejecución de las verificaciones de monitorización.

Icinga ha experimentado un desarrollo constante, con lanzamientos frecuentes y un crecimiento significativo en su base de usuarios. Su arquitectura modular, capacidad para recopilar datos de manera eficiente, generación de informes detallados, sistema de alertas altamente personalizable y capacidad para escalar desde implementaciones simples hasta despliegues complejos con miles de dispositivos monitoreados la convierten en una herramienta atractiva para una amplia gama de usuarios. La Última versión estable2.14.2 se lanzó el 18 de enero de 2024.

 
 ## 2.2  Funciones/utilidades y características. Ventajas y desventajas
Icinga: Una plataforma para la gestión electrónica de la administración pública
Icinga es una plataforma que permite a las administraciones públicas gestionar de forma electrónica los expedientes administrativos, la tramitación de procedimientos, la comunicación con los ciudadanos, la firma electrónica y el pago electrónico.

- Funciones:

  - Gestión de expedientes: Creación, seguimiento y gestión de expedientes administrativos de forma electrónica.
  - Tramitación electrónica: Presentación de solicitudes, consulta de expedientes y recepción de notificaciones.
  - Comunicación electrónica: Envío de mensajes, solicitud de información y realización de trámites.
  - Firma electrónica: Firma electrónica de documentos.
  - Pago electrónico: Pago de tasas y otros tributos.

- Utilidades:

  - Mejora la eficiencia de la administración pública: Agiliza los trámites, reduce el tiempo de espera y los costes.
  - Mejora la transparencia: Permite a los ciudadanos acceder a la información pública de forma más fácil.
  - Mejora la participación ciudadana: Facilita la participación de los ciudadanos en la toma de decisiones.
  - Mejora la accesibilidad: Permite a los ciudadanos acceder a los servicios públicos de forma más fácil.

- Características:

  - Plataforma segura y fiable: Cumple con los más altos estándares de seguridad.
  - Fácil de usar: Tanto para la administración como para los ciudadanos.
  - Personalizable: Se puede adaptar a las necesidades de cada administración.
  - Escalable: Se puede adaptar a las necesidades de cualquier administración.

- Ventajas:

  - Mejora la eficiencia, la transparencia, la participación y la accesibilidad.
  - Plataforma segura, fácil de usar, personalizable y escalable.

- Desventajas:

  - Coste de implementación: Puede ser costosa para las administraciones.
  - Necesidad de formación: Los usuarios necesitan formación para usarla.
  - Riesgo de brecha digital: Puede aumentar la brecha entre los ciudadanos con y sin acceso a internet.
En general, Icinga es una plataforma que ofrece muchas ventajas para la administración pública y los ciudadanos. Sin embargo, es importante tener en cuenta las desventajas antes de su implementación.
 ## 2.3  Plataformas posibles donde instalar  requisitos (agentes y máquinas desde las que se monitoriza).
Para instalar Icinga y cumplir con los requisitos necesarios para la monitorización de agentes y máquinas, hay varias plataformas y sistemas operativos a considerar:

Linux (Ubuntu, CentOS, Red Hat, Debian, etc.): Icinga es compatible con varias distribuciones de Linux. Puedes instalar los agentes de Icinga en máquinas que ejecuten cualquiera de estas distribuciones Linux para monitorizar su rendimiento y estado.

Windows Server: Icinga también es compatible con entornos Windows Server. Puedes instalar agentes de Icinga en servidores que utilicen sistemas operativos Windows para monitorizar su rendimiento y salud.

Cloud Platforms (AWS, Azure, Google Cloud Platform): Puedes instalar agentes de Icinga en instancias virtuales en la nube en plataformas como AWS (Amazon Web Services), Azure o Google Cloud Platform para monitorizar el rendimiento de tus recursos en la nube.

Contenedores (Docker): Icinga puede ejecutarse dentro de contenedores Docker, lo que permite una implementación fácil y portabilidad en diferentes entornos.

Entornos virtualizados (VMware, VirtualBox, Hyper-V): Si estás utilizando entornos virtualizados, puedes instalar agentes de Icinga en las máquinas virtuales para monitorizar su rendimiento y salud.

Dispositivos de red: Además de servidores y máquinas virtuales, Icinga también puede utilizarse para monitorizar dispositivos de red como enrutadores, switches y firewalls, siempre y cuando se puedan instalar agentes o se pueda acceder a ellos a través de SNMP (Simple Network Management Protocol).
 ## 2.4  Requisitos tanto de agentes como de máquinas de monitoreo.
 Los requisitos mínimos de hardware y software para Icinga pueden variar dependiendo de la cantidad de recursos que desees monitorear y la escala de tu implementación. Sin embargo, aquí hay una lista general de requisitos mínimos típicos para instalar y ejecutar Icinga:

- Requisitos de hardware:

  - CPU: Procesador de doble núcleo o superior.
  - RAM: 2 GB de RAM como mínimo. Se recomienda 4 GB o más para entornos de monitoreo más grandes.
  - Almacenamiento: Espacio suficiente en disco para instalar el software y almacenar los datos de monitoreo. Generalmente, se recomienda al menos 20 GB de espacio en disco.
  - Red: Conexión de red estable y suficiente ancho de banda para enviar y recibir datos de monitoreo.
- Requisitos de software:

  - Sistema Operativo: Icinga es compatible con una variedad de sistemas operativoAsegúrate de que estás utilizando una versión compatible del sistema operativo.
  - Java: Icinga requiere Java Runtime Environment (JRE) para ejecutarse. Asegúrese de tener instalada una versión compatible de Java en su sistema.
  - Base de datos: Icinga utiliza una base de datos para almacenar datos de monitoreo. Puedes usar MySQL, PostgreSQL o Microsoft SQL Server como base de datos backend.
 ## 2.5  Esquema de Red (entorno). Máquinas, dirección de la red, IP’s, S.O. de las máquinas, servicios instalados. 
![esquema](diagrama.png)
## 2.6  Instalación y configuración en máquinas a monitorizar.
### Instalación y Configuración de Icinga en un Servidor Windows

**Preparación del servidor:**

* **Actualice el sistema operativo:** Asegúrese de tener la última versión de Windows Server instalada.
* **Instale el paquete de .NET Framework 4.8:** Icinga requiere .NET Framework para funcionar.
* **Instale el módulo de Windows PowerShell ISE:** Se utiliza para ejecutar scripts de PowerShell para la configuración.
* **Descargue los archivos de instalación:** Obtenga la última versión de Icinga desde el sitio web oficial: https://icinga.com/get-started/download/

**Instalación de Icinga:**

1. **Ejecute el instalador:** Inicie el archivo `icinga-windows-x64.msi` y siga las instrucciones en pantalla.
2. **Elija el tipo de instalación:** Seleccione "Servidor Icinga" para una instalación completa con la interfaz web y la base de datos.
3. **Configure los componentes:** Elija los módulos de Icinga que desea instalar. Se recomienda instalar los módulos básicos como `icinga2`, `icingaweb2` e `ido-mysql`.
4. **Configure la base de datos:** Seleccione "Usar una base de datos existente" e ingrese la información de su servidor MySQL.
5. **Complete la instalación:** Siga las instrucciones en pantalla para finalizar la instalación.

**Configuración de Icinga:**

1. **Configure el archivo de configuración principal:** Abra el archivo `icinga2.conf` en un editor de texto como Notepad++.
2. **Ajuste la configuración general:** Modifique la configuración según sus necesidades, como la zona horaria, el nombre del servidor y la configuración de notificaciones.
3. **Defina los hosts y servicios a monitorizar:** Cree archivos de configuración para cada host y servicio que desea monitorizar. Utilice la sintaxis de Icinga para definir las comprobaciones y notificaciones.
4. **Importe la configuración:** Importe los archivos de configuración a Icinga usando el comando `icinga2 feature enable configimport`.
5. **Inicie el servicio Icinga:** Inicie el servicio `Icinga 2` para que la configuración surta efecto.

**Acceso a la interfaz web:**

1. Abra un navegador web e ingrese la dirección URL `https://localhost:5665/icingaweb2/`.
2. Inicie sesión con el usuario `icingaadmin` y la contraseña que estableció durante la instalación.
3. La interfaz web le permite ver el estado de sus hosts y servicios, administrar la configuración y crear nuevos monitores.

**Recursos adicionales:**

* Documentación oficial de Icinga: https://icinga.com/docs/icinga-2/latest/doc/04-configuration/
* Tutoriales de Icinga: https://www.youtube.com/watch?v=gmv66GIA0l8
* Foro de la comunidad de Icinga: https://community.icinga.com

# 3. Instalación y configuración en máquinas a monitorizar (agentes) y remotas.
 ## 3.1  Instalación y configuración en agentes 
 ## 3.2  Diseño de pruebas.  Decisión de servicios a monitorizar
 Con el software de monitoreo Icinga, puedes realizar una variedad de pruebas y monitorizar varios servicios en tus servidores. Aquí hay algunas pruebas que podrías realizar y servicios que podrías monitorizar en tus servidores MySQL, Apache y la máquina con Icinga:

- Pruebas de ping: Verifica la conectividad básica entre los servidores.
- Monitorización de recursos del servidor: Monitoriza el uso de CPU, memoria RAM y almacenamiento en disco en ambos servidores.
- Estado del servicio de MySQL: Verifica que el servicio de MySQL esté en ejecución y responde adecuadamente a las consultas.
- Estado del servicio de Apache: Verifica que el servicio de Apache esté en ejecución y pueda servir páginas web correctamente.
- Monitorización del uso de la base de datos: Monitoriza el rendimiento de MySQL, incluido el número de conexiones, la carga de consultas y el uso de recursos.
- Monitorización de la integridad del sitio web: Realiza pruebas de HTTP para verificar que el sitio web esté accesible y que las páginas se carguen correctamente.
- Monitorización de logs de errores: Monitoriza los logs de errores de MySQL y Apache en busca de posibles problemas.
- Monitorización de SSL/TLS: Si tu sitio web utiliza HTTPS, verifica la validez del certificado SSL/TLS y su fecha de caducidad.
- Monitorización de seguridad: Verifica que no haya vulnerabilidades conocidas en las versiones de MySQL, Apache y otros software instalados en tus servidores.
En cuanto a los servicios que deberías monitorizar:

Para el servidor de base de datos MySQL:

- Estado del servicio de MySQL.
- Uso de CPU y memoria.
- Uso de almacenamiento en disco.
- Número de conexiones activas.
- Rendimiento de las consultas.
  
Para el servidor web Apache:

- Estado del servicio de Apache.
- Uso de CPU y memoria.
- Uso de almacenamiento en disco.
- Carga del servidor y número de solicitudes.
- Tiempo de respuesta del servidor web.
- Códigos de estado HTTP.
 ## 3.3  Puesta en marcha (pruebas) y ejemplo de uso.

 # 4  [Otros puntos a investigar según la herramienta]

    • Instalación mediante script en las máquinas de la red a monitorizar.
    • Monitorización remota por SSH  o en consola. 
    • Monitorización usando el navegador web.Alerta a usuario 
    • Tarea programada (si procede) en cron.
    • Otros usos: proxy, etc 

 # 5  Conclusiones y problemas encontrados 
 Conclusiones tras conocer la herramienta. Indicar también problemas (y cómo se han solventado).


 # 6  OPCIONAL --- Comparativa con otras herramientas (trabajo de otro equipo)
 ## 6.1   Funciones/utilidades y características. Ventajas y desventajas
 ## 6.2   Plataformas y  requisitos.
 ## 6.3  Conclusión tras la comparativa (si lo consideras necesario)

 # 7  Bibliografía


# ANEXO. Desarrollo del proyecto con SCRUM
## I. Equipo y roles
## II. Reuniones realizadas (events)
## III. Documentos: 
- link al backlog del equipo  -- no olvidar compartir con mctripiana@iesgrancapitan.org --
- Añadir (compartir en drive, link) cualquier otro documento que sea necesario
           
           
