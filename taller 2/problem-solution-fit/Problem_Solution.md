# Problem / Solution Fit
## Sistema de Seguimiento de Proyectos Académicos

---

> **El prompt usado para el punto de problem solution es:**
>
> Actúa como analista de sistemas y ayúdame a desarrollar el punto Problem/Solution Fit para el caso  (Nuestra Squad). A partir del enunciado, identifica el problema real diferenciando síntomas, causas y consecuencias, plantea 3 formulaciones alternativas del problema con sus stakeholders y pain points 

[Contexto del documento proporcionado]
Problem/Solution Fit
Sistema de Seguimiento de Proyectos Académicos
1. Problema identificado
Un programa académico tiene numerosos proyectos desarrollados por estudiantes. Cada grupo debe entregar avances, documentos, resultados y evidencias durante el semestre, pero esta información se encuentra distribuida entre diferentes plataformas, correos y archivos. Como consecuencia, los docentes no pueden conocer rápidamente qué grupos han entregado, cuáles tienen retrasos y cuáles presentan dificultades, y la dirección académica evalúa implementar un sistema de seguimiento para resolver esta falta de visibilidad.
Formulación: el programa académico presenta dificultades para dar seguimiento a los proyectos de los grupos de estudiantes debido a la dispersión de la información entre plataformas, correos y archivos, lo que impide a docentes y dirección académica conocer de forma oportuna el estado, los retrasos y las dificultades de cada grupo.
2. Alternativas de formulación consideradas
Antes de seleccionar el enfoque final, se evaluaron tres formulaciones posibles (IA Resistente Nivel 3):
Alternativa | Enfoque | Principal limitación
A | Proceso y trazabilidad: falta de un mecanismo unificado para reportar y consolidar avances de los grupos. | No resuelve por sí sola la dispersión de la información entre plataformas distintas.
B | Multiplataforma: la información de cada grupo vive repartida entre correos, archivos y plataformas. | Centralizar las entradas no garantiza que docentes y estudiantes las usen de forma consistente.
C | Roles y visibilidad: falta de diferenciación entre quién debe supervisar el avance y quién debe reportarlo. | No resuelve directamente la dispersión de las fuentes de información.
Se seleccionó la Alternativa A como base, complementada con los elementos de multiplataforma (B) y de roles (C), por ser la que cubre más pain points del caso con mayor relación directa con el sistema propuesto.
3. Stakeholders afectados
Stakeholder | Necesidad principal
Estudiantes | Contar con un canal simple para registrar avances, documentos y evidencias sin que se sienta como una carga adicional.
Docentes | Conocer rápidamente qué grupos han entregado, cuáles tienen retrasos y cuáles presentan dificultades.
Dirección Académica | Tener visibilidad consolidada del estado general de los proyectos para sustentar sus decisiones.
Coordinación del Programa | Verificar que los flujos y reglas de entrega definidos se cumplan en la operación diaria.
Personal de TI | Contar con procesos claros de soporte y documentación técnica del sistema.
Líderes de Proyecto | Disponer de un canal formal para reportar avances y cuellos de botella detectados en campo.
Coordinación del Programa, Personal de TI y Líderes de Proyecto no se mencionan de forma literal en el enunciado; se incluyen como roles definidos por el equipo en la Fase 1 y deben sustentarse con evidencia del proyecto real.
4. Propuesta de valor
Ofrecer una plataforma centralizada de seguimiento de proyectos académicos que permita a los grupos registrar avances, documentos y evidencias en un solo lugar, y que brinde a docentes, coordinación y dirección académica visibilidad inmediata sobre el estado, los retrasos y las dificultades de cada grupo.
5. Pain points y su relación con la solución
Pain point | Problema asociado | Implicación para la solución
Docentes no conocen a tiempo qué grupos entregaron, tienen retraso o dificultades | Información dispersa entre plataformas, correos y archivos | Vista consolidada del estado de cada grupo (entregado / retrasado / con dificultades)
Dirección Académica sin visibilidad en tiempo real del avance general | Falta de un mecanismo consolidado de reporte | Panel de seguimiento consolidado por proyecto y por corte del semestre
Dificultad de Coordinación para verificar si se cumplen los flujos definidos | Falta de trazabilidad entre lo definido y lo ejecutado | Registro de cumplimiento de hitos por grupo
Estudiantes perciben el registro de avances como una carga adicional | Baja usabilidad reduce la adopción del sistema | Interfaz simple de carga de evidencias con confirmación automática
Retroalimentación informal entre Líderes de Proyecto y el sistema | Falta de registro formal de cuellos de botella | Módulo de reporte formal de incidencias detectadas en campo
Personal de TI sin procesos claros de escalamiento | Dependencia de conocimiento tácito sin documentación | Protocolo y documentación técnica centralizada de soporte
6. Supuestos que deben validarse
Porcentaje real de grupos con retrasos o dificultades en el semestre actual.
Criterios exactos para clasificar un grupo como "con dificultades".
Aceptación de los estudiantes y docentes de migrar a una única plataforma.
Si Coordinación del Programa, Personal de TI y Líderes de Proyecto son roles existentes en la operación real o deben ajustarse.
Viabilidad técnica de integrar las plataformas, correos y archivos actualmente en uso.
7. Uso de IA — Nivel 3
La IA se usó para generar y comparar alternativas de formulación del problema, y para proponer la estructura de trazabilidad entre pain points, problema y solución. El equipo verificó que cada pain point estuviera respaldado por el enunciado del caso, distinguiendo los stakeholders mencionados de forma literal (estudiantes, docentes, dirección académica) de los añadidos por el equipo en la Fase 1 (coordinación, TI, líderes de proyecto), que quedan como supuestos por validar con evidencia real del proyecto. La decisión final sobre el problema, el alcance y los stakeholders corresponde al equipo, no a la IA.
> ```

---

### 1. Problema identificado
Un programa académico tiene numerosos proyectos desarrollados por estudiantes. Cada grupo debe entregar avances, documentos, resultados y evidencias durante el semestre, pero esta información se encuentra distribuida entre diferentes plataformas, correos y archivos. Como consecuencia, los docentes no pueden conocer rápidamente qué grupos han entregado, cuáles tienen retrasos y cuáles presentan dificultades, y la dirección académica evalúa implementar un sistema de seguimiento para resolver esta falta de visibilidad.

**Formulación:** El programa académico presenta dificultades para dar seguimiento a los proyectos de los grupos de estudiantes debido a la dispersión de la información entre plataformas, correos y archivos, lo que impide a docentes y dirección académica conocer de forma oportuna el estado, los retrasos y las dificultades de cada grupo.

---

### 2. Alternativas de formulación consideradas
Antes de seleccionar el enfoque final, se evaluaron tres formulaciones posibles (IA Resistente Nivel 3):

| Alternativa | Enfoque | Principal limitación |
| :--- | :--- | :--- |
| **A** | **Proceso y trazabilidad:** falta de un mecanismo unificado para reportar y consolidar avances de los grupos. | No resuelve por sí sola la dispersión de la información entre plataformas distintas. |
| **B** | **Multiplataforma:** la información de cada grupo vive repartida entre correos, archivos y plataformas. | Centralizar las entradas no garantiza que docentes y estudiantes las usen de forma consistente. |
| **C** | **Roles y visibilidad:** falta de diferenciación entre quién debe supervisar el avance y quién debe reportarlo. | No resuelve directamente la dispersión de las fuentes de información. |

> **Selección:** Se seleccionó la **Alternativa A** como base, complementada con los elementos de multiplataforma (B) y de roles (C), por ser la que cubre más *pain points* del caso con mayor relación directa con el sistema propuesto.

---

### 3. Stakeholders afectados

| Stakeholder | Necesidad principal |
| :--- | :--- |
| **Estudiantes** | Contar con un canal simple para registrar avances, documentos y evidencias sin que se sienta como una carga adicional. |
| **Docentes** | Conocer rápidamente qué grupos han entregado, cuáles tienen retrasos y cuáles presentan dificultades. |
| **Dirección Académica** | Tener visibilidad consolidada del estado general de los proyectos para sustentar sus decisiones. |
| **Coordinación del Programa** | Verificar que los flujos y reglas de entrega definidos se cumplan en la operación diaria. |
| **Personal de TI** | Contar con procesos claros de soporte y documentación técnica del sistema. |
| **Líderes de Proyecto** | Disponer de un canal formal para reportar avances y cuellos de botella detectados en campo. |

> *Nota:* Coordinación del Programa, Personal de TI y Líderes de Proyecto no se mencionan de forma literal en el enunciado; se incluyen como roles definidos por el equipo en la Fase 1 y deben sustentarse con evidencia del proyecto real.

---

### 4. Propuesta de valor
Ofrecer una plataforma centralizada de seguimiento de proyectos académicos que permita a los grupos registrar avances, documentos y evidencias en un solo lugar, y que brinde a docentes, coordinación y dirección académica visibilidad inmediata sobre el estado, los retrasos y las dificultades de cada grupo.

---

### 5. Pain points y su relación con la solución

| Pain point | Problema asociado | Implicación para la solución |
| :--- | :--- | :--- |
| **Docentes no conocen a tiempo qué grupos entregaron, tienen retraso o dificultades** | Información dispersa entre plataformas, correos y archivos | Vista consolidada del estado de cada grupo (entregado / retrasado / con dificultades) |
| **Dirección Académica sin visibilidad en tiempo real del avance general** | Falta de un mecanismo consolidado de reporte | Panel de seguimiento consolidado por proyecto y por corte del semestre |
| **Dificultad de Coordinación para verificar si se cumplen los flujos definidos** | Falta de trazabilidad entre lo definido y lo ejecutado | Registro de cumplimiento de hitos por grupo |
| **Estudiantes perciben el registro de avances como una carga adicional** | Baja usabilidad reduce la adopción del sistema | Interfaz simple de carga de evidencias con confirmación automática |
| **Retroalimentación informal entre Líderes de Proyecto y el sistema** | Falta de registro formal de cuellos de botella | Módulo de reporte formal de incidencias detectadas en campo |
| **Personal de TI sin procesos claros de escalamiento** | Dependencia de conocimiento tácito sin documentación | Protocolo y documentación técnica centralizada de soporte |

---

### 6. Supuestos que deben validarse
- Porcentaje real de grupos con retrasos o dificultades en el semestre actual.
- Criterios exactos para clasificar un grupo como "con dificultades".
- Aceptación de los estudiantes y docentes de migrar a una única plataforma.
- Si Coordinación del Programa, Personal de TI y Líderes de Proyecto son roles existentes en la operación real o deben ajustarse.
- Viabilidad técnica de integrar las plataformas, correos y archivos actualmente en uso.

---

