<!-- ELUCENIA technical documentation · ipi-linfoma · fr · no clinical/professional/rights approval -->

# IPI (indice pronostique international)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/ipi-linfoma)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Âge \> 60 ans

`idade`

### LDH sérique supérieure à la limite normale

`ldh`

### ECOG ≥ 2

`ecog`

### Stade d’Ann Arbor III ou IV

`estadio`

### Plus de 1 site extraganglionnaire

`extranodal`

## Édition de la méthode

International Prognostic Index 1993 : 5 facteurs, 0–5 ; sans NCCN-IPI ni R-IPI

## Formule documentée

Un point par facteur : âge \> 60 ans · LDH élevée · ECOG ≥ 2 · stade III ou IV · plus de 1 site extranodal. Maximum : 5.

## Limites et population

Indice pronostique classique pour l’adulte atteint de lymphome non hodgkinien agressif, développé avant traitement dans des cohortes historiques recevant de la doxorubicine. Distinguez l’IPI classique, l’IPI ajusté à l’âge, le R-IPI et le NCCN-IPI. Les probabilités historiques ne démontrent pas un calibrage pour tous les sous-types ou traitements actuels.

## Références

- [The International Non-Hodgkin's Lymphoma Prognostic Factors Project. A predictive model for aggressive non-Hodgkin's lymphoma. N Engl J Med, 1993.](https://doi.org/10.1056/NEJM199309303291402)

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
