[README-resumenes-de-articulos-actualizado.md](https://github.com/user-attachments/files/32078226/README-resumenes-de-articulos-actualizado.md)
# Resúmenes y concentrados

Esta carpeta contiene **capas de acceso no normativas** para los artículos extensos del repositorio. Su función es facilitar la lectura, la navegación y la discusión del corpus sin sustituir los textos canónicos.

Aquí conviven dos tipos de documentos: **resúmenes operativos por artículo** y **concentrados transversales del conjunto**.

| **Capa de acceso** | **Función** | **Alcance** | **Autoridad** |
|---|---|---|---|
| **Concentrado de los diez artículos** | Ofrecer una puerta de entrada al proyecto completo, mostrar su arquitectura, conexiones, límites y vacantes | Transversal: recorre los diez artículos en un orden de lectura editorial | **No normativo** |
| **Resumen operativo de un artículo** | Exponer el problema, tesis, mecanismos, límites y relación de un artículo concreto | Un artículo | **No normativo** |
| **Artículo canónico** | Contener la formulación íntegra vigente, con sus condiciones, antecedentes, reglas y vacantes | Texto fuente | **Prevalece ante cualquier discrepancia** |

## El Concentrado de los diez artículos

El Concentrado es una **síntesis transversal del corpus**. Puede leerse por sí solo como documento de orientación, pero no pretende contener todo lo necesario para auditar o reconstruir cada argumento.

Su propósito es permitir que una persona —o un sistema de IA— comprenda primero **qué intenta hacer el proyecto en conjunto** antes de entrar en los textos extensos.

La edición actual es:

**[Condiciones para la coexistencia · Concentrado de los diez artículos · Revisión 5](./Condiciones-para-la-coexistencia-Concentrado-diez-articulos-R5-con-tabla.md)**

El Concentrado:

- presenta el problema general y el recorrido de la propuesta;
- resume qué pregunta responde cada artículo;
- conserva mecanismos, límites y vacantes relevantes;
- muestra dependencias y posibilidades de adopción parcial entre artículos;
- utiliza un **orden de lectura editorial**, que no tiene por qué coincidir con la numeración histórica;
- declara el **commit fuente** que está resumiendo;
- enlaza a los artículos completos para continuar la lectura.

La numeración de los artículos conserva su historia de construcción. El orden del Concentrado puede ser distinto porque sigue una secuencia argumental: **relación → muestra → invitación → calibración → decisión → pacto → comunicación → ubicación ontológica y ecológica → organización social → economía**.

La ausencia de un argumento, objeción, antecedente o detalle operativo en el Concentrado **no implica que esté ausente del corpus ni que haya sido resuelto**.

## Resúmenes operativos por artículo

Los resúmenes individuales funcionan a otra escala. Cada uno debe permitir localizar rápidamente el filo de un artículo concreto sin tener que recorrer de inmediato su versión completa.

En lo posible, cada resumen debe identificar:

- problema y pregunta central;
- propuesta o tesis;
- mecanismos principales;
- límites y condiciones;
- vacantes abiertas;
- relación con otros artículos;
- versión o commit canónico que resume;
- enlace al artículo completo.

Un resumen operativo puede ser más breve y específico que el Concentrado. El Concentrado **conecta el sistema**; el resumen individual **abre una pieza**.

## Regla de precedencia

Los documentos de esta carpeta facilitan navegación y exponen principios, mecanismos y límites centrales, pero pueden omitir detalle técnico, antecedentes, auditorías o condiciones específicas. No sustituyen el texto canónico ni crean derechos, obligaciones o excepciones nuevas.

> **Ante cualquier diferencia entre un resumen o concentrado y el artículo correspondiente, prevalece el artículo canónico.**

El Concentrado tampoco sustituye a las auditorías. Una afirmación resumida puede entenderse aquí; su genealogía, objeciones, adjudicaciones y cambios deben consultarse en los artículos y expedientes correspondientes.

## Versionado y actualización

Cada resumen o concentrado debe hacer explícito **qué estado del corpus representa**. Cuando cambie materialmente un artículo canónico:

- su resumen operativo debe actualizarse o quedar identificado como resumen de una versión histórica;
- el Concentrado debe revisarse cuando el cambio afecte lo que explica del conjunto;
- no debe modificarse retroactivamente una edición histórica para hacerla parecer equivalente al canon posterior.

Un resumen viejo puede conservar valor documental si deja claro qué versión representa. **Actualizar no significa borrar la genealogía.**

## Convención de nombres

Para los resúmenes individuales se recomienda un archivo por artículo, por ejemplo:

- `01-...-resumen-operativo.md`
- `01.5-...-resumen-operativo.md`
- `07-pacto-de-agencia-resumen-operativo.md`

Los concentrados transversales pueden usar un nombre descriptivo propio, siempre que indiquen claramente su revisión o estado editorial.

---

**Regla corta de esta carpeta:** el canon conserva el argumento completo; los resúmenes conservan el filo; el Concentrado muestra cómo las piezas se conectan.
