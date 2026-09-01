---
title: "HTMLTableSectionElement.InsertRow"
second_title: "Aspose.HTML für Java API-Referenz"
description: "HTMLTableSectionElement-Methode. Fügt eine Zeile in diesen Abschnitt ein. Die neue Zeile wird unmittelbar vor der aktuellen index‑ten Zeile in diesem Abschnitt eingefügt. Wenn index -1 ist oder gleich der Anzahl der Zeilen in diesem Abschnitt, wird die neue Zeile angehängt."
type: docs

url: /de/java/com.aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

Füge eine Zeile in diesen Abschnitt ein. Die neue Zeile wird sofort vor der aktuellen `index`‑ten Zeile in diesem Abschnitt eingefügt. Wenn `index` -1 ist oder gleich der Anzahl der Zeilen in diesem Abschnitt, wird die neue Zeile angehängt.

```java
public HTMLElement InsertRow(int index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Die Zeilennummer, an der eine neue Zeile eingefügt werden soll. Dieser Index beginnt bei 0 und bezieht sich nur auf die Zeilen, die in diesem Abschnitt enthalten sind, nicht auf alle Zeilen der Tabelle. |

### Rückgabewert

Die neu erstellte Zeile.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Wird ausgelöst, wenn der angegebene Index größer ist als die Anzahl der Zeilen oder wenn der Index eine negative Zahl außer -1 ist. @version DOM Level 2 |

### Siehe auch

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
