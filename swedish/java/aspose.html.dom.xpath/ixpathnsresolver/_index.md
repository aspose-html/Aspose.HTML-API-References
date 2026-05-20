---
title: "IXPathNSResolver‑gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.xpath.IXPathNSResolver‑gränssnitt. XPathNSResolver‑gränssnittet tillåter prefix‑strängar i uttrycket att bindas korrekt till packageURI‑strängar. IXPathEvaluator kan konstruera en implementation av IXPathNSResolver från en nod eller så kan gränssnittet implementeras av vilken applikation som helst"
type: docs

url: /sv/java/com.aspose.html.dom.xpath/ixpathnsresolver/
---
## IXPathNSResolver interface

`XPathNSResolver`‑gränssnittet tillåter `prefix`‑strängar i uttrycket att bindas korrekt till `packageURI`‑strängar. [`IXPathEvaluator`](../ixpathevaluator/) kan konstruera en implementation av `IXPathNSResolver` från en nod, eller så kan gränssnittet implementeras av vilken applikation som helst.

```java
public interface IXPathNSResolver
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [lookupNamespaceURI](../../com.aspose.html.dom.xpath/ixpathnsresolver/lookuppackageuri/)(String) | Slå upp package‑URI:n som är associerad med det angivna paket‑prefixet. XPath‑utvärderaren får aldrig anropa detta med ett `null`‑ eller tomt argument, eftersom resultatet av detta är odefinierat. |

### Se även

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
