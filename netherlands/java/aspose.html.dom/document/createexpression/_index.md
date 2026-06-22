---
title: "Document.CreateExpression"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Document-methode. Maakt een geparseerde XPath-expressie met opgeloste pakketten. Dit is nuttig wanneer een expressie opnieuw wordt gebruikt in een toepassing, omdat het mogelijk maakt de expressie‑String te compileren naar een efficiëntere interne vorm en alle pakket‑prefixen die in de expressie voorkomen vooraf op te lossen."
type: docs

url: /nl/java/com.aspose.html.dom/document/createexpression/
---
## Document.CreateExpression method

Maakt een geparseerde XPath‑expressie met opgeloste pakketten. Dit is nuttig wanneer een expressie opnieuw wordt gebruikt in een toepassing, omdat het mogelijk maakt de expressie‑String te compileren naar een efficiëntere interne vorm en alle pakket‑prefixen die in de expressie voorkomen vooraf op te lossen.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expressie | String | De XPath-expressie‑String die moet worden geparseerd. |
| resolver | IXPathNSResolver | De `resolver` staat vertaling van alle prefixen toe, inclusief de `xml`-pakketprefix, binnen de XPath-expressie naar geschikte pakket‑URI's. Als dit is opgegeven als `null`, zal elke pakketprefix binnen de expressie resulteren in een [`DOMException`](../../domexception/) die wordt gegooid met de code `NAMESPACE_ERR`. |

### Retourwaarde

De gecompileerde vorm van de XPath-expressie.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../domexception/) | INVALID_EXPRESSION_ERR: Opgeworpen als de expressie niet geldig is volgens de regels van de [`IXPathEvaluator`](../../../com.aspose.html.dom.xpath/ixpathevaluator/). |
| [dOMException](../../domexception/) | NAMESPACE_ERR: Opgeworpen als de expressie pakket‑prefixen bevat die niet kunnen worden opgelost door de opgegeven [`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/). |

### Zie ook

* interface [IXPathExpression](../../../com.aspose.html.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
