---
title: "Classe Attr"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.dom.Attr. L'interface Attr représente un attribut dans un objet Element. Typiquement, les valeurs autorisées pour l'attribut sont définies dans un schéma associé au document."
type: docs

url: /fr/java/com.aspose.html.dom/attr/
---
## Attr class

L'interface Attr représente un attribut dans un objet Element. Généralement, les valeurs autorisées pour l'attribut sont définies dans un schéma associé au document.

```java
public sealed class Attr : Node
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) La propriété en lecture seule baseURI de l'interface Node renvoie l'URL de base absolue du document contenant le nœud. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) La propriété en lecture seule childNodes de l'interface Node renvoie une [`NodeList`](../../com.aspose.html.collections/nodelist/) dynamique des nœuds enfants de l'élément donné où le premier nœud enfant reçoit l'index 0. Les nœuds enfants comprennent les éléments, le texte et les commentaires. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) La propriété en lecture seule firstChild de l'interface [`Node`](../node/) renvoie le premier enfant du nœud dans l'arbre, ou null si le nœud n'a aucun enfant. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) La propriété en lecture seule lastChild de l'interface [`Node`](../node/) renvoie le dernier enfant du nœud. Si son parent est un élément, l'enfant est généralement un nœud d'élément, un nœud texte ou un nœud commentaire. Elle renvoie null s'il n'y a aucun élément enfant. |
| [getLocalName](../../com.aspose.html.dom/attr/localname/) Renvoie la partie locale du nom qualifié de ce nœud. Pour les nœuds de tout type autre que ELEMENT_NODE et ATTRIBUTE_NODE et les nœuds créés avec une méthode DOM Niveau 1, comme Document.createElement(), c'est toujours null. |
| [getName](../../com.aspose.html.dom/attr/name/) Renvoie le nom de cet attribut. |
| [getNamespaceURI](../../com.aspose.html.dom/attr/packageuri/) L'URI du package de ce nœud, ou null s'il n'est pas spécifié. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) La propriété en lecture seule nextSibling de l'interface [`Node`](../node/) renvoie le nœud immédiatement suivant le nœud spécifié dans le [`childNodes`](../node/childnodes/) de leur parent, ou renvoie null si le nœud spécifié est le dernier enfant de l'élément parent. |
| [getNodeName](../../com.aspose.html.dom/attr/nodename/) Le nom de ce nœud, selon son type. |
| [getNodeType](../../com.aspose.html.dom/attr/nodetype/) Un code représentant le type de l'objet sous-jacent. |
| [nodeValue](../../com.aspose.html.dom/attr/nodevalue/) { get; set; } | La valeur de ce nœud, selon son type. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) La propriété en lecture seule ownerDocument de l'interface Node renvoie l'objet document de niveau supérieur du nœud. |
| [getOwnerElement](../../com.aspose.html.dom/attr/ownerelement/) Le nœud Element auquel cet attribut est attaché ou null si cet attribut n'est pas utilisé. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) La propriété en lecture seule parentElement de l'interface [`Node`](../node/) renvoie le parent [`Element`](../element/) du nœud DOM, ou null si le nœud n'a pas de parent ou si son parent n'est pas un Element DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) La propriété en lecture seule parentNode de l'interface Node renvoie le parent du nœud spécifié dans l'arbre DOM. |
| [getPrefix](../../com.aspose.html.dom/attr/prefix/) Le préfixe du package de ce nœud, ou null s'il n'est pas spécifié. Lorsqu'il est défini à null, le définir n'a aucun effet. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) La propriété en lecture seule previousSibling de l'interface [`Node`](../node/) renvoie le nœud immédiatement précédant le nœud spécifié dans la liste [`childNodes`](../node/firstchild/) de son parent, ou null si le nœud spécifié est le premier de cette liste. |
| [getSpecified](../../com.aspose.html.dom/attr/specified/) Vrai si cet attribut a explicitement reçu une valeur dans le document d'instance, faux sinon. |
| [textContent](../../com.aspose.html.dom/attr/textcontent/) { get; set; } | Cet attribut renvoie le contenu texte de ce nœud et de ses descendants. Lorsqu'il est défini à null, le définir n'a aucun effet. Lors de la définition, tous les enfants éventuels que ce nœud pourrait avoir sont supprimés et, si la nouvelle chaîne n'est pas vide ou null, remplacés par un seul nœud Text contenant la chaîne à laquelle cet attribut est assigné. |
[getValue]
[setValue] On retrieval, the value of the attribute is returned as a String. |

## Méthodes

| Nom | Description |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | La méthode addEventListener() de l'interface [`EventTarget `](../eventtarget/) configure une fonction qui sera appelée chaque fois que l'événement spécifié est livré à la cible. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | La méthode addEventListener() de l'interface [EventTarget ](T:com.aspose.html.dom.EventTarget) configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | La méthode addEventListener() de l'interface [EventTarget ](T:com.aspose.html.dom.EventTarget) configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | La méthode appendChild() de l'interface Node ajoute un nœud à la fin de la liste des enfants d'un nœud parent spécifié. Si l'enfant donné est une référence à un nœud existant dans le document, appendChild() le déplace de sa position actuelle vers la nouvelle position (il n'est pas nécessaire de supprimer le nœud de son nœud parent avant de l'ajouter à un autre nœud). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | La méthode cloneNode() de l'interface Node renvoie un duplicata du nœud sur lequel cette méthode a été appelée. Son paramètre détermine si le sous‑arbre contenu dans le nœud est également cloné ou non. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | La méthode cloneNode() de l'interface Node renvoie un duplicata du nœud sur lequel cette méthode a été appelée. Son paramètre détermine si le sous‑arbre contenu dans le nœud est également cloné ou non. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Déclenche un Event sur le [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) spécifié, (synchroniquement) en invoquant les EventListeners concernés dans l'ordre approprié. Les règles normales de traitement des événements (y compris les phases de capture et de bouillonnement optionnelles) s'appliquent également aux événements déclenchés manuellement avec [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Effectue les tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | La méthode hasChildNodes() de l'interface Node renvoie une valeur booléenne indiquant si le [`Node`](../node/) donné possède des nœuds enfants ou non. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | La méthode insertBefore() de l'interface Node insère un nœud avant un nœud de référence en tant qu'enfant d'un nœud parent spécifié. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | La méthode isDefaultNamespace() de l'interface Node accepte un URI de package en argument. Elle renvoie une valeur booléenne qui est true si le package est le package par défaut sur le nœud donné et false sinon. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | La méthode isEqualNode() de l'interface [`Node`](../node/) teste si deux nœuds sont égaux. Deux nœuds sont égaux lorsqu'ils ont le même type, des caractéristiques définissant (pour les éléments, cela inclut leur ID, le nombre d'enfants, etc.), leurs attributs correspondent, etc. L'ensemble spécifique de points de données qui doivent correspondre varie selon les types des nœuds. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | La méthode isSameNode() de l'interface Node est un alias hérité de l'opérateur d'égalité stricte ===. Autrement dit, elle teste si deux nœuds sont identiques (c'est‑à‑dire s'ils font référence au même objet). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | La méthode lookupNamespaceURI() de l'interface Node prend un préfixe en paramètre et renvoie l'URI de package qui lui est associé sur le nœud donné si trouvé (et null sinon). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | La méthode lookupPrefix() de l'interface Node renvoie une chaîne contenant le préfixe d'un URI de package donné, si présent, et null sinon. Lorsque plusieurs préfixes sont possibles, le premier préfixe est renvoyé. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Place tous les nœuds [`Text`](../text/) à la profondeur maximale du sous‑arbre sous ce Node, y compris les nœuds d'attribut, dans une forme "normale" où seule la structure (p. ex., [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), et [`entity references`](../entityreference/)) sépare les nœuds [`Text`](../text/), c’est‑à‑dit qu’il n’y a ni nœuds Text adjacents ni nœuds Text vides. Cela peut être utilisé pour garantir que la vue DOM d’un document est identique à celle d’un document enregistré puis rechargé, et est utile lorsque des opérations (telles que les recherches XPointer [XPointer]) qui dépendent d’une structure d’arbre de document particulière doivent être utilisées. Si le paramètre "normalize-characters" de l’objet [`DOMConfiguration`](../../com.aspose.html/configuration/) attaché au [`Node.ownerDocument`](../node/ownerdocument/) est vrai, cette méthode normalisera également complètement les caractères des nœuds Text. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | La méthode removeChild() de l'interface Node supprime un nœud enfant du DOM et renvoie le nœud supprimé. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Remplace le nœud enfant oldChild par newChild dans la liste des enfants, et renvoie le nœud oldChild. Si newChild est un objet [`DocumentFragment`](../documentfragment/), oldChild est remplacé par tous les enfants du [`DocumentFragment`](../documentfragment/) qui sont insérés dans le même ordre. Si le newChild est déjà dans l'arbre, il est d'abord supprimé. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Renvoie une chaîne qui représente cette instance. |

### Voir aussi

* class [Node](../node/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
