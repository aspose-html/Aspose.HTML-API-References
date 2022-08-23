---
title: HTMLInputElement
second_title: Référence de l'API Aspose.HTML pour .NET
description: Contrôle de formulaire. Selon lenvironnement dans lequel la page est visualisée la propriété value peut être en lecture seule pour le type dentrée de téléchargement de fichier . Pour le type dentrée mot de passe la valeur réelle renvoyée peut être masquée pour empêcher toute utilisation non autorisée. Voir la définition de lélément INPUT dans HTML 4.01http//www.w3.org/TR/1999/REChtml40119991224 .
type: docs
weight: 3310
url: /fr/net/aspose.html/htmlinputelement/
---
## HTMLInputElement class

Contrôle de formulaire. Selon l'environnement dans lequel la page est visualisée, la propriété value peut être en lecture seule pour le type d'entrée de téléchargement de fichier . Pour le type d'entrée "mot de passe", la valeur réelle renvoyée peut être masquée pour empêcher toute utilisation non autorisée. Voir la définition de l'élément INPUT dans [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224) ].

Voir aussi le[Spécification HTML de niveau 2 du modèle d'objet de document (DOM)](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109) .

```csharp
public class HTMLInputElement : HTMLElement
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Accept](../../aspose.html/htmlinputelement/accept) { get; set; } | Une liste de types de contenu séparés par des virgules qu'un serveur traitant ce formulaire gérera correctement. Voir la définition de l'attribut accept dans HTML 4.01. |
| [AccessKey](../../aspose.html/htmlinputelement/accesskey) { get; set; } | Une clé d'accès à un seul caractère pour donner accès au contrôle du formulaire. Voir la définition de l'attribut accesskey dans HTML 4.01. |
| [Align](../../aspose.html/htmlinputelement/align) { get; set; } | Aligne cet objet (verticalement ou horizontalement) par rapport au texte qui l'entoure . Voir la définition de l'attribut align dans HTML 4.01. Cet attribut est obsolète dans HTML 4.01. |
| [Alt](../../aspose.html/htmlinputelement/alt) { get; set; } | Texte alternatif pour les agents utilisateurs ne restituant pas le contenu normal de cet élément . Voir la définition de l'attribut alt dans HTML 4.01. |
| override [Attributes](../../aspose.html.dom/element/attributes) { get; } | Un NamedNodeMap contenant les attributs de ce nœud (si c'est un Element) ou null sinon. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri) { get; } | L'URI de base absolu de ce nœud ou null si l'implémentation n'a pas pu obtenir d'URI absolu. |
| [Checked](../../aspose.html/htmlinputelement/checked) { get; set; } | Lorsque le`taper`L'attribut de l'élément a la valeur "radio" ou "checkbox", cela représente l'état actuel du contrôle du formulaire , dans un agent utilisateur interactif. Les modifications apportées à cet attribut modifient l'état du contrôle de formulaire, mais ne modifient pas la valeur de l'attribut HTML coché de l'élément INPUT. Lors de la gestion d'un événement de clic sur un élément d'entrée avec un attribut type qui a le valeur "radio" ou "case à cocher", certaines implémentations peuvent modifier la valeur de cette propriété avant que l'événement ne soit distribué dans le document . Si l'action par défaut de l'événement est annulée, la valeur de la propriété peut être ramenée à sa valeur d'origine. Cela signifie que la valeur de cette propriété lors de la gestion des événements de clic dépend de l'implémentation. |
| [ChildElementCount](../../aspose.html.dom/element/childelementcount) { get; } | Renvoie le nombre actuel de nœuds d'élément qui sont des enfants de cet élément. 0 si cet élément n'a pas de nœuds enfants qui sont de nodeType 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes) { get; } | Une NodeList qui contient tous les enfants de ce nœud. S'il n'y a pas d'enfants, il s'agit d'une NodeList ne contenant aucun nœud.. |
| [Children](../../aspose.html.dom/element/children) { get; } | Renvoie les éléments enfants de l'élément actuel. |
| [ClassList](../../aspose.html.dom/element/classlist) { get; } | Renvoie une DOMTokenList en direct qui contient les jetons reçus de l'analyse de l'attribut "class". |
| [ClassName](../../aspose.html/htmlelement/classname) { get; set; } | L'attribut de classe de l'élément. Cet attribut a été renommé en raison de à des conflits avec le mot-clé "class" exposé par de nombreuses langues. Voir la définition d'attribut de classe dans HTML 4.01. |
| [DefaultChecked](../../aspose.html/htmlinputelement/defaultchecked) { get; set; } | Quand`taper` a la valeur "radio" ou "checkbox", ce représente l'attribut HTML coché de l'élément. La valeur de cet attribut ne change pas si l'état du contrôle de formulaire correspondant, dans un agent utilisateur interactif, change. Voir la définition de l'attribut coché dans HTML 4.01. |
| [DefaultValue](../../aspose.html/htmlinputelement/defaultvalue) { get; set; } | Lorsque le`taper`L'attribut de l'élément a la valeur "texte", "fichier" ou "mot de passe", cela représente la valeur HTML de l'attribut de l'élément. La valeur de cet attribut ne change pas si le contenu du contrôle de formulaire correspondant, dans un agent utilisateur interactif , change. Voir la définition de l'attribut value dans HTML 4.01. |
| [Dir](../../aspose.html/htmlelement/dir) { get; set; } | Spécifie la direction de base du texte directionnellement neutre et la directionnalité des tableaux. Voir la définition de l'attribut dir dans HTML 4.01. |
| [Disabled](../../aspose.html/htmlinputelement/disabled) { get; set; } | Le contrôle n'est pas disponible dans ce contexte. Voir la définition de l'attribut désactivé dans HTML 4.01. |
| [Files](../../aspose.html/htmlinputelement/files) { get; } | L'attribut IDL des fichiers permet aux scripts d'accéder aux fichiers sélectionnés de l'élément. Lors de l'obtention, si l'attribut IDL s'applique, il doit renvoyer un objet FileList qui représente les fichiers actuellement sélectionnés. Le même objet doit être renvoyé jusqu'à ce que la liste des fichiers sélectionnés change. Si l'attribut IDL ne s'applique pas, il doit à la place renvoyer null. [FILEAPI] |
| [FirstChild](../../aspose.html.dom/node/firstchild) { get; } | Le premier enfant de ce nœud. S'il n'y a pas de tel nœud, cela renvoie null. |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild) { get; } | Renvoie le premier nœud d'élément enfant de cet élément. null si cet élément n'a pas d'éléments enfants. |
| [Form](../../aspose.html/htmlinputelement/form) { get; set; } | Renvoie le`FORMULAIRE` élément contenant ce champ. Renvoie `nul` si ce champ n'est pas dans le contexte d'un formulaire . |
| [Id](../../aspose.html/htmlelement/id) { get; set; } | L'identifiant de l'élément. Voir la définition de l'attribut id dans HTML 4.01. |
| [InnerHTML](../../aspose.html.dom/element/innerhtml) { get; set; } | Renvoie un fragment de HTML ou XML qui représente le contenu de l'élément. Peut être défini pour remplacer le contenu de l'élément par des nœuds analysés à partir de la chaîne donnée. |
| [Lang](../../aspose.html/htmlelement/lang) { get; set; } | Code de langue défini dans RFC 1766. Voir la définition de l'attribut lang dans HTML 4.01. |
| [LastChild](../../aspose.html.dom/node/lastchild) { get; } | Le dernier enfant de ce nœud. S'il n'y a pas de tel nœud, cela renvoie null. |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild) { get; } | Renvoie le dernier nœud d'élément enfant de cet élément. null si cet élément n'a pas d'éléments enfants. |
| [List](../../aspose.html/htmlinputelement/list) { get; set; } | L'attribut list est utilisé pour identifier un élément qui liste les options prédéfinies proposées à l'utilisateur. S'il est présent, sa valeur doit être l'ID d'un élément datalist dans le même document. |
| override [LocalName](../../aspose.html.dom/element/localname) { get; } | Renvoie la partie locale du nom qualifié de ce nœud. Pour les nœuds de tout type autre que ELEMENT_NODE et ATTRIBUTE_NODE et les nœuds créés avec une méthode DOM de niveau 1, comme Document.createElement(), c'est toujours null. |
| [MaxLength](../../aspose.html/htmlinputelement/maxlength) { get; set; } | Nombre maximum de caractères pour les champs de texte, lorsque`taper` a la valeur "texte" ou "mot de passe". Voir la définition de l'attribut maxlength dans HTML 4.01. |
| [Name](../../aspose.html/htmlinputelement/name) { get; set; } | Contrôle de formulaire ou nom d'objet lorsqu'il est soumis avec un formulaire. Voir la définition de l'attribut name dans HTML 4.01. |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri) { get; } | L'URI de l'espace de noms de ce nœud, ou null s'il n'est pas spécifié. |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling) { get; } | Renvoie le prochain nœud d'élément frère de cet élément. null si cet élément n'a aucun nœud frère d'élément qui vient après celui-ci dans l'arborescence du document. |
| [NextSibling](../../aspose.html.dom/node/nextsibling) { get; } | Le nœud suivant immédiatement ce nœud. S'il n'y a pas de tel nœud, cela renvoie null. |
| override [NodeName](../../aspose.html.dom/element/nodename) { get; } | Le nom de ce nœud, en fonction de son type. |
| override [NodeType](../../aspose.html.dom/element/nodetype) { get; } | Un code représentant le type de l'objet sous-jacent. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue) { get; set; } | La valeur de ce nœud, en fonction de son type. |
| [OuterHTML](../../aspose.html.dom/element/outerhtml) { get; set; } | Renvoie un fragment de HTML ou XML qui représente l'élément et son contenu. Peut être défini pour remplacer l'élément par des nœuds analysés à partir de la chaîne donnée. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument) { get; } | L'objet Document associé à ce nœud. Il s'agit également de l'objet Document utilisé pour créer de nouveaux nœuds. Lorsque ce nœud est un Document ou un DocumentType qui n'est pas encore utilisé avec un Document, c'est null. |
| [ParentElement](../../aspose.html.dom/node/parentelement) { get; } | Obtient le parent[`Element`](../../aspose.html.dom/element) de ce nœud. |
| [ParentNode](../../aspose.html.dom/node/parentnode) { get; } | Le parent de ce nœud. Tous les nœuds, à l'exception de Attr, Document, DocumentFragment, Entity et Notation peuvent avoir un parent. Cependant, si un nœud vient d'être créé et n'a pas encore été ajouté à l'arbre, ou s'il a été supprimé de l'arbre, c'est null. |
| override [Prefix](../../aspose.html.dom/element/prefix) { get; } | Le préfixe d'espace de noms de ce nœud, ou null s'il n'est pas spécifié. Lorsqu'il est défini comme étant nul, sa définition n'a aucun effet |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling) { get; } | Renvoie le nœud d'élément frère précédent de cet élément. null si cet élément n'a aucun nœud frère d'élément qui précède celui-ci dans l'arborescence du document. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling) { get; } | Le nœud précédant immédiatement ce nœud. S'il n'y a pas de tel nœud, cela renvoie null. |
| [ReadOnly](../../aspose.html/htmlinputelement/readonly) { get; set; } | Ce contrôle est en lecture seule. Pertinent uniquement lorsque`taper` a la valeur "texte" ou "mot de passe". Voir la définition de l'attribut readonly dans HTML 4.01. |
| [SchemaTypeInfo](../../aspose.html.dom/element/schematypeinfo) { get; } | Les informations de type associées à cet élément. |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot) { get; } | Renvoie shadowRoot stocké sur cet élément ou null s'il est fermé. |
| [Size](../../aspose.html/htmlinputelement/size) { get; set; } | Informations sur la taille. La signification précise est propre à chaque type de champ . Voir la définition de l'attribut size dans HTML 4.01. @version DOM Level 2 |
| [Src](../../aspose.html/htmlinputelement/src) { get; set; } | Lorsque le`taper` la valeur "image", cet attribut spécifie l'emplacement de l'image à utiliser pour décorer le bouton de soumission graphique. Voir la définition de l'attribut src dans HTML 4.01. |
| [Style](../../aspose.html/htmlelement/style) { get; } | Représente un attribut de style qui permet à l'auteur d'appliquer directement des informations de style à un élément spécifique. |
| [TabIndex](../../aspose.html/htmlinputelement/tabindex) { get; set; } | Index qui représente la position de l'élément dans l'ordre de tabulation. Voir la définition de l'attribut tabindex dans HTML 4.01. |
| [TagName](../../aspose.html.dom/element/tagname) { get; } | Le nom de l'élément. |
| override [TextContent](../../aspose.html.dom/element/textcontent) { get; set; } | Cet attribut renvoie le contenu textuel de ce nœud et de ses descendants. Lorsqu'il est défini comme étant nul, sa définition n'a aucun effet. Lors de la définition, tous les enfants possibles que ce nœud peut avoir sont supprimés et, si la nouvelle chaîne n'est pas vide ou nulle, remplacés par un seul nœud Texte contenant la chaîne à laquelle cet attribut est défini. |
| [Title](../../aspose.html/htmlelement/title) { get; set; } | Le titre consultatif de l'élément. Voir la définition de l'attribut title dans HTML 4.01. |
| [Type](../../aspose.html/htmlinputelement/type) { get; set; } | Le type de champ créé (tout en minuscules). Voir la définition de l'attribut type dans HTML 4.01. @version DOM niveau 2 |
| [UseMap](../../aspose.html/htmlinputelement/usemap) { get; set; } | Utiliser une image cliquable côté client. Voir la définition de l'attribut usemap dans HTML 4.01. |
| [Value](../../aspose.html/htmlinputelement/value) { get; set; } | Lorsque le`taper` L'attribut de l'élément a la valeur "texte", "fichier" ou "mot de passe", cela représente le contenu actuel de le contrôle de formulaire correspondant, dans un agent utilisateur interactif. La modification de cet attribut modifie le contenu du contrôle de formulaire, mais ne modifie pas la valeur de l'attribut de valeur HTML de l'élément. Lorsque le`taper`L'attribut de l'élément a la valeur "bouton", "caché", "soumettre", "réinitialiser", "image", "case à cocher" ou "radio", cela représente l'attribut de valeur HTML de l'élément. Voir la définition de l'attribut value dans HTML 4.01. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener) | Cette méthode permet l'enregistrement des écouteurs d'événement sur la cible de l'événement. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | Cette méthode permet l'enregistrement des écouteurs d'événement sur la cible de l'événement. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | Cette méthode permet l'enregistrement des écouteurs d'événement sur la cible de l'événement. |
| [AppendChild](../../aspose.html.dom/node/appendchild)(Node) | Ajoute le nœud newChild à la fin de la liste des enfants de ce nœud. Si le newChild est déjà dans l'arborescence, il est d'abord supprimé. |
| [AttachShadow](../../aspose.html.dom/element/attachshadow)(ShadowRootMode) | Crée une racine fantôme et l'attache à l'élément actuel. |
| [CloneNode](../../aspose.html.dom/node/clonenode)() | Renvoie un doublon de ce nœud, c'est-à-dire qu'il sert de constructeur de copie générique pour les nœuds. Le nœud dupliqué n'a pas de parent (parentNode est nul) et pas de données utilisateur. |
| [CloneNode](../../aspose.html.dom/node/clonenode)(bool) | Renvoie un doublon de ce nœud, c'est-à-dire qu'il sert de constructeur de copie générique pour les nœuds. Le nœud dupliqué n'a pas de parent (parentNode est nul) et pas de données utilisateur. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent)(Event) | Cette méthode permet de répartir les événements dans le modèle d'événement des implémentations. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose)() | Effectue des tâches définies par l'application associées à la libération, à la libération ou à la réinitialisation des ressources non gérées. |
| [GetAttribute](../../aspose.html.dom/element/getattribute)(string) | Récupère une valeur d'attribut par nom. |
| [GetAttributeNode](../../aspose.html.dom/element/getattributenode)(string) | Récupère un nœud d'attribut par nom. |
| [GetAttributeNodeNS](../../aspose.html.dom/element/getattributenodens)(string, string) | Récupère un nœud Attr par nom local et URI d'espace de noms. |
| [GetAttributeNS](../../aspose.html.dom/element/getattributens)(string, string) | Récupère une valeur d'attribut par nom local et URI d'espace de noms. |
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname)(string) | Renvoie un objet NodeList actif contenant tous les éléments du document qui ont toutes les classes spécifiées dans l'argument. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname)(string) | Renvoie une NodeList de tous les éléments descendants avec un nom de balise donné, dans l'ordre du document. |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens)(string, string) | Renvoie une NodeList de tous les éléments descendants avec un nom local et un URI d'espace de noms donnés dans l'ordre du document. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | Cette méthode est utilisée pour récupérer l'objet ECMAScriptType . |
| [HasAttribute](../../aspose.html.dom/element/hasattribute)(string) | Renvoie vrai lorsqu'un attribut avec un nom donné est spécifié sur cet élément ou a une valeur par défaut, faux sinon. |
| [HasAttributeNS](../../aspose.html.dom/element/hasattributens)(string, string) | Renvoie vrai lorsqu'un attribut avec un nom local et un URI d'espace de noms donnés est spécifié sur cet élément ou a une valeur par défaut, faux sinon. |
| override [HasAttributes](../../aspose.html.dom/element/hasattributes)() | Renvoie si ce nœud (s'il s'agit d'un élément) a des attributs |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes)() | Renvoie si ce nœud a des enfants. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore)(Node, Node) | Insère le nœud avant le nœud enfant existant. Si enfant est nul, insère le nœud à la fin de la liste des enfants. Si enfant est un objet DocumentFragment, tous ses enfants sont insérés, dans le même ordre, avant enfant. Si l'enfant est déjà dans l'arborescence, il est d'abord supprimé. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace)(string) | Cette méthode vérifie si le namespaceURI spécifié est l'espace de noms par défaut ou non. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode)(Node) | Teste si deux nœuds sont égaux. Cette méthode teste l'égalité des nœuds, pas la similitude (c'est-à-dire si les deux nœuds sont des références au même objet) qui peut être testée avec Node.isSameNode(). Tous les nœuds identiques seront également égaux, bien que l'inverse puisse ne pas être vrai. |
| [IsSameNode](../../aspose.html.dom/node/issamenode)(Node) | Renvoie si ce nœud est le même nœud que celui donné. Cette méthode permet de déterminer si deux références de nœud renvoyées par l'implémentation font référence au même objet. Lorsque deux références de nœud sont des références au même objet, même via un proxy, les références peuvent être utilisées de manière complètement interchangeable, de sorte que tous les attributs ont les mêmes valeurs et que l'appel de la même méthode DOM sur l'une ou l'autre des références a toujours exactement le même effet. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri)(string) | Recherchez l'URI de l'espace de noms associé au préfixe donné, à partir de ce nœud. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix)(string) | Recherchez le préfixe associé à l'URI de l'espace de noms donné, à partir de ce nœud. Les déclarations d'espace de noms par défaut sont ignorées par cette méthode. Voir Recherche de préfixe d'espace de noms pour plus de détails sur l'algorithme utilisé par cette méthode. |
| [Normalize](../../aspose.html.dom/node/normalize)() | Met tous les nœuds de texte dans toute la profondeur de la sous-arborescence sous ce nœud, y compris les nœuds d'attribut, dans une forme "normale" où seule la structure (par exemple, les éléments, les commentaires, les instructions de traitement, les sections CDATA et les références d'entité) sépare le texte nœuds, c'est-à-dire qu'il n'y a ni nœuds Text adjacents ni nœuds Text vides. Cela peut être utilisé pour s'assurer que la vue DOM d'un document est la même que s'il avait été enregistré et rechargé, et est utile lorsque des opérations (telles que les recherches XPointer [XPointer]) qui dépendent d'une arborescence de document particulière doivent être utilisé. Si le paramètre "normalize-characters" de l'objet DOMConfiguration attaché au Node.ownerDocument est vrai, cette méthode normalisera également complètement les caractères des nœuds Text. |
| [QuerySelector](../../aspose.html.dom/element/queryselector)(string) | Renvoie le premier élément du document, qui correspond à selector |
| [QuerySelectorAll](../../aspose.html.dom/element/queryselectorall)(string) | Renvoie une NodeList de tous les éléments du document, qui correspondent à selector |
| [Remove](../../aspose.html.dom/element/remove)() | Supprime cette instance. |
| [RemoveAttribute](../../aspose.html.dom/element/removeattribute)(string) | Supprime un attribut par nom. |
| [RemoveAttributeNode](../../aspose.html.dom/element/removeattributenode)(Attr) | Supprime le nœud d'attribut spécifié. |
| [RemoveAttributeNS](../../aspose.html.dom/element/removeattributens)(string, string) | Supprime un attribut par nom local et URI d'espace de noms. |
| [RemoveChild](../../aspose.html.dom/node/removechild)(Node) | Supprime le nœud enfant indiqué par oldChild de la liste des enfants et le renvoie. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener) | Cette méthode permet de supprimer les écouteurs d'événement de la cible de l'événement. Si un[`IEventListener`](../../aspose.html.dom.events/ieventlistener) est retiré d'un[`EventTarget`](../../aspose.html.dom/eventtarget) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événement ne peuvent jamais être invoqués après avoir été supprimés. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | Cette méthode permet de supprimer les écouteurs d'événement de la cible de l'événement. Si un[`IEventListener`](../../aspose.html.dom.events/ieventlistener) est retiré d'un[`EventTarget`](../../aspose.html.dom/eventtarget) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événement ne peuvent jamais être invoqués après avoir été supprimés. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | Cette méthode permet de supprimer les écouteurs d'événement de la cible de l'événement. Si un[`IEventListener`](../../aspose.html.dom.events/ieventlistener) est retiré d'un[`EventTarget`](../../aspose.html.dom/eventtarget) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événement ne peuvent jamais être invoqués après avoir été supprimés. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild)(Node, Node) | Remplace le nœud enfant oldChild par newChild dans la liste des enfants et renvoie le nœud oldChild. Si newChild est un objet DocumentFragment, oldChild est remplacé par tous les enfants DocumentFragment, qui sont insérés dans le même ordre. Si le newChild est déjà dans l'arborescence, il est d'abord supprimé. |
| [SetAttribute](../../aspose.html.dom/element/setattribute)(string, string) | Ajoute un nouvel attribut. Si un attribut portant ce nom est déjà présent dans l'élément, sa valeur est modifiée pour être celle de la valeur parameter |
| [SetAttributeNode](../../aspose.html.dom/element/setattributenode)(Attr) | Ajoute un nouveau nœud d'attribut. Si un attribut portant ce nom (nodeName) est déjà présent dans l'élément, il est remplacé par le nouveau. |
| [SetAttributeNodeNS](../../aspose.html.dom/element/setattributenodens)(Attr) | Ajoute un nouvel attribut. Si un attribut avec ce nom local et cet URI d'espace de noms est déjà présent dans l'élément, il est remplacé par le nouveau. |
| [SetAttributeNS](../../aspose.html.dom/element/setattributens)(string, string, string) | Ajoute un nouvel attribut. Si un attribut avec le même nom local et le même URI d'espace de noms est déjà présent sur l'élément, son préfixe est modifié pour être la partie préfixe du qualifiéName, et sa valeur est modifiée pour être le paramètre de valeur. |
| [SetIdAttribute](../../aspose.html.dom/element/setidattribute)(string, bool) | Si le paramètre isId est vrai, cette méthode déclare l'attribut spécifié comme étant un attribut d'ID déterminé par l'utilisateur. |
| [SetIdAttributeNode](../../aspose.html.dom/element/setidattributenode)(Attr, bool) | Si le paramètre isId est vrai, cette méthode déclare l'attribut spécifié comme étant un attribut d'ID déterminé par l'utilisateur. |
| [SetIdAttributeNS](../../aspose.html.dom/element/setidattributens)(string, string, bool) | Si le paramètre isId est vrai, cette méthode déclare l'attribut spécifié comme étant un attribut d'ID déterminé par l'utilisateur. |
| override [ToString](../../aspose.html.dom/node/tostring)() | Renvoie unString qui représente cette instance. |

### Voir également

* class [HTMLElement](../htmlelement)
* espace de noms [Aspose.Html](../../aspose.html)
* Assemblée [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->