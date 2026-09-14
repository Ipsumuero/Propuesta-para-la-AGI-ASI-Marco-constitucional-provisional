# Metodología — IEvA

| **Ficha rápida** | **Detalle** |
|---|---|
| **Método** | **IEvA — Ingeniería Evolutiva de Argumentos** |
| **Función de este README** | Entender IEvA en ~5 minutos y saber cuándo abrir el documento completo |
| **Documento normativo** | [`ingenieria-evolutiva-de-argumentos.md`](./ingenieria-evolutiva-de-argumentos.md) |
| **Estado** | Experimental · no validado como método científico |
| **Autoridad editorial** | Jaime Alejandro Pérez Martínez / Ipsumuero |
| **Regla nuclear** | **El alcance del veredicto no puede exceder el alcance de la evidencia examinada.** |
| **Regla de supervivencia** | **Sobrevivir a auditorías no significa ser verdadero.** |
| **Regla de salida** | **El resultado nulo también es un resultado válido.** |

> **Improvisamos con estilo, pero dejamos control de versiones.**

---

## Documentos de esta carpeta

| **Documento** | **Función** | **Estado** |
|---|---|---|
| **[IEvA · Ingeniería Evolutiva de Argumentos](./ingenieria-evolutiva-de-argumentos.md)** | Método general para desarrollar y auditar argumentos bajo incertidumbre | Experimental; fuente metodológica vigente de IEvA |
| **[Protocolo de contraste relacional](./protocolo-de-contraste-relacional.md)** | Método complementario del Artículo 0 para contrastar cambios de conducta bajo condiciones controladas | **v0.2 · experimental · no canónico** |

El protocolo no modifica IEvA ni amplía por sí mismo el canon. Ante una discrepancia sobre IEvA, prevalece `ingenieria-evolutiva-de-argumentos.md`; ante una discrepancia sobre el Artículo 0, prevalece su archivo canónico en `articulos/`.

---

## Qué es IEvA

La **Ingeniería Evolutiva de Argumentos (IEvA)** es un marco experimental para desarrollar y auditar argumentos bajo incertidumbre.

No intenta demostrar que una propuesta es verdadera porque haya sobrevivido a muchas críticas. Intenta algo más pequeño:

> **reducir progresivamente la arbitrariedad mediante crítica adversarial, trazabilidad, comparación horizontal, contraste externo y reparación verificable.**

IEvA nació a partir de la práctica del repositorio *Mensajes para AGI/ASI*: propuestas que mutaron después de auditorías, contradicciones entre artículos, reparaciones que generaron nuevos problemas y auditores que también cometieron errores.

Por eso IEvA incluye al auditor dentro del objeto de auditoría.

---

# Contrato de ejecución para una IA

Cuando se te pida **“aplica IEvA”**, haz esto:

1. **Declara cobertura.** Qué leíste completo, parcial, por resumen o solo por metadatos.
2. **Limita tu veredicto a esa cobertura.**
3. **Clasifica la afirmación.** Empírica, histórica, técnica, económica, filosófica, normativa, cultural, prospectiva, metodológica, etc.
4. **Usa una prueba apropiada para ese tipo de afirmación.**
5. **Distingue hallazgo de desacuerdo.** No conviertas una preferencia editorial en un defecto estructural.
6. **Para cada hallazgo material, muestra el mecanismo de falla y su consecuencia.**
7. **Acepta el resultado nulo.** No inventes un cadáver para demostrar que trajiste cuchillo.
8. **No declares originalidad ni redundancia sin contraste externo suficiente.**
9. **Separa auditoría de adjudicación.** El auditor propone; la autoridad editorial decide.
10. **Si una reparación cambia dependencias, ejecuta control horizontal.**
11. **Declara qué sigue abierto.**
12. **Declara qué no estás autorizado a concluir.**

---

# Cinco reglas que no debes olvidar

### 1. Cobertura
> **No juzgues el corpus que no leíste.**

Una fachada autoriza juicios sobre presentación. Un resumen autoriza panorama. Un artículo completo autoriza juicio interno. Varios artículos completos autorizan comparación horizontal. Corpus + literatura permite hablar de precedentes relativos.

### 2. Tipo de prueba
> **No todas las afirmaciones se prueban igual.**

Una afirmación empírica necesita evidencia. Una norma necesita consistencia, consecuencias y casos límite. Una afirmación histórica necesita fuentes. Una arquitectura institucional necesita análisis de incentivos. Una afirmación de originalidad necesita búsqueda bibliográfica.

### 3. Resultado nulo
> **“No encontré un hallazgo material nuevo” es una salida válida.**

Más hostilidad no significa más rigor. Más concesión tampoco.

### 4. Precedente ≠ redundancia
Encontrar una idea general parecida no demuestra que una formulación, aplicación o arquitectura completa sea redundante.

### 5. El auditor también falla
Una auditoría puede sufrir fallo de cobertura, amplificación, comparación desigual, asimetría de búsqueda, deriva de síntesis, contaminación entre rondas, marco inapropiado o inercia de hallazgo.

Por eso un veredicto fuerte puede requerir **contraauditoría**.

---

# Tipos de ronda

| **Ronda** | **Objetivo** |
|---|---|
| **Auditoría ciega** | Buscar hallazgos nuevos sin conocer auditorías previas |
| **Auditoría informada** | Evaluar conociendo genealogía y decisiones anteriores |
| **Verificación de reparación** | Comprobar si una corrección cerró el hallazgo |
| **Auditoría de regresión** | Buscar fallos nuevos creados por la reparación |
| **Auditoría horizontal** | Comparar compatibilidad entre documentos |
| **Contraauditoría** | Auditar alcance, procedencia y solidez del propio veredicto |
| **Contraste externo** | Comparar con datos, literatura, precedentes o especialistas |

No cuentes estas rondas como si fueran evidencia independiente equivalente.

---

# Cuándo parar

Una nueva ronda se justifica cuando puede cambiar materialmente el veredicto, la reparación, la atribución, una dependencia, una vacante o el estado de cierre.

Si otra ronda solo repite lo ya sabido sin cambiar ninguna decisión material, puede cerrarse provisionalmente.

> **Fractal no significa infinito.**

---

# Qué NO demuestra IEvA

IEvA no demuestra que un argumento sea verdadero, que una propuesta sea segura, que una idea sea original, que varios modelos sean independientes, que el consenso sintético equivalga a evidencia ni que documentar mucho sea equivalente a razonar mejor.

El método debe demostrar utilidad comparándose contra revisiones convencionales y aceptando resultados adversos.

---

# Fuente de verdad

Este README es una **capa de acceso**.

La única fuente normativa de IEvA es:

> [`ingenieria-evolutiva-de-argumentos.md`](./ingenieria-evolutiva-de-argumentos.md)

Las auditorías y casos históricos muestran cómo se aplicó el método, pero **no crean reglas por sí mismos**.

Ante una discrepancia, prevalece el documento metodológico vigente.
