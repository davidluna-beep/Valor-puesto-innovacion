# Anexos — Proyectos de Innovación operativa (Animum)

**Complemento de:** `valor-puesto-innovacion-ejecutivo.md`  
**Fuente de alcance:** fichas de proyectos Innovación 2026 + experiencia operativa del autor  
**Lenguaje:** negocio (sin detalle técnico de herramientas)

---

## Cómo leer estos anexos

Cada ficha resume: problema → solución → resultado para Animum → transferibilidad al grupo AD Education. Las fechas provienen del registro de actividades / fichas INN; donde el desarrollo es continuo se indica explícitamente.

---

## A1. HubSpot Workflow Auditor + Wiki-Hubspot

**Área:** Innovación y BI  
**Estado:** en funcionamiento (auditor desde ~abril 2026; wiki en uso operativo)

### Problema
La gestión comercial, admisiones, marketing y tutores vive en HubSpot con un ecosistema grande de automatizaciones. Cuando algo falla (una propiedad, un workflow), el aviso existía, pero **encontrar la causa** era manual, lento y dependiente de expertos.

### Qué hace
- **Auditor:** herramienta para investigar fallos: histórico de cambios, revisión de workflows y diagnóstico asistido que orienta el “por qué” del error; también consulta de impacto (“este workflow toca qué propiedades” y al revés). Guarda incidencias para aprender.
- **Wiki-Hubspot:** base de conocimiento de solo consulta sobre la configuración del CRM. Permite preguntar con evidencia dónde existe un valor o qué se rompería al cambiarlo. Ejemplo reciente: revisión masiva de teléfonos/WhatsApp (ver ejecutivo §4.2).

### Valor Animum
Menos tiempo perdido en “caza del fallo”, menos dependencia de pocas personas, y datos comerciales más fiables (segmentación de contactos contactables).

### Transferible al grupo
Playbook de **gobierno y calidad de CRM**: cómo auditar automatizaciones y cómo mantener un mapa vivo de configuración sin tocar el CRM a ciegas.

| Inicio | Fin desarrollo | Puesta en marcha |
|---|---|---|
| 06/04/2026 | 29/05/2026 (núcleo) | En uso desde ~28/04/2026 |

---

## A2. Lumen — control de negocio (SentinEX, comisiones, calendario lectivo)

**Área:** Innovación y BI  
**Estado:** en desarrollo / puesta en marcha escalonada (horizonte 2026–2027 según ficha)

### Problema
Control de negocio fragmentado: scripts, hojas, liquidaciones parciales, sin un único sitio con roles y trazabilidad.

### Qué hace (tres frentes)

**SentinEX (CX / retención)**  
Clasifica y prioriza tickets de HelpDesk con contexto 360º del alumno y valora **riesgo de abandono**. Puede ejecutarse a diario de forma automática sobre los tickets nuevos.  
→ Valor: protección de ingresos + menos triaje manual.

**Comisiones / regularizaciones**  
Ciclo completo en la plataforma de control de negocio: liquidación, evolución (bruto / regularizado / neto) y **cálculo automático de regularizaciones** por churn (ventana editable), sin doble penalización, con consulta en tiempo real para comerciales y managers.  
→ Valor: sustituye regularización manual y la opacidad de “no sé cuánto llevo”.

**Calendario lectivo**  
Sustituir mantenimiento manual fragmentado (hojas + ERP) por gestión visual y auditable (convocatorias, fechas, regeneración de lecciones respetando descansos).  
→ Valor: menos errores de calendario y menos dependencia de procesos opacos.

### Valor Animum (conjunto)
Lumen como **único lugar** de visualización y control, con permisos por rol.

### Transferible al grupo
Modelo de “torre de control” de negocio: retención, comisiones y calendario —independiente del software concreto, el patrón es replicable.

| Inicio | Fin previsto | Puesta en marcha estimada |
|---|---|---|
| 26/05/2026 | 30/12/2026 | ~07/01/2027 (según ficha; SentinEX/comisiones pueden ir por fases) |

---

## A3. Procesos CX — TW-Scheduler + Encuestas semanales

**Área:** Innovación y BI  
**Estado:** en funcionamiento (v2.0 julio 2026)

### Problema
- Envios semanales de Tips & Warnings a tutores de muchos bloques a la vez: mucha dedicación y riesgo de error.
- Encuestas de satisfacción / feedback ligadas al ritmo lectivo: configuración y seguimiento dispersos.

### Qué hace
- **TW-Scheduler:** define el calendario anual de envíos T&W (lecciones 1–10 + encuesta) por convocatoria; ajusta por festivos y por tipo de tutor (directo vs. corrección); el CRM ejecuta los envíos de forma automatizada. Preparación: **5–10 min una vez al año** (antes: 15 min–2 h cada 5–6 semanas).
- **Encuestas semanales:** configuración sencilla del formulario, historial, estadísticas y exportación.

### Valor Animum
Operativa académica predecible, menos carga recurrente, mejor medición del pulso alumno/tutor.

### Transferible al grupo
Patrón “calendario académico → comunicaciones automáticas → medición”, aplicable a cualquier escuela con bloques y docentes.

| Inicio | Fin | Puesta en marcha |
|---|---|---|
| 29/04/2026 | 15/07/2026 | En uso desde ~06/05/2026; v2.0 julio 2026 |

---

## A4. Procesos de venta — Lead, scoring y automatizaciones Marketing (incl. Syncform)

**Área:** Innovación y BI  
**Estado:** continuo (sin fecha de cierre; entrega por petición / prioridad)

### Problema
Captación y marketing con mucha operativa manual y fragmentada (Excel, flujos descentralizados). Un contacto podía mezclarse con múltiples intereses formativos sin trazabilidad clara.

### Qué hace
- **Objeto Lead:** separa “persona” (contacto) de “interés formativo” (lead), con ciclo de vida propio.
- **Cualificación y lead scoring:** puntuación automática para priorizar esfuerzo comercial y marketing.
- **Automatización Marketing:** entre otras, **Syncform HubSpot** — al crear/cambiar disciplina o programa, las tareas que llevaban ~**45 min** + checklist pasan a ~**5 min**, con log y posibilidad de deshacer.

### Valor Animum
Pipeline más limpio, menos trabajo repetitivo en Marketing, menos errores al lanzar oferta, más capacidad comercial sin más headcount proporcional.

### Transferible al grupo
Diseño de captación en CRM + automatización de cambios de catálogo formativo: muy útil en redes multi-escuela / multi-programa.

| Inicio | Fin | Puesta en marcha |
|---|---|---|
| 17/11/2025 | Continuo | Por proyecto / petición |

---

## A5. Procesos tutores — Negocio Tutor + objetivos de reclutamiento

**Área (ficha):** Customer Experience (con fuerte componente de sistematización CRM)  
**Estado:** en funcionamiento (inicio previo al registro formal de actividades)

### Problema
Ciclo de vida del docente (captación, propuesta, formalización, baja) y previsión de necesidad de tutores gestionados de forma manual o poco conectada al ritmo de matrícula.

### Qué hace
- **Pipeline Negocio Tutor en HubSpot:** recruiting → colaboración → baja, con estados, formularios y automatizaciones de comunicación.
- **Objetivos de reclutamiento:** cuadro de mando (Sheets + conexión al CRM) que cruza matrícula con necesidad docente por bloque; se plantea migrar a Lumen.

### Valor Animum
Más capacidad de tutores con menos operativa; anticipación de carencias frente a picos de venta.

### Transferible al grupo
Gobierno del claustro / docentes asociados y planificación de capacidad ante ventas —común en escuelas con freelance o colaboradores externos.

| Inicio | Fin ficha | Puesta en marcha |
|---|---|---|
| Previo al registro | 06/02/2026 | En uso desde antes del registro |

---

## A6. Tabla resumen de impacto (orden crisis comercial / captación)

| # | Iniciativa | Tipo de valor | Indicador / nota |
|---|---|---|---|
| 1 | SentinEX | Protección de ingresos | Riesgo de baja; ejecución diaria |
| 2 | Teléfonos / WhatsApp | Capacidad comercial | 140k+ contactos, 5 días; >95 % fiabilidad; +20 % contacto útil est. |
| 3 | Lead Scoring | Priorización Ventas | En desarrollo; foco en leads de mayor valor |
| 4 | Signal Prospector | Capacidad captación | Conectado HubSpot; pruebas OK; **pendiente calibrar criterios** de valoración/puntuación; sin envío sin OK |
| 5 | Objeto Lead | Precisión del funnel | Desarrollado; pendiente go-live Marketing |
| 6 | CDM-Manager | Capacidad + coste SaaS | **En uso** (finalizado); cupo ~20k / techo ~21k; salvoconductos + score; propose→dry-run→confirm |
| 7 | Deal Loss Agent | Insight pérdidas | **Activado** en HubSpot; prueba OK; **pendiente entrenar** con operativa/productos/pipeline Animum |
| 8 | wiki-Hubspot + Auditor | Seguro CRM captación | En uso; impacto días→minutos |
| 9 | Oráculo | Multiplicador DWH/Lumen | En uso |
| 10 | Koalify | Higiene embudo captación | Probado en **sandbox**; prod = licencia (~75 €/mes 150k · ~100 €/mes 200k anual) + reglas de merge |
| 11 | Negocio Tutor / objetivos | Escala entrega docente | En uso; ~4,6k negocios tutor |
| 12 | Comisiones Lumen | Motivación + control | En proceso; bruto/regularizado/neto |
| 13 | Syncform | Velocidad oferta Mk | En uso; ~45 min → ~5 min |
| 14 | TW-Scheduler | Ahorro operativo CX | En uso; 15 min–2 h / ciclo → 5–10 min / año |
| 15 | Encuestas semanales | Medición pulso | En uso |
| 16 | Calendario lectivo Lumen | Operativa académica | En proceso |

---

## A9. CDM-Manager (cupo Contactos de Marketing)

**Área:** Innovación y BI · HubSpot / Marketing  
**Estado:** **finalizado y en uso**  

### Problema
El cupo de Contactos de Marketing es a la vez **coste SaaS** y **capacidad de nurturing/captación**. Superar el techo (~21.000) encarece; rotar mal pierde cobertura sobre contactos de valor.

### Qué hace
App propia (FastAPI + React), ciclo mensual **propose → dry-run → confirm** (objetivo ~20.000 / techo duro ~21.000):

- **Salvoconductos** (prioridad): secuencia de venta; nurturing/fidelización e inbound; tutores con participación activa; alumnos con matrícula activa; primeros 31 días; exclusiones manuales. Excluye sin-negocio / baja de suscripciones / tutores no activos.
- **Relleno** del cupo con candidatos por puntuación CDM.
- **Apply seguro:** solo listas `CDM_OPS_*` / `CDM_HIST_*` + workflows ALTA/BAJA; **sin mutar propiedades** de contacto; hard stop si bloqueo o > techo.

### Valor en crisis
Cada asiento del embudo activo cuenta: más alcance de Marketing/Ventas dentro del cupo contratado, con control de coste.

---

## A10. Signal Prospector (calibración)

**Estado:** conectado a HubSpot · pruebas OK · **pendiente calibración**  

Rankea señales de intención y prepara borradores de primer contacto. **Nunca envía sin OK humano.** Siguiente paso: definir/entrenar los criterios de valoración y puntuación de cada contacto. Relacionado con Lead Scoring.

---

## A11. Deal Loss Agent (entrenamiento)

**Estado:** activado y disponible en HubSpot · prueba OK · **pendiente entrenamiento**  

Patrones de deals closed-lost → insight para mejorar captación/cierre (no ejecución automática). Siguiente paso: aportarle operativa interna, productos, metodología y pipeline de trabajo con interesados, para informes más precisos. En el relato directivo va **después de CDM**.

---

## A12. Koalify (sandbox → producción)

**Estado:** conectado y probado en **sandbox** · **pendiente licencia + configuración en producción**  

**Higiene del embudo de captación** (menos duplicados / leads fantasma). Para prod: licencia ~**75 €/mes** (hasta 150k contactos) o ~**100 €/mes** (hasta 200k) con contratación anual; luego configurar criterios de detección y fusión. Complementa wiki-Auditor y la limpieza de teléfonos.

---

## A7. Nota sobre coste de herramienta (Cursor)

Licencia actual aproximada: **20 €/mes**.  
En la lógica de este documento, ese coste es un **insumo de productividad** del puesto (permite entregar apps y automatizaciones en plazos cortos). La decisión de inversión relevante es sobre el **puesto y la labor**, no sobre la herramienta aislada.

---

## A8. Mensaje para Notebook LM / presentación

Slides sugeridas (máx. 8–10):

1. Título: Valor del puesto en crisis comercial (inversión, no gasto)  
2. El problema: captar y retener sin crecer en plantilla al mismo ritmo  
3. Mi rol (1 frase) + equipo de 3  
4. Bloque comercial: SentinEX → teléfonos → scoring → Lead → CDM  
5. Signal / Deal Loss (calibración) + Koalify (sandbox → licencia)  
6. Seguro CRM (wiki + Auditor) + Oráculo  
7. Por qué no es prescindible (efecto palanca Ventas/Marketing)  
8. Transferible a AD Education  
9. Cierre: mantener e invertir en la función  

---

*Fin de anexos.*
