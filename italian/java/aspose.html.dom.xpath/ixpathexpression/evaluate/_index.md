---
title: "IXPathExpression.Evaluate"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo IXPathExpression. Valuta questa espressione XPath e restituisce un risultato."
type: docs

url: /it/java/com.aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Valuta questa espressione XPath e restituisce un risultato.

```java
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contextNode | Node | Il `context` è il nodo di contesto per la valutazione di questa espressione XPath. Se il [`IXPathEvaluator`](../../ixpathevaluator/) è stato ottenuto effettuando il cast del [`Document`](../../../com.aspose.html.dom/document/) allora questo deve appartenere allo stesso documento e deve essere un [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/), o un nodo XPathNamespace. Se il nodo di contesto è un [`Text`](../../../com.aspose.html.dom/text/) o un [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), allora il contesto è interpretato come l'intero nodo di testo logico visto da XPath, a meno che il nodo non sia vuoto, nel qual caso potrebbe non servire come contesto XPath. |
| type | XPathResultType | Se viene specificato un `type` specifico, il risultato sarà forzato a restituire il tipo specificato facendo affidamento sulle conversioni XPath e fallirà se la coercizione desiderata non è possibile. Deve essere uno dei valori di [`XPathResultType`](../../xpathresulttype/). |
| result | Object | Il `result` specifica un oggetto risultato specifico che può essere riutilizzato e restituito da questo metodo. Se è specificato come `null` o l'implementazione non riutilizza il risultato specificato, verrà costruito e restituito un nuovo oggetto risultato. Per i risultati XPath 1.0, questo oggetto sarà di tipo [`IXPathResult`](../../ixpathresult/). |

### Valore di ritorno

Il risultato della valutazione dell'espressione XPath. Per i risultati XPath 1.0, questo oggetto sarà di tipo [`IXPathResult`](../../ixpathresult/).

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: Sollevato se il risultato non può essere convertito per restituire il tipo specificato. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: Il Nodo proviene da un documento non supportato dal [`IXPathEvaluator`](../../ixpathevaluator/) che ha creato questo [`IXPathExpression`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Il Nodo non è di un tipo consentito come nodo di contesto XPath o il tipo di richiesta non è consentito da questo [`IXPathExpression`](../). |

### Vedi anche

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
