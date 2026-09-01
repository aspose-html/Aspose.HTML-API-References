---
title: "IXPathEvaluator.Evaluate"
second_title: "Aspose.HTML für Java API-Referenz"
description: "IXPathEvaluator-Methode. Bewertet einen XPath-Ausdruck-String und gibt, falls möglich, ein Ergebnis des angegebenen Typs zurück."
type: docs

url: /de/java/com.aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Evaluiert eine XPath‑Ausdruck‑Zeichenkette und gibt, falls möglich, ein Ergebnis des angegebenen Typs zurück.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Ausdruck | String | Der XPath-Ausdruck-String, der geparst und ausgewertet werden soll. |
| contextNode | Node | Der `context` ist der Kontextknoten für die Auswertung dieses XPath-Ausdrucks. Wenn der [`IXPathEvaluator`](../) durch Umwandlung des [`Document`](../../../com.aspose.html.dom/document/) erhalten wurde, muss dieser dem selben Dokument gehören und ein [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/) oder XPathNamespace-Knoten sein. Ist der Kontextknoten ein [`Text`](../../../com.aspose.html.dom/text/) oder ein [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), wird der Kontext als der gesamte logische Textknoten interpretiert, wie er von XPath gesehen wird, es sei denn, der Knoten ist leer, dann kann er nicht als XPath-Kontext dienen. |
| resolver | IXPathNSResolver | Der `resolver` ermöglicht die Übersetzung aller Präfixe, einschließlich des `xml`-Paketpräfixes, innerhalb des XPath-Ausdrucks in geeignete Paket-URIs. Wenn dies als `null` angegeben wird, führt jedes Paketpräfix im Ausdruck dazu, dass [`DOMException`](../../../com.aspose.html.dom/domexception/) mit dem Code `NAMESPACE_ERR` ausgelöst wird. |
| type | XPathResultType | Wenn ein bestimmter `type` angegeben ist, wird das Ergebnis als entsprechender Typ zurückgegeben. Für XPath‑1.0‑Ergebnisse muss dies einer der Werte des Enums [`XPathResultType`](../../xpathresulttype/) sein. |
| result | Object | Das `result` gibt ein bestimmtes Ergebnisobjekt an, das von dieser Methode wiederverwendet und zurückgegeben werden kann. Wenn es als `null` angegeben wird oder die Implementierung das angegebene Ergebnis nicht wiederverwendet, wird ein neues Ergebnisobjekt erstellt und zurückgegeben. Für XPath‑1.0‑Ergebnisse wird dieses Objekt vom Typ [`IXPathResult`](../../ixpathresult/) sein. |

### Rückgabewert

Das Ergebnis der Auswertung des XPath-Ausdrucks. Für XPath‑1.0‑Ergebnisse wird dieses Objekt vom Typ [`IXPathResult`](../../ixpathresult/) sein.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Wird ausgelöst, wenn der Ausdruck gemäß den Regeln des [`IXPathEvaluator`](../) nicht gültig ist. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: Wird ausgelöst, wenn das Ergebnis nicht in den angegebenen Typ konvertiert werden kann. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: Wird ausgelöst, wenn der Ausdruck Paketpräfixe enthält, die vom angegebenen [`IXPathNSResolver`](../../ixpathnsresolver/) nicht aufgelöst werden können. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: Der Knoten stammt aus einem Dokument, das von diesem [`IXPathEvaluator`](../) nicht unterstützt wird. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Der Knoten ist kein zulässiger Typ als XPath-Kontextknoten oder der angeforderte Typ wird von diesem [`IXPathEvaluator`](../) nicht unterstützt. |

### Siehe auch

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
