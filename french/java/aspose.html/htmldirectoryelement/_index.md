---
title: "HTMLDirectoryElement Classe"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.HTMLDirectoryElement classe. Liste de répertoires. Voir la définition de l'élément DIR dans HTML 4.01. Cet élément est obsolète dans HTML 4.01"
type: docs

url: /fr/java/com.aspose.html/htmldirectoryelement/
---
## HTMLDirectoryElement class

Liste de répertoires. Voir la définition de l'élément DIR dans HTML 4.01. Cet élément est obsolète dans HTML 4.01.

Voir également la [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109).

```java
public class HTMLDirectoryElement : HTMLElement
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getAttributes](../../com.aspose.html.dom/element/attributes/) Une NamedNodeMap contenant les attributs de ce nœud (s'il s'agit d'un Élément) ou null sinon. |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) La propriété en lecture seule baseURI de l'interface Node renvoie l'URL de base absolue du document contenant le nœud. |
| [getChildElementCount](../../com.aspose.html.dom/element/childelementcount/) Retourne le nombre actuel de nœuds d'élément qui sont enfants de cet élément. 0 si cet élément n'a aucun nœud enfant de type nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) La propriété en lecture seule childNodes de l'interface Node renvoie une [`NodeList`](../../com.aspose.html.collections/nodelist/) dynamique des nœuds enfants de l'élément donné où le premier nœud enfant reçoit l'index 0. Les nœuds enfants comprennent les éléments, le texte et les commentaires. |
| [getChildren](../../com.aspose.html.dom/element/children/) Retourne les éléments enfants de l'élément actuel. |
| [getClassList](../../com.aspose.html.dom/element/classlist/) Retourne une DOMTokenList dynamique qui contient les jetons obtenus en analysant l'attribut \"class\". |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
[getCompact]
[setCompact] Reduce spacing between list items. See the compact attribute definition in HTML 4.01. This attribute is deprecated in HTML 4.01. |
[getDir]
[setDir] Specifies the base direction of directionally neutral text and the directionality of tables. See the dir attribute definition in HTML 4.01. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) La propriété en lecture seule firstChild de l'interface [`Node`](../../com.aspose.html.dom/node/) renvoie le premier enfant du nœud dans l'arbre, ou null si le nœud n'a aucun enfant. |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) Retourne le premier nœud élément enfant de cet élément. null si cet élément n'a aucun élément enfant. |
[getId]
[setId] The element's identifier. See the id attribute definition in HTML 4.01. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
[getLang]
[setLang] Language code defined in RFC 1766. See the lang attribute definition in HTML 4.01. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) La propriété en lecture seule lastChild de l'interface [`Node`](../../com.aspose.html.dom/node/) renvoie le dernier enfant du nœud. Si son parent est un élément, l'enfant est généralement un nœud élément, un nœud texte ou un nœud commentaire. Elle renvoie null s'il n'y a aucun élément enfant |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) Renvoie le nœud de l'élément enfant dernier de cet élément. null si cet élément n'a aucun élément enfant. |
| [getLocalName](../../com.aspose.html.dom/element/localname/) Renvoie la partie locale du nom qualifié de ce nœud. Pour les nœuds de tout type autre que ELEMENT_NODE et ATTRIBUTE_NODE et les nœuds créés avec une méthode DOM Niveau 1, telle que Document.createElement(), ceci est toujours null. |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) L'URI d'espace de noms de ce nœud, ou null s'il n'est pas spécifié. |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) Renvoie le nœud de l'élément frère suivant de cet élément. null si cet élément n'a aucun nœud frère d'élément qui le suit dans l'arbre du document. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) La propriété en lecture seule nextSibling de l'interface [`Node`](../../com.aspose.html.dom/node/) renvoie le nœud immédiatement suivant celui spécifié dans le [`childNodes`](../../com.aspose.html.dom/node/childnodes/) de leur parent, ou renvoie null si le nœud spécifié est le dernier enfant de l'élément parent. |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) Le nom de ce nœud, selon son type. |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) Un code représentant le type de l'objet sous-jacent. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | La propriété nodeValue de l'interface [`Node `](../../com.aspose.html.dom/node/) renvoie ou définit la valeur du nœud actuel. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) La propriété en lecture seule ownerDocument de l'interface Node renvoie l'objet document de niveau supérieur du nœud. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) La propriété en lecture seule parentElement de l'interface [`Node`](../../com.aspose.html.dom/node/) renvoie le parent du nœud DOM [`Element`](../../com.aspose.html.dom/element/), ou null si le nœud n'a pas de parent, ou si son parent n'est pas un élément DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) La propriété en lecture seule parentNode de l'interface Node renvoie le parent du nœud spécifié dans l'arbre DOM. |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) Le préfixe d'espace de noms de ce nœud, ou null s'il n'est pas spécifié. Lorsqu'il est défini à null, le définir n'a aucun effet |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) Renvoie le nœud de l'élément frère précédent de cet élément. null si cet élément n'a aucun nœud frère d'élément qui le précède dans l'arbre du document. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) La propriété en lecture seule previousSibling de l'interface [`Node`](../../com.aspose.html.dom/node/) renvoie le nœud immédiatement précédent celui spécifié dans la liste [`childNodes`](../../com.aspose.html.dom/node/firstchild/) de son parent, ou null si le nœud spécifié est le premier de cette liste. |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) Renvoie le shadowRoot stocké sur cet élément ou null s'il est fermé. |
| [getStyle](../../com.aspose.html/htmlelement/style/) Représente un attribut de style qui permet à l'auteur d'appliquer directement des informations de style à un élément spécifique. |
| [getTagName](../../com.aspose.html.dom/element/tagname/) Le nom de l'élément. |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | Cet attribut renvoie le contenu texte de ce nœud et de ses descendants. Lorsqu'il est défini à null, le définir n'a aucun effet. Lors de la définition, tous les enfants éventuels que ce nœud pourrait avoir sont supprimés et, si la nouvelle chaîne n'est pas vide ou null, remplacés par un seul nœud Text contenant la chaîne à laquelle cet attribut est assigné. |
[getTitle]
[setTitle] The element's advisory title. See the title attribute definition in HTML 4.01. |

## Méthodes

| Nom | Description |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | La méthode addEventListener() de l'interface [`EventTarget `](../../com.aspose.html.dom/eventtarget/) configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | La méthode addEventListener() de l'interface [EventTarget ](T:com.aspose.html.dom.EventTarget) configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | La méthode addEventListener() de l'interface [EventTarget ](T:com.aspose.html.dom.EventTarget) configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | La méthode appendChild() de l'interface Node ajoute un nœud à la fin de la liste des enfants d'un nœud parent spécifié. Si l'enfant donné est une référence à un nœud existant dans le document, appendChild() le déplace de sa position actuelle vers la nouvelle position (il n'est pas nécessaire de supprimer le nœud de son nœud parent avant de l'ajouter à un autre nœud). |
| [attachShadow](../../com.aspose.html.dom/element/attachshadow/)(ShadowRootMode) | Crée une racine d'ombre et l'attache à l'élément actuel. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | La méthode cloneNode() de l'interface Node renvoie un duplicata du nœud sur lequel cette méthode a été appelée. Son paramètre détermine si le sous‑arbre contenu dans le nœud est également cloné ou non. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | La méthode cloneNode() de l'interface Node renvoie un duplicata du nœud sur lequel cette méthode a été appelée. Son paramètre détermine si le sous‑arbre contenu dans le nœud est également cloné ou non. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Déclenche un Event sur le [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) spécifié, (synchroniquement) en invoquant les EventListeners concernés dans l'ordre approprié. Les règles normales de traitement des événements (y compris les phases de capture et de bouillonnement optionnelles) s'appliquent également aux événements déclenchés manuellement avec [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Effectue les tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées. |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | Récupère la valeur d'un attribut par son nom. |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | Renvoie les noms d'attributs de l'élément sous forme de tableau de chaînes. Si l'élément n'a aucun attribut, il renvoie un tableau vide. |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | Récupère un nœud d'attribut par son nom. |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | Récupère un nœud Attr par nom local et URI de package. |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | Récupère la valeur d'un attribut par nom local et URI de package. |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | Renvoie un objet [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) contenant tous les éléments à l'intérieur du [`element`](../../com.aspose.html.dom/element/) qui possèdent toutes les classes spécifiées en argument. |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | Renvoie un objet [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) contenant tous les [`elements`](../../com.aspose.html.dom/element/) ayant un nom de balise donné, dans l'ordre du document. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | Renvoie un objet [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) contenant tous les [`elements`](../../com.aspose.html.dom/element/) avec un nom local et une chaîne d'URI de package donnés, dans l'ordre du document. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | Renvoie true lorsqu'un attribut avec le nom donné est spécifié sur cet élément ou possède une valeur par défaut, sinon false. |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | Renvoie true lorsqu'un attribut avec le nom local et l'URI de package donnés est spécifié sur cet élément ou possède une valeur par défaut, sinon false. |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | Renvoie si ce nœud (s'il s'agit d'un élément) possède des attributs |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | La méthode hasChildNodes() de l'interface Node renvoie une valeur booléenne indiquant si le [`Node`](../../com.aspose.html.dom/node/) donné possède des nœuds enfants ou non. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | La méthode insertBefore() de l'interface Node insère un nœud avant un nœud de référence en tant qu'enfant d'un nœud parent spécifié. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | La méthode isDefaultNamespace() de l'interface Node accepte un URI de package en argument. Elle renvoie une valeur booléenne qui est true si le package est le package par défaut sur le nœud donné et false sinon. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | La méthode isEqualNode() de l'interface [`Node`](../../com.aspose.html.dom/node/) teste si deux nœuds sont égaux. Deux nœuds sont égaux lorsqu'ils ont le même type, les mêmes caractéristiques définissant (pour les éléments, cela inclut leur ID, le nombre d'enfants, etc.), que leurs attributs correspondent, etc. L'ensemble spécifique de points de données qui doivent correspondre varie selon les types de nœuds. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | La méthode isSameNode() de l'interface Node est un alias hérité de l'opérateur d'égalité stricte ===. Autrement dit, elle teste si deux nœuds sont identiques (c'est‑à‑dire s'ils font référence au même objet). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | La méthode lookupNamespaceURI() de l'interface Node prend un préfixe en paramètre et renvoie l'URI de package qui lui est associé sur le nœud donné si trouvé (et null sinon). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | La méthode lookupPrefix() de l'interface Node renvoie une chaîne contenant le préfixe d'un URI de package donné, si présent, et null sinon. Lorsque plusieurs préfixes sont possibles, le premier préfixe est renvoyé. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Place tous les nœuds [`Text`](../../com.aspose.html.dom/text/) à la profondeur maximale du sous‑arbre sous ce nœud, y compris les nœuds d'attribut, dans une forme « normale » où seule la structure (par ex., [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), et [`entity references`](../../com.aspose.html.dom/entityreference/)) sépare les nœuds [`Text`](../../com.aspose.html.dom/text/), c’est‑à‑dire qu’il n’y a ni nœuds Text adjacents ni nœuds Text vides. Cela peut être utilisé pour garantir que la vue DOM d’un document est identique à celle d’un document enregistré puis rechargé, et est utile lorsque des opérations (telles que les recherches XPointer [XPointer]) qui dépendent d’une structure d’arbre de document particulière doivent être utilisées. Si le paramètre "normalize-characters" de l’objet [`DOMConfiguration`](../configuration/) attaché au [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) est vrai, cette méthode normalisera également complètement les caractères des nœuds Text. |
| [querySelector](../../com.aspose.html.dom/element/queryselector/)(String) | Renvoie le premier Element du document qui correspond au sélecteur |
| [querySelectorAll](../../com.aspose.html.dom/element/queryselectorall/)(String) | Renvoie une NodeList de tous les Elements du document qui correspondent au sélecteur |
| [remove](../../com.aspose.html.dom/element/remove/)() | Supprime cette instance. |
| [removeAttribute](../../com.aspose.html.dom/element/removeattribute/)(String) | Supprime un attribut par son nom. |
| [removeAttributeNode](../../com.aspose.html.dom/element/removeattributenode/)(Attr) | Supprime le nœud d'attribut spécifié. |
| [removeAttributeNS](../../com.aspose.html.dom/element/removeattributens/)(String, String) | Supprime un attribut par son nom local et son URI de package. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | La méthode removeChild() de l'interface Node supprime un nœud enfant du DOM et renvoie le nœud supprimé. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Remplace le nœud enfant oldChild par newChild dans la liste des enfants, et renvoie le nœud oldChild. Si newChild est un objet [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), oldChild est remplacé par tous les enfants du [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), qui sont insérés dans le même ordre. Si newChild est déjà dans l'arbre, il est d'abord supprimé. |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | Ajoute un nouvel attribut. Si un attribut portant ce nom est déjà présent dans l'élément, sa valeur est remplacée par celle du paramètre value. |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | Ajoute un nouveau nœud d'attribut. Si un attribut portant ce nom (nodeName) est déjà présent dans l'élément, il est remplacé par le nouveau. |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | Ajoute un nouvel attribut. Si un attribut avec ce nom local et cet URI de package est déjà présent dans l'élément, il est remplacé par le nouveau. |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | Ajoute un nouvel attribut. Si un attribut avec le même nom local et le même URI de package est déjà présent sur l'élément, son préfixe est remplacé par la partie préfixe de qualifiedName, et sa valeur est remplacée par le paramètre value. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String) | Si force n'est pas fourni, « toggle » qualifiedName, le supprimant s'il est présent et l'ajoutant s'il ne l'est pas. Si force est vrai, ajoute qualifiedName. Si force est faux, supprime qualifiedName. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String, bool) | Si force n'est pas fourni, « toggle » qualifiedName, le supprimant s'il est présent et l'ajoutant s'il ne l'est pas. Si force est vrai, ajoute qualifiedName. Si force est faux, supprime qualifiedName. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Renvoie une chaîne qui représente cette instance. |

## Événements

| Nom | Description |
| --- | --- |
| event [OnAbort](../../com.aspose.html/htmlelement/onabort/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnAbort. |
| event [OnBlur](../../com.aspose.html/htmlelement/onblur/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnBlur. |
| event [OnCancel](../../com.aspose.html/htmlelement/oncancel/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnCancel. |
| event [OnCanplay](../../com.aspose.html/htmlelement/oncanplay/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnCanplay. |
| event [OnCanPlayThrough](../../com.aspose.html/htmlelement/oncanplaythrough/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnCanPlayThrough. |
| event [OnChange](../../com.aspose.html/htmlelement/onchange/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnChange. |
| event [OnClick](../../com.aspose.html/htmlelement/onclick/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnClick. |
| event [OnCueChange](../../com.aspose.html/htmlelement/oncuechange/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnCueChange. |
| event [OnDblClick](../../com.aspose.html/htmlelement/ondblclick/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnDblClick. |
| event [OnDurationChange](../../com.aspose.html/htmlelement/ondurationchange/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnDurationChange. |
| event [OnEmptied](../../com.aspose.html/htmlelement/onemptied/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnEmptied. |
| event [OnEnded](../../com.aspose.html/htmlelement/onended/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnEnded. |
| event [OnError](../../com.aspose.html/htmlelement/onerror/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnError. |
| event [OnFocus](../../com.aspose.html/htmlelement/onfocus/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnFocus. |
| event [OnInput](../../com.aspose.html/htmlelement/oninput/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnInput. |
| event [OnInvalid](../../com.aspose.html/htmlelement/oninvalid/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnInvalid. |
| event [OnKeyDown](../../com.aspose.html/htmlelement/onkeydown/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnKeyDown. |
| event [OnKeyPress](../../com.aspose.html/htmlelement/onkeypress/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnKeyPress. |
| event [OnKeyUp](../../com.aspose.html/htmlelement/onkeyup/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnKeyUp. |
| event [OnLoad](../../com.aspose.html/htmlelement/onload/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnLoad. |
| event [OnLoadedData](../../com.aspose.html/htmlelement/onloadeddata/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnLoadedData. |
| event [OnLoadedMetadata](../../com.aspose.html/htmlelement/onloadedmetadata/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnLoadedMetadata. |
| event [OnLoadStart](../../com.aspose.html/htmlelement/onloadstart/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnLoadStart. |
| event [OnMouseDown](../../com.aspose.html/htmlelement/onmousedown/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnMouseDown. |
| event [OnMouseEnter](../../com.aspose.html/htmlelement/onmouseenter/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnMouseEnter. |
| event [OnMouseLeave](../../com.aspose.html/htmlelement/onmouseleave/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnMouseLeave. |
| event [OnMouseMove](../../com.aspose.html/htmlelement/onmousemove/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnMouseMove. |
| event [OnMouseOut](../../com.aspose.html/htmlelement/onmouseout/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnMouseOut. |
| event [OnMouseOver](../../com.aspose.html/htmlelement/onmouseover/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnMouseOver. |
| event [OnMouseUp](../../com.aspose.html/htmlelement/onmouseup/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnMouseUp. |
| event [OnMouseWheel](../../com.aspose.html/htmlelement/onmousewheel/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnMouseWheel. |
| event [OnPause](../../com.aspose.html/htmlelement/onpause/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnPause. |
| event [OnPlay](../../com.aspose.html/htmlelement/onplay/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnPlay. |
| event [OnPlaying](../../com.aspose.html/htmlelement/onplaying/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnPlaying. |
| event [OnProgress](../../com.aspose.html/htmlelement/onprogress/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnProgress. |
| event [OnRateChange](../../com.aspose.html/htmlelement/onratechange/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnRateChange. |
| event [OnReset](../../com.aspose.html/htmlelement/onreset/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnReset. |
| event [OnResize](../../com.aspose.html/htmlelement/onresize/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnResize. |
| event [OnScroll](../../com.aspose.html/htmlelement/onscroll/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnScroll. |
| event [OnSeeked](../../com.aspose.html/htmlelement/onseeked/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnSeeked. |
| event [OnSeeking](../../com.aspose.html/htmlelement/onseeking/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnSeeking. |
| event [OnSelect](../../com.aspose.html/htmlelement/onselect/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnSelect. |
| event [OnShow](../../com.aspose.html/htmlelement/onshow/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnShow. |
| event [OnStalled](../../com.aspose.html/htmlelement/onstalled/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnStalled. |
| event [OnSubmit](../../com.aspose.html/htmlelement/onsubmit/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnSubmit. |
| event [OnSuspend](../../com.aspose.html/htmlelement/onsuspend/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnSuspend. |
| event [OnTimeUpdate](../../com.aspose.html/htmlelement/ontimeupdate/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnTimeUpdate. |
| event [OnToggle](../../com.aspose.html/htmlelement/ontoggle/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnToggle. |
| event [OnVolumeChange](../../com.aspose.html/htmlelement/onvolumechange/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnVolumeChange. |
| event [OnWaiting](../../com.aspose.html/htmlelement/onwaiting/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnWaiting. |

### Voir aussi

* class [HTMLElement](../htmlelement/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
