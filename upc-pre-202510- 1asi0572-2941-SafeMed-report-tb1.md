# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

### 1.1.2. Perfiles de integrantes del equipo

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

### 1.2.2 Lean UX Process.

#### 1.2.2.1. Lean UX Problem Statements.

#### 1.2.2.2. Lean UX Assumptions.

#### 1.2.2.3. Lean UX Hypothesis Statements.

#### 1.2.2.4. Lean UX Canvas.

## 1.3. Segmentos objetivo.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores.

### 2.1.1. Análisis competitivo.

### 2.1.2. Estrategias y tácticas frente a competidores.

## 2.2. Entrevistas.

### 2.2.1. Diseño de entrevistas.

### 2.2.2. Registro de entrevistas.

### 2.2.3. Análisis de entrevistas.

## 2.3. Needfinding.

### 2.3.1. User Personas.

### 2.3.2. User Task Matrix.

### 2.3.3. User Journey Mapping.

### 2.3.4. Empathy Mapping.

### 2.3.5. As-is Scenario Mapping.

## 2.4. Ubiquitous Language.

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.

## 3.2. User Stories.

#### - Epics

| Epic ID | Título                                           | Descripción                                                                                                                                                                                           |
| ------- | ------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01      | Monitoreo en tiempo real del ritmo cardiaco      | Como doctor, quiero poder visualizar en una plataforma web el ritmo cardiaco de mis pacientes en tiempo real, para estar al tanto de cualquier irregularidad y actuar de manera oportuna.             |
| 02      | Alerta automática por ritmo cardiaco elevado     | Como doctor, quiero recibir una alerta automática en la plataforma web cuando el ritmo cardiaco de un paciente sea irregular y poder mandar una ambulancia a su ubicacion.                            |
| 03      | Notificación por SMS a contacto de emergencia    | Como paciente, quiero que un familiar o contacto de emergencia reciba un mensaje SMS si mi ritmo cardiaco presenta una anomalía, para que puedan ayudarme rápidamente.                                |
| 04      | Aplicación móvil para pacientes                  | Como paciente, quiero tener una aplicación móvil donde pueda monitorear mi ritmo cardiaco, visualizar alertas y gestionar mis citas médicas, para tener control sobre mi salud desde cualquier lugar. |
| 05      | Gestión de citas médicas entre paciente y doctor | Como paciente, quiero poder agendar citas médicas desde mi app móvil, y como doctor quiero visualizarlas desde la plataforma web, para organizar mejor el seguimiento clínico.                        |

### - User Stories

### Epic 01 - Monitoreo en tiempo real del ritmo cardiaco

| US  | Título                                   | Descripción                                                                                                                                     | Criterios de aceptación                                                                                                                                                                                                                                            | Epic relacionada |
| --- | ---------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------- |
| 01  | Visualizar ritmo cardiaco en tiempo real | Como doctor, quiero poder ver el ritmo cardiaco actual de mis pacientes en una interfaz web, para monitorear su estado de salud constantemente. | **Escenario 1:** Acceso al monitoreo en tiempo real <br> **Dado** que estoy logueado como doctor, <br> **Cuando** ingreso a la sección de monitoreo cardiaco, <br> **Entonces** puedo ver una gráfica en tiempo real del ritmo cardiaco del paciente seleccionado. | 01               |
| 02  | Seleccionar paciente para monitoreo      | Como doctor, quiero poder seleccionar un paciente específico, para ver únicamente su información de ritmo cardiaco.                             | **Escenario:** Filtro de paciente <br> **Dado** que tengo varios pacientes asignados, <br> **Cuando** selecciono uno en la lista, <br> **Entonces** solo veo el ritmo cardiaco de ese paciente en la gráfica.                                                      | 01               |
| 03  | Actualización automática de datos        | Como doctor, quiero que la información del ritmo cardiaco se actualice automáticamente, para no tener que refrescar la página.                  | **Escenario:** Actualización continua <br> **Dado** que estoy viendo la gráfica, <br> **Cuando** pasan unos segundos, <br> **Entonces** los valores deben actualizarse sin intervención manual.                                                                    | 01               |
| 04  | Ver estado de conexión del sensor        | Como doctor, quiero saber si el sensor del paciente está enviando datos correctamente, para asegurarme de que la información sea confiable.     | **Escenario:** Indicador de conexión <br> **Dado** que estoy monitoreando a un paciente, <br> **Cuando** el sensor esté desconectado o sin datos, <br> **Entonces** debo ver un mensaje de advertencia.                                                            | 01               |

---

### Epic 02 - Alerta automática por ritmo elevado

| US  | Título                         | Descripción                                                                                                                               | Criterios de aceptación                                                                                                                                                                            | Epic relacionada |
| --- | ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- |
| 01  | Alerta visual en la interfaz   | Como doctor, quiero recibir una alerta visual en la pantalla si el ritmo cardiaco de un paciente es elevado, para reaccionar rápidamente. | **Escenario:** Activación de alerta <br> **Dado** que monitoreo a un paciente, <br> **Cuando** su ritmo cardiaco supere un umbral crítico, <br> **Entonces** una alerta debe aparecer en pantalla. | 02               |
| 02  | Configurar umbrales de alerta  | Como doctor, quiero poder configurar los valores máximos y mínimos del ritmo cardiaco, para personalizar las alertas según el paciente.   | **Escenario:** Edición de umbrales <br> **Dado** que estoy visualizando un paciente, <br> **Cuando** ingreso a la configuración, <br> **Entonces** puedo definir sus límites de alerta.            | 02               |
| 03  | Alerta sonora opcional         | Como doctor, quiero poder activar una alarma sonora al recibir una alerta, para no perderme ninguna notificación urgente.                 | **Escenario:** Alarma activada <br> **Dado** que tengo una alerta activa, <br> **Cuando** la opción de sonido está activada, <br> **Entonces** escucho una alarma.                                 | 02               |
| 04  | Registro de alertas anteriores | Como doctor, quiero revisar las alertas previas que ha generado un paciente, para entender mejor sus antecedentes.                        | **Escenario:** Revisión de historial <br> **Dado** que selecciono un paciente, <br> **Cuando** accedo a su historial de alertas, <br> **Entonces** puedo ver fechas, horas y tipos de alerta.      | 02               |

---

### Epic 03 - Notificación por SMS a contacto asignado

| US  | Título                             | Descripción                                                                                                                                                                                                               | Criterios de aceptación                                                                                                                                                                                                             | Epic relacionada |
| --- | ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- |
| 01  | Registrar contacto de emergencia   | Como paciente, quiero poder registrar a una persona de contacto en la aplicación, para que reciba alertas por SMS si ocurre una emergencia.                                                                               | **Escenario:** Registro de contacto <br> **Dado** que estoy en mi perfil de paciente, <br> **Cuando** ingreso los datos del contacto de emergencia, <br> **Entonces** estos quedan guardados y vinculados a mi cuenta.              | 03               |
| 02  | Envío automático de SMS en alerta  | Como paciente, quiero que se envíe un mensaje SMS automáticamente a mi contacto registrado cuando se detecte un ritmo cardiaco elevado, para asegurarme de que alguien de confianza sea notificado en caso de emergencia. | **Escenario:** Activación de SMS <br> **Dado** que mi ritmo cardiaco excede el umbral, <br> **Cuando** se detecta esta condición, <br> **Entonces** se debe enviar automáticamente un SMS al contacto que registré previamente.     | 03               |
| 03  | Personalizar mensaje de emergencia | Como paciente, quiero poder personalizar el contenido del mensaje SMS, para que el contacto entienda mejor la situación.                                                                                                  | **Escenario:** Edición del mensaje <br> **Dado** que estoy configurando la función de emergencia, <br> **Cuando** ingreso el texto personalizado, <br> **Entonces** ese mensaje será el que se envíe al contacto en caso de alerta. | 03               |
| 04  | Ver historial de mensajes enviados | Como paciente, quiero revisar los SMS que han sido enviados por el sistema, para tener un registro de las alertas enviadas a mi contacto.                                                                                 | **Escenario:** Consulta de historial <br> **Dado** que accedo a la sección de emergencias, <br> **Cuando** reviso el historial, <br> **Entonces** puedo ver la fecha, hora y contenido del mensaje enviado.                         | 03               |

---

### Epic 04 - Aplicación móvil para pacientes

| US  | Título                                | Descripción                                                                                                                            | Criterios de aceptación                                                                                                                                                                                                | Epic relacionada |
| --- | ------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- |
| 01  | Visualizar datos personales y médicos | Como paciente, quiero poder ver mis datos personales y médicos en la app, para tener control sobre mi información.                     | **Escenario:** Acceso a perfil <br> **Dado** que estoy logueado en la app móvil, <br> **Cuando** accedo a la sección "Mi perfil", <br> **Entonces** puedo visualizar mis datos personales y médicos actualizados.      | 04               |
| 02  | Ver ritmo cardiaco desde el celular   | Como paciente, quiero poder ver mi ritmo cardiaco actual desde la aplicación móvil, para monitorear mi estado de salud.                | **Escenario:** Visualización en tiempo real <br> **Dado** que tengo el sensor conectado, <br> **Cuando** ingreso a la app, <br> **Entonces** puedo ver una gráfica con mi ritmo cardiaco actual.                       | 04               |
| 03  | Recibir notificaciones de alerta      | Como paciente, quiero recibir notificaciones push si se detecta un ritmo anormal, para estar informado de cualquier cambio importante. | **Escenario:** Notificación activa <br> **Dado** que mi ritmo cardiaco supera el límite, <br> **Cuando** se detecta la anomalía, <br> **Entonces** recibo una alerta en el teléfono móvil.                             | 04               |
| 04  | Solicitar soporte desde la app        | Como paciente, quiero poder solicitar ayuda o soporte desde la app móvil, para resolver problemas con el uso del sistema.              | **Escenario:** Enviar solicitud de ayuda <br> **Dado** que tengo un inconveniente, <br> **Cuando** ingreso a la sección de soporte y lleno el formulario, <br> **Entonces** mi solicitud es enviada al equipo técnico. | 04               |

---

### Epic 05 - Gestión de citas médicas desde la app

| US  | Título                               | Descripción                                                                                                                 | Criterios de aceptación                                                                                                                                                                                                        | Epic relacionada |
| --- | ------------------------------------ | --------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------- |
| 01  | Agendar una cita desde la app        | Como paciente, quiero poder agendar una cita médica desde mi aplicación móvil, para facilitar la programación de consultas. | **Escenario:** Crear nueva cita <br> **Dado** que estoy en la app móvil, <br> **Cuando** ingreso a la sección de citas y selecciono una fecha y hora, <br> **Entonces** se agenda la cita en el sistema.                       | 05               |
| 02  | Ver citas programadas                | Como paciente, quiero consultar mis citas futuras, para saber cuándo debo asistir a consulta.                               | **Escenario:** Consultar agenda <br> **Dado** que tengo citas agendadas, <br> **Cuando** ingreso a la sección de citas, <br> **Entonces** puedo ver la lista de fechas, horas y médicos asignados.                             | 05               |
| 03  | Cancelar o reprogramar una cita      | Como paciente, quiero poder cancelar o reprogramar una cita, para reorganizar mi agenda si tengo algún imprevisto.          | **Escenario:** Modificar cita <br> **Dado** que tengo una cita agendada, <br> **Cuando** accedo a su detalle, <br> **Entonces** puedo modificar la fecha/hora o cancelar si es necesario.                                      | 05               |
| 04  | Sincronización con agenda del doctor | Como doctor, quiero ver las citas programadas por los pacientes desde la app web, para organizar mejor mi horario.          | **Escenario:** Visualización de agenda <br> **Dado** que los pacientes agendan citas desde la app, <br> **Cuando** ingreso a la sección de agenda como doctor, <br> **Entonces** veo todas las citas asignadas en tiempo real. | 05               |

## 3.3. Impact Mapping.

## 3.4. Product Backlog.

| Orden | Epic ID | User Story ID | Título                                   | Descripción                                                                                                                  | Story Points |
| ----- | ------- | ------------- | ---------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ------------ |
| 1     | EP01    | US01          | Visualizar ritmo cardiaco en tiempo real | Como doctor, quiero visualizar el ritmo cardiaco de mis pacientes en tiempo real, para monitorear su estado de salud.        | 5            |
| 2     | EP01    | US02          | Seleccionar paciente para monitoreo      | Como doctor, quiero seleccionar a un paciente específico, para revisar únicamente su información de ritmo cardiaco.          | 3            |
| 3     | EP01    | US03          | Actualización automática de datos        | Como doctor, quiero que los datos del ritmo cardiaco se actualicen automáticamente, para evitar tener que recargar la vista. | 3            |
| 4     | EP01    | US04          | Ver estado de conexión del sensor        | Como doctor, quiero saber si el sensor está enviando datos correctamente, para garantizar que el monitoreo es fiable.        | 2            |
| 5     | EP02    | US01          | Alerta visual en la interfaz             | Como doctor, quiero recibir una alerta visual si un paciente presenta un ritmo elevado, para poder actuar de inmediato.      | 5            |
| 6     | EP02    | US02          | Configurar umbrales de alerta            | Como doctor, quiero configurar los umbrales máximos y mínimos del ritmo cardiaco, para adaptar el sistema a cada paciente.   | 3            |
| 7     | EP02    | US03          | Alerta sonora opcional                   | Como doctor, quiero activar una alarma sonora junto con la visual, para no perderme ninguna alerta urgente.                  | 2            |
| 8     | EP02    | US04          | Registro de alertas anteriores           | Como doctor, quiero revisar las alertas anteriores de un paciente, para tener un historial de sus eventos críticos.          | 3            |
| 9     | EP03    | US01          | Registrar contacto de emergencia         | Como paciente, quiero registrar un contacto de emergencia, para que sea notificado si tengo una emergencia cardiaca.         | 3            |
| 10    | EP03    | US02          | Envío automático de SMS en alerta        | Como paciente, quiero que se envíe un SMS automático a mi contacto en caso de ritmo elevado, para que me ayuden rápido.      | 5            |
| 11    | EP03    | US03          | Personalizar mensaje de emergencia       | Como paciente, quiero personalizar el mensaje SMS de alerta, para que mi contacto entienda mejor la situación.               | 2            |
| 12    | EP03    | US04          | Ver historial de mensajes enviados       | Como paciente, quiero ver los SMS que se han enviado a mi contacto, para llevar un registro de las alertas.                  | 2            |
| 13    | EP04    | US01          | Visualizar datos personales y médicos    | Como paciente, quiero ver mis datos médicos y personales en la app, para tener acceso a mi información de salud.             | 2            |
| 14    | EP04    | US02          | Ver ritmo cardiaco desde el celular      | Como paciente, quiero visualizar mi ritmo cardiaco actual en la app móvil, para monitorear mi estado de salud.               | 5            |
| 15    | EP04    | US03          | Recibir notificaciones de alerta         | Como paciente, quiero recibir notificaciones push si tengo un ritmo cardiaco anormal, para estar al tanto de emergencias.    | 3            |
| 17    | EP05    | US01          | Agendar una cita desde la app            | Como paciente, quiero agendar citas médicas desde la app móvil, para facilitar la planificación de mis consultas.            | 3            |
| 18    | EP05    | US02          | Ver citas programadas                    | Como paciente, quiero ver mis citas médicas futuras, para no olvidar mis consultas.                                          | 2            |
| 19    | EP05    | US03          | Cancelar o reprogramar una cita          | Como paciente, quiero modificar o cancelar una cita desde la app, para gestionar mejor mi agenda.                            | 3            |
| 20    | EP05    | US04          | Sincronización con agenda del doctor     | Como doctor, quiero ver las citas que agendan mis pacientes, para tener mi agenda médica organizada.                         | 3            |

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design.

### 4.1.1. EventStorming.

#### 4.1.1.1 Candidate Context Discovery.

#### 4.1.1.2 Domain Message Flows Modeling.

#### 4.1.1.3 Bounded Context Canvases.

### 4.1.2. Context Mapping.

### 4.1.3. Software Architecture.

#### 4.1.3.1. Software Architecture System Landscape Diagram.

#### 4.1.3.2. Software Architecture Context Level Diagrams.

#### 4.1.3.2. Software Architecture Container Level Diagrams.

#### 4.1.3.3. Software Architecture Deployment Diagrams.

## 4.2. Tactical-Level Domain-Driven Design

### 4.2.X. Bounded Context: <Bounded Context Name>

#### 4.2.X.1. Domain Layer.

#### 4.2.X.2. Interface Layer.

#### 4.2.X.3. Application Layer.

#### 4.2.X.4. Infrastructure Layer.

#### 4.2.X.5. Bounded Context Software Architecture Component Level Diagrams.

#### 4.2.X.6. Bounded Context Software Architecture Code Level Diagrams.

#### 4.2.X.6.1. Bounded Context Domain Layer Class Diagrams.

#### 4.2.X.6.2. Bounded Context Database Design Diagram.
