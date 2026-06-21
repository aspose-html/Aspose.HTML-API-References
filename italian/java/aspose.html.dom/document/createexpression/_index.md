---
title: "Document.CreateExpression"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo Document. Crea un'espressione XPath analizzata con i pacchetti risolti. Questo è utile quando un'espressione verrà riutilizzata in un'applicazione poiché consente di compilare la stringa dell'espressione in una forma interna più efficiente e di pre-risolvere tutti i prefissi dei pacchetti presenti nell'espressione."
type: docs

url: /it/java/com.aspose.html.dom/document/createexpression/
---
## Document.CreateExpression method

Crea un'espressione XPath analizzata con i pacchetti risolti. Questo è utile quando un'espressione verrà riutilizzata in un'applicazione poiché consente di compilare la Stringa dell'espressione in una forma interna più efficiente e di pre-risolvere tutti i prefissi dei pacchetti presenti nell'espressione.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| espressione | String | La stringa dell'espressione XPath da analizzare. |
| resolver | IXPathNSResolver | Il `resolver` consente la traduzione di tutti i prefissi, incluso il prefisso del pacchetto `xml`, all'interno dell'espressione XPath in URI di pacchetto appropriati. Se questo è specificato come `null`, qualsiasi prefisso di pacchetto all'interno dell'espressione causerà il lancio di [`DOMException`](../../domexception/) con il codice `NAMESPACE_ERR`. |

### Valore di ritorno

La forma compilata dell'espressione XPath.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../domexception/) | INVALID_EXPRESSION_ERR: Generato se l'espressione non è valida secondo le regole di [`IXPathEvaluator`](../../../com.aspose.html.dom.xpath/ixpathevaluator/). |
| [dOMException](../../domexception/) | NAMESPACE_ERR: Generato se l'espressione contiene prefissi di pacchetto che non possono essere risolti dal [`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/) specificato. |

### Vedi anche

* interface [IXPathExpression](../../../com.aspose.html.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
