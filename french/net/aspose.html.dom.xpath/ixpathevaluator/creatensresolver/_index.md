---
title: IXPathEvaluator.CreateNSResolver
second_title: Référence de l'API Aspose.HTML pour .NET
description: IXPathEvaluator méthode. Adapte nimporte quel nœud DOM pour résoudre les espaces de noms afin quune expression XPath puisse être facilement évaluée par rapport au contexte du nœud où elle est apparue dans le document. Cet adaptateur fonctionne comme la méthode DOM niveau 3lookupNamespaceURI sur les nœuds en résolvant le namespaceURI à partir dun préfixe donné en utilisant les informations actuelles disponibles dans la hiérarchie du nœud au moment où lookupNamespaceURI est appelé en résolvant également correctement le préfixe xml implicite.
type: docs
weight: 20
url: /fr/net/aspose.html.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

Adapte n'importe quel nœud DOM pour résoudre les espaces de noms afin qu'une expression XPath puisse être facilement évaluée par rapport au contexte du nœud où elle est apparue dans le document. Cet adaptateur fonctionne comme la méthode DOM niveau 3`lookupNamespaceURI` sur les nœuds en résolvant le namespaceURI à partir d'un préfixe donné en utilisant les informations actuelles disponibles dans la hiérarchie du nœud au moment où lookupNamespaceURI est appelé, en résolvant également correctement le préfixe xml implicite.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| nodeResolver | Node | Nœud à utiliser comme contexte pour la résolution d'espace de noms. |

### Return_Value

[`IXPathNSResolver`](../../ixpathnsresolver/) qui résout les espaces de noms par rapport aux definitions dans la portée d'un nœud spécifié.

### Voir également

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathEvaluator](../)
* espace de noms [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* Assemblée [Aspose.HTML](../../../)


