---
title: "NodeFilter.AcceptNode"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode NodeFilter. Tester si un nœud spécifié est visible dans la vue logique d’un TreeWalker ou d’un NodeIterator. Cette fonction sera appelée par l’implémentation de TreeWalker et NodeIterator ; elle n’est généralement pas appelée directement depuis le code utilisateur. Vous pourriez toutefois le faire si vous souhaitez utiliser le même filtre pour guider la logique de votre application."
type: docs

url: /fr/java/com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/
---
## NodeFilter.AcceptNode method

Vérifie si un nœud spécifié est visible dans la vue logique d’un TreeWalker ou d’un NodeIterator. Cette fonction sera appelée par l’implémentation de TreeWalker et NodeIterator ; elle n’est généralement pas appelée directement depuis le code utilisateur. (Bien que vous puissiez le faire si vous souhaitez utiliser le même filtre pour guider la logique de votre application.)

```java
public abstract short AcceptNode(Node n)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| n | Node | nœud à vérifier pour voir s'il passe le filtre ou non. |

### Valeur de retour

une constante permettant de déterminer si le nœud est accepté, rejeté ou ignoré, comme défini ci‑dessus.

### Voir aussi

* class [Node](../../../com.aspose.html.dom/node/)
* class [NodeFilter](../)
* package [com.aspose.html.dom.traversal.filters](../../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../../)
