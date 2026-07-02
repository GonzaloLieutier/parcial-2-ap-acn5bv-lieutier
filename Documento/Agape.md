# Parcial 2 -- Administración de Proyectos.

**Materia:** Administración de Proyectos.

**Alumno:** Gonzalo Lieutier

**Proyecto:** Agape - Aplicación de gestión de grupos.

# Introducción

En la actualidad, muchas parroquias gestionan la inscripción a sus grupos y actividades mediante formularios, mensajes de WhatsApp o de manera presencial. Esto puede dificultar la organización, la comunicación entre los distintos grupos.
Con el objetivo de mejorar este proceso, se propone el desarrollo de **Ágape**, una aplicación que permitirá a los miembros de la comunidad conocer los grupos disponibles, consultar información relevante e inscribirse de forma sencilla desde un único lugar. Además, la aplicación facilitará a los coordinadores la administración de los grupos y la comunicación con sus integrantes.
En este documento se presenta la planificación inicial del proyecto, incluyendo la definición de los objetivos, el análisis de los principales interesados, la metodología de trabajo seleccionada, los requerimientos funcionales y la organización de las tareas mediante un tablero de seguimiento.


# Objetivo SMART

Desarrollar Ágape, una aplicación móvil y web que permita a los miembros de la parroquia consultar los grupos disponibles, inscribirse a ellos y acceder a información sobre actividades y encuentros. El proyecto tendrá como objetivo finalizar el desarrollo del producto mínimo viable (MVP) en un plazo de cuatro meses, logrando que al menos el 80 % de las inscripciones a los grupos parroquiales se realicen a través de la aplicación durante los primeros tres meses posteriores a su implementación.

# Análisis de Stakeholders

Los stakeholders son todas aquellas personas o grupos que tienen interés o se ven afectados por el desarrollo del proyecto. Identificar a los principales interesados permite comprender sus necesidades, expectativas y el nivel de influencia que poseen sobre el éxito de la aplicación **Ágape**.

| Stakeholder | Interés | Influencia | Necesidades / Expectativas |
|--------------|----------|------------|----------------------------|
| Cura | Alto | Alta | Contar con una herramienta que facilite la organización de la comunidad, mejore la comunicación y permita supervisar la actividad de los distintos grupos parroquiales. |
| Coordinadores de grupos | Alto | Alta | Administrar los integrantes de sus grupos, publicar novedades, gestionar inscripciones y comunicarse con los participantes de manera sencilla. |
| Comunidad de la parroquia | Alto | Media | Conocer los grupos disponibles, inscribirse fácilmente, consultar horarios, recibir notificaciones y mantenerse informados sobre las actividades parroquiales. |


## Perfil de los Stakeholders

### Cura

Es el principal impulsor del proyecto y quien representa a la parroquia. Su objetivo es mejorar la organización de la comunidad mediante una herramienta que centralice la información y facilite la participación de los feligreses.

### Coordinadores de grupos

Son los responsables de gestionar cada grupo parroquial. El objetivo es que usen la aplicación para administrar las inscripciones, compartir información importante y mantener el contacto con los integrantes.

### Comunidad de la parroquia

Son los usuarios finales de la aplicación. Esperan tener una plataforma simple e intuitiva que les permita conocer las propuestas de la parroquia, inscribirse a los grupos de interés y acceder a toda la información necesaria desde un mismo lugar.

# Metodología ágil seleccionada

Para el desarrollo de la aplicacion se usaran dos metodologias agiles: Scrum + Kanban. Esto permite organizar el trabajo en ciclos cortos de desarrollo, priorizar las funcionalidades más importantes y visualizar el avance de cada tarea durante todo el proyecto.

## Scrum

Scrum se va a usar para planificar el trabajo en sprints de 2 semanas, en los cuales se van a desarrollar incrementos funcionales del producto. Al finalizar cada sprint, el equipo va a revisar lo construido y ajustaria las prioridades según las necesidades del proyecto.

Los roles principales serán:

| Rol | Responsabilidad |
|------|----------------|
| Product Owner | Representar las necesidades de la parroquia, priorizar funcionalidades y validar que el producto responda al objetivo del proyecto. |
| Scrum Master / equipo de coordinación | Facilitar la organización del trabajo, remover obstáculos y asegurar que se respeten las prácticas ágiles. |
| Equipo de desarrollo | Diseñar, construir y probar las funcionalidades de la aplicación. |

Los eventos de Scrum que se aplicarán son:

| Eventos | Descripción |
|------------|-------------|
| Planificación del sprint | Definir las tareas y objetivos que se van a trabajar durante las siguientes 2 semanas. |
| Daily breve | Revisar avances, bloqueos y próximos pasos del equipo. |
| Review | Presentar el incremento desarrollado a los interesados principales. |
| Retrospectiva | Analizar qué funcionó bien, qué se puede mejorar y qué ajustes aplicar en el próximo sprint. |

## Kanban

Kanban se va a usar como herramienta visual para realizar el seguimiento de las tareas. El tablero se usa para conocer el estado de cada actividad y detectar posibles bloqueos durante el desarrollo.

El tablero va a contar con estas columnas:

| Columna | Descripción |
|----------|-------------|
| Pendiente | Tareas identificadas que todavía no empezaron. |
| En proceso | Tareas que el equipo está desarrollando. |
| En revisión | Funcionalidades terminadas que deben validarse o corregirse. |
| Finalizado | Tareas completadas y aceptadas. |

## Justificación

Se uso scrum y kanban en el proyecto ya que necesita avanzar de manera ordenada hacia un MVP en un plazo de cuatro meses, pero también necesita flexibilidad para recibir feedback de los interesados.

Scrum va a permitir dividir el desarrollo en etapas cortas, priorizando funcionalidades esenciales como la consulta de grupos, la inscripción de miembros, la administración por parte de coordinadores y la comunicación con la comunidad. Y kanban va a facilitar el seguimiento visual del trabajo y ayuda a que el equipo pueda ver las tareas pendientes, bloqueadas o listas para revisión.

De esta manera, la metodología elegida permite entregar valor de forma incremental, validar avances con los usuarios, y ajustar el alcance del producto según las necesidades que aparezcan durante el desarrollo.

