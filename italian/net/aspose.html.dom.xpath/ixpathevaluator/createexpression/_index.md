---
title: IXPathEvaluator.CreateExpression
second_title: Aspose.HTML per riferimento API .NET
description: IXPathEvaluator metodo. Crea unespressione XPath analizzata con spazi dei nomi risolti. Questo è utile quando unespressione verrà riutilizzata in unapplicazione poiché rende possibile compilare la stringa dellespressione in un formato interno più efficiente e prerisolvere tutti i prefissi dello spazio dei nomi che ricorrono allinterno dellespressione.
type: docs
weight: 10
url: /it/net/aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Crea un'espressione XPath analizzata con spazi dei nomi risolti. Questo è utile quando un'espressione verrà riutilizzata in un'applicazione poiché rende possibile compilare la stringa dell'espressione in un formato interno più efficiente e pre-risolvere tutti i prefissi dello spazio dei nomi che ricorrono all'interno dell'espressione.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| expression | String | La stringa dell'espressione XPath da analizzare. |
| resolver | IXPathNSResolver | IL`risolutore` consente la traduzione di tutti i prefissi, compreso il`xml` prefisso dello spazio dei nomi, all'interno dell'espressione XPath in URI dello spazio dei nomi appropriati. Se questo è specificato come`nullo` , qualsiasi prefisso dello spazio dei nomi all'interno dell'espressione risulterà in[`DOMException`](../../../aspose.html.dom/domexception/) essere lanciato con il codice`NAMESPACE_ERR`. |

### Valore di ritorno

La forma compilata dell'espressione XPath.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: sollevato se l'espressione non è legale secondo le regole del[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR: sollevato se l'espressione contiene prefissi dello spazio dei nomi che non possono essere risolti dall'oggetto specificato[`IXPathNSResolver`](../../ixpathnsresolver/). |

### Guarda anche

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* spazio dei nomi [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* assemblea [Aspose.HTML](../../../)


