---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Propriété INodeIterator. La valeur de ce flag détermine si les enfants des nœuds de référence d'entité sont visibles pour l'itérateur. Si false, ils et leurs descendants seront rejetés. Notez que ce rejet a priorité sur whatToShow et le filtre. Notez également que c'est actuellement la seule situation où les NodeIterators peuvent rejeter un sous‑arbre complet plutôt que d'ignorer des nœuds individuels. Pour produire une vue du document où les références d'entité sont développées et ne pas exposer le nœud de référence d'entité lui‑même, utilisez les flags whatToShow pour masquer le nœud de référence d'entité et définissez expandEntityReferences à true lors de la création de l'itérateur. Pour produire une vue du document contenant des nœuds de référence d'entité mais sans expansion d'entité, utilisez les flags whatToShow pour afficher le nœud de référence d'entité et définissez expandEntityReferences à false."
type: docs

url: /fr/java/com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

La valeur de ce flag détermine si les enfants des nœuds de référence d'entité sont visibles pour l'itérateur. Si false, ils et leurs descendants seront rejetés. Notez que ce rejet a priorité sur whatToShow et le filtre. Notez également que c'est actuellement la seule situation où les NodeIterators peuvent rejeter un sous‑arbre complet plutôt que d'ignorer des nœuds individuels. Pour produire une vue du document où les références d'entité sont développées et ne pas exposer le nœud de référence d'entité, utilisez les flags whatToShow pour masquer le nœud de référence d'entité et définissez expandEntityReferences à true lors de la création de l'itérateur. Pour produire une vue du document contenant des nœuds de référence d'entité mais sans expansion d'entité, utilisez les flags whatToShow pour afficher le nœud de référence d'entité et définissez expandEntityReferences à false.

```java
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` si [expand entity references] ; sinon, `false`.

### Voir aussi

* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
