---
title: IXPathExpression.Evaluate
second_title: Aspose.HTML für .NET-API-Referenz
description: IXPathExpression methode. Wertet diesen XPathAusdruck aus und gibt ein Ergebnis zurück.
type: docs
weight: 10
url: /de/net/aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Wertet diesen XPath-Ausdruck aus und gibt ein Ergebnis zurück.

```csharp
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| contextNode | Node | Der`Kontext` ist Kontextknoten für die Auswertung dieses XPath-Ausdrucks. Wenn die[`IXPathEvaluator`](../../ixpathevaluator/) wurde durch Gießen der erhalten[`Document`](../../../aspose.html.dom/document/) dann muss dies im Besitz desselben Dokuments sein und muss a sein[`Document`](../../../aspose.html.dom/document/) ,[`Element`](../../../aspose.html.dom/element/) ,[`Attr`](../../../aspose.html.dom/attr/) , [`Text`](../../../aspose.html.dom/text/) ,[`CDATASection`](../../../aspose.html.dom/cdatasection/) ,[`Comment`](../../../aspose.html.dom/comment/) ,[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) , oderXPathNamespace Knoten. Wenn der Kontextknoten a[`Text`](../../../aspose.html.dom/text/) oder ein[`CDATASection`](../../../aspose.html.dom/cdatasection/), , dann wird der Kontext als der gesamte logische Textknoten interpretiert, wie er von XPath gesehen wird, es sei denn, der Knoten ist leer , in diesem Fall dient er möglicherweise nicht als XPath-Kontext. |
| type | XPathResultType | Wenn eine bestimmte`Typ` angegeben ist, wird das Ergebnis gezwungen, den angegebenen Typ zurückzugeben, der sich auf XPath-Konvertierungen stützt, und schlägt fehl, wenn die gewünschte Umwandlung nicht möglich ist. Dies muss einer der Werte von sein[`XPathResultType`](../../xpathresulttype/). |
| result | Object | Der`Ergebnis` gibt ein bestimmtes Ergebnisobjekt an, das wiederverwendet und von dieser Methode zurückgegeben werden kann. Wenn dies angegeben ist als`Null`oder die Implementierung das angegebene -Ergebnis nicht wiederverwendet, wird ein neues Ergebnisobjekt erstellt und zurückgegeben. Für XPath 1.0-Ergebnisse ist dieses Objekt vom Typ [`IXPathResult`](../../ixpathresult/). |

### Rückgabewert

Das Ergebnis der Auswertung des XPath-Ausdrucks. Für XPath 1.0-Ergebnisse ist dieses Objekt vom Typ [`IXPathResult`](../../ixpathresult/).

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: Wird ausgelöst, wenn das Ergebnis nicht konvertiert werden kann, um den angegebenen Typ zurückzugeben. |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: Der Knoten stammt aus einem Dokument, das nicht von unterstützt wird[`IXPathEvaluator`](../../ixpathevaluator/) der das geschaffen hat[`IXPathExpression`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Der Node ist kein Typ, der als XPath-Context-Node zugelassen ist, oder der Anforderungstyp ist von diesem nicht zugelassen[`IXPathExpression`](../). |

### Siehe auch

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* namensraum [Aspose.Html.Dom.XPath](../../ixpathexpression/)
* Montage [Aspose.HTML](../../../)


