<!-- ELUCENIA technical documentation · gad-7 · pt-BR · no clinical/professional/rights approval -->

# Escala GAD-7

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/gad-7)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Durante as últimas 2 semanas, com que frequência você foi incomodado(a) pelos problemas abaixo? 1. Sentir-se nervoso(a), ansioso(a) ou muito tenso(a)

`q1`

- `0` — Nenhuma vez
- `1` — Vários dias
- `2` — Mais da metade dos dias
- `3` — Quase todos os dias

### 2. Não ser capaz de impedir ou de controlar as preocupações

`q2`

- `0` — Nenhuma vez
- `1` — Vários dias
- `2` — Mais da metade dos dias
- `3` — Quase todos os dias

### 3. Preocupar-se muito com diversas coisas

`q3`

- `0` — Nenhuma vez
- `1` — Vários dias
- `2` — Mais da metade dos dias
- `3` — Quase todos os dias

### 4. Dificuldade para relaxar

`q4`

- `0` — Nenhuma vez
- `1` — Vários dias
- `2` — Mais da metade dos dias
- `3` — Quase todos os dias

### 5. Ficar tão agitado(a) que se torna difícil permanecer sentado(a)

`q5`

- `0` — Nenhuma vez
- `1` — Vários dias
- `2` — Mais da metade dos dias
- `3` — Quase todos os dias

### 6. Ficar facilmente aborrecido(a) ou irritado(a)

`q6`

- `0` — Nenhuma vez
- `1` — Vários dias
- `2` — Mais da metade dos dias
- `3` — Quase todos os dias

### 7. Sentir medo como se algo horrível fosse acontecer

`q7`

- `0` — Nenhuma vez
- `1` — Vários dias
- `2` — Mais da metade dos dias
- `3` — Quase todos os dias

## Edição do método

GAD 7/Spitzer 2006:7 itens 0–3, total 0–21; cortes 5/10/15; PTMoreno 2016

## Fórmula documentada

Cada item vale de 0 (nenhuma vez) a 3 (quase todos os dias). Total: 0 a 21. Pontos de corte de intensidade: 5, 10 e 15. Para rastrear transtorno de ansiedade generalizada, o corte ≥ 10 teve sensibilidade de 89% e especificidade de 82% no estudo original.

## Limites e população

Rastreamento e medida de intensidade de sintomas de ansiedade generalizada em adultos. Um resultado provável requer avaliação diagnóstica. Os estudos de atenção primária e a amostra comunitária brasileira não validam automaticamente novas populações, a implementação local ou traduções adicionais.

## Referências

- [Spitzer RL et al. A brief measure for assessing generalized anxiety disorder: the GAD-7. Arch Intern Med, 2006.](https://doi.org/10.1001/archinte.166.10.1092)

- [Moreno AL et al. Factor structure, reliability, and item parameters of the Brazilian-Portuguese version of the GAD-7 questionnaire. Temas em Psicologia, 2016.](https://doi.org/10.9788/TP2016.1-25)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
