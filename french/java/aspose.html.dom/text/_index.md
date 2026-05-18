---
title: "Classe Text"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.dom.Text. L'interface Text hérite de CharacterData et représente le contenu textuel appelé données de caractères en XML d'un Element ou d'un Attr"
type: docs

url: /fr/java/com.aspose.html.dom/text/
---
## Text class

L'interface Text hérite de CharacterData et représente le contenu textuel (appelé données de caractères en XML) d'un Element ou d'un Attr.

```java
public class Text : CharacterData
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) La propriété en lecture seule baseURI de l'interface Node renvoie l'URL de base absolue du document contenant le nœud. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) La propriété en lecture seule childNodes de l'interface Node renvoie une [`NodeList`](../../com.aspose.html.collections/nodelist/) dynamique des nœuds enfants de l'élément donné où le premier nœud enfant reçoit l'index 0. Les nœuds enfants comprennent les éléments, le texte et les commentaires. |
| [data](../../com.aspose.html.dom/characterdata/data/) { get; set; } | Les données de caractères du nœud qui implémente cette interface. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) La propriété en lecture seule firstChild de l'interface [`Node`](../node/) renvoie le premier enfant du nœud dans l'arbre, ou null si le nœud n'a aucun enfant. |
| [getIsElementContentWhitespace](../../com.aspose.html.dom/text/iselementcontentwhitespace/) Renvoie si ce nœud texte contient des espaces blancs de contenu d'élément, souvent abusivement appelés « ignorable whitespace ». |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) La propriété en lecture seule lastChild de l'interface [`Node`](../node/) renvoie le dernier enfant du nœud. Si son parent est un élément, l'enfant est généralement un nœud d'élément, un nœud texte ou un nœud commentaire. Elle renvoie null s'il n'y a aucun élément enfant. |
| [getLength](../../com.aspose.html.dom/characterdata/length/) Le nombre d'unités de 16 bits disponibles via la donnée et la méthode subStringData ci‑dessous. Cette valeur peut être zéro, c’est‑à‑dire que les nœuds CharacterData peuvent être vides. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Renvoie la partie locale du nom qualifié de ce nœud. Pour les nœuds de tout type autre que [`ELEMENT_NODE`](../node/element_node/) et [`ATTRIBUTE_NODE`](../node/attribute_node/) et les nœuds créés avec une méthode DOM Niveau 1, comme [`Document.createElement()`](../document/createelement/), ce champ est toujours nul. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) La propriété en lecture seule Element.packageURI renvoie l'URI du package de l'élément, ou null si l'élément n'est pas dans un package. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) La propriété en lecture seule nextSibling de l'interface [`Node`](../node/) renvoie le nœud immédiatement suivant le nœud spécifié dans le [`childNodes`](../node/childnodes/) de leur parent, ou renvoie null si le nœud spécifié est le dernier enfant de l'élément parent. |
| [getNodeName](../../com.aspose.html.dom/text/nodename/) Le nom de ce nœud, selon son type. |
| [getNodeType](../../com.aspose.html.dom/text/nodetype/) Un code représentant le type de l'objet sous‑jacent. |
| [nodeValue](../../com.aspose.html.dom/text/nodevalue/) { get; set; } | La valeur de ce nœud, selon son type. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) La propriété en lecture seule ownerDocument de l'interface Node renvoie l'objet document de niveau supérieur du nœud. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) La propriété en lecture seule parentElement de l'interface [`Node`](../node/) renvoie le parent [`Element`](../element/) du nœud DOM, ou null si le nœud n'a pas de parent ou si son parent n'est pas un Element DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) La propriété en lecture seule parentNode de l'interface Node renvoie le parent du nœud spécifié dans l'arbre DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | La propriété en lecture seule prefix renvoie le préfixe du package de l'élément spécifié, ou null si aucun préfixe n'est spécifié. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) La propriété en lecture seule previousSibling de l'interface [`Node`](../node/) renvoie le nœud immédiatement précédant le nœud spécifié dans la liste [`childNodes`](../node/firstchild/) de son parent, ou null si le nœud spécifié est le premier de cette liste. |
| [textContent](../../com.aspose.html.dom/text/textcontent/) { get; set; } | Cet attribut renvoie le contenu texte de ce nœud et de ses descendants. Lorsqu'il est défini à null, le définir n'a aucun effet. Lors de la définition, tous les enfants éventuels que ce nœud pourrait avoir sont supprimés et, si la nouvelle chaîne n'est pas vide ou null, remplacés par un seul nœud Text contenant la chaîne à laquelle cet attribut est assigné. |
| [getWholeText](../../com.aspose.html.dom/text/wholetext/) Renvoie tout le texte des nœuds Text logiquement adjacents à ce nœud, concaténé dans l'ordre du document. |

## Méthodes

| Nom | Description |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | La méthode addEventListener() de l'interface [`EventTarget `](../eventtarget/) configure une fonction qui sera appelée chaque fois que l'événement spécifié est livré à la cible. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | La méthode addEventListener() de l'interface [EventTarget ](T:com.aspose.html.dom.EventTarget) configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | La méthode addEventListener() de l'interface [EventTarget ](T:com.aspose.html.dom.EventTarget) configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | La méthode appendChild() de l'interface Node ajoute un nœud à la fin de la liste des enfants d'un nœud parent spécifié. Si l'enfant donné est une référence à un nœud existant dans le document, appendChild() le déplace de sa position actuelle vers la nouvelle position (il n'est pas nécessaire de supprimer le nœud de son nœud parent avant de l'ajouter à un autre nœud). |
| [appendData](../../com.aspose.html.dom/characterdata/appenddata/)(String) | Ajoute la chaîne à la fin des données de caractères du nœud. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | La méthode cloneNode() de l'interface Node renvoie un duplicata du nœud sur lequel cette méthode a été appelée. Son paramètre détermine si le sous‑arbre contenu dans le nœud est également cloné ou non. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | La méthode cloneNode() de l'interface Node renvoie un duplicata du nœud sur lequel cette méthode a été appelée. Son paramètre détermine si le sous‑arbre contenu dans le nœud est également cloné ou non. |
| [deleteData](../../com.aspose.html.dom/characterdata/deletedata/)(int, int) | Supprime une plage d'unités de 16 bits du nœud. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Déclenche un Event sur le [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) spécifié, (synchroniquement) en invoquant les EventListeners concernés dans l'ordre approprié. Les règles normales de traitement des événements (y compris les phases de capture et de bouillonnement optionnelles) s'appliquent également aux événements déclenchés manuellement avec [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Effectue les tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | La méthode hasChildNodes() de l'interface Node renvoie une valeur booléenne indiquant si le [`Node`](../node/) donné possède des nœuds enfants ou non. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | La méthode insertBefore() de l'interface Node insère un nœud avant un nœud de référence en tant qu'enfant d'un nœud parent spécifié. |
| [insertData](../../com.aspose.html.dom/characterdata/insertdata/)(int, String) | Insère une chaîne à l'offset d'unités de 16 bits spécifié. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | La méthode isDefaultNamespace() de l'interface Node accepte un URI de package en argument. Elle renvoie une valeur booléenne qui est true si le package est le package par défaut sur le nœud donné et false sinon. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | La méthode isEqualNode() de l'interface [`Node`](../node/) teste si deux nœuds sont égaux. Deux nœuds sont égaux lorsqu'ils ont le même type, des caractéristiques définissant (pour les éléments, cela inclut leur ID, le nombre d'enfants, etc.), leurs attributs correspondent, etc. L'ensemble spécifique de points de données qui doivent correspondre varie selon les types des nœuds. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | La méthode isSameNode() de l'interface Node est un alias hérité de l'opérateur d'égalité stricte ===. Autrement dit, elle teste si deux nœuds sont identiques (c'est‑à‑dire s'ils font référence au même objet). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | La méthode lookupNamespaceURI() de l'interface Node prend un préfixe en paramètre et renvoie l'URI de package qui lui est associé sur le nœud donné si trouvé (et null sinon). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | La méthode lookupPrefix() de l'interface Node renvoie une chaîne contenant le préfixe d'un URI de package donné, si présent, et null sinon. Lorsque plusieurs préfixes sont possibles, le premier préfixe est renvoyé. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Place tous les nœuds `Text` à la profondeur maximale du sous‑arbre sous ce nœud, y compris les nœuds d'attribut, dans une forme « normale » où seule la structure (par exemple, [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), et [`entity references`](../entityreference/)) sépare les nœuds `Text`, c’est‑à‑dire qu’il n’y a ni nœuds Text adjacents ni nœuds Text vides. Cela peut être utilisé pour garantir que la vue DOM d’un document est identique à celle d’un document enregistré puis rechargé, et est utile lorsque des opérations (telles que les recherches XPointer [XPointer]) qui dépendent d’une structure d’arbre de document particulière doivent être utilisées. Si le paramètre "normalize-characters" de l’objet [`DOMConfiguration`](../../com.aspose.html/configuration/) attaché à [`Node.ownerDocument`](../node/ownerdocument/) est vrai, cette méthode normalisera également complètement les caractères des nœuds Text. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | La méthode removeChild() de l'interface Node supprime un nœud enfant du DOM et renvoie le nœud supprimé. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Remplace le nœud enfant oldChild par newChild dans la liste des enfants, et renvoie le nœud oldChild. Si newChild est un objet [`DocumentFragment`](../documentfragment/), oldChild est remplacé par tous les enfants du [`DocumentFragment`](../documentfragment/) qui sont insérés dans le même ordre. Si le newChild est déjà dans l'arbre, il est d'abord supprimé. |
| [replaceData](../../com.aspose.html.dom/characterdata/replacedata/)(int, int, String) | Remplace les caractères à partir de l'offset d'unités de 16 bits spécifié par la chaîne spécifiée. |
| [replaceWholeText](../../com.aspose.html.dom/text/replacewholetext/)(String) | Remplace le texte du nœud actuel et de tous les nœuds texte logiquement adjacents par le texte spécifié. Tous les nœuds texte logiquement adjacents sont supprimés, y compris le nœud actuel, à moins qu'il n'ait été le destinataire du texte de remplacement. |
| [splitText](../../com.aspose.html.dom/text/splittext/)(int) | Divise ce nœud en deux nœuds à la position spécifiée, en conservant les deux comme frères dans l'arbre. |
| [subStringData](../../com.aspose.html.dom/characterdata/subStringdata/)(int, int) | Extrait une plage de données du nœud. |
| [toString](../../com.aspose.html.dom/characterdata/toString/)() | Renvoie une chaîne qui représente cette instance. |

### Voir aussi

* class [CharacterData](../characterdata/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
