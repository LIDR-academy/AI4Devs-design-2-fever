# Previo

Claro, aquí tienes la definición detallada de los tres casos de uso enviados para la plataforma LTI ATS:

1. Crear y Publicar Oferta de Empleo
   Descripción:
   Este caso de uso permite a los reclutadores crear y distribuir ofertas de empleo de manera eficiente. El proceso incluye:

Ingreso de detalles del puesto: El reclutador ingresa la descripción del puesto, requisitos, ubicación, y cualquier otra información relevante.
Selección de canales de publicación: El reclutador elige los portales de empleo, redes sociales o sitios web donde desea que se publique la oferta.
Automatización de la distribución: LTI ATS se encarga de distribuir automáticamente la oferta a los canales seleccionados, ahorrando tiempo y esfuerzo del reclutador.
Flujo:

El reclutador accede al módulo de creación de oferta.
Ingresan los detalles del puesto (descripción, requisitos, etc.).
Eligen los canales (portales de empleo, redes sociales, etc.).
La plataforma distribuye automáticamente la oferta en los canales seleccionados.
Objetivo:
Facilitar la creación y distribución de ofertas de empleo, ahorrando tiempo y mejorando el alcance de la publicación.

2. Gestión de Candidatos
   Descripción:
   Este caso de uso cubre el proceso desde que los candidatos se postulan hasta la organización de sus aplicaciones en la plataforma:

Recepción y almacenamiento de aplicaciones: Cuando un candidato se postula a una oferta, sus datos y currículum son almacenados en la base de datos del ATS.
Filtrado y preselección automatizada: Utilizando algoritmos de IA, el sistema filtra y clasifica los candidatos según criterios definidos (experiencia, habilidades, compatibilidad).
Ranking de candidatos: El sistema genera un ranking de los candidatos más prometedores para facilitar la selección.
Flujo:

El candidato se postula a una oferta.
El sistema almacena la información y el CV del candidato.
El ATS aplica filtros y clasifica los candidatos según los criterios definidos.
El reclutador puede ver el ranking de candidatos más relevantes.
Objetivo:
Optimizar la gestión de aplicaciones, reduciendo el tiempo de revisión y ayudando a los reclutadores a identificar rápidamente a los candidatos adecuados.

3. Colaboración y Seguimiento del Proceso de Selección
   Descripción:
   Este caso de uso permite a los reclutadores y gerentes colaborar en tiempo real durante todo el proceso de selección, facilitando la toma de decisiones y el seguimiento del progreso:

Comunicación en tiempo real: Los reclutadores y gerentes de contratación pueden interactuar a través de herramientas de comunicación internas (chats, comentarios, notificaciones).
Actualización del estado de los candidatos: El sistema permite que los miembros del equipo actualicen el estado de los candidatos en cada etapa (entrevista, evaluación, oferta, etc.).
Feedback y toma de decisiones: Los equipos colaboran en tiempo real para intercambiar feedback sobre los candidatos, tomar decisiones más rápidamente y coordinar las entrevistas.
Flujo:

El reclutador o gerente de contratación actualiza el estado de un candidato en el sistema.
El equipo colabora a través de comentarios, chats o reuniones virtuales.
El sistema registra el progreso del candidato y genera informes en tiempo real.
Objetivo:
Mejorar la eficiencia en la toma de decisiones, reducir el tiempo de respuesta y asegurar una colaboración fluida entre los reclutadores y los gerentes.

# User Stories

### User Story 1: Crear y Publicar Oferta de Empleo

**Como** reclutador,  
**Quiero** crear y publicar ofertas de empleo de manera automatizada,  
**Para** llegar a un mayor número de candidatos rápidamente y reducir el tiempo dedicado a la publicación manual.

#### Descripción:

El reclutador debe poder crear una oferta de empleo y distribuirla automáticamente a múltiples canales (portales de empleo, redes sociales, etc.), lo que le permitirá reducir el tiempo de publicación y aumentar el alcance de la oferta.

#### Criterios de Aceptación:

- **Dado que** un reclutador ha creado una oferta de empleo,  
  **Cuando** selecciona los canales de publicación,  
  **Entonces** la plataforma distribuye automáticamente la oferta a los canales seleccionados.
- **Dado que** un reclutador ha creado una oferta de empleo,  
  **Cuando** hace clic en el botón de "publicar",  
  **Entonces** la oferta se muestra en el portal de empleo y en las redes sociales elegidas sin intervención manual.

#### Notas Adicionales:

- Los canales de publicación deben incluir opciones como portales de empleo populares y redes sociales.
- La plataforma debería permitir editar la oferta antes de publicarla en los canales seleccionados.

#### Tareas:

1. Crear una interfaz para ingresar los detalles de la oferta de empleo.
2. Desarrollar integración con APIs de portales de empleo y redes sociales.
3. Probar la distribución automática en diferentes canales.

---

### User Story 2: Gestión de Candidatos

**Como** reclutador,  
**Quiero** recibir y filtrar automáticamente las aplicaciones de los candidatos,  
**Para** identificar rápidamente los candidatos más relevantes y ahorrar tiempo en la selección.

#### Descripción:

El reclutador recibe aplicaciones de candidatos, y la plataforma utiliza filtros y algoritmos de IA para clasificarlos según criterios como habilidades, experiencia y compatibilidad. Esto facilita una preselección eficiente.

#### Criterios de Aceptación:

- **Dado que** un candidato ha postulado a una oferta,  
  **Cuando** su información y CV son registrados en el sistema,  
  **Entonces** los criterios de preselección se aplican automáticamente para clasificar a los candidatos.
- **Dado que** un reclutador tiene múltiples candidatos,  
  **Cuando** accede a la lista de candidatos,  
  **Entonces** el sistema muestra los perfiles ordenados por el ranking de relevancia según los filtros definidos.

#### Notas Adicionales:

- Los algoritmos de IA deben estar ajustados a los requisitos de la oferta de empleo.
- El reclutador debe tener la opción de revisar los detalles de los candidatos antes de aplicar cualquier filtro.

#### Tareas:

1. Desarrollar el sistema de filtrado automatizado de candidatos.
2. Integrar IA para clasificación según criterios definidos.
3. Crear una interfaz para visualizar los candidatos filtrados y sus detalles.

---

### User Story 3: Colaboración y Seguimiento del Proceso de Selección

**Como** reclutador y gerente de contratación,  
**Quiero** colaborar en tiempo real con mi equipo para evaluar y dar seguimiento a los candidatos,  
**Para** tomar decisiones más rápidas y mejorar la comunicación en cada etapa del proceso de selección.

#### Descripción:

Los reclutadores y gerentes de contratación pueden colaborar en tiempo real, compartiendo comentarios y actualizaciones sobre el progreso de los candidatos. Esto facilita la toma de decisiones y mejora la coordinación del equipo.

#### Criterios de Aceptación:

- **Dado que** un reclutador o gerente actualiza el estado de un candidato,  
  **Cuando** se realiza una actualización,  
  **Entonces** todos los miembros del equipo reciben una notificación sobre el cambio.
- **Dado que** un reclutador ha dejado un comentario sobre un candidato,  
  **Cuando** el gerente revisa el perfil del candidato,  
  **Entonces** el comentario es visible y accesible para su revisión.

#### Notas Adicionales:

- Las notificaciones deben ser configurables para no saturar a los usuarios con alertas innecesarias.
- El sistema debe permitir agregar comentarios específicos a cada candidato en diferentes etapas del proceso.

#### Tareas:

1. Desarrollar una funcionalidad de chat y comentarios en el perfil de los candidatos.
2. Crear una funcionalidad de notificación para actualizaciones de estado de los candidatos.
3. Implementar una interfaz para seguimiento del progreso de los candidatos con todos los comentarios y actualizaciones.

## Backlog

Backlog Priorizado de LTI ATS

1. Crear y Publicar Oferta de Empleo
   Valor del Negocio: Alto. La capacidad de publicar ofertas rápidamente y en múltiples canales es fundamental para captar a los mejores candidatos.
   Urgencia: Alta. Publicar ofertas de empleo es la primera acción del proceso de reclutamiento, lo que la convierte en una función crítica.
   Dependencias: Ninguna significativa.
   Coste de Implementación: Moderado. Implica integración con múltiples canales, pero la funcionalidad no es compleja.
   Riesgos y Obstáculos: Bajo. La integración con APIs de portales de empleo y redes sociales podría presentar algunos desafíos técnicos, pero no son riesgos mayores.
   Feedback del Usuario: Los reclutadores necesitan esta funcionalidad para mejorar la rapidez y alcance de sus ofertas.
   Madurez Tecnológica: Alta. Existen soluciones maduras para la integración con portales y redes sociales.
   Prioridad: Alta

2. Gestión de Candidatos
   Valor del Negocio: Alto. Facilita la preselección automática y reduce la carga de trabajo manual de los reclutadores.
   Urgencia: Alta. Una vez que las ofertas son publicadas, la gestión eficiente de los candidatos es crítica para el proceso.
   Dependencias: Depende de la disponibilidad de los algoritmos de filtrado e integración con la base de datos de los candidatos.
   Coste de Implementación: Alto. Implica desarrollo de algoritmos de IA y diseño de una interfaz de usuario clara para la visualización de los candidatos.
   Riesgos y Obstáculos: Moderado. La implementación de IA puede ser compleja, especialmente para garantizar que los criterios de selección sean precisos y justos.
   Feedback del Usuario: La automatización en la preselección es muy valorada por los usuarios para reducir el sesgo y el tiempo de selección.
   Madurez Tecnológica: Moderada. La IA aplicada a la selección de candidatos es un área avanzada, pero existen buenas soluciones disponibles.
   Prioridad: Alta

3. Colaboración y Seguimiento del Proceso de Selección
   Valor del Negocio: Muy Alto. Facilita la comunicación entre equipos y acelera la toma de decisiones, lo que impacta directamente en la eficiencia del proceso de selección.
   Urgencia: Moderada. Aunque crucial, se puede realizar en etapas posteriores, una vez que las otras funcionalidades estén implementadas.
   Dependencias: Depende de la implementación de las funcionalidades de gestión de candidatos y creación de ofertas.
   Coste de Implementación: Moderado. Implica el desarrollo de un sistema de colaboración en tiempo real, como chat y comentarios, que podría requerir integración con otras plataformas.
   Riesgos y Obstáculos: Bajo. La funcionalidad de colaboración es relativamente sencilla, aunque la integración con otros sistemas de comunicación podría ser un reto.
   Feedback del Usuario: Muy alto. Los usuarios (reclutadores y gerentes) necesitan coordinarse constantemente, por lo que una herramienta de colaboración es esencial.
   Madurez Tecnológica: Alta. Las soluciones de chat y colaboración son estándar en muchas aplicaciones.
   Prioridad: Alta

### Resumen del Backlog Priorizado:

| **#** | **User Story**                                      | **Valor del Negocio** | **Urgencia** | **Coste de Implementación** | **Riesgos** | **Prioridad** |
| ----- | --------------------------------------------------- | --------------------- | ------------ | --------------------------- | ----------- | ------------- |
| 1     | Crear y Publicar Oferta de Empleo                   | Alto                  | Alta         | Moderado                    | Bajo        | Alta          |
| 2     | Gestión de Candidatos                               | Alto                  | Alta         | Alto                        | Moderado    | Alta          |
| 3     | Colaboración y Seguimiento del Proceso de Selección | Muy Alto              | Moderada     | Moderado                    | Bajo        | Alta          |

---

## Estimación Detallada de cada ítem del Backlog:

| **#** | **User Story**                                      | **Impacto en el Usuario y Valor del Negocio**                                                                                    | **Urgencia (Basada en Tendencias del Mercado y Feedback de Usuarios)**                                                  | **Complejidad y Esfuerzo Estimado de Implementación**                                                            | **Riesgos y Dependencias entre Tareas**                                                |
| ----- | --------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| 1     | Crear y Publicar Oferta de Empleo                   | Alto. Mejora la visibilidad de las ofertas, aumenta la rapidez en la captación de candidatos.                                    | Alta. Es la primera etapa del proceso de reclutamiento. La rapidez es clave.                                            | Moderado. Requiere integración con múltiples canales y portales, pero es una funcionalidad estándar.             | Dependencia de la integración con APIs externas para la publicación.                   |
| 2     | Gestión de Candidatos                               | Alto. Permite gestionar y filtrar automáticamente a los mejores candidatos, reduciendo el tiempo y los errores.                  | Alta. La eficiencia en la gestión de candidatos es clave para mantener el flujo de trabajo optimizado.                  | Alto. Implementación de IA para la preselección, integración de filtros avanzados y desarrollo de base de datos. | Dependencia de la calidad de los algoritmos de IA y la base de datos de candidatos.    |
| 3     | Colaboración y Seguimiento del Proceso de Selección | Muy Alto. Mejora la coordinación entre los equipos de selección, reduce los tiempos de respuesta y mejora la toma de decisiones. | Moderada. No es la primera prioridad, pero la colaboración continua es crucial para mantener la eficiencia del proceso. | Moderado. Desarrollo de herramientas de comunicación interna y seguimiento, integración con otros sistemas.      | Dependencia de la implementación de la gestión de candidatos y la creación de ofertas. |

---

## Prioridad Final:

1. **Crear y Publicar Oferta de Empleo**: Alta prioridad, ya que es la primera acción del reclutamiento y tiene un gran impacto en la eficiencia.
2. **Gestión de Candidatos**: Alta prioridad debido al alto valor que genera en la reducción de tiempo y errores en la selección.
3. **Colaboración y Seguimiento del Proceso de Selección**: Alta prioridad, aunque un poco menos urgente que las anteriores, pero fundamental para la toma de decisiones rápidas.

---

## Tickets de trabajo

# Ticket 1: Crear y Publicar Oferta de Empleo

**Descripción**:  
El objetivo de esta tarea es implementar la funcionalidad que permita a los reclutadores crear y publicar ofertas de empleo en múltiples canales. La tarea debe integrar portales de empleo y redes sociales, optimizando el proceso de difusión de ofertas.

**Criterios de Aceptación**:

- Los reclutadores pueden crear una oferta de empleo ingresando los datos esenciales como título, descripción, requisitos, y ubicación.
- La plataforma debe permitir la publicación automática de la oferta en los canales predefinidos (portales de empleo, redes sociales, etc.).
- Debe ser posible revisar las ofertas publicadas y actualizar su estado (abierta/cerrada).
- La funcionalidad debe ser accesible desde el dashboard del reclutador.

**Prioridad**: Alta

**Estimación**: 5 puntos de historia

**Asignado a**: Equipo de Backend y Frontend

**Etiquetas**: Reclutamiento, Frontend, Backend, Sprint 1

**Comentarios**:

- Verificar las integraciones con los APIs de portales de empleo.
- Considerar la adaptabilidad de la UI para diferentes tamaños de pantalla.

**Enlaces**:

- Documento de Especificaciones Funcionales para la Creación y Publicación de Ofertas de Empleo

**Historial de Cambios**:

- 16/02/2025: Creado por [nombre]
- 17/02/2025: Prioridad actualizada a Alta por [nombre]

---

# Ticket 2: Gestión de Candidatos

**Descripción**:  
Implementar el sistema de gestión de candidatos, que permita a los reclutadores almacenar, organizar y filtrar aplicaciones automáticamente. Utilizar algoritmos de IA para mejorar la preselección y clasificación de candidatos.

**Criterios de Aceptación**:

- Los candidatos que se postulan deben ser añadidos automáticamente a la base de datos con la información de su CV.
- La plataforma debe aplicar filtros automáticos basados en criterios como experiencia, habilidades y compatibilidad con el puesto.
- Los candidatos deben ser clasificados en un ranking, destacando los más relevantes.
- Los reclutadores pueden visualizar, editar y filtrar candidatos fácilmente desde el panel.

**Prioridad**: Alta

**Estimación**: 8 puntos de historia

**Asignado a**: Equipo de Backend (IA) y Frontend

**Etiquetas**: IA, Backend, Frontend, Sprint 2

**Comentarios**:

- Validar los algoritmos de IA con un conjunto de datos de prueba.
- Asegurarse de que los filtros sean fácilmente personalizables por los reclutadores.

**Enlaces**:

- Documento de Especificaciones Funcionales para la Gestión de Candidatos

**Historial de Cambios**:

- 16/02/2025: Creado por [nombre]
- 17/02/2025: Estimación actualizada a 8 puntos por [nombre]

---

# Ticket 3: Colaboración y Seguimiento del Proceso de Selección

**Descripción**:  
Crear una funcionalidad que permita a los reclutadores y gerentes colaborar en tiempo real, realizando seguimiento a los candidatos, proporcionando retroalimentación y gestionando entrevistas dentro de la plataforma.

**Criterios de Aceptación**:

- Los reclutadores y gerentes pueden agregar comentarios y notas a los perfiles de los candidatos.
- Debe existir la opción de agendar entrevistas y notificar a los involucrados.
- Los estados del candidato (entrevista, rechazo, etc.) deben ser actualizables.
- El sistema debe permitir ver el progreso de cada candidato en el proceso de selección.

**Prioridad**: Alta

**Estimación**: 7 puntos de historia

**Asignado a**: Equipo de Backend y Frontend

**Etiquetas**: Colaboración, Frontend, Backend, Sprint 3

**Comentarios**:

- Asegurar que las notificaciones y la interfaz de comentarios sean intuitivas.
- Verificar la integración con calendarios externos para las entrevistas.

**Enlaces**:

- Documento de Especificaciones Funcionales para la Colaboración y Seguimiento del Proceso

**Historial de Cambios**:

- 16/02/2025: Creado por [nombre]
- 17/02/2025: Estimación ajustada a 7 puntos por [nombre]

# Estimación

A continuación, realizo una estimación del esfuerzo de los tickets utilizando la **metodología de puntos de historia** basada en la secuencia de **Fibonacci** (1, 2, 3, 5, 8, 13, 21), que es comúnmente utilizada en la planificación ágil debido a su simplicidad y efectividad para capturar la incertidumbre en las estimaciones.

Aquí están los tickets con su respectiva estimación:

### Ticket 1: Crear y Publicar Oferta de Empleo

- **Estimación de Esfuerzo**: **5 puntos de historia**
- **Rationale**: Este ticket incluye múltiples componentes (crear, publicar, y administrar ofertas), pero no es tan complejo como las integraciones de IA o el seguimiento en tiempo real. Se trata de una funcionalidad de nivel medio en términos de complejidad.

### Ticket 2: Gestión de Candidatos

- **Estimación de Esfuerzo**: **8 puntos de historia**
- **Rationale**: La implementación de un sistema de clasificación automático con algoritmos de IA, junto con la integración de filtros y la base de datos, hace que este ticket sea relativamente complejo. Además, los algoritmos de IA agregan una capa de incertidumbre en la estimación.

### Ticket 3: Colaboración y Seguimiento del Proceso de Selección

- **Estimación de Esfuerzo**: **8 puntos de historia**
- **Rationale**: Este ticket incluye varias interacciones entre usuarios (reclutadores, gerentes) y funcionalidades en tiempo real (comentarios, notificaciones, programación de entrevistas). La complejidad de integrar múltiples flujos de trabajo y mantener la integridad de la colaboración aumenta el esfuerzo necesario.

### Resumen de las estimaciones:

| **Ticket**                                 | **Estimación de Esfuerzo** | **Rationale**                                                         |
| ------------------------------------------ | -------------------------- | --------------------------------------------------------------------- |
| **Crear y Publicar Oferta de Empleo**      | 5 puntos de historia       | Funcionalidad de nivel medio, sin integraciones complejas.            |
| **Gestión de Candidatos**                  | 8 puntos de historia       | Requiere implementación de IA y algoritmos de clasificación.          |
| **Colaboración y Seguimiento del Proceso** | 8 puntos de historia       | Interacciones en tiempo real y múltiples flujos de trabajo complejos. |

Estas estimaciones reflejan el esfuerzo relativo requerido para completar cada ticket, tomando en cuenta los componentes involucrados y la complejidad técnica.
