---
title: INodeIterator.PointerBeforeReferenceNode
second_title: Référence de l'API Aspose.HTML pour .NET
description: INodeIterator propriété. La valeur de cet indicateur détermine si les enfants des nœuds de référence entity sont visibles pour litérateur. Si faux ils et leurs descendants seront rejetés. Notez que ce rejet prend priorité sur whatToShow et le filtre. Notez également quil sagit actuellement de la seule situation où NodeIterators peut rejeter une sousarborescence complète plutôt que ignorer des nœuds individuels. Pour produire une vue du document qui a des références dentité développées et nexpose pas le nœud de référence dentité luimême utilisez les indicateurs whatToShow pour masquez la référence dentité node et définissez expandEntityReferences sur true lors de la création de litérateur . Pour produire une vue du document qui a des nœuds dentité reference mais pas dexpansion dentité utilisez le whatToShow flags pour afficher le nœud de référence dentité et set expandEntityReferences sur false.
type: docs
weight: 10
url: /fr/net/aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

La valeur de cet indicateur détermine si les enfants des nœuds de référence entity sont visibles pour l'itérateur. Si faux, ils et leurs descendants seront rejetés. Notez que ce rejet prend priorité sur whatToShow et le filtre. Notez également qu'il s'agit actuellement de la seule situation où NodeIterators peut rejeter une sous-arborescence complète plutôt que ignorer des nœuds individuels. Pour produire une vue du document qui a des références d'entité développées et n'expose pas le nœud de référence d'entité lui-même, utilisez les indicateurs whatToShow pour masquez la référence d'entité node et définissez expandEntityReferences sur true lors de la création de l'itérateur . Pour produire une vue du document qui a des nœuds d'entité reference mais pas d'expansion d'entité, utilisez le whatToShow flags pour afficher le nœud de référence d'entité et set expandEntityReferences sur false.

```csharp
public bool PointerBeforeReferenceNode { get; }
```

### Valeur de la propriété

`vrai`if [développer les références d'entité] ; sinon,`FAUX` .

### Voir également

* interface [INodeIterator](../)
* espace de noms [Aspose.Html.Dom.Traversal](../../inodeiterator/)
* Assemblée [Aspose.HTML](../../../)


