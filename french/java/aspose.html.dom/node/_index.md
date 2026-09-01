---
title: "Classe Node"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.dom.Node. L’interface Node est le type de données principal pour l’ensemble du Document Object Model. Elle représente un nœud unique dans l’arbre du document. Bien que tous les objets implémentant l’interface Node exposent des méthodes pour gérer les enfants, tous les objets implémentant l’interface Node ne possèdent pas forcément d’enfants. Par exemple, les nœuds Text peuvent ne pas avoir d’enfants et ajouter des enfants à de tels nœuds entraîne le déclenchement d’une DOMException."
type: docs

url: /fr/java/com.aspose.html.dom/node/
---
## Node class

L'interface Node est le type de données principal pour l'ensemble du Document Object Model. Elle représente un nœud unique dans l'arbre du document. Bien que tous les objets implémentant l'interface Node exposent des méthodes pour gérer les enfants, tous les objets implémentant l'interface Node ne peuvent pas avoir d'enfants. Par exemple, les nœuds [`Text`](../text/) peuvent ne pas avoir d'enfants, et ajouter des enfants à de tels nœuds entraîne le déclenchement d'une [`DOMException`](../domexception/).

Les attributs [`nodeName`](./nodename/), [`nodeValue`](./nodevalue/) et les attributs sont inclus comme un mécanisme pour accéder aux informations du nœud sans effectuer de cast vers l'interface dérivée spécifique. Dans les cas où il n'existe pas de correspondance évidente de ces attributs pour un [`nodeType`](./nodetype/) spécifique (par ex., nodeValue pour un [`Element`](../element/) ou les attributs pour un [`Comment`](../comment/)), cela renvoie null. Notez que les interfaces spécialisées peuvent contenir des mécanismes supplémentaires et plus pratiques pour obtenir et définir les informations pertinentes.

```java
public abstract class Node : EventTarget, IXPathNSResolver
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) La propriété en lecture seule baseURI de l'interface Node renvoie l'URL de base absolue du document contenant le nœud. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) La propriété en lecture seule childNodes de l'interface Node renvoie une [`NodeList`](../../com.aspose.html.collections/nodelist/) dynamique des nœuds enfants de l'élément donné où le premier nœud enfant reçoit l'index 0. Les nœuds enfants comprennent les éléments, le texte et les commentaires. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) La propriété en lecture seule firstChild de l'interface `Node` renvoie le premier enfant du nœud dans l'arbre, ou null si le nœud n'a pas d'enfants. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) La propriété en lecture seule lastChild de l'interface `Node` renvoie le dernier enfant du nœud. Si son parent est un élément, alors l'enfant est généralement un nœud d'élément, un nœud de texte ou un nœud de commentaire. Il renvoie null s'il n'y a aucun élément enfant |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Renvoie la partie locale du nom qualifié de ce nœud. Pour les nœuds de tout type autre que [`ELEMENT_NODE`](./element_node/) et [`ATTRIBUTE_NODE`](./attribute_node/) et les nœuds créés avec une méthode DOM Niveau 1, telle que [`Document.createElement()`](../document/createelement/), cela renvoie toujours null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) La propriété en lecture seule Element.packageURI renvoie l'URI du package de l'élément, ou null si l'élément n'est pas dans un package. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) La propriété en lecture seule nextSibling de l'interface `Node` renvoie le nœud immédiatement suivant celui spécifié dans les [`childNodes`](./childnodes/) de son parent, ou renvoie null si le nœud spécifié est le dernier enfant de l'élément parent. |
| abstract [getNodeName](../../com.aspose.html.dom/node/nodename/) La propriété en lecture seule nodeName de Node renvoie le nom du nœud actuel sous forme de chaîne. |
| abstract [getNodeType](../../com.aspose.html.dom/node/nodetype/) Un code représentant le type de l'objet sous-jacent. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | La propriété nodeValue de l'interface `Node `renvoie ou définit la valeur du nœud actuel. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) La propriété en lecture seule ownerDocument de l'interface Node renvoie l'objet document de niveau supérieur du nœud. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) La propriété en lecture seule parentElement de l'interface `Node` renvoie le parent du nœud DOM [`Element`](../element/), ou null si le nœud n'a pas de parent, ou si son parent n'est pas un élément DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) La propriété en lecture seule parentNode de l'interface Node renvoie le parent du nœud spécifié dans l'arbre DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | La propriété en lecture seule prefix renvoie le préfixe du package de l'élément spécifié, ou null si aucun préfixe n'est spécifié. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) La propriété en lecture seule previousSibling de l'interface `Node` renvoie le nœud immédiatement précédant celui spécifié dans les [`childNodes`](./firstchild/) de son parent, ou null si le nœud spécifié est le premier de cette liste. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | La propriété textContent de l'interface `Node` représente le contenu textuel du nœud et de ses descendants. |

## Méthodes

| Nom | Description |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | La méthode addEventListener() de l'interface [`EventTarget `](../eventtarget/) configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | La méthode addEventListener() de l'interface [EventTarget ](T:com.aspose.html.dom.EventTarget) configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | La méthode addEventListener() de l'interface [EventTarget ](T:com.aspose.html.dom.EventTarget) configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | La méthode appendChild() de l'interface Node ajoute un nœud à la fin de la liste des enfants d'un nœud parent spécifié. Si l'enfant donné est une référence à un nœud existant dans le document, appendChild() le déplace de sa position actuelle vers la nouvelle position (il n'est pas nécessaire de supprimer le nœud de son nœud parent avant de l'ajouter à un autre nœud). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode)() | La méthode cloneNode() de l'interface Node renvoie un duplicata du nœud sur lequel cette méthode a été appelée. Son paramètre détermine si le sous‑arbre contenu dans le nœud est également cloné ou non. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode_1)(bool) | La méthode cloneNode() de l'interface Node renvoie un duplicata du nœud sur lequel cette méthode a été appelée. Son paramètre détermine si le sous‑arbre contenu dans le nœud est également cloné ou non. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Déclenche un Event sur le [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) spécifié, (synchroniquement) en invoquant les EventListeners concernés dans l'ordre approprié. Les règles normales de traitement des événements (y compris les phases de capture et de bouillonnement optionnelles) s'appliquent également aux événements déclenchés manuellement avec [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Effectue les tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | La méthode hasChildNodes() de l'interface Node renvoie une valeur booléenne indiquant si le `Node` donné possède des nœuds enfants ou non. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | La méthode insertBefore() de l'interface Node insère un nœud avant un nœud de référence en tant qu'enfant d'un nœud parent spécifié. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | La méthode isDefaultNamespace() de l'interface Node accepte un URI de package en argument. Elle renvoie une valeur booléenne qui est true si le package est le package par défaut sur le nœud donné et false sinon. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | La méthode isEqualNode() de l'interface `Node` teste si deux nœuds sont égaux. Deux nœuds sont égaux lorsqu'ils ont le même type, les mêmes caractéristiques définissant (pour les éléments, cela serait leur ID, le nombre d'enfants, etc.), leurs attributs correspondent, etc. L'ensemble spécifique de points de données qui doivent correspondre varie selon les types de nœuds. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | La méthode isSameNode() de l'interface Node est un alias hérité de l'opérateur d'égalité stricte ===. Autrement dit, elle teste si deux nœuds sont identiques (c'est‑à‑dire s'ils font référence au même objet). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | La méthode lookupNamespaceURI() de l'interface Node prend un préfixe en paramètre et renvoie l'URI de package qui lui est associé sur le nœud donné si trouvé (et null sinon). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | La méthode lookupPrefix() de l'interface Node renvoie une chaîne contenant le préfixe d'un URI de package donné, si présent, et null sinon. Lorsque plusieurs préfixes sont possibles, le premier préfixe est renvoyé. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Place tous les nœuds [`Text`](../text/) à la profondeur maximale du sous-arbre sous ce Node, y compris les nœuds d'attribut, dans une forme « normale » où seule la structure (par ex., les [`elements`](../element/), les [`comments`](../comment/), les [`processing instructions`](../processinginstruction/), les [`CDATA sections`](../cdatasection/), et les [`entity references`](../entityreference/)) sépare les nœuds [`Text`](../text/), c’est‑à‑dire qu'il n'existe ni nœuds Text adjacents ni nœuds Text vides. Cela peut être utilisé pour garantir que la vue DOM d'un document est identique à celle d'un document enregistré puis rechargé, et est utile lorsque des opérations (telles que les recherches XPointer [XPointer]) qui dépendent d'une structure d'arbre de document particulière doivent être utilisées. Si le paramètre "normalize-characters" de l'objet [`DOMConfiguration`](../../com.aspose.html/configuration/) attaché au [`Node.ownerDocument`](./ownerdocument/) est vrai, cette méthode normalisera également complètement les caractères des nœuds Text. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | La méthode removeChild() de l'interface Node supprime un nœud enfant du DOM et renvoie le nœud supprimé. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Remplace le nœud enfant oldChild par newChild dans la liste des enfants, et renvoie le nœud oldChild. Si newChild est un objet [`DocumentFragment`](../documentfragment/), oldChild est remplacé par tous les enfants du [`DocumentFragment`](../documentfragment/), insérés dans le même ordre. Si newChild est déjà dans l'arbre, il est d'abord supprimé. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [ATTRIBUTE_NODE](../../com.aspose.html.dom/node/attribute_node/) | Un [`Attribute`](../attr/) d'un [`Element`](../element/). |
| const [CDATA_SECTION_NODE](../../com.aspose.html.dom/node/cdata_section_node/) | Une [`CDATASection`](../cdatasection/), telle que &lt;!CDATA[[ … ]]&gt;. |
| const [COMMENT_NODE](../../com.aspose.html.dom/node/comment_node/) | Un nœud [`Comment`](../comment/), tel que &lt;!-- … --&gt;. |
| const [DOCUMENT_FRAGMENT_NODE](../../com.aspose.html.dom/node/document_fragment_node/) | Un nœud [`DocumentFragment`](../documentfragment/). |
| const [DOCUMENT_NODE](../../com.aspose.html.dom/node/document_node/) | Un nœud [`Document`](../document/). |
| const [DOCUMENT_TYPE_NODE](../../com.aspose.html.dom/node/document_type_node/) | Un nœud [`DocumentType`](../documenttype/), tel que &lt;!DOCTYPE html&gt;. |
| const [ELEMENT_NODE](../../com.aspose.html.dom/node/element_node/) | Un nœud [`Element`](../element/) comme &lt;p&gt; ou &lt;div&gt;. |
| const [ENTITY_NODE](../../com.aspose.html.dom/node/entity_node/) | Un nœud [`Entity`](../entity/). |
| const [ENTITY_REFERENCE_NODE](../../com.aspose.html.dom/node/entity_reference_node/) | Un nœud [`EntityReference`](../entityreference/). |
| const [NOTATION_NODE](../../com.aspose.html.dom/node/notation_node/) | Un nœud [`Notation`](../notation/). |
| const [PROCESSING_INSTRUCTION_NODE](../../com.aspose.html.dom/node/processing_instruction_node/) | Une [`ProcessingInstruction`](../processinginstruction/) d'un document XML, comme &lt;?xml-stylesheet … ?&gt;. |
| const [TEXT_NODE](../../com.aspose.html.dom/node/text_node/) | Le texte réel [`Text`](../text/) à l'intérieur d'un [`Element`](../element/) ou d'un [`Attr`](../attr/). |

## Remarques

Référence :

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # interface-node](https://dom.spec.whatwg.org/#interface-node).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Voir aussi

* class [EventTarget](../eventtarget/)
* interface [IXPathNSResolver](../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
