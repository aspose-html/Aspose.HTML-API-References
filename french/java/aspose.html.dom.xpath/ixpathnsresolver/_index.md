---
title: "Interface IXPathNSResolver"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.dom.xpath.IXPathNSResolver interface. L'interface XPathNSResolver permet aux chaînes de préfixe dans l'expression d'être correctement liées aux chaînes packageURI. IXPathEvaluator peut construire une implémentation de IXPathNSResolver à partir d'un nœud ou l'interface peut être implémentée par n'importe quelle application"
type: docs

url: /fr/java/com.aspose.html.dom.xpath/ixpathnsresolver/
---
## IXPathNSResolver interface

L'interface `XPathNSResolver` permet aux chaînes `prefix` dans l'expression d'être correctement liées aux chaînes `packageURI`. [`IXPathEvaluator`](../ixpathevaluator/) peut construire une implémentation de `IXPathNSResolver` à partir d'un nœud, ou l'interface peut être implémentée par n'importe quelle application.

```java
public interface IXPathNSResolver
```

## Méthodes

| Nom | Description |
| --- | --- |
| [lookupNamespaceURI](../../com.aspose.html.dom.xpath/ixpathnsresolver/lookuppackageuri/)(String) | Recherchez l'URI du package associé au préfixe de package donné. L'évaluateur XPath ne doit jamais appeler cela avec un argument `null` ou vide, car le résultat de cette opération est indéfini. |

### Voir aussi

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
