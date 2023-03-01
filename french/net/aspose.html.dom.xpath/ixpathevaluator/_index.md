---
title: Interface IXPathEvaluator
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Dom.XPath.IXPathEvaluator interface. Lévaluation des expressions XPath est fournie parIXPathEvaluator .
type: docs
weight: 2560
url: /fr/net/aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

L'évaluation des expressions XPath est fournie par`IXPathEvaluator` .

```csharp
public interface IXPathEvaluator
```

## Méthodes

| Nom | La description |
| --- | --- |
| [CreateExpression](../../aspose.html.dom.xpath/ixpathevaluator/createexpression/)(string, IXPathNSResolver) | Crée une expression XPath analysée avec des espaces de noms résolus. Ceci est utile lorsqu'une expression sera réutilisée dans une application car cela permet de compiler la chaîne d'expression dans une forme interne plus efficace et de pré-résoudre tous les préfixes d'espace de noms qui se produisent dans l'expression. |
| [CreateNSResolver](../../aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | Adapte n'importe quel nœud DOM pour résoudre les espaces de noms afin qu'une expression XPath puisse être facilement évaluée par rapport au contexte du nœud où elle est apparue dans le document. Cet adaptateur fonctionne comme la méthode DOM niveau 3`lookupNamespaceURI` sur les nœuds en résolvant le namespaceURI à partir d'un préfixe donné en utilisant les informations actuelles disponibles dans la hiérarchie du nœud au moment où lookupNamespaceURI est appelé, en résolvant également correctement le préfixe xml implicite. |
| [Evaluate](../../aspose.html.dom.xpath/ixpathevaluator/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | Évalue une chaîne d'expression XPath et renvoie un résultat du type spécifié si possible. |

### Voir également

* espace de noms [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* Assemblée [Aspose.HTML](../../)


