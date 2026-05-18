---
title: "Node.RemoveChild"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Node. La méthode removeChild de l'interface Node supprime un nœud enfant du DOM et renvoie le nœud supprimé."
type: docs

url: /fr/java/com.aspose.html.dom/node/removechild/
---
## Node.RemoveChild method

La méthode removeChild() de l'interface Node supprime un nœud enfant du DOM et renvoie le nœud supprimé.

Remarque : tant qu'une référence au nœud supprimé est conservée, il reste en mémoire, mais ne fait plus partie du DOM. Il peut encore être réutilisé plus tard dans le code. Si la valeur de retour de removeChild() n'est pas stockée et qu'aucune autre référence n'est maintenue, il sera automatiquement supprimé de la mémoire après un court délai.

```java
public Node RemoveChild(Node child)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| child | Node | Un [`Node`](../) qui est le nœud enfant à supprimer du DOM. |

### Valeur de retour

Contrairement à [`Node.cloneNode()`](../clonenode/), la valeur de retour conserve les objets [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/) associés.

### Voir aussi

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
