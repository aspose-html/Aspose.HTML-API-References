---
title: "HTMLTableElement.InsertRow"
second_title: "Aspose.HTML voor Java API-referentie"
description: "HTMLTableElement methode. Voeg een nieuwe lege rij toe aan de tabel. De nieuwe rij wordt direct vóór en in dezelfde sectie als de huidige indexde rij in de tabel ingevoegd. Als index -1 is of gelijk aan het aantal rijen, wordt de nieuwe rij toegevoegd. Bovendien, wanneer de tabel leeg is, wordt de rij ingevoegd in een TBODY die wordt aangemaakt en in de tabel geplaatst. Een tabelrij mag niet leeg zijn volgens HTML 4.01"
type: docs

url: /nl/java/com.aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

Voeg een nieuwe lege rij toe aan de tabel. De nieuwe rij wordt direct vóór en in dezelfde sectie als de huidige `index`‑de rij in de tabel ingevoegd. Als `index` -1 is of gelijk aan het aantal rijen, wordt de nieuwe rij toegevoegd. Bovendien, wanneer de tabel leeg is, wordt de rij ingevoegd in een `TBODY` die wordt aangemaakt en in de tabel wordt geplaatst. Een tabelrij mag niet leeg zijn volgens [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)].

```java
public Node InsertRow(int index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | Het rijnummer waarop een nieuwe rij moet worden ingevoegd. Deze index begint bij 0 en is relatief ten opzichte van de logische volgorde (niet de documentvolgorde) van alle rijen die zich in de tabel bevinden. |

### Retourwaarde

De nieuw aangemaakte rij.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Opgetreden als de opgegeven index groter is dan het aantal rijen of als de index een negatief getal is anders dan -1. @version DOM Level 2 |

### Zie ook

* class [Node](../../../com.aspose.html.dom/node/)
* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
