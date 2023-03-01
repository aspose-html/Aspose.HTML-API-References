---
title: Document.Evaluate
second_title: Aspose.HTML per riferimento API .NET
description: Document metodo. Valuta una stringa di espressione XPath e se possibile restituisce un risultato del tipo specificato.
type: docs
weight: 950
url: /it/net/aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

Valuta una stringa di espressione XPath e, se possibile, restituisce un risultato del tipo specificato.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| expression | String | La stringa dell'espressione XPath da analizzare e valutare. |
| contextNode | Node | Il contesto è il nodo di contesto per la valutazione di questa espressione XPath. |
| resolver | IXPathNSResolver | Il resolver consente la traduzione di tutti i prefissi, incluso il prefisso dello spazio dei nomi xml , all'interno dell'espressione XPath negli URI dello spazio dei nomi appropriati. |
| type | XPathResultType | Se viene specificato un tipo specifico, il risultato verrà restituito come il tipo corrispondente. |
| result | Object | Il risultato specifica un oggetto risultato specifico che può essere riutilizzato e restituito da questo metodo. |

### Valore di ritorno

Il risultato della valutazione dell'espressione XPath.

### Guarda anche

* interface [IXPathResult](../../../aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* spazio dei nomi [Aspose.Html.Dom](../../document/)
* assemblea [Aspose.HTML](../../../)


