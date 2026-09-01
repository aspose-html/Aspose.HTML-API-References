---
title: "com.aspose.html.dom.xpath"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Le package contient des méthodes pour naviguer parmi les éléments et les attributs d’un document XML."
type: docs

url: /fr/java/com.aspose.html.dom.xpath/
---
Le paquet contient des méthodes pour naviguer à travers les éléments et les attributs d'un document XML.

## Interfaces

| Interface | Description |
| --- | --- |
| [IXPathEvaluator](./ixpathevaluator/) | L’évaluation des expressions XPath est fournie par [`IXPathEvaluator`](../com.aspose.html.dom.xpath/ixpathevaluator/). |
| [IXPathExpression](./ixpathexpression/) | L’interface `XPathExpression` représente une expression XPath analysée et résolue. |
| [IXPathNamespace](./ixpathpackage/) | L’interface XPathNamespace est renvoyée par les interfaces XPathResult pour représenter le type de nœud du package XPath qui manque dans le DOM. |
| [IXPathNSResolver](./ixpathnsresolver/) | L’interface `XPathNSResolver` permet aux chaînes `prefix` dans l’expression d’être correctement liées aux chaînes `packageURI`. [`IXPathEvaluator`](../com.aspose.html.dom.xpath/ixpathevaluator/) peut construire une implémentation de [`IXPathNSResolver`](../com.aspose.html.dom.xpath/ixpathnsresolver/) à partir d’un nœud, ou l’interface peut être implémentée par toute application. |
| [IXPathResult](./ixpathresult/) | L’interface `XPathResult` représente le résultat de l’évaluation d’une expression XPath 1.0 dans le contexte d’un nœud particulier. Étant donné que l’évaluation d’une expression XPath peut produire divers types de résultats, cet objet permet de découvrir et de manipuler le type et la valeur du résultat. |
## Énumération

| Énumération | Description |
| --- | --- |
| [XPathResultType](./xpathresulttype/) | Un entier court non signé indiquant le type de résultat. Si un `type` spécifique est indiqué, le résultat sera renvoyé sous le type correspondant, en utilisant les conversions de type XPath lorsque cela est requis et possible. |
