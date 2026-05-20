---
title: "com.aspose.html.dom.xpath"
second_title: "Aspose.HTML för Java API-referens"
description: "Paketet innehåller metoder för att navigera genom element och attribut i ett XML-dokument"
type: docs

url: /sv/java/com.aspose.html.dom.xpath/
---
Paketet innehåller metoder för att navigera genom element och attribut i ett XML-dokument.

## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IXPathEvaluator](./ixpathevaluator/) | Utvärderingen av XPath-uttryck tillhandahålls av [`IXPathEvaluator`](../com.aspose.html.dom.xpath/ixpathevaluator/). |
| [IXPathExpression](./ixpathexpression/) | `XPathExpression`-gränssnittet representerar ett parsat och löst XPath-uttryck. |
| [IXPathNamespace](./ixpathpackage/) | XPathNamespace-gränssnittet returneras av XPathResult-gränssnitt för att representera den XPath-paketnodtyp som DOM saknar. |
| [IXPathNSResolver](./ixpathnsresolver/) | `XPathNSResolver`-gränssnittet tillåter `prefix`-strängar i uttrycket att korrekt bindas till `packageURI`-strängar. [`IXPathEvaluator`](../com.aspose.html.dom.xpath/ixpathevaluator/) kan konstruera en implementation av [`IXPathNSResolver`](../com.aspose.html.dom.xpath/ixpathnsresolver/) från en nod, eller så kan gränssnittet implementeras av vilken applikation som helst. |
| [IXPathResult](./ixpathresult/) | `XPathResult`-gränssnittet representerar resultatet av utvärderingen av ett XPath 1.0-uttryck inom kontexten av en specifik nod. Eftersom utvärderingen av ett XPath-uttryck kan ge olika resultattyper, möjliggör detta objekt att upptäcka och manipulera typ och värde på resultatet. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [XPathResultType](./xpathresulttype/) | En osignerad short som indikerar vilken typ av resultat detta är. Om en specifik `type` anges, kommer resultatet att returneras som motsvarande typ, med XPath-typkonverteringar där det krävs och är möjligt. |
