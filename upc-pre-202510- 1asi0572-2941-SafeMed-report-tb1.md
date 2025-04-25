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

## 3.3. Impact Mapping.

## 3.4. Product Backlog.

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design.

### 4.1.1. EventStorming.
Dentro de este punto nos encontramos con estos 9 pasos a realizar:

**Step 1: Unstructured Exploration**

En este paso, se detectaron los siguientes puntos, los cuales posteriormente fueron utilizados dentro del sistema.

<img src="CAP4-IMAGES/EventStorming-Step-1.jpg" alt="Step1">

**Step 2: Timelines:**

En este paso se realizaron las distintas conexiones entre eventos del flujo de la aplicación.

<img src="CAP4-IMAGES/EventStorming-Step-2.jpg" alt="Step2">


**Step 3: Pain points**

En este paso se colocaron los eventos críticos y sus respectivos pain events identificados.

<img src="CAP4-IMAGES/EventStorming-Step-3.jpg" alt="Step3">

**Step 4: Pivotal points**

En este paso se incluyeron los pivotal points dentro del flujo de la aplicación.

<img src="CAP4-IMAGES/EventStorming-Step-4.jpg" alt="Step4">

**Step 5: Commands**
En este paso se identificó los comandos realizados por sus respectivos actores.

<img src="CAP4-IMAGES/EventStorming-Step-5.jpg" alt="Step5">

**Step 6: Policies**
En este paso se incluyeron las políticas, escenarios donde la aplicación ejecuta alguna acción.

<img src="CAP4-IMAGES/EventStorming-Step-6.jpg" alt="Step6">

**Step 7: Read Models**
En este paso se realizó el modelo de lectura de cada sistema de la aplicación.

<img src="CAP4-IMAGES/EventStorming-Step-7.jpg" alt="Step7">

**Step 8: External systems**
En este paso se identificaron algunos sistemas externos.

<img src="CAP4-IMAGES/EventStorming-Step-8.jpg" alt="Step8">

**Step 9: Aggregates**
En este paso se implementan los agregados de cada sistema de la aplicación.

<img src="CAP4-IMAGES/EventStorming-Step-9.jpg" alt="Step9">

#### 4.1.1.1 Candidate Context Discovery.

En este punto luego de la realización del Event storming, se identificaron los bounded context a trabajar. En este caso se lograron identificar 6.

<img src="CAP4-IMAGES/IAM.jpg" alt="IAM">

<img src="CAP4-IMAGES/Patient management.jpg" alt="Patient management">

<img src="CAP4-IMAGES/Medical history & analytics.jpg" alt="Medical history & analytics">

<img src="CAP4-IMAGES/Sensor monitoring.jpg" alt="Sensor monitoring">

<img src="CAP4-IMAGES/Alert & emergency handling.jpg" alt="Alert & emergency handling.jpg">

<img src="CAP4-IMAGES/Notification service.jpg" alt="Notification service">

Aqui podemos apreciarlo completo:

<img src="CAP4-IMAGES/Candidate-Context-Discovery.jpg" alt="Candidate-Context-Discovery">

#### 4.1.1.2 Domain Message Flows Modeling.

Paciente
Escenario: El paciente desea acceder a la plataforma

<img src="CAP4-IMAGES/Modeling-1.jpg" alt="Modeling-1">

Scan
Escenario: Paciente vincula su sensor y comienza la sesión
Flujo:

<img src="CAP4-IMAGES/Modeling-2.jpg" alt="Modeling-2">

Monitoreo
Escenario: Ritmo cardíaco crítico detectado automáticamente
<img src="CAP4-IMAGES/Modeling-3.jpg" alt="Modeling-3">

Doctor
Escenario: Doctor revisa sesiones pasadas del paciente

<img src="CAP4-IMAGES/Modeling-4.jpg" alt="Modeling-4">

#### 4.1.1.3 Bounded Context Canvases.

- IAM

<img src="CAP4-IMAGES/Bounded-Context-Canvases-IAM.jpg" alt="Bounded-Context-Canvases-IAM">

- Patient Management

<img src="CAP4-IMAGES/Bounded-Context-Canvases-Patient management.jpg" alt="Bounded-Context-Canvases-Patient management">

- Sensor Monitoring

<img src="CAP4-IMAGES/Bounded-Context-Canvases-Sensor Monitoring.jpg" alt="Bounded-Context-Canvases-Sensor Monitoring">

- Alert & Emergency Handling

<img src="CAP4-IMAGES/Bounded-Context-Canvases-Alert & Emergency handling.jpg" alt="Bounded-Context-Canvases-Alert & Emergency handling">

- Medical History & Analytics

<img src="CAP4-IMAGES/Bounded-Context-Canvases-Medical history & analytics.jpg" alt="Bounded-Context-Canvases-Medical history & analytics">

- Notification Service

<img src="CAP4-IMAGES/Bounded-Context-Canvases-Notification service.jpg" alt="Bounded-Context-Canvases-Notification service">

### 4.1.2. Context Mapping.

Dentro del Event storming, se identificaron 6 bounded context:
- IAM
- Patient management
- Medical hisotry & analytics
- Sensor monitoring
- Alert & emergency handling
- Notification service

Se ha decidido hacer uso los patrones de Conformist y de Customer/Supplier:

**Conformist:**
- Sensor Monitoring es conformista de Patient Management: adapta los modelos de paciente y contacto.

- Alert & Emergency Handling es conformista de Sensor Monitoring: entiende el formato de eventos críticos sin imponer cambios.

<img src="CAP4-IMAGES/Context-Mapping.jpg" alt="Context-Mapping">

### 4.1.3. Software Architecture.

#### 4.1.3.1. Software Architecture System Landscape Diagram.

La plataforma MedSystem conecta a pacientes y doctores mediante una aplicación móvil y web, que a su vez se integra con dispositivos IoT (sensores de frecuencia cardíaca) y servicios de notificaciones externas.

**Actores involucrados:**

- Paciente: Usa la aplicación para registrar su actividad cardíaca y recibir notificaciones.

- Doctor: Accede al sistema para revisar los datos de los pacientes y recibir alertas de emergencia.

**Sistemas externos relevantes:**

- Notification Gateway (para alertas de emergencia vía Email/SMS).

- IoT Device Platform (para enviar datos del sensor).

**Relaciones clave:**

- El Paciente interactúa directamente con la app (MedSystem Platform).

- El Doctor consulta el estado y la historia clínica de sus pacientes mediante la plataforma.

- El sistema MedSystem se comunica con servicios externos para notificaciones y lectura de sensores.

<img src="CAP4-IMAGES/Landscape-Diagram.png" alt="Landscape-Diagram">

#### 4.1.3.2. Software Architecture Context Level Diagrams.

Sistema central: MedSystem Platform

**Interacciones principales:**

- El Paciente crea su cuenta, vincula su sensor, monitorea su estado de salud y recibe notificaciones de alerta.

- El Doctor revisa los registros históricos, monitorea alertas en tiempo real y responde a emergencias de sus pacientes.

- Sensores IoT envían la frecuencia cardíaca hacia la plataforma.

- Notification Gateway se utiliza para enviar alertas externas en caso de anomalías cardíacas.

**Visión general:**

MedSystem centraliza toda la interacción entre usuarios humanos (pacientes y doctores) y sistemas externos (IoT, notificaciones).

<img src="CAP4-IMAGES/Context-Level-Diagrams.png" alt="Context-Level-Diagrams">

#### 4.1.3.3. Software Architecture Container Level Diagrams.

| Container              | Technology            | Main Responsibility                              |
|-------------------------|------------------------|--------------------------------------------------|
| **Web/Mobile App**       | Flutter / React        | Interface for patients and doctors              |
| **API Gateway**          | Node.js / Express      | Management of REST requests and authentication  |
| **IAM Service**          | Auth0 / Custom Auth    | Handling login, roles, and permissions           |
| **Sensor Monitoring**    | Python + MQTT          | Collection and validation of heart rate sensor data |
| **Alert Engine**         | Node.js                | Detection of anomalies and alert generation     |
| **Notification Service** | Firebase / SMTP        | Sending notifications to patients and doctors   |
| **Medical History API**  | Python / FastAPI       | Consultation of medical histories and reports   |
| **Database**             | PostgreSQL / MongoDB   | Storage of users, sessions, and medical records |

**Notes:**
- The app distinguishes between patients and doctors through roles managed in IAM.
- Critical alerts generated by the system are automatically sent to the assigned doctor.

<img src="CAP4-IMAGES/Container-Level-Diagrams.png" alt="Context-Level-Diagrams">

#### 4.1.3.4. Software Architecture Deployment Diagrams.

Entorno de despliegue:

**Nube pública (AWS, Azure o GCP):**

- Contenedores desplegados en instancias de aplicación o Kubernetes.

- Base de datos (RDS, Cloud SQL o equivalente) para almacenar registros de usuarios y sesiones.

- IoT Core o MQTT Broker para recibir datos de sensores en tiempo real.

- Servicio de notificaciones externas configurado (Firebase Cloud Messaging, Twilio, SMTP Gateway).

**Diagrama de despliegue conceptual:**

- Paciente y Doctor → Web/Mobile App → API Gateway

- API Gateway → IAM Service (autenticación) + Sensor Monitoring (vía eventos)

- Sensor Monitoring → Alert Engine → Notification Service → Paciente/Doctor

- Medical History API → Base de datos

<img src="CAP4-IMAGES/Deployment-Diagrams.png" alt="DeploymentDiagrams">

link: https://structurizr.com/share/101697/ddc19bf8-07c7-4949-ad6f-375475a613d5
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
