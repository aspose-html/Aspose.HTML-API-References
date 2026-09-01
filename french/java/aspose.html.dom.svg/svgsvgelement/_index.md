---
title: "Classe SVGSVGElement"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.dom.svg.SVGSVGElement. Une définition d'interface clé est l'interface SVGSVGElement qui correspond à l'élément svg. Cette interface contient diverses méthodes utilitaires couramment utilisées, telles que les opérations sur les matrices et la capacité de contrôler le temps de redessin sur les dispositifs de rendu visuel."
type: docs

url: /fr/java/com.aspose.html.dom.svg/svgsvgelement/
---
## SVGSVGElement class

Une définition d'interface clé est l'interface SVGSVGElement, qui est l'interface correspondant à l'élément ‘svg’. Cette interface contient diverses méthodes utilitaires couramment utilisées, telles que les opérations matricielles et la capacité de contrôler le moment du rafraîchissement sur les dispositifs de rendu visuel.

```java
public class SVGSVGElement : SVGGraphicsElement, IDocumentEvent, ISVGFitToViewBox, ISVGZoomAndPan
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
| [getClassName](../../com.aspose.html.dom.svg/svgelement/classname/) Correspond à l'attribut ‘class’ de l'élément donné. |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
[getCurrentScale]
[setCurrentScale] On an outermost svg element, this attribute indicates the current scale factor relative to the initial view to take into account user magnification and panning operations, as described under Magnification and panning. DOM attributes currentScale and currentTranslate are equivalent to the 2x3 matrix [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. If "magnification" is enabled (i.e., zoomAndPan="magnify"), then the effect is as if an extra transformation were placed at the outermost level on the SVG document fragment (i.e., outside the outermost svg element). When accessed on an ‘svg’ element that is not an outermost svg element, it is undefined what behavior this attribute has. |
| [getCurrentTranslate](../../com.aspose.html.dom.svg/svgsvgelement/currenttranslate/) Sur un élément svg le plus externe, le facteur de translation correspondant qui tient compte de la « magnification » de l'utilisateur. Lorsqu'il est accédé sur un élément ‘svg’ qui n'est pas l'élément svg le plus externe, le comportement de cet attribut est indéfini. |
| [getFarthestViewportElement](../../com.aspose.html.dom.svg/svggraphicselement/farthestviewportelement/) L'élément ancêtre le plus éloigné ‘svg’. Null si l'élément actuel est l'élément svg le plus externe. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) La propriété en lecture seule firstChild de l'interface [`Node`](../../com.aspose.html.dom/node/) renvoie le premier enfant du nœud dans l'arbre, ou null si le nœud n'a aucun enfant. |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) Retourne le premier nœud élément enfant de cet élément. null si cet élément n'a aucun élément enfant. |
| [getHeight](../../com.aspose.html.dom.svg/svgsvgelement/height/) Correspond à l'attribut ‘height’ de l'élément ‘svg’ donné. |
[getId]
[setId] The value of the ‘id’ attribute on the given element, or the empty String if ‘id’ is not present. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) La propriété en lecture seule lastChild de l'interface [`Node`](../../com.aspose.html.dom/node/) renvoie le dernier enfant du nœud. Si son parent est un élément, l'enfant est généralement un nœud élément, un nœud texte ou un nœud commentaire. Elle renvoie null s'il n'y a aucun élément enfant |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) Renvoie le nœud de l'élément enfant dernier de cet élément. null si cet élément n'a aucun élément enfant. |
| [getLocalName](../../com.aspose.html.dom/element/localname/) Renvoie la partie locale du nom qualifié de ce nœud. Pour les nœuds de tout type autre que ELEMENT_NODE et ATTRIBUTE_NODE et les nœuds créés avec une méthode DOM Niveau 1, telle que Document.createElement(), ceci est toujours null. |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) L'URI d'espace de noms de ce nœud, ou null s'il n'est pas spécifié. |
| [getNearestViewportElement](../../com.aspose.html.dom.svg/svggraphicselement/nearestviewportelement/) L'élément qui a établi le viewport actuel. Souvent, l'ancêtre ‘svg’ le plus proche. Null si l'élément actuel est l'élément svg le plus externe. |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) Renvoie le nœud de l'élément frère suivant de cet élément. null si cet élément n'a aucun nœud frère d'élément qui le suit dans l'arbre du document. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) La propriété en lecture seule nextSibling de l'interface [`Node`](../../com.aspose.html.dom/node/) renvoie le nœud immédiatement suivant celui spécifié dans le [`childNodes`](../../com.aspose.html.dom/node/childnodes/) de leur parent, ou renvoie null si le nœud spécifié est le dernier enfant de l'élément parent. |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) Le nom de ce nœud, selon son type. |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) Un code représentant le type de l'objet sous-jacent. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | La propriété nodeValue de l'interface [`Node `](../../com.aspose.html.dom/node/) renvoie ou définit la valeur du nœud actuel. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) La propriété en lecture seule ownerDocument de l'interface Node renvoie l'objet document de niveau supérieur du nœud. |
| [getOwnerSVGElement](../../com.aspose.html.dom.svg/svgelement/ownersvgelement/) L'élément ‘svg’ ancêtre le plus proche. Null si l'élément fourni est l'élément svg le plus externe. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) La propriété en lecture seule parentElement de l'interface [`Node`](../../com.aspose.html.dom/node/) renvoie le parent du nœud DOM [`Element`](../../com.aspose.html.dom/element/), ou null si le nœud n'a pas de parent, ou si son parent n'est pas un élément DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) La propriété en lecture seule parentNode de l'interface Node renvoie le parent du nœud spécifié dans l'arbre DOM. |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) Le préfixe d'espace de noms de ce nœud, ou null s'il n'est pas spécifié. Lorsqu'il est défini à null, le définir n'a aucun effet |
| [getPreserveAspectRatio](../../com.aspose.html.dom.svg/svgsvgelement/preserveaspectratio/) Correspond à l'attribut ‘preserveAspectRatio’ de l'élément donné. |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) Renvoie le nœud de l'élément frère précédent de cet élément. null si cet élément n'a aucun nœud frère d'élément qui le précède dans l'arbre du document. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) La propriété en lecture seule previousSibling de l'interface [`Node`](../../com.aspose.html.dom/node/) renvoie le nœud immédiatement précédent celui spécifié dans la liste [`childNodes`](../../com.aspose.html.dom/node/firstchild/) de son parent, ou null si le nœud spécifié est le premier de cette liste. |
| [getRequiredExtensions](../../com.aspose.html.dom.svg/svggraphicselement/requiredextensions/) Correspond à l'attribut ‘requiredExtensions’ sur l'élément donné. |
| [getRequiredFeatures](../../com.aspose.html.dom.svg/svggraphicselement/requiredfeatures/) Correspond à l'attribut ‘requiredFeatures’ sur l'élément donné. |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) Renvoie le shadowRoot stocké sur cet élément ou null s'il est fermé. |
| [getStyle](../../com.aspose.html.dom.svg/svgelement/style/) Correspond à l'attribut ‘style’ de l'élément donné. Si l'agent utilisateur ne prend pas en charge le style avec CSS, cet attribut doit toujours avoir la valeur null. |
| [getSystemLanguage](../../com.aspose.html.dom.svg/svggraphicselement/systemlanguage/) Correspond à l'attribut ‘systemLanguage’ sur l'élément donné. |
| [getTagName](../../com.aspose.html.dom/element/tagname/) Le nom de l'élément. |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | Cet attribut renvoie le contenu texte de ce nœud et de ses descendants. Lorsqu'il est défini à null, le définir n'a aucun effet. Lors de la définition, tous les enfants éventuels que ce nœud pourrait avoir sont supprimés et, si la nouvelle chaîne n'est pas vide ou null, remplacés par un seul nœud Text contenant la chaîne à laquelle cet attribut est assigné. |
| [getTransform](../../com.aspose.html.dom.svg/svggraphicselement/transform/) Correspond à l'attribut ‘transform’ sur l'élément donné. |
| [getViewBox](../../com.aspose.html.dom.svg/svgsvgelement/viewbox/) Correspond à l'attribut ‘viewBox’ de l'élément donné. |
| [getViewportElement](../../com.aspose.html.dom.svg/svgelement/viewportelement/) L'élément qui a établi le viewport actuel. Souvent, l'élément ‘svg’ ancêtre le plus proche. Null si l'élément fourni est l'élément svg le plus externe. |
| [getWidth](../../com.aspose.html.dom.svg/svgsvgelement/width/) Correspond à l'attribut ‘width’ de l'élément ‘svg’ donné. |
| [X](../../com.aspose.html.dom.svg/svgsvgelement/x/) { get; } | Correspond à l'attribut ‘x’ de l'élément ‘svg’ donné. |
| [Y](../../com.aspose.html.dom.svg/svgsvgelement/y/) { get; } | Correspond à l'attribut ‘y’ de l'élément ‘svg’ donné. |
[getZoomAndPan]
[setZoomAndPan] Corresponds to attribute ‘zoomAndPan’ on the given element. The value must be one of the SVG_ZOOMANDPAN_* constants defined on this interface. |

## Méthodes

| Nom | Description |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | La méthode addEventListener() de l'interface [`EventTarget `](../../com.aspose.html.dom/eventtarget/) configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | La méthode addEventListener() de l'interface [EventTarget ](T:com.aspose.html.dom.EventTarget) configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | La méthode addEventListener() de l'interface [EventTarget ](T:com.aspose.html.dom.EventTarget) configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible. |
| [animationsPaused](../../com.aspose.html.dom.svg/svgsvgelement/animationspaused/)() | Renvoie true si ce fragment de document SVG est en état de pause. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | La méthode appendChild() de l'interface Node ajoute un nœud à la fin de la liste des enfants d'un nœud parent spécifié. Si l'enfant donné est une référence à un nœud existant dans le document, appendChild() le déplace de sa position actuelle vers la nouvelle position (il n'est pas nécessaire de supprimer le nœud de son nœud parent avant de l'ajouter à un autre nœud). |
| [attachShadow](../../com.aspose.html.dom/element/attachshadow/)(ShadowRootMode) | Crée une racine d'ombre et l'attache à l'élément actuel. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | La méthode cloneNode() de l'interface Node renvoie un duplicata du nœud sur lequel cette méthode a été appelée. Son paramètre détermine si le sous‑arbre contenu dans le nœud est également cloné ou non. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | La méthode cloneNode() de l'interface Node renvoie un duplicata du nœud sur lequel cette méthode a été appelée. Son paramètre détermine si le sous‑arbre contenu dans le nœud est également cloné ou non. |
| [createEvent](../../com.aspose.html.dom.svg/svgsvgelement/createevent/)(String) | Crée un [`Event`](../../com.aspose.html.dom.events/event/) d'un type pris en charge par l'implémentation. |
| [createSVGAngle](../../com.aspose.html.dom.svg/svgsvgelement/createsvgangle/)() | Crée un objet SVGAngle en dehors de tout arbre de document. L'objet est initialisé à la valeur 0 degré (sans unité). |
| [createSVGLength](../../com.aspose.html.dom.svg/svgsvgelement/createsvglength/)() | Crée un objet SVGLength en dehors de tout arbre de document. L'objet est initialisé à la valeur 0 unité utilisateur. |
| [createSVGMatrix](../../com.aspose.html.dom.svg/svgsvgelement/createsvgmatrix/)() | Crée un objet SVGMatrix en dehors de tout arbre de document. L'objet est initialisé à la matrice identité. |
| [createSVGNumber](../../com.aspose.html.dom.svg/svgsvgelement/createsvgnumber/)() | Crée un objet SVGNumber en dehors de tout arbre de document. L'objet est initialisé à la valeur zéro. |
| [createSVGPoint](../../com.aspose.html.dom.svg/svgsvgelement/createsvgpoint/)() | Crée un objet SVGPoint en dehors de tout arbre de document. L'objet est initialisé au point (0,0) dans le système de coordonnées utilisateur. |
| [createSVGRect](../../com.aspose.html.dom.svg/svgsvgelement/createsvgrect/)() | Crée un objet SVGRect en dehors de tout arbre de document. L'objet est initialisé de façon à ce que toutes les valeurs soient à 0 unité utilisateur. |
| [createSVGTransform](../../com.aspose.html.dom.svg/svgsvgelement/createsvgtransform/)() | Crée un objet SVGTransform en dehors de tout arbre de document. L'objet est initialisé à une transformation de matrice identité (SVG_TRANSFORM_MATRIX). |
| [createSVGTransformFromMatrix](../../com.aspose.html.dom.svg/svgsvgelement/createsvgtransformfrommatrix/)(SVGMatrix) | Crée un objet SVGTransform en dehors de tout arbre de document. L'objet est initialisé à la transformation matricielle fournie (c.-à-d. SVG_TRANSFORM_MATRIX). Les valeurs de la matrice paramètre sont copiées, le paramètre matrix n'est pas adopté comme SVGTransform::matrix. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Déclenche un Event sur le [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) spécifié, (synchroniquement) en invoquant les EventListeners concernés dans l'ordre approprié. Les règles normales de traitement des événements (y compris les phases de capture et de bouillonnement optionnelles) s'appliquent également aux événements déclenchés manuellement avec [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Effectue les tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées. |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | Récupère la valeur d'un attribut par son nom. |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | Renvoie les noms d'attributs de l'élément sous forme de tableau de chaînes. Si l'élément n'a aucun attribut, il renvoie un tableau vide. |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | Récupère un nœud d'attribut par son nom. |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | Récupère un nœud Attr par nom local et URI de package. |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | Récupère la valeur d'un attribut par nom local et URI de package. |
| [getBBox](../../com.aspose.html.dom.svg/svggraphicselement/getbbox/)() | Renvoie la boîte englobante précise dans l'espace utilisateur actuel (c’est‑à‑dire après l'application de l'attribut ‘transform’, le cas échéant) sur la géométrie de tous les éléments graphiques contenus, excluant le traçage, le découpage, le masquage et les effets de filtre). Notez que getBBox doit renvoyer la boîte englobante réelle au moment où la méthode est appelée, même si l'élément n’a pas encore été rendu. |
| [getCTM](../../com.aspose.html.dom.svg/svggraphicselement/getctm/)() | Renvoie la matrice de transformation des unités utilisateur actuelles (c’est‑à‑dire après l'application de l'attribut ‘transform’, le cas échéant) vers le système de coordonnées du viewport pour le nearestViewportElement. |
| [getCurrentTime](../../com.aspose.html.dom.svg/svgsvgelement/getcurrenttime/)() | Renvoie le temps actuel en secondes par rapport au temps de départ du fragment de document SVG en cours. Si getCurrentTime est appelé avant le début de la chronologie du document (par exemple, par un script s'exécutant dans un élément ‘script’ avant que l'événement SVGLoad du document ne soit déclenché), alors 0 est renvoyé. |
| [getElementById](../../com.aspose.html.dom.svg/svgsvgelement/getelementbyid/)(String) | Recherche dans ce fragment de document SVG (c.-à-d. la recherche est limitée à un sous-ensemble de l'arbre du document) un Élément dont l'identifiant est fourni par elementId. Si un Élément est trouvé, cet Élément est renvoyé. Si aucun élément de ce type n'existe, renvoie null. Le comportement n'est pas défini si plusieurs éléments portent cet identifiant. |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | Renvoie un objet [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) contenant tous les éléments à l'intérieur du [`element`](../../com.aspose.html.dom/element/) qui possèdent toutes les classes spécifiées en argument. |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | Renvoie un objet [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) contenant tous les [`elements`](../../com.aspose.html.dom/element/) ayant un nom de balise donné, dans l'ordre du document. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | Renvoie un objet [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) contenant tous les [`elements`](../../com.aspose.html.dom/element/) avec un nom local et une chaîne d'URI de package donnés, dans l'ordre du document. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |
| [getScreenCTM](../../com.aspose.html.dom.svg/svggraphicselement/getscreenctm/)() | Renvoie la matrice de transformation des unités utilisateur actuelles (c’est‑à‑dire après l'application de l'attribut ‘transform’, le cas échéant) vers la notion de "pixel" de l'agent utilisateur parent. Pour les dispositifs d'affichage, cela représente idéalement un pixel physique d'écran. Pour d'autres dispositifs ou environnements où la taille physique des pixels n'est pas connue, un algorithme similaire à la définition CSS2 d'un "pixel" peut être utilisé à la place. Notez que null est renvoyé si cet élément n'est pas intégré à l'arbre du document. Cette méthode aurait pu être plus correctement nommée getClientCTM, mais le nom getScreenCTM est conservé pour des raisons historiques. |
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
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Place tous les nœuds [`Text`](../../com.aspose.html.dom/text/) à la profondeur maximale du sous‑arbre sous ce Node, y compris les nœuds d'attribut, dans une forme "normale" où seule la structure (par ex., [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), et [`entity references`](../../com.aspose.html.dom/entityreference/)) sépare les nœuds [`Text`](../../com.aspose.html.dom/text/), c’est‑à‑dire qu’il n’y a ni nœuds Text adjacents ni nœuds Text vides. Cela peut être utilisé pour garantir que la vue DOM d’un document est identique à celle d’un document enregistré puis rechargé, et est utile lorsque des opérations (telles que les recherches XPointer [XPointer]) qui dépendent d’une structure d’arbre de document particulière doivent être utilisées. Si le paramètre "normalize-characters" de l’objet [`DOMConfiguration`](../../com.aspose.html/configuration/) attaché au [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) est true, cette méthode normalisera également complètement les caractères des nœuds Text. |
| [pauseAnimations](../../com.aspose.html.dom.svg/svgsvgelement/pauseanimations/)() | Suspend (c.-à-d. met en pause) toutes les animations en cours définies dans le fragment de document SVG correspondant à cet élément ‘svg’, faisant en sorte que l'horloge d'animation associée à ce fragment de document reste arrêtée jusqu'à ce qu'elle soit reprise. |
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
| [setCurrentTime](../../com.aspose.html.dom.svg/svgsvgelement/setcurrenttime/)(float) | Ajuste l'horloge pour ce fragment de document SVG, établissant un nouveau temps actuel. Si setCurrentTime est appelé avant que la chronologie du document n'ait commencé (par exemple, par un script s'exécutant dans un élément ‘script’ avant que l'événement SVGLoad du document ne soit déclenché), alors la valeur des secondes lors de la dernière invocation de la méthode indique le moment auquel le document cherchera à se positionner une fois la chronologie du document commencée. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String) | Si force n'est pas fourni, « toggle » qualifiedName, le supprimant s'il est présent et l'ajoutant s'il ne l'est pas. Si force est vrai, ajoute qualifiedName. Si force est faux, supprime qualifiedName. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String, bool) | Si force n'est pas fourni, « toggle » qualifiedName, le supprimant s'il est présent et l'ajoutant s'il ne l'est pas. Si force est vrai, ajoute qualifiedName. Si force est faux, supprime qualifiedName. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Renvoie une chaîne qui représente cette instance. |
| [unpauseAnimations](../../com.aspose.html.dom.svg/svgsvgelement/unpauseanimations/)() | Reprend (c’est‑à‑dire désuspend) les animations en cours d'exécution définies dans le fragment de document SVG, faisant ainsi continuer l'horloge d'animation à partir du moment où elle a été suspendue. |

### Voir aussi

* class [SVGGraphicsElement](../svggraphicselement/)
* interface [ISVGFitToViewBox](../isvgfittoviewbox/)
* interface [IDocumentEvent](../../com.aspose.html.dom.events/idocumentevent/)
* interface [IViewCSS](../../com.aspose.html.dom.css/iviewcss/)
* interface [IDocumentCSS](../../com.aspose.html.dom.css/idocumentcss/)
* interface [ISVGZoomAndPan](../isvgzoomandpan/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
