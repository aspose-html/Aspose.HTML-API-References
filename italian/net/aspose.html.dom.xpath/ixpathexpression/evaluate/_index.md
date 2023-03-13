---
title: IXPathExpression.Evaluate
second_title: Aspose.HTML per riferimento API .NET
description: IXPathExpression metodo. Valuta questa espressione XPath e restituisce un risultato.
type: docs
weight: 10
url: /it/net/aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Valuta questa espressione XPath e restituisce un risultato.

```csharp
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contextNode | Node | IL`contesto` è il nodo di contesto per la valutazione di questa espressione XPath. Se il[`IXPathEvaluator`](../../ixpathevaluator/) è stato ottenuto fondendo il[`Document`](../../../aspose.html.dom/document/) quindi questo deve essere di proprietà dello stesso documento e deve essere a[`Document`](../../../aspose.html.dom/document/) ,[`Element`](../../../aspose.html.dom/element/) ,[`Attr`](../../../aspose.html.dom/attr/) , [`Text`](../../../aspose.html.dom/text/) ,[`CDATASection`](../../../aspose.html.dom/cdatasection/) ,[`Comment`](../../../aspose.html.dom/comment/) ,[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) , oXPathNamespace nodo. Se il nodo di contesto è a[`Text`](../../../aspose.html.dom/text/) o un[`CDATASection`](../../../aspose.html.dom/cdatasection/), allora il contesto viene interpretato come l'intero nodo di testo logico visto da XPath, a meno che il nodo non sia vuoto nel qual caso potrebbe non fungere da contesto XPath. |
| type | XPathResultType | Se uno specifico`tipo` viene specificato, il risultato verrà forzato a restituire il tipo specificato basandosi sulle conversioni XPath e avrà esito negativo se la coercizione desiderata non è possibile. Questo deve essere uno dei valori di[`XPathResultType`](../../xpathresulttype/). |
| result | Object | IL`risultato` specifica un oggetto risultato specifico che può essere riutilizzato e restituito da questo metodo. Se questo è specificato come`nullo` l'implementazione non riutilizza il risultato specificato, verrà costruito e restituito un nuovo oggetto risultato. Per i risultati XPath 1.0, questo oggetto sarà di tipo [`IXPathResult`](../../ixpathresult/). |

### Valore di ritorno

Il risultato della valutazione dell'espressione XPath. Per i risultati XPath 1.0, questo oggetto sarà di tipo [`IXPathResult`](../../ixpathresult/).

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: sollevato se il risultato non può essere convertito per restituire il tipo specificato. |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: il nodo proviene da un documento non supportato da il[`IXPathEvaluator`](../../ixpathevaluator/) che ha creato questo[`IXPathExpression`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: il nodo non è un tipo consentito come nodo di contesto XPath o il tipo di richiesta non è consentito da questo[`IXPathExpression`](../). |

### Guarda anche

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* spazio dei nomi [Aspose.Html.Dom.XPath](../../ixpathexpression/)
* assemblea [Aspose.HTML](../../../)


