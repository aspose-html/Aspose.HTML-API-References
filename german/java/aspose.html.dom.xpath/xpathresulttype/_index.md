---
title: "XPathResultType‑Enum"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.xpath.XPathResultType‑Enum. Ein unsigned short, das angibt, welchen Ergebnis‑Typ dies darstellt. Wird ein bestimmter Typ angegeben, wird das Ergebnis als entsprechender Typ zurückgegeben, wobei bei Bedarf und Möglichkeit XPath‑Typkonvertierungen verwendet werden."
type: docs

url: /de/java/com.aspose.html.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

Ein unsigned short, das angibt, um welchen Ergebnis­typ es sich handelt. Wenn ein bestimmter `type` angegeben ist, wird das Ergebnis als der entsprechende Typ zurückgegeben, wobei bei Bedarf und Möglichkeit XPath‑Typumwandlungen verwendet werden.

```java
public enum XPathResultType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Any | `0` | Dieser Code stellt keinen spezifischen Typ dar. Die Auswertung eines XPath‑Ausdrucks liefert diesen Typ niemals. Wird dieser Typ angefordert, gibt die Auswertung den natürlich aus dem Ausdruck resultierenden Typ zurück. Wenn das natürliche Ergebnis ein Knotensatz ist, wenn der Typ `Any` angefordert wurde, ist `UnorderedNodeIterator` stets der resultierende Typ. Jede andere Darstellung eines Knotensatzes muss explizit angefordert werden. |
| Number | `1` | Das Ergebnis ist eine Zahl, wie in [XPath 1.0] definiert. Dokumentänderungen machen die Zahl nicht ungültig, können jedoch dazu führen, dass eine erneute Auswertung nicht dieselbe Zahl liefert. |
| String | `2` | Das Ergebnis ist ein String, wie in [XPath 1.0] definiert. Dokumentänderungen machen den String nicht ungültig, können jedoch dazu führen, dass der String nicht mehr dem aktuellen Dokument entspricht. |
| Boolean | `3` | Das Ergebnis ist ein Boolean, wie in [XPath 1.0] definiert. Dokumentänderungen machen den Boolean nicht ungültig, können jedoch dazu führen, dass eine erneute Auswertung nicht denselben Boolean liefert. |
| UnorderedNodeIterator | `4` | Das Ergebnis ist ein Knotensatz, wie in [XPath 1.0] definiert, der iterativ abgerufen wird und möglicherweise keine bestimmte Reihenfolge der Knoten liefert. Dokumentänderungen machen die Iteration ungültig. Dies ist der Standardtyp, der zurückgegeben wird, wenn das Ergebnis ein Knotensatz ist und der Typ `Any` angefordert wird. |
| OrderedNodeIterator | `5` | Das Ergebnis ist ein Knotensatz, wie in [XPath 1.0] definiert, der iterativ abgerufen wird und dokumentgeordneten Knoten liefert. Dokumentänderungen machen die Iteration ungültig. |
| UnorderedNodeSnapshot | `6` | Das Ergebnis ist ein Knotensatz, wie in [XPath 1.0] definiert, der als Snapshot‑Liste von Knoten abgerufen wird, die möglicherweise nicht in einer bestimmten Reihenfolge liegen. Dokumentänderungen machen den Snapshot nicht ungültig, können jedoch dazu führen, dass eine erneute Auswertung nicht denselben Snapshot liefert und die Knoten im Snapshot geändert, verschoben oder aus dem Dokument entfernt wurden. |
| OrderedNodeSnapshot | `7` | Das Ergebnis ist ein Knotensatz, wie in [XPath 1.0] definiert, der als Snapshot‑Liste von Knoten abgerufen wird, die in der ursprünglichen Dokumentenreihenfolge stehen. Dokumentänderungen machen den Snapshot nicht ungültig, können jedoch dazu führen, dass eine erneute Auswertung nicht denselben Snapshot liefert und die Knoten im Snapshot geändert, verschoben oder aus dem Dokument entfernt wurden. |
| AnyUnorderedNode | `8` | Das Ergebnis ist ein Knotensatz, wie in [XPath 1.0] definiert, und wird als einzelner Knoten abgerufen, der `null` sein kann, wenn der Knotensatz leer ist. Dokumentänderungen machen den Knoten nicht ungültig, können jedoch dazu führen, dass der Ergebnis‑Knoten nicht mehr dem aktuellen Dokument entspricht. Dies ist ein Komfort, der Optimierungen ermöglicht, da die Implementierung stoppen kann, sobald irgendein Knoten im Ergebnis‑Satz gefunden wurde. Gibt es mehr als einen Knoten im tatsächlichen Ergebnis, ist der zurückgegebene einzelne Knoten möglicherweise nicht der erste in Dokumentenreihenfolge. |
| FirstOrderedNode | `9` | Das Ergebnis ist ein Knotensatz, wie in [XPath 1.0] definiert, und wird als einzelner Knoten abgerufen, der `null` sein kann, wenn der Knotensatz leer ist. Dokumentänderungen machen den Knoten nicht ungültig, können jedoch dazu führen, dass der Ergebnis‑Knoten nicht mehr dem aktuellen Dokument entspricht. Dies ist ein Komfort, der Optimierungen ermöglicht, da die Implementierung stoppen kann, sobald der erste Knoten in Dokumentenreihenfolge des Ergebnis‑Satzes gefunden wurde. Gibt es mehr als einen Knoten im tatsächlichen Ergebnis, ist der zurückgegebene einzelne Knoten der erste in Dokumentenreihenfolge. |

### Siehe auch

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
