<!-- ELUCENIA technical documentation · ipi-linfoma · de · no clinical/professional/rights approval -->

# IPI (Internationaler Prognoseindex)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/ipi-linfoma)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Alter \> 60 Jahre

`idade`

### Serum-LDH oberhalb der oberen Normgrenze

`ldh`

### ECOG ≥ 2

`ecog`

### Ann-Arbor-Stadium III oder IV

`estadio`

### Mehr als 1 extranodaler Befall

`extranodal`

## Fassung der Methode

International Prognostic Index 1993: 5 Faktoren, 0–5; kein NCCN-IPI oder R-IPI

## Dokumentierte Formel

Ein Punkt je Faktor: Alter \> 60 Jahre · erhöhte LDH · ECOG ≥ 2 · Stadium III oder IV · mehr als 1 extranodale Lokalisation. Maximum: 5.

## Grenzen und Population

Klassischer Prognoseindex für Erwachsene mit aggressivem Non-Hodgkin-Lymphom, vor Behandlungsbeginn in historischen Doxorubicin-Kohorten entwickelt. Unterscheiden Sie klassischen IPI, altersangepassten IPI, R-IPI und NCCN-IPI. Historische Wahrscheinlichkeiten belegen keine Kalibrierung für alle Subtypen oder heutigen Behandlungen.

## Referenzen

- [The International Non-Hodgkin's Lymphoma Prognostic Factors Project. A predictive model for aggressive non-Hodgkin's lymphoma. N Engl J Med, 1993.](https://doi.org/10.1056/NEJM199309303291402)

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
