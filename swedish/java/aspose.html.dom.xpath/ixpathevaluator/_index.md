---
title: "IXPathEvaluator Interface"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.xpath.IXPathEvaluator interface. Utvärderingen av XPath-uttryck tillhandahålls av IXPathEvaluator"
type: docs

url: /sv/java/com.aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

Utvärderingen av XPath-uttryck tillhandahålls av `IXPathEvaluator`.

```java
public interface IXPathEvaluator
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [createExpression](../../com.aspose.html.dom.xpath/ixpathevaluator/createexpression/)(String, IXPathNSResolver) | Skapar ett parsat XPath‑uttryck med upplösta paket. Detta är användbart när ett uttryck ska återanvändas i en applikation eftersom det möjliggör att kompilera uttrycksssträngen till en mer effektiv intern form och förupplösa alla paketprefix som förekommer i uttrycket. |
| [createNSResolver](../../com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | Anpassar vilken DOM‑nod som helst för att lösa paket så att ett XPath‑uttryck enkelt kan utvärderas relativt till nodens kontext där det förekom i dokumentet. Denna adapter fungerar som DOM Level 3‑metoden `lookupNamespaceURI` på noder för att lösa paket‑URI från ett givet prefix med den information som finns i nodens hierarki när lookupNamespaceURI anropas, och löser även korrekt det implicita xml‑prefixet. |
| [evaluate](../../com.aspose.html.dom.xpath/ixpathevaluator/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Utvärderar en XPath‑uttryck‑String och returnerar ett resultat av den angivna typen om möjligt. |

### Se även

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
