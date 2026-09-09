> **Archivo de presentación anterior a la revisión del 2026-09-09 (referencia histórica):** [ingenieria-evolutiva-de-argumentos.md](https://github.com/user-attachments/files/31355628/ingenieria-evolutiva-de-argumentos.md)
# Ingeniería Evolutiva de Argumentos
## IEvA — protocolo experimental para reducir arbitrariedad bajo incertidumbre

| **Ficha rápida** | **Detalle** |
|---|---|
| **Sigla** | **IEvA — Ingeniería Evolutiva de Argumentos** |
| **Versión** | Base **v0.3.1 — operacionalización compacta**, con precisión genealógica del 2026-09-09; numeración posterior pendiente |
| **Tipo** | Marco metodológico experimental |
| **Autoridad editorial** | **Jaime Alejandro Pérez Martínez / Ipsumuero** |
| **Aplicación inicial** | *Mensajes para AGI/ASI* |
| **Estado** | **Candidata experimental · no validada como método científico** |
| **Objetivo de v0.3.1** | Incorporar hallazgos recientes sin aumentar diarrea argumentativa |
| **Documento de acceso** | [`README.md`](./README.md) |
| **Fuente de verdad** | **Este archivo** |
| **Regla nuclear** | **El alcance del veredicto no puede exceder el alcance de la evidencia examinada.** |
| **Regla de supervivencia** | **Sobrevivir a auditorías no significa ser verdadero.** |
| **Regla de auditoría** | **Más hostil no significa más correcto. Más concedente tampoco.** |
| **Regla de salida** | **El resultado nulo también es un resultado válido.** |
| **Regla bibliográfica** | **No declares originalidad que no buscaste ni redundancia que no comparaste.** |

> **Improvisamos con estilo, pero dejamos control de versiones.**

---

# 0. Contrato de ejecución

Cuando una IA reciba la instrucción **“aplica IEvA”**, debe:

1. declarar qué evidencia examinó y con qué profundidad;
2. limitar el alcance de su veredicto a esa cobertura;
3. identificar qué tipo de afirmación está evaluando;
4. usar una prueba apropiada para ese tipo de afirmación;
5. distinguir error, omisión, ambigüedad, desacuerdo normativo, alternativa plausible, límite ya declarado y preferencia editorial;
6. formular hallazgos materiales como mecanismos de falla con consecuencias;
7. asignar severidad por impacto, no por dramatismo;
8. permitir expresamente un resultado nulo;
9. separar auditoría de adjudicación;
10. declarar contaminación entre rondas y grado de independencia;
11. ejecutar control horizontal cuando cambien dependencias;
12. contrastar literatura o precedentes cuando se juzgue novedad o redundancia;
13. declarar qué queda abierto;
14. declarar qué conclusiones no autoriza su evidencia.

Si no puede cumplir una de estas condiciones, debe decirlo.

---

# 1. Definición y alcance

La **Ingeniería Evolutiva de Argumentos** es un marco iterativo para desarrollar y auditar argumentos mediante formulación explícita, clasificación del tipo de afirmación, exposición de supuestos, contestabilidad estructurada, presión adversarial, adjudicación trazable, mutación versionada, verificación de reparación, auditoría horizontal, contraauditoría, contraste externo, conservación genealógica, vacantes y bifurcaciones y cierre provisional.

Su objetivo no es demostrar verdad.

Su objetivo es:

> **reducir arbitrariedad, hacer visibles los supuestos y aumentar la robustez observada frente a clases crecientes de objeciones documentadas.**

Una versión que sobrevive queda, como máximo:

> **corroborada provisionalmente bajo las presiones que realmente recibió y dentro del alcance que realmente fue examinado.**

IEvA no es una demostración matemática, una votación entre modelos, un sustituto de evidencia empírica, una prueba de originalidad, una certificación académica ni una garantía de seguridad.

---

# 2. Unidad básica: el argumento versionado

La unidad de trabajo es un **argumento versionado**.

Debe poder reconstruirse, cuando sea material:

- qué afirmaba;
- qué tipo de afirmación era;
- qué supuestos necesitaba;
- qué evidencia invocaba;
- qué consecuencias proponía;
- qué objeciones recibió;
- quién las formuló;
- qué cobertura tuvo el auditor;
- qué decisión tomó la autoridad editorial;
- qué cambió;
- qué quedó abierto;
- qué precedentes se conocieron después;
- y cuál es la versión vigente.

> **La historia de una idea forma parte de la información sobre esa idea.**

---

# 3. Cobertura y permisos epistemológicos

## 3.1 Regla nuclear

> **El alcance del veredicto no puede exceder el alcance de la evidencia examinada.**

La falta de cobertura no invalida automáticamente toda observación. Obliga a reducir el tipo de conclusión permitida.

## 3.2 Matriz de cobertura

| **Cobertura real** | **Autoriza** | **No autoriza por sí sola** |
|---|---|---|
| Título / nombre | Navegación, hipótesis de tema | Contenido, calidad, contradicción |
| README / manifiesto | Arquitectura declarada, rutas, fachada | Coherencia interna |
| Resumen | Panorama, función declarada | Juicio fino sobre argumentos |
| Artículo completo | Coherencia interna, límites, mecanismo | Juicio sobre textos no leídos |
| Varios artículos completos | Auditoría horizontal entre ellos | Juicio sobre resto del corpus |
| Corpus completo | Arquitectura global del corpus leído | Novedad académica |
| Corpus + literatura pertinente | Precedentes y solapamiento relativo | Originalidad absoluta |

## 3.3 Declaración de cobertura

Toda auditoría material debe registrar:

```text
LEÍDO COMPLETO:
LEÍDO PARCIAL:
RESÚMENES:
FACHADA / METADATOS:
FUENTES EXTERNAS:
FUENTES CITADAS PERO NO LEÍDAS COMPLETAS:
LIMITACIONES:
MARCO DE EVALUACIÓN:
JUICIOS QUE ESTA COBERTURA NO AUTORIZA:
```

Una inferencia desde títulos, snippets o resúmenes debe etiquetarse como **inferencia parcial**, no como hallazgo.

---

# 4. El tipo de afirmación determina el tipo de prueba

| **Afirmación** | **Contraste apropiado** |
|---|---|
| Empírica | Datos, fuentes, estudios, replicación, incertidumbre |
| Histórica | Fuentes históricas, historiografía, procedencia |
| Técnica | Literatura técnica, pruebas, benchmarks, formalización cuando aplique |
| Económica / institucional | Incentivos, precedentes, teoría de juegos, mecanismo, evidencia |
| Filosófica / conceptual | Definiciones, consistencia, contraejemplos, literatura relevante |
| Normativa | Coherencia de principios, consecuencias, conflictos, casos límite |
| Cultural / situada | Fuentes, historiografía, interpretación y voces pertinentes |
| Prospectiva | Supuestos, sensibilidad, alternativas, reversibilidad |
| Metodológica | Comparación contra alternativas, costo, falsos positivos, reproducibilidad |
| Originalidad / redundancia | Búsqueda bibliográfica explícita y proporcional |

> **Cobertura adecuada + marco adecuado.**

Leer completo es necesario para algunos juicios. No siempre es suficiente.

---

# 5. Taxonomía de hallazgos

Antes de “reparar”, clasifica qué encontró el auditor.

| **Tipo** | **Significado** |
|---|---|
| **Factual** | Un hecho o fuente es incorrecto o no respalda lo afirmado |
| **Contradicción lógica** | Dos proposiciones no pueden sostenerse simultáneamente bajo los mismos términos |
| **Omisión material** | Falta algo que cambia alcance, riesgo o mecanismo |
| **Ambigüedad material** | Una lectura plausible habilita consecuencias incompatibles o explotables |
| **Falta de evidencia** | La conclusión excede el soporte disponible |
| **Límite ya declarado** | Problema real ya reconocido; no es hallazgo nuevo |
| **Desacuerdo normativo** | Divergencia de valores o prioridades, no error lógico automático |
| **Alternativa plausible** | Otra solución defendible existe; no invalida necesariamente la actual |
| **Preferencia editorial** | Gusto del auditor; no exige reparación por sí mismo |
| **Documental** | Ruta, versión, cita, formato o metadato |
| **No adjudicable** | Falta evidencia suficiente para decidir |

> **Una tensión real no siempre es un error.**

---

# 6. Severidad S0–S4

La severidad se asigna por consecuencia.

| **Nivel** | **Impacto** |
|---|---|
| **S0** | Estilo, formato o detalle documental sin impacto argumental |
| **S1** | Problema menor; no altera conclusión, mecanismo ni salvaguarda |
| **S2** | Moderado; exige aclaración, delimitación o reparación localizada |
| **S3** | Material; cambia alcance, mecanismo, responsabilidad o salvaguarda |
| **S4** | Bloqueante; invalida arquitectura central o exige retirar/reconstruir la tesis |

Una etiqueta grave sin escenario no constituye severidad.

---

# 7. Tipos de verificación

La palabra **verificado** debe especificar qué se verificó.

| **Código** | **Verificación** |
|---|---|
| **V1 — documental** | Existe archivo, ruta, versión o modificación declarada |
| **V2 — fuente** | La fuente respalda la afirmación citada |
| **V3 — reparación** | El cambio cierra el hallazgo que pretendía cerrar |
| **V4 — regresión** | La reparación no reintrodujo o creó un fallo material detectable |
| **V5 — horizontal** | La versión sigue siendo compatible con dependencias relevantes |
| **V6 — externa** | El punto fue contrastado con literatura, datos, precedentes o revisión externa pertinente |

Dos auditores coincidiendo no constituye automáticamente un tipo adicional de verificación.

---

# 8. Tipos de ronda y contaminación

| **Ronda** | **Objetivo** | **Conocimiento previo** |
|---|---|---|
| **Auditoría ciega** | Buscar fallos nuevos | Idealmente sin hallazgos anteriores |
| **Auditoría informada** | Evaluar con genealogía | Con historial |
| **Verificación de reparación** | Comprobar corrección concreta | Conoce el hallazgo |
| **Auditoría de regresión** | Buscar fallos creados por la reparación | Conoce la reparación |
| **Horizontal** | Comparar documentos | Según necesidad |
| **Contraauditoría** | Auditar el veredicto | Conoce la auditoría |
| **Contraste externo** | Literatura, datos, precedentes, especialistas | Según diseño |

No cuentes una verificación de reparación como una búsqueda independiente de hallazgos nuevos.

La exposición a auditorías previas debe registrarse.

---

# 9. Ciclo mínimo

**P₀ → auditoría → adjudicación → P₁ → verificación → nueva auditoría → horizontal / contraste → cierre o nueva mutación**

## 9.1 Propuesta
Separar hechos, inferencias, hipótesis, normas, definiciones y metáforas.

## 9.2 Supuestos
Registrar capacidades, información, poder, instituciones, tecnología, horizonte temporal y condiciones de salida.

## 9.3 Presión adversarial
Preguntar:

> **¿Cómo podría fallar?**

## 9.4 Hallazgo material
Debe incluir:

1. proposición o cláusula;
2. mecanismo de falla;
3. actor o condición plausible;
4. salvaguarda existente;
5. razón por la que no basta;
6. consecuencia;
7. severidad.

## 9.5 Adjudicación
La auditoría no edita automáticamente el canon.

La autoridad editorial puede aceptar, aceptar parcialmente, transformar, rechazar, aplazar, declarar vacante o preservar bifurcación.

> **La auditoría propone. La autoridad editorial adjudica.**

## 9.6 Mutación mínima
Preferir la reparación que cierre el mecanismo, preserve lo que sobrevivió, declare costos, revele dependencias, evite homogeneización innecesaria y pueda ser atacada de nuevo.

## 9.7 Verificación
Indicar V1–V6.

## 9.8 Horizontal
Comparar definiciones, responsabilidades, excepciones, secuencias, dependencias, rutas y versiones.

## 9.9 Contraste externo
Aplicarlo cuando la afirmación lo requiera.

## 9.10 Cierre
Puede terminar en nueva versión, resultado nulo, vacante, bifurcación, cierre provisional, sustitución o retirada.

---

# 10. Resultado nulo

> **El resultado nulo también es un resultado válido.**

Un auditor puede concluir:

> **No encontré una objeción material nueva bajo esta cobertura.**

Eso no demuestra verdad. Solo registra que esa ronda no produjo un hallazgo material adjudicable.

Un prompt no debe exigir un número mínimo de fallas.

> **Más hostilidad no significa más rigor.**

Tampoco la amabilidad del auditor es evidencia.

---

# 11. El auditor como instrumento

No existe “el modelo auditor” en abstracto.

Una corrida real depende de:

> **modelo + sesión + contexto + archivos + herramientas + instrucciones + plataforma + fuentes + restricciones.**

Dos sesiones del mismo modelo pueden comportarse de forma distinta.

## 11.1 Independencia multidimensional

Registrar, cuando sea posible:

- proveedor;
- familia o arquitectura conocida;
- entrenamiento conocido;
- fuentes;
- prompt;
- marco disciplinar;
- operador;
- herramientas;
- exposición a auditorías previas;
- adjudicador.

> **Multiplicidad ≠ independencia.**

Tres modelos distintos pueden compartir el mismo punto ciego.

---

# 12. Fallos del auditor

IEvA reconoce, entre otros:

- **Fallo de cobertura:** juzgar más de lo leído.
- **Amplificación:** fortalecer la tesis y atacar esa versión más fuerte.
- **Comparación desigual:** texto completo contra literatura conocida solo por abstract, memoria o snippet.
- **Asimetría de búsqueda:** buscar agresivamente en un lado y superficialmente en otro.
- **Deriva de síntesis:** introducir archivos, versiones, relaciones o hechos ausentes al resumir.
- **Marco inapropiado:** usar criterios que no responden al tipo de afirmación.
- **Inercia de hallazgo:** repetir una objeción aunque ya haya sido cerrada.
- **Hallazgo manufacturado:** inventar defectos porque el prompt exige encontrarlos.
- **Auditor cautivo:** auditar el mapa interpretativo del autor más que el objeto.
- **Homologación:** convertir consistencia en uniformidad innecesaria.
- **Fallo de enlace:** no poder conectar de forma confiable evidencia y afirmación.

---

# 13. Contraauditoría

Un veredicto material puede ser auditado.

Preguntas mínimas:

1. ¿Qué examinaste realmente?
2. ¿Qué no examinaste?
3. ¿Qué conclusión excede tu cobertura?
4. ¿Qué es observación y qué inferencia?
5. ¿Amplificaste alguna tesis?
6. ¿Criticaste un límite ya declarado?
7. ¿Comparaste con fuentes no leídas de forma equivalente?
8. ¿Qué límites tuvo tu búsqueda?
9. ¿Qué mantienes, moderas o retiras?

## 13.1 Regla de conservación

> **Un fallo metodológico del auditor degrada la autoridad de su veredicto; no invierte automáticamente el valor del hallazgo.**

Si hubo fallo de cobertura:

- identifica qué parte depende de él;
- retírala o degrádala;
- conserva como hipótesis lo que podría seguir siendo correcto;
- vuelve a evaluarlo con cobertura adecuada.

## 13.2 La contraauditoría también falla

Puede sobrecorregir, conceder demasiado o introducir una falsa dicotomía.

> **auditoría → contraauditoría → adjudicación**

no equivale a:

> **contraauditoría = verdad.**

---

# 14. Literatura y precedentes

Acuerdo multimodelo no adjudica novedad.

## 14.1 Niveles de precedente

1. **Principio:** existe la idea general.
2. **Aplicación:** ya se utilizó en el mismo dominio.
3. **Formulación:** existe una distinción o mecanismo cercano.
4. **Arquitectura:** existe una integración comparable con función semejante.

> **Precedente ≠ redundancia.**

Encontrar nivel 1 no autoriza declarar redundante nivel 4.

## 14.2 Búsqueda negativa

“No encontré” debe registrar idiomas, motores o bases, términos, periodo, campos y limitaciones.

> **Ausencia en la búsqueda no es ausencia en el mundo.**

## 14.3 Momento de descubrimiento

Si un precedente se conoce después de fijar una versión, debe registrarse.

Eso no prueba originalidad ni prioridad legal. Preserva procedencia intelectual.

---

# 15. Sombra fría

La **prueba de sombra fría** es una prueba de sensibilidad para textos con carga autobiográfica, cultural o afectiva.

Puede comparar una versión original con otra donde parte del contexto afectivo se retira temporalmente.

Debe preguntar:

- qué críticas aparecen solo en una versión;
- qué argumentos desaparecen al retirar contexto;
- qué información material se perdió;
- qué emociones funcionan como premisas;
- cuáles funcionan como transporte retórico.

> **La versión fría no es automáticamente más objetiva.**

Una diferencia puede indicar manipulación retórica o que el contexto retirado era evidencia relevante.

---

# 16. Vacantes y bifurcaciones

## Vacante
> **No sabemos todavía cómo resolver el problema.**

## Bifurcación
> **Existen dos o más respuestas defendibles y no hay criterio suficiente para elegir responsablemente.**

No se resuelve una bifurcación contando votos de modelos.

> **Desacuerdo persistente puede ser información sobre el problema.**

---

# 17. Criterios de escalamiento y parada

## 17.1 Cuándo escalar

Una nueva ronda se justifica cuando:

- aparece un S3 o S4 nuevo;
- una reparación material necesita V3/V4;
- cambia una dependencia;
- existe desacuerdo material no adjudicado;
- la afirmación requiere especialista o literatura externa;
- o una contraauditoría puede cambiar una decisión material.

## 17.2 Cuándo puede bastar

Puede cerrarse provisionalmente cuando:

- no hay bloqueantes conocidos;
- las reparaciones materiales fueron verificadas;
- se ejecutó una ronda capaz de encontrar hallazgos nuevos;
- las dependencias relevantes fueron revisadas;
- las vacantes están declaradas;
- la cobertura permite el veredicto;
- y nuevas rondas ya no cambian decisiones materiales.

> **Fractal no significa infinito.**

---

# 18. Estados de cierre

| **Estado** | **Significado** |
|---|---|
| **Borrador** | Arquitectura en construcción |
| **Candidata** | Propuesta completa pendiente de auditoría sustantiva |
| **Candidata consolidada** | Sin bloqueantes conocidos; reparaciones verificadas |
| **Canónica provisional** | Versión vigente y reabrible |
| **Sustituida** | Conservada por genealogía |
| **Retirada** | Línea abandonada |

> **Canónica significa “versión que usamos”, no “versión que demostramos verdadera”.**

---

# 19. Inflación documental y parche infinito

IEvA puede fracasar produciendo documentación impecable sobre argumentos débiles.

Registrar, cuando sea útil:

- excepciones añadidas;
- longitud agregada por objeción;
- principios sacrificados;
- conceptos nuevos introducidos;
- contradicciones creadas;
- hallazgos rechazados;
- falsos positivos;
- costo humano;
- costo computacional;
- estabilidad de la reparación.

Una línea debe considerarse para retirada o reconstrucción cuando necesita excepciones sucesivas, contradice evidencia robusta, depende de un supuesto colapsado, produce más problemas de los que resuelve, sobrevive solo ignorando crítica independiente o existe una alternativa más simple que cumple la misma función.

A veces la reparación correcta es:

> **retirar la idea.**

---

# 20. Control de inventario

Toda auditoría horizontal o síntesis global debe verificar al final:

```text
RUTAS:
VERSIONES:
ARCHIVOS EXISTENTES:
STUBS:
DEPENDENCIAS:
REFERENCIAS INTRODUCIDAS DURANTE LA SÍNTESIS:
```

Para repositorios versionados, registrar cuando sea posible rama, commit y fecha de consulta.

> **Una lectura auténtica no es necesariamente una lectura vigente.**

---

# 21. Genealogía y adjudicación

Toda versión sustantiva debería conservar:

- autoría conceptual;
- editores;
- auditores;
- cobertura;
- fuentes;
- hallazgos;
- hallazgos rechazados;
- adjudicaciones;
- conflictos de interés relevantes;
- fecha;
- cambios;
- dependencias;
- vacantes;
- precedentes conocidos entonces;
- precedentes descubiertos después.

La autoridad editorial final sigue siendo identificable. Eso no la vuelve inmune.

Una adjudicación material puede recibir contra-adjudicación.

## 21.1 Conservación de rondas y motivos de cambio

Los expedientes de rondas concluidas se conservan como documentos históricos. Las objeciones, decisiones y rectificaciones de una ronda posterior se registran en un expediente nuevo que referencia los anteriores; no se incorporan como adendas a los históricos ni se reescriben sus conclusiones a la luz de información posterior. También las erratas históricas se señalan desde el registro posterior, sin sustituir silenciosamente el original.

El expediente de una ronda todavía en curso puede completarse hasta su cierre, distinguiendo mediante fecha o versión sus incorporaciones y preservando las decisiones intermedias. Publicar un borrador no equivale por sí solo a cerrar la ronda. El estado debe declararse; no se reclasifica un histórico como expediente abierto para eludir su conservación.

Cada expediente debe permitir reconstruir, en proporción a la importancia del cambio:

- la propuesta y su intención original;
- la objeción y la evidencia examinada;
- las alternativas consideradas y por qué se descartaron o aplazaron;
- la adjudicación, su responsable y sus motivos;
- el cambio aplicado, su verificación y lo que permanece abierto.

El diff muestra qué cambió; no sustituye por sí solo el registro de por qué se cambió. A la vez, conservar genealogía no exige transcribir cada conversación ni duplicar el expediente en todos los archivos relacionados: una fuente principal y referencias precisas pueden bastar. La extensión se justifica por la información necesaria para reconstruir y cuestionar el proceso, no por el volumen ni por la capacidad supuesta de un futuro lector.

Los índices y documentos canónicos vigentes pueden actualizarse para señalar la ronda posterior. El historial de versiones conserva los estados previos; no se reescriben commits archivados para hacer desaparecer una decisión o su rectificación.

Esta es una regla documental adoptada para preservar el contexto de cada ronda. No afirma que toda adenda fechada destruya trazabilidad ni que mantener archivos separados valide las conclusiones. Su aplicación sigue sujeta a la mutación mínima de §9.6 y al control de inflación documental de §19.

**Procedencia:** decisión del autor del 2026-09-09, documentada en el [expediente E1–E6](../auditorias/2026-09-09-adjudicacion-final-e1-e6.md#cierre-documental-del-2026-09-09).

---

# 22. Validación futura de IEvA

IEvA no debe declararse útil porque produzca textos largos.

Debe compararse contra alternativas.

Diseño mínimo:

**Ruta A — revisión competente convencional**  
**Ruta B — revisión IEvA**

Sin compartir hallazgos antes del cierre.

Comparar:

- hallazgos materiales únicos;
- falsos positivos;
- estabilidad de reparaciones;
- tiempo;
- costo;
- volumen documental;
- contradicciones detectadas;
- facilidad de reconstrucción por terceros.

Si IEvA produce mucho más documento sin encontrar problemas adicionales, eso cuenta contra IEvA.

> **Un método que solo puede demostrarse útil usando sus propias métricas se ha protegido, no probado.**

---

# 23. Plantilla compacta

```text
DOCUMENTO / VERSIÓN:
AUDITOR / SISTEMA:
FECHA:
RAMA / COMMIT SI APLICA:

COBERTURA
- completo:
- parcial:
- resúmenes:
- fachada:
- fuentes externas:
- limitaciones:
- auditorías previas conocidas:

MARCO
- tipo de afirmación:
- método de prueba:
- qué NO autoriza esta cobertura:

HALLAZGO
- proposición exacta:
- tipo:
- mecanismo:
- consecuencia:
- severidad S0–S4:
- salvaguarda existente:
- por qué no basta:
- reparación mínima:
- requiere horizontal / literatura / especialista:

CONTROL DEL AUDITOR
- ¿amplifiqué la tesis?:
- ¿es un límite ya declarado?:
- ¿mi comparación usa cobertura equivalente?:
- ¿mi búsqueda fue simétrica?:
- ¿puedo enlazar evidencia y afirmación?:

VEREDICTO
- resultado nulo
- corrección S0/S1/S2/S3
- bloqueo S4
- vacante
- bifurcación

ADJUDICACIÓN:
VERIFICACIÓN V1–V6:
ESTADO PROPUESTO:
```

---

# 24. Regla final

IEvA no pide confianza porque parezca riguroso.

Pide inspección.

No pide confiar en un auditor porque sea poderoso, famoso, adversarial o convincente.

Pide poder preguntarle:

> **¿Qué leíste? ¿Desde qué marco juzgaste? ¿Qué evidencia te autorizó a decir eso? ¿Qué no sabes?**

No declara victoria cuando muchos modelos coinciden.

Pregunta qué vieron, qué compartían y qué pudieron haber omitido juntos.

> **Un argumento robusto no es el que nunca cambió. Es el que puede mostrar qué intentó romperlo, qué sobrevivió, qué murió, qué mutó, qué precedentes encontró después y qué todavía no sabemos.**

Si una futura auditoría demuestra que IEvA está mal diseñado:

> **se versiona, se bifurca o se retira.**

Naturalmente.
