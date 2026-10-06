<!-- ELUCENIA technical documentation · ipi-linfoma · es · no clinical/professional/rights approval -->

# IPI (índice pronóstico internacional)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/ipi-linfoma)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Edad \> 60 años

`idade`

### LDH sérica por encima del límite superior normal

`ldh`

### ECOG ≥ 2

`ecog`

### Estadio de Ann Arbor III o IV

`estadio`

### Más de 1 localización extraganglionar

`extranodal`

## Edición del método

International Prognostic Index 1993: 5 factores, 0–5; sin NCCN-IPI ni R-IPI

## Fórmula documentada

Un punto por factor: edad \> 60 años · LDH elevada · ECOG ≥ 2 · estadio III o IV · más de 1 sitio extranodal. Máximo: 5.

## Límites y población

Índice pronóstico clásico para adultos con linfoma no Hodgkin agresivo, desarrollado antes del tratamiento en cohortes históricas con doxorrubicina. Distinga IPI clásico, ajustado por edad, R-IPI y NCCN-IPI. Las probabilidades históricas no demuestran calibración para todos los subtipos ni tratamientos actuales.

## Referencias

- [The International Non-Hodgkin's Lymphoma Prognostic Factors Project. A predictive model for aggressive non-Hodgkin's lymphoma. N Engl J Med, 1993.](https://doi.org/10.1056/NEJM199309303291402)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Riesgo bajo: supervivencia a 5 años del 73%

Remisión completa en 87% (era pre-rituximab).


### 2

Riesgo alto-intermedio: supervivencia a 5 años del 43%

Remisión completa en 55%.


### 3

Riesgo bajo-intermedio: supervivencia a 5 años del 51%

Remisión completa en 67%.


### 4

Riesgo alto: supervivencia a 5 años del 26%

Remisión completa en 44%.

