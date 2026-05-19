---
title: "Interfaccia IXPathNSResolver"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Interfaccia com.aspose.html.dom.xpath.IXPathNSResolver. L'interfaccia XPathNSResolver consente alle stringhe di prefisso nell'espressione di essere correttamente associate a stringhe packageURI. IXPathEvaluator può costruire un'implementazione di IXPathNSResolver da un nodo o l'interfaccia può essere implementata da qualsiasi applicazione"
type: docs

url: /it/java/com.aspose.html.dom.xpath/ixpathnsresolver/
---
## IXPathNSResolver interface

L'interfaccia `XPathNSResolver` consente alle stringhe `prefix` nell'espressione di essere correttamente associate a stringhe `packageURI`. [`IXPathEvaluator`](../ixpathevaluator/) può costruire un'implementazione di `IXPathNSResolver` da un nodo, oppure l'interfaccia può essere implementata da qualsiasi applicazione.

```java
public interface IXPathNSResolver
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [lookupNamespaceURI](../../com.aspose.html.dom.xpath/ixpathnsresolver/lookuppackageuri/)(String) | Cerca l'URI del pacchetto associato al prefisso di pacchetto fornito. L'evaluatore XPath non deve mai chiamare questo metodo con un argomento `null` o vuoto, poiché il risultato sarebbe indefinito. |

### Vedi anche

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
