---
title: "IXPathExpression.Evaluate"
second_title: "Aspose.HTML für Java API-Referenz"
description: "IXPathExpression-Methode. Bewertet diesen XPath-Ausdruck und gibt ein Ergebnis zurück."
type: docs

url: /de/java/com.aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Evaluert diesen XPath-Ausdruck und gibt ein Ergebnis zurück.

```java
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| contextNode | Node | Der `context` ist der Kontextknoten für die Auswertung dieses XPath-Ausdrucks. Wenn der [`IXPathEvaluator`](../../ixpathevaluator/) durch Casten des [`Document`](../../../com.aspose.html.dom/document/) erhalten wurde, muss dieser dem selben Dokument gehören und muss ein [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/) oder XPathNamespace-Knoten sein. Wenn der Kontextknoten ein [`Text`](../../../com.aspose.html.dom/text/) oder ein [`CDATASection`](../../../com.aspose.html.dom/cdatasection/) ist, wird der Kontext als der gesamte logische Textknoten interpretiert, wie er von XPath gesehen wird, es sei denn, der Knoten ist leer, dann kann er nicht als XPath-Kontext dienen. |
| type | XPathResultType | Wenn ein bestimmter `type` angegeben ist, wird das Ergebnis so umgewandelt, dass es den angegebenen Typ zurückgibt, wobei XPath-Konvertierungen verwendet werden, und schlägt fehl, wenn die gewünschte Umwandlung nicht möglich ist. Dies muss einer der Werte von [`XPathResultType`](../../xpathresulttype/) sein. |
| result | Object | Das `result` gibt ein bestimmtes Ergebnisobjekt an, das von dieser Methode wiederverwendet und zurückgegeben werden kann. Wenn es als `null` angegeben wird oder die Implementierung das angegebene Ergebnis nicht wiederverwendet, wird ein neues Ergebnisobjekt erstellt und zurückgegeben. Für XPath‑1.0‑Ergebnisse wird dieses Objekt vom Typ [`IXPathResult`](../../ixpathresult/) sein. |

### Rückgabewert

Das Ergebnis der Auswertung des XPath-Ausdrucks. Für XPath‑1.0‑Ergebnisse wird dieses Objekt vom Typ [`IXPathResult`](../../ixpathresult/) sein.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: Ausgelöst, wenn das Ergebnis nicht in den angegebenen Typ konvertiert werden kann. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: Der Knoten stammt aus einem Dokument, das von dem [`IXPathEvaluator`](../../ixpathevaluator/) nicht unterstützt wird, der diesen [`IXPathExpression`](../) erstellt hat. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Der Knoten ist kein zulässiger Typ für einen XPath-Kontextknoten oder der Anforderungstyp ist von diesem [`IXPathExpression`](../) nicht erlaubt. |

### Siehe auch

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
