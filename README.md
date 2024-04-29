<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="Logo UPC">


# Universidad Peruana de Ciencias Aplicadas

Ingeniería de Software

Ciclo 2024-01

<hr>

# <center>Aplicaciones Web</center>

## TF REPORT

**Sección:** SW53

**Profesor**: Alex Humberto Sánchez Ponce

**StartUp Name**: NinjaCode

**Producto**: HormonalCare

### Team Members:

| Member                            |    Code    |
| :-------------------------------- | :--------: |
| Claudio Sandro Quispesivana Torres| U202215099 |
| Jherson David Astuyauri Calderon  | U202218451 |
| Estefano Sebastian Lostaunau Pereira | U202211742 |
| Chinchihualpa Saldarriaga Luis Sebastian | U202212112 |
| Hernan Emilio Morales Calderon | U202216263 |

<br>
</div>
























































































































































































































































































































































































































































































































































































## Capítulo-III-Requirements-Specification

### 3.1. To-Be Scenario Mapping.
Nuestro equipo, durante el proceso de elaboración del mapa "To Be" involucró la generación de ideas y propuestas de mejora mediante una lluvia de ideas individual. Se identificaron soluciones potenciales para abordar los desafíos y problemas identificados en el mapa "As Is". Luego, se definieron las fases del proceso como columnas en el mapa "To Be" y se representaron las mejoras propuestas para cada fase. Estas mejoras incluyeron la implementación de soluciones tecnológicas para agilizar la gestión de citas, mejorar el acceso a la información del paciente y facilitar la comunicación entre médicos y pacientes.

**User Persona: Paciente**
<img src="images/To be-medico.png">
**User Persona: Médico**
<img src="images/To be - paciente.png">
[Enlace To.be](https://miro.com/app/board/uXjVKaoDitI=/)


### 3.2. User Stories.
En la siguiente tabla, se presentan las User Stories junto con sus criterios de aceptación correspondientes para nuestro proyecto "HormonalCare". Las User Stories representan las funcionalidades clave que se desean implementar en la aplicación para mejorar la experiencia de los usuarios, tanto pacientes como médicos endocrinólogos. 


|<p>**Epic / Story** </p><p>**ID**</p>|**Título**|**Descripción**|**Criterios de Aceptación**|**Relacionado con (Story ID/ Epic ID)**|
| - | - | - | - | - |
|Epic001.|Gestión de Suscripciones.|**Como usuario interesado en acceder a servicios premium, quiero poder suscribirme fácilmente para tener acceso a funciones adicionales y mejorar mi experiencia en la plataforma.**|**-**|US17, US32 y US38.|
|Epic002 |Gestión de horarios y calendarios |**Como usuario quiero tener la capacidad de organizar y gestionar mis horarios donde se incluyan las citas médicas programadas y los horarios de medicación en un calendario integrado para optimizar mi planificación diaria y asegurarme de no perder ninguna tarea del calendario.**|**-**|US08, US27, US41 y US43.|
|Epic003|Gestión de citas médicas.|**Como usuario, quiero poder programar y gestionar citas médicas de manera sencilla para garantizar una atención oportuna y eficiente.**|**-**|US09, US14, US18, US25, US31, US37 Y US44.|
|Epic004|Gestión de exámenes.|**Como usuario quiero poder gestionar mis exámenes para obtener un tratamiento personalizado eficiente.**|**-**|US15, US24.|
|Epic005|Gestión de la historia clínica exámenes médicos|Como usuario deseo gestionar la historia clínica de un paciente para observar los antecedentes y ajustar el proceso.|**-**|US29, US45, US47, US48, US49 & US50.|
|Epic006|Gestión de comunicación médica – paciente.|Como usuario, quiero poder comunicarme de manera segura y efectiva para hacer preguntas, obtener asesoramiento y recibir seguimiento.|**-**|US06, US21, US30 y US39.|
|Epic007|Gestión de notificaciones.|Como usuario de la plataforma, quiero recibir notificaciones relevantes y personalizadas sobre citas, recordatorios de medicación y actualizaciones importantes para mantenerme informado y organizado en todo momento|**.**|US07, US22, US42 y US46.|
|Epic008|Gestión de medicación y tratamiento.|<p>**Como paciente con un régimen de medicación, quiero recibir recordatorios y seguimiento de dosis para asegurarme de tomar mis medicamentos según lo prescrito y mantenerme en buen estado de salud.**</p><p></p>|**-**|US19, US20 y US23.|
|Epic 009|Gestión de la landing page|**Como visitante interesado en el proyecto, quiero encontrar información clara y atractiva sobre los servicios ofrecidos en la landing page para comprender rápidamente los beneficios y funcionalidades que ofrece la plataforma.**|**-**|US01, US02, US03, US04, US05.|
|Epic 010|Registro de usuarios|**Como nuevo usuario, quiero poder registrarme de manera rápida y sencilla para acceder a todas las funciones y servicios de la plataforma y comenzar a beneficiarme de sus características.**|**-**|US10, US11, US12, US13 y US16.|
|Epic 011|Gestión de perfiles de usuario|**Como usuario registrado, quiero tener la capacidad de personalizar mi perfil y ajustar mis preferencias para adaptar la experiencia de la plataforma a mis necesidades individuales.**|**-**|US26, US28 y US40.|
|Epic 012|Gestión de búsquedas y filtros|**Como usuario de información específica, quiero contar con herramientas de búsqueda avanzadas y filtros para encontrar rápidamente la información relevante dentro de la plataforma y mejorar mi experiencia de usuario.**|**-**|US33, US34, US35 y US36.|
|Scenario: Add US01 |<p>Visualización del Header.</p><p></p><p></p>|Como como visitante deseo observar un header con varias secciones para conocer más sobre el producto.|<p>**Escenario 1:** Un visitante explora el header.</p><p>**Dado que** el visitante visita la landing page.</p><p>**Cuando** el visitante observa las secciones disponibles en el header.</p><p>**Entonces** el visitante encuentra fácilmente información relevante para su interés profesional.</p><p>**Escenario 2:** Un visitante hace clic en una sección del header.</p><p>**Dado que** el visitante endocrinólogo observa la landing page</p><p>**Cuando** el visitante hace clic en una sección específica del header.</p><p>**Entonces** el visitante es redirigido a la página correspondiente con más detalles sobre esa sección.</p>|Epic009|
|<p>US02</p><p></p>|Información sobre Planes o Suscripciones.|Como como visitante deseo observar una sección con información de los planes o suscripciones de la app para elegir el que mejor se ajusta a mi situación.|<p>**Escenario 1:** Un visitante considera las opciones de suscripción.</p><p>**Dado que** el visitante está interesado en suscribirse a "HormonalCare"</p><p>**Cuando** el visitante explora la sección de planes o suscripciones.</p><p>**Entonces** el visitante comprende claramente las características y beneficios de cada opción disponible.</p><p>**Escenario 2:** Un visitante solicita más información sobre un plan específico.</p><p>**Dado que** el visitante está interesado en un plan de suscripción</p><p>**Cuando** el visitante solicita más detalles sobre ese plan específico.</p><p>**Entonces** el sistema proporciona información detallada sobre las características y beneficios de ese plan.</p>|Epic009|
|US03|Visualización del footer en la landing page.|Como visitante, quiero acceder rápidamente a información relevante sobre la aplicación para informarme o revisar información adicional.|<p>**Escenario 1:** Un visitante busca información adicional.</p><p>**Dado que** un visitante quiere encontrar información sobre la aplicación.</p><p>**Cuando** revisa el footer de la lading page.</p><p>**Entonces** encuentra enlaces rápidos hacia secciones como "Acerca de Nosotros", "Contacto" y "Planes de Suscripción".</p><p>**Escenario 2:** Un visitante busca acceso rápido a las redes sociales o recursos adicionales.</p><p></p><p>**Dado que** el visitante desea acceder a las redes sociales o recursos adicionales relacionados con la app.</p><p>**Cuando** busca en el footer de la lading page.</p><p>**Entonces** el visitante encuentra enlaces directos a las redes sociales de la aplicación y recursos como blogs o artículos relacionados.</p>|Epic009|
|US04|Conocer la misión y visión de la aplicación|Como visitante deseo conocer más sobre la misión, visión y valores de la empresa detrás de la aplicación.|<p>**Escenario 1:** Un visitante busca información sobre la empresa.</p><p></p><p>**Dado que** el visitante está interesado en conocer más sobre la empresa detrás de la aplicación.</p><p>**Cuando** navega hacia la sección "Acerca de Nosotros".</p><p>**Entonces** el visitante encuentra una descripción clara de la misión, visión y valores de la empresa.</p><p>**Escenario 2:** Un usuario busca entender la historia y el equipo detrás de la aplicación.</p><p></p><p>**Dado que** el visitante desea conocer la historia y el equipo detrás de la aplicación.</p><p>**Cuando** el visitante explora la sección "Acerca de Nosotros".</p><p>**Entonces** el visitante encuentra una breve historia de la empresa y una presentación del equipo clave involucrado en el desarrollo y mantenimiento de la aplicación.</p>|Epic009|
|<p>US05</p><p></p>|Comunicación directa con el equipo de soporte|Como visitante de la aplicación, deseo poder comunicarme directamente con el equipo de soporte para solucionar problemas técnicos o comentarios sobre la plataforma.|<p>**Escenario 1:** Un visitante busca asistencia o tiene preguntas sobre la aplicación.</p><p>**Dado que** el visitante necesita asistencia o tiene preguntas sobre la aplicación.</p><p>**Cuando** el visitante busca la sección "Contáctanos".</p><p>**Entonces** el visitante encuentra múltiples canales de comunicación, como un formulario de contacto, dirección de correo electrónico y números de teléfono, para ponerse en contacto con el equipo de soporte.</p><p>**Escenario 2:** Un visitante tiene un problema técnico y necesita ayuda inmediata.</p><p></p><p>**Dado que** el visitante experimenta un problema técnico mientras utiliza la aplicación.</p><p>**Cuando** el visitante accede a la sección "Contáctanos".</p><p>**Entonces** el visitante encuentra información clara sobre cómo reportar problemas técnicos urgentes y recibe una respuesta rápida y efectiva del equipo de soporte.</p>|Epic009|
|US06|Integración de Twilio para comunicación por chat entre pacientes y doctores.|<p>Como desarrollador,</p><p>Necesito integrar Twilio en nuestra aplicación médica</p><p>Para permitir la comunicación por chat entre pacientes y doctores.</p>|<p>**Escenario:** Iniciar chat entre paciente y doctor.</p><p>**Dado que** un paciente desea comunicarse con su doctor a través de chat en la aplicación.</p><p>**Cuando** el paciente inicia un chat con el doctor seleccionado en la lista de contactos.</p><p>**Entonces** la aplicación utiliza Twilio para establecer una conexión de chat en tiempo real entre el paciente y el doctor.</p><p>**Escenario:** Enviar mensaje en el chat</p><p>**Dado que** un paciente y un doctor están en una conversación de chat a través de la aplicación</p><p>**Cuando** el paciente o el doctor envía un mensaje</p><p>**Entonces** la aplicación utiliza Twilio para enviar el mensaje al destinatario en tiempo real.</p>|Epic006|
|US07|Integración de Twilio para notificaciones en la aplicación médica.|<p>Como desarrollador,</p><p>Necesito integrar Twilio en nuestra aplicación médica</p><p>Para enviar notificaciones importantes a pacientes y doctores.</p>|<p>Escenario: Enviar notificación de cita programada</p><p>Dado que un paciente tiene una cita médica programada en la aplicación</p><p>Cuando llega la hora de la cita</p><p>Entonces la aplicación utiliza Twilio para enviar una notificación de recordatorio al paciente sobre la cita programada.</p><p></p><p>Escenario: Enviar notificación de cambio de horario de cita</p><p>Dado que se ha producido un cambio en la hora de una cita médica programada en la aplicación</p><p>Cuando se actualiza la hora de la cita</p><p>Entonces la aplicación utiliza Twilio para enviar una notificación al paciente afectado sobre el cambio de horario de la cita.</p>|Epic007|
|US08|Integración de Google Calendar para visualizar citas médicas y medicamentos.|<p>Como desarrollador,</p><p>Necesito integrar Google Calendar en nuestra aplicación médica</p><p>Para permitir que los usuarios visualicen sus citas médicas programadas y los horarios de medicación.</p><p></p>|<p>**Escenario:** Visualizar citas médicas en Google Calendar</p><p>**Dado que** un paciente desea ver sus citas médicas programadas en la aplicación</p><p>**Cuando** accede a la función de calendario dentro de la aplicación</p><p>**Entonces** la aplicación utiliza la API de Google Calendar para mostrar todas las citas médicas del paciente en su calendario personalizado dentro de la aplicación.</p><p>**Escenario:** Visualizar horarios de medicación en Google Calendar.</p><p>**Dado que** un paciente desea ver los horarios de medicación programados en la aplicación.</p><p>**Cuando** accede a la sección de horarios de medicación dentro de la aplicación.</p><p>**Entonces** la aplicación utiliza la API de Google Calendar para mostrar los horarios de medicación junto con los medicamentos correspondientes en su calendario personalizado dentro de la aplicación.</p>|Epic002|
|US09|Integración de Google Meet para citas médicas virtuales|<p>Como desarrollador,</p><p>Necesito integrar Google Meet en nuestra aplicación médica</p><p>Para permitir citas médicas virtuales entre pacientes y doctores.</p>|<p>**Escenario:** Programar cita médica virtual</p><p>**Dado que** un paciente desea programar una cita médica virtual en la aplicación.</p><p>**Cuando** selecciona un horario disponible y elige la opción de cita médica virtual</p><p>**Entonces** la aplicación genera automáticamente un enlace de Google Meet para la reunión y lo comparte con el paciente y el doctor involucrado en la cita.</p><p></p><p>**Escenario:** Unirse a la reunión virtual de Google Meet</p><p>**Dado que** ha llegado el momento de una cita médica virtual programada</p><p>**Cuando** el paciente o el doctor accede a la cita médica en la aplicación</p><p>**Entonces** la aplicación utiliza el enlace de Google Meet asociado para iniciar automáticamente la reunión virtual en Google Meet.</p>|Epic003|
|**US10**|Registro de usuario.|Como usuario de "HormonalCare" quiero poder registrarme en la aplicación para guardar mi cuenta en la plataforma.|<p>**Escenario 1:** Registro exitoso</p><p>**Dado que** un visitante desea registrarse en "HormonalCare".</p><p>**Cuando** el visitante proporciona la información necesaria para el registro.</p><p>**Entonces** el sistema crea una nueva cuenta de usuario y envía un mensaje de confirmación.</p><p>**Escenario 2:** Registro fallido por correo electrónico inválido.</p><p>**Dado que** un visitante intenta registrarse con un correo electrónico que inválido.</p><p>**Cuando** el visitante proporciona la información necesaria para el registro</p><p>**Entonces** el sistema muestra un mensaje de error indicando que el correo electrónico es inválido.</p><p></p>|Epic010|
|**US11**|Inicio de sesión con cuenta de HormonalCare|Como usuario de "HormonalCare" quiero iniciar sesión con mi cuenta registrada para acceder a mis configuraciones de forma rápida y segura. |<p>**Escenario 1:** Inicio de sesión una cuenta registrada.</p><p>**Dado que** un usuario registrado elige iniciar sesión con su cuenta creada.</p><p>**Cuando** el usuario autentica correctamente su correo y contraseña.</p><p>**Entonces** el sistema le concede acceso a su cuenta de "HormonalCare".</p><p>**Escenario 2:** Inicio de sesión fallido por contraseña incorrecta.</p><p>**Dado que** un usuario registrado elige iniciar sesión.</p><p>**Cuando** el usuario ingresa una contraseña errónea.</p><p>**Entonces** el sistema muestra un mensaje de error y no completa el inicio de sesión.</p>|Epic010|
|**US12**|Selección de Rol|Como usuario de "HormonalCare" deseo poder elegir el rol de paciente o médico para utilizar la app según mis necesidades.|<p>**Escenario 1:** Un usuario elige su rol como paciente</p><p>**Dado que** el usuario está registrando sus preferencias iniciales en la aplicación</p><p>**Cuando** elige el rol de "paciente".</p><p>**Entonces** el sistema personaliza la interfaz y las opciones disponibles según el rol de paciente.</p><p>**Escenario 2:** Un usuario elige su rol como médico.</p><p>**Dado que** el usuario está registrando sus preferencias iniciales en la aplicación.</p><p>**Cuando** elige el rol de "médico".</p><p>**Entonces** el sistema personaliza la interfaz y las opciones disponibles según el rol de médico.</p>|Epic010|
|**US13**|Recuperación de contraseña|Como** usuario de "HormonalCare" quiero recuperar mi contraseña para mantener mi cuenta.|<p>**Escenario 1:** Usuario restablece su contraseña.</p><p>**Dado que** un usuario ha olvidado su contraseña.</p><p>**Cuando el usuario** ingresa la dirección de correo electrónico asociada a su cuenta </p><p>Y el usuario solicita restablecer la contraseña.</p><p>**Entonces** el sistema envía un correo electrónico con un enlace válido para restablecer la contraseña.</p><p>**Escenario 2:** El usuario confirma su nueva contraseña.</p><p>**Dado que** el usuario se ha recibido un correo electrónico para restablecer la contraseña,</p><p>**Cuando** el usuario hace clic en el enlace proporcionado,</p><p>**Entonces** el usuario es redirigido a una página segura donde puede ingresar y confirmar una nueva contraseña.</p><p></p><p></p><p></p><p></p>|Epic010|
|**US14**|Agendar cita con médico endocrinólogo para usuarios totalmente nuevos.|Como paciente quiero poder agendar una cita con un médico endocrinólogo que me parezca adecuado tanto en precio como en calificación para poder recibir el tratamiento de mi enfermedad hormonal de manera remota.|<p>Escenario 1: Un paciente se encuentra en su pantalla principal.</p><p>Dado que un paciente que recién debuta con una enfermedad hormonal se encuentra en su pantalla principal de paciente.</p><p>Y desea agendar una cita con algún médico que tenga una buena relación costo-beneficio.</p><p>Cuando hace clic en la opción de “Médicos Disponibles” en el header.</p><p>Entonces este es redirigido a la página de Médicos Disponibles donde ver el perfil de algún médico que mejor le parezca en cuanto a calificación de estrellas, especialidad y/o precios.</p><p>Escenario 2: Agendar cita por parte del paciente con su médico deseado.</p><p>Dado que un paciente escoge un médico que ofrezca una mejor opción costo-beneficio.</p><p>Cuando hace clic en el botón “Agendar cita” que se encuentra en el perfil del médico.</p><p>Entonces es redirigido a la página de horarios disponibles del médico.</p><p>Y escogerá el turno de cita que mejor le perezca para un primer chequeo de su enfermedad hormonal.</p><p>Escenario 3: Pago de la cita previamente agendada por el paciente.</p><p>Dado que el paciente escoge un horario de cita con un médico que mejor le parezca.</p><p>Cuando hace clic en la opción de “Confirmar horario y proceder con el pago”.</p><p>Entonces el sistema lo redirige a la página de método de pago donde escogerá si quiere pagar con tarjeta, yape o plin.</p><p></p>|Epic003|
|**US15**|Subir resultados de exámenes médicos de laboratorio por parte del paciente.|Como paciente quiero poder cargar mis resultados de laboratorio para que mi medico los lea y me recete un determinado tratamiento para mi enfermedad hormonal.|<p>Escenario 1: Paciente encuentra el botón de subir resultados de exámenes para su médico.</p><p>Dado que un paciente fue recetado por un médico para hacerse exámenes de laboratorio sobre su enfermedad hormonal.</p><p>Y este se encuentre en su pantalla principal de paciente.</p><p>Cuando hace clic en el botón “Sube tus exámenes”.</p><p>Entonces aparece una ventana superpuesta en la pantalla principal en donde podrá observar todos los exámenes pendientes que tiene que subir.</p><p>Escenario 2: Pacientes su un examen de laboratorio en el sistema.</p><p>Dado que el paciente se encuentre en la ventana de Sube tus exámenes.</p><p>Cuando este hace clic en alguno de sus exámenes.</p><p>Entonces aparecerá una nueva ventana en donde podrá cargar los archivos de los resultados de sus exámenes hormonales.</p><p>Y se habilitará la opción de “Enviar” para que le lleguen los resultados a su médico.</p><p></p>|Epic004|
|**US16**|Usuario se registra como paciente con código que un médico le proporcionó. |Como paciente quiero poder registrarme con el código que me proporciono mi medico endocrinólogo para que sea él quien lleve mi tratamiento de manera remota.|<p>Escenario 1: Usuario desea registrase como paciente.</p><p>Dado que un usuario desea registrarse en HormonalCare como un paciente.</p><p>Cuando este se encuentre en la pantalla de bienvenida.</p><p>Y haga clic en la opción de “Registrese”.</p><p>Entonces se cargará el apartado donde podrá llenar sus datos personales.</p><p>Escenario 2: Usuario ingresa código de medico en su registro como paciente.</p><p>Dado que un usuario que se encuentre en el apartado de registro y tenga consigo un código de médico.</p><p>Cuando seleccione la respuesta “Si” de la pregunta “Viene de parte de algún medico”.</p><p>Entonces se habilitará la opción de Ingresar código del médico.</p><p>Y el sistema validará si código existe en la base de datos para que la pantalla principal del paciente se configuré de acuerdo con su médico.</p>|Epic010|
|**US17**|Cambiar plan de suscripción de médico desde su perfil de usuario.|Como medico quiero poder cambiar mi plan de suscripción actual para poder atender a una mayor cartera de clientes.|<p>Escenario 1: Médico encuentra la opción para cambiar su plan de suscripción.</p><p>Dado que el médico se encuentre en su pantalla principal.</p><p>Cuando el médico le dé clic al botón de “Perfil” en su header.</p><p>Entonces se cargará su perfil de usuario en donde aparecerá el contador de pacientes que le permite su plan.</p><p>Y también estará presente el botón para “Mejorar plan”</p><p>Escenario 2: Médico cambia su plan de suscripción.</p><p>Dado que el médico se encuentre en su perfil de usuario.</p><p>Cuando le de clic al botón de “Mejorar plan”.</p><p>Entonces se carga una ventana superpuesta en el perfil que mostrará el plan actual del médico y los demás planes que podría obtener.</p><p>Escenario 3: Médico anula su suscripción.</p><p>Dado que el médico se encuentre en la ventana superpuesta de cambiar plan en su perfil de usuario.</p><p>Cuando este hace clic en “Cancelar suscripción”.</p><p>Entonces se preguntará si realmente desea anular su suscripción. </p><p>Y si es sí, se mostrará un mensaje de despedida, y si es no volverá al apartado de cambiar suscripción.</p>|Epic001|
|**US18**|Médico asigna a paciente y programa una cita con un colega.|Como medico quiero poder realizar un traslado de paciente a otro médico para que pueda tener un horario más flexible.|<p>**Escenario 1:** Médico busca a su colega.</p><p>**Dado que** el médico desea contactar con su colega para asignarle un paciente.</p><p>**Y** este encuentre en la pantalla principal.</p><p>**Cuando** hace clic en el apartado de barra de búsqueda.</p><p>**Y** ingresé el correo de su colega.</p><p>**Entonces** se mostrará el perfil de su colega con toda su información y certificados.</p><p>**Escenario 2:** Contactar con colega.</p><p>**Dado que** el médico este viendo el perfil de uno de sus colegas.</p><p>**Cuando** le di clic al botón de enviar mensaje.</p><p>**Entonces** se abrirá un chat donde podrá informar el traslado de un paciente.</p><p>**Escenario 3:** Traslado de un paciente.</p><p>**Dado que** el médico haya contactado con su colega y le haya comunicado el traslado de un paciente.</p><p>**Cuando** el médico este en el perfil de su colega y haga clic en el botón asignar paciente.</p><p>**Entonces** se mostrará todos los pacientes que tiene el médico y podrá añadirlo a su perfil de su colega asignado un horario con el sin previo pago.</p><p></p>|Epic003|
|**US19**|Ver información detallada de los pacientes.|Como medico quiero poder tener de manera organizada los resultados de mis pacientes para que pueda llevar un registro más detallado de su tratamiento.|<p>**Escenario 1:** Ver información resumida del paciente.</p><p>**Dado que** el médico desea ver la información resumida de su lista de pacientes.</p><p>**Cuando** el médico haya iniciado sesión en la plataforma.</p><p>**Entonces** esta mostrará en la pantalla principal toda la información de la lista de pacientes que tiene el médico según su plan de suscripción.</p><p>**Escenario 2:** Ver información a detalle de cada paciente.</p><p>**Dado que** el médico desea saber y tener de manera organizada toda la información principal del paciente.</p><p>**Y** se encuentre en la pantalla principal.</p><p>**Cuando** hace clic en uno de sus pacientes.</p><p>**Entonces** se mostrará toda la información del paciente determinado.</p>|Epic 008|
|**US20**|Ver lista de pacientes del día.|Como médico deseo ver los pacientes del día para tener una cita médica más eficiente.|<p>**Escenario 1:** El médico observa los pacientes de hoy.</p><p>**Dado que** el médico desea organizar su agenda para el día.</p><p>**Cuando** el médico accede a su sección principal.</p><p>**Entonces** se muestra una lista clara y completa de todos los pacientes programados para ese día, con información relevante como nombre, tipo de atención, hora, diagnóstico, alerta y videoconferencia.  </p><p>**Escenario 2:** El médico busca un paciente de su cartera.</p><p>**Dado que** el médico se encuentra en la sección principal propia.</p><p>**Cuando** el médico acceda al buscador de pacientes.</p><p>**Entonces** el sistema permite encontrar a cualquier paciente dentro de su cartera de pacientes.</p>|Epic 008|
|**US21**|Comunicación directa con el paciente.|Como médico quiero comunicarme de forma directa con el paciente para resolver consultas.|<p>**Escenario 1:** El médico accede al chat con el paciente.</p><p>**Dado que** un médico necesita resolver consultas de manera eficiente.</p><p>**Cuando** accede a la función de comunicación directa disponible en la plataforma.</p><p>**Entonces** puede seleccionar al paciente con quien desea comunicarse y comenzar una conversación.</p><p>**Escenario 2:** El médico recibe una notificación del mensaje de un paciente.</p><p>**Dado que** un médico está interactuando con un paciente a través de la función de comunicación directa.</p><p>**Cuando** el paciente responde a la consulta o plantea preguntas adicionales.</p><p>**Entonces** el médico recibe una notificación para responder y puede mantener una conversación fluida hasta resolver todas las consultas.</p><p>**Escenario 3:** El médico archiva una conversación con un paciente.</p><p>**Dado que** un médico ha finalizado la comunicación con el paciente.</p><p>**Cuando** la consulta se ha resuelto satisfactoriamente.</p><p>**Entonces** el médico puede cerrar la conversación y archivarla para futuras referencias si es necesario.</p>|Epic 006|
|**US22**|Notificaciones a médicos de las citas.|Como médico deseo recibir notificaciones de las citas para prepárame mejor.|<p>**Escenario 1:** El médico accede a sus preferencias de notificación.</p><p>**Dado que** un médico desea estar informado sobre sus citas programadas.</p><p>**Cuando** accede a la configuración de su cuenta en la plataforma,</p><p>**Entonces** puede encontrar una sección dedicada a las preferencias de notificación.</p><p>**Escenario 2:** El médico configura sus preferencias de notificación.</p><p>**Dado que** un médico está configurando sus preferencias de notificación,</p><p>**Cuando** selecciona la opción de recibir notificaciones de citas,</p><p>**Entonces** puede elegir el método de notificación preferido (por ejemplo, correo electrónico, mensaje de texto, notificación en la aplicación).</p><p>**Escenario 3:** El médico recibe una notificación.</p><p>**Dado que** un médico ha configurado sus preferencias de notificación para recibir alertas sobre citas.</p><p>**Cuando** se programan nuevas citas para el médico en la plataforma.</p><p>**Entonces** el médico recibe notificaciones inmediatas sobre las citas programadas, utilizando el método de notificación seleccionado previamente.</p><p>**Escenario 4:** El médico observa a detalle su notificación.</p><p>**Dado que** un médico ha recibido una notificación sobre una cita programada,</p><p>Cuando revisa la notificación,</p><p>**Entonces** la información proporcionada en la notificación incluye detalles relevantes sobre la cita, como la fecha, la hora y la información del paciente, para permitir una mejor preparación**.**</p><p></p>|Epic 007|
|**US23**|Ver la medicación del paciente.|Como médico quiero ver la medicación dispuesta a cada paciente para verificar o cambiar la receta médica.|<p>**Escenario 1:** El médico observa la medicación actual de un paciente.</p><p>**Dado que** el médico un médico necesita revisar la medicación de un paciente.</p><p>**Cuando** el médico accede a la vista de cada paciente.</p><p>**Entonces** el médico puede encontrar una sección dedicada a la medicación del paciente.</p><p>**Escenario 2:** El médico observa la lista completa al detalle de medicamentos del paciente.</p><p>**Dado que** un médico está revisando la medicación de un paciente.</p><p>**Cuando** selecciona la sección de medicación.</p><p>**Entonces** se muestra una lista completa de todos los medicamentos prescritos al paciente, junto con detalles como nombre del medicamento, dosis, frecuencia y duración del tratamiento.</p><p>**Escenario 3:** El médico realiza ajustes a la medicación del paciente.</p><p>**Dado que** el médico que un médico está revisando la medicación de un paciente,</p><p>**Cuando** el médico identifica la necesidad de cambiar la receta médica,</p><p>**Entonces** el médico puede realizar los ajustes necesarios en la medicación directamente desde el perfil del paciente.</p>|Epic 008|
|**US24**|Ver los exámenes a evaluar.|Como médico deseo observar los exámenes que tengo que evaluar de cada paciente para personalizar su tratamiento.|<p>**Escenario 1:** El médico observa los exámenes a evaluar.</p><p>**Dado que** un médico necesita personalizar el tratamiento de un paciente basándose en los resultados de los exámenes,</p><p>**Cuando** el medico accede a la vista de cada paciente,</p><p>**Entonces** el sistema muestra una sección dedicada a los resultados de los exámenes médicos.</p><p>**Escenario 2:** El médico ingresa al apartado de los exámenes a evaluar.</p><p>**Dado que** un médico está revisando los resultados de los exámenes de un paciente.</p><p>**Cuando** le médico selecciona la sección de resultados de exámenes,</p><p>**Entonces** el sistema muestra una lista completa de todos los exámenes realizados al paciente, junto con los resultados obtenidos.</p>|Epic 004|
|**US25**|Agendar una cita con el paciente.|Como médico quiero agendar una cita médica a un paciente que ya se atiende conmigo para continuar con el tratamiento.|<p>**Escenario 1:** El médico selecciona agendar una siguiente cita.</p><p>**Dado que** un médico necesita continuar el tratamiento de un paciente,</p><p>**Cuando** el medico accede a la vista de cada paciente,</p><p>**Entonces** puede agendar una siguiente cita para el paciente.</p><p>**Escenario 1:** El médico agenda una siguiente cita.</p><p>**Dado que** un médico ha seleccionado agendar una siguiente cita a un paciente,</p><p>**Cuando** el médico elige la fecha y hora para la cita médica,</p><p>**Entonces** el médico puede reservar la cita en el horario adecuado para ambas partes.</p>|**Epic003**|
|**US26**|Edición de Perfil por parte del Médico.|Como médico, quiero poder acceder y editar mi perfil en la plataforma para mantener actualizada mi información profesional.|<p>**Escenario 1:** Acceso al Perfil.</p><p>**Dado que** soy un médico registrado.</p><p>**Cuando** inicio sesión en la plataforma.</p><p>**Entonces** debo poder acceder a mi perfil médico.</p><p>**Escenario 2:** Edición del Perfil.</p><p>**Dado que** estoy en mi perfil médico.</p><p>**Cuando** deseo realizar cambios en mi información profesional (por ejemplo, especialidad, información de contacto, foto de perfil).</p><p>**Entonces** debo poder editar los campos necesarios y guardar los cambios de manera exitosa.</p>|**Epic 011**|
|**US27**|Visualización y Gestión de Horario por parte del Médico.|Como médico, quiero poder ver mi horario con eventos programados y tener la capacidad de crear nuevos eventos según sea necesario, para organizar eficientemente mis actividades diarias y administrar mi agenda profesional de manera efectiva.|<p>**Escenario 1:** Visualización del Horario.</p><p>**Dado que** soy un médico registrado.</p><p>**Cuando** accedo a la página principal de la plataforma.</p><p>**Entonces** debo poder ver claramente mi horario con los eventos médicos programados para cada día.<br><br>**Escenario 2:** Creación de Nuevo Evento.</p><p>**Dado que** estoy visualizando mi horario.</p><p>**Cuando** deseo agregar un nuevo evento (como una cita médica, reunión o procedimiento).</p><p>**Entonces** debo tener la opción de crear un nuevo evento, especificando la fecha, hora, tipo de evento y detalles relevantes.</p>|**Epic 002**|
|**US28**|Búsqueda y Visualización de Perfiles de Otros Médicos por parte del Médico.|Como médico, quiero poder buscar a otro médico en la plataforma desde la página principal, para visualizar su perfil con sus datos personales y tener la capacidad de enviar mensajes y asignar pacientes según sea necesario.|<p>**Escenario 1:** Búsqueda de Médico.</p><p>**Dado que** soy un médico registrado y me encuentro en la página principal.</p><p>**Cuando** utilizo el buscador para buscar a otro médico por nombre, especialidad u otros criterios.</p><p>**Entonces** debo poder encontrar y seleccionar el perfil del médico deseado.<br><br>**Escenario 2:** Visualización, Mensaje y Asignación.</p><p>**Dado que** he seleccionado el perfil de otro médico.</p><p>**Cuando** accedo al perfil, quiero ver información detallada como nombre, apellido, eMail, Nº Colegio, títulos y disponibilidad de citas.</p><p>**Entonces** debo poder visualizar todos estos datos de manera clara y organizada.</p><p>**Y** quiero tener la opción de enviar un mensaje al médico desde la plataforma y la capacidad de asignar pacientes específicos a ese médico si tengo la autorización correspondiente.</p>|**Epic011**|
|**US29**|Ver el historial médico de un paciente.|Como médico deseo ver el historial médico de mi paciente para garantizar un tratamiento óptimo.|<p>**Escenario 1:**  Un médico accede al historial clínico de un paciente.</p><p>**Dado que** un médico necesita revisar el historial médico de un paciente para proporcionar un tratamiento óptimo.</p><p>**Cuando** accede a la sección de historial médico del paciente en el sistema.</p><p>**Entonces** se muestra de manera clara y organizada la información relevante, como diagnósticos previos, tratamientos anteriores, alergias, resultados de exámenes médicos, medicaciones recetadas, entre otros.</p><p>**Escenario 2:** El médico observa información específica del historial de un paciente.</p><p>**Dado que** un médico está revisando el historial médico del paciente.</p><p>**Cuando** necesita información específica, como resultados de exámenes o tratamientos anteriores.</p><p>**Entonces** puede acceder a detalles adicionales haciendo clic en los elementos pertinentes del historial médico.</p>|**Epic005**|
|**US30**|Acceso al Chat desde el Perfil de Otro Médico por parte del Médico.|Como médico, cuando estoy visualizando el perfil de otro médico en la plataforma, quiero tener la capacidad de iniciar un chat directo con ese médico para enviarle mensajes de forma rápida y directa.|<p>**Escenario 1:** Acceso al Chat desde el Perfil.</p><p>**Dado que** soy un médico y estoy visualizando el perfil de otro médico.</p><p>**Cuando** deseo comunicarme con ese médico de manera privada.</p><p>**Entonces** debo tener la opción clara y accesible para iniciar un chat directo desde el perfil del médico.</p><p>**Escenario 2:** Interacción en el Chat Directo.</p><p>**Dado que** he iniciado un chat directo con otro médico desde su perfil.</p><p>**Cuando** envío un mensaje.</p><p>**Entonces** el médico destinatario debe recibir el mensaje de manera inmediata y poder responder en tiempo real.</p>|**Epic006**|
|**US31**|Asignación de Paciente a Otro Médico con Programación de Cita por parte del Médico.|Como médico, cuando estoy visualizando el perfil de otro médico en la plataforma y deseo asignarle un paciente, quiero tener la capacidad de seleccionar al paciente deseado y luego ver los horarios disponibles del médico para programar una cita con el paciente asignado.|<p>**Escenario 1:** Selección de Paciente.</p><p>**Dado que** soy un médico y estoy en el perfil de otro médico.</p><p>**Cuando** decido asignarle un paciente al médico seleccionado.</p><p>**Entonces** debo poder elegir al paciente deseado desde una lista de pacientes disponibles.</p><p>**Escenario 2:** Programación de Cita con Horarios Disponibles.</p><p>**Dado que** he seleccionado al paciente para asignar al médico.</p><p>**Cuando** busco los horarios disponibles del médico para programar una cita con el paciente.</p><p>**Entonces** debo poder ver los horarios disponibles del médico según el mes seleccionado.</p><p>**Y** también debo tener la capacidad de seleccionar y confirmar un horario específico para la cita con el paciente asignado.**<br></p>|**Epic003**|
|**US32**|Cancelación de Plan de Suscripción desde el Perfil por parte del Médico.|Como médico, cuando estoy en mi perfil en la plataforma, quiero tener la capacidad de gestionar mi plan de suscripción, para cancelar la suscripción si así lo deseo.|<p>**Escenario 1:** Acceso a la Gestión de Suscripción.</p><p>**Dado que** soy un médico y estoy en mi perfil en la plataforma.</p><p>**Cuando** quiero gestionar mi plan de suscripción.</p><p>**Entonces** debo tener la opción clara y visible para acceder a la sección de gestión de suscripción.<br><br>**Escenario 2:** Cancelación de Suscripción.</p><p>**Dado que** he accedido a la sección de gestión de suscripción.</p><p>**Cuando** decido cancelar mi suscripción.</p><p>**Entonces** debo poder seleccionar la opción de cancelar mi suscripción.</p>|**Epic001**|
|**US33**|Buscador de colegas médicos.|Como médico quiero buscar a mis colegas gestionar un seguimiento conjunto de los pacientes.|<p>**Escenario 1:** Un médico busca correctamente a su colega.</p><p>**Dado que** el médico se encuentra en su página principal.</p><p>**Cuando** el medico acceda al buscador </p><p>**Y** coloca un correo de un colega</p><p>**Entonces** el sistema muestra la información de su colega.</p><p>**Escenario 2:** Un médico busca a su colega con un valor inválido.</p><p>**Dado que** el médico se encuentra en su página principal.</p><p>**Cuando** el medico acceda al buscador </p><p>**Y** coloca el nombre o la especialidad de algún colega</p><p>**Entonces** el sistema muestra un mensaje de error indicando que solo es posible buscar por correo.</p><p></p>|**Epic012**|
|**US34**|Visualizar médicos disponibles|Como paciente quiero poder visualizar a los médicos disponibles con campos como especialidad, subespecialidad, tarifa, recomendaciones, nombre y foto para tratar mi enfermedad hormonal|<p>**Escenario 1:** Paciente nuevo desea buscar un médico</p><p>**Dado que** soy un paciente recientemente registrado en la aplicación y no tengo la referencia de un médico y me encuentro en la pestaña principal de la aplicación</p><p>**Cuando** hago clic sobre Médicos disponibles</p><p>**Entonces** se despliega la interfaz de los médicos disponibles en los que se pueda visualizar todos los médicos disponibles en la plataforma y pueda previsualizar campos como especialidad, subespecialidad, tarifa, recomendaciones, nombre y foto</p>|**Epic012** |
|**US35**|Filtrar médicos disponibles|Como paciente nuevo en la aplicación quiero poder visualizar a todos los médicos disponibles y poder filtrarlos por campos como su sexo, subespecialidad, recomendaciones, experiencia y rango de tarifas para tomar elegir al mejor doctor de acuerdo con mis preferencias.|<p>**Escenario 1:** Paciente nuevo desea filtrar y buscar los médicos disponibles</p><p>**Dado que** soy un paciente recientemente registrado en la aplicación y no tengo la referencia de un médico y me encuentro visualizando a los médicos disponibles</p><p>**Cuando** hago clic sobre los campos de filtro y búsqueda del campo lateral</p><p>**Entonces** el sistema ordena, filtra o elige los médicos que cumplan con los filtros ingresados por el usuario con el fin de que pueda tomar la elección que este desee</p>|**Epic012**|
|**US36**|Selección de médico disponible|Como paciente nuevo quiero poder ver el perfil del médico elegido con campos como su nombre completo, sus años de experiencia, títulos adjuntos e información profesional como su formación de pregrado, postgrado, número de colegio médico, registro nacional de especialista y la tarifa estándar para informarme sobre las bondades de su servicio.|<p>**Escenario 1:** Paciente nuevo que elige al doctor con el que llevará el tratamiento</p><p>**Dado que** soy un paciente recientemente registrado en la aplicación y ya escogí al médico luego de filtrarlo</p><p>**Cuando** hago clic sobre su nombre</p><p>**Entonces** el sistema muestra el perfil del médico con campos como nombre completo, sus años de experiencia, títulos adjuntos e información profesional como su formación de pregrado, postgrado, número de colegio médico, registro nacional de especialista y la tarifa estándar</p>|Epic012|
|**US37**|Agendar cita con el médico especialista|Como paciente nuevo quiero ver y elegir el horario disponible del médico para poder agendar mi cita|<p>**Escenario 1:** Paciente nuevo que elige el horario disponible en el que tendrá su cita</p><p>**Dado que** soy un paciente recientemente registrado en la aplicación y ya escogí al médico luego de filtrarlo</p><p>**Cuando** hago clic sobre el botón de agendar cita</p><p>**Entonces** el sistema muestra despliega una interfaz en la que figura con un calendario los horarios más próximos en los que el médico estará disponible para agendar una cita </p>|Epic003|
|**US38**|Pago de cita|Como paciente quiero poder seleccionar el método de pago como tarjeta de débito/crédito, Yape o Plin para poder pagar y agendar mi cita |<p>**Escenario 1:** Paciente nuevo que escogió el horario disponible en el que tendrá su cita y quiere hacer el pago con tarjeta de débito/crédito.</p><p>**Dado que** soy un paciente recientemente registrado en la aplicación</p><p>**Y** ya escogí al médico luego de filtrarlo</p><p>**Y** ya escogí el horario</p><p>**Y** quiero proceder a hacer el pago</p><p>**Cuando** hago clic sobre el botón sobre el botón “Confirmar horario y hacer pago”</p><p>**Y** escojo el método de pago tarjeta de débito/crédito </p><p>**Y** completo los campos como número de la tarjeta, fecha de expiración, CVV, nombre y apellido, eMail y número de cuotas.</p><p>**Entonces** el sistema muestra una pantalla de Pago exitoso.</p><p>**Y** se agenda la cita en el calendario del paciente, así como en el calendario del médico.</p><p>**Escenario 2:** Paciente nuevo que escogió el horario disponible en el que tendrá su cita y quiere hacer el pago con Yape o Plin</p><p>**Dado que** soy un paciente recientemente registrado en la aplicación</p><p>**Y** ya escogí al médico luego de filtrarlo</p><p>**Y** ya escogí el horario</p><p>**Y** quiero proceder a hacer el pago</p><p>**Cuando** hago clic sobre el botón sobre el botón “Confirmar horario y hacer pago”</p><p>**Y** escojo el método de pago Yape o Plin</p><p>**Y** escaneo el código QR</p><p>**Entonces** el sistema muestra una pantalla de Pago exitoso.</p><p>**Y** se agenda la cita en el calendario del paciente, así como en el calendario del médico.</p>|Epic001|
|<p>**US39**</p><p></p><p></p><p></p><p></p><p></p><p></p><p></p>|Comunicación entre el paciente y el médico especialista|Como paciente, quiero poder comunicarme con mi doctor a través de un chat para poder hacer preguntas sobre mi enfermedad hormonal y su tratamiento|<p>Escenario 1: Paciente quiere comunicarse con el medico por alguna consulta medica</p><p>**Dado que** el paciente tiene una pregunta sobre su enfermedad hormonal,</p><p>**Cuando** inicia un chat con su médico en la aplicación,</p><p>**Y** envía un mensaje con su pregunta,</p><p>**Entonces** el médico recibe el mensaje y le responde dentro de las 24 horas.</p><p></p>|Epic006|
|**US40**|<p>Paciente accede a su perfil de usuario</p><p></p>|<p>Como paciente, quiero poder ver y editar mi perfil médico en la aplicación, para poder acceder a mi información médica de forma segura y cómoda.</p><p></p><p></p>|<p>Escenario 1: Paciente entra a su perfil de usuario para ver su informacion.</p><p>**Dado que** un paciente necesita ver su información médica,</p><p>**Cuando** inicia sesión en la aplicación,</p><p>**Y** accede a su interfaz de perfil de usuario</p><p>**Entonces** la aplicación muestra su nombre completo, correo, contraseña, foto, etc.</p><p>Escenario 2: El paciente quiere cambiar su información</p><p>**Dado que** un paciente necesita cambiar su información personal,</p><p>**Cuando** el paciente se encuentra en su perfil de usuario</p><p>**Y** presiona el boton de editar</p><p>**Entonces** la aplicación le muestra una interfaz donde cambiar el valor de su nombre, apellido, correo o contraseña.</p><p>**Y** puedo visualizar en mi calendario los medicamentes que debo tomar junto con la hora y dosis.</p>|Epic011|
|**US41**|Ver calendario paciente.|Como paciente, quiero poder ver mi calendario para revisar mis citas programadas y los medicamentes que debo tomar a qué hora.|<p>Escenario 1: Paciente quiere ver sus citas programadas</p><p>**Dado que** soy un paciente registrado en la aplicación</p><p>**Y** he programado una cita con un médico que he escogido hace tiempo</p><p>**Y** quiero poder ver cuando es la cita</p><p>**Cuando** estoy dentro de la aplicación, presiono el icono de calendario</p><p>**Entonces** puedo ver claramente todas mis citas programadas con el endocrinólogo, incluyendo la fecha, hora y motivo de cada cita.</p><p>Escenario 2: Paciente quiere revisar el horario de su medicación</p><p>Dado que soy un paciente con medicación activa </p><p>Y quiero revisar cuando debo tomar mi medicación</p><p>Cuando estoy en el interfaz del calendario</p><p>Entonces hago clic y filtro para solo ver los medicamentos que debo tomar en el calendario                                                                                                   </p>|Epic002|
|US42|Ver recordatorios de hoy.|<p>Como paciente, quiero poder visualizar todos los recordatorios programados para el día de hoy, para estár al tanto de mis compromisos médicos y de salud.</p><p></p>|<p>Escenario 1: Ver citas médicas programadas para hoy</p><p></p><p>Dado que soy un paciente con citas médicas que desea ver los recordatorios de medicamentos para el día de hoy,</p><p>Cuando accedo a la sección de recordatorios en la aplicación,</p><p>Entonces debo ver una lista clara y ordenada de todas las citas médicas programadas para hoy, incluyendo la hora de cada cita y el nombre del médico.</p><p></p><p>Escenario 2: Ver recordatorio de medicamentos para hoy</p><p></p><p>Dado que soy un paciente con recordatorios de medicamentos para el día de hoy,</p><p>Cuando accedo a la sección de recordatorios en la aplicación,</p><p>Entonces debo ver una lista clara y ordenada de todos los medicamentos que debo tomar hoy, incluyendo la hora específica para cada dosis si es relevante, así como el nombre del medicamento y cualquier instrucción adicional asociada.</p>|Epic007|
| :- | :- | :- | :- | :- |
|US43|Ver próximas citas.|Como paciente, quiero poder visualizar mis próximas citas médicas programadas, para poder estar preparado y organizado para mis consultas.|<p>Escenario 1: Ver mis próximas citas programadas</p><p></p><p>Dado que soy un paciente que desea visualizar sus próximas citas programadas en la aplicación</p><p>Cuando le de click a la opción de “Tu próxima cita”</p><p>Entonces podré observar todas mis próximas citas con el día, la hora exacta y el nombre del médico que me citó.</p><p></p><p>Escenario 2: Regresar a mis citas programadas para hoy</p><p></p><p>Dado que terminé de ver todas mis próximas citas programadas</p><p>Cuando le de click al botón de “Atrás”</p><p>Entonces regresaré a la visualización de mis recordatorios para el día de hoy</p>|Epic003|
|US44|Enlace de videoconferencias|Como médico quiero poder acceder a la videollamada programada para poder atender a mi paciente.|<p>Escenario 1: Acceder a la videollamada para la cita</p><p></p><p>Dado que soy un médico endocrinólogo registrado en la aplicación</p><p>Y me encuentro en la pestaña principal de la aplicación.</p><p>Cuando presione el ícono de videollamada junto a los tados de un paciente en específico dentro de la hora programada para cita y dentro de la sección Pacientes de hoy</p><p>Entonces el sistema debe abrir un link vinculado a Google Meet  en el que pueda acceder a la videollamada con mi paciente</p>|Epic003|
|US45|Subir mis exámenes|Como paciente, quiero poder subir mis resultados de exámenes médicos en la aplicación de manera segura y sencilla para que mi médico pueda acceder a ellos y revisarlos cuando sea necesario.|<p>Escenario 1: Visualizar lista de exámenes pendientes</p><p></p><p>Dado que soy un paciente registrado en la aplicación</p><p>Y deseo visualizar que examenes medicos tengo pendientes para subir</p><p>Cuando le de click al botón de “Sube tus exámenes”</p><p>Entonces podré observar una lista de los exámenes médico que tengo pendiente </p><p></p><p>Escenario 2: Subir examen médico</p><p></p><p>Dado que deseo subir los resultados de un examen médico</p><p>Y me encuentro dentro de la opción de “Sube tus exámenes”</p><p>Cuando me dirige al examen que deseo subir dandole click al recuadro de “subir”</p><p>Entonces debo poder seleccionar el archivo de mi examen desde mi dispositivo local y cargarlo con éxito en la aplicación</p><p></p><p>Escenario 3: Verificar carga exitosa del examen médico</p><p></p><p>Dado que he subido un examen médico a la aplicación</p><p>Cuando me dirige a la opción de “subir examen” nuevamente</p><p>Entonces el examen que acabo de subir estará tachado.</p><p></p>|Epic005|
|US46|Ver notificaciones|Como paciente, quiero poder recibir notificaciones sobre mensajes enviados por mi médico, para mantenerme informado sobre cualquier comunicación relevante relacionada con mi atención médica.|<p>Escenario 1: Recibir notificación de nuevo mensaje de médico</p><p></p><p>Dado que soy un paciente registrado en la aplicación</p><p>Cuando un nuevo mensaje es enviado por mi médico a través de la aplicación,</p><p>Entonces debo recibir una notificación clara y visible en la página web indicando que tengo un nuevo mensaje</p><p></p><p>Escenario 2: Acceder a notificación de mensaje de médico</p><p></p><p>Dado que soy un paciente y he recibido una notificación sobre un nuevo mensaje de mi médico,</p><p>Cuando accedo a la sección de mensajes en la aplicación</p><p>Entonces debo poder ver una lista de todos los mensajes recibidos junto a otras notificaciones como recordatorios de mis citas y pastillas.</p><p></p>|Epic007|
|US47|Visualización de la Historia Clínica del paciente por parte del médico|Como médico quiero poder visualizar una historia clínica con campos como datos del paciente, motivo de consulta, antecedentes, exámenes médicos, reportes externos y diagnósticos y tratamiento, vinculada al paciente para poder tener un registro del paciente y brindar una mejor atención|<p>Escenario 1: Médico quiere visualizar los datos médicos del paciente.</p><p></p><p>Dado que un médico endocrinólogo registrado en la aplicación se encuentra en su página principal</p><p>Cuando haga clic en ver la Historia clínica de uno de mis pacientes de mi cartera dentro de la pestaña principal.</p><p>Entonces el sistema mostrará los datos clínicos principales del paciente en el panel izquierdo de la interfaz.</p><p></p><p>Escenario 2: Médico quiere visualizar los antecedentes, razón de consulta, exámenes médicos,reportes externos y diagnósticos y tratamientos.</p><p></p><p>Dado que un médico endocrinólogo registrado en la aplicación se encuentra en su página principal</p><p>Cuando haga clic en ver la Historia clínica de uno de mis pacientes de mi cartera dentro de la pestaña principal.</p><p>Entonces el sistema mostrará los antecedentes, razón de consulta, exámenes médicos,reportes externos y diagnósticos y tratamientos del paciente en los distintos paneles derechos de la interfaz.</p>|Epic005|
|US48|Ingreso de información y edición de la historia clínica del paciente por parte del médico|Como médico quiero poder ingresar y editar la información de la historia clínica de mi paciente para poder tener la información actualizada de la historia clínica.|<p>Escenario 1: Médico quiere editar la razón de consulta de la historia clínica.</p><p></p><p>Dado que un médico endocrinólogo registrado en la aplicación se encuentra en la historia clínica del paciente</p><p>Cuando haga clic en la pestaña “Razón de consulta” en el panel derecho.</p><p>Y haga clic en el botón editar</p><p>Entonces el sistema le permitirá editar la información exitente o ingresar nueva información del campo en cuestión y de la sintomatología.</p><p></p><p>Escenario 2: Médico quiere editar los antecedentes de la historia clínica.</p><p></p><p>Dado que un médico endocrinólogo registrado en la aplicación se encuentra en la historia clínica del paciente</p><p>Cuando haga clic en la pestaña “Antecedentes” en el panel derecho.</p><p>Y haga clic en el botón editar</p><p>Entonces el sistema le permitirá editar la información exitente o ingresar nueva información en los campos de Antecedentes personales y antecedentes familiares.</p><p></p><p>Escenario 3: Médico quiere editar la sección de exámenes físicos de la historia clínica.</p><p></p><p>Dado que un médico endocrinólogo registrado en la aplicación se encuentra en la historia clínica del paciente</p><p>Cuando haga clic en la pestaña “Exámenes medicos” en el panel derecho.</p><p>Y haga clic en el botón editar de la sección “Examen físico”</p><p>Entonces el sistema le permitirá editar la información exitente o ingresar nueva información.</p><p></p><p></p><p></p>|Epic005|
|US49|Diagnóstico y tratamiento|Como médico quiero poder añadir Diagnósticos y tratamiento a mi paciente para tener un registro detallado de su evolución. |<p>Escenario 1: Médico quiere añadir un nuevo tratamiento y medicación a su paciente.</p><p></p><p>Dado que un médico endocrinólogo registrado en la aplicación se encuentra en la historia clínica del paciente</p><p>Cuando haga clic en la pestaña “Diagnósticos y tratamiento” en el panel derecho.</p><p>Y haga clic en el botón “Añadir” de la sección Tratamiento y medicación.</p><p>Entonces el sistema abrirá una pestaña que le permitirá añadir información sobre el tratamiento y poder añadir medicación con campos como el nombre del medicamento, cantidad, concentración y frecuecia en horas.</p><p></p><p>Escenario 2: Médico quiere añadir un nuevo Diagnóstico a su paciente</p><p></p><p>Dado que un médico endocrinólogo registrado en la aplicación se encuentra en la historia clínica del paciente</p><p>Cuando haga clic en la pestaña “Diagnósticos y tratamiento” en el panel derecho.</p><p>Y haga clic en el botón “Añadir” de la sección Diagnóstico</p><p>Entonces el sistema abrirá una pestaña que le permitirá añadir información sobre el nuevo Diagnóstico.</p>|Epic005|
|US50|Añadir medicación|Como médico quiero poder añadir una receta médica vinculada a la medicación para facilitar al paciente la obtención del medicamento.|<p>Escenario 1: Médico quiere añadir una receta médica para su paciente</p><p></p><p>Dado que un médico endocrinólogo registrado en la aplicación se encuentra en la historia clínica del paciente</p><p>Cuando haga clic en la pestaña “Añadir tratamiento y medicación”</p><p>Y haga clic en el botón “Añadir receta médica” </p><p>Entonces el sistema abrirá una pestaña que le permitirá subir un archivo con la receta médica firmada por el paciente</p><p>Y le llegará una notifiación al paciente para que pueda descargarla y adquirir el medicamento.</p><p></p>|Epic005|

### 3.3. Impact Mapping.

<img src="images/impac mapping.png" alt="impac mapping">

### 3.4. Product Backlog.
Para elaborar nuestro product backlog hemos utilizado la escala Fibonacci (1,2,3,5…). Además, la Historia de usuario base elegida por el grupo es US016, ya que como grupo consideramos que su nivel de complejidad, frecuencia y riesgo son intermedios.

|#Orden|User Story Id|Titulo|Descripción|Story points (1/2/3/5/8)|
| - | - | - | - | - |
|01|US01|Visualización del Header.  |Como como visitante deseo observar un header con varias secciones para conocer más sobre el producto.|3|
|02|US02|Información sobre Planes o Suscripciones.|Como como visitante deseo observar una sección con información de los planes o suscripciones de la app para elegir el que mejor se ajusta a mi situación.|2|
|03|US03|Visualización del footer en la landing page.|Como visitante, quiero acceder rápidamente a información relevante sobre la aplicación para informarme o revisar información adicional.|1|
|04|US04|Conocer la misión y visión de la aplicación.|Como visitante deseo conocer más sobre la misión, visión y valores de la empresa detrás de la aplicación.|5|
|05|US05|Comunicación directa con el equipo de soporte.|Como visitante de la aplicación, deseo poder comunicarme directamente con el equipo de soporte para solucionar problemas técnicos o comentarios sobre la plataforma.|2|
|06|US09|Integración de Google Meet para citas médicas virtuales	|<p>Como desarrollador,</p><p>Necesito integrar Google Meet en nuestra aplicación médica</p><p>Para permitir citas médicas virtuales entre pacientes y doctores.</p>|5|
|07|US10|Registro de usuario.|Como usuario de "HormonalCare" quiero poder registrarme en la aplicación para guardar mi cuenta en la plataforma.|1|
|08|US14|Agendar cita con médico endocrinólogo para usuarios totalmente nuevos.|Como paciente quiero poder agendar una cita con un médico endocrinólogo que me parezca adecuado tanto en precio como en calificación para poder recibir el tratamiento de mi enfermedad hormonal de manera remota.|3|
|09|US25|Agendar una cita con el paciente.|Como médico quiero agendar una cita médica a un paciente que ya se atiende conmigo para continuar con el tratamiento.|3|
|10|US31|Asignación de Paciente a Otro Médico con Programación de Cita por parte del Médico.|Como médico, cuando estoy visualizando el perfil de otro médico en la plataforma y deseo asignarle un paciente, quiero tener la capacidad de seleccionar al paciente deseado y luego ver los horarios disponibles del médico para programar una cita con el paciente asignado.|5|
|11|US37|Agendar cita con el médico especialista	|Como paciente nuevo quiero ver y elegir el horario disponible del médico para poder agendar mi cita|3|
|12|US43|Ver próximas citas.|Como paciente, quiero poder visualizar mis próximas citas médicas programadas, para poder estar preparado y organizado para mis consultas.|5|
|13|US44|Enlace de videoconferencias|Como médico quiero poder acceder a la videollamada programada para poder atender a mi paciente.|3|
|14|US08|Integración de Google Calendar para visualizar citas médicas y medicamentos.|<p>Como desarrollador,</p><p>Necesito integrar Google Calendar en nuestra aplicación médica</p><p>Para permitir que los usuarios visualicen sus citas médicas programadas y los horarios de medicación.</p>|5|
|15|US11|Inicio de sesión con cuenta de HormonalCare|Como usuario de "HormonalCare" quiero iniciar sesión con mi cuenta registrada para acceder a mis configuraciones de forma rápida y segura.|1|
|16|US12|Selección de Rol|Como usuario de "HormonalCare" deseo poder elegir el rol de paciente o médico para utilizar la app según mis necesidades.|2|
|17|US18|Médico asigna a paciente y programa una cita con un colega.|Como medico quiero poder realizar un traslado de paciente a otro médico para que pueda tener un horario más flexible.|3|
|18|US20|Ver lista de pacientes del día.|Como médico deseo ver los pacientes del día para tener una cita médica más eficiente.|1|
|19|US27|Visualización y Gestión de Horario por parte del Médico.|Como médico, quiero poder ver mi horario con eventos programados y tener la capacidad de crear nuevos eventos según sea necesario, para organizar eficientemente mis actividades diarias y administrar mi agenda profesional de manera efectiva.|5|
|20|US41|Ver calendario paciente.|Como paciente, quiero poder ver mi calendario para revisar mis citas programadas y los medicamentes que debo tomar a qué hora.|3|
|21|US13|Recuperación de contraseña|Como usuario de "HormonalCare" quiero recuperar mi contraseña para mantener mi cuenta.|3|
|22|` `US15|Subir resultados de exámenes médicos de laboratorio por parte del paciente.|Como paciente quiero poder cargar mis resultados de laboratorio para que mi medico los lea y me recete un determinado tratamiento para mi enfermedad hormonal.|1|
|23|US19|Ver información detallada de los pacientes.|Como medico quiero poder tener de manera organizada los resultados de mis pacientes para que pueda llevar un registro más detallado de su tratamiento.|3|
|24|US23|Ver la medicación del paciente.|Como médico quiero ver la medicación dispuesta a cada paciente para verificar o cambiar la receta médica.|3|
|25|US24|Ver los exámenes a evaluar.|Como médico deseo observar los exámenes que tengo que evaluar de cada paciente para personalizar su tratamiento.	|3|
|26|US29|Ver el historial médico de un paciente.	|Como médico deseo ver el historial médico de mi paciente para garantizar un tratamiento óptimo.|5|
|27|US06|Integración de Twilio para comunicación por chat entre pacientes y doctores.|<p>Como desarrollador,</p><p>Necesito integrar Twilio en nuestra aplicación médica</p><p>Para permitir la comunicación por chat entre pacientes y doctores.</p>|8|
|28|US45|Subir mis exámenes.|Como paciente, quiero poder subir mis resultados de exámenes médicos en la aplicación de manera segura y sencilla para que mi médico pueda acceder a ellos y revisarlos cuando sea necesario.	|3|
|29|US50|Añadir medicación.|Como médico quiero poder añadir una receta médica vinculada a la medicación para facilitar al paciente la obtención del medicamento.|2|
|30|US49|Diagnóstico y tratamiento.|Como médico quiero poder añadir Diagnósticos y tratamiento a mi paciente para tener un registro detallado de su evolución.|3|
|31|US48|Ingreso de información y edición de la historia clínica del paciente por parte del médico.|Como médico quiero poder ingresar y editar la información de la historia clínica de mi paciente para poder tener la información actualizada de la historia clínica.|1|
|32|US47|Visualización de la Historia Clínica del paciente por parte del médico.|Como médico quiero poder visualizar una historia clínica con campos como datos del paciente, motivo de consulta, antecedentes, exámenes médicos, reportes externos y diagnósticos y tratamiento, vinculada al paciente para poder tener un registro del paciente y brindar una mejor atención|1|
|33|US40|Paciente accede a su perfil de usuario.|Como paciente, quiero poder ver y editar mi perfil médico en la aplicación, para poder acceder a mi información médica de forma segura y cómoda.	|2|
|34|US35|Filtrar médicos disponibles.|Como paciente nuevo en la aplicación quiero poder visualizar a todos los médicos disponibles y poder filtrarlos por campos como su sexo, subespecialidad, recomendaciones, experiencia y rango de tarifas para tomar elegir al mejor doctor de acuerdo con mis preferencias.|3|
|35|US33|Buscador de colegas médicos.|Como médico quiero buscar a mis colegas gestionar un seguimiento conjunto de los pacientes.|2|
|36|US28|Búsqueda y Visualización de Perfiles de Otros Médicos por parte del Médico.|Como médico, quiero poder buscar a otro médico en la plataforma desde la página principal, para visualizar su perfil con sus datos personales y tener la capacidad de enviar mensajes y asignar pacientes según sea necesario.|3|
|37|US16|Usuario se registra como paciente con código que un médico le proporcionó.|Como paciente quiero poder registrarme con el código que me proporciono mi medico endocrinólogo para que sea él quien lleve mi tratamiento de manera remota.|3|
|38|US17|Cambiar plan de suscripción de médico desde su perfil de usuario.|Como medico quiero poder cambiar mi plan de suscripción actual para poder atender a una mayor cartera de clientes.|3|
|39|US07|Integración de Twilio para notificaciones en la aplicación médica.|<p>Como desarrollador,</p><p>Necesito integrar Twilio en nuestra aplicación médica</p><p>Para enviar notificaciones importantes a pacientes y doctores.</p>|5|
|40|US21|Comunicación directa con el paciente.|Como médico quiero comunicarme de forma directa con el paciente para resolver consultas.|5|
|41|US22|Notificaciones a médicos de las citas.	|Como médico deseo recibir notificaciones de las citas para prepárame mejor.|3|
|42|US26|Edición de Perfil por parte del Médico.|Como médico, quiero poder acceder y editar mi perfil en la plataforma para mantener actualizada mi información profesional.|2|
|43|US29|Ver el historial médico de un paciente.|Como médico deseo ver el historial médico de mi paciente para garantizar un tratamiento óptimo.|3|
|44|US30|Acceso al Chat desde el Perfil de Otro Médico por parte del Médico.|Como médico, cuando estoy visualizando el perfil de otro médico en la plataforma, quiero tener la capacidad de iniciar un chat directo con ese médico para enviarle mensajes de forma rápida y directa.|3|
|45|US32|Cancelación de Plan de Suscripción desde el Perfil por parte del Médico.	|Como médico, cuando estoy en mi perfil en la plataforma, quiero tener la capacidad de gestionar mi plan de suscripción, para cancelar la suscripción si así lo deseo.|2|
|46|US36|Selección de médico disponible.|Como paciente nuevo quiero poder ver el perfil del médico elegido con campos como su nombre completo, sus años de experiencia, títulos adjuntos e información profesional como su formación de pregrado, postgrado, número de colegio médico, registro nacional de especialista y la tarifa estándar para informarme sobre las bondades de su servicio.|1|
|47|US38|Pago de cita.|Como paciente quiero poder seleccionar el método de pago como tarjeta de débito/crédito, Yape o Plin para poder pagar y agendar mi cita.|5|
|48|US39|Comunicación entre el paciente y el médico especialista.|Como paciente, quiero poder comunicarme con mi doctor a través de un chat para poder hacer preguntas sobre mi enfermedad hormonal y su tratamiento.|5|
|49|US42|Ver recordatorios de hoy.|Como paciente, quiero poder visualizar todos los recordatorios programados para el día de hoy, para estar al tanto de mis compromisos médicos y de salud.|2|
|50|US46|Ver notificaciones.|Como paciente, quiero poder recibir notificaciones sobre mensajes enviados por mi médico, para mantenerme informado sobre cualquier comunicación relevante relacionada con mi atención médica.|3|

**Asimismo, se adjunta el enlace del product backlog en la herramienta indicada.**
<img src="images/Product Backlog en Trello.png" >
[Enlace product Backlog en Trello](https://trello.com/invite/b/66EkeO8t/ATTI7681f5c932b9217761b0224c0051dd4cC0E965E5/aplicaciones-web-hormonalcare) 

