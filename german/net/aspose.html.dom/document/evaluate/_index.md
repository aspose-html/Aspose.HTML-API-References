---
title: Document.Evaluate
second_title: Aspose.HTML für .NET-API-Referenz
description: Document methode. Wertet eine XPathAusdruckszeichenfolge aus und gibt wenn möglich ein Ergebnis des angegebenen Typs zurück.
type: docs
weight: 950
url: /de/net/aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

Wertet eine XPath-Ausdruckszeichenfolge aus und gibt, wenn möglich, ein Ergebnis des angegebenen Typs zurück.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expression | String | Die zu analysierende und auszuwertende XPath-Ausdruckszeichenfolge. |
| contextNode | Node | Der Kontext ist Kontextknoten für die Auswertung dieses XPath-Ausdrucks. |
| resolver | IXPathNSResolver | Der Resolver erlaubt die Übersetzung aller Präfixe, einschließlich des Namensraumpräfixes xml , innerhalb des XPath-Ausdrucks in geeignete Namensraum-URIs. |
| type | XPathResultType | Wenn ein bestimmter Typ angegeben wird, wird das Ergebnis als der entsprechende Typ zurückgegeben. |
| result | Object | Das Ergebnis gibt ein bestimmtes Ergebnisobjekt an, das von dieser Methode wiederverwendet und zurückgegeben werden kann. |

### Rückgabewert

Das Ergebnis der Auswertung des XPath-Ausdrucks.

### Siehe auch

* interface [IXPathResult](../../../aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* namensraum [Aspose.Html.Dom](../../document/)
* Montage [Aspose.HTML](../../../)


