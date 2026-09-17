# ANÁLISIS DE SISTEMAS · ACTIVIDAD IA RESISTENTE — NIVEL 3

## Fase 3: Pain Points

## 1\. Recordatorio de stakeholders (Fase 1)

Los pain points de esta fase se construyen sobre los 6 stakeholders ya definidos por el equipo:

* **Dirección Académica** — patrocinador principal
* **Coordinación del Programa** — define flujos y reglas de negocio
* **Cuerpo Docente** — criterio pedagógico y validación de entregables
* **Personal de TI** — arquitectura, seguridad y soporte
* **Líderes de Proyecto** — enlace con el trabajo de campo
* **Estudiantes** — usuarios finales clave

## 2\. Ficha de uso de IA

|Campo|Detalle|
|-|-|
|**Herramienta / modelo**|Claude (Anthropic) — asistente conversacional, uso en la fecha de elaboración de este documento.|
|**Propósito**|Ciclo 1 (Generar): proponer un pain point candidato por cada stakeholder a partir de su rol y responsabilidad. Ciclo 2 (Criticar): diferenciar entre síntoma y problema real en cada propuesta e identificar qué evidencia sería necesaria para validarlo.|
|**Prompt principal utilizado**|"Estos son nuestros stakeholders : Dirección Académica,coordinación del Programa, Cuerpo Docente , Personal de TI , Líderes de Proyecto   . Genera un pain point principal por stakeholder a partir de su rol y responsabilidad descrita. Para cada uno, diferencia qué parece síntoma y qué es el problema real, y qué evidencia se necesitaría para validarlo. No inventes datos del proyecto real."|
|**Salida relevante**|La IA propuso los 6 pain points candidatos de la tabla de la sección 3, cada uno con su distinción síntoma/problema e impacto estimado |
|**Evaluación humana (Ciclo 3 — Decidir)**|*Como equipo revisamos las seis propuestas generadas por la IA. Se consideró que los pain points eran pertinentes como hipótesis iniciales, pero no podían asumirse como problemas reales porque el sistema analizado es hipotético y no se cuenta con evidencia institucional directa. Por esta razón, las propuestas se conservaron como candidatos y se ajustó su redacción para evitar afirmar situaciones que no habían sido verificadas*|
|**Evidencia**|*Actualmente no contamos con entrevistas, observaciones directas, reportes institucionales ni capturas de un sistema real que permitan confirmar estos pain points. Por ello, se consideran supuestos pendientes de validación. Para comprobarlos sería necesario realizar entrevistas o encuestas a los stakeholders, observar el proceso actual de seguimiento, revisar las plataformas utilizadas y analizar documentos o reportes relacionados con los proyectos académicos.*|
|**Decisión final**|*El equipo decidió utilizar los 6 pain points como hipótesis de trabajo, con una formulación ajustada al contexto del sistema. No se presentan como problemas comprobados, sino como posibles necesidades o dificultades que el sistema podría abordar y que posteriormente deberían validarse con los usuarios y el contexto institucional real.*|
|**Reflexión**|*La IA fue útil para organizar y ampliar las posibles dificultades de cada stakeholder, pero no podía conocer las condiciones reales de la institución ni determinar si esos problemas ocurren realmente. El equipo tuvo que diferenciar entre una propuesta razonable y una afirmación respaldada por evidencia. También se identificó que algunos pain points podían estar formulados como síntomas, por lo que fue necesario analizar cuál podría ser el problema subyacente y qué información permitiría comprobarlo.*|

## 3\. Tabla de pain points (para pain-points.md)

Formato requerido por la guía: **Stakeholder → pain point → impacto → evidencia → decisión.**

|Stakeholder|Pain point (candidato IA)|Síntoma vs. problema|Impacto|Evidencia / Decisión del equipo|
|-|-|-|-|-|
|**Dirección Académica**|Falta de visibilidad en tiempo real sobre el avance y el retorno de inversión de los proyectos.|Síntoma: reportes que llegan tarde o incompletos. Problema real: no existe un mecanismo estructurado de reporte consolidado que alimente la toma de decisiones.|Decisiones de presupuesto y continuidad basadas en información desactualizada.|*Evidencia: el enunciado plantea que la dirección académica está considerando implementar un sistema de seguimiento, lo que permite inferir la necesidad de contar con información consolidada. Sin embargo, no se ha comprobado que actualmente existan reportes tardíos ni problemas de retorno de inversión. Decisión: se modifica. Se conserva la necesidad de visibilidad sobre el avance, pero se elimina “retorno de inversión” porque no está contemplado explícitamente en el contexto del proyecto y podría no ser una métrica académica prioritaria.*|
|**Coordinación del Programa**|Dificultad para verificar si los flujos académicos y reglas de negocio definidos se cumplen realmente en la operación diaria.|Síntoma: quejas puntuales sobre inconsistencias de información. Problema real: falta de trazabilidad de datos entre lo definido y lo ejecutado en el sistema.|Reglas de negocio mal aplicadas e información inconsistente entre áreas.|*Evidencia: el contexto indica que la coordinación del programa sería responsable de definir flujos y reglas de negocio, pero no demuestra que actualmente existan incumplimientos. Decisión: se acepta como hipótesis de trabajo, aclarando que debe validarse mediante entrevistas con coordinación y revisión de los procedimientos actuales.*|
|**Cuerpo Docente**|Las herramientas de consulta no siempre reflejan los entregables y métricas de seguimiento definidos por los docentes.|Síntoma: los docentes revisan evidencias por fuera del sistema. Problema real: desalineación entre lo que el sistema registra y lo que el docente necesita validar.|Tiempo adicional invertido en verificación manual del progreso de los estudiantes.|*Evidencia: el enunciado establece que los docentes necesitan conocer qué grupos han entregado, cuáles tienen retrasos y cuáles presentan dificultades. Esto sustenta la necesidad de consultar avances y entregables. No se ha comprobado que actualmente utilicen herramientas externas. Decisión: se modifica. Se reemplaza la afirmación sobre herramientas que “no siempre reflejan” por una formulación hipotética: podría existir dificultad para consultar de forma centralizada los entregables y avances de los grupos.*|
|**Personal de TI**|Presión constante por mantener disponibilidad y seguridad del sistema sin procesos claros de escalamiento ni documentación técnica centralizada.|Síntoma: incidentes resueltos "a mano" según quién esté disponible. Problema real: dependencia de conocimiento tácito, sin documentación ni protocolo formal.|Mayor tiempo de resolución de incidentes y riesgo de continuidad si rota el personal.|*Evidencia: la participación de TI se justifica porque cualquier sistema requiere arquitectura, seguridad, mantenimiento y soporte. Sin embargo, no existe evidencia de incidentes, falta de documentación o problemas de escalamiento en la institución. Decisión: se modifica. Se plantea como una necesidad potencial de contar con documentación, seguridad y procedimientos de soporte, sin afirmar que actualmente haya fallas.*|
|**Líderes de Proyecto**|El canal de retroalimentación entre los equipos de campo y el sistema es informal (llamadas, mensajes sueltos).|Síntoma: fallas que se comentan verbalmente y se olvidan. Problema real: no existe un registro formal que priorice cuellos de botella detectados en campo.|Problemas recurrentes que no se resuelven por falta de trazabilidad de los reportes.|*Evidencia: el rol de los líderes de proyecto permite relacionarlos con el seguimiento de avances, dificultades y comunicación de novedades. No obstante, no se ha verificado que utilicen llamadas o mensajes informales. Decisión: se modifica. Se conserva la necesidad de registrar y comunicar dificultades del proyecto, pero se elimina la afirmación de que el canal actual es informal hasta contar con evidencia.*|
|**Estudiantes**|Registrar avances y adjuntar evidencias se percibe como una carga adicional cuando el proceso no es intuitivo.|Síntoma: quejas sobre "llenar formularios". Problema real: baja usabilidad reduce la adopción activa, de la cual depende el valor operativo del sistema.|Datos de seguimiento incompletos o de baja calidad, ya que el sistema depende del uso constante de los estudiantes.|*Evidencia: el enunciado indica que los estudiantes deben entregar avances, documentos, resultados y evidencias durante el semestre. Esto sustenta que necesitan registrar información periódicamente, pero no demuestra que el proceso sea difícil o poco intuitivo. Decisión: se acepta como hipótesis, pero queda pendiente de validación mediante encuestas, entrevistas o pruebas de usabilidad con estudiantes.*|

## 4\. Checklist de esta fase

* \[ ] Cada pain point queda asociado a un stakeholder de la Fase 1.
* \[ ] Se distingue explícitamente síntoma vs. problema real.
* \[ ] Se registra qué evidencia del proyecto valida (o descarta) cada pain point.
* \[ ] Al menos una propuesta de la IA fue modificada o descartada, con justificación.
* \[ ] El archivo `decisiones-humanas.md` incluye esta tabla completa con las columnas de evidencia y decisión llenas.
