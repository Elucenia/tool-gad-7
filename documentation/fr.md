<!-- ELUCENIA technical documentation · gad-7 · fr · no clinical/professional/rights approval -->

# Échelle GAD-7

[conditions, sources et autorisations](https://elucenia.org/fr/outils/gad-7)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Au cours des 2 dernières semaines, à quelle fréquence avez-vous été gêné par les problèmes suivants ? 1. Vous sentir nerveux, anxieux ou très tendu

`q1`

- `0` — Jamais
- `1` — Plusieurs jours
- `2` — Plus de la moitié des jours
- `3` — Presque tous les jours

### 2. Ne pas parvenir à arrêter ou à contrôler les inquiétudes

`q2`

- `0` — Jamais
- `1` — Plusieurs jours
- `2` — Plus de la moitié des jours
- `3` — Presque tous les jours

### 3. S’inquiéter beaucoup de différentes choses

`q3`

- `0` — Jamais
- `1` — Plusieurs jours
- `2` — Plus de la moitié des jours
- `3` — Presque tous les jours

### 4. Difficulté à se détendre

`q4`

- `0` — Jamais
- `1` — Plusieurs jours
- `2` — Plus de la moitié des jours
- `3` — Presque tous les jours

### 5. Être si agité qu’il est difficile de rester assis

`q5`

- `0` — Jamais
- `1` — Plusieurs jours
- `2` — Plus de la moitié des jours
- `3` — Presque tous les jours

### 6. Être facilement contrarié ou irritable

`q6`

- `0` — Jamais
- `1` — Plusieurs jours
- `2` — Plus de la moitié des jours
- `3` — Presque tous les jours

### 7. Avoir peur comme si quelque chose d’horrible allait arriver

`q7`

- `0` — Jamais
- `1` — Plusieurs jours
- `2` — Plus de la moitié des jours
- `3` — Presque tous les jours

## Édition de la méthode

GAD-7/Spitzer 2006 : 7 items 0–3, total 0–21 ; seuils 5/10/15 ; portugais brésilien Moreno 2016

## Formule documentée

Chaque item 0 (jamais) à 3 (presque chaque jour). Total 0 à 21. Seuils de sévérité : 5, 10, 15. Pour l’anxiété généralisée, ≥10 avait sensibilité 89% et spécificité 82% dans l’étude initiale.

## Limites et population

Dépistage et mesure de l’intensité des symptômes d’anxiété généralisée chez l’adulte. Un résultat probable nécessite une évaluation diagnostique. Les études en soins primaires et l’échantillon communautaire brésilien ne valident pas automatiquement de nouvelles populations, l’implémentation locale ou des traductions supplémentaires.

## Références

- [Spitzer RL et al. A brief measure for assessing generalized anxiety disorder: the GAD-7. Arch Intern Med, 2006.](https://doi.org/10.1001/archinte.166.10.1092)

- [Moreno AL et al. Factor structure, reliability, and item parameters of the Brazilian-Portuguese version of the GAD-7 questionnaire. Temas em Psicologia, 2016.](https://doi.org/10.9788/TP2016.1-25)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
