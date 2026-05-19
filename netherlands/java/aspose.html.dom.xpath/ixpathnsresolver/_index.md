---
title: "IXPathNSResolver‑interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.xpath.IXPathNSResolver‑interface. De XPathNSResolver‑interface staat toe dat prefix‑Strings in de expressie correct worden gebonden aan packageURI‑Strings. IXPathEvaluator kan een implementatie van IXPathNSResolver construeren vanuit een knooppunt of de interface kan door elke toepassing worden geïmplementeerd"
type: docs

url: /nl/java/com.aspose.html.dom.xpath/ixpathnsresolver/
---
## IXPathNSResolver interface

De `XPathNSResolver`‑interface staat toe dat `prefix`‑Strings in de expressie correct worden gebonden aan `packageURI`‑Strings. [`IXPathEvaluator`](../ixpathevaluator/) kan een implementatie van `IXPathNSResolver` construeren vanuit een knooppunt, of de interface kan door elke toepassing worden geïmplementeerd.

```java
public interface IXPathNSResolver
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [lookupNamespaceURI](../../com.aspose.html.dom.xpath/ixpathnsresolver/lookuppackageuri/)(String) | Zoek de package‑URI die bij het opgegeven package‑prefix hoort. De XPath‑evaluator mag dit nooit aanroepen met een `null` of leeg argument, omdat het resultaat hiervan ongedefinieerd is. |

### Zie ook

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
