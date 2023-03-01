---
title: HTMLTableElement.DeleteRow
second_title: Aspose.HTML für .NET-API-Referenz
description: HTMLTableElement methode. Löschen einer Tabellenzeile.
type: docs
weight: 190
url: /de/net/aspose.html/htmltableelement/deleterow/
---
## HTMLTableElement.DeleteRow method

Löschen einer Tabellenzeile.

```csharp
public void DeleteRow(int index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Der Index der zu löschenden Zeile. Dieser Index beginnt bei 0 und ist relativ zur logischen Reihenfolge (nicht zur Dokumentenreihenfolge) von aller in der Tabelle enthaltenen Zeilen. Wenn der Index -1 ist, wird die letzte Zeile in der Tabelle gelöscht. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Wird ausgelöst, wenn der angegebene Index größer oder gleich der Anzahl der Zeilen ist oder wenn der Index eine negative Zahl anders als -1 ist. @Version DOM Level 2 |

### Siehe auch

* class [HTMLTableElement](../)
* namensraum [Aspose.Html](../../htmltableelement/)
* Montage [Aspose.HTML](../../../)


