---
title: "Classe HTMLDocument"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.HTMLDocument. Représente un document HTML. Tous les objets HTML de niveau supérieur sont ajoutés à cet objet. Cette classe représente la page HTML telle que nous la voyons dans le navigateur. Tous les formulaires, tableaux, scripts… sont ajoutés à la page HTML via les interfaces de cette classe. HTMLDocument est l’implémentation HTML de l’interface Document la plus générale et les deux constituent le point central ou racine du DOM – Document Object Model. Ces concepts sont en pleine conformité avec les bases ou normes officielles du développement web. Aux fins du développement web, vous pouvez généralement considérer HTMLDocument comme un alias du Document sur lequel HTMLDocument est basé."
type: docs

url: /fr/java/com.aspose.html/htmldocument/
---
## HTMLDocument class

Représente un document HTML. Tous les objets HTML de niveau supérieur sont ajoutés à cet objet. Cette classe représente la page HTML telle que nous la voyons dans le navigateur. Tous les formulaires, tableaux, scripts, ... sont ajoutés à la page HTML via les interfaces de cette classe. [HTMLDocument](https://dom.spec.whatwg.org/#ref-for-dom-domimplementation-createhtmldocument) est l'implémentation HTML de l'interface [Document](https://dom.spec.whatwg.org/#document) la plus générale et les deux constituent le point central ou racine du [DOM](https://dom.spec.whatwg.org/) - Document Object Model. Ces concepts sont en pleine conformité avec les bases ou normes officielles du développement web. Aux fins du développement web, vous pouvez généralement considérer HTMLDocument comme un alias de Document, sur lequel HTMLDocument est basé.

```java
public class HTMLDocument : Document, IDocumentCSS
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [HTMLDocument](htmldocument/#constructor)() | Le constructeur HTMLDocument crée un nouvel objet Document HTML qui est une page web chargée dans le navigateur et sert de point d’entrée au contenu de la page. |
| [HTMLDocument](htmldocument/#constructor_1)(Configuration) | Le constructeur HTMLDocument crée un nouvel objet Document HTML qui est une page web chargée dans le navigateur et sert de point d’entrée au contenu de la page. |
| [HTMLDocument](htmldocument/#constructor_2)(RequestMessage) | Crée un document HTML à partir de l’objet [`RequestMessage`](../../com.aspose.html.net/requestmessage/). |
| [HTMLDocument](htmldocument/#constructor_10)(String) | Charge le document HTML depuis une adresse. |
| [HTMLDocument](htmldocument/#constructor_4)(Url) | Charge le document HTML depuis une URL. |
| [HTMLDocument](htmldocument/#constructor_3)(RequestMessage, Configuration) | Crée un document HTML à partir d’un objet [RequestMessage](T:com.aspose.html.net.RequestMessage). |
| [HTMLDocument](htmldocument/#constructor_8)(Stream, String) | Crée un document HTML à partir d’un contenu [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) avec l’URI de base spécifiée, utilisée pour résoudre le chemin des ressources relatives. |
| [HTMLDocument](htmldocument/#constructor_6)(Stream, Url) | Crée un document HTML à partir d’un contenu [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) avec l’URI de base spécifiée, utilisée pour résoudre le chemin des ressources relatives. |
| [HTMLDocument](htmldocument/#constructor_11)(String, Configuration) | Charge le document HTML depuis une adresse avec les paramètres de configuration d’environnement spécifiés. |
| [HTMLDocument](htmldocument/#constructor_14)(String, String) | Crée un document HTML à partir d’un contenu String avec l’URI de base spécifiée. |
| [HTMLDocument](htmldocument/#constructor_12)(String, Url) | Crée un document HTML à partir d’un contenu String avec l’URI de base spécifiée. |
| [HTMLDocument](htmldocument/#constructor_5)(Url, Configuration) | Charge le document HTML depuis une URL avec les paramètres de configuration d’environnement spécifiés. |
| [HTMLDocument](htmldocument/#constructor_9)(Stream, String, Configuration) | Crée un document HTML à partir d’un contenu [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) avec l’URI de base et les paramètres de configuration d’environnement spécifiés. |
| [HTMLDocument](htmldocument/#constructor_7)(Stream, Url, Configuration) | Crée un document HTML à partir d’un contenu [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) avec l’URI de base et les paramètres de configuration d’environnement spécifiés. |
| [HTMLDocument](htmldocument/#constructor_15)(String, String, Configuration) | Crée un document HTML à partir d’un contenu String avec l’URI de base et les paramètres de configuration d’environnement spécifiés. |
| [HTMLDocument](htmldocument/#constructor_13)(String, Url, Configuration) | Crée un document HTML à partir d’un contenu String avec l’URI de base et les paramètres de configuration d’environnement spécifiés. |

## Propriétés

| Nom | Description |
| --- | --- |
| [getAnchors](../../com.aspose.html/htmldocument/anchors/) Une collection de tous les éléments d’ancre (`A`) d’un document ayant une valeur pour l’attribut `name`. Pour des raisons de compatibilité ascendante, l’ensemble renvoyé ne contient que les ancres créées avec l’attribut `name`, et non celles créées avec l’attribut `id`. Notez que dans [[XHTML 1.0](http://www.w3.org/TR/2002/REC-xhtml1-20020801)], l’attribut `name` (voir section 4.10) n’a aucune sémantique et n’est présent que pour les agents utilisateurs hérités : l’attribut `id` est utilisé à la place. Les utilisateurs devraient privilégier les mécanismes d’itération fournis par [[DOM Level 2 Traversal](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)] à la place. |
| [getApplets](../../com.aspose.html/htmldocument/applets/) Une collection de tous les éléments `OBJECT` qui incluent des applets et des éléments `APPLET` (obsolète) dans un document. |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) L'URI de base absolu de ce nœud ou null si l'implémentation n'a pas pu obtenir un URI absolu. |
[getBody]
[setBody] The element that contains the content for the document. In documents with `BODY` contents, returns the `BODY`element. In frameset documents, this returns the outermost `FRAMESET` element. |
| [getCharacterSet](../../com.aspose.html.dom/document/characterset/) Obtient le codage du document. |
| [getCharset](../../com.aspose.html.dom/document/charset/) Obtient le codage du document. |
| [getChildElementCount](../../com.aspose.html.dom/document/childelementcount/) Renvoie le nombre actuel de nœuds d'élément qui sont enfants de cet élément. 0 si cet élément n'a aucun nœud enfant de type nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) La propriété en lecture seule childNodes de l'interface Node renvoie une [`NodeList`](../../com.aspose.html.collections/nodelist/) dynamique des nœuds enfants de l'élément donné où le premier nœud enfant reçoit l'index 0. Les nœuds enfants comprennent les éléments, le texte et les commentaires. |
| [getChildren](../../com.aspose.html.dom/document/children/) Renvoie les éléments enfants. |
| [getContentType](../../com.aspose.html.dom/document/contenttype/) Obtient le type de contenu du document. |
| [getContext](../../com.aspose.html.dom/document/context/) Obtient le contexte de navigation actuel. |
| [getDefaultView](../../com.aspose.html.dom/document/defaultview/) L'attribut IDL defaultView de l'interface Document, lors de la lecture, doit renvoyer l'objet WindowProxy du contexte de navigation de ce Document, si ce Document possède un contexte de navigation associé, ou null sinon. |
| [getDoctype](../../com.aspose.html.dom/document/doctype/) La déclaration de type de document (Document Type Declaration) associée à ce document. |
| [getDocumentElement](../../com.aspose.html.dom/document/documentelement/) Il s'agit d'un attribut pratique qui permet d'accéder directement au nœud enfant qui est l'élément document du document. |
| [getDocumentURI](../../com.aspose.html.dom/document/documenturi/) L'emplacement du document ou null s'il est indéfini ou si le Document a été créé à l'aide de DOMImplementation.createDocument. |
| [getDomain](../../com.aspose.html/htmldocument/domain/) Le nom de domaine du serveur qui a fourni le document, ou `null` si le serveur ne peut pas être identifié par un nom de domaine. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) La propriété en lecture seule firstChild de l'interface [`Node`](../../com.aspose.html.dom/node/) renvoie le premier enfant du nœud dans l'arbre, ou null si le nœud n'a aucun enfant. |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) Renvoie le premier nœud élément enfant de cet élément. null si cet élément n'a aucun élément enfant. |
| [getForms](../../com.aspose.html/htmldocument/forms/) Une collection de tous les formulaires d’un document. |
| [getImages](../../com.aspose.html/htmldocument/images/) Une collection de tous les éléments `IMG` d’un document. Le comportement est limité aux éléments `IMG` pour des raisons de compatibilité ascendante. Comme le suggère [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)], pour inclure des images, les auteurs peuvent utiliser l’élément `OBJECT` ou l’élément `IMG`. Ainsi, il est recommandé de ne pas utiliser cet attribut pour rechercher les images dans le document mais d’utiliser `getElementsByTagName` avec HTML 4.01 ou `getElementsByTagNameNS` avec XHTML 1.0. |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) L'objet DOMImplementation qui gère ce document. |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) Obtient l'encodage du document. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) La propriété en lecture seule lastChild de l'interface [`Node`](../../com.aspose.html.dom/node/) renvoie le dernier enfant du nœud. Si son parent est un élément, l'enfant est généralement un nœud élément, un nœud texte ou un nœud commentaire. Elle renvoie null s'il n'y a aucun élément enfant |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) Renvoie le dernier nœud élément enfant de cet élément. null si cet élément n'a aucun élément enfant. |
| [getLinks](../../com.aspose.html/htmldocument/links/) Une collection de tous les éléments `AREA` et des ancres (`A`) d’un document ayant une valeur pour l’attribut `href`. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Renvoie la partie locale du nom qualifié de ce nœud. Pour les nœuds de tout type autre que [`ELEMENT_NODE`](../../com.aspose.html.dom/node/element_node/) et [`ATTRIBUTE_NODE`](../../com.aspose.html.dom/node/attribute_node/) et les nœuds créés avec une méthode du DOM Niveau 1, comme [`Document.createElement()`](../../com.aspose.html.dom/document/createelement/), ceci est toujours null. |
| [getLocation](../../com.aspose.html.dom/document/location/) L'emplacement du document. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) La propriété en lecture seule Element.packageURI renvoie l'URI du package de l'élément, ou null si l'élément n'est pas dans un package. |
| [getNextElementSibling](../../com.aspose.html.dom/document/nextelementsibling/) Renvoie le nœud élément frère suivant de cet élément. null si cet élément n'a aucun nœud frère élément qui le suit dans l'arbre du document. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) La propriété en lecture seule nextSibling de l'interface [`Node`](../../com.aspose.html.dom/node/) renvoie le nœud immédiatement suivant celui spécifié dans le [`childNodes`](../../com.aspose.html.dom/node/childnodes/) de leur parent, ou renvoie null si le nœud spécifié est le dernier enfant de l'élément parent. |
| [getNodeName](../../com.aspose.html.dom/document/nodename/) Le nom de ce nœud, selon son type. |
| [getNodeType](../../com.aspose.html.dom/document/nodetype/) Un code représentant le type de l'objet sous-jacent. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | La propriété nodeValue de l'interface [`Node `](../../com.aspose.html.dom/node/) renvoie ou définit la valeur du nœud actuel. |
| [getOrigin](../../com.aspose.html.dom/document/origin/) Obtient l'origine du document. |
| [getOwnerDocument](../../com.aspose.html.dom/document/ownerdocument/) Obtient le document propriétaire. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) La propriété en lecture seule parentElement de l'interface [`Node`](../../com.aspose.html.dom/node/) renvoie le parent du nœud DOM [`Element`](../../com.aspose.html.dom/element/), ou null si le nœud n'a pas de parent, ou si son parent n'est pas un élément DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) La propriété en lecture seule parentNode de l'interface Node renvoie le parent du nœud spécifié dans l'arbre DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | La propriété en lecture seule prefix renvoie le préfixe du package de l'élément spécifié, ou null si aucun préfixe n'est spécifié. |
| [getPreviousElementSibling](../../com.aspose.html.dom/document/previouselementsibling/) Renvoie le nœud élément frère précédent de cet élément. null si cet élément n'a aucun nœud frère élément qui le précède dans l'arbre du document. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) La propriété en lecture seule previousSibling de l'interface [`Node`](../../com.aspose.html.dom/node/) renvoie le nœud immédiatement précédent celui spécifié dans la liste [`childNodes`](../../com.aspose.html.dom/node/firstchild/) de son parent, ou null si le nœud spécifié est le premier de cette liste. |
| [getReadyState](../../com.aspose.html.dom/document/readystate/) Renvoie l'état de préparation du document. "loading" pendant le chargement du Document, "interactive" une fois le parsing terminé mais les sous‑ressources toujours en cours de chargement, et "complete" une fois le chargement terminé. |
| [getReferrer](../../com.aspose.html/htmldocument/referrer/) Retourne l’URI [[IETF RFC 2396](http://www.ietf.org/rfc/rfc2396.txt)] de la page qui a créé un lien vers cette page. La valeur est une chaîne vide si l’utilisateur a accédé à la page directement (pas via un lien, mais, par exemple, via un signet). |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) Une liste contenant toutes les feuilles de style explicitement liées ou incorporées dans un document. Pour les documents HTML, cela inclut les feuilles de style externes, incluses via l'élément HTML LINK, et les éléments STYLE en ligne. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | La propriété textContent de l'interface [`Node`](../../com.aspose.html.dom/node/) représente le contenu texte du nœud et de ses descendants. |
[getTitle]
[setTitle] The title of a document as specified by the `TITLE` element in the head of the document. |
[getXmlStandalone]
[setXmlStandalone] An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
[getXmlVersion]
[setXmlVersion] An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## Méthodes

| Nom | Description |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | La méthode addEventListener() de l'interface [`EventTarget `](../../com.aspose.html.dom/eventtarget/) configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | La méthode addEventListener() de l'interface [EventTarget ](T:com.aspose.html.dom.EventTarget) configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | La méthode addEventListener() de l'interface [EventTarget ](T:com.aspose.html.dom.EventTarget) configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | La méthode appendChild() de l'interface Node ajoute un nœud à la fin de la liste des enfants d'un nœud parent spécifié. Si l'enfant donné est une référence à un nœud existant dans le document, appendChild() le déplace de sa position actuelle vers la nouvelle position (il n'est pas nécessaire de supprimer le nœud de son nœud parent avant de l'ajouter à un autre nœud). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | La méthode cloneNode() de l'interface Node renvoie un duplicata du nœud sur lequel cette méthode a été appelée. Son paramètre détermine si le sous‑arbre contenu dans le nœud est également cloné ou non. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | La méthode cloneNode() de l'interface Node renvoie un duplicata du nœud sur lequel cette méthode a été appelée. Son paramètre détermine si le sous‑arbre contenu dans le nœud est également cloné ou non. |
| [createAttribute](../../com.aspose.html.dom/document/createattribute/)(String) | La méthode Document.createAttribute() crée un nouveau nœud d'attribut et le renvoie. L'objet créé est un nœud implémentant l'interface [`Attr`](../../com.aspose.html.dom/attr/). Le DOM n'impose aucune restriction sur le type d'attributs pouvant être ajoutés à un élément particulier de cette manière. |
| [createAttributeNS](../../com.aspose.html.dom/document/createattributens/)(String, String) | La méthode Document.createAttribute() crée un nouveau nœud d'attribut et le renvoie. L'objet créé est un nœud implémentant l'interface [Attr](T:com.aspose.html.dom.Attr). Le DOM n'impose aucune restriction sur le type d'attributs pouvant être ajoutés à un élément particulier de cette manière. |
| [createCDATASection](../../com.aspose.html.dom/document/createcdatasection/)(String) | Crée un nœud [`CDATASection`](../../com.aspose.html.dom/cdatasection/) dont la valeur est la chaîne spécifiée. |
| [createComment](../../com.aspose.html.dom/document/createcomment/)(String) | Crée un nœud [`Comment`](../../com.aspose.html.dom/comment/) à partir de la chaîne spécifiée. |
| [createDocumentFragment](../../com.aspose.html.dom/document/createdocumentfragment/)() | Crée un nouveau [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) vide dans lequel des nœuds DOM peuvent être ajoutés pour construire un arbre DOM hors écran. |
| [createDocumentType](../../com.aspose.html.dom/document/createdocumenttype/)(String, String, String, String) | La méthode renvoie un objet [`DocumentType`](../../com.aspose.html.dom/documenttype/) qui peut être utilisé avec DOMImplementation.createDocument lors de la création du document ou être inséré dans le document via des méthodes telles que Node.insertBefore() ou Node.replaceChild(). |
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | Dans un document HTML, la méthode document.createElement() crée l’élément HTML spécifié par tagName, ou un [`HTMLUnknownElement`](../htmlunknownelement/) si tagName n’est pas reconnu. |
| [createElementNS](../../com.aspose.html.dom/document/createelementns/)(String, String) | Crée un élément avec le nom qualifié et l'URI de package fournis. |
| [createEntityReference](../../com.aspose.html.dom/document/createentityreference/)(String) | Crée un objet EntityReference. De plus, si l'entité référencée est connue, la liste des enfants du nœud EntityReference devient identique à celle du nœud Entity correspondant. |
| [createEvent](../../com.aspose.html.dom/document/createevent/)(String) | Crée un [`Event`](../../com.aspose.html.dom.events/event/) d'un type pris en charge par l'implémentation. |
| [createExpression](../../com.aspose.html.dom/document/createexpression/)(String, IXPathNSResolver) | Crée une expression XPath analysée avec les packages résolus. Ceci est utile lorsqu'une expression sera réutilisée dans une application, car cela permet de compiler la chaîne d'expression en une forme interne plus efficace et de pré‑résoudre tous les préfixes de package présents dans l'expression. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node) | Crée un nouveau NodeIterator sur le sous-arbre dont la racine est le nœud spécifié. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long) | Crée un nouveau NodeIterator sur le sous-arbre dont la racine est le nœud spécifié. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long, INodeFilter) | Crée un nouveau NodeIterator sur le sous-arbre dont la racine est le nœud spécifié. |
| [createNSResolver](../../com.aspose.html.dom/document/creatensresolver/)(Node) | Adapte tout nœud DOM pour résoudre les packages afin qu'une expression XPath puisse être évaluée facilement par rapport au contexte du nœud où elle apparaît dans le document. Cet adaptateur fonctionne comme la méthode du DOM Niveau 3 `lookupNamespaceURI` sur les nœuds pour résoudre le packageURI à partir d'un préfixe donné en utilisant les informations disponibles dans la hiérarchie du nœud au moment de l'appel, tout en résolvant correctement le préfixe xml implicite. |
| [createProcessingInstruction](../../com.aspose.html.dom/document/createprocessinginstruction/)(String, String) | Crée un nœud ProcessingInstruction à partir des chaînes de caractères nom et données spécifiées. |
| [createTextNode](../../com.aspose.html.dom/document/createtextnode/)(String) | Crée un nœud Text à partir de la chaîne spécifiée. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node) | Crée un nouveau TreeWalker sur le sous-arbre dont la racine est le nœud spécifié. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long) | Crée un nouveau TreeWalker sur le sous-arbre dont la racine est le nœud spécifié. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long, INodeFilter) | Crée un nouveau TreeWalker sur le sous-arbre dont la racine est le nœud spécifié. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Déclenche un Event sur le [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) spécifié, (synchroniquement) en invoquant les EventListeners concernés dans l'ordre approprié. Les règles normales de traitement des événements (y compris les phases de capture et de bouillonnement optionnelles) s'appliquent également aux événements déclenchés manuellement avec [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Effectue les tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées. |
| [evaluate](../../com.aspose.html.dom/document/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Évalue une chaîne d'expression XPath et renvoie un résultat du type spécifié si possible. |
| [getElementById](../../com.aspose.html.dom/document/getelementbyid/)(String) | La méthode Document getElementById() renvoie un objet [`Element`](../../com.aspose.html.dom/element/) représentant l'élément dont la propriété id correspond à la chaîne spécifiée. Étant donné que les IDs d'éléments doivent être uniques lorsqu'ils sont spécifiés, ils constituent un moyen pratique d'accéder rapidement à un élément spécifique. |
| [getElementsByClassName](../../com.aspose.html.dom/document/getelementsbyclassname/)(String) | La méthode getElementsByClassName de l'interface [`Document`](../../com.aspose.html.dom/document/) renvoie un objet de type tableau contenant tous les éléments enfants qui possèdent tous les noms de classe fournis. |
| [getElementsByTagName](../../com.aspose.html.dom/document/getelementsbytagname/)(String) | La méthode getElementsByTagName de l'interface [`Document`](../../com.aspose.html.dom/document/) renvoie une [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) d'éléments portant le nom de balise indiqué. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/document/getelementsbytagnamens/)(String, String) | Renvoie une liste d'éléments avec le nom de balise indiqué appartenant au package spécifié. Le document complet est parcouru, y compris le nœud racine. |
| [getOverrideStyle](../../com.aspose.html/htmldocument/getoverridestyle/)(Element, String) | Cette méthode est utilisée pour récupérer la déclaration de style de substitution pour un élément spécifié et un pseudo‑élément spécifié. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | La méthode hasChildNodes() de l'interface Node renvoie une valeur booléenne indiquant si le [`Node`](../../com.aspose.html.dom/node/) donné possède des nœuds enfants ou non. |
| [importNode](../../com.aspose.html.dom/document/importnode/)(Node, bool) | Importe un nœud d'un autre document dans celui-ci, sans modifier ni supprimer le nœud source du document d'origine ; cette méthode crée une nouvelle copie du nœud source. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | La méthode insertBefore() de l'interface Node insère un nœud avant un nœud de référence en tant qu'enfant d'un nœud parent spécifié. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | La méthode isDefaultNamespace() de l'interface Node accepte un URI de package en argument. Elle renvoie une valeur booléenne qui est true si le package est le package par défaut sur le nœud donné et false sinon. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | La méthode isEqualNode() de l'interface [`Node`](../../com.aspose.html.dom/node/) teste si deux nœuds sont égaux. Deux nœuds sont égaux lorsqu'ils ont le même type, les mêmes caractéristiques définissant (pour les éléments, cela inclut leur ID, le nombre d'enfants, etc.), que leurs attributs correspondent, etc. L'ensemble spécifique de points de données qui doivent correspondre varie selon les types de nœuds. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | La méthode isSameNode() de l'interface Node est un alias hérité de l'opérateur d'égalité stricte ===. Autrement dit, elle teste si deux nœuds sont identiques (c'est‑à‑dire s'ils font référence au même objet). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | La méthode lookupNamespaceURI() de l'interface Node prend un préfixe en paramètre et renvoie l'URI de package qui lui est associé sur le nœud donné si trouvé (et null sinon). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | La méthode lookupPrefix() de l'interface Node renvoie une chaîne contenant le préfixe d'un URI de package donné, si présent, et null sinon. Lorsque plusieurs préfixes sont possibles, le premier préfixe est renvoyé. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(RequestMessage) | Charge le document en fonction de l'objet de requête spécifié, en remplaçant le contenu précédent. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String) | Charge le document à l'Uniform Resource Locator (URL) spécifié dans l'instance actuelle, en remplaçant le contenu précédent. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Url) | Charge le document à l'Uniform Resource Locator (URL) spécifié dans l'instance actuelle, en remplaçant le contenu précédent. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, String) | Charge le document à partir du contenu spécifié en utilisant baseUri pour résoudre les ressources relatives, en remplaçant le contenu précédent. Le chargement du document commence à partir de la position actuelle dans le flux. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, Url) | Charge le document à partir du contenu spécifié en utilisant baseUri pour résoudre les ressources relatives, en remplaçant le contenu précédent. Le chargement du document commence à partir de la position actuelle dans le flux. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, String) | Charge le document à partir du contenu spécifié en utilisant baseUri pour résoudre les ressources relatives, en remplaçant le contenu précédent. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, Url) | Charge le document à partir du contenu spécifié en utilisant baseUri pour résoudre les ressources relatives, en remplaçant le contenu précédent. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Place tous les nœuds [`Text`](../../com.aspose.html.dom/text/) à la profondeur maximale du sous‑arbre sous ce nœud, y compris les nœuds d'attribut, dans une forme « normale » où seule la structure (par ex., [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), et [`entity references`](../../com.aspose.html.dom/entityreference/)) sépare les nœuds [`Text`](../../com.aspose.html.dom/text/), c’est‑à‑dire qu’il n’y a ni nœuds Text adjacents ni nœuds Text vides. Cela peut être utilisé pour garantir que la vue DOM d’un document est identique à celle d’un document enregistré puis rechargé, et est utile lorsque des opérations (telles que les recherches XPointer [XPointer]) qui dépendent d’une structure d’arbre de document particulière doivent être utilisées. Si le paramètre "normalize-characters" de l’objet [`DOMConfiguration`](../configuration/) attaché au [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) est vrai, cette méthode normalisera également complètement les caractères des nœuds Text. |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | Renvoie le premier Element du document qui correspond au sélecteur |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | Renvoie une NodeList de tous les Elements du document qui correspondent au sélecteur |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | La méthode removeChild() de l'interface Node supprime un nœud enfant du DOM et renvoie le nœud supprimé. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [renderTo](../../com.aspose.html/htmldocument/renderto/)(IDevice) | Cette méthode est utilisée pour imprimer le contenu du document actuel sur le dispositif spécifié. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Remplace le nœud enfant oldChild par newChild dans la liste des enfants, et renvoie le nœud oldChild. Si newChild est un objet [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), oldChild est remplacé par tous les enfants du [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), qui sont insérés dans le même ordre. Si newChild est déjà dans l'arbre, il est d'abord supprimé. |
| [save](../../com.aspose.html/htmldocument/save/#save)(ResourceHandler) | Enregistre le contenu du document et les ressources en utilisant le [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_10)(String) | Enregistre le document dans un fichier local spécifié par le chemin. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent, dont le nom sera construit ainsi : output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_5)(Url) | Enregistre le document dans un fichier local spécifié par l'url. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent, dont le nom sera construit comme output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_1)(ResourceHandler, HTMLSaveFormat) | Enregistre le contenu du document et les ressources en utilisant le [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_2)(ResourceHandler, HTMLSaveOptions) | Enregistre le contenu du document et les ressources en utilisant le [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_3)(ResourceHandler, MarkdownSaveOptions) | Enregistre le contenu du document et les ressources en utilisant le [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_4)(ResourceHandler, MHTMLSaveOptions) | Enregistre le contenu du document et les ressources en utilisant le [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_11)(String, HTMLSaveFormat) | Enregistre le document dans un fichier local spécifié par le chemin. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent, dont le nom sera construit comme output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_12)(String, HTMLSaveOptions) | Enregistre le document dans un fichier local spécifié par le chemin. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent, dont le nom sera construit ainsi : output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_13)(String, MarkdownSaveOptions) | Enregistre le document dans un fichier local spécifié par le chemin. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent, dont le nom sera construit ainsi : output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_14)(String, MHTMLSaveOptions) | Enregistre le document dans un fichier local spécifié par le chemin. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent, dont le nom sera construit ainsi : output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_6)(Url, HTMLSaveFormat) | Enregistre le document dans un fichier local spécifié par l'url. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent, dont le nom sera construit comme output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_7)(Url, HTMLSaveOptions) | Enregistre le document dans un fichier local spécifié par l'url. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent, dont le nom sera construit comme : output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_8)(Url, MarkdownSaveOptions) | Enregistre le document dans un fichier local spécifié par l'url. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent, dont le nom sera construit comme : output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_9)(Url, MHTMLSaveOptions) | Enregistre le document dans un fichier local spécifié par l'url. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent, dont le nom sera construit comme : output_file_name + "_files". |
| [toString](../../com.aspose.html.dom/node/toString/)() | Renvoie une chaîne qui représente cette instance. |
| [write](../../com.aspose.html.dom/document/write/)(params String[]) | Écrit une chaîne de texte dans un flux de document ouvert par open(). Notez que la fonction produira un document qui n'est pas nécessairement régi par une DTD et pourrait donc produire un résultat invalide dans le contexte du document. |
| [writeLn](../../com.aspose.html.dom/document/writeln/)(params String[]) | Écrit une chaîne de texte suivie d'un caractère de nouvelle ligne dans un flux de document ouvert par open(). Notez que la fonction produira un document qui n'est pas nécessairement régi par une DTD et pourrait donc produire un résultat invalide dans le contexte du document. |

## Événements

| Nom | Description |
| --- | --- |
| event [OnAbort](../../com.aspose.html.dom/document/onabort/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnAbort. |
| event [OnBlur](../../com.aspose.html.dom/document/onblur/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnBlur. |
| event [OnCancel](../../com.aspose.html.dom/document/oncancel/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnCancel. |
| event [OnCanplay](../../com.aspose.html.dom/document/oncanplay/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnCanplay. |
| event [OnCanPlayThrough](../../com.aspose.html.dom/document/oncanplaythrough/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnCanPlayThrough. |
| event [OnChange](../../com.aspose.html.dom/document/onchange/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnChange. |
| event [OnClick](../../com.aspose.html.dom/document/onclick/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnClick. |
| event [OnCueChange](../../com.aspose.html.dom/document/oncuechange/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnCueChange. |
| event [OnDblClick](../../com.aspose.html.dom/document/ondblclick/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnDblClick. |
| event [OnDurationChange](../../com.aspose.html.dom/document/ondurationchange/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnDurationChange. |
| event [OnEmptied](../../com.aspose.html.dom/document/onemptied/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnEmptied. |
| event [OnEnded](../../com.aspose.html.dom/document/onended/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnEnded. |
| event [OnError](../../com.aspose.html.dom/document/onerror/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnError. |
| event [OnFocus](../../com.aspose.html.dom/document/onfocus/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnFocus. |
| event [OnInput](../../com.aspose.html.dom/document/oninput/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnInput. |
| event [OnInvalid](../../com.aspose.html.dom/document/oninvalid/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnInvalid. |
| event [OnKeyDown](../../com.aspose.html.dom/document/onkeydown/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnKeyDown. |
| event [OnKeyPress](../../com.aspose.html.dom/document/onkeypress/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnKeyPress. |
| event [OnKeyUp](../../com.aspose.html.dom/document/onkeyup/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnKeyUp. |
| event [OnLoad](../../com.aspose.html.dom/document/onload/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnLoad. |
| event [OnLoadedData](../../com.aspose.html.dom/document/onloadeddata/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnLoadedData. |
| event [OnLoadedMetadata](../../com.aspose.html.dom/document/onloadedmetadata/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnLoadedMetadata. |
| event [OnLoadStart](../../com.aspose.html.dom/document/onloadstart/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnLoadStart. |
| event [OnMouseDown](../../com.aspose.html.dom/document/onmousedown/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnMouseDown. |
| event [OnMouseEnter](../../com.aspose.html.dom/document/onmouseenter/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnMouseEnter. |
| event [OnMouseLeave](../../com.aspose.html.dom/document/onmouseleave/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnMouseLeave. |
| event [OnMouseMove](../../com.aspose.html.dom/document/onmousemove/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnMouseMove. |
| event [OnMouseOut](../../com.aspose.html.dom/document/onmouseout/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnMouseOut. |
| event [OnMouseOver](../../com.aspose.html.dom/document/onmouseover/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnMouseOver. |
| event [OnMouseUp](../../com.aspose.html.dom/document/onmouseup/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnMouseUp. |
| event [OnMouseWheel](../../com.aspose.html.dom/document/onmousewheel/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnMouseWheel. |
| event [OnPause](../../com.aspose.html.dom/document/onpause/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnPause. |
| event [OnPlay](../../com.aspose.html.dom/document/onplay/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnPlay. |
| event [OnPlaying](../../com.aspose.html.dom/document/onplaying/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnPlaying. |
| event [OnProgress](../../com.aspose.html.dom/document/onprogress/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnProgress. |
| event [OnRateChange](../../com.aspose.html.dom/document/onratechange/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnRateChange. |
| event [OnReadyStateChange](../../com.aspose.html.dom/document/onreadystatechange/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnReadyStateChange. |
| event [OnReset](../../com.aspose.html.dom/document/onreset/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnReset. |
| event [OnResize](../../com.aspose.html.dom/document/onresize/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnResize. |
| event [OnScroll](../../com.aspose.html.dom/document/onscroll/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnScroll. |
| event [OnSeeked](../../com.aspose.html.dom/document/onseeked/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnSeeked. |
| event [OnSeeking](../../com.aspose.html.dom/document/onseeking/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnSeeking. |
| event [OnSelect](../../com.aspose.html.dom/document/onselect/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnSelect. |
| event [OnShow](../../com.aspose.html.dom/document/onshow/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnShow. |
| event [OnStalled](../../com.aspose.html.dom/document/onstalled/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnStalled. |
| event [OnSubmit](../../com.aspose.html.dom/document/onsubmit/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnSubmit. |
| event [OnSuspend](../../com.aspose.html.dom/document/onsuspend/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnSuspend. |
| event [OnTimeUpdate](../../com.aspose.html.dom/document/ontimeupdate/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnTimeUpdate. |
| event [OnToggle](../../com.aspose.html.dom/document/ontoggle/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnToggle. |
| event [OnVolumeChange](../../com.aspose.html.dom/document/onvolumechange/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnVolumeChange. |
| event [OnWaiting](../../com.aspose.html.dom/document/onwaiting/) | Obtient ou définit le gestionnaire d'événement pour l'événement OnWaiting. |

## Remarques

Plus d'informations sur HTMLDocument, Document et DOM peuvent être obtenues dans les ressources populaires de développement web :

[General Document interface](https://developer.mozilla.org/en-US/docs/Web/API/Document).[Html specific HTMLDocument interface](https://developer.mozilla.org/en-US/docs/Web/API/HTMLDocument).[What is the HTML DOM](https://www.w3schools.com/js/js_htmldom.asp).

Référence des normes :

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exemples

```java
    // Créer une instance d'un document HTML
	using (var document = new HTMLDocument())
      {
        // Créer un élément style et attribuer la couleur verte à tous les éléments dont le nom de classe est égal à 'gr'.
        var style = document.CreateElement("style");
        style.TextContent = ".gr { color: green }";

        // Trouver l'élément d'en-tête du document et ajouter l'élément style à l'en-tête
        var head = document.GetElementsByTagName("head").First();
        head.AppendChild(style);

        // Créer un élément paragraphe avec le nom de classe 'gr'.
        var p = (HTMLParagraphElement)document.CreateElement("p");
        p.ClassName = "gr";

        // Créer un nœud texte
        var text = document.CreateTextNode("Hello World!!");

        // Ajouter le nœud texte au paragraphe
        p.AppendChild(text);

        // Ajouter le paragraphe à l'élément corps du document
        document.Body.AppendChild(p);

        // Enregistrer le document HTML dans un fichier 
        document.Save(Path.Combine(OutputDir, "using-dom.html"));

        // Créer une instance du dispositif de sortie PDF et rendre le document dans ce dispositif
        using (var device = new PdfDevice(Path.Combine(OutputDir, "using-dom.pdf")))
        {
          // Rendre le HTML en PDF
          document.RenderTo(device);
        }
      }       
```

### Voir aussi

* class [Document](../../com.aspose.html.dom/document/)
* interface [IDocumentCSS](../../com.aspose.html.dom.css/idocumentcss/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
