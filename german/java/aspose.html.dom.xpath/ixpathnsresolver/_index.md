---
title: "IXPathNSResolver‑Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.xpath.IXPathNSResolver‑Schnittstelle. Das XPathNSResolver‑Interface erlaubt es, Präfix‑Strings im Ausdruck korrekt an packageURI‑Strings zu binden. IXPathEvaluator kann eine Implementierung von IXPathNSResolver aus einem Knoten erstellen oder das Interface kann von jeder Anwendung implementiert werden."
type: docs

url: /de/java/com.aspose.html.dom.xpath/ixpathnsresolver/
---
## IXPathNSResolver interface

Das `XPathNSResolver`‑Interface erlaubt es, `prefix`‑Strings im Ausdruck korrekt an `packageURI`‑Strings zu binden. [`IXPathEvaluator`](../ixpathevaluator/) kann eine Implementierung von `IXPathNSResolver` aus einem Knoten erstellen, oder das Interface kann von jeder Anwendung implementiert werden.

```java
public interface IXPathNSResolver
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [lookupNamespaceURI](../../com.aspose.html.dom.xpath/ixpathnsresolver/lookuppackageuri/)(String) | Sucht die dem angegebenen Paketpräfix zugehörige package‑URI. Der XPath‑Evaluator darf dies niemals mit einem `null`‑ oder leeren Argument aufrufen, da das Ergebnis dieses Aufrufs undefiniert ist. |

### Siehe auch

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
