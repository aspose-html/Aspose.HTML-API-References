---
title: "HTMLTableElement.DeleteRow"
second_title: "Aspose.HTML für Java API-Referenz"
description: "HTMLTableElement-Methode. Löscht eine Tabellenzeile."
type: docs

url: /de/java/com.aspose.html/htmltableelement/deleterow/
---
## HTMLTableElement.DeleteRow method

Lösche eine Tabellenzeile.

```java
public void DeleteRow(int index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Der Index der zu löschenden Zeile. Dieser Index beginnt bei 0 und bezieht sich auf die logische Reihenfolge (nicht die Dokumentenreihenfolge) aller Zeilen, die in der Tabelle enthalten sind. Ist der Index -1, wird die letzte Zeile in der Tabelle gelöscht. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Wird ausgelöst, wenn der angegebene Index größer als oder gleich der Anzahl der Zeilen ist oder wenn der Index eine negative Zahl ist, die nicht -1 ist. @version DOM Level 2 |

### Siehe auch

* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
