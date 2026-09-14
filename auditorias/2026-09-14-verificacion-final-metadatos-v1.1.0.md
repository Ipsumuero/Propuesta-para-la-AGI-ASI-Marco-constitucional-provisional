---
titulo: "Verificación final de metadatos y árbol vivo para v1.1.0"
fecha: 2026-09-14
tipo: "auditoría documental de release y regresión"
estado: "candidato de release validado; tag y depósito pendientes"
---

# Verificación final de metadatos y árbol vivo para `v1.1.0`

| **Ficha de control** | **Resultado** |
|---|---|
| **Fecha** | 2026-09-14 · UTC |
| **Commit base** | [`b52d015ba7f04099a50d95766abe9d32a4f551f2`](https://github.com/Ipsumuero/Propuesta-para-la-AGI-ASI-Marco-constitucional-provisional/commit/b52d015ba7f04099a50d95766abe9d32a4f551f2) |
| **Método** | IEvA v0.3.1 · V1 documental, V3 reparación, V4 regresión, V5 horizontal y V6 externa localizada |
| **Auditor** | Sesión de OpenAI Codex; la interfaz identifica el entorno, sin atestación independiente y firmada de la identidad técnica exacta del modelo |
| **Autoridad editorial** | Jaime Alejandro Pérez Martínez / Ipsumuero |
| **Objeto** | Retiro de R5 del árbol vivo y coherencia de `CITATION.cff`/`.zenodo.json` para `1.1.0` |
| **Veredicto** | **CANDIDATO DE RELEASE VALIDADO; TAG Y DEPÓSITO TODAVÍA PENDIENTES** |

> [!IMPORTANT]
> R5 nunca fue un artículo canónico: era una capa de acceso histórica. Su retiro de `main` evita que el paquete `v1.1.0` contenga dos concentrados competidores, sin borrar su genealogía Git ni sus auditorías.

---

# 1 · Cobertura y límites

**LEÍDO COMPLETO:** [CITATION.cff](../CITATION.cff), [.zenodo.json](../.zenodo.json), índices afectados, Concentrado R6 en ambos idiomas y auditoría inmediatamente anterior.

**CONTROLADO POR INVENTARIO:** once artículos, ruta editorial, árbol de archivos, enlaces internos, hashes de R6 y licencia, diferencias contra el commit base.

**FUENTES EXTERNAS:**

- [esquema oficial CFF 1.2.0](https://github.com/citation-file-format/citation-file-format/blob/main/schema.json);
- [guía oficial del esquema CFF](https://github.com/citation-file-format/citation-file-format/blob/main/schema-guide.md);
- [documentación de Zenodo sobre `CITATION.cff`](https://help.zenodo.org/docs/github/describe-software/citation-file/);
- [documentación de Zenodo sobre `.zenodo.json`](https://help.zenodo.org/docs/github/describe-software/zenodo-json/).

**NO AUTORIZA:** afirmar que el depósito ya existe, asignar anticipadamente un DOI, certificar novedad o verdad doctrinal, ni sustituir la revisión humana de la ficha que Zenodo muestre antes de publicar.

---

# 2 · Cambios adjudicados

## 2.1 Retiro forward-only de R5

Se elimina del árbol vivo:

`resumenes-de-articulos/Condiciones-para-la-coexistencia-Concentrado-diez-articulos-R5.md`

La eliminación no reescribe ningún commit anterior. El archivo continúa recuperable en el [commit inmediatamente precedente](https://github.com/Ipsumuero/Propuesta-para-la-AGI-ASI-Marco-constitucional-provisional/blob/b52d015ba7f04099a50d95766abe9d32a4f551f2/resumenes-de-articulos/Condiciones-para-la-coexistencia-Concentrado-diez-articulos-R5.md), en su expediente editorial y en la genealogía del repositorio.

El índice vivo de resúmenes deja de enlazarlo. Las menciones históricas dentro de R6 y de auditorías permanecen porque explican procedencia; no presentan R5 como canon vigente.

## 2.2 `CITATION.cff`

- `version`: `1.1.0`;
- `date-released`: `2026-09-14`;
- resumen actualizado a once artículos, Artículo 0 y R6 bilingüe;
- palabras clave de transición epistémica, corroboración, preservación de evidencia e interlocución;
- `type`: de `article` a `dataset`.

El último cambio es una reparación de validez: CFF 1.2 sólo admite `software` o `dataset` como tipo raíz. Para este corpus documental, `dataset` es la opción válida más cercana. La clasificación archivística específica permanece en `.zenodo.json` como `publication` / `other`.

## 2.3 `.zenodo.json`

- `version`: `1.1.0`;
- `publication_date`: `2026-09-14`;
- creador, título, licencia, idioma y tipo archivístico conservados;
- descripción actualizada para declarar los once artículos, Artículo 0, R6, protocolo experimental, licencia y preservación genealógica de R5;
- palabras clave bilingües nuevas, sin duplicados.

Zenodo declara que, cuando existen ambos archivos, `.zenodo.json` controla los metadatos del archivado de una release de GitHub y `CITATION.cff` no se ingiere para ese depósito. Se mantienen ambos coherentes porque CFF sigue alimentando la sugerencia de cita de GitHub y otros consumidores.

---

# 3 · Hallazgos y reparación

| **ID** | **Severidad** | **Hallazgo** | **Resultado** |
|---|---:|---|---|
| M-01 | S2 | `CITATION.cff` usaba `type: article`, valor no permitido en la raíz del esquema CFF 1.2.0. | Reparado a `dataset` y validado contra el JSON Schema oficial. |
| M-02 | S1 | CFF y Zenodo todavía describían `1.0.0` y la fecha histórica del 2026-09-05. | Ambos actualizados coordinadamente a `1.1.0` y 2026-09-14. |
| M-03 | S1 | La descripción Zenodo aún presentaba la primera edición y no identificaba el corpus de once artículos ni R6. | Descripción y palabras clave actualizadas sin adjudicar un DOI inexistente. |
| M-04 | S1 | R5 seguía empaquetado en el árbol vivo pese a que R6 ya era la capa transversal vigente. | R5 retirado de `main`; archivo, autoría y trazabilidad preservados en Git. |

No apareció una modificación doctrinal nueva ni una regresión en los once artículos, los dos R6 o la licencia.

---

# 4 · Matriz de validación

| **Control** | **Resultado** |
|---|---|
| CFF parseado con rechazo de claves YAML duplicadas | Superado |
| CFF validado contra el JSON Schema oficial 1.2.0 | Superado |
| `.zenodo.json` y `repository-manifest.json` parseados con rechazo de claves JSON duplicadas | Superado |
| Título, autor, versión y fecha concordantes entre CFF y Zenodo | Superado |
| Licencias concordantes como `CC-BY-4.0` / `cc-by-4.0` | Superado |
| Zenodo conserva `upload_type: publication` y `publication_type: other` | Superado |
| R5 ausente del árbol vivo y recuperable en el commit base | Superado |
| Exactamente once artículos y once rutas únicas en el orden `2 → 3 → 4 → 0 → 6 → 5 → 7 → 8 → 9 → 1 → 1.5` | Superado |
| R6 español, R6 inglés y `LICENSE` idénticos al commit base | Superado |
| Todos los Markdown vivos parsean como GFM y sus enlaces internos resuelven | Superado |
| Sin colisiones de ruta por mayúsculas/minúsculas | Superado |
| `git diff --check` | Superado |

---

# 5 · Estado de publicación

Este commit queda preparado para convertirse en la referencia de `v1.1.0`. Todavía faltan dos actos externos y verificables:

1. crear el tag/release `v1.1.0` sobre el commit que contiene esta acta;
2. comprobar la ficha generada por Zenodo y publicar la nueva versión, conservando intactos `v1.0.0` y su DOI histórico.

> [!CAUTION]
> No debe copiarse el DOI de `v1.0.0` como identificador de `v1.1.0`. El DOI nuevo sólo puede registrarse después de que Zenodo lo reserve o lo asigne para esta versión.

**Veredicto final: apto para etiquetar como `v1.1.0`, sujeto a revisión visual de la ficha de Zenodo antes de publicar.**

> **STOP. No seguir ampliando el canon.**

El SHA del commit que publica esta acta debe leerse en el historial Git para evitar una referencia circular dentro del propio archivo.
