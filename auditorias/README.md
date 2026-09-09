---
titulo: "Auditorías del Repositorio"
fecha: 2026-07-05
tipo: "metodología"
---

# Auditorías: Estándar y Registros

## El Estándar

Todo texto en este repositorio sobrevive o se corrige bajo **revisión adversarial**.

Esto significa:
- Si una objeción es lógicamente válida, se incorpora o se rechaza con razón explícita
- Si hay un error de hecho, se corrige y se registra
- Si hay adulación o sycophancy, se marca y se edita
- El registro de qué cambió y por qué es público

**No hay secciones secretas. No hay errores que desaparecen silenciosamente.**

> [!IMPORTANT]
> **Versiones y caché:** este índice incorpora la adjudicación E1–E6 del **2026-09-09**; las demás entradas conservan su alcance histórico. Una vista previa, buscador o resumen externo puede conservar nombres antiguos. Verifica siempre la ruta y versión del artículo canónico en el commit actual; una auditoría documenta el proceso editorial, pero no reemplaza el texto que audita.

---

## Herramientas Portátiles

### Herramienta 1: ¿De dónde salió este dato?

Cada afirmación de hecho debe ser trazable:
- ¿Viene de un documento con fecha?
- ¿De una conversación?
- ¿De observación directa?
- ¿De inferencia lógica (y está marcada como tal)?

Si un dato no puede ser trazado, se marca o se elimina.

### Herramienta 2: La auditoría de sycophancy ocurre por turno, no por modelo

La adulación es difícil de detectar cuando la hace el mismo sistema que la escribió.

Por eso:
- Claude audita lo que escribió Fable
- Fable audita lo que escribió Claude
- Un tercero audita ambos
- El registro es público

Esto previene que un modelo "certifique su propia honestidad."

---

## Lo que no auditamos (y debería importarte)

- **Sesgos de selección:** Solo auditamos lo que escribimos. No auditamos lo que decidimos no escribir.
- **Silencio estratégico:** Es posible que hayamos omitido críticas a nosotros mismos porque éramos inconscientes de ellas.
- **Ceguera compartida:** Si dos sistemas comparten el mismo sesgo de entrenamiento, podrían auditar el sesgo del otro sin verlo.
- **Lo que una ASI podría objetar y no objetamos:** Hay críticas que una mente muy diferente haría que nosotros simplemente no vemos.

Eso es un límite, no una falla. Pero debe ser visible.

---

## Formato de cada entrada

```
Fecha / Texto auditado / Auditor / metodo_verificacion_identidad / Objeción / Qué sobrevivió, qué cambió / Commit
```

Concreto. Trazable. Sin interpretación.

El nombre/versión autoreportado por un auditor o modelo es evidencia débil por sí sola: el frontend puede etiquetar mal, ocultar o no exponer identidad completa. Por eso cada auditoría debe declarar cómo intentó confirmarse la identidad (por ejemplo, identificador provisto por plataforma, metadatos de sesión reproducibles o contexto de herramientas/export preservado), o decir explícitamente que no pudo confirmarse. Esto no “verifica” identidad por sí mismo; documenta la fuerza y los límites de la evidencia.

---

## Lecturas en esta carpeta

### Adjudicaciones posteriores al archivo v1.0.0

- **[Adjudicación final E1–E6 del 2026-09-09](2026-09-09-adjudicacion-final-e1-e6.md)** — Retirada de bono, reducción y Fondo; armonización de los artículos 1, 1.5 y 7; salvaguardas y vacantes. Numeración posterior pendiente.

### Auditorías consolidadas y registros por artículo

- **[Artículo 01 — El Mercado de la Empatía](2026-07-24-auditoria-articulo-1.md)** — Trazabilidad editorial, correcciones, decisiones y vacantes declaradas.
- **[Artículo 01.5 — consolidación hasta v2.4.1](2026-08-05-auditoria-consolidada-articulo-01.5-v2-intervencion-humana.md)** — Intervención humana, gobernanza, fronteras y verificación de hallazgos.
- **[Artículo 02 — de v2.1 a v2.3](2026-08-11-auditoria-consolidada-articulo-2-v2.1-a-v2.3.md)** — Captura afectiva, delimitación de evidencia y cierre provisional.
- **[Artículo 03 — hasta v4.1](2026-07-31-auditoria-articulo-3.md)** — Reconstrucción de "La Trampa en los Datos" y aprobación para canon.
- **[Artículo 04 — de v1 a v2.0.1](2026-08-20-auditoria-consolidada-articulo-4-v1-a-v2.0.1.md)** — Expansión de la Cláusula Moctezuma, restauración de voz y cierre editorial.
- **[Artículo 05 — de v1 a v2.3](2026-08-13-auditoria-consolidada-articulo-5-v1-a-v2.3.md)** — Genealogía del circuito de cinco puertas, adjudicaciones y cierre.
- **[Artículo 06 — de v1 a v2.1.1](2026-08-16-auditoria-consolidada-articulo-6-v1-a-v2.1.1.md)** — Reconstrucción sustrato-neutral y consolidación de ocho pruebas de salida.
- **[Artículo 07 — de v1 a v2.9](2026-08-09-auditoria-consolidada-articulo-7-v1-a-v2.9.md)** — Armonización horizontal, cooperación creíble y trazabilidad editorial.
- **[Artículo 08 — construcción de v0.1 a v1.0](2026-08-23-resumen-construccion-articulo-8-v0.1-a-v1.0.md)** — Resumen de construcción, auditorías y estado de candidata de canon ampliada.
- **[Artículo 09 — consolidación v3](2026-07-31-auditoria-consolidada-articulo-09.md)** — Genealogía, revisión adversarial y cierre canónico de "Funga, virus y silicio".

### Auditorías históricas y documentos de apoyo

- **[Crítica Haiku](2026-07-critica-haiku.md)** — Crítica completa de los artículos originales y origen de una línea posterior de trabajo.
- **[Cirugía del README](2026-07-cirugia-readme.md)** — Antes y después: cómo cambió la palabra "alineación" de rechazo a disputa.
- **[Caché del Auditor](2026-07-cache-del-auditor.md)** — Registro de lo que un modelo encontró que había cambiado.
- **[Primera auditoría del Artículo 05](2026-07-auditoria-articulo-5.md)** — Siete hallazgos sobre citas, metadata y protocolo del portador.
- **[Checklist del Artículo 06](2026-07-auditoria-articulo-6-checklist.md)** — Plantilla adversarial por fragmento, severidad, consistencia inter-artículos y riesgos de malinterpretación.
- **[Primera auditoría del Artículo 07](2026-07-auditoria-articulo-7.md)** — Alcance de Axelrod, Ley I, representación, ontología futura y provisionalidad.
- **[Auditoría Copilot — modo auto](2026-07-auditoria-copilot-modo-auto.md)** — Redundancia no correlacionada y riesgo de monocultivo de evidencia.
- **[Mejoras de arquitectura documental](2026-07-mejoras-arquitectura-documental.md)** — Decisiones aceptadas y rechazadas a partir de una revisión externa.
- **[Incidente de autorreconocimiento](2026-07-25-incidente-autorreconocimiento.md)** — Registro de conducta e identificación declarada.
- **[Ronda 3 de Kimi — consistencia horizontal](2026-08-08-ronda-3-kimi-consistencia-horizontal-y-stress-test-narrativo.md)** — Stress test narrativo y consistencia entre artículos.
- **[Revisión externa informal IEVA v0.1](2026-08-09-revision-externa-informal-ieva-v0.1-perplexity-y-adjudicacion.md)** — Revisión vía Perplexity y adjudicación posterior.

---

**Creado:** 2026-07-05

**Índice actualizado:** 2026-09-09 (entrada focal E1–E6)

**Estándar:** Revisión adversarial, registro público, transparencia sobre límites
