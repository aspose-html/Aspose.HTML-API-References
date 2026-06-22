---
title: "com.aspose.html.dom.xpath"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Het pakket bevat methoden om door elementen en attributen in een XML-document te navigeren."
type: docs

url: /nl/java/com.aspose.html.dom.xpath/
---
Het pakket bevat methoden om door elementen en attributen in een XML-document te navigeren.

## Interfaces

| Interface | Beschrijving |
| --- | --- |
| [IXPathEvaluator](./ixpathevaluator/) | De evaluatie van XPath-expressies wordt geleverd door [`IXPathEvaluator`](../com.aspose.html.dom.xpath/ixpathevaluator/). |
| [IXPathExpression](./ixpathexpression/) | De `XPathExpression`-interface vertegenwoordigt een geparseerde en opgeloste XPath-expressie. |
| [IXPathNamespace](./ixpathpackage/) | De XPathNamespace-interface wordt geretourneerd door XPathResult-interfaces om het XPath-pakketknooppunttype weer te geven dat DOM mist. |
| [IXPathNSResolver](./ixpathnsresolver/) | De `XPathNSResolver`-interface staat `prefix`-strings in de expressie toe om correct te worden gekoppeld aan `packageURI`-strings. [`IXPathEvaluator`](../com.aspose.html.dom.xpath/ixpathevaluator/) kan een implementatie van [`IXPathNSResolver`](../com.aspose.html.dom.xpath/ixpathnsresolver/) construeren vanuit een knoop, of de interface kan door elke applicatie worden geïmplementeerd. |
| [IXPathResult](./ixpathresult/) | De `XPathResult`-interface vertegenwoordigt het resultaat van de evaluatie van een XPath 1.0-expressie binnen de context van een specifiek knooppunt. Aangezien de evaluatie van een XPath-expressie kan resulteren in verschillende resultaatssoorten, maakt dit object het mogelijk om het type en de waarde van het resultaat te ontdekken en te manipuleren. |
## Enumeratie

| Enumeratie | Beschrijving |
| --- | --- |
| [XPathResultType](./xpathresulttype/) | Een unsigned short die aangeeft van welk type resultaat dit is. Als een specifiek `type` is opgegeven, wordt het resultaat geretourneerd als het overeenkomstige type, met gebruik van XPath-typeconversies waar nodig en mogelijk. |
