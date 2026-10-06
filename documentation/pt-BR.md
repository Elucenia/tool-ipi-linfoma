<!-- ELUCENIA technical documentation · ipi-linfoma · pt-BR · no clinical/professional/rights approval -->

# IPI (Índice Prognóstico Internacional)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/ipi-linfoma)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Idade \> 60 anos

`idade`

### LDH sérica acima do limite superior normal

`ldh`

### ECOG ≥ 2

`ecog`

### Estádio de Ann Arbor III ou IV

`estadio`

### Mais de 1 sítio extranodal

`extranodal`

## Edição do método

International Prognostic Index 1993:5 fatores 0–5; sem NCCNIPI ou RIPI

## Fórmula documentada

Um ponto para cada fator: idade \> 60 anos · LDH elevada · ECOG ≥ 2 · estádio III ou IV · mais de 1 sítio extranodal. Máximo: 5.

## Limites e população

Índice prognóstico clássico para adultos com linfoma não Hodgkin agressivo, desenvolvido antes do tratamento em coortes históricas com doxorrubicina. Distinga IPI clássico, ajustado à idade, R-IPI e NCCN-IPI. As probabilidades históricas não demonstram calibração para todos os subtipos ou tratamentos atuais.

## Referências

- [The International Non-Hodgkin's Lymphoma Prognostic Factors Project. A predictive model for aggressive non-Hodgkin's lymphoma. N Engl J Med, 1993.](https://doi.org/10.1056/NEJM199309303291402)

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

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Risco baixo: sobrevida em 5 anos de 73%

Remissão completa em 87% (era pré-rituximabe).


### 2

Risco alto-intermediário: sobrevida em 5 anos de 43%

Remissão completa em 55%.


### 3

Risco baixo-intermediário: sobrevida em 5 anos de 51%

Remissão completa em 67%.


### 4

Risco alto: sobrevida em 5 anos de 26%

Remissão completa em 44%.

