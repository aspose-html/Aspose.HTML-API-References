---
title: "Classe NodeFilter"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.dom.traversal.filters.NodeFilter. Les filtres sont des objets qui savent comment filtrer les nœuds"
type: docs

url: /fr/java/com.aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Les filtres sont des objets qui savent comment "filtrer" les nœuds.

```java
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Méthodes

| Nom | Description |
| --- | --- |
| abstract [AcceptNode](../../com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | Vérifie si un nœud spécifié est visible dans la vue logique d’un TreeWalker ou d’un NodeIterator. Cette fonction sera appelée par l’implémentation de TreeWalker et NodeIterator ; elle n’est généralement pas appelée directement depuis le code utilisateur. (Bien que vous puissiez le faire si vous souhaitez utiliser le même filtre pour guider la logique de votre application.) |
| [getPlatformType](../../com.aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | Cette méthode est utilisée pour récupérer le type d'objet ECMAScript. |

## Champs

| Nom | Description |
| --- | --- |
| const [FILTER_ACCEPT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | Accepter le nœud. Les méthodes de navigation définies pour NodeIterator ou TreeWalker renverront ce nœud. |
| const [FILTER_REJECT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | Rejeter le nœud. Les méthodes de navigation définies pour NodeIterator ou TreeWalker ne renverront pas ce nœud. Pour TreeWalker, les enfants de ce nœud seront également rejetés. Les NodeIterators considèrent cela comme un synonyme de FILTER_SKIP. |
| const [FILTER_SKIP](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | Ignorer ce nœud unique. Les méthodes de navigation définies pour NodeIterator ou TreeWalker ne renverront pas ce nœud. Pour les deux, NodeIterator et TreeWalker, les enfants de ce nœud seront toujours pris en compte. |
| const [SHOW_ALL](../../com.aspose.html.dom.traversal.filters/nodefilter/show_all/) | Afficher tous les nœuds. |
| const [SHOW_ATTRIBUTE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | Afficher les nœuds Attr. Cela n'a de sens que lors de la création d'un itérateur ou d'un tree-walker avec un nœud d'attribut comme racine ; dans ce cas, cela signifie que le nœud d'attribut apparaîtra en première position de l'itération ou du parcours. Étant donné que les attributs ne sont jamais des enfants d'autres nœuds, ils n'apparaissent pas lors du parcours de l'arbre du document. |
| const [SHOW_CDATA_SECTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | Afficher les nœuds CDATASection. |
| const [SHOW_COMMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_comment/) | Afficher les nœuds Comment. |
| const [SHOW_DOCUMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document/) | Afficher les nœuds Document. |
| const [SHOW_DOCUMENT_FRAGMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | Afficher les nœuds DocumentFragment. |
| const [SHOW_DOCUMENT_TYPE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | Afficher les nœuds DocumentType. |
| const [SHOW_ELEMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_element/) | Afficher les nœuds Element. |
| const [SHOW_ENTITY](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity/) | Afficher les nœuds Entity. Cela n'a de sens que lors de la création d'un itérateur ou d'un tree-walker avec un nœud Entity comme racine ; dans ce cas, cela signifie que le nœud Entity apparaîtra en première position du parcours. Étant donné que les entités ne font pas partie de l'arbre du document, elles n'apparaissent pas lors du parcours de l'arbre du document. |
| const [SHOW_ENTITY_REFERENCE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | Afficher les nœuds EntityReference. |
| const [SHOW_NOTATION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_notation/) | Afficher les nœuds Notation. Cela n’a de sens que lors de la création d’un itérateur ou d’un arbre‑parcourir avec un nœud Notation comme racine ; dans ce cas, cela signifie que le nœud Notation apparaîtra en première position du parcours. Étant donné que les notations ne font pas partie de l’arbre du document, elles n’apparaissent pas lors du parcours de l’arbre du document. |
| const [SHOW_PROCESSING_INSTRUCTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | Afficher les nœuds ProcessingInstruction. |
| const [SHOW_TEXT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_text/) | Afficher les nœuds Text. |

### Voir aussi

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [INodeFilter](../../com.aspose.html.dom.traversal/inodefilter/)
* package [com.aspose.html.dom.traversal.filters](../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../)
