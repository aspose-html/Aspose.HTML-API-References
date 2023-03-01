---
title: HTMLTableSectionElement.InsertRow
second_title: Aspose.HTML voor .NET API-referentie
description: HTMLTableSectionElement methode. Voeg een rij in deze sectie in. De nieuwe rij wordt onmiddellijk vóór de huidige ingevoegdinhoudsopgave e rij in dit gedeelte. Als inhoudsopgave is 1 of gelijk is aan het aantal rijen in deze sectie  wordt de nieuwe rij toegevoegd.
type: docs
weight: 70
url: /nl/net/aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

Voeg een rij in deze sectie in. De nieuwe rij wordt onmiddellijk vóór de huidige ingevoegd`inhoudsopgave` e rij in dit gedeelte. Als `inhoudsopgave` is -1 of gelijk is aan het aantal rijen in deze sectie , wordt de nieuwe rij toegevoegd.

```csharp
public HTMLElement InsertRow(int index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | Het rijnummer waar een nieuwe rij moet worden ingevoegd. Deze index begint bij 0 en is alleen relatief ten opzichte van de rijen binnen deze sectie, niet alle rijen in de tabel. |

### Winstwaarde

De nieuw aangemaakte rij.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: verhoogd als de opgegeven index groter is dan het aantal rijen of als de index een negatief getal is anders dan -1. @version DOM Level 2 |

### Zie ook

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* naamruimte [Aspose.Html](../../htmltablesectionelement/)
* montage [Aspose.HTML](../../../)


