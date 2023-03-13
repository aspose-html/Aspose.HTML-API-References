---
title: IXPathEvaluator.Evaluate
second_title: Aspose.HTML per riferimento API .NET
description: IXPathEvaluator metodo. Valuta una stringa di espressione XPath e se possibile restituisce un risultato del tipo specificato.
type: docs
weight: 30
url: /it/net/aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Valuta una stringa di espressione XPath e, se possibile, restituisce un risultato del tipo specificato.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| expression | String | La stringa dell'espressione XPath da analizzare e valutare. |
| contextNode | Node | IL`contesto` è il nodo di contesto per la valutazione di questa espressione XPath. Se la[`IXPathEvaluator`](../) è stato ottenuto lanciando [`Document`](../../../aspose.html.dom/document/) allora questo deve essere di proprietà dello stesso documento e deve essere un [`Document`](../../../aspose.html.dom/document/) ,[`Element`](../../../aspose.html.dom/element/) ,[`Attr`](../../../aspose.html.dom/attr/) ,[`Text`](../../../aspose.html.dom/text/) , [`CDATASection`](../../../aspose.html.dom/cdatasection/) ,[`Comment`](../../../aspose.html.dom/comment/) ,[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) , oXPathNamespace nodo. Se il nodo di contesto è a[`Text`](../../../aspose.html.dom/text/) o un [`CDATASection`](../../../aspose.html.dom/cdatasection/)il contesto viene interpretato come l'intero nodo di testo logico visto da XPath, a meno che il nodo non sia vuoto, nel qual caso potrebbe non fungere da contesto XPath. |
| resolver | IXPathNSResolver | IL`risolutore` consente la traduzione di tutti i prefissi, incluso the`xml` prefisso dello spazio dei nomi, all'interno dell'espressione XPath negli URI dello spazio dei nomi appropriati. Se questo è specificato come`nullo` , qualsiasi prefisso dello spazio dei nomi all'interno dell'espressione risulterà in[`DOMException`](../../../aspose.html.dom/domexception/) essere lanciato con il codice`NAMESPACE_ERR`. |
| type | XPathResultType | Se uno specifico`tipo` è specificato, il risultato verrà restituito come il tipo corrispondente. Per i risultati XPath 1.0, questo deve essere uno dei valori di [`XPathResultType`](../../xpathresulttype/) enum. |
| result | Object | IL`risultato` specifica un oggetto risultato specifico che può essere riutilizzato e restituito da questo metodo. Se questo è specificato come`nullo` l'implementazione non riutilizza il risultato specificato, verrà costruito e restituito un nuovo oggetto risultato. Per i risultati XPath 1.0 , questo oggetto sarà di tipo[`IXPathResult`](../../ixpathresult/). |

### Valore di ritorno

Il risultato della valutazione dell'espressione XPath. Per i risultati XPath 1.0, questo oggetto sarà di tipo[`IXPathResult`](../../ixpathresult/).

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: sollevata se l'espressione non è legale secondo secondo le regole del[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: sollevato se il risultato non può essere convertito per restituire il tipo specificato. |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR: sollevato se l'espressione contiene prefissi dello spazio dei nomi che non possono essere risolti dall'oggetto specificato[`IXPathNSResolver`](../../ixpathnsresolver/). |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: il nodo proviene da un documento che non è supportato da questo[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: il nodo non è un tipo consentito come nodo del contesto XPath o il tipo di richiesta non è consentito da questo[`IXPathEvaluator`](../). |

### Guarda anche

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* spazio dei nomi [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* assemblea [Aspose.HTML](../../../)


