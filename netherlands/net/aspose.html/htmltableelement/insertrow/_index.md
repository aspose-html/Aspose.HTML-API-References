---
title: HTMLTableElement.InsertRow
second_title: Aspose.HTML voor .NET API-referentie
description: HTMLTableElement methode. Voeg een nieuwe lege rij in de tabel in. De nieuwe rij wordt ingevoegd direct voor en in dezelfde sectie als de huidige inhoudsopgave e rij in de tabel. Alsinhoudsopgave is 1 of gelijk aan het aantal rijen wordt de nieuwe rij toegevoegd. Bovendien wanneer de tabel leeg is wordt de rij ingevoegd in eenT LICHAAM die is gemaakt en in de tabel is ingevoegd. Een tabelrij kan niet leeg zijn volgens HTML4.01 .
type: docs
weight: 220
url: /nl/net/aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

Voeg een nieuwe lege rij in de tabel in. De nieuwe rij wordt ingevoegd direct voor en in dezelfde sectie als de huidige `inhoudsopgave` e rij in de tabel. Als`inhoudsopgave` is -1 of gelijk aan het aantal rijen, wordt de nieuwe rij toegevoegd. Bovendien, wanneer de tabel leeg is, wordt de rij ingevoegd in een`T LICHAAM` die is gemaakt en in de tabel is ingevoegd. Een tabelrij kan niet leeg zijn volgens [[HTML4.01](http://www.w3.org/TR/1999/REC-html401-19991224) ].

```csharp
public Node InsertRow(int index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | Het rijnummer waar een nieuwe rij moet worden ingevoegd. Deze index begint bij 0 en is relatief ten opzichte van de logische volgorde (niet document volgorde) van alle rijen in de tabel. |

### Winstwaarde

De nieuw aangemaakte rij.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: wordt verhoogd als de opgegeven index groter is dan het aantal rijen of als de index een negatief getal is anders dan -1. @version DOM Level 2 |

### Zie ook

* class [Node](../../../aspose.html.dom/node/)
* class [HTMLTableElement](../)
* naamruimte [Aspose.Html](../../htmltableelement/)
* montage [Aspose.HTML](../../../)


