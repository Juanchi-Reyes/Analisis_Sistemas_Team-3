# Decisiones Humanas
## Consolidación de decisiones del equipo frente a las propuestas de IA

La utilización de inteligencia artificial durante el desarrollo del taller se realizó como herramienta de apoyo para generar alternativas, ampliar el análisis y realizar críticas sobre las propuestas iniciales. Las decisiones definitivas no fueron tomadas directamente por la IA. 

El equipo revisó las propuestas, contrastó su pertinencia con el enunciado del problema, los conceptos investigados y las condiciones conocidas del proyecto, y posteriormente determinó qué propuestas conservar, modificar o rechazar.

---

### Fase 1: Stakeholders

| Propuesta IA | ¿Qué verificamos? | Decisión del equipo | Razón / Evidencia |
| :--- | :--- | :--- | :--- |
| **Separar a los estudiantes** en tres stakeholders (con dificultades, con retrasos y que quieren consultar su progreso). | Se revisó el concepto de stakeholder y se identificó que los tres grupos corresponden al mismo grupo general de usuarios: Estudiantes. | **Rechazar** la separación y agruparlos como un único stakeholder: Estudiantes. | La separación generaba redundancia y dificultaba la representación de los actores reales del sistema. Constituyen un grupo de interés común con diferentes necesidades. |
| **Programa académico** como stakeholder. | Se analizó su relación con el sistema y se comparó con las responsabilidades que debería tener cada actor dentro del proyecto. | **Rechazar/Reemplazar** por Coordinación del Programa. | La coordinación representa de manera más concreta las responsabilidades relacionadas con los flujos académicos, reglas de negocio y necesidades operativas. |
| **Agregar Personal de TI y Líderes de Proyecto** como stakeholders. | Se verificó que ambos grupos tienen responsabilidades diferentes y una relación directa con la implementación y funcionamiento. | **Aceptar** ambos stakeholders. | TI participa en arquitectura y seguridad. Los líderes sirven como enlace con los equipos de campo. |
| **Dirección Académica** como stakeholder principal. | Se revisó el papel de la dirección dentro del contexto planteado y su capacidad para decidir sobre la implementación. | **Aceptar.** | El enunciado indica que la Dirección Académica está considerando implementar un sistema de seguimiento, evidenciando su poder de decisión. |

---

### Fase 2: PESTEL

| Propuesta IA | ¿Qué verificamos? | Decisión del equipo | Razón / Evidencia |
| :--- | :--- | :--- | :--- |
| **Generar factores PESTEL** para las dimensiones Política, Económica y Ecológica/Ambiental. | Se revisó cada factor para diferenciar condiciones externas del entorno de problemas internos del sistema, identificando qué información faltaba confirmar. | **Conservar** como alternativas o hipótesis pendientes de validación. | Al ser un escenario hipotético, no se cuenta con información institucional específica para afirmar hechos sobre presupuestos o impacto ambiental. |
| **Político:** políticas institucionales de transformación digital y herramientas. | Se verificó que afectarían la implementación, pero no se dispone de una política institucional real. | **Aceptar** como factores relevantes pendientes de validación. | Podrían determinar si el sistema reemplaza o se integra con plataformas existentes. |
| **Económico:** existencia de presupuesto disponible. | Una solución tecnológica requiere recursos, pero no se conoce un presupuesto real asignado. | **Modificar/Mantener** como supuesto pendiente de validación. | El equipo decidió no afirmar que existe financiación ni determinar costos sin información real. |
| **Social:** aceptación de los usuarios. | Estudiantes y docentes tendrían que usar el sistema, pero no hay encuestas de usabilidad previas. | **Mantener** como hipótesis pendiente de validación. | Se necesitarían pruebas con los usuarios para determinar su aceptación real. |
| **Tecnológico:** integración con plataformas existentes. | El problema plantea que la información está distribuida. Una nueva solución necesitaría interoperar. | **Aceptar** como factor tecnológico relevante. | El enunciado evidencia la fragmentación, aunque falte validar las tecnologías específicas utilizadas. |
| **Ecológico:** digitalización para reducir documentos físicos. | Podría disminuir procesos en papel, pero no se conoce cuánto se usa actualmente. | **Conservar** como posibilidad, no como beneficio comprobado. | Requeriría comparar el proceso actual con el proceso digital propuesto. |
| **Legal:** protección de datos y propiedad intelectual. | El sistema manejaría información académica confidencial. | **Aceptar** como factores legales obligatorios. | Exige analizar controles de acceso y permisos, pendiente de revisión normativa institucional. |

---

### Fase 3: Pain Points

| Propuesta IA | ¿Qué verificamos? | Decisión del equipo | Razón / Evidencia |
| :--- | :--- | :--- | :--- |
| **Dirección Académica:** falta de visibilidad sobre avance y retorno de inversión. | El enunciado plantea la necesidad de visibilidad, pero no menciona retorno de inversión. | **Modificar.** Conservar únicamente la necesidad de visibilidad sobre el avance. | El retorno de inversión no es una necesidad explícita del caso y podría no ser prioritario. |
| **Cuerpo Docente:** las herramientas actuales no reflejan entregables y métricas. | Necesitan conocer entregas y retrasos, pero no se demuestra que las herramientas actuales sean inherentemente deficientes. | **Modificar** a una hipótesis sobre la dificultad para consultar de forma centralizada. | Se elimina la afirmación no comprobada sobre fallas en las herramientas actuales. |
| **Personal de TI:** presión constante, incidentes manuales y falta de documentación. | TI tendría responsabilidades, pero no hay evidencia de incidentes o fallas de escalamiento. | **Modificar** como necesidad potencial de seguridad y documentación. | Afirmar problemas internos de TI sin evidencia convertiría un supuesto en un hecho falso. |
| **Líderes de Proyecto:** comunicación informal mediante llamadas y mensajes. | Los líderes comunican novedades, pero no se conoce el canal actual. | **Modificar.** Conservar la necesidad de registrar dificultades. | Se elimina la afirmación sobre llamadas informales por falta de evidencia. |
| **Estudiantes:** registrar avances se percibe como carga adicional. | Deben entregar avances, pero el enunciado no demuestra que el proceso genere rechazo hoy en día. | **Conservar** como hipótesis pendiente de validación. | Debe comprobarse mediante entrevistas o encuestas de usabilidad. |

---

### Fase 5: Lean Canvas

| Propuesta IA | ¿Qué verificamos? | Decisión del equipo | Razón / Evidencia |
| :--- | :--- | :--- | :--- |
| **Lean Canvas A:** Desarrollar un sistema 100% nuevo donde los estudiantes carguen evidencias. | Se contrastó con los pain points y el análisis PESTEL (Económico, Político y Tecnológico). | **RECHAZAR** la propuesta de sistema 100% nuevo. | Obligar a usar una plataforma nueva podría agravar la carga de registro de los estudiantes. Implicaría costos, infraestructura y presión sobre TI no validados ni viables frente a plataformas existentes. |
| **Lean Canvas B:** Integración de herramientas existentes (APIs, Dashboard). | Se analizó si la integración respondía al problema de dispersión sin obligar a los estudiantes a modificar sus flujos. | **ACEPTAR** como alternativa seleccionada por el equipo. | La integración responde mejor a la fragmentación descrita en el enunciado, conectando el ecosistema actual (Moodle, Drive, etc.) y solucionando el dolor docente sin generar fricción en el estudiante. |

---

### Conclusión de las Decisiones Humanas

El análisis realizado demuestra que la inteligencia artificial fue utilizada como una herramienta de apoyo para generar alternativas, detectar posibles omisiones y realizar críticas sobre las propuestas del equipo, pero **no como autoridad para establecer las decisiones finales.**

En todos los casos (Stakeholders, PESTEL, Pain Points y Canvas), la decisión final correspondió al equipo. Se contrastaron las propuestas con el alcance del caso, se diferenciaron los supuestos de los hechos respaldados por evidencia, y se tomó la decisión crítica de rechazar la construcción de un sistema nuevo en favor de la integración de herramientas existentes para garantizar la viabilidad del modelo de negocio en un entorno real.
