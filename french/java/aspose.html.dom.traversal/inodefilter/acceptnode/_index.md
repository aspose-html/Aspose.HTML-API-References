---
title: "INodeFilter.AcceptNode"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode INodeFilter. Teste si un nœud spécifié est visible dans la vue logique d'un TreeWalker ou d'un NodeIterator. Cette fonction sera appelée par l'implémentation de TreeWalker et NodeIterator, elle n'est normalement pas appelée directement depuis le code utilisateur. Vous pouvez toutefois le faire si vous souhaitez utiliser le même filtre pour guider la logique de votre propre application."
type: docs

url: /fr/java/com.aspose.html.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

Vérifie si un nœud spécifié est visible dans la vue logique d’un TreeWalker ou d’un NodeIterator. Cette fonction sera appelée par l’implémentation de TreeWalker et NodeIterator ; elle n’est généralement pas appelée directement depuis le code utilisateur. (Bien que vous puissiez le faire si vous souhaitez utiliser le même filtre pour guider la logique de votre application.)

```java
public short AcceptNode(Node n)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| n | Node | nœud à vérifier pour voir s'il passe le filtre ou non. |

### Valeur de retour

une constante permettant de déterminer si le nœud est accepté, rejeté ou ignoré, comme défini ci‑dessus.

### Voir aussi

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
