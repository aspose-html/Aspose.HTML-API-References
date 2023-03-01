---
title: HTMLTableElement.InsertRow
second_title: Aspose.HTML für .NET-API-Referenz
description: HTMLTableElement methode. Fügen Sie eine neue leere Zeile in die Tabelle ein. Die neue Zeile wird unmittelbar vor und im selben Abschnitt wie die aktuelle eingefügt.Index Zeile in der Tabelle. WennIndex 1 oder gleich der Anzahl der Zeilen ist wird die neue Zeile angehängt. Außerdem wird  wenn die Tabelle leer ist die Zeile in a eingefügtKÖRPER  die erstellt und in die Tabelle eingefügt wird. Eine Tabellenzeile kann nicht leer sein gemäß HTML4.01 .
type: docs
weight: 220
url: /de/net/aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

Fügen Sie eine neue leere Zeile in die Tabelle ein. Die neue Zeile wird unmittelbar vor und im selben Abschnitt wie die aktuelle eingefügt.`Index` Zeile in der Tabelle. Wenn`Index` -1 oder gleich der Anzahl der Zeilen ist, wird die neue Zeile angehängt. Außerdem wird , wenn die Tabelle leer ist, die Zeile in a eingefügt`KÖRPER` , die erstellt und in die Tabelle eingefügt wird. Eine Tabellenzeile kann nicht leer sein gemäß [[HTML4.01](http://www.w3.org/TR/1999/REC-html401-19991224) ].

```csharp
public Node InsertRow(int index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Die Zeilennummer, wo eine neue Zeile eingefügt werden soll. Dieser Index beginnt bei 0 und ist relativ zur logischen Reihenfolge (nicht zur Dokument- -Reihenfolge) aller in der Tabelle enthaltenen Zeilen. |

### Rückgabewert

Die neu erstellte Zeile.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Wird ausgelöst, wenn der angegebene Index größer als die Anzahl von Zeilen ist oder wenn der Index eine negative Zahl ungleich -1 ist. @Version DOM Level 2 |

### Siehe auch

* class [Node](../../../aspose.html.dom/node/)
* class [HTMLTableElement](../)
* namensraum [Aspose.Html](../../htmltableelement/)
* Montage [Aspose.HTML](../../../)


