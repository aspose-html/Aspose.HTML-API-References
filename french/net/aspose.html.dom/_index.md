---
title: Aspose.Html.Dom
second_title: Référence de l'API Aspose.HTML pour .NET
description: Le Aspose.Html.Dom modèle dobjet de document namespace fournit une API qui représente et interagit avec tous les documents HTML XML ou SVG. Le DOM est un modèle de document chargé dans le navigateur et représentant le document sous la forme dune arborescence de nœuds où chaque nœud représente une partie du document par exemple un élément un texte chaîne ou commentaire.
type: docs
weight: 40
url: /fr/net/aspose.html.dom/
---
Le **Aspose.Html.Dom (modèle d'objet de document)** namespace fournit une API qui représente et interagit avec tous les documents HTML, XML ou SVG. Le DOM est un modèle de document chargé dans le navigateur et représentant le document sous la forme d'une arborescence de nœuds, où chaque nœud représente une partie du document (par exemple, un élément, un texte chaîne ou commentaire).

## Des classes

| Classer | La description |
| --- | --- |
| [Attr](./attr) | L'interface Attr représente un attribut dans un objet Element. Généralement, les valeurs autorisées pour l'attribut sont définies dans un schéma associé au document. |
| [CDATASection](./cdatasection) | Les sections CDATA sont utilisées pour échapper des blocs de texte contenant des caractères qui seraient autrement considérés comme du balisage. |
| [CharacterData](./characterdata) | Le CharacterData étend Node avec un ensemble d'attributs et de méthodes pour accéder aux données de caractères dans le DOM. |
| [Comment](./comment) | Hérite de CharacterData et représente le contenu d'un commentaire, c'est-à-dire tous les caractères entre le ' de début . |
| [Document](./document) | Le Document représente l'intégralité du document HTML, XML ou SVG. Conceptuellement, il s'agit de la racine de l'arborescence du document et fournit l'accès principal aux données du document. |
| [DocumentFragment](./documentfragment) | DocumentFragment est un objet Document "léger" ou "minimal". Il est très courant de vouloir pouvoir extraire une partie de l'arborescence d'un document ou de créer un nouveau fragment d'un document. |
| [DocumentType](./documenttype) | Le DocumentType fournit une interface à la liste des entités qui sont définies pour le document |
| [DOMException](./domexception) | L'interface DOMException représente un événement anormal (appelé une exception) qui se produit à la suite de l'appel d'une méthode ou de l'accès à une propriété d'une API Web. C'est essentiellement ainsi que les conditions d'erreur sont décrites dans les API Web. |
| [DOMObject](./domobject) | Le type DOMObject est utilisé pour représenter un objet de base pour l'ensemble du modèle d'objet de document. Pour Java et ECMAScript, DOMObject est lié au type d'objet. |
| [Element](./element) | L'interface Element représente un élément dans un document HTML ou XML. |
| [Entity](./entity) | Représente une entité connue, analysée ou non, dans un document XML. |
| [EntityReference](./entityreference) | Les nœuds EntityReference peuvent être utilisés pour représenter une référence d'entité dans l'arborescence. |
| [EventTarget](./eventtarget) | Le[`EventTarget`](../aspose.html.dom/eventtarget) est implémentée par tous les nœuds dans une implémentation qui prend en charge le modèle d'événement DOM. Par conséquent, cette interface peut être obtenue en utilisant des méthodes de conversion spécifiques à la liaison sur une instance de l'interface de nœud. L'interface permet l'enregistrement et la suppression des écouteurs d'événement sur un[`EventTarget`](../aspose.html.dom/eventtarget) et l'envoi d'événements à ce[`IEventTarget`](../aspose.html.dom.events/ieventtarget) . |
| [Node](./node) | L'interface Node est le type de données principal pour l'ensemble du modèle d'objet Document. Il représente un nœud unique dans l'arborescence du document. |
| [Notation](./notation) | Représente une notation déclarée dans la DTD. |
| [ProcessingInstruction](./processinginstruction) | Le ProcessingInstruction représente une "instruction de traitement", utilisée en XML comme moyen de conserver des informations spécifiques au processeur dans le texte du document. |
| [ShadowRoot](./shadowroot) | ShadowRoot est un nœud racine de l'arbre fantôme. |
| [Text](./text) | L'interface Text hérite de CharacterData et représente le contenu textuel (appelé données de caractères en XML) d'un Element ou Attr. |
| [TypeInfo](./typeinfo) | Le TypeInfo représente un type référencé à partir des nœuds Element ou Attr, spécifié dans les schémas associés au document. |
## Interfaces

| Interface | La description |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext) | Un contexte de navigation est un environnement dans lequel[`Document`](../aspose.html.dom/document) les objets sont présentés à l'utilisateur. |
| [IChildNode](./ichildnode) | Définit[`IChildNode`](../aspose.html.dom/ichildnode) interface qui devrait être implémentée par[`Node`](../aspose.html.dom/node) qui peut avoir un parent. |
| [IDocumentInit](./idocumentinit) | Cette interface fournit[`Document`](../aspose.html.dom/document) informations d'initialisation. |
| [IDOMImplementation](./idomimplementation) | L'interface DOMImplementation fournit un certain nombre de méthodes pour effectuer des opérations qui sont indépendantes de toute instance particulière du modèle d'objet de document. |
| [IElementInit](./ielementinit) | Cette interface fournit[`Element`](../aspose.html.dom/element) informations d'initialisation. |
| [IGlobalEventHandlers](./iglobaleventhandlers) | Représente l'interface qui doit être héritée par tous les éléments pris en charge par la gestion des événements système |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode) | Définit[`IChildNode`](../aspose.html.dom/ichildnode) qui ne sont pas[`DOCUMENT_TYPE_NODE`](../aspose.html.dom/node/document_type_node) . |
| [INonElementParentNode](./inonelementparentnode) | Définit[`IParentNode`](../aspose.html.dom/iparentnode) qui ne sont pas de type Element. |
| [IParentNode](./iparentnode) | Définit le[`IParentNode`](../aspose.html.dom/iparentnode) interface qui est implémentée par tous les parents possibles. |
## Énumération

| Énumération | La description |
| --- | --- |
| [ShadowRootMode](./shadowrootmode) | Modes dans lesquels ShadowRoot peut fonctionner. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
