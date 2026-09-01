---
title: "Node.InsertBefore"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Node. La méthode insertBefore de l'interface Node insère un nœud avant un nœud de référence en tant qu'enfant d'un nœud parent spécifié."
type: docs

url: /fr/java/com.aspose.html.dom/node/insertbefore/
---
## Node.InsertBefore method

La méthode insertBefore() de l'interface Node insère un nœud avant un nœud de référence en tant qu'enfant d'un nœud parent spécifié.

Si le nœud fourni existe déjà dans le document, insertBefore() le déplace de sa position actuelle vers la nouvelle position. (C’est-à-dire qu’il sera automatiquement retiré de son parent existant avant d’être ajouté au nouveau parent spécifié.)

Cela signifie qu'un nœud ne peut pas se trouver simultanément à deux emplacements du document.

```java
public Node InsertBefore(Node node, Node child)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nœud | Node | Le nœud à insérer. |
| enfant | Node | Le nœud devant lequel newNode est inséré. Si cette valeur est null, alors newNode est inséré à la fin des nœuds enfants du nœud. |

### Valeur de retour

Renvoie l'enfant ajouté (à moins que newNode ne soit un [`DocumentFragment`](../../documentfragment/), auquel cas le [`DocumentFragment`](../../documentfragment/) vide est renvoyé).

### Voir aussi

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
