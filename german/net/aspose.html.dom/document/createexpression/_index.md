---
title: Document.CreateExpression
second_title: Aspose.HTML für .NET-API-Referenz
description: Document methode. Erstellt einen geparsten XPathAusdruck mit aufgelösten Namespaces. Dies ist nützlich wenn ein Ausdruck in einer Anwendung wiederverwendet wird da es ermöglicht die Ausdruckszeichenfolge in eine effizientere interne Form zu kompilieren und alle Namensraumpräfixe vorab aufzulösen die innerhalb des Ausdrucks vorkommen.
type: docs
weight: 890
url: /de/net/aspose.html.dom/document/createexpression/
---
## Document.CreateExpression method

Erstellt einen geparsten XPath-Ausdruck mit aufgelösten Namespaces. Dies ist nützlich, wenn ein Ausdruck in einer Anwendung wiederverwendet wird, da es ermöglicht, die Ausdruckszeichenfolge in eine effizientere interne Form zu kompilieren und alle Namensraumpräfixe vorab aufzulösen, die innerhalb des Ausdrucks vorkommen.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expression | String | Die zu analysierende XPath-Ausdruckszeichenfolge. |
| resolver | IXPathNSResolver | Der`Resolver` ermöglicht die Übersetzung aller Präfixe, einschließlich der`xml` Namespace-Präfix innerhalb des XPath-Ausdrucks in entsprechende Namespace-URIs. Wenn dies angegeben ist als`Null` , führt jedes Namespace-Präfix innerhalb des Ausdrucks zu[`DOMException`](../../domexception/) mit dem Code geworfen werden`NAMESPACE_ERR`. |

### Rückgabewert

Die kompilierte Form des XPath-Ausdrucks.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../domexception/) | INVALID_EXPRESSION_ERR: Wird ausgelöst, wenn der Ausdruck nach den Regeln des nicht legal ist[`IXPathEvaluator`](../../../aspose.html.dom.xpath/ixpathevaluator/). |
| [DOMException](../../domexception/) | NAMESPACE_ERR: Wird ausgelöst, wenn der Ausdruck Namespace -Präfixe enthält, die nicht durch die angegebenen aufgelöst werden können[`IXPathNSResolver`](../../../aspose.html.dom.xpath/ixpathnsresolver/). |

### Siehe auch

* interface [IXPathExpression](../../../aspose.html.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* namensraum [Aspose.Html.Dom](../../document/)
* Montage [Aspose.HTML](../../../)


