---
title: "IXPathEvaluator.CreateExpression"
second_title: "Riferimento API Aspose.HTML per Java"
description: "IXPathEvaluator method. Crea un'espressione XPath analizzata con i pacchetti risolti. Questo è utile quando un'espressione verrà riutilizzata in un'applicazione poiché consente di compilare la stringa dell'espressione in una forma interna più efficiente e di pre-risolvere tutti i prefissi dei pacchetti presenti nell'espressione."
type: docs

url: /it/java/com.aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Crea un'espressione XPath analizzata con i pacchetti risolti. Questo è utile quando un'espressione verrà riutilizzata in un'applicazione poiché consente di compilare la Stringa dell'espressione in una forma interna più efficiente e di pre-risolvere tutti i prefissi dei pacchetti presenti nell'espressione.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| espressione | String | La stringa dell'espressione XPath da analizzare. |
| resolver | IXPathNSResolver | Il `resolver` consente la traduzione di tutti i prefissi, incluso il prefisso del pacchetto `xml`, all'interno dell'espressione XPath in URI di pacchetto appropriati. Se viene specificato come `null`, qualsiasi prefisso di pacchetto nell'espressione provocherà il lancio di [`DOMException`](../../../com.aspose.html.dom/domexception/) con il codice `NAMESPACE_ERR`. |

### Valore di ritorno

La forma compilata dell'espressione XPath.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Generato se l'espressione non è valida secondo le regole di [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: Generato se l'espressione contiene prefissi di pacchetto che non possono essere risolti dal [`IXPathNSResolver`](../../ixpathnsresolver/) specificato. |

### Vedi anche

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
