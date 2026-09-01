---
title: "HTMLTableSectionElement.DeleteRow"
second_title: "Aspose.HTML für Java API-Referenz"
description: "HTMLTableSectionElement-Methode. Löscht eine Zeile aus diesem Abschnitt"
type: docs

url: /de/java/com.aspose.html/htmltablesectionelement/deleterow/
---
## HTMLTableSectionElement.DeleteRow method

Lösche eine Zeile aus diesem Abschnitt.

```java
public void DeleteRow(int index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Der Index der zu löschenden Zeile oder -1, um die letzte Zeile zu löschen. Dieser Index beginnt bei 0 und bezieht sich nur auf die Zeilen, die in diesem Abschnitt enthalten sind, nicht auf alle Zeilen der Tabelle. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Wird ausgelöst, wenn der angegebene Index größer als oder gleich der Zeilenanzahl ist oder wenn der Index eine negative Zahl ist, die nicht -1 ist. @version DOM Level 2 |

### Siehe auch

* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
