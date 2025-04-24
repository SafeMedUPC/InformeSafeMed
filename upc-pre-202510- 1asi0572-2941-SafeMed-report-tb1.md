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

<img src="CAP4-IMAGES/Alert & emergency handling.jpg" alt="MAlert & emergency handling.jpg">

<img src="CAP4-IMAGES/Notification service.jpg" alt="Notification service">

Aqui podemos apresiarlo completo:

<img src="CAP4-IMAGES/Candidate-Context-Discovery.jpg" alt="Candidate-Context-Discovery">

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
