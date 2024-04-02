## Transacciones

<details>
  <summary>Transacción General SAP</summary>

  - [SA38](#sa38)
</details>

<details>
  <summary>Análisis de Sistema</summary>

  - [SPRO - Customizing: Tratar proyecto](#spro---customizing-tratar-proyecto)
  - [ST01 - Trace sistema](#st01---trace-sistema)
  - [ST03N - Carga sistema y estad. rendimiento](#st03n---carga-sistema-y-estad-rendimiento)
  - [SM59 - Destino RFC (visualizar/editar)](#sm59---destino-rfc-visualizareditar)
  - [RZ11 - Actualización parámetros de perfil](#rz11---actualización-parámetros-de-perfil)
</details>

<details>
  <summary>Transacciones de Mantenimiento de Usuario</summary>

  - [PFCG - Actualizar roles](#pfcg---actualizar-roles)
  - [SU01 - Actualización de usuarios](#su01---actualización-de-usuarios)
  - [SU01D - Visualizar Usuarios](#su01d---visualizar-usuarios)
  - [SU3 - Actualiz. datos propios usuar.](#su3---actualiz-datos-propios-usuar)
  - [SU10 - Actualización en masa de usuarios](#su10---actualización-en-masa-de-usuarios)
  - [SU24 - Datos prop. autorización (Custom)](#su24---datos-prop-autorización-custom)
  - [SU53 - Evaluación verificación autorización](#su53---evaluación-verificación-autorización)
  - [SUIM - Sistema de información de usuario](#suim---sistema-de-información-de-usuario)
</details>

<details>
  <summary>Tabla de Base de Datos</summary>

  - [SE16 - Browser de datos](#se16---browser-de-datos)
  - [SE16N - Visualización general tabla](#se16n---visualización-general-tabla)
</details>

<details>
  <summary>Vigilancia</summary>

  - [SM19 - Log auditoría seguridad: Configur.](#sm19---log-auditoría-seguridad-configur)
  - [SM20 - Evaluar log auditoría seguridad](#sm20---evaluar-log-auditoría-seguridad)
</details>

<details>
  <summary>Consulta SAP</summary>

  - [SQ00 - Query SAP: Iniciar queries](#sq00---query-sap-iniciar-queries)
  - [SQ01 - Query SAP: Actualizar queries](#sq01---query-sap-actualizar-queries)
  - [SQ02 - Query SAP: Actualizar InfoSet](#sq02---query-sap-actualizar-infoset)
  - [SQ03 - Query SAP: Actualizar grupos usuarios](#sq03---query-sap-actualizar-grupos-usuarios)
  - [SQVI - QuickViewer](#sqvi---quickviewer)
</details>

<details>
  <summary>ABAP</summary>

  - [SM30 - Llamar actualización de vistas](#sm30---llamar-actualización-de-vistas)
  - [SM37 - Módulos de funciones ABAP](#sm37---módulos-de-funciones-abap)
  - [SE38 - Editor ABAP](#se38---editor-abap)
</details>

## SA38
La transacción SA38 en SAP es una herramienta que se utiliza para ejecutar programas ABAP (Advanced Business Application Programming) de manera directa. Permite a los usuarios ejecutar programas estándar del sistema o programas personalizados que han sido desarrollados utilizando el lenguaje de programación ABAP.

Mediante la transacción SA38, los usuarios pueden especificar el nombre del programa ABAP que desean ejecutar y, opcionalmente, proporcionar parámetros de entrada si el programa lo requiere. Una vez que se inicia la ejecución, el sistema SAP procesará el programa y mostrará los resultados en pantalla.

Esta herramienta es útil para llevar a cabo diversas tareas, como ejecutar informes estándar de SAP, programas de utilidad, programas de mantenimiento de datos, entre otros. Además, los desarrolladores pueden utilizar SA38 para probar y depurar programas ABAP durante el proceso de desarrollo.

[Volver al inicio](#transacciones)

## SPRO - Customizing: Tratar proyecto
La transacción SPRO en SAP es una de las más importantes y ampliamente utilizadas. SPRO es la abreviatura de "SAP Project Reference Object", y se utiliza para acceder al entorno de Customizing, que es donde se lleva a cabo la configuración y personalización del sistema SAP para adaptarlo a los procesos de negocio específicos de una empresa.

Dentro de la transacción SPRO, los usuarios pueden acceder a una amplia gama de vistas organizativas y realizar configuraciones en diferentes áreas funcionales del sistema SAP, como finanzas, logística, recursos humanos, entre otras. Estas configuraciones pueden incluir la definición de la estructura organizativa de la empresa, la parametrización de procesos empresariales, la configuración de datos maestros, la definición de flujos de trabajo, entre otros.

SPRO es una herramienta poderosa que permite a los consultores de SAP y a los administradores del sistema realizar ajustes precisos en la configuración del sistema para satisfacer los requisitos específicos de una empresa. Sin embargo, se debe tener cuidado al realizar cambios en el Customizing, ya que pueden tener un impacto significativo en el funcionamiento del sistema y en los procesos empresariales. Por lo tanto, es común que los cambios en SPRO sean realizados por personal con experiencia y conocimientos adecuados sobre el sistema SAP y los procesos empresariales implicados.

[Volver al inicio](#transacciones)

## ST01 - Trace sistema
La transacción ST01 en SAP es utilizada para rastrear y analizar la ejecución de transacciones en el sistema SAP. Proporciona una herramienta de traza (trace) que permite a los administradores y consultores de SAP examinar detalladamente qué actividades están realizando los usuarios en el sistema, así como también identificar posibles problemas de rendimiento.

Al utilizar la transacción ST01, los usuarios pueden activar y desactivar la traza para monitorear actividades específicas en el sistema. Esto incluye la posibilidad de rastrear las transacciones específicas que un usuario está ejecutando, las tablas de base de datos que están siendo accedidas y las funciones de sistema que están siendo llamadas durante la ejecución de una transacción.

El uso de la transacción ST01 puede ser útil para identificar cuellos de botella en el rendimiento del sistema, diagnosticar problemas de autorización, auditar actividades de usuario y optimizar la ejecución de procesos empresariales en SAP. Sin embargo, debido a la cantidad de datos que puede generar la traza, se recomienda utilizarla con moderación y solo cuando sea necesario para resolver problemas específicos o realizar análisis detallados.

[Volver al inicio](#transacciones)

## ST03N - Carga sistema y estad. rendimiento

La transacción ST03N en SAP se utiliza para analizar el rendimiento del sistema y obtener información detallada sobre la carga de trabajo y el tiempo de respuesta en un sistema SAP. Proporciona datos históricos y en tiempo real sobre el rendimiento del sistema, lo que permite a los administradores y consultores de SAP identificar posibles problemas de rendimiento y realizar ajustes para optimizar el sistema.

Dentro de la transacción ST03N, los usuarios pueden acceder a diversos informes y herramientas de análisis para obtener información sobre el rendimiento del sistema en diferentes áreas, como el tiempo de respuesta de las transacciones, el uso de recursos del sistema (CPU, memoria, disco), la carga de trabajo por usuario, el análisis de autorización, entre otros.

El análisis de rendimiento realizado a través de ST03N es fundamental para garantizar un funcionamiento eficiente y sin problemas del sistema SAP. Al monitorear y analizar regularmente el rendimiento del sistema, los administradores pueden identificar áreas de mejora y tomar medidas proactivas para evitar problemas de rendimiento antes de que afecten a los usuarios finales.

[Volver al inicio](#transacciones)

## SM59 - Destino RFC (visualizar/editar)
La transacción SM59 en SAP se utiliza para configurar y mantener destinos RFC (Remote Function Call) en el sistema. Estos destinos RFC son utilizados para establecer comunicación con sistemas externos a través de tecnologías como TCP/IP, HTTP, RFC, entre otras.

Dentro de la transacción SM59, los administradores pueden crear, modificar y visualizar los destinos RFC existentes. También pueden realizar pruebas de conectividad con los sistemas externos para verificar la configuración y la conectividad adecuada.

Algunos ejemplos de uso de la transacción SM59 incluyen la configuración de destinos RFC para comunicarse con sistemas SAP externos, sistemas no SAP, bases de datos externas, servicios web y otros sistemas externos. Esta transacción es esencial para la integración de sistemas y permite a los usuarios de SAP interactuar con sistemas externos de manera transparente desde el entorno SAP.

[Volver al inicio](#transacciones)

## RZ11 - Actualización parámetros de perfil
La transacción RZ11 en SAP se utiliza para visualizar y modificar los parámetros de perfil del sistema. Estos parámetros controlan diversos aspectos de la configuración y el comportamiento del sistema SAP, como la memoria asignada, los tiempos de espera, los límites de recursos, entre otros.

Dentro de la transacción RZ11, los administradores pueden ver una lista de todos los parámetros de perfil disponibles en el sistema, así como sus valores actuales y descripciones. También tienen la opción de modificar los valores de los parámetros de perfil según sea necesario para ajustar la configuración del sistema de acuerdo con los requisitos específicos.

Es importante tener cuidado al modificar los parámetros de perfil en RZ11, ya que los cambios incorrectos pueden afectar el rendimiento y la estabilidad del sistema SAP. Se recomienda que los administradores tengan un buen entendimiento de cómo cada parámetro afecta al sistema antes de realizar modificaciones significativas. Además, es aconsejable realizar cambios en un entorno de pruebas antes de implementarlos en un entorno de producción.

[Volver al inicio](#transacciones)

## PFCG - Actualizar roles
La transacción PFCG en SAP se utiliza para administrar los roles de autorización en el sistema. Los roles de autorización son conjuntos de autorizaciones que determinan qué actividades pueden realizar los usuarios en el sistema SAP. Esto incluye el acceso a transacciones específicas, la visualización y modificación de datos, y otras acciones dentro del sistema.

Dentro de la transacción PFCG, los administradores pueden crear, modificar y mantener roles de autorización. Pueden asignar autorizaciones individuales a los roles, definir niveles de autorización y estructurar los roles de manera que se ajusten a los requisitos de seguridad y los procesos empresariales de la organización.

Además de la administración de roles, la transacción PFCG también permite realizar análisis de roles para verificar la consistencia y la eficacia de los roles de autorización existentes. Esto incluye la comparación de roles, la búsqueda de duplicados y la identificación de posibles conflictos de autorización.

En resumen, la transacción PFCG es fundamental para la gestión de la seguridad y el control de acceso en el sistema SAP, ya que permite a los administradores definir y gestionar los roles de autorización para garantizar que los usuarios tengan el acceso adecuado a los recursos y las funciones del sistema.

[Volver al inicio](#transacciones)

## SU01 - Actualización de usuarios
La transacción SU01 en SAP se utiliza para administrar usuarios en el sistema. A través de SU01, los administradores pueden crear, modificar y visualizar información detallada sobre los usuarios del sistema SAP.

Algunas de las tareas comunes que se pueden realizar con la transacción SU01 incluyen:

- 1.- Crear nuevos usuarios en el sistema SAP, especificando detalles como nombre de usuario, contraseña, roles de autorización, y otros datos personales y de contacto.
- 2.- Modificar la información de usuarios existentes, como cambiar contraseñas, actualizar detalles de contacto o ajustar roles de autorización.
- 3.- Visualizar información detallada sobre los usuarios, incluyendo los roles asignados, las autorizaciones específicas y los datos maestros del usuario.
- 4.- Bloquear o desbloquear usuarios para evitar o permitir su acceso al sistema.
- 5.- Realizar otras acciones relacionadas con la gestión de usuarios, como la asignación de roles, la copia de perfiles, la eliminación de usuarios, entre otros.

En resumen, SU01 es una herramienta esencial para la administración de usuarios en el sistema SAP, permitiendo a los administradores gestionar de manera eficiente y segura el acceso de los usuarios a los recursos y funciones del sistema.

[Volver al inicio](#transacciones)

## SU01D - Visualizar Usuarios
La transacción SU01D en SAP es similar a la transacción SU01, pero está diseñada específicamente para visualizar usuarios de forma rápida y sencilla sin la posibilidad de realizar modificaciones en los datos.

A través de SU01D, los usuarios pueden ver la información detallada de otros usuarios en el sistema, incluyendo sus datos maestros, roles asignados, perfiles de autorización y otros detalles relevantes. Esta transacción es útil para propósitos de consulta y auditoría, ya que proporciona acceso rápido a la información de los usuarios sin la posibilidad de realizar cambios accidentalmente.

En resumen, SU01D es una herramienta útil para revisar la información de los usuarios en el sistema SAP de manera rápida y segura, especialmente cuando se necesita consultar la configuración de autorizaciones y roles de un usuario sin la intención de realizar modificaciones.

[Volver al inicio](#transacciones)

## SU3 - Actualiz. datos propios usuar.
La transacción SU3 en SAP se utiliza para mantener los datos de usuario propios, es decir, permite a los usuarios actualizar su propio perfil de usuario en el sistema. A través de SU3, los usuarios pueden configurar preferencias personales que afectan la forma en que interactúan con el sistema SAP.

Algunas de las configuraciones que los usuarios pueden ajustar utilizando la transacción SU3 incluyen:

- 1.- Preferencias de visualización, como formato de fecha, formato de hora, idioma preferido, etc.
- 2.- Configuración de impresión, como la impresora predeterminada.
Ajustes de correo electrónico, como la dirección de correo electrónico predeterminada.
- 3.- Preferencias de visualización en diferentes aplicaciones y módulos del sistema SAP.
- 4.- Otras configuraciones personales que afectan la experiencia del usuario en el sistema.

En resumen, SU3 proporciona a los usuarios la capacidad de personalizar su experiencia en el sistema SAP de acuerdo con sus preferencias individuales, lo que puede ayudar a mejorar la eficiencia y comodidad en el uso diario del sistema.

[Volver al inicio](#transacciones)

## SU10 - Actualización en masa de usuarios

La transacción SU10 en SAP se utiliza para realizar cambios en masa en los datos maestros de usuario en el sistema. Es especialmente útil cuando se necesita actualizar ciertos campos en los registros de usuario para varios usuarios al mismo tiempo, lo que permite a los administradores o especialistas en recursos humanos realizar modificaciones de manera eficiente y consistente.

Algunas de las tareas comunes que se pueden realizar con la transacción SU10 incluyen:

- 1.- Actualización de datos maestros de usuario, como dirección de correo electrónico, número de teléfono, posición organizativa, etc., para múltiples usuarios a la vez.
- 2.- Asignación o eliminación masiva de roles de autorización para un grupo de usuarios.
- 3.- Activación o desactivación de usuarios en masa.
- 4.- Modificación de campos de datos específicos para varios usuarios simultáneamente.

El uso de SU10 puede ayudar a agilizar los procesos de administración de usuarios en el sistema SAP, especialmente en entornos con una gran cantidad de usuarios o cuando se realizan cambios frecuentes en los datos de usuario. Sin embargo, es importante tener cuidado al utilizar esta transacción para evitar errores y asegurarse de mantener la integridad de los datos del sistema.

[Volver al inicio](#transacciones)

## SU24 - Datos prop. autorización (Custom)
La transacción SU24 en SAP se utiliza para gestionar los datos de propuestas de autorización. Las propuestas de autorización son sugerencias automáticas que el sistema SAP proporciona a los administradores de roles para las autorizaciones requeridas por ciertas transacciones.

Cuando un usuario ejecuta una transacción que requiere ciertas autorizaciones, el sistema SAP puede generar una propuesta de autorización en función de la configuración existente en la transacción. Estas propuestas se pueden ver y gestionar en la transacción SU24.

Algunas de las tareas que se pueden realizar con la transacción SU24 incluyen:

- 1.- Visualizar las propuestas de autorización existentes para transacciones específicas.
- 2.- Aprobar o rechazar propuestas de autorización.
- 3.- Modificar las propuestas de autorización para ajustarlas a los requisitos específicos de la empresa.
- 4.- Crear nuevas propuestas de autorización si es necesario.

El uso de la transacción SU24 es importante para garantizar que los roles de autorización estén configurados adecuadamente y proporcionen acceso apropiado a los usuarios para realizar sus funciones en el sistema SAP. Al gestionar de manera efectiva las propuestas de autorización, los administradores pueden mantener un control preciso sobre los permisos de los usuarios y garantizar la seguridad y la integridad del sistema.

[Volver al inicio](#transacciones)

## SU53 - Evaluación verificación autorización
La transacción SU53 en SAP se utiliza para realizar la evaluación de verificación de autorizaciones. Permite a los usuarios verificar las autorizaciones que se necesitan pero que no se han proporcionado, o para identificar las autorizaciones que están faltando o son insuficientes para llevar a cabo una determinada acción en el sistema.

Cuando un usuario recibe un error de autorización al intentar realizar una acción en el sistema SAP, pueden utilizar la transacción SU53 para analizar el problema. Al ejecutar la transacción SU53 después de recibir un error de autorización, el sistema SAP mostrará una lista de todas las autorizaciones que el usuario necesitaba para realizar la acción que intentaron, pero que no tenían en ese momento.

La información proporcionada por SU53 puede ser útil para los administradores de sistemas y los especialistas en autorizaciones para solucionar problemas de autorización y asegurarse de que los usuarios tengan los permisos adecuados para realizar sus funciones en el sistema SAP. También puede ser utilizado para fines de auditoría y cumplimiento normativo, ya que proporciona un registro de las autorizaciones que se necesitaban en momentos específicos en el sistema.

[Volver al inicio](#transacciones)

## SUIM - Sistema de información de usuario
La transacción SUIM en SAP se utiliza para generar informes y realizar consultas relacionadas con la gestión de usuarios en el sistema. SUIM proporciona una amplia gama de herramientas y funcionalidades que permiten a los administradores y especialistas en seguridad de SAP obtener información detallada sobre los usuarios, roles de autorización, perfiles, y otros aspectos relacionados con la gestión de la seguridad y los accesos en el sistema.

Algunas de las funcionalidades comunes que se pueden realizar con la transacción SUIM incluyen:

Generar informes sobre usuarios activos, inactivos, bloqueados o eliminados en el sistema.
Visualizar información detallada sobre los roles de autorización asignados a los usuarios, incluyendo los roles críticos y sensibles.
Realizar análisis de autorizaciones para identificar posibles conflictos de autorización o duplicados.
Revisar los registros de cambios en la gestión de usuarios para fines de auditoría y seguimiento.
Realizar consultas y búsquedas avanzadas para obtener información específica sobre usuarios, roles o perfiles en el sistema.
En resumen, SUIM es una herramienta poderosa que proporciona capacidades de generación de informes y análisis para la gestión de usuarios y la seguridad en el sistema SAP. Permite a los administradores y especialistas en seguridad monitorear y mantener un control preciso sobre los accesos y autorizaciones en el sistema, garantizando la integridad y la seguridad de los datos y procesos empresariales.

[Volver al inicio](#transacciones)

## SE16 - Browser de datos
La transacción SE16 en SAP se utiliza para visualizar datos en tablas de la base de datos del sistema. Proporciona una interfaz de búsqueda y consulta que permite a los usuarios ver los contenidos de las tablas del sistema, así como también de las tablas de usuario definidas por el usuario.

A través de SE16, los usuarios pueden buscar y ver datos de manera rápida y eficiente utilizando diferentes criterios de búsqueda y filtros. Pueden acceder a una amplia gama de tablas de la base de datos para visualizar información relevante para su trabajo, como datos maestros, registros de transacciones, registros de documentos, entre otros.

Es importante destacar que SE16 es una herramienta de solo lectura, lo que significa que los usuarios no pueden realizar modificaciones directamente en los datos utilizando esta transacción. Sin embargo, pueden exportar los resultados de la consulta a otros formatos, como Excel, para su posterior análisis o manipulación.

En resumen, SE16 es una herramienta útil para la visualización y consulta de datos en el sistema SAP, proporcionando a los usuarios una forma conveniente de acceder y explorar la información almacenada en las tablas de la base de datos del sistema.

[Volver al inicio](#transacciones)

## SE16N - Visualización general tabla
La transacción SE16N en SAP es una versión mejorada de SE16, que se utiliza para visualizar datos en las tablas de la base de datos del sistema. Al igual que SE16, SE16N proporciona una interfaz de búsqueda y consulta que permite a los usuarios ver los contenidos de las tablas del sistema, así como también de las tablas de usuario definidas por el usuario.

Sin embargo, SE16N ofrece algunas mejoras y características adicionales en comparación con SE16, incluyendo:

- 1.- Una interfaz de usuario más intuitiva y fácil de usar, con opciones de búsqueda y navegación mejoradas.
- 2.- Mayor flexibilidad en términos de selección y visualización de datos, incluyendo la capacidad de cambiar las columnas mostradas y aplicar filtros adicionales.
- 3.- Posibilidad de visualizar datos relacionados en varias tablas a través de relaciones definidas.
- 4.- Funcionalidades adicionales de exportación de datos a diferentes formatos, como Excel, texto plano, etc.
- 5.- Herramientas integradas para la gestión de variantes de selección y visualización, que permiten a los usuarios guardar y reutilizar configuraciones de búsqueda específicas.

En resumen, SE16N proporciona una experiencia de visualización y consulta de datos más avanzada y flexible en comparación con SE16, lo que permite a los usuarios acceder y explorar la información almacenada en las tablas de la base de datos del sistema de manera más eficiente y conveniente.

[Volver al inicio](#transacciones)

## SM19 - Log auditoría seguridad: Configur.
La transacción SM19 en SAP se utiliza para visualizar y analizar registros de auditoría relacionados con la seguridad en el sistema. Proporciona información detallada sobre actividades de usuario, intentos de acceso no autorizados, cambios en roles de autorización, entre otros eventos relacionados con la seguridad.

Algunas de las funcionalidades comunes que se pueden realizar con la transacción SM19 incluyen:

- 1.- Visualizar registros de auditoría para un período de tiempo específico.
- 2.- Filtrar registros de auditoría por tipo de evento, usuario, objeto afectado, etc.
- 3.- Analizar patrones de actividad de usuario para identificar comportamientos inusuales o potencialmente maliciosos.
- 4.- Monitorear cambios en roles de autorización y privilegios de usuario.
- 5.- Realizar investigaciones de seguridad y auditorías para cumplir con requisitos de cumplimiento y políticas de seguridad.

La transacción SM19 es una herramienta importante para la gestión de la seguridad en el sistema SAP, ya que proporciona a los administradores y especialistas en seguridad una visibilidad completa sobre las actividades de usuario y los eventos relacionados con la seguridad en el sistema. Esto les permite detectar y responder rápidamente a posibles amenazas y violaciones de seguridad para proteger los datos y recursos críticos de la empresa.

[Volver al inicio](#transacciones)

## SM20 - Evaluar log auditoría seguridad
La transacción SM20 en SAP se utiliza para analizar los registros de auditoría de seguridad en el sistema. Proporciona una interfaz para visualizar y analizar los registros de auditoría generados por el sistema SAP, lo que permite a los administradores y especialistas en seguridad monitorear las actividades de los usuarios y detectar posibles problemas de seguridad.

Algunas de las funcionalidades comunes que se pueden realizar con la transacción SM20 incluyen:

- 1.- Visualizar registros de auditoría para un período de tiempo específico.
- 2.- Filtrar registros de auditoría por tipo de evento, usuario, objeto afectado, etc.
- 3.- Realizar análisis de tendencias para identificar patrones de actividad de usuario y posibles amenazas de seguridad.
- 4.- Monitorear cambios en roles de autorización y privilegios de usuario.
- 5.- Generar informes de auditoría y cumplimiento normativo.

En resumen, la transacción SM20 es una herramienta importante para la gestión de la seguridad en el sistema SAP, ya que proporciona a los administradores y especialistas en seguridad una visibilidad completa sobre las actividades de usuario y los eventos relacionados con la seguridad en el sistema. Esto les permite detectar y responder rápidamente a posibles amenazas y violaciones de seguridad para proteger los datos y recursos críticos de la empresa.

[Volver al inicio](#transacciones)

## SQ00 - Query SAP: Iniciar queries

La transacción SQ00 en SAP se utiliza para trabajar con las herramientas de Query en el sistema SAP. Estas herramientas permiten a los usuarios crear y ejecutar consultas para recuperar datos de la base de datos del sistema y generar informes personalizados.

Algunas de las funcionalidades que se pueden realizar con la transacción SQ00 incluyen:

- 1.- Creación de consultas básicas utilizando la herramienta de Query.
- 2.- Definición de criterios de selección para filtrar los datos recuperados por la consulta.
- 3.- Configuración de opciones de visualización para el formato del informe resultante.
- 4.- Ejecución de la consulta para recuperar y visualizar los datos de acuerdo con los criterios especificados.
- 5.- Exportación de los resultados de la consulta a diferentes formatos, como Excel, PDF, etc.

La transacción SQ00 es una herramienta útil para los usuarios que necesitan acceder y analizar datos en el sistema SAP de una manera flexible y personalizada. Permite a los usuarios crear consultas específicas para sus necesidades y generar informes personalizados para analizar la información recuperada de la base de datos del sistema.

[Volver al inicio](#transacciones)

## SQ01 - Query SAP: Actualizar queries
La transacción SQ01 en SAP se utiliza para crear y mantener consultas de usuario en el sistema. Permite a los usuarios definir consultas ad hoc para recuperar datos de la base de datos del sistema SAP y generar informes personalizados según los requisitos específicos del usuario.

Algunas de las funcionalidades que se pueden realizar con la transacción SQ01 incluyen:

- 1.- Crear nuevas consultas de usuario desde cero utilizando la herramienta de Query.
- 2.- Definir criterios de selección para filtrar los datos recuperados por la consulta.
- 3.- Configurar opciones de visualización para el formato del informe resultante, incluyendo campos, columnas y cálculos.
- 4.- Ejecutar la consulta para recuperar y visualizar los datos de acuerdo con los criterios especificados.
- 5.- Modificar y mantener consultas existentes, incluyendo la adición o eliminación de campos, cambios en los criterios de selección, etc.

La transacción SQ01 es una herramienta poderosa que permite a los usuarios crear consultas ad hoc para analizar datos en el sistema SAP de una manera flexible y personalizada. Permite a los usuarios generar informes personalizados para satisfacer sus necesidades específicas de análisis y reporting.

[Volver al inicio](#transacciones)

## SQ02 - Query SAP: Actualizar InfoSet
La transacción SQ02 en SAP se utiliza para mantener y administrar InfoSets, que son conjuntos de datos lógicos definidos por el usuario en el sistema SAP. Un InfoSet permite a los usuarios combinar datos de diferentes tablas de la base de datos SAP para crear consultas y generar informes personalizados.

Algunas de las funcionalidades que se pueden realizar con la transacción SQ02 incluyen:

- 1.- Crear nuevos InfoSets: Los usuarios pueden definir nuevos conjuntos de datos lógicos especificando las tablas de la base de datos SAP que desean incluir y estableciendo las relaciones entre ellas.
- 2.- Mantener InfoSets existentes: Los usuarios pueden modificar y actualizar InfoSets existentes, incluyendo la adición o eliminación de campos, cambios en las relaciones entre tablas, etc.
- 3.- Definir atributos adicionales para los campos de InfoSets, como formatos de visualización, ayudas para la entrada de datos, descripciones, etc.
- 4.- Asignar autorizaciones a los InfoSets para controlar el acceso de los usuarios a los datos.
- 5.- Utilizar InfoSets en consultas y reportes: Una vez definidos, los InfoSets pueden ser utilizados en las herramientas de Query (como SQ01) para crear consultas y generar informes basados en los datos definidos en el conjunto de datos lógico.

En resumen, la transacción SQ02 es una herramienta importante para la creación y administración de InfoSets en el sistema SAP. Permite a los usuarios definir conjuntos de datos lógicos que combinan información de diferentes tablas de la base de datos para facilitar la creación de consultas y reportes personalizados.

[Volver al inicio](#transacciones)

## SQ03 - Query SAP: Actualizar grupos usuarios
La transacción SQ03 en SAP se utiliza para mantener y administrar grupos de usuarios para consultas (Query Groups). Un grupo de usuarios para consultas es una agrupación lógica de usuarios que tienen acceso a ciertos conjuntos de datos o informes específicos en el sistema SAP.

Algunas de las funcionalidades que se pueden realizar con la transacción SQ03 incluyen:

- 1.- Crear nuevos grupos de usuarios para consultas: Los usuarios pueden definir nuevos grupos de usuarios y asignarles permisos de acceso a ciertos conjuntos de datos o informes.
- 2.- Mantener grupos de usuarios existentes: Los usuarios pueden modificar y actualizar grupos de usuarios existentes, incluyendo la adición o eliminación de usuarios, cambios en los permisos de acceso, etc.
- 3.- Definir autorizaciones para los grupos de usuarios: Los administradores pueden asignar permisos de acceso específicos a ciertos conjuntos de datos o informes a los grupos de usuarios.
- 4.- Utilizar grupos de usuarios en consultas y reportes: Una vez definidos, los grupos de usuarios pueden ser utilizados en las herramientas de Query (como SQ01) para restringir el acceso a ciertos datos o informes basados en la pertenencia a un grupo de usuarios específico.

En resumen, la transacción SQ03 es una herramienta importante para la gestión de grupos de usuarios para consultas en el sistema SAP. Permite a los administradores definir y mantener grupos de usuarios y asignarles permisos de acceso específicos a conjuntos de datos o informes, lo que ayuda a controlar el acceso a la información y garantizar la seguridad de los datos en el sistema.
[Volver al inicio](#transacciones)

## SQVI - QuickViewer
La transacción SQVI en SAP se utiliza para acceder al QuickViewer, que es una herramienta que permite a los usuarios crear informes ad-hoc de manera rápida y sencilla sin la necesidad de conocimientos técnicos avanzados en programación.

Con SQVI, los usuarios pueden realizar las siguientes acciones:

- 1.- Crear consultas utilizando una interfaz gráfica de usuario.
- 2.- Definir criterios de selección para filtrar los datos recuperados por la consulta.
- 3.- Seleccionar los campos que desean visualizar en el informe.
- 4.- Personalizar la apariencia del informe, incluyendo el orden de los campos, los títulos de las columnas, etc.
- 5.- Ejecutar la consulta y visualizar los resultados en forma de tabla.
- 6.- Exportar los resultados a diferentes formatos, como Excel, PDF, etc.

El QuickViewer es una herramienta útil para los usuarios que necesitan generar informes ad-hoc de manera rápida y sencilla, sin la necesidad de recurrir a herramientas más complejas de desarrollo de informes. Permite a los usuarios acceder y analizar datos en el sistema SAP de una manera flexible y personalizada, lo que facilita la toma de decisiones basada en datos.

[Volver al inicio](#transacciones)

## SM30 - Llamar actualización de vistas
La transacción SM30 en SAP se utiliza para mantener vistas de actualización en el sistema. Las vistas de actualización son estructuras que se utilizan para definir y mantener los datos maestros y configuración del sistema en tablas específicas.

Con SM30, los usuarios pueden realizar las siguientes acciones:

- 1.-  Visualizar y modificar datos en tablas específicas.
- 2.- Agregar, editar y eliminar registros en las tablas.
- 3.- Utilizar criterios de selección para filtrar los datos mostrados.
- 4.- Realizar actividades de mantenimiento masivo en los datos de la tabla.
- 5.- Definir y mantener vistas de actualización.

Es importante tener en cuenta que SM30 permite realizar cambios directamente en los datos de la tabla, por lo que se deben tomar precauciones para garantizar la integridad de los datos y seguir las mejores prácticas de seguridad al usar esta transacción.

En resumen, SM30 es una herramienta útil para realizar tareas de mantenimiento de datos en el sistema SAP, permitiendo a los usuarios acceder y actualizar registros en las tablas de manera eficiente y segura.

[Volver al inicio](#transacciones)

## SM37 - Módulos de funciones ABAP
La transacción SM37 en SAP se utiliza para visualizar y administrar trabajos en el sistema SAP. Permite a los usuarios monitorear y controlar los trabajos que se han ejecutado o están en cola para su ejecución en el sistema SAP.

Algunas de las funcionalidades que se pueden realizar con la transacción SM37 incluyen:

- 1.- Visualizar una lista de todos los trabajos en el sistema, incluyendo trabajos en cola, trabajos en ejecución y trabajos completados.
- 2.- Ver detalles específicos de cada trabajo, como el estado, el usuario que lo ejecutó, el momento de inicio y finalización, el programa asociado, etc.
- 3.- Modificar o eliminar trabajos en cola antes de su ejecución.
- 4.- Reiniciar o relanzar trabajos que han finalizado con errores o han sido cancelados.
- 5.- Realizar búsquedas y filtrar trabajos basados en diferentes criterios, como el nombre del trabajo, el usuario, el estado, etc.

La transacción SM37 es una herramienta importante para la gestión y supervisión de trabajos en el sistema SAP, ya que permite a los usuarios mantener un control completo sobre las actividades programadas y asegurarse de que se ejecuten de manera efectiva y eficiente según lo planeado.

[Volver al inicio](#transacciones)

## SE38 - Editor ABAP
La transacción SM38 en SAP se utiliza para visualizar y administrar los trabajos de background en el sistema. Los trabajos de background son procesos que se ejecutan en segundo plano de manera automática y periódica para realizar tareas como procesamiento de datos, generación de informes, actualizaciones de bases de datos, entre otras.

Algunas de las funcionalidades que se pueden realizar con la transacción SM38 incluyen:

- 1.- Visualizar una lista de todos los trabajos de background en el sistema.
- 2.- Ver detalles específicos de cada trabajo, como el nombre del trabajo, el programa asociado, el estado, el momento de inicio y finalización, etc.
- 3.- Modificar o eliminar trabajos de background en cola antes de su ejecución.
- 4.- Reiniciar o relanzar trabajos que han finalizado con errores o han sido cancelados.
- 5.- Realizar búsquedas y filtrar trabajos basados en diferentes criterios, como el nombre del trabajo, el usuario, el estado, etc.

La transacción SM38 es una herramienta importante para la gestión y supervisión de los trabajos de background en el sistema SAP, ya que permite a los usuarios mantener un control completo sobre las actividades programadas y asegurarse de que se ejecuten de manera efectiva y eficiente según lo planeado.

[Volver al inicio](#transacciones)
