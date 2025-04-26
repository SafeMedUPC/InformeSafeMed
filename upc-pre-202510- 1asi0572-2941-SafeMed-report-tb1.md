# SafeMed - Report

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="LogoUPC">
</p>

# Universdiad Peruana de Ciencias Aplicadas

# INGENIERÍA DE SOFTWARE

### Ciclo: 7

## CURSO: Desarrollo de Soluciones IOT | SECCIÓN 2941

Profesor: Leon Baca, Marco Antonio

# Proyecto de curso

## Informe del TF

#### StartUp: SafeMed

#### Producto: MedSystem

### Integrantes:

| Integrantes                            | Codigo     |
| -------------------------------------- | ---------- |
| De La Piedra Quintanilla, Erwin Miquel | U202112179 |
| Gutierrez Zumaeta, Manuel Alonso       | U202112353 |
| Mendez Rosales, Marco Aurelio          | U202018273 |
| Roca Huapaya, Orlando Arturo           | U201919742 |
| Ventura Chancafe, Eduardo Renato       | U202212645 |

#### Ciclo 2025-10

##### Abril, 2025

---

# Registro de Versiones del informe

| Versión | Fecha | Autor | Descripción de modificación |
|---------|-------|--------|------------------------------|
| 0.1     |       |        |                              |
| 0.2     |       |        |                              |
| 0.3     |       |        |                              |
| 0.4     |       |        |                              |
| 0.5     |       |        |                              |

# Project Report Collaboration Insights

# Student Outcome
**ABET – EAC - Student Outcome 5**: Trabaja efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo; crea un entorno colaborativo e inclusivo y establece metas, planifica tareas y cumple objetivos 

| Criterio específico | Acciones realizadas | Conclusiones |
|---------------------|---------------------|--------------|
| 5.c.1 Trabaja en equipo para proporcionar liderazgo en forma conjunta |  |  |
| 5.c.2 Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos |  |  |

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup
SafeMed es una startup tecnológica creada por estudiantes de Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas (UPC), enfocada en el desarrollo de soluciones innovadoras para el sector salud mediante el uso de tecnologías IoT. Nuestro propósito es brindar herramientas digitales que permitan mejorar la calidad de vida de pacientes con enfermedades crónicas, facilitando el monitoreo remoto de sus signos vitales y proporcionando canales de comunicación directa entre familiares y profesionales médicos.

SafeMed nace como respuesta a la creciente necesidad de una atención médica más preventiva, accesible y en tiempo real. A través de nuestro sistema inteligente, buscamos detectar de forma oportuna alteraciones en la salud de los pacientes y notificar automáticamente a las personas responsables de su cuidado, ayudando a reducir tiempos de respuesta y mejorar la gestión médica.

Misión: Salvar vidas a través de tecnología accesible e inteligente, brindando soluciones que permitan a las familias y al personal médico monitorear en tiempo real la salud de los pacientes, y actuar con rapidez ante cualquier anomalía.

Visión: Ser la plataforma líder en Latinoamérica en soluciones digitales para el monitoreo remoto de salud, reconocida por su innovación, confiabilidad y contribución al bienestar de los pacientes.

### 1.1.2. Perfiles de integrantes del equipo
| Foto                                       | Nombre y Descripción                                                                                          |
| ------------------------------------------ | ------------------------------------------------------------------------------------------------------------- |
| ![Foto Manuel](CAP1-IMAGES/FotoManuel.jpg) | **Nombre:** Manuel Alonso Gutierrez Zumaeta <br>**Código:** u202112353 <br>**Descripción:** Soy Manuel Gutierrez, estudiante de la carrera de Ingeniería de Software, tengo 20 años. Tengo experiencia en el desarrollo de aplicaciones web, tanto frontend como backend, programación móvil en Flutter. Me considero una persona responsable y que se propone hacer un buen trabajo.                                                      |
| ![Foto Marcos](ruta/a/la/foto)              | **Nombre:** <br>**Código:** <br>**Descripción:**                                                              |
| ![Foto Miquel](ruta/a/la/foto)             | **Nombre:** <br>**Código:** <br>**Descripción:**                                                              |
| ![Foto Eduardo](ruta/a/la/foto)               | **Nombre:** <br>**Código:** <br>**Descripción:**                                                              |
| ![Foto Orlando](https://cdn.discordapp.com/attachments/877299205696262227/1365191908304879666/Captura_de_pantalla_2024-06-16_173218.png?ex=680c698a&is=680b180a&hm=2a5b43302b228e7f9097a0e64bc85d4669760f53401359d703cf1d9ba3b3d3c9&)               | **Nombre:** Orlando Arturo Roca Huapaya <br>**Código:** u201919742<br>**Descripción:** Como estudiante de ingeniería de software, mi contribución al equipo se centra en mis conocimientos en la planificación y diseño de software. A lo largo de     mi formación he podido desarrollar proyectos utilizando Java, lo que me da una ventaja significativa con el sistema que trabajamos. Estoy entusiasmado por aplicar mis habilidades en el desarrollo y trabajar junto al equipo para alcanzar         nuestros objetivos.                                                             |

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática
Las enfermedades cardiovasculares y otros trastornos relacionados con los signos vitales representan una de las principales causas de hospitalizaciones y muertes a nivel mundial. Según datos de la Organización Mundial de la Salud (OMS), millones de personas sufren cada año eventos de salud que podrían ser evitados o tratados de manera más efectiva si existieran mecanismos de monitoreo continuo fuera del ámbito hospitalario.

Actualmente, muchos pacientes con condiciones de riesgo no cuentan con dispositivos accesibles que les permitan una vigilancia constante de su estado de salud en tiempo real. La ausencia de monitoreo domiciliario efectivo genera que las alteraciones en signos vitales pasen desapercibidas, retrasando la intervención médica oportuna. Además, la falta de notificaciones inmediatas a familiares o médicos contribuye a incrementar la gravedad de los eventos de emergencia.

En respuesta a esta necesidad, SafeMed propone una solución que integra tecnología IoT mediante sensores de frecuencia cardiaca conectados a una aplicación móvil, permitiendo el monitoreo remoto en tiempo real. La plataforma no solo alerta automáticamente a familiares y médicos ante cualquier desviación crítica, sino que también ofrece herramientas de gestión médica para mejorar el seguimiento clínico de los pacientes.

#### What (¿Qué?):
Falta de monitoreo remoto continuo de signos vitales que permita alertar de forma automática y oportuna sobre posibles emergencias de salud.

#### When (¿Cuándo?):
Durante la vida diaria del paciente, especialmente en momentos sin supervisión directa de profesionales médicos.

#### Where (¿Dónde?):
En el hogar, en el trabajo o cualquier lugar donde el paciente se encuentre fuera de un entorno hospitalario.

#### Who (¿Quién?):
Pacientes con enfermedades cardiovasculares, adultos mayores, personas con condiciones médicas crónicas, sus familiares, y profesionales de salud encargados de su cuidado.

#### Why (¿Por qué?):
La falta de soluciones accesibles y eficientes para el monitoreo constante incrementa el riesgo de que eventos críticos no sean detectados a tiempo.

#### How (¿Cómo?):
A través de un sensor portátil que mide la frecuencia cardiaca en tiempo real, conectado a una aplicación móvil que genera alertas automáticas a familiares y médicos.

#### How Much (¿Cuánto?):
Estudios recientes en Latinoamérica estiman que cerca del 30% de las hospitalizaciones por eventos cardiovasculares podrían ser prevenidas mediante sistemas de alerta temprana en el hogar (fuente simulada para ilustrar).

### 1.2.2 Lean UX Process.

#### 1.2.2.1. Lean UX Problem Statements.
El sistema de atención médica actual presenta una limitación importante: no garantiza un monitoreo continuo ni alertas inmediatas para pacientes con condiciones crónicas o de riesgo, especialmente fuera de los entornos hospitalarios. Esta carencia expone a los pacientes a situaciones de emergencia que podrían ser prevenidas o atendidas de forma más oportuna.

Hemos observado que, en el entorno domiciliario, los pacientes en riesgo no cuentan con soluciones accesibles para detectar alteraciones críticas en sus signos vitales ni mecanismos automáticos de alerta hacia sus familiares o doctores de confianza. Esta brecha genera un aumento en la gravedad de los episodios médicos, incrementa los costos de atención hospitalaria y afecta negativamente la calidad de vida tanto de los pacientes como de sus familias.

¿Cómo podríamos diseñar una solución de monitoreo remoto que permita detectar alteraciones en tiempo real y notificar automáticamente a familiares y médicos, mejorando así la atención oportuna y la seguridad de los pacientes, sin necesidad de intervención manual constante?

#### 1.2.2.2. Lean UX Assumptions.

##### User Assumptions:
##### ¿Quién es el usuario?
Pacientes con condiciones de salud que requieren monitoreo constante (como enfermedades cardiovasculares), sus familiares directos y médicos tratantes.

##### ¿Dónde encaja nuestro producto en su trabajo o vida?
SafeMed se integra en la vida cotidiana del paciente y su familia, proporcionando monitoreo continuo de signos vitales, generando alertas inmediatas en caso de anomalías, y facilitando la gestión médica a distancia.

##### ¿Qué problemas tiene que resolver nuestro producto?

Falta de monitoreo permanente de signos vitales en el hogar.

Falta de notificaciones inmediatas ante emergencias.

Dificultad en el seguimiento médico remoto y en la toma de decisiones oportunas.

##### ¿Cuándo y cómo es usado nuestro producto?
SafeMed se usa diariamente de manera pasiva: el sensor mide continuamente la frecuencia cardiaca, y la aplicación móvil procesa los datos en tiempo real. Solo en caso de detectar valores anormales, se envían notificaciones automáticas a familiares y médicos.

##### ¿Cómo debe verse y comportarse nuestro producto?
Debe ser intuitivo, fácil de configurar, seguro y confiable. La app debe mostrar la información de manera clara, con gráficos sencillos de interpretar, y notificar con rapidez y precisión ante cualquier riesgo.

##### Business Assumptions:
- Creo que mis usuarios necesitan una solución de software eficiente y accesible para la personalización de su auto, evitando que otras personas o empresas los estafen.

- Estas necesidades se pueden satisfacer mediante una aplicación móvil intuitiva y segura que guíe a los usuarios a través del proceso de personalización automotriz y les proporcione transparencia en las transacciones.

- Mis clientes iniciales son propietarios de vehículos que desean personalizar sus autos de manera confiable y sin riesgos.

- El valor #1 que un cliente busca en mi servicio es la capacidad de personalizar su vehículo de forma segura y confiable, evitando estafas y asegurándose de obtener los productos y servicios deseados.

- El cliente también puede obtener estos beneficios adicionales: una amplia selección de opciones de personalización, asesoramiento experto, precios transparentes y competitivos, y una experiencia de usuario fluida.

- Voy a adquirir la mayoría de mis clientes a través de campañas de marketing digital dirigidas a propietarios de vehículos interesados en la personalización automotriz, así como mediante asociaciones con concesionarios de automóviles y talleres especializados.

- Haré dinero a través de una combinación de modelos de negocio, que pueden incluir distintos planes de suscripción, ingresos por publicidad dentro de la aplicación y otros servicios premium. Además, estableceré acuerdos de asociación con staffs mecánicos para ofrecer servicios exclusivos y beneficios a los suscriptores.

- Mi competencia principal en el mercado son otras aplicaciones y plataformas en línea que ofrecen servicios similares de personalización automotriz, así como talleres físicos y tiendas especializadas.

- Los venceremos debido a nuestra atención en la seguridad y transparencia del proceso, nuestra amplia gama de opciones de personalización, y nuestra interfaz intuitiva y fácil de usar.

- Mi mayor riesgo es la falta de confianza por parte de los usuarios en la seguridad y la transparencia de la plataforma.

- Resolvemos esto a través de una estricta verificación de los staff mecánicos y la implementación de medidas de seguridad robustas, así como una comunicación clara y transparente con los usuarios sobre los procesos y las políticas de la plataforma.

#### 1.2.2.3. Lean UX Hypothesis Statements.

- Creemos que al proporcionar un monitoreo continuo de signos vitales y alertas automáticas en tiempo real a familiares y médicos, los usuarios podrán detectar de manera temprana eventos críticos de salud. 

  Sabremos que hemos tenido éxito

  Cuando el 80% de los eventos de emergencia sean detectados y notificados en menos de 10 segundos, y cuando se reduzca el tiempo de respuesta de familiares y médicos en un 30%.

- Creemos que al ofrecer una aplicación móvil intuitiva y segura que centralice la información médica de los pacientes, facilitaremos el seguimiento remoto de la salud y mejoraremos la continuidad del tratamiento médico.

  Sabremos que hemos tenido éxito 

  Cuando el 70% de los médicos usuarios consulte semanalmente los reportes de signos vitales, y cuando la adherencia a planes de tratamiento por parte de pacientes monitorizados aumente en un 25%.

- Creemos que al proporcionar tranquilidad y confianza mediante alertas tempranas y un historial accesible de la salud del paciente, incrementaremos la satisfacción de las familias y su confianza en el sistema. 

  Sabremos que hemos tenido éxito 

  Cuando el 90% de los usuarios familiares reporten sentirse más tranquilos respecto al estado de salud de su ser querido tras un mes de uso, y cuando la tasa de renovación de suscripciones al servicio supere el 75% luego   de los primeros tres meses.

#### 1.2.2.4. Lean UX Canvas.

![Lean UX Canvas](https://cdn.discordapp.com/attachments/1251414631180931113/1365458075829665813/5b59cc1a-b2c6-4d16-bb2c-a233897280d0.png?ex=680d616e&is=680c0fee&hm=3c9b17eeeb9ffa137d66bfb99a0bf29ba136583d0b48b19b09d52496d3e2963b&)

## 1.3. Segmentos objetivo.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores.

### 2.1.1. Análisis competitivo.

<table><tr><th colspan="6" valign="top">Competitive Analysis Landscape</th></tr>
<tr><td colspan="1" valign="top">¿Por qué llevar a cabo este análisis?</td><td colspan="5" valign="top">El objetivo de este análisis es identificar las características de los competidores y encontrar maneras de diferenciarnos.</td></tr>
<tr><td colspan="2" rowspan="2" valign="top">Startup y Competidores</td><td colspan="1" valign="top">MedSystem</td><td colspan="1" valign="top">Home Medical Management</td><td colspan="1" valign="top">LOLIMSA</td><td colspan="1" valign="top">SAMA</td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td colspan="1" rowspan="2" valign="top">Perfil</td><td colspan="1" valign="top">Overview</td><td colspan="1" valign="top">Plataforma de gestión de procesos de un consultorio o clínica, que cuenta con diferentes funcionalidades para pacientes, doctores y laboratorios.</td><td colspan="1" valign="top">Es una compañía que a través de una plataforma digital y sus profesionales, asegura la ejecución y calidad del servicio de salud domiciliaria.</td><td colspan="1" valign="top">Es una empresa de software doctor con soluciones tecnológicas para la gestión de centros doctores como clínicas y hospitales, farmacias y cadenas de farmacias y clínicas veterinarias.</td><td colspan="1" valign="top">Es un consorcio de inversión dedicado a brindar servicios integrales de salud, especializados en la seguridad y salud en el trabajo. Contamos con distintas sedes a lo largo del norte del país, las cuales cuentan con el respaldo de la acreditación DIGESA/MINSA.</td></tr>
<tr><td colspan="1" valign="top">Ventaja competitiva ¿Qué valor ofrece a los clientes?</td><td colspan="1" valign="top">Cuenta con distintas funcionalidades como un sistema de gestión de citas en línea que permita a los pacientes y doctores programar fácilmente consultas, programación de cirugías ,exámenes y seguimientos de tratamiento o recuperaciones.</td><td colspan="1" valign="top">Utilizan inteligencia artificial e innovación para mejorar el servicio a los pacientes y facilitar la atención a los profesionales y prestadores de salud.</td><td colspan="1" valign="top">Reduce entre 10 y 20% tus costos hospitalarios utilizando las mejores prácticas de Health Management con LOLCLI, el software de gestión hospitalaria más completo de Latinoamérica.</td><td colspan="1" valign="top">Organización que orienta todos sus esfuerzos en realizar un servicio doctor de calidad a través de la presentación de resultados confiables.</td></tr>
<tr><td colspan="1" rowspan="2" valign="top">Perfil de Marketing</td><td colspan="1" valign="top">Mercado objetivo</td><td colspan="1" valign="top">Consultorio, clínicas y hospitales.</td><td colspan="1" valign="top">Prestadores de salud, pacientes y personal doctor</td><td colspan="1" valign="top">Clínicas y hospitales</td><td colspan="1" valign="top">Hospitales y clínicas</td></tr>
<tr><td colspan="1" valign="top">Estrategias de marketing</td><td colspan="1" valign="top">Publicidad por redes sociales y campañas.</td><td colspan="1" valign="top">Publicidad por redes sociales.</td><td colspan="1" valign="top">Publicidad por redes sociales.</td><td colspan="1" valign="top">Publicidad por redes sociales.</td></tr>
<tr><td colspan="1" rowspan="3" valign="top">Perfil de producto</td><td colspan="1" valign="top">Productos & Servicios</td><td colspan="1" valign="top">Una plataforma para gestionar las citas médicas, programar cirugías, exámenes y seguimiento de tratamientos. Además, la plataforma almacena el historial clínico de los pacientes.</td><td colspan="1" valign="top">Un software basado en el diseño centrado en el paciente, con información integrada, que utiliza la geolocalización y la valoración del servicio, como forma de optimizar la gestión del modelo.</td><td colspan="1" valign="top">Software de gestión hospitalaria, impulsado por una plataforma de software de última generación que controla al detalle todas las actividades, desde que el paciente ingresa hasta que se retira del establecimiento</td><td colspan="1" valign="top">Servicios integrales de salud: -Exámenes doctores ocupacionales -Monitores ocupacionales -Vigilancia médica ocupacional -Análisis de laboratorio -radiografias digitales</td></tr>
<tr><td colspan="1" valign="top">Precios & Costos</td><td colspan="1" valign="top">Varían según características de la clínica, con opciones de suscripción mensual o anual.</td><td colspan="1" valign="top">Varían según el producto y pueden incluir tarifas de suscripción o costos de licencia.</td><td colspan="1" valign="top">Los precios varían según el producto y pueden incluir tarifas de suscripción mensuales o costos de licencia.</td><td colspan="1" valign="top">Los precios varían según el tamaño del hospital o clínica y las características específicas de la solución, con opciones de suscripción mensual o anual</td></tr>
<tr><td colspan="1" valign="top">Canales de distribución (Web y/o Móvil)</td><td colspan="1" valign="top">Principalmente a través de su sitio web oficial</td><td colspan="1" valign="top">Principalmente a través de su sitio web, con posibilidad de acceso móvil.</td><td colspan="1" valign="top">Principalmente a través de su sitio web oficial.</td><td colspan="1" valign="top">Principalmente a través de su sitio web oficial.</td></tr>
<tr><td colspan="1" rowspan="4" valign="top">Análisis SWOT</td><td colspan="1" valign="top">Fortalezas</td><td colspan="1" valign="top">Ofrece una solución integral para la gestión de procesos en consultorios y clínicas, lo que incluye funcionalidades específicas para pacientes, doctores y laboratorios. Esta centralización de información puede mejorar la eficiencia operativa y la coordinación entre todas las partes involucradas en el proceso de atención médica.</td><td colspan="1" valign="top">Ofrece cuidados personalizados en el hogar, generando satisfacción y lealtad. Su enfoque centrado en el paciente y su capacidad de adaptación son ventajas.</td><td colspan="1" valign="top">Cuenta con amplia experiencia en software doctor y ofrece soluciones integrales y personalizadas respaldadas por un sólido servicio de soporte técnico.</td><td colspan="1" valign="top">Samma ofrece una variedad de herramientas de bienestar mental y una interfaz amigable que atrae a una amplia gama de usuarios.</td></tr>
<tr><td colspan="1" valign="top">Debilidades</td><td colspan="1" valign="top">La competencia en el mercado de software de gestión de consultorios y clínicas es intensa, con numerosas empresas que ofrecen soluciones similares.</td><td colspan="1" valign="top">Limitaciones geográficas y dependencia del personal pueden afectar la expansión y la consistencia de los servicios.</td><td colspan="1" valign="top">Enfrenta competencia en el mercado de software doctor y puede estar sujeta a dependencia tecnológica y costos asociados con el desarrollo de soluciones.</td><td colspan="1" valign="top">La competencia en el mercado de aplicaciones de bienestar mental puede dificultar que Samma se destaque, especialmente si enfrenta problemas de usabilidad o dependencia tecnológica.</td></tr>
<tr><td colspan="1" valign="top">Oportunidades</td><td colspan="1" valign="top">La creciente demanda de soluciones digitales en el sector de la salud ofrece una oportunidad para capturar una parte del mercado en constante expansión.</td><td colspan="1" valign="top">Puede expandir servicios, integrar tecnología y formar asociaciones para llegar a más clientes y mejorar la eficiencia.</td><td colspan="1" valign="top">Tiene potencial de expansión tanto nacional como internacional, además de oportunidades para desarrollar nuevas funcionalidades y establecer alianzas estratégicas.</td><td colspan="1" valign="top">La expansión internacional y la colaboración estratégica ofrecen oportunidades para llegar a nuevos mercados y asociarse con empresas o instituciones para aumentar el alcance de la aplicación.</td></tr>
<tr><td colspan="1" valign="top">Amenazas</td><td colspan="1" valign="top">Las preocupaciones sobre la privacidad y seguridad de los datos en el sector de la salud son una amenaza constante.</td><td colspan="1" valign="top">Competencia, cambios regulatorios y preocupaciones sobre privacidad y seguridad de datos pueden impactar la rentabilidad y confianza en los servicios.</td><td colspan="1" valign="top">Los posibles cambios regulatorios, preocupaciones sobre seguridad de datos y avances tecnológicos rápidos representan riesgos que podrían afectar su posición en el mercado.</td><td colspan="1" valign="top">Cambios en la regulación, críticas negativas y avances tecnológicos representan amenazas potenciales para la operación y la reputación de Samma en el mercado.</td></tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores.

MedSystem puede destacarse en el mercado ofreciendo una plataforma de gestión de procesos clínicos altamente personalizable y fácil de usar, tanto para pacientes como para profesionales de la salud, diferenciándose así de competidores como Home Medical Management y LOLIMSA. Con un enfoque específico en la atención domiciliaria, la plataforma puede ofrecer funcionalidades especializadas para la coordinación y seguimiento de la atención médica en el hogar, proporcionando comodidad y eficiencia para pacientes y cuidadores. Además, MedSystem puede invertir en el desarrollo de tecnologías avanzadas, como inteligencia artificial y análisis de datos, para mejorar la gestión de consultorios y clínicas, posicionándose como una opción innovadora frente a empresas como LOLIMSA. Para competir con SAMA en el ámbito de la salud ocupacional y la seguridad laboral, MedSystem puede ofrecer módulos especializados y herramientas de cumplimiento normativo, aprovechando su experiencia en la gestión clínica para proporcionar soluciones integrales a empresas e instituciones. Una estrategia de marketing sólida, centrada en la educación del mercado sobre la importancia de la gestión eficiente de consultorios y clínicas, así como en testimonios de usuarios satisfechos, puede ayudar a MedSystem a construir una sólida reputación y atraer clientes potenciales. Además, explorar alianzas estratégicas con instituciones médicas y otros actores del sector puede ampliar su alcance y fortalecer su posición en el mercado. En resumen, MedSystem puede destacarse mediante la combinación de personalización, tecnología avanzada, especialización en atención domiciliaria y salud ocupacional, una sólida estrategia de marketing y alianzas estratégicas, lo que le permitirá diferenciarse y prosperar en un mercado competitivo.

## 2.2. Entrevistas.

### 2.2.1. Diseño de entrevistas.

**Preguntas para el segmento objetivo paciente:**

- _¿Cuáles son los mayores desafíos que enfrentas al cuidar tu salud cuando no estás en el consultorio médico?_
- _¿Qué tipo de dispositivos tecnológicos (como celulares, tablets o computadoras) usas para cuidar o monitorear tu salud? ¿Por qué prefieres esos dispositivos?_
- _¿Qué herramientas o funciones te gustaría tener para poder revisar en tiempo real cosas como tu oxigenación o ritmo cardíaco?_
- _¿Qué características te parecen más importantes al usar una aplicación o tecnología para cuidar tu salud desde casa?_
- _¿Cómo te gustaría recibir alertas o información importante si tu salud está en riesgo?_
- _¿Qué crees que se podría mejorar en la comunicación entre los médicos y tus familiares cuando tú estás en una situación médica delicada?_
- _¿Qué funciones te parecerían útiles en una aplicación que reúna información de sensores de salud (como pulseras o medidores) y que también te ayude con tu cuidado médico?_
- _¿Cómo estás cuidando tu salud actualmente si tienes una enfermedad crónica o estás en recuperación fuera del hospital?_
- _¿Qué tan importante es para ti la seguridad y privacidad de tus datos médicos cuando se recopilan con dispositivos tecnológicos?_
- _¿Qué te gustaría que mejorara en la forma en que puedes ver o compartir tu historial médico, especialmente si incluye datos en tiempo real?_
- _¿Qué piensas sobre el uso de tecnología como sensores o dispositivos conectados para mejorar tu atención médica o prevenir enfermedades?_

**Preguntas para el segmento objetivo doctor:**

- _¿Cuáles son los mayores desafíos que enfrentas al hacer seguimiento del estado de salud de tus pacientes fuera del consultorio?_
- _¿Qué tipo de dispositivos tecnológicos (móviles, tablets, computadoras) usas para el seguimiento de pacientes? ¿Por qué prefieres esos dispositivos?_
- _¿Qué herramientas o funcionalidades te serían útiles para monitorear signos vitales como oxigenación y ritmo cardíaco en tiempo real?_
- _¿Qué características consideras más importantes al elegir una solución tecnológica para el monitoreo remoto de pacientes?_
- _¿Cómo prefieres recibir alertas o información crítica sobre un paciente en situación de riesgo?_
- _¿Qué aspectos te gustaría mejorar en la comunicación con los familiares de tus pacientes en situaciones médicas delicadas?_
- _¿Qué funcionalidades consideras cruciales en una plataforma que integre datos de sensores IoT y gestión médica?_
- _¿Cómo manejas actualmente la continuidad del cuidado de pacientes crónicos o en recuperación fuera del hospital?_
- _¿Qué medidas de seguridad y privacidad consideras esenciales al manejar datos médicos recolectados por dispositivos IoT?_
- _¿Qué mejoras te gustaría ver en el acceso y documentación del historial clínico relacionado con datos en tiempo real?_
- _¿Cuál es tu opinión sobre el uso de tecnología IoT para mejorar la atención y la prevención en medicina?_

### 2.2.2. Registro de entrevistas.

| Entrevista 2                           | Gonzalo Jaime Zapata Campos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| -------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Edad                                   | 20 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Distrito                               | San Martin de Porres                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| ![Imagen 1.png](images/Imagen%201.png) | Gonzalo es un estudiante de 20 años que vive actualmente en San Martin de Porres. Sus sistemas operativos de preferencia son Ios en móviles y Windows en ordenadores. El navegador que usa con mayor frecuencia es Google Chrome. Nos comenta que ha tenido problemas anteriormente al momento de sacar cita, como el dijo no había una buena organización de citas por lo que para sacar una ha tenido que esperar mucho tiempo. Además habla de algunas características que le gustaría tener antes de poder sacar una cita y también otra para los envíos de los resultados de algún examen médico que hice, dependiendo de la gravedad de la situación, él pueda elegir entre que sea virtual o presencial. |
| URL de grabación                       | [upc-pre-202402-si657-SW71-MedTechSolutions-needfinding-sprint-1](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112936_upc_edu_pe/EVqboYQCGwZCud-3FINbNTMByTfeiCoFC-BK3OS3VW6xww)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| Timing                                 | 07:56 - 14:47                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |

| Entrevista 3                       | Jorge Villavicencio                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Edad                               | 64 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| Distrito                           | Santiago de surco                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ![Imagen3.png](images/Imagen3.png) | Jorge Villavicencio es un adulto de 64 años, que vive en Santiago de Surco, tiene como sistemas operativos de preferencia Windows en ordenador y IOS en móviles. Dentro de la entrevista realizada, podemos destacar la importancia que le da a la tecnologías al momento de la realización de citas médicas, como para la revisión de los resultados de sus chequeos médicos. Nos comenta el beneficio que brinda poder conocer al médico que lo atiende y poder coordinar de manera rápida y efectiva una cita, evitando los típicos protocolos tediosos y posibles demoras que suceden a lo largo de este. |
| URL de grabación                   | [upc-pre-202402-si657-SW71-MedTechSolutions-needfinding-sprint-1](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112936_upc_edu_pe/EVqboYQCGwZCud-3FINbNTMByTfeiCoFC-BK3OS3VW6xww)                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Timing                             | 14:48 - 25:33                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |

**Segmento Médico**

| Entrevista 1                               | Gaby Manrique                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Edad                                       | 50 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| Distrito                                   | La Molina                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| ![Entrevista2.png](images/Entrevista2.png) | Gaby Manrique es una adulta de 50 años, que vive actualmente en La Molina. Sus sistemas operativos de preferencia son Android en móviles y Windows en ordenadores. El navegador que usa con mayor frecuencia es Microsoft Edge. Durante la entrevista con Gaby, llevada a cabo a través de una videoconferencia en la plataforma Zoom, exploramos los desafíos diarios que enfrenta en su práctica médica. La doctora destacó la necesidad de herramientas tecnológicas eficientes para gestionar sus citas y comunicarse con otros profesionales de la salud y laboratorios. Mencionó que prefiere recibir pedidos médicos y resultados de pruebas de manera electrónica, utilizando plataformas seguras y fáciles de usar. En cuanto a la tecnología, el médico utilizó su computadora de escritorio con el navegador Chrome durante la videoconferencia. Además, expresó preocupación por la seguridad y privacidad de los datos médicos, destacando la importancia de medidas sólidas de protección de la información en línea. |
| URL de grabación                           | [upc-pre-202402-si657-SW71-MedTechSolutions-needfinding-sprint-1](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112936_upc_edu_pe/EVqboYQCGwZCud-3FINbNTMByTfeiCoFC-BK3OS3VW6xww)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Timing                                     | 25:34 - 33:12                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |

| Entrevista 2                               | Javier Puertas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Edad                                       | 28 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Distrito                                   | San Borja                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| ![Entrevista3.png](images/Entrevista3.png) | Javier Puertas, médico traumatólogo de 28 años en Lima, enfrenta desafíos en la gestión del tiempo y la coordinación con otros especialistas. Utiliza Windows y Android para su trabajo y prefiere herramientas tecnológicas seguras y fáciles de usar. Destaca la necesidad de aplicaciones integradas para la gestión de citas y comunicación con otros médicos. Prioriza la seguridad, facilidad de uso e integración al elegir tecnología. Además, valora la telemedicina y la historia clínica electrónica, pero señala la importancia de recibir formación adecuada para utilizar estas herramientas eficazmente. |
| URL de grabación                           | [upc-pre-202402-si657-SW71-MedTechSolutions-needfinding-sprint-1](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202112936_upc_edu_pe/EVqboYQCGwZCud-3FINbNTMByTfeiCoFC-BK3OS3VW6xww)                                                                                                                                                                                                                                                                                                                                                                                                                               |
| Timing                                     | 33:13 - 43:08                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |

### 2.2.3. Análisis de entrevistas.

**Segmento Objetivo #1: Paciente**

Los pacientes entrevistados han identificado consistentemente la mala organización y los largos tiempos de espera como problemas principales en la programación de citas médicas. Estas preocupaciones son comunes en todos los entrevistados, lo que sugiere que una solución que ofrezca una mejor gestión de citas sería bien recibida. Además, un patrón emergente es la preferencia por la flexibilidad en la elección entre consultas virtuales o presenciales, dependiendo de la gravedad de la situación. Este aspecto refleja una necesidad de personalización y adaptación a las circunstancias individuales de los pacientes.

**Segmento Objetivo #2: Médico**

Los médicos entrevistados han destacado de manera uniforme la necesidad de herramientas tecnológicas que integren eficientemente la gestión de citas, historias clínicas electrónicas, y la comunicación con otros profesionales. Un aspecto recurrente en las entrevistas es la priorización de la seguridad de la información y la facilidad de uso al elegir estas herramientas, lo que indica que cualquier solución tecnológica debe cumplir con estos criterios para ser considerada viable en un entorno médico. Además, la telemedicina se menciona como un recurso valioso, pero su implementación efectiva depende de una formación adecuada, subrayando la importancia de capacitar a los profesionales en el uso de nuevas tecnologías. Esta información es fundamental para desarrollar un arquetipo de médico que valore la eficiencia, la seguridad y la innovación en su práctica diaria.

## 2.3. Needfinding.

### 2.3.1. User Personas.

Los Users personas que se muestran a continuación, fueron realizados a partir de la información recopilada de la sección de entrevistas. Estos nos ayudarán a describir de forma general nuestro segmento objetivo.

- **Paciente:
  ![Userpersona1.png](images/Userpersona1.png)**
- **Doctor:
  ![Userpersona2.png](images/Userpersona2.png)**

### 2.3.2. User Task Matrix.

En esta sección se presenta el user task matrix de los segmentos objetivos, con el fin de identificar la frecuencia de las actividades realizadas por los usuarios, y de esta manera se refleja la importancia de determinadas tareas.

| Task                                                | <p>Pacientes </p><p> </p> | Profesionales doctores | <p></p><p>Laboratorio</p> |             |            |             |
| --------------------------------------------------- | ------------------------- | ---------------------- | ------------------------- | :---------- | :--------- | :---------- |
|                                                     | Frecuencia                | Importancia            | Frecuencia                | Importancia | Frecuencia | Importancia |
| Programar una cita                                  | Alta                      | Alta                   | Alta                      | Alta        | -          | -           |
| Acceder a resultados de exámenes                    | Media                     | Alta                   | Alta                      | Alta        | Alta       | Alta        |
| Realizar seguimiento de tratamiento                 | Alta                      | Alta                   | Alta                      | Alta        | -          | -           |
| Agendar una cirugía                                 | Baja                      | Alta                   | Media                     | Alta        | -          | -           |
| Participar en consultas virtuales                   | Baja                      | Alta                   | Media                     | Alta        | -          | -           |
| Recibir recordatorios automáticos de citas          | Alta                      | Alta                   | Alta                      | Alta        | -          | -           |
| Acceder a historias clínicas                        | -                         | -                      | Alta                      | Alta        | -          | -           |
| Consultar información sobre medicamentos            | Media                     | Alta                   | Media                     | Alta        | -          | -           |
| Comunicarse con el especialista                     | Alta                      | Alta                   | Media                     | Alta        | Alta       | Alta        |
| Proporcionar retroalimentación sobre la experiencia | Baja                      | Media                  | -                         | -           | -          | -           |
| Solicitar análisis clínicos                         | Baja                      | Alta                   | -                         | -           | Alta       | Alta        |
| Enviar resultado de análisis                        | -                         | -                      | -                         | -           | Alta       | Alta        |

En base al User Task Matrix presentado, podemos destacar las siguientes tareas con mayor frecuencia e importancia para cada segmento de usuarios:

**Pacientes:**

- Programar una cita
  - Explicación: Los pacientes programan citas con frecuencia y consideran esta tarea crucial para recibir atención médica oportuna.
- Realizar seguimiento de tratamiento
  - Explicación: Mantenerse al día con su tratamiento es vital para los pacientes, lo que refleja la alta frecuencia y la importancia atribuida a esta tarea.

**Profesionales doctores:**

- Acceder a resultados de exámenes
  - Explicación: Los profesionales doctores necesitan consultar los resultados de los exámenes con frecuencia para tomar decisiones informadas sobre el tratamiento de sus pacientes.
- Acceder a historias clínicas
  - Explicación: Las historias clínicas proporcionan antecedentes doctores completos y son esenciales para el diagnóstico y tratamiento adecuado de los pacientes.

Principales diferencias y coincidencias

- Coincidencias:
  - Tanto los pacientes como los profesionales doctores consideran que programar una cita es una tarea de alta frecuencia e importancia.
  - Acceder a resultados de exámenes es crucial tanto para los profesionales doctores como para los laboratorios, reflejando una alta frecuencia e importancia en ambas categorías.
- Diferencias:
  - Los pacientes valoran altamente el seguimiento de su tratamiento y recibir recordatorios automáticos de citas, mientras que los profesionales doctores ponen más énfasis en el acceso a historias clínicas y consultas virtuales.

### 2.3.3. User Journey Mapping.

En esta sección se presentan los User Journey Mapping de los segmentos objetivos, que realizamos con el fin de dar a entender cómo se siente nuestro usuario al usar la aplicación, detallando cada paso que realiza y las emociones que experimenta.

**Paciente:**

![JourneyMap1.png](images/JourneyMap1.png)

**Doctor:**

![JourneyMap2.png](images/JourneyMap2.png)

### 2.3.4. Empathy Mapping.

En esta sección mostramos los empathy mapping de los segmentos objetivos realizados con la información recopilada de componentes anteriores.

**Paciente:**
![Empathymap.png](images/Empathymap.png)IMAGEN

**Doctor:**

![Empathymap2.png](images/Empathymap2.png)**IMAGEN**

### 2.3.5. As-is Scenario Mapping.

En esta sección se realizaron las distintas etapas de preparación, tales como la lluvia de ideas individual, revisión e identificación de fases como columnas, para conseguir los As-is Scenario Mapping de los segmentos objetivos.

**Para el segmento 1 (Pacientes):**

![AsIs1.jpg](images/AsIs1.jpg)IMAGEN

**Para el segmento 2 (Doctores):**

![AsIs2.jpg](images/AsIs2.jpg)IMAGEN

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.

- Segmento Objetivo: Paciente

<img src="CAP3-IMAGES/ToBe1.png" alt="tobe1">

- Segmento Objetivo: Doctor

<img src="CAP3-IMAGES/ToBe2.png" alt="tobe2">

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

| US  | Título                                  | Descripción                                                                                                                                            | Criterios de aceptación                                                                                                                                                                                                       | Epic relacionada |
| --- | --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- |
| 01  | Visualizar datos personales y médicos   | Como paciente, quiero poder ver mis datos personales y médicos en la app, para tener control sobre mi información.                                     | **Escenario:** Acceso a perfil <br> **Dado** que estoy logueado en la app móvil, <br> **Cuando** accedo a la sección "Mi perfil", <br> **Entonces** puedo visualizar mis datos personales y médicos actualizados.             | 04               |
| 02  | Ver ritmo cardiaco desde el celular     | Como paciente, quiero poder ver mi ritmo cardiaco actual desde la aplicación móvil, para monitorear mi estado de salud.                                | **Escenario:** Visualización en tiempo real <br> **Dado** que tengo el sensor conectado, <br> **Cuando** ingreso a la app, <br> **Entonces** puedo ver una gráfica con mi ritmo cardiaco actual.                              | 04               |
| 03  | Recibir notificaciones de alerta        | Como paciente, quiero recibir notificaciones push si se detecta un ritmo anormal, para estar informado de cualquier cambio importante.                 | **Escenario:** Notificación activa <br> **Dado** que mi ritmo cardiaco supera el límite, <br> **Cuando** se detecta la anomalía, <br> **Entonces** recibo una alerta en el teléfono móvil.                                    | 04               |
| 04  | Configurar preferencias de notificación | Como paciente, quiero configurar mis preferencias de notificación en la app móvil, para decidir cómo y cuándo recibir alertas sobre mi ritmo cardiaco. | **Escenario:** Ajustar preferencias <br> **Dado** que estoy en la sección de configuración, <br> **Cuando** modifico mis opciones de notificación, <br> **Entonces** el sistema guarda mis preferencias para futuras alertas. | 04               |

---

### Epic 05 - Gestión de citas médicas desde la app

| US  | Título                               | Descripción                                                                                                                 | Criterios de aceptación                                                                                                                                                                                                        | Epic relacionada |
| --- | ------------------------------------ | --------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------- |
| 01  | Agendar una cita desde la app        | Como paciente, quiero poder agendar una cita médica desde mi aplicación móvil, para facilitar la programación de consultas. | **Escenario:** Crear nueva cita <br> **Dado** que estoy en la app móvil, <br> **Cuando** ingreso a la sección de citas y selecciono una fecha y hora, <br> **Entonces** se agenda la cita en el sistema.                       | 05               |
| 02  | Ver citas programadas                | Como paciente, quiero consultar mis citas futuras, para saber cuándo debo asistir a consulta.                               | **Escenario:** Consultar agenda <br> **Dado** que tengo citas agendadas, <br> **Cuando** ingreso a la sección de citas, <br> **Entonces** puedo ver la lista de fechas, horas y médicos asignados.                             | 05               |
| 03  | Cancelar o reprogramar una cita      | Como paciente, quiero poder cancelar o reprogramar una cita, para reorganizar mi agenda si tengo algún imprevisto.          | **Escenario:** Modificar cita <br> **Dado** que tengo una cita agendada, <br> **Cuando** accedo a su detalle, <br> **Entonces** puedo modificar la fecha/hora o cancelar si es necesario.                                      | 05               |
| 04  | Sincronización con agenda del doctor | Como doctor, quiero ver las citas programadas por los pacientes desde la app web, para organizar mejor mi horario.          | **Escenario:** Visualización de agenda <br> **Dado** que los pacientes agendan citas desde la app, <br> **Cuando** ingreso a la sección de agenda como doctor, <br> **Entonces** veo todas las citas asignadas en tiempo real. | 05               |

## 3.3. Impact Mapping.

- Paciente
  <img src="CAP3-IMAGES/Impact1.png" alt="ImpactMapPaciente">

- Doctor
  <img src="CAP3-IMAGES/Impact2.png" alt="ImpactMapDoctor">

## 3.4. Product Backlog.

| Orden | Epic ID | User Story ID | Título                                   | Descripción                                                                                                                                            | Story Points |
| ----- | ------- | ------------- | ---------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------ |
| 1     | EP01    | US01          | Visualizar ritmo cardiaco en tiempo real | Como doctor, quiero visualizar el ritmo cardiaco de mis pacientes en tiempo real, para monitorear su estado de salud.                                  | 5            |
| 2     | EP01    | US02          | Seleccionar paciente para monitoreo      | Como doctor, quiero seleccionar a un paciente específico, para revisar únicamente su información de ritmo cardiaco.                                    | 3            |
| 3     | EP01    | US03          | Actualización automática de datos        | Como doctor, quiero que los datos del ritmo cardiaco se actualicen automáticamente, para evitar tener que recargar la vista.                           | 3            |
| 4     | EP01    | US04          | Ver estado de conexión del sensor        | Como doctor, quiero saber si el sensor está enviando datos correctamente, para garantizar que el monitoreo es fiable.                                  | 2            |
| 5     | EP02    | US01          | Alerta visual en la interfaz             | Como doctor, quiero recibir una alerta visual si un paciente presenta un ritmo elevado, para poder actuar de inmediato.                                | 5            |
| 6     | EP02    | US02          | Confirmación manual de alertas críticas  | Como doctor, quiero confirmar manualmente que he visto una alerta crítica, para asegurar que no se pase por alto ninguna situación urgente.            | 3            |
| 7     | EP02    | US03          | Notificación por correo electrónico      | Como doctor, quiero recibir alertas importantes también por correo electrónico, para asegurarme de no perderme notificaciones críticas.                | 2            |
| 8     | EP02    | US04          | Registro de alertas anteriores           | Como doctor, quiero revisar las alertas anteriores de un paciente, para tener un historial de sus eventos críticos.                                    | 3            |
| 9     | EP03    | US01          | Registrar contacto de emergencia         | Como paciente, quiero registrar un contacto de emergencia, para que sea notificado si tengo una emergencia cardiaca.                                   | 3            |
| 10    | EP03    | US02          | Envío automático de SMS en alerta        | Como paciente, quiero que se envíe un SMS automático a mi contacto en caso de ritmo elevado, para que me ayuden rápido.                                | 5            |
| 11    | EP03    | US03          | Personalizar mensaje de emergencia       | Como paciente, quiero personalizar el mensaje SMS de alerta, para que mi contacto entienda mejor la situación.                                         | 2            |
| 12    | EP03    | US04          | Ver historial de mensajes enviados       | Como paciente, quiero ver los SMS que se han enviado a mi contacto, para llevar un registro de las alertas.                                            | 2            |
| 13    | EP04    | US01          | Visualizar datos personales y médicos    | Como paciente, quiero ver mis datos médicos y personales en la app, para tener acceso a mi información de salud.                                       | 2            |
| 14    | EP04    | US02          | Ver ritmo cardiaco desde el celular      | Como paciente, quiero visualizar mi ritmo cardiaco actual en la app móvil, para monitorear mi estado de salud.                                         | 5            |
| 15    | EP04    | US03          | Recibir notificaciones de alerta         | Como paciente, quiero recibir notificaciones push si tengo un ritmo cardiaco anormal, para estar al tanto de emergencias.                              | 3            |
| 16    | EP04    | US04          | Configurar preferencias de notificación  | Como paciente, quiero configurar mis preferencias de notificación en la app móvil, para decidir cómo y cuándo recibir alertas sobre mi ritmo cardiaco. | 2            |
| 17    | EP05    | US01          | Agendar una cita desde la app            | Como paciente, quiero agendar citas médicas desde la app móvil, para facilitar la planificación de mis consultas.                                      | 3            |
| 18    | EP05    | US02          | Ver citas programadas                    | Como paciente, quiero ver mis citas médicas futuras, para no olvidar mis consultas.                                                                    | 2            |
| 19    | EP05    | US03          | Cancelar o reprogramar una cita          | Como paciente, quiero modificar o cancelar una cita desde la app, para gestionar mejor mi agenda.                                                      | 3            |
| 20    | EP05    | US04          | Sincronización con agenda del doctor     | Como doctor, quiero ver las citas que agendan mis pacientes, para tener mi agenda médica organizada.                                                   | 3            |

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

<img src="CAP4-IMAGES/Bounded-Context-Canvases-Sensor monitoring.jpg" alt="Bounded-Context-Canvases-Sensor monitoring">

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

**Customer/Supplier**
- Medical History & Analytics es cliente de Sensor Monitoring (supplier).

- Notification Service es cliente de Alert & Emergency Handling (supplier).

- Sensor Monitoring es cliente de IAM (para validar tokens y sesiones).

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
