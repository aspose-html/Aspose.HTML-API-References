---
title: "Document.Evaluate"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Documentmethode. Evalueert een XPath-expressiestring en retourneert een resultaat van het opgegeven type indien mogelijk"
type: docs

url: /nl/java/com.aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

Evalueert een XPath‑expressie‑String en retourneert een resultaat van het opgegeven type indien mogelijk.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expressie | String | De XPath-expressie‑String die moet worden geparseerd en geëvalueerd. |
| contextNode | Node | De context is het contextknooppunt voor de evaluatie van deze XPath-expressie. |
| resolver | IXPathNSResolver | De resolver staat vertaling van alle prefixen, inclusief het xml-pakketprefix, binnen de XPath-expressie naar de juiste pakket-URI's toe. |
| type | XPathResultType | Als een specifiek type is opgegeven, wordt het resultaat geretourneerd als het overeenkomstige type. |
| result | Object | Het resultaat specificeert een specifiek resultaatobject dat door deze methode kan worden hergebruikt en geretourneerd. |

### Retourwaarde

Het resultaat van de evaluatie van de XPath-expressie.

### Zie ook

* interface [IXPathResult](../../../com.aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../com.aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
