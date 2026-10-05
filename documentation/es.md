<!-- ELUCENIA technical documentation · gad-7 · es · no clinical/professional/rights approval -->

# Escala GAD-7

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/gad-7)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Durante las últimas 2 semanas, ¿con qué frecuencia le han molestado los siguientes problemas? 1. Sentirse nervioso, ansioso o muy tenso

`q1`

- `0` — Nunca
- `1` — Varios días
- `2` — Más de la mitad de los días
- `3` — Casi todos los días

### 2. No poder detener o controlar las preocupaciones

`q2`

- `0` — Nunca
- `1` — Varios días
- `2` — Más de la mitad de los días
- `3` — Casi todos los días

### 3. Preocuparse mucho por distintas cosas

`q3`

- `0` — Nunca
- `1` — Varios días
- `2` — Más de la mitad de los días
- `3` — Casi todos los días

### 4. Dificultad para relajarse

`q4`

- `0` — Nunca
- `1` — Varios días
- `2` — Más de la mitad de los días
- `3` — Casi todos los días

### 5. Estar tan inquieto que resulta difícil permanecer sentado

`q5`

- `0` — Nunca
- `1` — Varios días
- `2` — Más de la mitad de los días
- `3` — Casi todos los días

### 6. Molestarse o irritarse con facilidad

`q6`

- `0` — Nunca
- `1` — Varios días
- `2` — Más de la mitad de los días
- `3` — Casi todos los días

### 7. Sentir miedo como si fuera a ocurrir algo horrible

`q7`

- `0` — Nunca
- `1` — Varios días
- `2` — Más de la mitad de los días
- `3` — Casi todos los días

## Edición del método

GAD-7/Spitzer 2006: 7 ítems 0–3, total 0–21; cortes 5/10/15; portugués brasileño Moreno 2016

## Fórmula documentada

Cada ítem 0 (nunca) a 3 (casi todos los días). Total 0 a 21. Cortes de intensidad: 5, 10, 15. Para ansiedad generalizada, ≥10 tuvo sensibilidad 89% y especificidad 82% en el estudio original.

## Límites y población

Cribado y medición de la intensidad de síntomas de ansiedad generalizada en adultos. Un resultado probable requiere evaluación diagnóstica. Los estudios de atención primaria y la muestra comunitaria brasileña no validan automáticamente nuevas poblaciones, la implementación local ni traducciones adicionales.

## Referencias

- [Spitzer RL et al. A brief measure for assessing generalized anxiety disorder: the GAD-7. Arch Intern Med, 2006.](https://doi.org/10.1001/archinte.166.10.1092)

- [Moreno AL et al. Factor structure, reliability, and item parameters of the Brazilian-Portuguese version of the GAD-7 questionnaire. Temas em Psicologia, 2016.](https://doi.org/10.9788/TP2016.1-25)

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
