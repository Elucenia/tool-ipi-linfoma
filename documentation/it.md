<!-- ELUCENIA technical documentation · ipi-linfoma · it · no clinical/professional/rights approval -->

# IPI (indice prognostico internazionale)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/ipi-linfoma)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Età \> 60 anni

`idade`

### LDH sierica sopra il limite superiore normale

`ldh`

### ECOG ≥ 2

`ecog`

### Stadio di Ann Arbor III o IV

`estadio`

### Più di 1 sede extranodale

`extranodal`

## Edizione del metodo

International Prognostic Index 1993: 5 fattori, 0–5; non NCCN-IPI né R-IPI

## Formula documentata

Un punto per fattore: età \> 60 anni · LDH elevata · ECOG ≥ 2 · stadio III o IV · più di 1 sede extranodale. Massimo: 5.

## Limiti e popolazione

Indice prognostico classico per adulti con linfoma non Hodgkin aggressivo, sviluppato prima del trattamento in coorti storiche con doxorubicina. Distinguere IPI classico, aggiustato per età, R-IPI e NCCN-IPI. Le probabilità storiche non dimostrano una calibrazione per tutti i sottotipi o i trattamenti attuali.

## Riferimenti

- [The International Non-Hodgkin's Lymphoma Prognostic Factors Project. A predictive model for aggressive non-Hodgkin's lymphoma. N Engl J Med, 1993.](https://doi.org/10.1056/NEJM199309303291402)

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

Rischio basso: sopravvivenza a 5 anni del 73%

Remissione completa nell'87% (era pre-rituximab).


### 2

Rischio intermedio-alto: sopravvivenza a 5 anni del 43%

Remissione completa nel 55%.


### 3

Rischio intermedio-basso: sopravvivenza a 5 anni del 51%

Remissione completa nel 67%.


### 4

Rischio alto: sopravvivenza a 5 anni del 26%

Remissione completa nel 44%.

