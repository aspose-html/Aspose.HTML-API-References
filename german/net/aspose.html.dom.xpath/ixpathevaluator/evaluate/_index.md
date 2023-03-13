---
title: IXPathEvaluator.Evaluate
second_title: Aspose.HTML für .NET-API-Referenz
description: IXPathEvaluator methode. Wertet eine XPathAusdruckszeichenfolge aus und gibt wenn möglich ein Ergebnis des angegebenen Typs zurück.
type: docs
weight: 30
url: /de/net/aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Wertet eine XPath-Ausdruckszeichenfolge aus und gibt, wenn möglich, ein Ergebnis des angegebenen Typs zurück.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expression | String | Die zu analysierende und auszuwertende XPath-Ausdruckszeichenfolge. |
| contextNode | Node | Der`Kontext` ist Kontextknoten für die Auswertung dieses XPath-Ausdrucks. Wenn die[`IXPathEvaluator`](../) wurde durch das Gießen des erhalten[`Document`](../../../aspose.html.dom/document/) dann muss dies demselben Dokument gehören und ein sein[`Document`](../../../aspose.html.dom/document/) ,[`Element`](../../../aspose.html.dom/element/) ,[`Attr`](../../../aspose.html.dom/attr/) ,[`Text`](../../../aspose.html.dom/text/) , [`CDATASection`](../../../aspose.html.dom/cdatasection/) ,[`Comment`](../../../aspose.html.dom/comment/) ,[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) , oderXPathNamespace Knoten. Wenn der Kontextknoten a[`Text`](../../../aspose.html.dom/text/) oder ein [`CDATASection`](../../../aspose.html.dom/cdatasection/)dann wird der Kontext als der gesamte logische Textknoten interpretiert, wie er von XPath gesehen wird, es sei denn, der Knoten ist leer, in diesem Fall dient er möglicherweise nicht als XPath-Kontext. |
| resolver | IXPathNSResolver | Der`Resolver` ermöglicht die Übersetzung aller Präfixe, einschließlich die`xml` Namespace-Präfix innerhalb des XPath-Ausdrucks in die entsprechenden Namespace-URIs. Wenn dies angegeben ist als`Null` , führt jedes Namespace-Präfix innerhalb des Ausdrucks zu [`DOMException`](../../../aspose.html.dom/domexception/) mit dem Code geworfen werden`NAMESPACE_ERR`. |
| type | XPathResultType | Wenn eine bestimmte`Typ` angegeben ist, wird das Ergebnis als des entsprechenden Typs zurückgegeben. Für XPath 1.0-Ergebnisse muss dies einer der Werte von sein.[`XPathResultType`](../../xpathresulttype/) Aufzählung. |
| result | Object | Der`Ergebnis` gibt ein bestimmtes Ergebnisobjekt an, das wiederverwendet und von dieser Methode zurückgegeben werden kann. Wenn dies angegeben ist als`Null`oder die Implementierung das angegebene Ergebnis nicht wiederverwendet, wird ein neues Ergebnisobjekt erstellt und zurückgegeben. Für XPath 1.0 -Ergebnisse ist dieses Objekt vom Typ[`IXPathResult`](../../ixpathresult/). |

### Rückgabewert

Das Ergebnis der Auswertung des XPath-Ausdrucks. Für XPath 1.0-Ergebnisse ist dieses Objekt vom Typ[`IXPathResult`](../../ixpathresult/).

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Wird ausgelöst, wenn der Ausdruck gemäß den Regeln des nicht zulässig ist[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: Wird ausgelöst, wenn das Ergebnis nicht konvertiert werden kann, um den angegebenen Typ zurückzugeben. |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR: Wird ausgelöst, wenn der Ausdruck Namespace-Präfixe enthält, die von den angegebenen nicht aufgelöst werden können[`IXPathNSResolver`](../../ixpathnsresolver/). |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: Der Knoten stammt aus einem Dokument, das von diesem nicht unterstützt wird[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Der Knoten ist kein Typ, der als XPath-Kontext -Knoten zugelassen ist, oder der Anforderungstyp ist von diesem nicht zugelassen[`IXPathEvaluator`](../). |

### Siehe auch

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* namensraum [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* Montage [Aspose.HTML](../../../)


