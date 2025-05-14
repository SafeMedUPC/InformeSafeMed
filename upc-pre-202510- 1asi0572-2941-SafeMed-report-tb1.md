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

# Capítulo V: Solution UI/UX Design

## 5.1. Style Guidelines.

### 5.1.1. General Style Guidelines.

<p>
En este caso, las etiquetas de información se representarán en el idioma inglés, y estas serán claras y concisas para que el usuario entienda por completo la funcionalidad. Las etiquetas más importantes de nuestra aplicación son: 
</p>

<p><strong>Appointments:</strong> Aquí se muestran las opciones para agendar citas, las que se desean programar, y las que ya tienen una fecha programada de asistencia, junto con todos los datos del paciente, el doctor a cargo de la consulta y la fecha y hora de esta.</p>

<p><strong>Chat:</strong> En este apartado se muestran todos los chats de los pacientes con los que el doctor ha tenido contacto, y en el caso del paciente, se le muestra los doctores con los que ha tenido consulta. Por este medio se pueden aclarar dudas y su uso es solo para fines médicos. </p>

<p><strong>Treatments for patient:</strong> En este apartado el usuario podrá visualizar el tratamiento que debe realizar de acuerdo a las indicaciones del médico, el cual también podra ir editando en este apartado e ir viendo como evoluciona el paciente.</p>

<p><strong>Request history:</strong> En este apartado el médico va poder ver diagnósticos anteriores del paciente, que tratamientos ha llevado y datos médicos específicos del paciente; con el fin de saber cual sería el mejor tratamiento para llevarse a cabo. Asimismo, podrá actualizar el historial clínico del paciente, una vez haya terminado cierto tratamiento. 
</p>

<p><strong>Request results:</strong> En este apartado el médico podrá pedir los resultados de un paciente a un laboratorio, brindando los datos del examen tomado y del paciente. De esta forma, el doctor obtiene los resultados y sabe que tratamiento llevar a cabo.
</p>

### 5.1.2. Web, Mobile and IoT Style Guidelines.

## 5.2. Information Architecture.

### 5.2.1. Organization Systems.

<p>
El principal objetivo de este punto es ofrecer una guía y apoyo para estructurar la información de la página web. Esto asegurará que, al llevar a cabo la implementación del sistema, sea accesible y sencillo de utilizar para los usuarios. En este nuevo proyecto, se ha decidido emplear la organización jerárquica para las diversas secciones del Landing Page. Esta elección se fundamenta en la variedad de grupos de usuarios y las diferencias según el tipo de usuario que la utilice. Además, para la clasificación del contenido, se opta por un orden numérico para las fucnionalidades que mencionamos en la aplicación.
</p>

### 5.2.2. Labeling Systems.

<p>
En este caso, las etiquetas de información se representarán en el idioma inglés, y estas serán claras y concisas para que el usuario entienda por completo la funcionalidad. Las etiquetas más importantes de nuestra aplicación son: 
</p>

<p><strong>Appointments:</strong> Aquí se muestran las opciones para agendar citas, las que se desean programar, y las que ya tienen una fecha programada de asistencia, junto con todos los datos del paciente, el doctor a cargo de la consulta y la fecha y hora de esta.</p>

<p><strong>Chat:</strong> En este apartado se muestran todos los chats de los pacientes con los que el doctor ha tenido contacto, y en el caso del paciente, se le muestra los doctores con los que ha tenido consulta. Por este medio se pueden aclarar dudas y su uso es solo para fines médicos. </p>

<p><strong>Treatments for patient:</strong> En este apartado el usuario podrá visualizar el tratamiento que debe realizar de acuerdo a las indicaciones del médico, el cual también podra ir editando en este apartado e ir viendo como evoluciona el paciente.</p>

<p><strong>Request history:</strong> En este apartado el médico va poder ver diagnósticos anteriores del paciente, que tratamientos ha llevado y datos médicos específicos del paciente; con el fin de saber cual sería el mejor tratamiento para llevarse a cabo. Asimismo, podrá actualizar el historial clínico del paciente, una vez haya terminado cierto tratamiento. 
</p>

<p><strong>Request results:</strong> En este apartado el médico podrá pedir los resultados de un paciente a un laboratorio, brindando los datos del examen tomado y del paciente. De esta forma, el doctor obtiene los resultados y sabe que tratamiento llevar a cabo.
</p>

### 5.2.3. SEO Tags and Meta Tags

A continuación, mostraremos las etiquetas que representarán el contenido presentado tanto en nuestra aplicación web como en nuestra página de inicio. Estas etiquetas facilitarán la identificación y localización de nuestra aplicación MedSystem.

Landing Page:

Title: MedSystem

Description: MedSystem - SafeMed Oficial Landing Page

Keywords: Appointments, treatments, doctors, patients, monitoring.

Authors: SafeMed

Web application:

Title: MedSystem

Description: MedSystem - SafeMed Oficial Web Site

Keywords: Appointments, Clinic History, Treatment Tracking, medical tests, test results, registration, diagnosis, monitoring.

Authors: SafeMed

### 5.2.4. Searching Systems.

<p>
El sistema de búsqueda es un elemento fundamental en nuestra aplicación, puesto que se va usar bastante al momento ded pedir las historias clinicas del paciente, al momento de pedir los resultados, y al momento de buscar a un paciente en el apartado de chats. Considerando que el sistema maneja una gran cantidad de datos, y a medida que estos van incrementando, se ha pensado en un sistema de busqueda ágil que funcione con la base de datos de manera fluída, y de esta forma los usuarios no tengan alguna insatisfacción al momento de usar el sistema.
</p>

### 5.2.5. Navigation Systems.

<p>
El método de navegación entre las diversas secciones de la landing page estará facilitado por una barra superior. Esta barra estará compuesta por los títulos representativos de cada sección, permitiendo que los usuarios puedan acceder directamente a la información deseada simplemente haciendo clic en el título correspondiente. En el caso de la aplicación web, la navegación se irá dando a través de una barra lateral, la cual contendrá los títulos de cada función que se ofrece. Esta estructura de navegación se ha diseñado para integrarse de manera armoniosa con la interfaz visual de la Landing Page y la aplicación web, proporcionando una experiencia agradable y fluida para los usuarios.
</p>

## 5.3. Landing Page UI Design.

### 5.3.1. Landing Page Wireframe.

### 5.3.2. Landing Page Mock-up.

## 5.4. Applications UX/UI Design.

### 5.4.1. Applications Wireframes.

### 5.4.2. Applications Wireflow Diagrams.

### 5.4.2. Applications Mock-ups.

### 5.4.3. Applications User Flow Diagrams.

## 5.5. Applications Prototyping.

# Capítulo VI: Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management.

### 6.1.1. Software Development Environment Configuration.

### 6.1.2. Source Code Management.

### 6.1.3. Source Code Style Guide & Conventions.

### 6.1.4. Software Deployment Configuration.

## 6.2. Landing Page, Services & Applications Implementation.

### 6.2.1. Sprint 1

#### 6.2.1.1. Sprint Planning 1.

#### 6.2.1.2. Aspect Leaders and Collaborators.

#### 6.2.1.3. Sprint Backlog n.

#### 6.2.1.4. Development Evidence for Sprint Review.

#### 6.2.1.5. Testing Suite Evidence for Sprint Review.

#### 6.2.1.6. Execution Evidence for Sprint Review.

#### 6.2.1.7. Services Documentation Evidence for Sprint Review.

#### 6.2.1.8. Software Deployment Evidence for Sprint Review.

#### 6.2.1.9. Team Collaboration Insights during Sprint.
