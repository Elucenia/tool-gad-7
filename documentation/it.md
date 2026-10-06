<!-- ELUCENIA technical documentation · gad-7 · it · no clinical/professional/rights approval -->

# Scala GAD-7

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/gad-7)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Nelle ultime 2 settimane, con quale frequenza è stato disturbato dai seguenti problemi? 1. Sentirsi nervoso, ansioso o molto teso

`q1`

- `0` — Mai
- `1` — Diversi giorni
- `2` — Più della metà dei giorni
- `3` — Quasi ogni giorno

### 2. Non riuscire a interrompere o controllare le preoccupazioni

`q2`

- `0` — Mai
- `1` — Diversi giorni
- `2` — Più della metà dei giorni
- `3` — Quasi ogni giorno

### 3. Preoccuparsi molto per diverse cose

`q3`

- `0` — Mai
- `1` — Diversi giorni
- `2` — Più della metà dei giorni
- `3` — Quasi ogni giorno

### 4. Difficoltà a rilassarsi

`q4`

- `0` — Mai
- `1` — Diversi giorni
- `2` — Più della metà dei giorni
- `3` — Quasi ogni giorno

### 5. Essere così irrequieto da avere difficoltà a rimanere seduto

`q5`

- `0` — Mai
- `1` — Diversi giorni
- `2` — Più della metà dei giorni
- `3` — Quasi ogni giorno

### 6. Infastidirsi o irritarsi facilmente

`q6`

- `0` — Mai
- `1` — Diversi giorni
- `2` — Più della metà dei giorni
- `3` — Quasi ogni giorno

### 7. Provare paura come se potesse accadere qualcosa di terribile

`q7`

- `0` — Mai
- `1` — Diversi giorni
- `2` — Più della metà dei giorni
- `3` — Quasi ogni giorno

## Edizione del metodo

GAD-7/Spitzer 2006: 7 item 0–3, totale 0–21; soglie 5/10/15; portoghese brasiliano Moreno 2016

## Formula documentata

Ogni item 0 (mai) a 3 (quasi ogni giorno). Totale 0 a 21. Soglie di intensità: 5, 10, 15. Per ansia generalizzata, ≥10 aveva sensibilità 89% e specificità 82% nello studio originale.

## Limiti e popolazione

Screening e misurazione dell’intensità dei sintomi di ansia generalizzata negli adulti. Un risultato probabile richiede una valutazione diagnostica. Gli studi nell’assistenza primaria e il campione comunitario brasiliano non validano automaticamente nuove popolazioni, l’implementazione locale o traduzioni aggiuntive.

## Riferimenti

- [Spitzer RL et al. A brief measure for assessing generalized anxiety disorder: the GAD-7. Arch Intern Med, 2006.](https://doi.org/10.1001/archinte.166.10.1092)

- [Moreno AL et al. Factor structure, reliability, and item parameters of the Brazilian-Portuguese version of the GAD-7 questionnaire. Temas em Psicologia, 2016.](https://doi.org/10.9788/TP2016.1-25)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Ansia minima (0 a 4)

Strumento di screening: non pone diagnosi.


### 2

Ansia moderata (10 a 14): screening positivo

Confermare con intervista clinica: anche il DAG, il panico, l’ansia sociale e il PTSD ottengono punteggi elevati.


### 3

Ansia grave (15 a 21): screening positivo

Confermare con intervista clinica e iniziare un trattamento attivo.

