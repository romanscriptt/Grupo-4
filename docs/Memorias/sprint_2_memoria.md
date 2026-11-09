# Memoria Final — Sprint 2

## Integrantes del grupo y coevaluación:
- Álvaro López 95%
- Ángel Luis Sánchez 95%
- Carmen Monge 95%
- Elena Sáez 95%


## 1. Sector profesional y perfil de usuarios
### 1.1 Contexto:
A día de hoy, la competitividad en el sector de la logística la gana quien posee los datos más limpios y procesables. El uso de la IA, IoT y Transportation Management System (TMS) han dejado de ser una mejora y pasan a ser la base operativa. El control, la visibilidad y la sostenibilidad actualmente son los activos más valorados en el sector. Estos permiten a las empresas ser ágiles en un mercado que actualmente no se puede permitir la fragmentación.[1]


### 1.2. Principales tendencias de digitalización:[3]
- **Automatización y robótica en almacenes:**  
Incorporación de robots, sistemas automáticos de clasificación, preparación de pedidos (picking) y gestión inteligente de inventarios.  
**Objetivo:** reducir errores, costes operativos y tiempos de preparación, aumentando la productividad.

- **Internet de las cosas (IoT) y trazabilidad en tiempo real:**  
Uso de sensores conectados en vehículos, contenedores, palés y almacenes para controlar la ubicación y las condiciones de las mercancías, como la temperatura y la humedad.  
**Objetivo:** conocer el estado de los envíos, detectar incidencias y garantizar la conservación de productos sensibles.

- **Inteligencia artificial y analítica predictiva:**  
Algoritmos para prever la demanda, optimizar rutas, planificar recursos y anticipar retrasos o interrupciones en el suministro.  
**Objetivo:** pasar de reaccionar ante los problemas a anticiparlos y tomar decisiones basadas en datos.

- **Gemelos digitales:**  
Creación de réplicas virtuales de almacenes, procesos o redes logísticas para simular cambios y analizar sus consecuencias antes de aplicarlos.  
**Objetivo:** reducir riesgos, identificar cuellos de botella y mejorar la planificación de operaciones.

- **Plataformas en la nube y conectividad 5G:**  
Integración de información sobre pedidos, inventarios, transportes y proveedores mediante sistemas conectados y servicios en la nube.  
**Objetivo:** compartir información actualizada, coordinar operaciones y mejorar la visibilidad global de la cadena de suministro.

- **Digitalización del último tramo:**  
Uso de rutas dinámicas, taquillas inteligentes, puntos de recogida y herramientas de seguimiento de entregas. Los drones y vehículos autónomos aparecen como soluciones emergentes.  
**Objetivo:** reducir los costes de reparto, mejorar la puntualidad y ofrecer mayor flexibilidad al cliente.


#### 2.1. ¿Qué es la digitalización?
La digitalización es el paso del formato físico al digital [2]


#### 2.2. ¿Qué diferencia hay entre digitalización y transformación digital?
La digitalización se enfoca en un único objeto, mientras que la transformación digital implica a todo el negocio, pudiendo requerir incluso de programas de formación [2]


#### 2.3. Ventajas de la digitalización: [2]
- **Ahorro de espacio** --> Los documentos a papel ocupan más espacio físico, el cual se puede aprovechar para otra cosas o para mantener un un entorno de trabajo más espacioso y organizado.
- **Protección de documentos** --> Si los documentos se encuentran en estado físico puede sufrir daños, ya sea por humedad, que se arruguen, rompan, pierdan, traspapelen, etc. Al tener dichos documentos en la nube o almacenados de forma externa, ese daño es reducido.
- **Rapidez en la consulta** --> Al ahorrar en tiempo en las consultas de datos se puede dedicar dicho tiempo a la elaboración de otras tareas mejorando la productividad.
- **Ahorro de papel** --> Se mejora en las cuestiones medioambientales al dejar de utilizar papel, tal y como se establece en el certificación ISO 14001 – Sistemas de Gestión Ambiental (SGA).
- **Mejor acceso a la información** --> Al poder acceder a la información de manera remota, se pueden implementar mejores medidas de seguridad, entre ellas, quién tiene permisos para ver ciertos documentos.


### 1.3. Necesidades tecnológicas del sector
La transformación digital del sector logístico hace necesario disponer de sistemas informáticos capaces de gestionar la información del almacén de forma centralizada, fiable y segura. La identificación de productos, el registro de movimientos y el seguimiento de las mercancías son aspectos fundamentales para mejorar la trazabilidad y coordinar las operaciones logísticas [4], [5].
A partir de las tendencias digitales se ha llegado a la conclusión de que las necesidades son las siguientes:
- Automatización
- Conectividad
- Análisis de datos
- Integración de sistemas
- Seguridad digital.


### 1.4. Identificación y clasificación de los perfiles de usuarios
La aplicación SGA será utilizada por personas que desempeñan diferentes funciones dentro del almacén y de la organización. Cada perfil tiene unas responsabilidades concretas y necesita acceder a determinadas funcionalidades. Por ello, es importante establecer un sistema de roles y permisos que permita que cada usuario consulte o modifique únicamente la información necesaria para desempeñar su trabajo. Esta separación de permisos es coherente con los modelos de gestión de usuarios y de control de operaciones que se utilizan en sistemas SGA comerciales [6].

Los perfiles que se proponen a continuación son las clasificaciones funcionales existentes en la logística de almacenamiento. No todas las empresas tienen por qué disponer de todos ellos.


#### 4.1. Ficha de usuario 1: **Administrador del sistema**
**Descripción del perfil:** Es la persona responsable de administrar la aplicación, configurar sus parámetros y gestionar las cuentas de los usuarios.
- **Objetivo principal:** garantizar el funcionamiento correcto y seguro del SGA.
- **Funciones principales:**
  - Crear, modificar y desactivar cuentas de usuario.
  - Asignar roles y permisos.
  - Configurar parámetros generales del sistema.
  - Consultar registros de actividad y errores.
  - Gestionar copias de seguridad, cuando corresponda.
- **Necesidades tecnológicas:** acceso a herramientas de administración, gestión de credenciales, registro de actividad y mecanismos de recuperación.
- **Funcionalidades del SGA:** gestión de usuarios, roles, configuración y auditoría.
- **Permisos:** acceso administrativo a la configuración.


#### 4.2. Ficha de usuario 2: **Responsable o jefe de almacén**
**Descripción del perfil:** Supervisa las operaciones diarias del almacén, organiza los recursos y comprueba que las mercancías se gestionen correctamente.
- **Objetivo principal:** optimizar el funcionamiento del almacén y cumplir los plazos de preparación y expedición.
- **Funciones principales:**
  - Supervisar las entradas y salidas de mercancías.
  - Consultar las existencias y las ubicaciones.
  - Asignar y supervisar tareas.
  - Revisar incidencias y diferencias de inventario.
  - Consultar indicadores e informes de actividad.
- **Necesidades tecnológicas:** información actualizada, paneles de control, filtros de búsqueda e informes.
- **Funcionalidades del SGA:** consulta global del almacén, supervisión de pedidos, control de inventario e informes.
- **Permisos:** consultar la información operativa y autorizar determinadas modificaciones o ajustes, según las reglas establecidas.


#### 4.3. Ficha de usuario 3: **Operario de recepción de mercancías**
**Descripción del perfil:** Se encarga de recibir las mercancías procedentes de proveedores u otros almacenes y comprobar que coincidan con la documentación correspondiente.
- **Objetivo principal:** registrar correctamente las mercancías que entran en el almacén.
- **Funciones principales:**
  - Consultar las recepciones previstas.
  - Identificar los productos recibidos.
  - Registrar cantidades, lotes y posibles incidencias.
  - Comunicar productos dañados o cantidades incorrectas.
  - Confirmar la recepción de mercancías.
- **Necesidades tecnológicas:** interfaz sencilla, búsqueda de productos, formularios rápidos y lectura de códigos de barras.
- **Funcionalidades del SGA:** recepción, consulta de pedidos de entrada, registro de cantidades e incidencias.
- **Permisos:** crear y modificar recepciones propias mientras estén pendientes de confirmación, sin acceso a la administración general.


#### 4.4. Ficha de usuario 4: **Operario de almacén y preparación de pedidos**
**Descripción del perfil:** Realiza tareas de ubicación, traslado y recogida de productos para completar los pedidos solicitados.
- **Objetivo principal:** localizar y mover las mercancías correctamente, reduciendo errores y tiempos de trabajo.
- **Funciones principales:**
  - Consultar las ubicaciones de los productos.
  - Registrar movimientos entre ubicaciones.
  - Consultar las tareas de preparación asignadas.
  - Confirmar los productos recogidos y sus cantidades.
  - Comunicar incidencias de localización o falta de existencias.
- **Necesidades tecnológicas:** acceso rápido desde dispositivos móviles, búsqueda por código y confirmación de operaciones.
- **Funcionalidades del SGA:** consulta de ubicaciones, movimientos internos, preparación de pedidos y comunicación de incidencias.
- **Permisos:** registrar los movimientos y las tareas asignadas, sin poder modificar libremente el inventario global.


#### 4.5. Ficha de usuario 5: **Responsable de inventario**
**Descripción del perfil:** Comprueba que las cantidades registradas en el sistema coincidan con las existencias físicas del almacén.
- **Objetivo principal:** mantener un inventario fiable y detectar diferencias entre los datos registrados y la realidad.
- **Funciones principales:**
  - Consultar las existencias por producto y ubicación.
  - Realizar recuentos físicos y cíclicos.
  - Registrar diferencias encontradas.
  - Revisar el historial de movimientos.
  - Proponer o ejecutar ajustes autorizados.
- **Necesidades tecnológicas:** consultas precisas, historial de operaciones, herramientas de recuento y registro de diferencias.
- **Funcionalidades del SGA:** inventario, recuentos, consulta de movimientos y gestión de ajustes.
- **Permisos:** consultar el stock y registrar recuentos; los ajustes definitivos pueden requerir autorización del responsable de almacén.


#### 4.6. Ficha de usuario 6: **Operario de expedición y preparación final**
**Descripción del perfil:** Verifica los productos preparados, los acondiciona para su envío y registra la salida de las mercancías.
- **Objetivo principal:** garantizar que los pedidos expedidos coincidan con lo solicitado y queden registrados correctamente.
- **Funciones principales:**
  - Consultar los pedidos pendientes de expedición.
  - Verificar los productos y las cantidades.
  - Registrar el embalaje y el etiquetado, si forman parte del sistema.
  - Confirmar la salida de los pedidos.
  - Comunicar errores o incidencias antes del envío.
- **Necesidades tecnológicas:** consulta de pedidos, validación de productos, generación de etiquetas cuando corresponda y registro de expediciones.
- **Funcionalidades del SGA:** expedición, consulta de pedidos, validación y trazabilidad de las salidas.
- **Permisos:** gestionar las expediciones asignadas y confirmar salidas, sin modificar la configuración del sistema.


### 1.5. Necesidades de los usuarios y requisitos de la aplicación
La identificación de los perfiles permite transformar las necesidades laborales en funcionalidades concretas del SGA.

 | Necesidad del usuario | Requisito que debe cubrir la aplicación | 
 |---|---|
 | Conocer las existencias disponibles | Consultar el stock actualizado por producto y ubicación | 
 | Registrar entradas y salidas | Disponer de formularios para confirmar los movimientos | 
 | Localizar rápidamente los productos | Permitir búsquedas por referencia, nombre o código  | 
 | Evitar errores en la preparación | Validar los productos y las cantidades de cada pedido | 
 | Conocer el historial de un producto | Consultar sus movimientos y datos de trazabilidad | 
 | Acceder solo a las funciones autorizadas | Implementar autenticación y control de permisos por rol | 
 | Detectar diferencias de inventario | Registrar recuentos, incidencias y ajustes autorizados | 
 | Supervisar el funcionamiento del almacén | Generar informes sobre existencias, movimientos y pedidos | 
 | Trabajar desde distintos dispositivos | Diseñar una interfaz adaptable a ordenadores y móviles | 

Estas necesidades se derivan de los procesos habituales de identificación, almacenamiento, preparación, expedición y trazabilidad de mercancías [4], [5], así como de la separación de responsabilidades y permisos presente en las aplicaciones SGA [6].


### 1.6. Referencias
[1] M. Hernández, «Qué es la digitalización y cuáles son sus ventajas», Telefónica. Accedido: 21 de octubre de 2026. [En línea]. Disponible en: https://www.telefonica.com/es/sala-comunicacion/blog/digitalizacion-que-es/
[2] «Digitalización logística 2026: tendencias», Synex Logistics. Accedido: 20 de octubre de 2026. [En línea]. Disponible en: https://synexlogistics.com/es/articulos/tendencias-de-la-digitalizacion-logistica-en-2026/
[3] «Tendencias logísticas 2026: Tecnologías, IA, oportunidades.», Blog Across Logistics. Accedido: 26 de octubre de 2026. [En línea]. Disponible en: https://acrosslogistics.com/blog/tendencias-logisticas/
[4] «El Sistema GS1», GS1 Spain. Accedido: 27 de octubre de 2026. [En línea]. Disponible en: https://www.gs1es.org/estandares-gs1-identificar-capturar-compartir/
[5] «GS1 Global Traceability Standard | GS1». Accedido: 27 de octubre de 2026. [En línea]. Disponible en: https://www.gs1.org/standards/gs1-global-traceability-standard/#2-Traceability-and-the-importance-of-standards
[6] «NetSuite Applications Online Help», Oracle Help Center. Accedido: 27 de octubre de 2026. [En línea]. Disponible en: https://docs.oracle.com/en/cloud/saas/netsuite/ns-online-help/section_156520480478.html
## 1. Contexto:
A día de hoy, la competitividad en el sector de la logística la gana quien posee los datos más limpios y procesables. El uso de la IA, IoT y Transportation Management System (TMS) han dejado de ser una mejora y pasan a ser la base operativa. El control, la visibilidad y la sostenibilidad actualmente son los activos más valorados en el sector. Estos permiten a las empresas ser ágiles en un mercado que actualmente no se puede permitir la fragmentación.[1]


## 2. Principales tendencias de digitalización:[3]
- **Automatización y robótica en almacenes:**  
Incorporación de robots, sistemas automáticos de clasificación, preparación de pedidos (picking) y gestión inteligente de inventarios.  
**Objetivo:** reducir errores, costes operativos y tiempos de preparación, aumentando la productividad.

- **Internet de las cosas (IoT) y trazabilidad en tiempo real:**  
Uso de sensores conectados en vehículos, contenedores, palés y almacenes para controlar la ubicación y las condiciones de las mercancías, como la temperatura y la humedad.  
**Objetivo:** conocer el estado de los envíos, detectar incidencias y garantizar la conservación de productos sensibles.

- **Inteligencia artificial y analítica predictiva:**  
Algoritmos para prever la demanda, optimizar rutas, planificar recursos y anticipar retrasos o interrupciones en el suministro.  
**Objetivo:** pasar de reaccionar ante los problemas a anticiparlos y tomar decisiones basadas en datos.

- **Gemelos digitales:**  
Creación de réplicas virtuales de almacenes, procesos o redes logísticas para simular cambios y analizar sus consecuencias antes de aplicarlos.  
**Objetivo:** reducir riesgos, identificar cuellos de botella y mejorar la planificación de operaciones.


### 2.1. ¿Qué es la digitalización?
La digitalización es el paso del formato físico al digital [2]


### 2.2. ¿Qué diferencia hay entre digitalización y transformación digital?
La digitalización se enfoca en un único objeto, mientras que la transformación digital implica a todo el negocio, pudiendo requerir incluso de programas de formación [2]


### 2.3. Ventajas de la digitalización: [2]
- **Ahorro de espacio** --> Los documentos a papel ocupan más espacio físico, el cual se puede aprovechar para otra cosas o para mantener un un entorno de trabajo más espacioso y organizado.
- **Protección de documentos** --> Si los documentos se encuentran en estado físico puede sufrir daños, ya sea por humedad, que se arruguen, rompan, pierdan, traspapelen, etc. Al tener dichos documentos en la nube o almacenados de forma externa, ese daño es reducido.
- **Rapidez en la consulta** --> Al ahorrar en tiempo en las consultas de datos se puede dedicar dicho tiempo a la elaboración de otras tareas mejorando la productividad.
- **Ahorro de papel** --> Se mejora en las cuestiones medioambientales al dejar de utilizar papel, tal y como se establece en el certificación ISO 14001 – Sistemas de Gestión Ambiental (SGA).
- **Mejor acceso a la información** --> Al poder acceder a la información de manera remota, se pueden implementar mejores medidas de seguridad, entre ellas, quién tiene permisos para ver ciertos documentos.


## 3. Necesidades tecnológicas del sector
La transformación digital del sector logístico hace necesario disponer de sistemas informáticos capaces de gestionar la información del almacén de forma centralizada, fiable y segura. La identificación de productos, el registro de movimientos y el seguimiento de las mercancías son aspectos fundamentales para mejorar la trazabilidad y coordinar las operaciones logísticas [4], [5].
A partir de las tendencias digitales se ha llegado a la conclusión de que las necesidades son las siguientes:
- Automatización
- Conectividad
- Análisis de datos
- Integración de sistemas
- Seguridad digital.

- **Plataformas en la nube y conectividad 5G:**  
Integración de información sobre pedidos, inventarios, transportes y proveedores mediante sistemas conectados y servicios en la nube.  
**Objetivo:** compartir información actualizada, coordinar operaciones y mejorar la visibilidad global de la cadena de suministro.

- **Digitalización del último tramo:**  
Uso de rutas dinámicas, taquillas inteligentes, puntos de recogida y herramientas de seguimiento de entregas. Los drones y vehículos autónomos aparecen como soluciones emergentes.  
**Objetivo:** reducir los costes de reparto, mejorar la puntualidad y ofrecer mayor flexibilidad al cliente.


## 4. Identificación y clasificación de los perfiles de usuarios
La aplicación SGA será utilizada por personas que desempeñan diferentes funciones dentro del almacén y de la organización. Cada perfil tiene unas responsabilidades concretas y necesita acceder a determinadas funcionalidades. Por ello, es importante establecer un sistema de roles y permisos que permita que cada usuario consulte o modifique únicamente la información necesaria para desempeñar su trabajo. Esta separación de permisos es coherente con los modelos de gestión de usuarios y de control de operaciones que se utilizan en sistemas SGA comerciales [6].

Los perfiles que se proponen a continuación son las clasificaciones funcionales existentes en la logística de almacenamiento. No todas las empresas tienen por qué disponer de todos ellos.


### 4.1. Ficha de usuario 1: **Administrador del sistema**
**Descripción del perfil:** Es la persona responsable de administrar la aplicación, configurar sus parámetros y gestionar las cuentas de los usuarios.
- **Objetivo principal:** garantizar el funcionamiento correcto y seguro del SGA.
- **Funciones principales:**
  - Crear, modificar y desactivar cuentas de usuario.
  - Asignar roles y permisos.
  - Configurar parámetros generales del sistema.
  - Consultar registros de actividad y errores.
  - Gestionar copias de seguridad, cuando corresponda.
- **Necesidades tecnológicas:** acceso a herramientas de administración, gestión de credenciales, registro de actividad y mecanismos de recuperación.
- **Funcionalidades del SGA:** gestión de usuarios, roles, configuración y auditoría.
- **Permisos:** acceso administrativo a la configuración.


### 4.2. Ficha de usuario 2: **Responsable o jefe de almacén**
**Descripción del perfil:** Supervisa las operaciones diarias del almacén, organiza los recursos y comprueba que las mercancías se gestionen correctamente.
- **Objetivo principal:** optimizar el funcionamiento del almacén y cumplir los plazos de preparación y expedición.
- **Funciones principales:**
  - Supervisar las entradas y salidas de mercancías.
  - Consultar las existencias y las ubicaciones.
  - Asignar y supervisar tareas.
  - Revisar incidencias y diferencias de inventario.
  - Consultar indicadores e informes de actividad.
- **Necesidades tecnológicas:** información actualizada, paneles de control, filtros de búsqueda e informes.
- **Funcionalidades del SGA:** consulta global del almacén, supervisión de pedidos, control de inventario e informes.
- **Permisos:** consultar la información operativa y autorizar determinadas modificaciones o ajustes, según las reglas establecidas.


### 4.3. Ficha de usuario 3: **Operario de recepción de mercancías**
**Descripción del perfil:** Se encarga de recibir las mercancías procedentes de proveedores u otros almacenes y comprobar que coincidan con la documentación correspondiente.
- **Objetivo principal:** registrar correctamente las mercancías que entran en el almacén.
- **Funciones principales:**
  - Consultar las recepciones previstas.
  - Identificar los productos recibidos.
  - Registrar cantidades, lotes y posibles incidencias.
  - Comunicar productos dañados o cantidades incorrectas.
  - Confirmar la recepción de mercancías.
- **Necesidades tecnológicas:** interfaz sencilla, búsqueda de productos, formularios rápidos y lectura de códigos de barras.
- **Funcionalidades del SGA:** recepción, consulta de pedidos de entrada, registro de cantidades e incidencias.
- **Permisos:** crear y modificar recepciones propias mientras estén pendientes de confirmación, sin acceso a la administración general.


### 4.4. Ficha de usuario 4: **Operario de almacén y preparación de pedidos**
**Descripción del perfil:** Realiza tareas de ubicación, traslado y recogida de productos para completar los pedidos solicitados.
- **Objetivo principal:** localizar y mover las mercancías correctamente, reduciendo errores y tiempos de trabajo.
- **Funciones principales:**
  - Consultar las ubicaciones de los productos.
  - Registrar movimientos entre ubicaciones.
  - Consultar las tareas de preparación asignadas.
  - Confirmar los productos recogidos y sus cantidades.
  - Comunicar incidencias de localización o falta de existencias.
- **Necesidades tecnológicas:** acceso rápido desde dispositivos móviles, búsqueda por código y confirmación de operaciones.
- **Funcionalidades del SGA:** consulta de ubicaciones, movimientos internos, preparación de pedidos y comunicación de incidencias.
- **Permisos:** registrar los movimientos y las tareas asignadas, sin poder modificar libremente el inventario global.


### 4.5. Ficha de usuario 5: **Responsable de inventario**
**Descripción del perfil:** Comprueba que las cantidades registradas en el sistema coincidan con las existencias físicas del almacén.
- **Objetivo principal:** mantener un inventario fiable y detectar diferencias entre los datos registrados y la realidad.
- **Funciones principales:**
  - Consultar las existencias por producto y ubicación.
  - Realizar recuentos físicos y cíclicos.
  - Registrar diferencias encontradas.
  - Revisar el historial de movimientos.
  - Proponer o ejecutar ajustes autorizados.
- **Necesidades tecnológicas:** consultas precisas, historial de operaciones, herramientas de recuento y registro de diferencias.
- **Funcionalidades del SGA:** inventario, recuentos, consulta de movimientos y gestión de ajustes.
- **Permisos:** consultar el stock y registrar recuentos; los ajustes definitivos pueden requerir autorización del responsable de almacén.


### 4.6. Ficha de usuario 6: **Operario de expedición y preparación final**
**Descripción del perfil:** Verifica los productos preparados, los acondiciona para su envío y registra la salida de las mercancías.
- **Objetivo principal:** garantizar que los pedidos expedidos coincidan con lo solicitado y queden registrados correctamente.
- **Funciones principales:**
  - Consultar los pedidos pendientes de expedición.
  - Verificar los productos y las cantidades.
  - Registrar el embalaje y el etiquetado, si forman parte del sistema.
  - Confirmar la salida de los pedidos.
  - Comunicar errores o incidencias antes del envío.
- **Necesidades tecnológicas:** consulta de pedidos, validación de productos, generación de etiquetas cuando corresponda y registro de expediciones.
- **Funcionalidades del SGA:** expedición, consulta de pedidos, validación y trazabilidad de las salidas.
- **Permisos:** gestionar las expediciones asignadas y confirmar salidas, sin modificar la configuración del sistema.


## 5. Necesidades de los usuarios y requisitos de la aplicación
La identificación de los perfiles permite transformar las necesidades laborales en funcionalidades concretas del SGA.

 | Necesidad del usuario | Requisito que debe cubrir la aplicación | 
 |---|---|
 | Conocer las existencias disponibles | Consultar el stock actualizado por producto y ubicación | 
 | Registrar entradas y salidas | Disponer de formularios para confirmar los movimientos | 
 | Localizar rápidamente los productos | Permitir búsquedas por referencia, nombre o código  | 
 | Evitar errores en la preparación | Validar los productos y las cantidades de cada pedido | 
 | Conocer el historial de un producto | Consultar sus movimientos y datos de trazabilidad | 
 | Acceder solo a las funciones autorizadas | Implementar autenticación y control de permisos por rol | 
 | Detectar diferencias de inventario | Registrar recuentos, incidencias y ajustes autorizados | 
 | Supervisar el funcionamiento del almacén | Generar informes sobre existencias, movimientos y pedidos | 
 | Trabajar desde distintos dispositivos | Diseñar una interfaz adaptable a ordenadores y móviles | 

Estas necesidades se derivan de los procesos habituales de identificación, almacenamiento, preparación, expedición y trazabilidad de mercancías [4], [5], así como de la separación de responsabilidades y permisos presente en las aplicaciones SGA [6].


## 6. Referencias
[1] M. Hernández, «Qué es la digitalización y cuáles son sus ventajas», Telefónica. Accedido: 21 de octubre de 2026. [En línea]. Disponible en: https://www.telefonica.com/es/sala-comunicacion/blog/digitalizacion-que-es/
[2] «Digitalización logística 2026: tendencias», Synex Logistics. Accedido: 20 de octubre de 2026. [En línea]. Disponible en: https://synexlogistics.com/es/articulos/tendencias-de-la-digitalizacion-logistica-en-2026/
[3] «Tendencias logísticas 2026: Tecnologías, IA, oportunidades.», Blog Across Logistics. Accedido: 26 de octubre de 2026. [En línea]. Disponible en: https://acrosslogistics.com/blog/tendencias-logisticas/
[4] «El Sistema GS1», GS1 Spain. Accedido: 27 de octubre de 2026. [En línea]. Disponible en: https://www.gs1es.org/estandares-gs1-identificar-capturar-compartir/
[5] «GS1 Global Traceability Standard | GS1». Accedido: 27 de octubre de 2026. [En línea]. Disponible en: https://www.gs1.org/standards/gs1-global-traceability-standard/#2-Traceability-and-the-importance-of-standards
[6] «NetSuite Applications Online Help», Oracle Help Center. Accedido: 27 de octubre de 2026. [En línea]. Disponible en: https://docs.oracle.com/en/cloud/saas/netsuite/ns-online-help/section_156520480478.html

## 2. Análisis de la necesidad

## 1. Proceso actual
La gestión de un almacén comprende diferentes actividades relacionadas con la recepción, comprobación, almacenamiento, organización, control de inventario, preparación de pedidos y expedición de mercancías. Todas estas operaciones deben estar coordinadas para garantizar que los productos estén disponibles cuando sean necesarios [1], [2].

A continuación, se describen las principales fases del proceso de almacenamiento.


### 1.1. Recepción de mercancías
La recepción es la primera fase del proceso y comienza cuando los productos llegan al almacén procedentes de los proveedores. En esta etapa, los trabajadores descargan la mercancía y comprueban que las cantidades y características de los productos coincidan con la documentación del envío. También se realiza una inspección para detectar posibles daños o defectos en los artículos recibidos. Una vez comprobada la mercancía, se registran las entradas en el inventario y se prepara el traslado de los productos hacia las zonas de almacenamiento correspondientes [1], [2].


### 1.2. Almacenamiento y ubicación de productos
Una vez recibidos y comprobados los productos, se trasladan a las zonas de almacenamiento. En esta fase se determina dónde colocar cada artículo, teniendo en cuenta factores como el espacio disponible, las características de la mercancía y la facilidad para acceder a ella posteriormente. En los almacenes tradicionales, los productos pueden organizarse mediante estanterías fijas y la intervención directa de los trabajadores, que se encargan de colocar y recuperar los artículos cuando sea necesario. La correcta distribución de los productos permite aprovechar mejor el espacio disponible y reducir los tiempos empleados en localizar y recuperar mercancías [1], [2].


### 1.3. Control de inventario
El control de inventario consiste en registrar y supervisar las cantidades de productos disponibles en el almacén, así como sus respectivas ubicaciones. Para mantener esta información actualizada, es necesario registrar las entradas, salidas y movimientos internos de mercancías. En una gestión tradicional, este control puede realizarse mediante documentos, hojas de cálculo o registros informáticos básicos, que requieren introducir y actualizar los datos después de cada operación. La información del inventario permite conocer la disponibilidad de los productos, planificar las necesidades de reposición y evitar situaciones de exceso o falta de existencias [1], [2].


### 1.4. Preparación de pedidos (Picking)
La preparación de pedidos consiste en seleccionar y recoger los productos necesarios para satisfacer una solicitud de un cliente. Para realizar esta actividad, los trabajadores consultan los artículos y las cantidades solicitadas, localizan sus ubicaciones y los trasladan a la zona de preparación [1], [2]. Existen diferentes métodos de preparación de pedidos, entre ellos el picking manual, el semiautomático y el automático. En el método manual, el trabajador debe desplazarse hasta las ubicaciones de los productos, recogerlos y llevarlos a la zona correspondiente [2]. Una vez recogidos los artículos, se comprueba que las cantidades y referencias sean correctas antes de continuar con el embalaje y la expedición [1], [2].


### 1.5. Embalaje y etiquetado (Packing)
Después de preparar el pedido, los productos pasan al proceso de embalaje, donde se seleccionan los materiales adecuados para protegerlos durante el transporte. Posteriormente, se colocan las etiquetas correspondientes, que pueden incluir información como el destino, el número de pedido y los códigos de barras necesarios para facilitar su identificación y seguimiento [1].


### 1.6. Envío de mercancías
El envío es la última fase del proceso de almacenamiento y consiste en preparar los pedidos para su salida del almacén y posterior entrega al cliente. En esta etapa se verifica que los productos preparados coincidan con el pedido, se finaliza el embalaje y se organiza la mercancía para su envío. Además, se registra la salida de los productos para mantener actualizado el inventario [1], [2].


## 2. Identificación de problemas y consecuencias
La gestión de un almacén requiere coordinar correctamente las operaciones y mantener actualizada la información de los productos. Cuando los procesos dependen excesivamente de tareas manuales o no existe una herramienta centralizada, pueden aparecer ineficiencias que afectan al funcionamiento general del almacén [1], [2], [3].

A partir de los procesos anteriores, hemos identificado los siguientes problemas potenciales:


### 2.1. Errores en el registro de entradas y salidas
Cuando los trabajadores deben introducir manualmente los datos de las mercancías recibidas o entregadas, existe la posibilidad de cometer errores al registrar las referencias o las cantidades de los productos. Estos errores pueden provocar diferencias entre las existencias físicas y las reflejadas en los registros [1], [2].

**Consecuencias:**
- Información incorrecta sobre las cantidades disponibles [1], [2].
- Dificultades para controlar las entradas y salidas de mercancías [1], [2].
- Riesgo de preparar pedidos con cantidades incorrectas o productos que no están disponibles [2], [3].


### 2.2. Dificultad para localizar productos
Cuando las ubicaciones de los artículos no están correctamente organizadas o registradas, los trabajadores pueden necesitar realizar búsquedas adicionales para encontrar los productos solicitados. La organización de las ubicaciones es importante para reducir los tiempos de búsqueda y facilitar las operaciones de recuperación de mercancías [1], [2].

**Consecuencias:**
- Aumento del tiempo empleado en localizar productos [1], [2].
- Desplazamientos innecesarios dentro del almacén [2], [3].
- Retrasos en la preparación y finalización de pedidos [1], [2].


### 2.3. Falta de actualización del inventario
Si los movimientos de mercancías no se registran correctamente después de cada operación, la información del inventario puede dejar de coincidir con las existencias reales. La visibilidad actualizada de las cantidades y ubicaciones resulta fundamental para evitar excedentes o productos faltantes [1], [2].

**Consecuencias:**
- Dificultad para conocer las existencias reales [1], [2].
- Riesgo de roturas de stock [2].
- Posibilidad de acumular productos innecesarios [1], [2].
- Problemas para planificar las reposiciones [2].


### 2.4. Preparación de pedidos poco eficiente
La preparación manual de pedidos requiere que los trabajadores localicen los productos, recorran las diferentes zonas del almacén y comprueben que las referencias y cantidades sean correctas. Una organización inadecuada de estas actividades puede incrementar los desplazamientos y el tiempo necesario para completar los pedidos [2], [4].

**Consecuencias:**
- Mayor tiempo de preparación de pedidos [2], [4].
- Incremento de los desplazamientos de los trabajadores [2], [4].
- Posibilidad de seleccionar productos equivocados [1], [4].
- Menor capacidad para preparar pedidos en un periodo determinado [4].


### 2.5. Falta de trazabilidad de los productos
La trazabilidad permite conocer los movimientos y cambios que experimentan los productos durante su estancia en el almacén. Cuando la información de las operaciones no se registra de forma organizada, resulta más difícil consultar el recorrido de las mercancías y localizar el origen de determinadas incidencias [1], [3].

**Consecuencias:**
- Dificultad para conocer dónde se encuentran determinados productos [1], [3].
- Mayor complejidad para investigar errores o incidencias [1], [3].
- Dificultad para consultar el historial de movimientos de las mercancías [3].


### 2.6. Falta de información centralizada
Cuando los datos del almacén se encuentran repartidos entre diferentes documentos o herramientas, puede resultar complicado consultar toda la información necesaria desde un único lugar. La utilización de sistemas de gestión permite centralizar la información y facilitar la coordinación de las operaciones logísticas [1], [3].

**Consecuencias:**
- Duplicidad de información [1], [3].
- Mayor dificultad para consultar los datos [1], [3].
- Problemas para coordinar las tareas de los trabajadores [1], [3].
- Dificultad para tomar decisiones basadas en información actualizada [1], [3].


## 3. Explicación de soluciones ante las carencias identificadas anteriormente
Para solucionar los problemas detectados, se propone desarrollar una aplicación SGA, el cual permite gestionar de forma digital y centralizada las principales operaciones del almacén. Este tipo de sistemas se utilizan para facilita el control de las mercancías, el seguimiento de los movimientos, la gestión de ubicaciones y la preparación de pedidos [1], [2], [3].

Las funcionalidades que suelen incorporar los SGA son las siguientes:


### 3.1. Registro de entradas y salidas de mercancías
La aplicación permite registrar las entradas de productos cuando se reciban mercancías de los proveedores, almacenando información como el código del producto, su nombre, la cantidad recibida y la fecha de entrada. También permitirá registrar las salidas de productos cuando se preparen y envíen pedidos, actualizando las existencias disponibles después de cada operación [2], [3].

**¿Qué soluciona?:** 
Se reduce la dependencia de los registros manuales y se facilita el control de las operaciones de entrada y salida de mercancías [2], [3].


### 3.2. Gestión centralizada del inventario
El sistema dispone de una base de datos centralizada donde se almacena la información de los productos y sus existencias. Los usuarios pueden consultar las cantidades disponibles y acceder a la información de los artículos registrados. Además, cada movimiento que afecta al inventario actualiza las cantidades correspondientes, permitiendo mantener un control más preciso de las existencias [2], [3].

**¿Qué soluciona?:** 
Se facilita la consulta del inventario y se reduce el riesgo de trabajar con información desactualizada sobre las cantidades disponibles [2], [3].


### 3.3. Gestión de ubicaciones del almacén
La aplicación permite registrar las diferentes ubicaciones físicas del almacén, como pasillos, estanterías, niveles y zonas de almacenamiento. Cada producto está asociado a una ubicación para facilitar su localización. De esta manera, cuando un trabajador necesita buscar un artículo, puede consultar directamente en la aplicación dónde se encuentra almacenado [2], [3].

**¿Qué soluciona?:** 
Se reducen los tiempos de búsqueda y los desplazamientos innecesarios, mejorando la organización interna del almacén [1], [2].


### 3.4. Gestión y preparación de pedidos
El SGA permite registrar los pedidos y consultar los productos y cantidades que deben prepararse. Los trabajadores pueden visualizar los artículos solicitados y sus respectivas ubicaciones para realizar las operaciones de recogida. También se puede incorporar un sistema de seguimiento del estado de los pedidos, diferenciando entre pedidos pendientes, en preparación, preparados y expedidos [2], [3].

**¿Qué soluciona?:** 
Se facilita la organización del trabajo y se reduce el tiempo dedicado a buscar información sobre los productos que forman parte de cada pedido [2], [4].


### 3.5. Control de movimientos y trazabilidad
La aplicación registra los movimientos realizados sobre los productos, incluyendo entradas, salidas y traslados entre diferentes ubicaciones del almacén. Cada movimiento queda asociado a la información correspondiente para poder consultar el historial de operaciones de un producto y conocer los cambios que se han producido durante su almacenamiento [2], [3].

También cabe la posibilidad de incorporar campos para gestionar lotes y números de serie, mejorando el seguimiento de determinados artículos [3].

**¿Qué soluciona?:**
Se facilita el seguimiento de las mercancías y la consulta de su historial de movimientos, mejorando la disponibilidad de información ante posibles incidencias [2], [3].


### 3.6. Consulta de información e informes
La aplicación permite consultar información relacionada con los productos, las cantidades disponibles, las ubicaciones y los pedidos registrados [2], [3].

También se podría incorporar informes que permitan visualizar el estado del inventario y consultar información sobre las operaciones realizadas en el almacén [1], [3].

**¿Qué soluciona?:**
Se facilita el acceso a la información y se mejora la capacidad de supervisar y organizar las operaciones del almacén [1], [3].


## 4. Justificación de la necesidad de desarrollar la aplicación
El desarrollo de la aplicación SGA está justificado por la necesidad de mejorar la organización y el control de las operaciones que se realizan dentro de un almacén. La recepción, el almacenamiento, el control de inventario y la preparación de pedidos son actividades que deben coordinarse correctamente para garantizar un funcionamiento eficiente de la cadena de suministro [1], [2]. 

Los problemas identificados, como los errores en el registro de mercancías, las dificultades para localizar productos, la falta de actualización del inventario y los desplazamientos innecesarios durante la preparación de pedidos, pueden afectar a los tiempos de trabajo y a la calidad del servicio logístico [1], [2], [4]. La incorporación de un SGA permitirá digitalizar estos procesos y disponer de una herramienta que centralice la información y facilite el trabajo de los empleados. Además, el uso de sistemas con integración herramientas tecnológicas, ordenadores y programas software (sistemas informatizados), permite mejorar la visibilidad del inventario, organizar las ubicaciones y gestionar las operaciones de preparación y envío [2], [3].

La importancia de mejorar estos procesos también se refleja en investigaciones científicas sobre la optimización de almacenes. Daiki Ueno y Enna Hirata estudiaron diferentes métodos para optimizar las rutas de preparación de pedidos, teniendo en cuenta situaciones reales como los cambios inesperados en los pedidos y los bloqueos de pasillos. Los resultados de su investigación muestran que la optimización de las rutas permitió reducir las distancias recorridas hasta un 20% en un escenario general y hasta un 31% cuando se producían cambios en los pedidos [4]. Estos resultados demuestran el potencial de las herramientas informáticas para mejorar la organización de las operaciones de preparación de pedidos, aunque no representan una mejora garantizada para cualquier almacén.

Por tanto, invertir tiempo y recursos en desarrollar esta aplicación permitirá disponer de una solución informática orientada a mejorar el control de las mercancías, reducir las ineficiencias operativas y facilitar la gestión de las actividades logísticas [1], [2], [3], [4].


## 5. Conclusión
Tras analizar las diferentes fases del proceso de almacenamiento, se identifica la importancia de disponer de una herramienta que permita controlar de manera organizada las mercancías desde su recepción hasta su expedición [1], [2].

Las principales necesidades detectadas están relacionadas con el control de inventario, la gestión de ubicaciones, la preparación de pedidos, el registro de movimientos y la centralización de la información [1], [2], [3].

La aplicación SGA pretende solucionar estas carencias mediante la digitalización de las operaciones del almacén, permitiendo consultar información de los productos, controlar sus existencias, conocer sus ubicaciones y realizar un seguimiento de los pedidos y movimientos registrados [2], [3].

En definitiva, el desarrollo de esta aplicación está justificado porque permitirá establecer una gestión del almacén más organizada, mejorar la disponibilidad de la información y facilitar el trabajo de los usuarios, contribuyendo a optimizar los procesos logísticos [1], [2], [3].


## 6. Referencias
[1] A. Arango, «Logística de almacén: qué es, procesos e importancia para la cadena de suministro», Logístiko. Accedido: 28 de octubre de 2026. [En línea]. Disponible en: https://logistiko.es/blog/logistica-de-almacen-que-es-procesos-e-importancia-para-la-cadena-de-suministro/
[2] «Proceso de Almacenamiento: Guía Completa para Empresa». Accedido: 28 de octubre de 2026. [En línea]. Disponible en: https://eplogistics.com/es/blog/proceso-de-almacenamiento/
[3] «What is a WMS? - Warehouse Management System Explained - AWS», Amazon Web Services, Inc. Accedido: 1 de noviembre de 2026. [En línea]. Disponible en: https://aws.amazon.com/what-is/wms/
[4] D. Ueno y E. Hirata, «The Optimization of Picking in Logistics Warehouses in the Event of Sudden Picking Order Changes and Picking Route Blockages», Mathematics, vol. 12, n.º 16, p. 2580, ago. 2024, doi: [10.3390/math12162580](https://doi.org/10.3390/math12162580).

## 3. Estudio de soluciones existentes

### 1. Objetivo y metodología

Se realizó un análisis comparativo de mercado (benchmarking) para identificar qué alternativas existen para el control de stock en un almacén, qué aportan y qué limitaciones presentan, y justificar así el valor diferencial de StockScan SGA.

Se seleccionaron cuatro alternativas reales que cubren distintos tipos de solución: un ERP con versión comunitaria y de pago, una solución comercial en la nube, otra solución comercial orientada a pymes y una de código abierto. Los datos se recogieron de las páginas oficiales de cada producto el 20 de octubre de 2026, por lo que los precios y las condiciones pueden haber cambiado desde entonces. Los parámetros que no figuran en las fuentes oficiales se marcan como "no consta" o "no verificado", y los que dependen de la experiencia de uso se presentan como valoración del equipo.

La elección parte del formulario de validación realizado a 30 personas: 17 de ellas utilizan Excel o no llevan ningún control formal del stock, y solo 7 emplean un programa de gestión (ERP o SGA). Por ello se compararon herramientas accesibles para pymes y no solo grandes sistemas.

### 2. Alternativas seleccionadas

| Alternativa | Tipo | Motivo de la elección |
|---|---|---|
| Odoo | ERP, con versión de pago y comunitaria | Referencia entre los ERP con módulo de inventario |
| Zoho Inventory | Comercial, en la nube | Dispone de plan gratuito y de aplicaciones móviles |
| inFlow Inventory | Comercial, orientado a pymes | Se centra en el inventario y el escaneo de códigos |
| ERPNext | Código abierto (GPL-3.0) | Alternativa gratuita y autoalojable al software comercial |

### 3. Análisis comparativo

**Odoo.** Ofrece un plan gratuito de una sola aplicación, aunque Inventario no figura entre las gratuitas. El plan Standard cuesta desde 24,90 USD por usuario al mes y el Custom desde 49 USD, con facturación anual [1]. Se ofrece en la nube y solo el plan Custom permite instalarlo en un servidor propio [1]. Al ser un ERP, su extensibilidad es alta. Entre sus limitaciones, el escaneo con la aplicación de códigos de barras requiere configurar varios ajustes (nomenclatura y base de datos de productos), y los códigos deben asignarse a cada variante del producto y no a la plantilla [2].

**Zoho Inventory.** Dispone de un plan gratuito limitado a 1 usuario, 1 ubicación y 50 pedidos al mes. Los planes de pago cuestan entre 29 y 249 USD al mes por organización, con facturación anual [3]. Ofrece aplicaciones para iOS, Android y Windows, generación y escaneo de códigos de barras, informes y análisis, e integraciones con tiendas en línea, contabilidad y transporte [4]. Cada plan limita el número de pedidos, usuarios y ubicaciones, y ampliarlos supone un coste adicional [3]. Su web no menciona el funcionamiento sin conexión [4].

**inFlow Inventory.** Ofrece una prueba gratuita de 14 días sin tarjeta [5]. Los planes van de 29 a 249 USD al mes según el precio mostrado, que la página no etiqueta como mensual o anual, y limitan los usuarios y los pedidos de venta por año, con un recargo por cada pedido adicional [6]. Funciona en Android e iOS, y genera y escanea códigos de barras, aunque el escáner es opcional y se adquiere por separado [5][6]. Su web no menciona el funcionamiento sin conexión [5].

**ERPNext.** Es gratuito y de código abierto (GPL-3.0). Alojado en Frappe Cloud cuesta desde 5 USD al mes, y la implantación se realiza con la documentación propia o con partners de pago [7]. Su extensibilidad es alta, ya que el código es público y la web indica que no hay funciones de pago ocultas [7]. Su principal limitación es que la implantación y la personalización requieren conocimientos técnicos o la contratación de un partner [7].

### 4. Matriz comparativa

| Parámetro | Odoo | Zoho Inventory | inFlow | ERPNext | StockScan SGA |
|---|---|---|---|---|---|
| Licencia | De pago (y comunitaria) | Comercial | Comercial | Código abierto (GPL-3.0) | Proyecto académico |
| Precio de entrada | Desde 24,90 USD/usuario/mes | Gratis; de pago desde 29 USD/mes | Desde 29 USD/mes (prueba de 14 días) | Gratis (alojamiento propio) | Por definir |
| Plan gratuito | Sí, de una app (sin Inventario) | Sí | No (solo prueba) | Sí (software) | No aplica |
| Plataformas | Nube; servidor propio solo en Custom | iOS, Android, Windows | Android, iOS | No verificado | Por definir |
| Escaneo de códigos | Sí, con configuración | Sí | Sí (escáner opcional) | No verificado | Objetivo del proyecto |
| Funcionamiento sin internet | No verificado | No consta | No consta | No verificado | Por decidir |
| Informes | No verificado | Sí | Sí | No verificado | Por desarrollar |
| Extensibilidad | Alta | Integraciones | Integraciones limitadas por plan | Alta (código abierto) | Modular (MVC) |
| Curva de aprendizaje (valoración del equipo) | Alta (ERP completo) | Media | Media | Alta (requiere implantación) | Baja (objetivo) |
| Usabilidad de la interfaz | Por evaluar | Por evaluar | Por evaluar | Por evaluar | Objetivo principal |
| Limitaciones | Configuración del escaneo | Límites de pedidos y usuarios | Límite de pedidos por plan | Implantación técnica | Prototipo |

### 5. Hallazgos

- Las tres soluciones comerciales limitan el uso según el plan (pedidos, usuarios o ubicaciones) y se cobran en dólares y por mes [3][6]. En el formulario, 20 de los 30 encuestados pagarían como máximo 100 €, si bien la pregunta no especificaba el periodo.
- Ninguna de las webs oficiales consultadas que describen el producto menciona el funcionamiento sin internet [4][5]. En el formulario, 12 de 30 personas lo eligieron entre sus tres prioridades.
- Los ERP (Odoo y ERPNext) son completos, pero más complejos de implantar [2][7]. Las prioridades de los encuestados son la rapidez (24 de 30), la precisión (26 de 30) y la facilidad de uso (19 de 30).
- 20 de los 30 encuestados prefieren disponer de chat, agenda y stock en una sola aplicación.

### 6. Justificación de la propuesta

Las alternativas analizadas son sistemas de propósito general: ERP completos, como Odoo o ERPNext, que exigen configuración o implantación, y herramientas comerciales, como Zoho Inventory o inFlow, que limitan el uso por plan y se pagan por suscripción. StockScan SGA no pretende competir con ellas en número de funciones, sino en la experiencia de uso diaria del operario. A partir de lo que pidieron los encuestados (precisión, rapidez y facilidad de uso), el prototipo se centra en el diseño de la interfaz: un sistema de colores con significado (verde, rojo y ámbar) que permite ver el estado de cada operación de un vistazo, flujos de escaneo cortos y validación en tiempo real. Se plantea como una propuesta modular, pensada para una pyme que hoy trabaja con hojas de cálculo o sin control formal. Queda por decidir si funcionará sin conexión, un requisito que las alternativas no declaran y que sí valoran muchos de los encuestados.

### Referencias

[1] Odoo S.A., "Pricing," Odoo. [Online]. Available: https://www.odoo.com/pricing (accessed Oct. 20, 2026).

[2] Odoo S.A., "Barcode: Software setup," Odoo Documentation 19.0. [Online]. Available: https://www.odoo.com/documentation/19.0/applications/inventory_and_mrp/barcode/setup/software.html (accessed Oct. 20, 2026).

[3] Zoho Corporation, "Zoho Inventory pricing," Zoho. [Online]. Available: https://www.zoho.com/inventory/pricing/ (accessed Oct. 20, 2026).

[4] Zoho Corporation, "Zoho Inventory," Zoho. [Online]. Available: https://www.zoho.com/inventory/ (accessed Oct. 20, 2026).

[5] inFlow Inventory, "inFlow Inventory," inFlow. [Online]. Available: https://www.inflowinventory.com/ (accessed Oct. 20, 2026).

[6] inFlow Inventory, "Software pricing," inFlow Partners. [Online]. Available: https://partnerstack.inflowinventory.com/software-pricing (accessed Oct. 20, 2026).

[7] Frappe Technologies, "ERPNext pricing," Frappe. [Online]. Available: https://frappe.io/erpnext/pricing (accessed Oct. 20, 2026).

## 4. Partes interesadas (Stakeholders)

### 1. Objetivo y metodología
 
Se identificaron las personas, colectivos y entidades que tienen interés en StockScan SGA o que se verán afectados por su implantación, con el fin de recoger sus expectativas, priorizar el backlog y decidir cómo comunicarse con cada grupo.
 
Los grupos se identificaron a partir del contexto del proyecto y de los resultados del formulario de validación realizado a 30 personas, y se clasificaron en internos y externos según su relación con el sistema [2]. Después se valoró el nivel de influencia (alto, medio o bajo) y de interés (alto, medio o bajo) de cada grupo y se ubicaron en una matriz de poder e interés, que asigna una estrategia de comunicación a cada cuadrante [1]. Los niveles de influencia e interés son una valoración del equipo, no una medición, y pueden revisarse en sprints posteriores.
 
### 2. Partes interesadas identificadas[2]
 
| Grupo | Tipo | Papel en el proyecto |
|---|---|---|
| Equipo de desarrollo (Carmen Monge, Álvaro López, Ángel Luis Sánchez y Elena Sáez) | Interno | Diseña, programa y documenta el sistema |
| Tutores / profesorado | Interno | Evalúa el proyecto intermodular y los entregables de cada sprint |
| Dirección / propietario del almacén | Interno | Decide si se adopta la herramienta y financia su implantación |
| Supervisor de almacén | Interno | Define las reglas de ubicación, asigna tareas y turnos, y revisa alertas e historial |
| Administrador del sistema | Interno | Gestiona usuarios, roles y el panel de gestión |
| Operarios de almacén | Interno | Usuarios diarios de la app móvil (escaneo, entradas, salidas, traspasos, chat y agenda) |
| Pymes y negocios con gestión de stock | Externo | Clientes potenciales; los 30 encuestados representan este grupo |
| Proveedores de mercancía | Externo | Sus entregas generan las entradas de stock y los tickets que se importan |
| Agencias de transporte | Externo | Quedan fuera del alcance, pero reciben o entregan mercancía que el sistema registra |
| AEPD y marco RGPD / LOPDGDD | Externo | Regulan el tratamiento de los datos de usuarios y operarios |
| Auditores / calidad | Externo | Pueden necesitar la trazabilidad de los movimientos |
| Plataformas tecnológicas (Google, Apple, Flutter, GitHub) | Externo | Condicionan la distribución y las herramientas |
| Competidores (Sortly, Stockagile, When I Work, Slack/Teams) | Externo | No participan en el proyecto, pero marcan el estándar del mercado |
 
### 3. Análisis de poder e interés[2]
 
| Grupo | Influencia | Interés | Expectativas principales | Estrategia de comunicación |
|---|---|---|---|---|
| Tutores / profesorado | Alta | Alto | Cumplimiento de la rúbrica, trazabilidad por miembro, entregas en GitHub | Sprint Review al cierre de cada sprint y consulta de dudas en tutoría |
| Equipo de desarrollo | Alta | Alto | Reparto equilibrado, alcance realista, buena nota | Daily breve, GitHub Project y chat del grupo |
| Dirección / propietario | Alta | Alto | Menos roturas de stock, ahorro de tiempo en inventario, coste asumible | Demo del prototipo |
| Supervisor | Media | Alto | Control de ubicaciones, alertas fiables, historial para auditar | Sesiones de validación del prototipo |
| Administrador | Media | Alto | Gestión sencilla de usuarios y roles, panel claro | Reunión de requisitos y pruebas del panel |
| Operarios | Media | Alto | Rapidez, pocos clics, menos errores, uso con una mano o con guantes | Pruebas de usabilidad con el prototipo de Figma y encuesta breve |
| Pymes / clientes potenciales | Media | Medio | Alternativa sencilla al Excel o al papel, bajo coste | Resultados de la encuesta y difusión de la demo |
| Proveedores de mercancía | Baja | Medio | Entradas registradas correctamente | Informar del formato de tickets si afecta a las entregas |
| Agencias de transporte | Baja | Bajo | Registro claro de recepciones | Sin canal directo; se informa vía Dirección |
| AEPD / normativa | Alta | Bajo | Cumplimiento de RGPD y LOPDGDD | Privacy by Design, documentado en la sección 7 |
| Auditores / calidad | Media | Bajo | Trazabilidad e historial fiables | Exportación del historial de movimientos |
| Plataformas tecnológicas | Media | Bajo | Cumplimiento de sus políticas de distribución | Revisar sus condiciones al preparar el despliegue |
| Competidores | Baja | Bajo | No aplica | Seguimiento mediante el benchmarking |
 
| | **Interés bajo** | **Interés alto** |
|---|---|---|
| **Poder alto** | *Mantener satisfechos:* AEPD / normativa | *Gestionar de cerca:* tutores, equipo de desarrollo, dirección |
| **Poder bajo o medio** | *Monitorizar:* proveedores, transporte, competidores, plataformas, auditores | *Mantener informados:* supervisor, administrador, operarios, pymes |
 
### 4. Hallazgos
 
1. Los grupos con más poder y más interés son los tutores, el equipo y la dirección. Los dos primeros condicionan los entregables y el calendario, y la dirección decide la adopción de la herramienta, por lo que sus expectativas (menos roturas de stock y ahorro de tiempo) orientan la propuesta de valor.
2. Los operarios tienen influencia media, pero son los usuarios diarios y su aceptación depende de la facilidad de uso. En el formulario, 26 de los 30 encuestados señalaron la precisión como prioridad, 24 la rapidez y 19 la facilidad de uso.
3. Las pymes y los negocios con gestión de stock son el mercado potencial. En el formulario, 19 de los 30 encuestados (63 %) controlan el stock con Excel, papel o sin control formal, y los problemas más repetidos fueron las roturas de stock (13 de 30) y los errores al contar o apuntar (11 de 30).
4. Los supervisores, administradores y operarios comparten la expectativa de reunir las funciones en una sola herramienta: 20 de los 30 encuestados prefieren disponer de chat, agenda y stock en una sola aplicación.
5. La normativa de protección de datos tiene una influencia alta aunque su interés directo en el proyecto sea bajo, ya que el sistema registra datos de los operarios (acceso, turnos, fichajes, mensajes y movimientos realizados). Su análisis se desarrolla en la sección 7.
### 5. Conclusiones
 
1. Los grupos que más condicionan el proyecto son los tutores, la dirección y el propio equipo, por lo que se priorizan los entregables evaluables y el ahorro operativo demostrable.
2. Los operarios tienen poder medio pero son los usuarios diarios: su aceptación depende de una interfaz rápida y clara, lo que justifica el flujo Escanear > Confirmar > Actualizar.
3. La normativa de protección de datos tiene influencia alta aunque el interés directo sea bajo, y se desarrolla en la sección 7.
### Referencias
 
[1] Universidad Autónoma del Estado de Hidalgo, "Qué son los stakeholders y métodos para su análisis,": https://www.uaeh.edu.mx/divulgacion-ciencia/stakeholders-metodos/
 
[2] ProjectManager, "Gestión de los interesados de un proyecto: guía rápida,": 
https://www.projectmanager.com/es/gestion-de-interesados-de-un-proyecto
 

## 5. Estudio de viabilidad técnica

## 1. Objetivo y metodología

El objetivo de este estudio es determinar si el equipo, las herramientas y la infraestructura disponibles permiten desarrollar, integrar, probar y desplegar **StockScan SGA**, una aplicación de gestión de almacén. El análisis se centra en cuatro aspectos: la pila tecnológica y su justificación, los requisitos de hardware y despliegue, los conocimientos previos del equipo y la madurez y licencia de las tecnologías seleccionadas.

Las versiones de Java, Flutter y Dart se mantienen fijadas por los requisitos del proyecto: **Java 21, Flutter 3.35.2 y Dart 3.9.0**. Las versiones de las demás dependencias deben comprobarse en sus fuentes oficiales y validarse con el proyecto antes de actualizarlas.

## 2. Pila tecnológica

| Capa | Tecnología y versión | Función en StockScan SGA |
|---|---|---|
| Interfaz móvil | Flutter 3.35.2 y Dart 3.9.0 [1][2] | Aplicación para operarios: inicio de sesión, consulta de stock, escaneo, entradas, salidas, traspasos, chat y agenda. |
| Escaneo | `mobile_scanner` 7.4.2 [3] | Lectura de códigos de barras y códigos QR mediante la cámara del dispositivo. |
| Lógica de negocio y servidor | Java 21 LTS, Eclipse Temurin [4] | Validación de movimientos, control de permisos y roles, alertas de stock bajo, autenticación e importación de tickets. |
| Persistencia | SQLite 3.53.4, mediante `org.xerial:sqlite-jdbc` 3.53.4.0 [5] | Almacenamiento de productos, ubicaciones, historial de movimientos, usuarios, mensajes, turnos y tareas. |
| Panel de gestión | Java Swing y FlatLaf 3.7.2 [6] | Aplicación de escritorio para el dashboard, el historial, la gestión de usuarios y las alertas. |
| Pruebas | JUnit 6.2.0 y `flutter_test` [7] | Pruebas automatizadas de la lógica Java y de la aplicación Flutter. |
| Diseño y organización | Figma, Git y GitHub Projects | Diseño del sistema visual, prototipos, control de versiones, documentación y planificación del trabajo. |

**Arquitectura prevista.** Los clientes no deben acceder directamente a la base de datos. La aplicación móvil y el panel de gestión se comunicarán con la capa Java, que validará las operaciones, aplicará los permisos por rol y registrará los movimientos. De esta forma, las reglas de negocio y los controles se centralizan. **Queda por concretar y documentar el mecanismo de comunicación entre los clientes y el servidor**, por ejemplo, mediante una API REST sobre HTTPS. La arquitectura definitiva deberá especificar también cómo se gestionan las sesiones, los errores, las transacciones y las conexiones concurrentes.

### Justificación de las elecciones

1. **Flutter y Dart.** Permiten mantener una base de código para Android e iOS y ofrecen herramientas para construir interfaces coherentes. El paquete `mobile_scanner` cubre la lectura de códigos mediante la cámara en las plataformas que declara compatibles. La interfaz se diseñará con contraste suficiente, botones claros y mensajes de confirmación comprensibles.
2. **Java 21.** Se ajusta a los conocimientos del equipo y permite organizar el servidor mediante una arquitectura MVC/DAO y acceder a SQLite con JDBC. Java 21 es una versión LTS; se mantiene por la restricción del proyecto.
3. **SQLite.** Es una base de datos integrada que no requiere administrar un servidor de base de datos independiente, y su software se encuentra en el dominio público. Resulta apropiada para un prototipo y una carga moderada, siempre que se controle el acceso concurrente y se realicen copias de seguridad.
4. **Java Swing y FlatLaf.** Swing se ha trabajado en el módulo de Desarrollo de Interfaces y forma parte de la plataforma Java. FlatLaf proporciona temas y opciones de personalización visual. La accesibilidad no queda garantizada solo por usar el tema: se deberán comprobar el contraste, los tamaños, el foco por teclado y la legibilidad de cada pantalla.

### Alternativas consideradas

| Decisión | Alternativa | Motivo para no seleccionarla en este proyecto |
|---|---|---|
| Interfaz móvil | React Native | El prototipo ya está planteado con Flutter y cambiar de tecnología añadiría aprendizaje y trabajo de adaptación. |
| Interfaz móvil | Aplicación nativa Android | Limitaría la solución a Android o exigiría desarrollar una aplicación separada para iOS. |
| Base de datos | PostgreSQL o MySQL | Incorporan un servicio de base de datos que requiere configuración y administración adicionales para el alcance del prototipo. Podrían evaluarse si las necesidades de concurrencia o despliegue lo justifican. |
| Base de datos | Firebase | Introduciría dependencia de un servicio externo y habría que revisar sus condiciones, límites y posibles costes. |
| Panel de gestión | JavaFX, Flutter Web o panel web | Swing encaja con los conocimientos y las herramientas trabajadas por el equipo. No se afirma que las alternativas sean técnicamente inferiores, sino que no son la opción prioritaria para el alcance y el tiempo disponibles. |

## 3. Requisitos de hardware y despliegue

### Equipos de desarrollo

Los cuatro miembros trabajan con el mismo modelo de equipo: **HP ProOne 440 23.8 G9 All-in-One**.

| Componente | Referencia de planificación del proyecto | Equipo disponible |
|---|---|---|
| Procesador | Intel Core i5 o AMD Ryzen 5 de una generación reciente, como referencia orientativa | Intel Core i5-12500T, 12.ª generación |
| Memoria RAM | 16 GB como objetivo recomendado para trabajar con el IDE, emulador y herramientas simultáneamente | 16 GB |
| Almacenamiento | SSD con espacio libre suficiente para los SDK, dependencias, emuladores y repositorios; se estima un margen de 40 GB para el proyecto | Aproximadamente 527 GB libres de 954 GB |
| Sistema operativo | Windows 11 de 64 bits o un sistema compatible con las herramientas utilizadas | Windows 11 de 64 bits |

La configuración disponible parece suficiente para el desarrollo previsto. La cifra de 40 GB es una **estimación interna de planificación**, no un requisito oficial de Flutter o Java. Para utilizar el emulador de Android debe comprobarse que la virtualización está habilitada en la BIOS/UEFI y configurada correctamente en Windows. Como alternativa, las pruebas de cámara y escaneo pueden realizarse en un dispositivo físico.

### Equipos cliente

| Cliente o infraestructura | Requisito previsto |
|---|---|
| Móvil Android del operario | Dispositivo con una versión de Android compatible con la versión fijada de Flutter 3.35.2 y con `mobile_scanner` 7.4.2, cámara funcional y conectividad con el servidor. La versión mínima exacta debe verificarse en la documentación correspondiente a esas versiones. |
| iPhone del operario (opcional) | Dispositivo con una versión de iOS compatible con Flutter 3.35.2 y `mobile_scanner` 7.4.2. Para compilar y firmar la aplicación para iOS se necesita un equipo macOS con Xcode. |
| Panel de gestión | Equipo de escritorio con un sistema operativo compatible con Java 21 y con las dependencias del proyecto. Para mantener un entorno homogéneo se recomienda Eclipse Temurin JDK 21 durante el desarrollo; para ejecutar la aplicación bastará un entorno de ejecución compatible si el empaquetado lo permite. |
| Servidor | Equipo que pueda ejecutar la aplicación Java y alojar el archivo de base de datos SQLite, con permisos de acceso restringidos, almacenamiento suficiente y copias de seguridad periódicas. |
| Red | Conectividad estable entre los clientes y el servidor. Si el servidor está conectado por cable y los móviles por Wi-Fi, ambas redes deben permitir la comunicación necesaria. |

Los requisitos mínimos de Android e iOS no se fijan en este documento porque deben contrastarse con las versiones exactas del SDK, el paquete de escaneo y las herramientas de compilación que utilice el proyecto. No se deben trasladar automáticamente los requisitos de versiones posteriores de Flutter a Flutter 3.35.2 [1][2][3].

### Seguridad y despliegue

El servidor deberá ofrecer comunicaciones cifradas mediante HTTPS cuando los clientes se conecten a través de la red. Las contraseñas no se almacenarán en texto plano: se utilizará un algoritmo de hash para contraseñas adecuado y configurado con sus parámetros recomendados. El acceso al archivo SQLite se limitará al proceso servidor y se definirán copias de seguridad periódicas y un procedimiento de restauración.

En el alcance académico, la aplicación móvil se instalará manualmente en dispositivos de prueba y el servidor Java se ejecutará en un equipo local o de laboratorio. La publicación en Google Play o App Store se considera un escenario posterior, cuya viabilidad económica y requisitos de distribución deberán evaluarse por separado.

## 4. Curva de aprendizaje y madurez técnica

### Conocimiento del equipo

La tabla recoge la **autovaloración declarada por los integrantes**. Los niveles son cualitativos y no constituyen una evaluación objetiva de competencia.

| Miembro | Java | Swing / FlatLaf | Flutter / Dart | SQLite / SQL | Figma | Git / GitHub |
|---|---|---|---|---|---|---|
| Carmen Monge | Medio alto | Medio alto | Medio bajo | Medio alto | Bajo | Alto |
| Álvaro López | Medio alto | Medio alto | Medio | Medio alto | Alto | Alto |
| Ángel Luis Sánchez | Medio alto | Medio bajo | Bajo | Medio bajo | Bajo | Medio bajo |
| Elena Sáez | Medio alto | Medio alto | Medio bajo | Medio alto | Medio alto | Alto |

### Madurez y licencias

| Tecnología | Madurez y uso previsto | Licencia o condiciones |
|---|---|---|
| Java 21 / OpenJDK / Eclipse Temurin | Muy alta. Plataforma consolidada, con una versión LTS seleccionada para el proyecto. | OpenJDK se distribuye bajo GPLv2 con Classpath Exception. Debe consultarse la licencia de la distribución concreta y de sus componentes. |
| Flutter 3.35.2 / Dart 3.9.0 | Alta. Tecnologías con ecosistema consolidado para el desarrollo multiplataforma. | Flutter y Dart utilizan licencias de tipo BSD de tres cláusulas; conviene consultar los ficheros de licencia de las versiones distribuidas. |
| SQLite | Muy alta. Motor ampliamente utilizado en aplicaciones móviles, de escritorio e integradas. | Dominio público. |
| Java Swing | Muy alta. Biblioteca madura de interfaces gráficas incluida en la plataforma Java. | Swing forma parte de la plataforma OpenJDK; la licencia aplicable debe entenderse dentro de la distribución OpenJDK utilizada, no como una licencia comercial independiente de Swing. |
| FlatLaf 3.7.2 | Alta. Biblioteca de apariencia visual para Swing, mantenida y orientada a modernizar interfaces Java de escritorio. | Apache License 2.0. |
| `mobile_scanner` 7.4.2 | Paquete mantenido para escanear códigos de barras y QR mediante la cámara; se deben probar las plataformas concretas que vaya a utilizar el proyecto. | BSD-3-Clause, según la ficha del paquete. |
| SQLite JDBC (`org.xerial:sqlite-jdbc` 3.53.4.0) | Driver que permite utilizar SQLite desde Java mediante JDBC. | Consultar la licencia y los avisos incluidos en el repositorio y el artefacto utilizado. |
| Figma | Herramienta de diseño colaborativo y prototipado. | Software propietario; el plan gratuito está sujeto a las condiciones y limitaciones vigentes del servicio. |
| JUnit 6.2.0 | Framework de pruebas para Java. | Consultar la licencia publicada por el proyecto JUnit y las dependencias que se incorporen. |

Las versiones de las bibliotecas anteriores se han contrastado con las páginas oficiales o de publicación de sus proyectos a fecha de **28 de octubre de 2026**. En particular, las páginas consultadas muestran `mobile_scanner` 7.4.2, FlatLaf 3.7.2 y `sqlite-jdbc` 3.53.4.0 como las versiones estables más recientes disponibles en sus respectivos listados consultados [3][5][6]. JUnit publica notas de la versión 6.2.0, por lo que se actualiza la referencia anterior a 6.1.3 [7]. Esto no significa que deba actualizarse una dependencia sin comprobar antes su compatibilidad, las pruebas y el fichero de dependencias del proyecto.

## 5. Hallazgos

1. **Base técnica adecuada.** Según la autovaloración, los cuatro integrantes tienen un nivel medio alto en Java. Tres declaran nivel medio alto en Swing/FlatLaf y en SQLite/SQL, lo que proporciona una base para desarrollar la lógica del servidor y el panel de gestión.
2. **Flutter es la principal necesidad de aprendizaje.** Ningún integrante se sitúa por encima del nivel medio en Flutter/Dart. Se propone utilizar la documentación oficial, dividir el trabajo en tareas pequeñas y realizar programación por parejas y revisiones de código.
3. **El hardware disponible es suficiente para comenzar.** El equipo de desarrollo dispone de 16 GB de RAM y amplio espacio libre. Aun así, deben probarse el emulador y el escaneo en dispositivos reales, porque el rendimiento del emulador no sustituye las pruebas con cámara.
4. **Hay conocimientos concentrados en algunas herramientas.** La autovaloración muestra que Figma y Git/GitHub no están distribuidos por igual. Conviene compartir el conocimiento mediante revisiones, documentación breve y rotación de tareas.
5. **La comunicación entre componentes está pendiente de concretar.** Debe elegirse y documentarse el protocolo entre Flutter, el panel y el servidor Java. Una API REST sobre HTTPS es una opción posible, pero no debe presentarse como una decisión tomada hasta que el equipo la apruebe.
6. **SQLite requiere controlar el acceso concurrente.** SQLite puede ser suficiente para el prototipo, pero las transacciones, los bloqueos, las escrituras simultáneas y las copias de seguridad deben probarse. Si la carga, la concurrencia o el despliegue multiusuario lo exigen, se evaluará una base de datos cliente-servidor como PostgreSQL o MySQL.
7. **La seguridad debe formar parte del diseño.** Antes de dar por cerrada la arquitectura, se deben definir autenticación, autorización por roles, hash de contraseñas, comunicaciones cifradas, gestión de errores y restauración de copias de seguridad.

## 6. Conclusión

El desarrollo de **StockScan SGA se considera técnicamente viable para el alcance académico previsto**, siempre que se validen las integraciones y se aborden los riesgos identificados. El equipo dispone de hardware suficiente y de una base de conocimientos en Java y SQL. Flutter/Dart constituye la principal curva de aprendizaje.

La viabilidad definitiva depende de cerrar la comunicación entre los clientes y el servidor Java, comprobar las versiones mínimas de los dispositivos móviles, definir las medidas de seguridad y probar el comportamiento de SQLite con operaciones concurrentes. Estas tareas deben incorporarse a la planificación y a la matriz de riesgos. La conclusión no implica que la solución esté preparada para un despliegue de producción sin trabajo adicional.

## Referencias

[1] Flutter, *Supported deployment platforms*.  
https://docs.flutter.dev/reference/supported-platforms

[2] Flutter, *SDK archive* (para consultar y descargar la versión fijada del SDK).  
https://docs.flutter.dev/install/archive

[3] Dart/Flutter packages, *mobile_scanner: versiones, plataforma, changelog y licencia*.  
https://pub.dev/packages/mobile_scanner  
https://pub.dev/packages/mobile_scanner/versions  
https://pub.dev/packages/mobile_scanner/changelog

[4] Eclipse Adoptium, *Temurin releases — Java 21*.  
https://adoptium.net/temurin/releases/?version=21

[5] Xerial, *sqlite-jdbc: repositorio y versiones publicadas*.  
https://github.com/xerial/sqlite-jdbc  
https://github.com/xerial/sqlite-jdbc/releases

[6] FormDev Software, *FlatLaf: versiones publicadas*.  
https://github.com/JFormDesigner/FlatLaf/releases  
https://www.formdev.com/blog/flatlaf-3-7/

[7] JUnit Team, *Release notes*.  
https://docs.junit.org/6.2.0/release-notes.html

[8] SQLite, *About SQLite*.  
https://www.sqlite.org/about.html

[9] OpenJDK, *Licensing information*.  
https://openjdk.org/legal/

[10] Figma, *Terms of Service*.  
https://www.figma.com/legal/tos/

## 6. Estudio de viabilidad económica
### 1. Objetivo y metodología
 
Se estimó el coste de desarrollar StockScan SGA y el posible retorno económico de su implantación en un almacén, para comprobar si el proyecto es económicamente sostenible. Los importes se agrupan en tres tipos: costes **reales** (desembolsos efectivos), **estimados** (valoración de los recursos usados durante el desarrollo) e **hipotéticos** (gastos de una futura implantación comercial).
 
El trabajo del equipo se valora con una tarifa orientativa de 18 €/hora, propia de un desarrollador júnior. Las horas son las acumuladas por los cuatro integrantes: 74 h realizadas y 17 h pendientes, en total 91 h. Los demás valores (potencia de los equipos, precio de la electricidad, tarifa de Internet y ahorro de tiempo) son hipótesis de cálculo y no datos medidos.
 
### 2. Presupuesto de desarrollo
 
| Concepto | Cálculo | Importe |
|---|---|---:|
| Personal | 91 h × 18 €/h | 1.638,00 € |
| Hardware | Cuatro ordenadores HP ProOne cedidos por el centro | 0,00 € |
| Electricidad | 4 equipos × 16,65 h × 0,060 kW × 0,20 €/kWh | 0,80 € |
| Internet | 5 % de 4 conexiones domésticas de 35 €/mes durante 5,5 meses | 38,50 € |
| Software e infraestructura | Herramientas con versión o plan gratuito, sin alojamiento contratado | 0,00 € |
| Contingencias | 10 % de 1.677,30 € | 167,73 € |
| **Inversión inicial estimada** | | **1.845,03 €** |
 
Los 1.845,03 € son el valor económico del proyecto, incluido el trabajo del equipo, y no el dinero desembolsado: el gasto real es solo el coste proporcional de electricidad e Internet.
 
### 3. Mantenimiento
 
Para una futura implantación se estiman 24 horas anuales de mantenimiento (corrección de errores, actualizaciones, pequeñas mejoras y soporte), que a 18 €/hora suponen **432 € al año**. Este importe es hipotético y queda fuera de la inversión inicial.
 
### 4. Retorno de la inversión (ROI)
 
Escenario hipotético: dos trabajadores usan la aplicación, cada uno ahorra 30 minutos al día durante 220 días al año, con un coste laboral de 15 €/hora.
 
| Concepto | Cálculo | Resultado |
|---|---|---:|
| Horas ahorradas al año | 2 × 0,5 h × 220 días | 220 h |
| Ahorro anual | 220 h × 15 €/h | 3.300 € |
| Beneficio neto del primer año | 3.300 − 432 − 1.845,03 | 1.022,97 € |
| ROI | 1.022,97 / 1.845,03 × 100 | 55,44 % |
| Periodo de recuperación | 1.845,03 / (3.300 − 432) | 0,64 años (unos 7,7 meses) |
 
### 5. Hallazgos
 
1. El gasto directo del desarrollo es muy bajo (39,30 €), porque las herramientas tienen versión gratuita y los equipos los cede el centro.
2. Casi toda la inversión es el valor del trabajo del equipo (1.638 € de 1.845,03 €).
3. El mantenimiento anual (432 €) es pequeño frente al ahorro estimado (3.300 €), por lo que el resultado depende sobre todo del tiempo que se ahorre realmente.
### 6. Conclusión
 
En el escenario planteado, StockScan SGA presenta una **viabilidad económica inicial favorable**, con un ROI del 55,44 % en el primer año y una recuperación de la inversión en unos 7,7 meses.
 
Estos resultados son orientativos: se basan en un almacén hipotético y no en datos medidos, y dependen del tamaño del almacén, del número de trabajadores y del ahorro real de tiempo. Habría que validarlos con pruebas en un entorno real. Además, el estudio no incluye los costes de publicar la aplicación en Google Play y App Store ni los de un servidor en producción, que corresponderían a una distribución comercial.

## 7. Estudio de viabilidad legal y normativa

### 7.1. Protección de datos personales
## Marco Legal, Protección de Datos y Privacidad desde el Diseño

En el desarrollo e implementación del sistema **StockScan SGA**, la protección de los datos de carácter personal y la garantía de los derechos digitales de los usuarios constituyen un pilar fundamental de la arquitectura. A continuación, se detalla el análisis normativo y las medidas técnicas aplicadas en cumplimiento del Reglamento General de Protección de Datos (RGPD, UE 2016/679) y la Ley Orgánica 3/2018, de 5 de diciembre, de Protección de Datos Personales y garantía de los derechos digitales (LOPDGDD).

### 1. Identificación de Datos de Carácter Personal Recabados

Atendiendo al principio de **minimización de datos** (Art. 5.1.c del RGPD), el sistema limita la recogida de información a los campos estrictamente necesarios para la operativa logística y la gestión de almacenes:

* **Datos de Identificación y Acceso:** Nombre completo, correo electrónico corporativo, nombre de usuario (`username`) e identificador único (`user_id`). Las contraseñas se procesan de forma irreversible y nunca se almacenan en texto plano.
* **Perfil Operativo:** Rol asignado en la aplicación (*Operario*, *Supervisor*, *Administrador*) y asignación de cuadrantes o turnos de trabajo.
* **Datos de Registro Horario y Trazabilidad Operativa:** Marcas de tiempo de fichaje (entrada/salida de la jornada laboral) e historial de acciones en planta (lecturas de códigos de barras, movimientos de palés, mermas y reubicaciones vinculadas al ID del usuario).
* **Comunicaciones Internas:** Historial de mensajes y marcas de tiempo procesados mediante el chat interno de planta.

### 2. Base de Legitimación del Tratamiento (Art. 6.1 RGPD)

El tratamiento de los datos personales recopilados en StockScan SGA se justifica bajo las siguientes bases jurídicas:

* **Ejecución del Contrato Laboral (Art. 6.1.b RGPD):** Tratamiento indispensable para la asignación de tareas, la operativa de almacén y la ejecución de la prestación laboral por parte de los operarios.
* **Cumplimiento de Obligación Legal (Art. 6.1.c RGPD y Art. 20.2 LOPDGDD):** Respaldo jurídico directo para la recogida y conservación del registro diario de la jornada laboral exigido por la normativa laboral vigente en España.
* **Interés Legítimo (Art. 6.1.f RGPD):** Garantizar la seguridad de los activos de la empresa, la trazabilidad técnica del inventario, la prevención de descuadres o fraudes y el control físico de las mercancías en planta.

### 3. Medidas de Privacidad desde el Diseño y por Defecto (Art. 25 RGPD)

Para asegurar un nivel adecuado de seguridad frente a los riesgos del tratamiento (Art. 32 RGPD), se han integrado en el software las siguientes soluciones técnicas:

#### Control de Acceso Basado en Roles (RBAC)
La interfaz y la lógica de negocio restringen las funcionalidades según el rol autenticado. Los operarios solo acceden a las vistas de lectura y registro operativo, mientras que las métricas globales y la administración de usuarios quedan reservadas a supervisores y administradores.

#### Almacenamiento Seguro de Credenciales
Se implementan algoritmos de hashing seguro (**bcrypt** / **SHA-256** con *salt*) en la capa DAO antes de persistir cualquier credencial de acceso en la base de datos, imposibilitando su recuperación en texto plano.

#### Persistencia Local Protegida (SQLite)
El almacenamiento local en la base de datos SQLite aprovecha el entorno de aislamiento (*sandbox*) proporcionado por el sistema operativo del dispositivo (Android/iOS/Desktop), impidiendo que aplicaciones de terceros puedan acceder al archivo de datos.

#### Política de Retención y Eliminación de Datos
* **Chat de planta:** Purga automática periódica de los mensajes del chat transcurridos 30 días.
* **Fichajes e Historial:** Retención de datos de jornada durante el plazo legal obligatorio (4 años) y posterior borrado seguro o anonimización tras la baja laboral del trabajador.

---

**Referencias (IEEE)**
[1] Unión Europea, "Reglamento (UE) 2016/679 del Parlamento Europeo y del Consejo (RGPD)," *Diario Oficial de la Unión Europea*, L 119, pp. 1-88, 2016. [En línea]. Disponible en: https://eur-lex.europa.eu/legal-content/ES/TXT/?uri=CELEX:32016R0679  
[2] Jefatura del Estado (España), "Ley Orgánica 3/2018, de 5 de diciembre, de Protección de Datos Personales y garantía de los derechos digitales (LOPDGDD)," *Boletín Oficial del Estado*, no. 294, BOE-A-2018-16673, 2018. [En línea]. Disponible en: https://www.boe.es/buscar/act.php?id=BOE-A-2018-16673  
[3] Agencia Española de Protección de Datos (AEPD), "Guía de Privacidad desde el Diseño," *AEPD*, 2019. [En línea]. Disponible en: https://www.aepd.es/es/documento/guia-privacidad-desde-el-diseno.pdf  
[4] SQLite Development Team, "Databases in Mobile Applications and Local Storage Security," *SQLite Documentation*, 2024. [En línea]. Disponible en: https://www.sqlite.org/docs.html

### 7.2. Propiedad intelectual y licencias
do estático/dinámico de aplicaciones comerciales sin transmitir el efecto *copyleft* al código propio [4]. |
| **FlatLaf** | Look & Feel (Swing GUI) | Apache License 2.0 | Compatible | Permite la incorporación, modificación y distribución en software comercial sin exigir la liberación del fuente. Requiere mantener el aviso de copyright [2]. |
| **SQLite JDBC Driver** | Conector Base de Datos | Apache License 2.0 / Public Domain | Compatible | Facilita la persistencia local en dispositivos sin imponer restricciones de redistribución ni derechos de autor limitantes [3]. |
| **jBCrypt** | Cifrado de Credenciales | MIT License | Compatible | Licencia ampliamente permisiva que permite su libre empaquetado en productos comerciales manteniendo la nota de autor original [1]. |
| **JUnit 5** | Pruebas Unitarias | Eclipse Public License 2.0 (EPL 2.0) | Compatible | Empleado exclusivamente como herramienta de pruebas en la fase de desarrollo e integración continua. No se distribuye dentro del binario final en producción [1]. |
| **Lucide / FontAwesome** | Iconografía e Interfaz | ISC / SIL OFL / CC BY 4.0 | Compatible | Recurso gráfico abierto compatible con el diseño de interfaces comerciales mediante la correcta inclusión de los créditos tipográficos e iconográficos [1]. | 

### 3. Dictamen de Viabilidad Legal

De acuerdo con la auditoría realizada sobre la matriz de dependencias, **se confirma la plena viabilidad legal del proyecto** [1], [2]. Ninguna de las bibliotecas ni componentes de terceros integrados en la arquitectura de StockScan SGA infringe derechos de propiedad intelectual de terceros ni impone restricciones que comprometan la titularidad exclusiva del código propietario desarrollado por el equipo [1], [3].

---

**Referencias (IEEE)**
[1] Free Software Foundation (FSF), "Various Licenses and Comments about Them," *GNU Operating System*, 2024. [En línea]. Disponible en: https://www.gnu.org/licenses/license-list.html  
[2] Apache Software Foundation, "Apache License, Version 2.0," *Apache Software Foundation*, 2024. [En línea]. Disponible en: https://www.apache.org/licenses/LICENSE-2.0  
[3] SQLite Development Team, "SQLite Copyright and Intellectual Property," *SQLite Documentation*, 2024. [En línea]. Disponible en: https://www.sqlite.org/copyright.html  
[4] Oracle, "Oracle Java SE Licensing FAQ," *Oracle Technology Network*, 2024. [En línea]. Disponible en: https://www.oracle.com/java/technologies/javase/jdk-faqs.htm

### 7.3. Accesibilidad y otros requisitos aplicables
## 1. Objetivos de Accesibilidad

El objetivo fundamental de este apartado es garantizar que la interfaz gráfica de **StockScan SGA** sea plenamente operativa y eficiente para el mayor número de personas posible, incluyendo usuarios con limitaciones sensoriales (auditivas o de visión del color) y motrices. 

Para lograrlo, la arquitectura de la interfaz se ha diseñado en estricto cumplimiento con los estándares internacionales de accesibilidad digital y las normativas europeas/nacionales aplicables a productos y servicios TIC.
## 2. Marco Normativo y Principios Adoptados

### 2.1. Norma UNE-EN 301 549 y Pautas WCAG 2.1 (Nivel AA)
Se adopta como marco de referencia la norma **UNE-EN 301 549** (*Requisitos de accesibilidad para productos y servicios TIC*) en convergencia con las **Pautas de Accesibilidad al Contenido Web (WCAG 2.1 Nivel AA)** adaptadas a interfaces de escritorio (`WCAG2ICT`):
1. **Perceptible:** La información y los componentes de la interfaz gráfica son presentados de forma que todos los usuarios puedan percibirlos (contraste cromático, ausencia de dependencia cromática única y textos alternativos).
2. **Operable:** Todos los componentes interactivos son navegables y accionables desde el teclado sin requerir dispositivos apuntadores (ratón).
3. **Comprensible:** Los flujos de trabajo, mensajes de error y estados del sistema siguen un patrón intuitivo, coherente y predecible.
4. **Robusto:** El diseño de la interfaz en Swing es compatible con tecnologías de asistencia mediante la API de accesibilidad nativa de Java (`Java Access Bridge`).

## 3. Justificación de Decisiones de Diseño en la Interfaz

### 3.1. Ratios de Contraste Cromático y Uso del Color
* **Cumplimiento del Criterio WCAG 1.4.3 (Contraste Mínimo):**
  * **Texto Principal (`#1C1C1E`) sobre Fondo Claro (`#FFFFFF`):** Ratio de contraste de **17:1** (supera holgadamente el mínimo de 4.5:1 exigido para texto normal).
  * **Texto Blanco sobre Azul Primario (`#1B4F72`):** Ratio de contraste de **8.7:1**.
  * **Texto Secundario sobre Fondo Claro:** Ratio de contraste de **5.1:1**.
* **Cumplimiento del Criterio WCAG 1.4.1 (Uso del Color):**
  * El color **nunca es el único canal de información**. Los estados de inventario combinan color de acento con etiquetas de texto formateadas e iconos descriptivos:
    * Verde (`#27AE60`) + `[OK] En stock`
    * Ámbar (`#F39C12`) + `[BAJO] Stock bajo`
    * Rojo (`#E74C3C`) + `[SIN STOCK] Sin stock`

---

### 3.2. Navegación Asistida por Teclado (Foco y Tabulación)
* **Secuencia Lógica de Tabulación (Criterio 2.4.3):** El orden de foco sigue un recorrido estrictamente visual de izquierda a derecha y de arriba a abajo (`Tab` para avanzar, `Shift+Tab` para retroceder).
* **Foco Visible y Resaltado (Criterio 2.4.7):** Todos los componentes interactivos (`JButton`, `JTextField`, `JComboBox`, `JTable`) cuentan con un indicador de foco visual distintivo al estar activos.
* **Atajos y Teclas Rápidas:**
  * Tecla `Enter`: Confirma acciones en formularios y diálogos modales.
  * Tecla `Esc`: Cancela o cierra ventanas de diálogo sin guardar cambios.
  * **Foco Inicial Automático:** En formularios de lectura/búsqueda (`txtBuscarStock`), el foco se posiciona automáticamente mediante `SwingUtilities.invokeLater()` para permitir el uso directo de pistolas escáner de código de barras.

---

### 3.3. Tipografía Escalable y Jerarquía de Texto
* **Fuente del Sistema:** Uso de la familia sans-serif `SansSerif` / `Inter` para legibilidad general y tipografía monoespaciada (`Monospaced`) para códigos de referencia (`SKU`), ubicaciones (`PAS-02-EST-04`) y cantidades numéricas.
* **Jerarquía Mínima:** La información crítica del almacén utiliza tamaños de fuente de 14 px a 24 px en pesos de grosor medio a negrita (`Bold`), evitando el uso de tamaños inferiores a 12 px para datos representativos.

---

### 3.4. Lectores de Pantalla y Ayudas Sensibles al Contexto
* **Integración con Java Access Bridge:** Todos los componentes Swing incorporan etiquetas de accesibilidad mediante la API `AccessibleContext`:
  * `setAccessibleName(String)`: Asigna un nombre descriptivo a los botones que solo contienen icono (ej. *"Imprimir código QR"* o *"Cerrar diálogo"*).
  * `setAccessibleDescription(String)`: Proporciona ayuda contextual explicativa sobre la función del componente.
* **Tablas Accesibles:** Las `JTable` exponen la información de cabeceras asociadas a cada celda para que herramientas de lectura como **NVDA** puedan verbalizar el contexto de la columna seleccionada.
  
## 4. Auditoría y Verificación

| Prueba de Accesibilidad | Herramienta / Método | Resultado Obtenido | Estatus |
| :--- | :--- | :--- | :--- |
| **Contraste Cromático** | Colour Contrast Analyser (CCA) | Ratios $\ge 4.5:1$ en todos los pares texto/fondo de los 9 paneles. | **CONFORME** |
| **Navegación por Teclado** | Auditoría manual sin ratón | 100% de los elementos navegables y accionables vía `Tab` / `Enter`. | **CONFORME** |
| **Lectura Accesible** | NVDA + Java Access Bridge | Reconocimiento correcto de árboles de accesibilidad y nombres en botones. | **CONFORME** |


## 8. Análisis de riesgos iniciales
Se realizó un análisis de riesgos inicial para anticipar los obstáculos técnicos, de planificación, operativos y de equipo que podrían amenazar el éxito del proyecto, valorar su impacto y definir respuestas preventivas y correctivas. El análisis sigue el proceso general de gestión del riesgo descrito en la norma ISO 31000 [1], que comprende identificar, evaluar y tratar los riesgos.

Para la evaluación se empleó un análisis cualitativo basado en una matriz de probabilidad e impacto con tres niveles (bajo, medio y alto), un método habitual en proyectos de tecnologías de la información [2]. Los valores los estimó el equipo a partir de su criterio. Para obtener la severidad se asignó un valor numérico a cada nivel (bajo = 1, medio = 2, alto = 3) y se multiplicaron probabilidad e impacto. Las severidades de 1 a 2 se consideran bajas, las de 3 a 4 medias y las de 6 a 9 altas.

### 2. Riesgos identificados y evaluación

Se identificaron diez riesgos. Seis tienen severidad alta, tres media y uno baja. El más grave es el R06, los retrasos por falta de tiempo, con probabilidad alta e impacto alto (severidad 9).

### 3. Matriz de gestión de riesgos

| ID | Descripción | Probabilidad | Impacto | Severidad | Medida de prevención | Plan de contingencia |
|---|---|---|---|---|---|---|
| R01 | Rendimiento insuficiente en equipos antiguos o PDA | Media | Medio | 4 (Media) | Probar pronto en un equipo modesto; no cargar listas enteras | Reducir datos mostrados y simplificar pantallas |
| R02 | Incompatibilidades en empaquetado y ejecución multiplataforma | Media | Alto | 6 (Alta) | Versión de Java común; probar el empaquetado en varios sistemas y en HiDPI | Entregar con instrucciones y versión de Java necesaria |
| R03 | Cambios de alcance | Alta | Medio | 6 (Alta) | Product Backlog priorizado y alcance cerrado por sprint | Cambios nuevos al siguiente sprint |
| R04 | Retrasos por falta de tiempo | Alta | Alto | 9 (Alta) | Planificar con margen y revisar el avance cada semana | Recortar funciones de menor prioridad y avisar al equipo |
| R05 | Reparto desigual o baja disponibilidad de un miembro | Media | Alto | 6 (Alta) | Issues con responsable y reuniones breves | Reasignar tareas entre el resto |
| R06 | Conflictos al fusionar código en Git | Media | Bajo | 2 (Baja) | Ramas por funcionalidad, commits frecuentes y pull requests | Resolver entre todos y recuperar versiones del historial |
| R07 | Decisiones técnicas pendientes que obliguen a rehacer trabajo | Media | Medio | 4 (Media) | Decidir pronto el uso sin conexión y el almacenamiento | Aislar el acceso a datos en el modelo (MVC) |
| R08 | Pérdida o corrupción de datos | Baja | Alto | 3 (Media) | Validar datos antes de guardar y hacer copias periódicas | Restaurar la última copia |

### 4. Conclusiones

Los riesgos más importantes se concentran en la planificación y en la implementación: la falta de tiempo, la fidelidad del diseño en Swing, el empaquetado multiplataforma, los cambios de alcance y la disponibilidad del equipo. Las medidas de prevención se aplican desde el inicio, con alcance cerrado por sprint, prototipos tempranos y un reparto claro del trabajo, y la matriz se revisa en cada sprint para actualizar la probabilidad y el impacto de cada riesgo.

### Referencias

[1] International Organization for Standardization, "Risk management — Guidelines," ISO 31000:2018, 2nd ed., Feb. 2018. [Online]. Available: https://www.iso.org/standard/65694.html

[2] P. Croswell, "Qualitative risk analysis," GEOG 871: Geospatial Technology Project Management, The Pennsylvania State University. [Online]. Available: https://courses.ems.psu.edu/geog871/node/1772 (accessed Oct. 26, 2026).
### 1. Objetivo y metodología

Se realizó un análisis de riesgos inicial para anticipar los obstáculos técnicos, de planificación, operativos y de equipo que podrían amenazar el éxito del proyecto, valorar su impacto y definir respuestas preventivas y correctivas. El análisis sigue el proceso general de gestión del riesgo descrito en la norma ISO 31000 [1], que comprende identificar, evaluar y tratar los riesgos.

Para la evaluación se empleó un análisis cualitativo basado en una matriz de probabilidad e impacto con tres niveles (bajo, medio y alto), un método habitual en proyectos de tecnologías de la información [2]. Los valores los estimó el equipo a partir de su criterio. Para obtener la severidad se asignó un valor numérico a cada nivel (bajo = 1, medio = 2, alto = 3) y se multiplicaron probabilidad e impacto. Las severidades de 1 a 2 se consideran bajas, las de 3 a 4 medias y las de 6 a 9 altas.

### 2. Riesgos identificados y evaluación

Se identificaron diez riesgos. Seis tienen severidad alta, tres media y uno baja. El más grave es el R06, los retrasos por falta de tiempo, con probabilidad alta e impacto alto (severidad 9).

### 3. Matriz de gestión de riesgos

| ID | Descripción | Probabilidad | Impacto | Severidad | Medida de prevención | Plan de contingencia |
|---|---|---|---|---|---|---|
| R01 | Rendimiento insuficiente en equipos antiguos o PDA | Media | Medio | 4 (Media) | Probar pronto en un equipo modesto; no cargar listas enteras | Reducir datos mostrados y simplificar pantallas |
| R02 | Incompatibilidades en empaquetado y ejecución multiplataforma | Media | Alto | 6 (Alta) | Versión de Java común; probar el empaquetado en varios sistemas y en HiDPI | Entregar con instrucciones y versión de Java necesaria |
| R03 | Cambios de alcance | Alta | Medio | 6 (Alta) | Product Backlog priorizado y alcance cerrado por sprint | Cambios nuevos al siguiente sprint |
| R04 | Retrasos por falta de tiempo | Alta | Alto | 9 (Alta) | Planificar con margen y revisar el avance cada semana | Recortar funciones de menor prioridad y avisar al equipo |
| R05 | Reparto desigual o baja disponibilidad de un miembro | Media | Alto | 6 (Alta) | Issues con responsable y reuniones breves | Reasignar tareas entre el resto |
| R06 | Conflictos al fusionar código en Git | Media | Bajo | 2 (Baja) | Ramas por funcionalidad, commits frecuentes y pull requests | Resolver entre todos y recuperar versiones del historial |
| R07 | Decisiones técnicas pendientes que obliguen a rehacer trabajo | Media | Medio | 4 (Media) | Decidir pronto el uso sin conexión y el almacenamiento | Aislar el acceso a datos en el modelo (MVC) |
| R08 | Pérdida o corrupción de datos | Baja | Alto | 3 (Media) | Validar datos antes de guardar y hacer copias periódicas | Restaurar la última copia |

### 4. Conclusiones

Los riesgos más importantes se concentran en la planificación y en la implementación: la falta de tiempo, la fidelidad del diseño en Swing, el empaquetado multiplataforma, los cambios de alcance y la disponibilidad del equipo. Las medidas de prevención se aplican desde el inicio, con alcance cerrado por sprint, prototipos tempranos y un reparto claro del trabajo, y la matriz se revisa en cada sprint para actualizar la probabilidad y el impacto de cada riesgo.

### Referencias

[1] International Organization for Standardization, "Risk management — Guidelines," ISO 31000:2018, 2nd ed., Feb. 2018. [Online]. Available: https://www.iso.org/standard/65694.html

[2] P. Croswell, "Qualitative risk analysis," GEOG 871: Geospatial Technology Project Management, The Pennsylvania State University. [Online]. Available: https://courses.ems.psu.edu/geog871/node/1772 (accessed Oct. 26, 2026).
