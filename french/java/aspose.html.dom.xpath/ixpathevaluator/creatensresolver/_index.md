---
title: "IXPathEvaluator.CreateNSResolver"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode IXPathEvaluator. Adapte tout nœud DOM pour résoudre les packages afin qu'une expression XPath puisse être évaluée facilement par rapport au contexte du nœud où elle apparaît dans le document. Cet adaptateur fonctionne comme la méthode DOM Level 3 lookupNamespaceURI sur les nœuds pour résoudre le packageURI à partir d'un préfixe donné en utilisant les informations courantes disponibles dans la hiérarchie des nœuds au moment où lookupNamespaceURI est appelé, tout en résolvant correctement le préfixe xml implicite."
type: docs

url: /fr/java/com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

Adapte tout nœud DOM pour résoudre les packages afin qu'une expression XPath puisse être évaluée facilement par rapport au contexte du nœud où elle apparaît dans le document. Cet adaptateur fonctionne comme la méthode du DOM Niveau 3 `lookupNamespaceURI` sur les nœuds pour résoudre le packageURI à partir d'un préfixe donné en utilisant les informations disponibles dans la hiérarchie du nœud au moment de l'appel, tout en résolvant correctement le préfixe xml implicite.

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nodeResolver | Node | Le nœud à utiliser comme contexte pour la résolution des packages. |

### Valeur de retour

[`IXPathNSResolver`](../../ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### Voir aussi

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
