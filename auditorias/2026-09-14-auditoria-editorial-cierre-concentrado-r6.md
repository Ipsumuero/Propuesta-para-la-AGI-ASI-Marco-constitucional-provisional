---
titulo: "Auditoría editorial y general de cierre del Concentrado R6"
fecha: 2026-09-14
tipo: "auditoría documental, de regresión y preparación de versión"
estado: "apto para preparar el commit de release v1.1.0"
---

# Auditoría editorial y general de cierre del Concentrado R6

## Acta de preparación previa a `v1.1.0`

| **Ficha de control** | **Resultado** |
|---|---|
| **Fecha de ejecución** | 2026-09-14 · UTC |
| **Repositorio** | `Ipsumuero/Propuesta-para-la-AGI-ASI-Marco-constitucional-provisional` |
| **Rama y base examinada** | `main` · `93634ef1ec18b76a669f27d333e17075e7c1c1d4` |
| **Método** | IEvA v0.3.1 · V1 documental, V3 reparación, V4 regresión, V5 horizontal y V6 externa localizada |
| **Auditor** | Sesión de OpenAI Codex; la interfaz identifica el entorno, pero no aporta una atestación independiente y firmada de la identidad técnica exacta del modelo |
| **Autoridad editorial** | Jaime Alejandro Pérez Martínez / Ipsumuero |
| **Objeto principal** | Publicación Markdown del Concentrado R6 en español e inglés, licencia raíz, navegación, manifiesto estructurado y estado general pre-release |
| **Canon** | **Once artículos; sin ampliación ni modificación doctrinal** |
| **Veredicto** | **APTO PARA PREPARAR EL COMMIT DE RELEASE `v1.1.0`, con una compuerta de metadatos todavía pendiente** |

> [!IMPORTANT]
> Esta acta no crea la versión `v1.1.0`, no mueve etiquetas y no deposita en Zenodo. Certifica que el cierre editorial y documental revisado puede pasar a una operación de release separada.

---

# 1 · Declaración de cobertura IEvA

**LEÍDO COMPLETO:**

- Concentrado R6 en español;
- Digest R6 en inglés;
- `README.md`, `AI.md`, `resumenes-de-articulos/README.md` y `auditorias/README.md`;
- `repository-manifest.json`, `CITATION.cff` y `.zenodo.json`;
- licencia CC BY 4.0 incorporada como `LICENSE`;
- metodología IEvA vigente y los registros inmediatamente relevantes para el cierre de R5 y la integración del Artículo 0.

**LEÍDO PARCIAL / CONTROLADO POR INVENTARIO:**

- los once artículos canónicos fueron controlados por existencia, unicidad de ruta, orden, destino de enlaces y líneas citadas por el manifiesto de R6;
- el resto de los Markdown del repositorio fue sometido a parseo y resolución de enlaces internos, no a una nueva auditoría doctrinal integral.

**FACHADA / METADATOS:**

- manifiesto JSON con rechazo de claves duplicadas;
- CFF y metadatos de Zenodo;
- índices de raíz, resúmenes y auditorías;
- inventario de nombres, rutas y colisiones por mayúsculas/minúsculas.

**FUENTES EXTERNAS:**

- documentación oficial de GitHub sobre [licencias de repositorio](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository);
- texto legal oficial de [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode).

**LIMITACIONES:**

- no existía todavía un depósito de Zenodo para `v1.1.0`, por lo que no pudo verificarse su DOI, sus archivos ni su página pública;
- no se realizó en esta ronda una búsqueda bibliográfica de novedad ni una validación científica o empírica de las propuestas;
- el cotejo inglés-español fue editorial y estructural; no equivale a una traducción jurada;
- el parseo correcto y la resolución de enlaces no demuestran la verdad de su contenido.

**JUICIOS QUE ESTA COBERTURA NO AUTORIZA:**

- verdad, originalidad absoluta, seguridad o eficacia institucional del marco;
- consciencia, agencia o estatus moral de ningún sistema;
- asesoría jurídica sobre casos concretos;
- garantía de que GitHub, Zenodo o terceros conservarán indefinidamente sus interfaces o metadatos.

---

# 2 · Inventario controlado

## 2.1 Artefactos incorporados

| **Ruta** | **Función** | **Estado** |
|---|---|---|
| `resumenes-de-articulos/Condiciones-para-la-coexistencia-Concentrado-once-articulos-R6.md` | Edición española de referencia del Concentrado R6 | Incorporada |
| `resumenes-de-articulos/Conditions-for-Coexistence-Digest-Eleven-Articles-R6.md` | Traducción inglesa revisada, con prevalencia declarada del español | Incorporada |
| `LICENSE` | Texto estándar íntegro de CC BY 4.0 para reconocimiento por GitHub y consulta local | Incorporado en la raíz |
| `auditorias/2026-09-14-auditoria-editorial-cierre-concentrado-r6.md` | Esta acta de cierre pre-release | Incorporada |

## 2.2 Navegación y metadatos reparados

| **Ruta** | **Cambio permitido** |
|---|---|
| `README.md` | Enlaces a R6, estructura real y vínculo a `LICENSE` |
| `AI.md` | Entrada transversal a ambas ediciones R6 y alcance no normativo |
| `resumenes-de-articulos/README.md` | R6 como edición transversal vigente; R5 preservado como antecedente histórico |
| `auditorias/README.md` | Incorporación de esta acta y del registro de antecedentes públicos |
| `repository-manifest.json` | Rutas de R6, regla de traducción, auditoría de cierre y archivo de licencia |

## 2.3 Objetos expresamente preservados

- los once archivos de `articulos/`;
- el Concentrado R5;
- todas las auditorías históricas;
- el tag y release `v1.0.0`;
- el commit archivado `8505e9151b7d98e8b9726148912dd8a244cd7a91`;
- el DOI histórico `10.5281/zenodo.22492282`;
- `CITATION.cff` y `.zenodo.json` en versión `1.0.0`, hasta la operación posterior de release.

---

# 3 · Hallazgos y adjudicación

| **ID** | **Severidad** | **Mecanismo de falla observado** | **Adjudicación y verificación** |
|---|---:|---|---|
| F-01 | S1 | El repositorio declaraba CC BY 4.0 en metadatos, pero carecía del archivo raíz que permite consultar el texto y favorece su detección por GitHub. | Se incorporó el texto estándar íntegro como `LICENSE`. V1, V3, V4 y contraste externo localizado V6. |
| F-02 | S1 | El índice de resúmenes aún presentaba R5 como edición transversal más reciente y R6 como futuro. | Se declaró R6 vigente y R5 histórico, sin reescribir R5. V1, V3, V4 y V5. |
| F-03 | S1 | R6 no era navegable desde las fachadas principales ni estaba descrito en el manifiesto estructurado. | Se añadieron rutas, regla de precedencia lingüística y naturaleza no normativa. V1, V3, V4 y V5. |
| F-04 | S0 | El documento metodológico interno retirado ya no aparece en índices activos ni como enlace. Su nombre subsiste una sola vez, sin hipervínculo, en el inventario de un expediente histórico anterior. | Se preservó esa mención genealógica para no reescribir una auditoría histórica. No existe enlace roto ni entrada activa de manifiesto. |
| F-05 | S0 · compuerta | `CITATION.cff` y `.zenodo.json` todavía declaran `1.0.0`. Cambiarlos antes de fijar fecha y commit de release confundiría preparación con publicación. | Se mantuvieron intactos deliberadamente. Deben actualizarse juntos, con la fecha real, en el siguiente commit de release. |

**Resultado doctrinal nulo:** bajo esta cobertura no apareció una objeción material nueva S2–S4 contra el canon. Este resultado significa únicamente que la integración documental revisada no introdujo una falla doctrinal detectable; no certifica la verdad del marco.

---

# 4 · Matriz de verificación

| **Control** | **Resultado** | **Código IEvA** |
|---|---|---|
| `repository-manifest.json` parsea con un cargador que rechaza claves duplicadas | Superado | V1 · V4 |
| El manifiesto contiene exactamente 11 registros de artículo | Superado | V1 |
| `ruta_de_lectura_recomendada` contiene 11 rutas únicas | Superado | V1 · V5 |
| Orden exacto `2 → 3 → 4 → 0 → 6 → 5 → 7 → 8 → 9 → 1 → 1.5` | Superado | V1 · V5 |
| Existen los 11 destinos canónicos de la ruta | Superado | V1 |
| R6 español e inglés contienen 11 secciones, 11 citas de manifiesto y 11 fuentes canónicas | Superado | V1 · V5 |
| Las cinco puertas del Artículo 5 permanecen numeradas `1–5` en ambas ediciones | Superado | V4 · V5 |
| La cita del Artículo 0 apunta a `#L625` en ambas ediciones | Superado | V1 · V5 |
| Los once anclajes del manifiesto corresponden a líneas existentes del canon fuente | Superado | V1 · V5 |
| El inglés conserva el paquete «content, confidence, provenance, context, weight, power, action and exit» | Superado | V4 · V5 |
| El inglés declara que el texto español prevalece ante divergencias | Superado | V1 · V5 |
| Todos los Markdown del repositorio parsean como GFM | Superado | V4 |
| Todos los enlaces Markdown internos resuelven a destinos existentes | Superado | V4 · V5 |
| No existen colisiones de ruta insensibles a mayúsculas/minúsculas | Superado | V4 |
| `git diff --check` | Superado | V4 |
| Canon, R5 y metadatos históricos de release sin cambios | Superado | V4 · V5 |

## 4.1 Huellas SHA-256 de los artefactos principales

| **Archivo** | **SHA-256** |
|---|---|
| R6 español | `7143ee746ddf7507786f1e842422559068fb751b9a1427ed35c2f619ad8df884` |
| R6 inglés | `63a75dfa180af43eaedeefd2147c14a5ef68df5d115e3a1df8b695c88cda96de` |
| `LICENSE` | `f5b745ef98087f531e719ee8ca6a96809444573ecc7173c6fa68eaad39b3cc3f` |

---

# 5 · Compuerta para publicar `v1.1.0`

El estado documental queda **listo para el siguiente paso**, no etiquetado todavía. La operación de release debe ejecutarse por separado y en este orden:

1. actualizar `CITATION.cff` y `.zenodo.json` a `1.1.0` con la fecha real de publicación;
2. comprobar nuevamente JSON, CFF, rutas, enlaces y ausencia de regresiones;
3. crear el commit de release y fijar sobre él el tag `v1.1.0`;
4. crear la release de GitHub;
5. depositar una nueva versión en Zenodo, sin sustituir ni alterar el registro histórico de `v1.0.0`;
6. verificar el DOI y los archivos efectivamente publicados antes de anunciar el cierre.

> [!CAUTION]
> El nombre de versión debe materializarse como metadatos concordantes, commit y tag; no como un simple cambio cosmético en el README.

---

# 6 · Veredicto final

**Apto para pasar al commit de release `v1.1.0`, condicionado únicamente a la actualización coordinada y verificable de los metadatos de versión.**

La integración conserva exactamente once artículos, mantiene la ruta editorial acordada, publica R6 en ambos idiomas, hace visible la licencia, no modifica R5 ni `v1.0.0` y no atribuye al DOI histórico una edición que todavía no representa.

> **STOP. No seguir ampliando el canon.**

El commit que contiene esta acta constituye su referencia de publicación en Git; por evitar autorreferencia circular, su SHA no se inscribe dentro del propio archivo y debe leerse en el historial del repositorio.
