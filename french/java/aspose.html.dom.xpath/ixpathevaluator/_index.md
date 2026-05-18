---
title: "Interface IXPathEvaluator"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.dom.xpath.IXPathEvaluator interface. L'évaluation des expressions XPath est fournie par IXPathEvaluator"
type: docs

url: /fr/java/com.aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

L'évaluation des expressions XPath est fournie par `IXPathEvaluator`.

```java
public interface IXPathEvaluator
```

## Méthodes

| Nom | Description |
| --- | --- |
| [createExpression](../../com.aspose.html.dom.xpath/ixpathevaluator/createexpression/)(String, IXPathNSResolver) | Crée une expression XPath analysée avec les packages résolus. Ceci est utile lorsqu'une expression sera réutilisée dans une application, car cela permet de compiler la chaîne d'expression en une forme interne plus efficace et de pré‑résoudre tous les préfixes de package présents dans l'expression. |
| [createNSResolver](../../com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | Adapte tout nœud DOM pour résoudre les packages afin qu'une expression XPath puisse être évaluée facilement par rapport au contexte du nœud où elle apparaît dans le document. Cet adaptateur fonctionne comme la méthode du DOM Niveau 3 `lookupNamespaceURI` sur les nœuds pour résoudre le packageURI à partir d'un préfixe donné en utilisant les informations disponibles dans la hiérarchie du nœud au moment de l'appel, tout en résolvant correctement le préfixe xml implicite. |
| [evaluate](../../com.aspose.html.dom.xpath/ixpathevaluator/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Évalue une chaîne d'expression XPath et renvoie un résultat du type spécifié si possible. |

### Voir aussi

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
