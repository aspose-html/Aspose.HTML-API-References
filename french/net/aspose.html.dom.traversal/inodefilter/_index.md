---
title: Interface INodeFilter
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Dom.Traversal.INodeFilter interface. Les filtres sont des objets qui savent comment filtrer les nœuds. Si un NodeIterator ou TreeWalker reçoit un NodeFilter il applique le filtre avant de renvoyer le nœud suivant. Si le filtre dit daccepter le nœud la logique de traversée le renvoie  sinon la traversée recherche le nœud suivant et prétend que le nœud qui a été rejeté nétait pas là.
type: docs
weight: 2490
url: /fr/net/aspose.html.dom.traversal/inodefilter/
---
## INodeFilter interface

Les filtres sont des objets qui savent comment "filtrer" les nœuds. Si un NodeIterator ou TreeWalker reçoit un NodeFilter, il applique le filtre avant de renvoyer le nœud suivant. Si le filtre dit d'accepter le nœud, la logique de traversée le renvoie ; sinon, la traversée recherche le nœud suivant et prétend que le nœud qui a été rejeté n'était pas là.

Le DOM ne fournit aucun filtre. NodeFilter est juste une interface que les utilisateurs peuvent implémenter pour fournir leurs propres filtres.

Les NodeFilters n'ont pas besoin de savoir comment traverser de nœud à nœud, ni de savoir quoi que ce soit sur la structure de données que est traversée. Cela rend très facile l'écriture de filtres, puisque la seule chose qu'ils doivent savoir faire est d'évaluer un seul nœud. Un filtre peut être utilisé avec plusieurs types de parcours différents, encourageant la réutilisation du code.

Voir aussi le[Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @depuis le niveau DOM 2

```csharp
public interface INodeFilter
```

## Méthodes

| Nom | La description |
| --- | --- |
| [AcceptNode](../../aspose.html.dom.traversal/inodefilter/acceptnode/)(Node) | Teste si un nœud spécifié est visible dans la vue logique d'un TreeWalker ou NodeIterator. Cette fonction sera appelée par l'implémentation de TreeWalker et NodeIterator ; il n'est normalement pas appelé directement depuis le code utilisateur . (Bien que vous puissiez le faire si vous vouliez utiliser le même filtre pour guider votre propre logique d'application.) |

### Voir également

* espace de noms [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* Assemblée [Aspose.HTML](../../)


