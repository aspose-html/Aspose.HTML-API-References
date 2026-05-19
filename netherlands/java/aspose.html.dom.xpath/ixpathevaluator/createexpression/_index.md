---
title: "IXPathEvaluator.CreateExpression"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IXPathEvaluator-methode. Maakt een geparseerde XPath-expressie met opgeloste pakketten. Dit is handig wanneer een expressie opnieuw wordt gebruikt in een toepassing, omdat het mogelijk maakt de expressie‑String te compileren naar een efficiëntere interne vorm en alle pakket‑prefixen die in de expressie voorkomen vooraf op te lossen."
type: docs

url: /nl/java/com.aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Maakt een geparseerde XPath‑expressie met opgeloste pakketten. Dit is nuttig wanneer een expressie opnieuw wordt gebruikt in een toepassing, omdat het mogelijk maakt de expressie‑String te compileren naar een efficiëntere interne vorm en alle pakket‑prefixen die in de expressie voorkomen vooraf op te lossen.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expressie | String | De XPath‑expressie‑String die moet worden geparseerd. |
| resolver | IXPathNSResolver | De `resolver` staat vertaling van alle prefixen toe, inclusief de `xml`-pakketprefix, binnen de XPath‑expressie naar de juiste pakket‑URI's. Als dit wordt opgegeven als `null`, zal elke pakket‑prefix in de expressie resulteren in een [`DOMException`](../../../com.aspose.html.dom/domexception/) met de code `NAMESPACE_ERR`. |

### Retourwaarde

De gecompileerde vorm van de XPath‑expressie.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Opgeworpen als de expressie niet geldig is volgens de regels van de [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: Opgeworpen als de expressie pakket‑prefixen bevat die niet kunnen worden opgelost door de opgegeven [`IXPathNSResolver`](../../ixpathnsresolver/). |

### Zie ook

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
