---
title: "com.aspose.html.dom"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Le package com.aspose.html.dom Document Object Model fournit une API qui représente et interagit avec tout document HTML, XML ou SVG. Le DOM est un modèle de document chargé dans le navigateur et représente le document sous forme d'arbre de nœuds où chaque nœud représente une partie du document, par exemple un élément, du texte, une String ou un commentaire."
type: docs

url: /fr/java/com.aspose.html.dom/
---
Le package **com.aspose.html.dom (Document Object Model)** fournit une API qui représente et interagit avec tout document HTML, XML ou SVG. Le DOM est un modèle de document chargé dans le navigateur et représentant le document sous forme d'arbre de nœuds, où chaque nœud représente une partie du document (par ex. un élément, une chaîne de texte ou un commentaire).

## Classes

| Classe | Description |
| --- | --- |
| [Attr](./attr/) | L'interface Attr représente un attribut dans un objet Element. Généralement, les valeurs autorisées pour l'attribut sont définies dans un schéma associé au document. |
| [CDATASection](./cdatasection/) | Les sections CDATA sont utilisées pour échapper des blocs de texte contenant des caractères qui seraient autrement considérés comme du balisage. |
| [CharacterData](./characterdata/) | Le CharacterData étend Node avec un ensemble d'attributs et de méthodes pour accéder aux données de caractères dans le DOM. |
| [Comment](./comment/) | Hérite de CharacterData et représente le contenu d'un commentaire, c'est‑à‑dire tous les caractères entre les guillemets de début ''. |
| [Document](./document/) | Le Document représente l'ensemble du document HTML, XML ou SVG. Conceptuellement, il est la racine de l'arbre du document et fournit l'accès principal aux données du document. |
| [DocumentFragment](./documentfragment/) | DocumentFragment est un objet Document "léger" ou "minimal". Il est très fréquent de vouloir extraire une partie de l'arbre d'un document ou créer un nouveau fragment d'un document. |
| [DocumentType](./documenttype/) | Le DocumentType fournit une interface vers la liste des entités définies pour le document. |
| [DOMException](./domexception/) | L'interface DOMException représente un événement anormal (appelé exception) qui se produit suite à l'appel d'une méthode ou à l'accès à une propriété d'une API web. C'est essentiellement ainsi que les conditions d'erreur sont décrites dans les API web. |
| [DOMObject](./domobject/) | Le type DOMObject est utilisé pour représenter un objet de base pour l'ensemble du Document Object Model. Pour Java et ECMAScript, DOMObject est lié au type Object. |
| [Element](./element/) | L'interface Element représente un élément dans un document HTML ou XML. |
| [Entity](./entity/) | Représente une entité connue, analysée ou non analysée, dans un document XML. |
| [EntityReference](./entityreference/) | Les nœuds EntityReference peuvent être utilisés pour représenter une référence d'entité dans l'arbre. |
| [EventTarget](./eventtarget/) | L'interface EventTarget est implémentée par les objets qui peuvent recevoir des événements et peuvent avoir des écouteurs pour ceux‑ci. En d'autres termes, toute cible d'événements implémente les trois méthodes associées à cette interface. |
| [Node](./node/) | L'interface Node est le type de données principal pour l'ensemble du Document Object Model. Elle représente un nœud unique dans l'arbre du document. Bien que tous les objets implémentant l'interface Node exposent des méthodes pour gérer les enfants, tous les objets implémentant l'interface Node ne peuvent pas avoir d'enfants. Par exemple, les nœuds [`Text`](../com.aspose.html.dom/text/) peuvent ne pas avoir d'enfants, et l'ajout d'enfants à de tels nœuds entraîne le déclenchement d'une [`DOMException`](../com.aspose.html.dom/domexception/). |
| [Notation](./notation/) | Représente une notation déclarée dans la DTD. |
| [ProcessingInstruction](./processinginstruction/) | L'interface ProcessingInstruction représente une "processing instruction", utilisée en XML comme moyen de conserver des informations spécifiques au processeur dans le texte du document. |
| [QualifiedName](./qualifiedname/) | Représente un nom qualifié HTML. |
| [ShadowRoot](./shadowroot/) | ShadowRoot est un nœud racine d'un arbre d'ombre. |
| [Text](./text/) | L'interface Text hérite de CharacterData et représente le contenu textuel (appelé données de caractères en XML) d'un Element ou d'un Attr. |
| [TypeInfo](./typeinfo/) | Le TypeInfo représente un type référencé à partir des nœuds Element ou Attr, spécifié dans les schémas associés au document. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | Un contexte de navigation est un environnement dans lequel les objets [`Document`](../com.aspose.html.dom/document/) sont présentés à l'utilisateur. |
| [IChildNode](./ichildnode/) | Définit l'interface [`IChildNode`](../com.aspose.html.dom/ichildnode/) qui doit être implémentée par le [`Node`](../com.aspose.html.dom/node/) pouvant avoir un parent. |
| [IDOMImplementation](./idomimplementation/) | L'interface DOMImplementation fournit un certain nombre de méthodes pour effectuer des opérations indépendantes de toute instance particulière du modèle d'objet document. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | Représente une interface qui doit être héritée par tout élément prenant en charge la gestion des événements système. |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | Définit les [`IChildNode`](../com.aspose.html.dom/ichildnode/) qui ne sont pas des [`DOCUMENT_TYPE_NODE`](../com.aspose.html.dom/node/document_type_node/). |
| [INonElementParentNode](./inonelementparentnode/) | Définit les [`IParentNode`](../com.aspose.html.dom/iparentnode/) qui ne sont pas de type Element. |
| [IParentNode](./iparentnode/) | Définit l'interface [`IParentNode`](../com.aspose.html.dom/iparentnode/) qui est implémentée par tout parent possible. |
| [IStorage](./istorage/) | Cette interface de l'API Web Storage fournit un accès au stockage de session ou local d'un domaine particulier. Voir la spécification Web Storage : [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage) |
## Énumération

| Énumération | Description |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | Modes dans lesquels ShadowRoot peut fonctionner. |
