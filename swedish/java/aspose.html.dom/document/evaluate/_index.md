---
title: "Document.Evaluate"
second_title: "Aspose.HTML för Java API-referens"
description: "Dokumentmetod. Utvärderar en XPath‑uttryckssträng och returnerar ett resultat av den angivna typen om möjligt."
type: docs

url: /sv/java/com.aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

Utvärderar en XPath‑uttryck‑sträng och returnerar ett resultat av den angivna typen om möjligt.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uttryck | String | XPath‑uttryck String som ska analyseras och utvärderas. |
| contextNode | Node | Kontexten är kontextnod för utvärderingen av detta XPath‑uttryck. |
| resolver | IXPathNSResolver | Resolvern tillåter översättning av alla prefix, inklusive xml‑paketprefixet, i XPath‑uttrycket till lämpliga paket‑URI:er. |
| typ | XPathResultType | Om en specifik typ anges kommer resultatet att returneras som motsvarande typ. |
| result | Objekt | Resultatet specificerar ett specifikt resultatobjekt som kan återanvändas och returneras av denna metod. |

### Returvärde

Resultatet av utvärderingen av XPath‑uttrycket.

### Se även

* interface [IXPathResult](../../../com.aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../com.aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
