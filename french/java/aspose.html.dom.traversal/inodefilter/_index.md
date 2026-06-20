---
title: "Interface INodeFilter"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.dom.traversal.INodeFilter. Les filtres sont des objets qui savent comment filtrer les nœuds. Si un NodeIterator ou un TreeWalker reçoit un NodeFilter, il applique le filtre avant de renvoyer le nœud suivant. Si le filtre indique d’accepter le nœud, la logique de traversée le renvoie ; sinon la traversée recherche le nœud suivant et fait comme si le nœud rejeté n’existait pas."
type: docs

url: /fr/java/com.aspose.html.dom.traversal/inodefilter/
---
## INodeFilter interface

Les filtres sont des objets qui savent comment « filtrer » les nœuds. Si un NodeIterator ou un TreeWalker reçoit un NodeFilter, il applique le filtre avant de renvoyer le nœud suivant. Si le filtre indique d'accepter le nœud, la logique de parcours le renvoie ; sinon, le parcours recherche le nœud suivant et fait comme si le nœud rejeté n'existait pas.

Le DOM ne fournit aucun filtre. NodeFilter n’est qu’une interface que les utilisateurs peuvent implémenter pour fournir leurs propres filtres.

Les NodeFilters n’ont pas besoin de savoir comment traverser d’un nœud à l’autre, ni de connaître la structure de données traversée. Cela rend l’écriture de filtres très simple, car la seule chose qu’ils doivent savoir faire est d’évaluer un seul nœud. Un filtre peut être utilisé avec plusieurs types de traversées, favorisant la réutilisation du code.

Voir également la [Spécification du modèle d’objet Document (DOM) Niveau 2 – Traversal et Range](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface INodeFilter
```

## Méthodes

| Nom | Description |
| --- | --- |
| [acceptNode](../../com.aspose.html.dom.traversal/inodefilter/acceptnode/)(Node) | Vérifie si un nœud spécifié est visible dans la vue logique d’un TreeWalker ou d’un NodeIterator. Cette fonction sera appelée par l’implémentation de TreeWalker et NodeIterator ; elle n’est généralement pas appelée directement depuis le code utilisateur. (Bien que vous puissiez le faire si vous souhaitez utiliser le même filtre pour guider la logique de votre application.) |

### Voir aussi

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
