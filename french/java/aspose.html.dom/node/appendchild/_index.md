---
title: "Node.AppendChild"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Node. La méthode appendChild de l'interface Node ajoute un nœud à la fin de la liste des enfants d'un nœud parent spécifié. Si l'enfant fourni est une référence à un nœud existant dans le document, appendChild le déplace de sa position actuelle vers la nouvelle position ; il n'est pas nécessaire de retirer le nœud de son nœud parent avant de l'ajouter à un autre nœud."
type: docs

url: /fr/java/com.aspose.html.dom/node/appendchild/
---
## Node.AppendChild method

La méthode appendChild() de l'interface Node ajoute un nœud à la fin de la liste des enfants d'un nœud parent spécifié. Si l'enfant donné est une référence à un nœud existant dans le document, appendChild() le déplace de sa position actuelle vers la nouvelle position (il n'est pas nécessaire de supprimer le nœud de son nœud parent avant de l'ajouter à un autre nœud).

Cela signifie qu'un nœud ne peut pas se trouver à deux endroits du document simultanément. Ainsi, si le nœud possède déjà un parent, il est d'abord retiré, puis ajouté à la nouvelle position. La méthode [`Node.cloneNode()`](../clonenode/) peut être utilisée pour créer une copie du nœud avant de l'ajouter sous le nouveau parent. Les copies réalisées avec [`cloneNode`](../clonenode/) ne sont pas automatiquement synchronisées.

```java
public Node AppendChild(Node node)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nœud | Node | Le nœud à ajouter au nœud parent donné (généralement un élément). |

### Valeur de retour

Un nœud qui est l'enfant ajouté (aChild), sauf lorsque aChild est un [`DocumentFragment`](../../documentfragment/), auquel cas le [`DocumentFragment`](../../documentfragment/) vide est renvoyé.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../domexception/) | Lancée lorsque les contraintes de l'arbre DOM sont violées. |

### Voir aussi

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
