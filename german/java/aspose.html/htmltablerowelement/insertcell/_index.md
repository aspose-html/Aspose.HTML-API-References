---
title: "HTMLTableRowElement.InsertCell"
second_title: "Aspose.HTML für Java API-Referenz"
description: "HTMLTableRowElement‑Methode. Fügt dieser Zeile eine leere TD‑Zelle ein. Wenn der Index -1 ist oder der Anzahl der Zellen entspricht, wird die neue Zelle angehängt"
type: docs

url: /de/java/com.aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

Füge eine leere `TD`‑Zelle in diese Zeile ein. Wenn `index` -1 ist oder der Anzahl der Zellen entspricht, wird die neue Zelle angehängt.

```java
public HTMLElement InsertCell(int index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Der Platz, an dem die Zelle eingefügt wird, beginnend bei 0. |

### Rückgabewert

Die neu erstellte Zelle.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Wird ausgelöst, wenn der angegebene `index` größer als die Anzahl der Zellen ist oder wenn der Index eine negative Zahl außer -1 ist. @version DOM Level 2 |

### Siehe auch

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableRowElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
