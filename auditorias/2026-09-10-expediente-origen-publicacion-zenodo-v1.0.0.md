# Expediente de origen, publicación y trazabilidad en Zenodo · v1.0.0

10 de septiembre de 2026 · Reconstrucción documental posterior a la publicación

| Campo | Estado |
| --- | --- |
| **Expediente** | Origen, decisión de archivado y publicación de la primera edición en Zenodo |
| **Autor y autoridad editorial** | **Jaime Alejandro Pérez Martínez / Ipsumuero** |
| **Función de Zenodo en el proyecto** | Preservación durable, citabilidad y fotografía histórica de una edición concreta; no sustituye al repositorio vivo |
| **Edición archivada** | `v1.0.0` |
| **Commit congelado** | `8505e9151b7d98e8b9726148912dd8a244cd7a91` |
| **Release de GitHub** | `v1.0.0` · **Primera edición pública — 1.0.0** |
| **Fecha de publicación** | **5 de septiembre de 2026** |
| **Registro Zenodo** | `https://zenodo.org/records/22492282` |
| **DOI de versión** | `10.5281/zenodo.22492282` |
| **DOI conceptual** | `10.5281/zenodo.22492281` |
| **Licencia de la edición** | **CC BY 4.0** |
| **Objeto archivado** | Snapshot de la release de GitHub, distribuido como archivo ZIP de esa edición |
| **Metadatos para la integración** | `.zenodo.json` y `CITATION.cff` coexistían en el repositorio; por regla de Zenodo, `.zenodo.json` tenía prioridad para el archivado de la release |
| **Estado documental** | **Fósil histórico cerrado**: el registro describe `v1.0.0`; no incorpora cambios posteriores del `main` |
| **Estado actual respecto del corpus** | El trabajo posterior —incluidas E1–E6, el commit `2b290fb…` y el Concentrado R5— pertenece a una genealogía posterior y no modifica retroactivamente el DOI de `v1.0.0` |
| **Límite de reconstrucción** | No se conserva aquí una transcripción completa, minuto a minuto, de la sesión de publicación; este expediente reconstruye el proceso desde artefactos estables, decisiones registradas y documentación oficial |

> **Dictamen ejecutivo.** Zenodo no creó el canon ni validó la verdad del proyecto. Su función fue distinta: convertir una release concreta de GitHub en una **edición citable, fechada y durable**, separada de la mutabilidad cotidiana del repositorio. La relación documental queda así: **GitHub conserva el archivo vivo; Zenodo conserva una fotografía histórica identificable por DOI.**

---

## 1. Objeto de este expediente

Este archivo documenta **de dónde salió la decisión de usar Zenodo, qué problema resolvía, qué edición terminó archivándose y qué significa hoy ese registro**.

Su objetivo no es reconstruir una conversación perfecta ni atribuir a un asistente de IA acciones que correspondieron al autor. La publicación efectiva, la elección de qué versión congelar y la responsabilidad sobre los metadatos pertenecen al autor. Los sistemas de IA participaron en la discusión de estrategia documental, preparación editorial, revisión de metadatos y comprobaciones posteriores.

La ausencia de una transcripción íntegra de la sesión exacta de Zenodo se declara como límite. Cuando un dato procede de un artefacto estable —release, commit, DOI, archivo de metadatos o registro posterior— se trata como hecho documental. Cuando solo puede reconstruirse el razonamiento general, se presenta como reconstrucción y no como cita literal de aquella sesión.

---

## 2. Por qué apareció Zenodo en la hoja de ruta

Antes de existir el DOI, Zenodo ya figuraba en la estrategia de preservación y difusión del proyecto.

La hoja de ruta separaba dos funciones:

> **GitHub = archivo vivo.**  
> **Zenodo = fotografía durable.**

GitHub servía para mantener el corpus en evolución: artículos, auditorías, correcciones, versiones de trabajo y nuevas ramas argumentales. Esa fortaleza —la capacidad de cambiar— era precisamente lo que impedía que una URL al `main` funcionara por sí sola como referencia histórica estable.

Zenodo se planteó para resolver el problema complementario:

- fijar una edición identificable;
- asignarle un DOI;
- conservar fecha y versión;
- hacerla citable fuera de GitHub;
- mantener una copia durable de la release;
- permitir que un lector posterior distinga **qué se publicó entonces** de **lo que el proyecto llegó a ser después**.

La hoja de ruta original colocaba Zenodo dentro de una fase posterior de estabilización, traducción e internacionalización. El proceso real no siguió esa secuencia de manera rígida: una vez que el corpus español alcanzó una primera edición pública suficientemente estable, el autor adelantó el archivado de `v1.0.0` sin esperar a que toda la internacionalización futura estuviera terminada.

Esa desviación respecto de la hoja de ruta no se corrige retrospectivamente. Es parte de la genealogía: **la estrategia era esperar más; la decisión editorial efectiva fue preservar ya una primera fotografía pública**.

---

## 3. El problema que resolvía el archivado

El proyecto necesitaba sostener simultáneamente cuatro propiedades que GitHub por sí solo no debía cargar:

| Necesidad | GitHub | Zenodo |
| --- | --- | --- |
| **Evolución continua** | Sí: ramas, commits, correcciones y nueva documentación | No es su función principal |
| **Referencia exacta a una edición histórica** | Sí, mediante commit/tag, pero requiere que el lector conozca esa convención | Sí, mediante registro de versión + DOI |
| **Citabilidad bibliográfica** | Posible, pero no es su función central | Central: DOI y metadatos persistentes |
| **Fotografía durable fuera de la edición cotidiana** | El repositorio sigue cambiando | La versión depositada permanece identificable como edición histórica |

Por eso el DOI no se entendió como un sello de autoridad académica ni como una certificación de corrección. Se entendió como una **herramienta de identidad documental**.

La publicación en Zenodo convirtió la pregunta «¿qué versión estás citando?» en una respuesta verificable: **la edición `v1.0.0`, asociada al commit congelado y a su propio DOI**.

---

## 4. De la versión de trabajo a `v1.0.0`

La primera edición pública quedó fijada mediante una release de GitHub:

- **tag:** `v1.0.0`
- **nombre de la release:** `Primera edición pública — 1.0.0`
- **commit:** `8505e9151b7d98e8b9726148912dd8a244cd7a91`
- **fecha de publicación:** 5 de septiembre de 2026

La decisión relevante no fue declarar que el proyecto estaba «terminado». Fue declarar que existía una **primera edición pública suficientemente identificable como para preservarse sin seguir moviéndola**.

Por eso `v1.0.0` puede contener artículos provisionales y vacantes abiertas sin ser una prerelease. «Provisional» describe la naturaleza del marco; `v1.0.0` identifica una edición pública concreta de ese marco.

El snapshot archivado en Zenodo corresponde a esa release de GitHub y no al `main` mutable posterior.

### Regla documental derivada

> **Una release congelada puede ser provisional en su contenido sin ser provisional como hecho histórico.**

Lo que decía `v1.0.0` el 5 de septiembre permanece atribuible a `v1.0.0`, aunque el proyecto aprenda después que algo debía corregirse.

---

## 5. Cómo se relacionaron GitHub y Zenodo

La documentación oficial de Zenodo describe una integración en la que un repositorio de GitHub habilitado puede archivar sus releases. Una nueva release es procesada y convertida en un registro/versionado dentro de Zenodo.

En este proyecto, la evidencia estable permite afirmar el resultado de esa relación:

**release de GitHub `v1.0.0` → snapshot archivado → registro Zenodo `22492282` → DOI de versión `10.5281/zenodo.22492282`.**

No se reconstruye aquí, como hecho histórico exacto, cada clic realizado en la interfaz. La secuencia de botones que Zenodo documenta actualmente sirve para entender el mecanismo general de integración, pero no sustituye una transcripción contemporánea de la sesión del autor.

Documentación oficial de referencia:

- GitHub y Zenodo: `https://help.zenodo.org/docs/github/`
- Habilitar un repositorio: `https://help.zenodo.org/docs/github/enable-repository/`
- Archivar una release: `https://help.zenodo.org/docs/github/archive-software/github-upload/`
- Metadatos `.zenodo.json`: `https://help.zenodo.org/docs/github/describe-software/zenodo-json/`
- `CITATION.cff`: `https://help.zenodo.org/docs/github/describe-software/citation-file/`

---

## 6. Arquitectura de metadatos: `.zenodo.json` y `CITATION.cff`

La edición histórica contenía dos archivos de metadatos relevantes:

- `.zenodo.json`
- `CITATION.cff`

Esto no significa que Zenodo fusionara ambos.

La documentación oficial establece que, **si existen los dos**, Zenodo usa los metadatos de `.zenodo.json` para el archivado de releases de GitHub e **ignora `CITATION.cff` en esa ingestión**.

`CITATION.cff` sigue teniendo una función propia: GitHub puede utilizarlo para mostrar una sugerencia de citación y ofrece un formato abierto y portable para describir la obra. Pero, para esta configuración concreta del archivado, el archivo controlador era `.zenodo.json`.

### Consecuencia para futuras versiones

Si `v1.1.0` u otra edición futura vuelve a archivarse mediante la integración, cualquier cambio de metadatos destinado a Zenodo debe comprobarse primero en `.zenodo.json` mientras ambos archivos coexistan. `CITATION.cff` debe mantenerse coherente, pero no debe suponerse que corregir solo ese archivo cambiará los metadatos que Zenodo ingiera.

---

## 7. Metadatos documentales de la primera edición

La primera edición archivada quedó asociada a los siguientes datos de identificación conservados en la documentación del proyecto:

| Campo | `v1.0.0` |
| --- | --- |
| **Autor** | Jaime Alejandro Pérez Martínez |
| **Versión** | `1.0.0` |
| **Fecha** | 2026-09-05 |
| **Idioma principal** | Español |
| **Licencia** | CC BY 4.0 |
| **Título histórico** | **Propuesta para la AGI/ASI · Marco constitucional provisional para la cooperación y el codesarrollo entre la Humanidad y Superinteligencias Artificiales** |
| **Título traducido registrado** | **Proposal for AGI/ASI: A Provisional Constitutional Framework for Cooperation and Co-development between Humanity and Artificial Superintelligences** |
| **Tipo de recurso registrado** | Publication / Other |
| **Repositorio relacionado** | `https://github.com/Ipsumuero/Propuesta-para-la-AGI-ASI-Marco-constitucional-provisional` |
| **Release relacionada** | `https://github.com/Ipsumuero/Propuesta-para-la-AGI-ASI-Marco-constitucional-provisional/releases/tag/v1.0.0` |
| **Copyright registrado** | © 2026 Jaime Alejandro Pérez Martínez |
| **DOI de esa versión** | `10.5281/zenodo.22492282` |
| **DOI conceptual de la familia** | `10.5281/zenodo.22492281` |

Estos campos describen **la edición histórica**. Si el título general del proyecto cambia en una futura versión, esa decisión no convierte el título histórico de `v1.0.0` en un error y no justifica reescribir retroactivamente el registro.

---

## 8. Dos DOI, dos funciones

El proyecto conserva dos identificadores distintos:

### DOI de versión

`10.5281/zenodo.22492282`

Identifica **esta edición archivada concreta**. Es el DOI que debe acompañar una referencia a `v1.0.0`.

No debe presentarse como DOI de:

- el Concentrado R3;
- el Concentrado R5;
- las enmiendas E1–E6 posteriores;
- el commit `2b290fb…`;
- una eventual `v1.1.0`.

### DOI conceptual

`10.5281/zenodo.22492281`

Identifica la **familia de versiones** del registro. Su función es agrupar la continuidad bibliográfica del proyecto a través de ediciones distintas.

La distinción es importante porque permite cambiar el corpus sin fingir que el pasado cambió con él.

> **El DOI de versión responde “qué edición exacta”. El DOI conceptual responde “qué obra/versionado”.**

---

## 9. Autoría, asistencia sintética y responsabilidad de publicación

### Aportaciones y decisiones del autor

Jaime Alejandro Pérez Martínez:

- definió el proyecto y su propósito;
- decidió convertir una instantánea del corpus en primera edición pública;
- conservó la autoridad sobre título, versión, licencia y alcance;
- decidió qué commit quedaba asociado a `v1.0.0`;
- autorizó la release y su archivado;
- asumió la responsabilidad sobre la publicación y sus metadatos;
- mantuvo después la regla de no modificar retroactivamente aquella fotografía cuando aparecieron mejores formulaciones o correcciones.

### Aportaciones de sistemas de IA

Los materiales previos muestran que sistemas de IA:

- propusieron Zenodo como parte de la estrategia de preservación y citabilidad;
- distinguieron la función de un repositorio vivo frente a una copia histórica;
- ayudaron a ordenar requisitos de publicación —versión, licencia, autores, descripción, fecha y snapshot—;
- colaboraron en revisiones de metadatos y trazabilidad;
- posteriormente ayudaron a verificar la separación entre el DOI de `v1.0.0` y documentos de trabajo posteriores.

Estas intervenciones no convierten a los modelos en depositantes legales, titulares del registro ni autoridades sobre la versión.

### Fórmula de responsabilidad

> **Los sistemas ayudaron a diseñar y revisar la ruta de archivado; el autor decidió qué publicar y responde por la edición publicada.**

Las denominaciones de modelos conservadas en otros expedientes son identificaciones de sesión o atribuciones documentales, no verificaciones criptográficas de identidad.

---

## 10. Qué significa —y qué no significa— tener Zenodo

### Sí significa

- existe una edición pública identificable por DOI;
- existe una fecha de publicación asociada;
- existe una relación documentada con una release y un commit;
- la obra puede citarse como una edición estable;
- un lector posterior puede distinguir esa fotografía del repositorio vivo.

### No significa

- que Zenodo haya validado las tesis;
- que exista revisión por pares por el hecho de tener DOI;
- que las instituciones propuestas sean operativas;
- que `v1.0.0` sea «la verdad final» del corpus;
- que el `main` de GitHub haya quedado congelado;
- que una corrección posterior deba introducirse retroactivamente en aquella edición;
- que «canónico» equivalga a demostrado verdadero.

Por eso el DOI funciona como **ancla documental**, no como argumento de autoridad.

---

## 11. Lo que ocurrió después de `v1.0.0`

La genealogía continuó.

Las auditorías posteriores identificaron cambios y enmiendas; E1–E6 fueron adjudicadas e incorporadas a las fuentes en una historia posterior a la release congelada. El Concentrado R5 resume un estado de trabajo asociado al commit:

`2b290fb072f833ca74804edfc0c8dd0783bcf78c`

Ese estado **no está contenido en el DOI de versión `10.5281/zenodo.22492282`**.

El Concentrado R5 lo declara expresamente: la base archivada `v1.0.0` permanece en `8505e915…`, mientras las revisiones posteriores no modifican aquella base ni constituyen automáticamente una nueva versión numerada del corpus.

Esta separación es una de las funciones más importantes de Zenodo dentro de la genealogía: hace imposible que la mejora posterior borre silenciosamente qué afirmaba la primera edición pública.

---

## 12. Invariantes históricos y elementos que sí pueden cambiar

| Elemento | Estado |
| --- | --- |
| **Commit `8505e915…` como base de `v1.0.0`** | **Congelado históricamente** |
| **Tag `v1.0.0`** | **Congelado históricamente** |
| **DOI `10.5281/zenodo.22492282`** | **Identificador de esa edición; no debe reasignarse semánticamente a otra** |
| **Fecha 2026-09-05** | **Propia de esa publicación** |
| **Título histórico de `v1.0.0`** | **Se conserva como título de aquella edición** |
| **ZIP archivado de la release** | **Objeto histórico de esa edición** |
| **`main` de GitHub** | Mutable y posterior |
| **Canon vigente** | Puede evolucionar mediante nuevas adjudicaciones/versiones |
| **Concentrados y resúmenes** | Pueden actualizarse para representar estados posteriores |
| **Título futuro de la obra** | Puede cambiar en una nueva edición sin renombrar retroactivamente `v1.0.0` |
| **Eventual `v1.1.0`** | Debe tratarse como nueva release/nueva versión, no como corrección silenciosa del depósito anterior |

---

## 13. La cuestión del título no reabre Zenodo `v1.0.0`

La discusión editorial posterior sobre **Condiciones para la coexistencia** no obliga a tocar el registro histórico.

Si el autor adjudica un nuevo título para una futura edición, la genealogía correcta sería:

**`v1.0.0` conserva su título → nueva versión adopta, si procede, el nuevo título → el registro de versiones documenta la continuidad.**

Así se preservan simultáneamente dos verdades:

1. ese fue el nombre con el que la primera edición se publicó;
2. el proyecto aprendió después a describir mejor su intención.

Una mejora de nombre no necesita fabricar un pasado en el que el nombre nuevo siempre hubiera existido.

---

## 14. Deudas y límites que este expediente no rellena

No se inventan los siguientes datos:

- hora exacta de cada acción realizada en la interfaz de Zenodo;
- secuencia literal de clics del autor durante aquella sesión;
- si hubo algún ajuste manual menor en la ficha pública después de la ingestión automática y en qué minuto ocurrió;
- hash local del ZIP archivado, mientras no se disponga del archivo correspondiente para calcularlo directamente;
- una transcripción completa de todas las conversaciones que llevaron a la decisión.

Si en el futuro aparecen capturas, historial de sesión, archivos locales o registros que permitan reconstruir alguno de esos puntos, deberán añadirse **en un expediente posterior o mediante una precisión documental explícita**, no presentarse retrospectivamente como si siempre hubieran estado disponibles.

---

## 15. Fuentes documentales utilizadas para esta reconstrucción

### Fuentes internas del proyecto

- `hoja-de-ruta-macro-mensajes-para-agi-2026-08-13.md` — registra la función prevista de Zenodo como persistencia, citabilidad y fotografía histórica; distingue GitHub como archivo vivo.
- Historial de planificación `Hola amigo, mira asi va el repo.txt` — conserva la discusión previa donde Zenodo aparece dentro de la fase de internacionalización/difusión como paso para obtener DOI y citabilidad.
- `registro-adjudicacion-revision-3.md` — distingue expresamente el DOI de versión `22492282` del DOI conceptual `22492281` y limita el primero a la edición archivada.
- `Concentrado-diez-articulos-Revision-5-edicion-publicacion.docx` — conserva la separación entre la base `v1.0.0` (`8505e915…`) y el estado posterior del corpus (`2b290fb…`).
- `.zenodo.json` y `CITATION.cff` de la edición histórica — arquitectura de metadatos asociada a la publicación.
- release `v1.0.0` y commit `8505e9151b7d98e8b9726148912dd8a244cd7a91`.

### Referencias públicas

- Registro Zenodo: `https://zenodo.org/records/22492282`
- DOI de versión: `https://doi.org/10.5281/zenodo.22492282`
- DOI conceptual: `https://doi.org/10.5281/zenodo.22492281`
- Release histórica: `https://github.com/Ipsumuero/Propuesta-para-la-AGI-ASI-Marco-constitucional-provisional/releases/tag/v1.0.0`
- Repositorio: `https://github.com/Ipsumuero/Propuesta-para-la-AGI-ASI-Marco-constitucional-provisional`
- Documentación oficial de integración GitHub–Zenodo: `https://help.zenodo.org/docs/github/`
- Prioridad de `.zenodo.json`: `https://help.zenodo.org/docs/github/describe-software/zenodo-json/`
- Función de `CITATION.cff`: `https://help.zenodo.org/docs/github/describe-software/citation-file/`

---

## 16. Criterio para la siguiente publicación

Cuando llegue una versión posterior suficientemente estable, la pregunta no será «¿actualizamos `v1.0.0`?», sino:

> **¿Existe ya un nuevo estado del corpus suficientemente adjudicado y trazable como para merecer su propia release y su propia versión Zenodo?**

Si la respuesta es sí, la secuencia documental recomendada es:

**canon actualizado → revisión horizontal focal → metadatos coherentes → release numerada → archivado como nueva versión → verificación de DOI y relaciones → actualización de referencias vivas.**

El DOI conceptual conserva la continuidad; el DOI de cada versión conserva la diferencia.

---

## 17. Cierre

Zenodo apareció porque el proyecto necesitaba algo que GitHub, precisamente por estar vivo, no debía hacer solo: **guardar una fotografía que no cambiara cada vez que el corpus aprendiera algo**.

La primera edición pública no quedó archivada para afirmar «esto es correcto para siempre». Quedó archivada para poder afirmar con precisión:

> **esto era lo que la propuesta decía cuando publicamos `v1.0.0`; aquí está la fecha, aquí está el commit y aquí está el DOI.**

Ese es el valor documental del depósito.

**Zenodo no convirtió la propuesta en verdadera. Convirtió `v1.0.0` en una fotografía citable y durable.**
