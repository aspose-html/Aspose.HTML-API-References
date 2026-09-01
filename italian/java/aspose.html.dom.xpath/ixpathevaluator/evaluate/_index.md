---
title: "IXPathEvaluator.Evaluate"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo IXPathEvaluator. Valuta una stringa di espressione XPath e restituisce un risultato del tipo specificato, se possibile."
type: docs

url: /it/java/com.aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Valuta una Stringa di espressione XPath e restituisce un risultato del tipo specificato, se possibile.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| espressione | String | La stringa dell'espressione XPath da analizzare e valutare. |
| contextNode | Node | Il `context` è il nodo di contesto per la valutazione di questa espressione XPath. Se il [`IXPathEvaluator`](../) è stato ottenuto mediante cast del [`Document`](../../../com.aspose.html.dom/document/), allora questo deve appartenere allo stesso documento e deve essere un [`Document`](../../../com.aspose.html.dom/document/), un [`Element`](../../../com.aspose.html.dom/element/), un [`Attr`](../../../com.aspose.html.dom/attr/), un [`Text`](../../../com.aspose.html.dom/text/), un [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), un [`Comment`](../../../com.aspose.html.dom/comment/), un [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/), o un nodo XPathNamespace. Se il nodo di contesto è un [`Text`](../../../com.aspose.html.dom/text/) o un [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), allora il contesto è interpretato come l'intero nodo di testo logico visto da XPath, a meno che il nodo non sia vuoto, nel qual caso potrebbe non servire come contesto XPath. |
| resolver | IXPathNSResolver | Il `resolver` consente la traduzione di tutti i prefissi, incluso il prefisso del pacchetto `xml`, all'interno dell'espressione XPath in URI di pacchetto appropriati. Se viene specificato come `null`, qualsiasi prefisso di pacchetto nell'espressione provocherà il lancio di [`DOMException`](../../../com.aspose.html.dom/domexception/) con il codice `NAMESPACE_ERR`. |
| type | XPathResultType | Se viene specificato un `type` specifico, il risultato verrà restituito come il tipo corrispondente. Per i risultati XPath 1.0, questo deve essere uno dei valori dell'enumerazione [`XPathResultType`](../../xpathresulttype/). |
| result | Object | Il `result` specifica un oggetto risultato specifico che può essere riutilizzato e restituito da questo metodo. Se è specificato come `null` o l'implementazione non riutilizza il risultato specificato, verrà costruito e restituito un nuovo oggetto risultato. Per i risultati XPath 1.0, questo oggetto sarà del tipo [`IXPathResult`](../../ixpathresult/). |

### Valore di ritorno

Il risultato della valutazione dell'espressione XPath. Per i risultati XPath 1.0, questo oggetto sarà del tipo [`IXPathResult`](../../ixpathresult/).

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Generato se l'espressione non è valida secondo le regole di [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: Sollevato se il risultato non può essere convertito per restituire il tipo specificato. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: Generato se l'espressione contiene prefissi di pacchetto che non possono essere risolti dal [`IXPathNSResolver`](../../ixpathnsresolver/) specificato. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: Il nodo proviene da un documento non supportato da questo [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Il nodo non è di un tipo consentito come nodo di contesto XPath o il tipo di richiesta non è consentito da questo [`IXPathEvaluator`](../). |

### Vedi anche

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
