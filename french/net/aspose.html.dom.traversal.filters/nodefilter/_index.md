---
title: NodeFilter
second_title: Référence de l'API Aspose.HTML pour .NET
description: Les filtres sont des objets qui savent filtrer les nœuds.
type: docs
weight: 2470
url: /fr/net/aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Les filtres sont des objets qui savent "filtrer" les nœuds.

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Méthodes

| Nom | La description |
| --- | --- |
| abstract [AcceptNode](../../aspose.html.dom.traversal.filters/nodefilter/acceptnode)(Node) | Teste si un nœud spécifié est visible dans la vue logique d'un TreeWalker ou NodeIterator. Cette fonction sera appelée par l'implémentation de TreeWalker et NodeIterator ; il n'est normalement pas appelé directement à partir du code utilisateur . (Bien que vous puissiez le faire si vous vouliez utiliser le même filtre pour guider votre propre logique d'application.) |
| override [GetPlatformType](../../aspose.html.dom.traversal.filters/nodefilter/getplatformtype)() | Cette méthode est utilisée pour récupérer l'objet ECMAScriptType . |

## Des champs

| Nom | La description |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.html.dom.traversal.filters/nodefilter/filter_accept) | Acceptez le nœud. Les méthodes de navigation définies pour NodeIterator ou TreeWalker renverront ce nœud . |
| const [FILTER_REJECT](../../aspose.html.dom.traversal.filters/nodefilter/filter_reject) | Rejeter le nœud. Les méthodes de navigation définies pour NodeIterator ou TreeWalker ne renverront pas ce nœud. Pour TreeWalker, les enfants de ce nœud seront également rejetés. Les NodeIterators traitent cela comme un synonyme de FILTER_SKIP. |
| const [FILTER_SKIP](../../aspose.html.dom.traversal.filters/nodefilter/filter_skip) | Ignorez ce nœud unique. Les méthodes de navigation définies pour NodeIterator ou TreeWalker ne renverront pas ce nœud. Pour NodeIterator et TreeWalker, les enfants de ce nœud seront toujours pris en compte. |
| const [SHOW_ALL](../../aspose.html.dom.traversal.filters/nodefilter/show_all) | Afficher tous les nœuds. |
| const [SHOW_ATTRIBUTE](../../aspose.html.dom.traversal.filters/nodefilter/show_attribute) | Afficher les nœuds Attr. Cela n'a de sens que lors de la création d'un itérateur ou d'un arborescence avec un nœud d'attribut comme racine ; dans ce cas, cela signifie que le nœud d'attribut apparaîtra en première position de l'itération ou du parcours. Étant donné que les attributs ne sont jamais des enfants d'autres nœuds, ils n'apparaissent pas lors de la traversée de l'arborescence du document. |
| const [SHOW_CDATA_SECTION](../../aspose.html.dom.traversal.filters/nodefilter/show_cdata_section) | Afficher les nœuds de la section CDATA. |
| const [SHOW_COMMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_comment) | Afficher les nœuds de commentaire. |
| const [SHOW_DOCUMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document) | Afficher les nœuds de document. |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document_fragment) | Afficher les nœuds DocumentFragment. |
| const [SHOW_DOCUMENT_TYPE](../../aspose.html.dom.traversal.filters/nodefilter/show_document_type) | Afficher les nœuds DocumentType. |
| const [SHOW_ELEMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_element) | Afficher les nœuds d'élément. |
| const [SHOW_ENTITY](../../aspose.html.dom.traversal.filters/nodefilter/show_entity) | Afficher les nœuds d'entité. Cela n'a de sens que lors de la création d'un itérateur ou d'un arborescence avec un nœud Entity comme racine ; dans ce cas, cela signifie que le nœud Entity apparaîtra en première position du parcours. Étant donné que les entités ne font pas partie de l'arborescence du document, elles n'apparaissent pas lorsque parcourt l'arborescence du document. |
| const [SHOW_ENTITY_REFERENCE](../../aspose.html.dom.traversal.filters/nodefilter/show_entity_reference) | Afficher les nœuds EntityReference. |
| const [SHOW_NOTATION](../../aspose.html.dom.traversal.filters/nodefilter/show_notation) | Afficher les nœuds de notation. Cela n'a de sens que lors de la création d'un itérateur ou d'un arborescence avec un nœud Notation comme racine ; dans ce cas, cela signifie que le nœud Notation apparaîtra en première position du parcours . Étant donné que les notations ne font pas partie de l'arborescence du document, elles n'apparaissent pas lors de la traversée de l'arborescence du document. |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction) | Afficher les nœuds ProcessingInstruction. |
| const [SHOW_TEXT](../../aspose.html.dom.traversal.filters/nodefilter/show_text) | Afficher les nœuds de texte. |

### Voir également

* class [DOMObject](../../aspose.html.dom/domobject)
* interface [INodeFilter](../../aspose.html.dom.traversal/inodefilter)
* espace de noms [Aspose.Html.Dom.Traversal.Filters](../../aspose.html.dom.traversal.filters)
* Assemblée [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
