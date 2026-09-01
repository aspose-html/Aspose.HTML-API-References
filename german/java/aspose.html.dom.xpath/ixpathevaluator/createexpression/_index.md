---
title: "IXPathEvaluator.CreateExpression"
second_title: "Aspose.HTML für Java API-Referenz"
description: "IXPathEvaluator-Methode. Erstellt einen geparsten XPath-Ausdruck mit aufgelösten Paketen. Dies ist nützlich, wenn ein Ausdruck in einer Anwendung wiederverwendet werden soll, da es ermöglicht, den Ausdrucks-String in eine effizientere interne Form zu kompilieren und alle im Ausdruck vorkommenden Paketpräfixe vorab aufzulösen."
type: docs

url: /de/java/com.aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Erstellt einen geparsten XPath‑Ausdruck mit aufgelösten Paketen. Dies ist nützlich, wenn ein Ausdruck in einer Anwendung wiederverwendet werden soll, da er die Kompilierung der Ausdruckszeichenkette in eine effizientere interne Form ermöglicht und alle im Ausdruck vorkommenden Paket‑Präfixe vorab auflöst.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Ausdruck | String | Der XPath-Ausdruck-String, der geparst werden soll. |
| resolver | IXPathNSResolver | Der `resolver` ermöglicht die Übersetzung aller Präfixe, einschließlich des `xml`-Paketpräfixes, innerhalb des XPath-Ausdrucks in geeignete Paket-URIs. Wenn dies als `null` angegeben wird, führt jedes Paketpräfix im Ausdruck dazu, dass [`DOMException`](../../../com.aspose.html.dom/domexception/) mit dem Code `NAMESPACE_ERR` ausgelöst wird. |

### Rückgabewert

Die kompilierte Form des XPath-Ausdrucks.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Wird ausgelöst, wenn der Ausdruck gemäß den Regeln des [`IXPathEvaluator`](../) nicht gültig ist. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: Wird ausgelöst, wenn der Ausdruck Paketpräfixe enthält, die vom angegebenen [`IXPathNSResolver`](../../ixpathnsresolver/) nicht aufgelöst werden können. |

### Siehe auch

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
