<!-- ELUCENIA technical documentation · gad-7 · de · no clinical/professional/rights approval -->

# GAD-7-Skala

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/gad-7)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Wie häufig haben Sie sich in den letzten 2 Wochen durch folgende Probleme beeinträchtigt gefühlt? 1. Nervosität, Ängstlichkeit oder starke Anspannung

`q1`

- `0` — Nie
- `1` — An mehreren Tagen
- `2` — An mehr als der Hälfte der Tage
- `3` — Fast jeden Tag

### 2. Sorgen nicht stoppen oder kontrollieren können

`q2`

- `0` — Nie
- `1` — An mehreren Tagen
- `2` — An mehr als der Hälfte der Tage
- `3` — Fast jeden Tag

### 3. Sich über verschiedene Dinge viele Sorgen machen

`q3`

- `0` — Nie
- `1` — An mehreren Tagen
- `2` — An mehr als der Hälfte der Tage
- `3` — Fast jeden Tag

### 4. Schwierigkeiten, sich zu entspannen

`q4`

- `0` — Nie
- `1` — An mehreren Tagen
- `2` — An mehr als der Hälfte der Tage
- `3` — Fast jeden Tag

### 5. So unruhig sein, dass es schwerfällt, still zu sitzen

`q5`

- `0` — Nie
- `1` — An mehreren Tagen
- `2` — An mehr als der Hälfte der Tage
- `3` — Fast jeden Tag

### 6. Leicht verärgert oder gereizt sein

`q6`

- `0` — Nie
- `1` — An mehreren Tagen
- `2` — An mehr als der Hälfte der Tage
- `3` — Fast jeden Tag

### 7. Angst haben, als könnte etwas Schreckliches passieren

`q7`

- `0` — Nie
- `1` — An mehreren Tagen
- `2` — An mehr als der Hälfte der Tage
- `3` — Fast jeden Tag

## Fassung der Methode

GAD-7/Spitzer 2006: 7 Items 0–3, Gesamt 0–21; Grenzen 5/10/15; brasilianisches Portugiesisch Moreno 2016

## Dokumentierte Formel

Je Item 0 (überhaupt nicht) bis 3 (beinahe täglich). Gesamt 0 bis 21. Schweregradgrenzen: 5, 10, 15. Für generalisierte Angst ergab ≥10 im Original Sensitivität 89% und Spezifität 82%.

## Grenzen und Population

Screening und Intensitätsmessung generalisierter Angstsymptome bei Erwachsenen. Ein wahrscheinlicher Befund erfordert diagnostische Beurteilung. Primärversorgungsstudien und die brasilianische Bevölkerungsstichprobe validieren nicht automatisch neue Populationen, die lokale Implementierung oder zusätzliche Übersetzungen.

## Referenzen

- [Spitzer RL et al. A brief measure for assessing generalized anxiety disorder: the GAD-7. Arch Intern Med, 2006.](https://doi.org/10.1001/archinte.166.10.1092)

- [Moreno AL et al. Factor structure, reliability, and item parameters of the Brazilian-Portuguese version of the GAD-7 questionnaire. Temas em Psicologia, 2016.](https://doi.org/10.9788/TP2016.1-25)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Minimale Angst (0 bis 4)

Screening-Instrument: stellt keine Diagnose.


### 2

Mäßige Angst (10 bis 14): positives Screening

Mit klinischem Interview bestätigen: Auch GAS, Panik, soziale Angst und PTBS erzielen hohe Werte.


### 3

Schwere Angst (15 bis 21): positives Screening

Mit klinischem Interview bestätigen und eine aktive Behandlung einleiten.

