---
title: HTMLTableRowElement.InsertCell
second_title: Aspose.HTML voor .NET API-referentie
description: HTMLTableRowElement methode. Voeg een leegTD cel in deze rij. Als inhoudsopgave is 1 of gelijk aan het aantal cellen wordt de nieuwe cel toegevoegd.
type: docs
weight: 100
url: /nl/net/aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

Voeg een leeg`TD` cel in deze rij. Als `inhoudsopgave` is -1 of gelijk aan het aantal cellen, wordt de nieuwe cel toegevoegd.

```csharp
public HTMLElement InsertCell(int index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | De plaats om de cel in te voegen, beginnend bij 0. |

### Winstwaarde

De nieuw aangemaakte cel.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Verhoogd indien opgegeven`inhoudsopgave` is groter dan het aantal cellen of als de index een negatief getal is anders dan dan -1. @versie DOM Level 2 |

### Zie ook

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableRowElement](../)
* naamruimte [Aspose.Html](../../htmltablerowelement/)
* montage [Aspose.HTML](../../../)


