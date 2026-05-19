---
title: "Document.Evaluate"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo Document. Valuta una stringa di espressione XPath e restituisce un risultato del tipo specificato, se possibile"
type: docs

url: /it/java/com.aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

Valuta una Stringa di espressione XPath e restituisce un risultato del tipo specificato, se possibile.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| espressione | String | La stringa dell'espressione XPath da analizzare e valutare. |
| contextNode | Node | Il contesto è il nodo di contesto per la valutazione di questa espressione XPath. |
| resolver | IXPathNSResolver | Il risolutore consente la traduzione di tutti i prefissi, incluso il prefisso del pacchetto xml, all'interno dell'espressione XPath in URI di pacchetto appropriati. |
| tipo | XPathResultType | Se viene specificato un tipo specifico, il risultato verrà restituito come il tipo corrispondente. |
| result | Oggetto | Il risultato specifica un oggetto risultato specifico che può essere riutilizzato e restituito da questo metodo. |

### Valore di ritorno

Il risultato della valutazione dell'espressione XPath.

### Vedi anche

* interface [IXPathResult](../../../com.aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../com.aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
