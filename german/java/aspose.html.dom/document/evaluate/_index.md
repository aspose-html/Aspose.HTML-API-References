---
title: "Document.Evaluate"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Document-Methode. Bewertet einen XPath-Ausdruck-String und gibt, falls möglich, ein Ergebnis des angegebenen Typs zurück."
type: docs

url: /de/java/com.aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

Evaluert eine XPath‑Ausdruck‑Zeichenkette und gibt, falls möglich, ein Ergebnis des angegebenen Typs zurück.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Ausdruck | String | Der XPath-Ausdruck-String, der geparst und ausgewertet werden soll. |
| contextNode | Node | Der Kontext ist der Kontextknoten für die Auswertung dieses XPath-Ausdrucks. |
| resolver | IXPathNSResolver | Der Resolver ermöglicht die Übersetzung aller Präfixe, einschließlich des xml-Paketpräfixes, innerhalb des XPath-Ausdrucks in geeignete Paket-URIs. |
| Typ | XPathResultType | Wenn ein bestimmter Typ angegeben ist, wird das Ergebnis als der entsprechende Typ zurückgegeben. |
| result | Objekt | Das Ergebnis gibt ein bestimmtes Ergebnisobjekt an, das von dieser Methode wiederverwendet und zurückgegeben werden kann. |

### Rückgabewert

Das Ergebnis der Auswertung des XPath-Ausdrucks.

### Siehe auch

* interface [IXPathResult](../../../com.aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../com.aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
