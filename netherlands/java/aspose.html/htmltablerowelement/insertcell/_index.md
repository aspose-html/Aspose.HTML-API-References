---
title: "HTMLTableRowElement.InsertCell"
second_title: "Aspose.HTML voor Java API-referentie"
description: "HTMLTableRowElement-methode. Voeg een lege TD-cel toe aan deze rij. Als index -1 is of gelijk aan het aantal cellen, wordt de nieuwe cel toegevoegd."
type: docs

url: /nl/java/com.aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

Voeg een lege `TD`-cel toe aan deze rij. Als `index` -1 is of gelijk aan het aantal cellen, wordt de nieuwe cel toegevoegd.

```java
public HTMLElement InsertCell(int index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | De plaats om de cel in te voegen, beginnend bij 0. |

### Retourwaarde

De nieuw aangemaakte cel.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Opgetreden als de opgegeven `index` groter is dan het aantal cellen of als de index een negatief getal is anders dan -1. @version DOM Level 2 |

### Zie ook

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableRowElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
