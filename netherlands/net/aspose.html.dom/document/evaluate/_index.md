---
title: Document.Evaluate
second_title: Aspose.HTML voor .NET API-referentie
description: Document methode. Evalueert een XPathexpressietekenreeks en retourneert indien mogelijk een resultaat van het opgegeven type.
type: docs
weight: 950
url: /nl/net/aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

Evalueert een XPath-expressietekenreeks en retourneert indien mogelijk een resultaat van het opgegeven type.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expression | String | De tekenreeks voor de XPath-expressie die moet worden geparseerd en geëvalueerd. |
| contextNode | Node | De context is het contextknooppunt voor de evaluatie van deze XPath-expressie. |
| resolver | IXPathNSResolver | De resolver staat vertaling toe van alle prefixen, inclusief het xml -naamruimtevoorvoegsel, binnen de XPath-expressie in geschikte naamruimte-URI's. |
| type | XPathResultType | Als een specifiek type is opgegeven, wordt het resultaat geretourneerd als het overeenkomstige type. |
| result | Object | Het resultaat specificeert een specifiek resultaatobject dat door deze methode kan worden hergebruikt en geretourneerd. |

### Winstwaarde

Het resultaat van de evaluatie van de XPath-expressie.

### Zie ook

* interface [IXPathResult](../../../aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* naamruimte [Aspose.Html.Dom](../../document/)
* montage [Aspose.HTML](../../../)


