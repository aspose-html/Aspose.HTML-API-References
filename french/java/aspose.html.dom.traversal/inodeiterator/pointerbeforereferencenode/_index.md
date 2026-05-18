---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Propriété INodeIterator. La valeur de ce drapeau détermine si les enfants des nœuds de référence d'entité sont visibles pour l'itérateur. Si false, ils et leurs descendants seront rejetés. Notez que ce rejet a priorité sur whatToShow et le filtre. Notez également que c'est actuellement la seule situation où les NodeIterators peuvent rejeter un sous‑arbre complet plutôt que d'ignorer des nœuds individuels. Pour produire une vue du document avec les références d'entité développées et ne pas exposer le nœud de référence d'entité lui‑même, utilisez les drapeaux whatToShow pour masquer le nœud de référence d'entité et définissez expandEntityReferences sur true lors de la création de l'itérateur. Pour produire une vue du document avec des nœuds de référence d'entité mais sans expansion d'entité, utilisez les drapeaux whatToShow pour afficher le nœud de référence d'entité et définissez expandEntityReferences sur false."
type: docs

url: /fr/java/com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

La valeur de ce drapeau détermine si les enfants des nœuds de référence d'entité sont visibles pour l'itérateur. Si false, ils et leurs descendants seront rejetés. Notez que ce rejet a priorité sur whatToShow et le filtre. Notez également que c'est actuellement la seule situation où les NodeIterators peuvent rejeter un sous‑arbre complet plutôt que d'ignorer des nœuds individuels. Pour produire une vue du document avec les références d'entité développées et ne pas exposer le nœud de référence d'entité, utilisez les drapeaux whatToShow pour masquer le nœud de référence d'entité et définissez expandEntityReferences sur true lors de la création de l'itérateur. Pour produire une vue du document avec des nœuds de référence d'entité mais sans expansion d'entité, utilisez les drapeaux whatToShow pour afficher le nœud de référence d'entité et définissez expandEntityReferences sur false.

```java
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` si [expand entity references] ; sinon, `false`.

### Voir aussi

* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
