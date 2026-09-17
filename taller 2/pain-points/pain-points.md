# ANÁLISIS DE SISTEMAS · ACTIVIDAD IA RESISTENTE — NIVEL 3
## Fase 3: Pain Points

## 1. Recordatorio de stakeholders (Fase 1)

Los pain points de esta fase se construyen sobre los 6 stakeholders ya definidos por el equipo:

- **Dirección Académica** — patrocinador principal
- **Coordinación del Programa** — define flujos y reglas de negocio
- **Cuerpo Docente** — criterio pedagógico y validación de entregables
- **Personal de TI** — arquitectura, seguridad y soporte
- **Líderes de Proyecto** — enlace con el trabajo de campo
- **Estudiantes** — usuarios finales clave

## 2. Ficha de uso de IA

| Campo | Detalle |
|---|---|
| **Herramienta / modelo** | Claude (Anthropic) — asistente conversacional, uso en la fecha de elaboración de este documento. |
| **Propósito** | Ciclo 1 (Generar): proponer un pain point candidato por stakeholder a partir del contexto entregado. Ciclo 2 (Criticar): diferenciar síntoma vs. problema real en cada propuesta. |
| **Prompt principal utilizado** | "Estos son nuestros stakeholders [LISTA con roles]. Genera un pain point principal por stakeholder a partir de su rol y responsabilidad descrita. Para cada uno, diferencia qué parece síntoma y qué es el problema real, y qué evidencia se necesitaría para validarlo. No inventes datos del proyecto real." |
| **Salida relevante** | La IA propuso los 6 pain points candidatos de la tabla de la sección 3, cada uno con su distinción síntoma/problema e impacto estimado (ver tabla). |
| **Evaluación humana (Ciclo 3 — Decidir)** | *[ Completar: qué propuestas acepta el equipo tal cual, cuáles modifica y cuáles descarta, y por qué ]* |
| **Evidencia** | *[ Completar: entrevistas, observación directa, capturas del sistema, reportes u otro dato del proyecto real que confirme o refute cada pain point ]* |
| **Decisión final** | *[ Completar: pain point definitivo por stakeholder, redactado por el equipo ]* |
| **Reflexión** | *[ Completar: ¿en qué se equivocó o quedó corta la IA? ¿qué pudo decidir el equipo que la IA no podía saber sin el contexto real del proyecto? ]* |

## 3. Tabla de pain points (para pain-points.md)

Formato requerido por la guía: **Stakeholder → pain point → impacto → evidencia → decisión.**

| Stakeholder | Pain point (candidato IA) | Síntoma vs. problema | Impacto | Evidencia / Decisión del equipo |
|---|---|---|---|---|
| **Dirección Académica** | Falta de visibilidad en tiempo real sobre el avance y el retorno de inversión de los proyectos. | Síntoma: reportes que llegan tarde o incompletos. Problema real: no existe un mecanismo estructurado de reporte consolidado que alimente la toma de decisiones. | Decisiones de presupuesto y continuidad basadas en información desactualizada. | *[ Completar con evidencia real del proyecto y decisión: se acepta / se modifica / se descarta ]* |
| **Coordinación del Programa** | Dificultad para verificar si los flujos académicos y reglas de negocio definidos se cumplen realmente en la operación diaria. | Síntoma: quejas puntuales sobre inconsistencias de información. Problema real: falta de trazabilidad de datos entre lo definido y lo ejecutado en el sistema. | Reglas de negocio mal aplicadas e información inconsistente entre áreas. | *[ Completar con evidencia real del proyecto y decisión: se acepta / se modifica / se descarta ]* |
| **Cuerpo Docente** | Las herramientas de consulta no siempre reflejan los entregables y métricas de seguimiento definidos por los docentes. | Síntoma: los docentes revisan evidencias por fuera del sistema. Problema real: desalineación entre lo que el sistema registra y lo que el docente necesita validar. | Tiempo adicional invertido en verificación manual del progreso de los estudiantes. | *[ Completar con evidencia real del proyecto y decisión: se acepta / se modifica / se descarta ]* |
| **Personal de TI** | Presión constante por mantener disponibilidad y seguridad del sistema sin procesos claros de escalamiento ni documentación técnica centralizada. | Síntoma: incidentes resueltos "a mano" según quién esté disponible. Problema real: dependencia de conocimiento tácito, sin documentación ni protocolo formal. | Mayor tiempo de resolución de incidentes y riesgo de continuidad si rota el personal. | *[ Completar con evidencia real del proyecto y decisión: se acepta / se modifica / se descarta ]* |
| **Líderes de Proyecto** | El canal de retroalimentación entre los equipos de campo y el sistema es informal (llamadas, mensajes sueltos). | Síntoma: fallas que se comentan verbalmente y se olvidan. Problema real: no existe un registro formal que priorice cuellos de botella detectados en campo. | Problemas recurrentes que no se resuelven por falta de trazabilidad de los reportes. | *[ Completar con evidencia real del proyecto y decisión: se acepta / se modifica / se descarta ]* |
| **Estudiantes** | Registrar avances y adjuntar evidencias se percibe como una carga adicional cuando el proceso no es intuitivo. | Síntoma: quejas sobre "llenar formularios". Problema real: baja usabilidad reduce la adopción activa, de la cual depende el valor operativo del sistema. | Datos de seguimiento incompletos o de baja calidad, ya que el sistema depende del uso constante de los estudiantes. | *[ Completar con evidencia real del proyecto y decisión: se acepta / se modifica / se descarta ]* |

## 4. Checklist de esta fase

- [ ] Cada pain point queda asociado a un stakeholder de la Fase 1.
- [ ] Se distingue explícitamente síntoma vs. problema real.
- [ ] Se registra qué evidencia del proyecto valida (o descarta) cada pain point.
- [ ] Al menos una propuesta de la IA fue modificada o descartada, con justificación.
- [ ] El archivo `decisiones-humanas.md` incluye esta tabla completa con las columnas de evidencia y decisión llenas.
