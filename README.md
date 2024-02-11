# ASO_TrabajoMonitorizacion

# 1  Las herramientas de monitorización de servidores.
       
## 1.1  Introducción general.
La monitorización de sistemas y estructuras de Tecnologías de la Información (TI) es un proceso fundamental para supervisar y analizar continuamente los componentes de una infraestructura informática, con el fin de detectar problemas y errores en tiempo real y poder resolverlos de manera efectiva. Esta práctica se lleva a cabo mediante el uso de herramientas y software especializado, que permiten recopilar, visualizar, analizar, correlacionar y alertar sobre datos de rendimiento del servidor, lo que facilita la detección y resolución efectiva de problemas. La monitorización de servidores es esencial para garantizar la disponibilidad, el rendimiento y la seguridad de los sistemas informáticos.

La monitorización de servidores abarca varios procesos fundamentales que se llevan a cabo a través de herramientas especializadas. Estos procesos incluyen la recopilación de datos, su visualización, análisis, correlación y generación de alertas. La recopilación de datos implica la obtención de información relevante desde distintas fuentes, que luego se almacena para su posterior análisis. Una vez recopilados, estos datos se visualizan y analizan para crear información útil en forma de métricas o indicadores clave de rendimiento (KPIs). La correlación de datos permite identificar relaciones entre diferentes eventos o parámetros, mientras que las alertas se generan cuando los valores obtenidos no se encuentran entre los límites correctos o no cumplen con los umbrales establecidos

Es importante tener un plan de monitorización bien definido en el que se especifiquen los objetivos, metas y parámetros a medir (KPIs), así como los umbrales de alerta a utilizar. Una vez establecido un plan de monitorización, se pueden seleccionar e implementar las herramientas adecuadas para recopilar y analizar datos sobre el rendimiento del servidor. La elección de las herramientas de monitorización adecuadas depende del tamaño del entorno a monitorear, los recursos disponibles y las necesidades específicas

La combinación de estas herramientas y un plan de monitorización eficaz es crucial para mantener un control en tiempo real sobre los sistemas y redes, lo que permite mitigar o solucionar problemas de manera efectiva. La detección temprana de problemas a través de la monitorización puede prevenir interrupciones en el servicio, pérdida de datos o vulnerabilidades en la seguridad. Por ejemplo, la detección anticipada de un aumento inusual en el uso del disco puede permitir tomar medidas preventivas antes de que se agote el espacio en disco, evitando así posibles interrupciones en el servicio
## 1.2  Las herramientas  a estudiar: ICINGA
           

 # 2  La herramienta XXX
 ## 2.1  Historia
 ## 2.2  Funciones/utilidades y características. Ventajas y desventajas
Inciga: Una plataforma para la gestión electrónica de la administración pública
Inciga es una plataforma que permite a las administraciones públicas gestionar de forma electrónica los expedientes administrativos, la tramitación de procedimientos, la comunicación con los ciudadanos, la firma electrónica y el pago electrónico.

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
En general, Inciga es una plataforma que ofrece muchas ventajas para la administración pública y los ciudadanos. Sin embargo, es importante tener en cuenta las desventajas antes de su implementación.
 ## 2.3  Plataformas posibles donde instalar  requisitos (agentes y máquinas desde las que se monitoriza).
Para instalar Inciga y cumplir con los requisitos necesarios para la monitorización de agentes y máquinas, hay varias plataformas y sistemas operativos a considerar:

Linux (Ubuntu, CentOS, Red Hat, Debian, etc.): Inciga es compatible con varias distribuciones de Linux. Puedes instalar los agentes de Inciga en máquinas que ejecuten cualquiera de estas distribuciones Linux para monitorizar su rendimiento y estado.

Windows Server: Inciga también es compatible con entornos Windows Server. Puedes instalar agentes de Inciga en servidores que utilicen sistemas operativos Windows para monitorizar su rendimiento y salud.

Cloud Platforms (AWS, Azure, Google Cloud Platform): Puedes instalar agentes de Inciga en instancias virtuales en la nube en plataformas como AWS (Amazon Web Services), Azure o Google Cloud Platform para monitorizar el rendimiento de tus recursos en la nube.

Contenedores (Docker): Inciga puede ejecutarse dentro de contenedores Docker, lo que permite una implementación fácil y portabilidad en diferentes entornos.

Entornos virtualizados (VMware, VirtualBox, Hyper-V): Si estás utilizando entornos virtualizados, puedes instalar agentes de Inciga en las máquinas virtuales para monitorizar su rendimiento y salud.

Dispositivos de red: Además de servidores y máquinas virtuales, Inciga también puede utilizarse para monitorizar dispositivos de red como enrutadores, switches y firewalls, siempre y cuando se puedan instalar agentes o se pueda acceder a ellos a través de SNMP (Simple Network Management Protocol).
 ## 2.4  Requisitos tanto de agentes como de máquinas de monitoreo.
 Los requisitos mínimos de hardware y software para Inciga pueden variar dependiendo de la cantidad de recursos que desees monitorear y la escala de tu implementación. Sin embargo, aquí hay una lista general de requisitos mínimos típicos para instalar y ejecutar Inciga:

- Requisitos de hardware:

  - CPU: Procesador de doble núcleo o superior.
  - RAM: 2 GB de RAM como mínimo. Se recomienda 4 GB o más para entornos de monitoreo más grandes.
  - Almacenamiento: Espacio suficiente en disco para instalar el software y almacenar los datos de monitoreo. Generalmente, se recomienda al menos 20 GB de espacio en disco.
  - Red: Conexión de red estable y suficiente ancho de banda para enviar y recibir datos de monitoreo.
- Requisitos de software:

  - Sistema Operativo: Inciga es compatible con una variedad de sistemas operativoAsegúrate de que estás utilizando una versión compatible del sistema operativo.
  - Java: Inciga requiere Java Runtime Environment (JRE) para ejecutarse. Asegúrese de tener instalada una versión compatible de Java en su sistema.
  - Base de datos: Inciga utiliza una base de datos para almacenar datos de monitoreo. Puedes usar MySQL, PostgreSQL o Microsoft SQL Server como base de datos backend.
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
           
           
