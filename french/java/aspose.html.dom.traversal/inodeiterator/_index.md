---
title: "Interface INodeIterator"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.dom.traversal.INodeIterator. Les itérateurs sont utilisés pour parcourir un ensemble de nœuds, par exemple l'ensemble des nœuds d'une NodeList, le sous-arbre du document régi par un nœud particulier, les résultats d'une requête ou tout autre ensemble de nœuds. L'ensemble de nœuds à itérer est déterminé par l'implémentation du NodeIterator. Le DOM Niveau 2 spécifie une implémentation unique de NodeIterator pour le parcours en ordre de document d'un sous-arbre du document. Les instances de ces itérateurs sont créées en appelant DocumentTraversal .createNodeIterator"
type: docs

url: /fr/java/com.aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

Les itérateurs sont utilisés pour parcourir un ensemble de nœuds, par exemple l'ensemble des nœuds d'une NodeList, le sous-arbre du document régi par un nœud particulier, les résultats d'une requête, ou tout autre ensemble de nœuds. L'ensemble de nœuds à itérer est déterminé par l'implémentation du NodeIterator. Le DOM Niveau 2 spécifie une implémentation unique de NodeIterator pour le parcours en ordre du document d'un sous-arbre du document. Les instances de ces itérateurs sont créées en appelant DocumentTraversal .createNodeIterator().

Voir également la [Spécification du modèle d’objet Document (DOM) Niveau 2 – Traversal et Range](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface INodeIterator : ITraversal
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getPointerBeforeReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) La valeur de ce drapeau détermine si les enfants des nœuds de référence d'entité sont visibles pour l'itérateur. Si false, ils et leurs descendants seront rejetés. Notez que ce rejet a priorité sur whatToShow et le filtre. Notez également que c'est actuellement la seule situation où les NodeIterators peuvent rejeter un sous-arbre complet plutôt que d'ignorer des nœuds individuels. Pour produire une vue du document avec les références d'entité développées et ne pas exposer le nœud de référence d'entité lui‑même, utilisez les drapeaux whatToShow pour masquer le nœud de référence d'entité et définissez expandEntityReferences à true lors de la création de l'itérateur. Pour produire une vue du document contenant des nœuds de référence d'entité mais sans expansion d'entité, utilisez les drapeaux whatToShow pour afficher le nœud de référence d'entité et définissez expandEntityReferences à false. |
| [getReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/referencenode/) Le nœud de référence actuel. |

## Méthodes

| Nom | Description |
| --- | --- |
| [detach](../../com.aspose.html.dom.traversal/inodeiterator/detach/)() | Détache le NodeIterator de l'ensemble qu'il a parcouru, libérant toutes les ressources computationnelles et plaçant l'itérateur dans l'état INVALID. Après l'appel de detach, les appels à nextNode ou previousNode lèveront l'exception INVALID_STATE_ERR. |
| [nextNode](../../com.aspose.html.dom.traversal/inodeiterator/nextnode/)() | Renvoie le nœud suivant dans l'ensemble et avance la position de l'itérateur dans l'ensemble. Après la création d'un NodeIterator, le premier appel à nextNode() renvoie le premier nœud de l'ensemble. |
| [previousNode](../../com.aspose.html.dom.traversal/inodeiterator/previousnode/)() | Renvoie le nœud précédent dans l'ensemble et déplace la position du NodeIterator en arrière dans l'ensemble. |

### Voir aussi

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
