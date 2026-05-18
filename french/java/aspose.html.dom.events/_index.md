---
title: "com.aspose.html.dom.events"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Le package com.aspose.html.dom.events fournit des objets pour tous les événements liés à la mise à jour du DOM. Il inclut l'abonnement à l'observation d'informations contextuelles spécifiques associées à un événement ainsi que la construction d'événements personnalisés."
type: docs

url: /fr/java/com.aspose.html.dom.events/
---
Le package **com.aspose.html.dom.events** fournit des objets pour tous les événements liés à la mise à jour du DOM. Il inclut l'abonnement à l'observation d'informations contextuelles spécifiques associées à un événement ainsi que la construction d'événements personnalisés.

## Classes

| Classe | Description |
| --- | --- |
| [CustomEvent](./customevent/) | Les événements utilisant l'interface CustomEvent peuvent être utilisés pour transporter des données personnalisées. |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | L'événement DocumentLoadErrorEvent se produit lorsque la ressource demandée n'est pas disponible. |
| [DOMEventHandler](./domeventhandler/) | Représente un délégué générique de rappel pour la gestion des événements du Document Object Model (DOM). |
| [ErrorEvent](./errorevent/) | L'ErrorEvent fournit des informations contextuelles sur les erreurs survenues pendant l'exécution. |
| [Event](./event/) | Le est utilisé pour fournir des informations contextuelles sur un événement au gestionnaire qui traite l'événement. |
| [FocusEvent](./focusevent/) | L'interface FocusEvent fournit des informations contextuelles spécifiques associées aux événements Focus. |
| [InputEvent](./inputevent/) | Les événements d'entrée sont envoyés sous forme de notifications chaque fois que le DOM est mis à jour. |
| [KeyboardEvent](./keyboardevent/) | L'interface KeyboardEvent fournit des informations contextuelles spécifiques associées aux périphériques clavier. Chaque événement clavier fait référence à une touche à l'aide d'une valeur. Les événements clavier sont généralement dirigés vers l'élément qui a le focus. |
| [MouseEvent](./mouseevent/) | L'interface MouseEvent fournit des informations contextuelles spécifiques associées aux événements de souris. |
| [UIEvent](./uievent/) | L'interface UIEvent fournit des informations contextuelles spécifiques associées aux événements d'interface utilisateur. |
| [WheelEvent](./wheelevent/) | L'interface WheelEvent fournit des informations contextuelles spécifiques associées aux événements de molette. Pour créer une instance de l'interface WheelEvent, utilisez le constructeur WheelEvent en passant un dictionnaire optionnel WheelEventInit. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | L'interface DocumentEvent fournit un mécanisme permettant à l'utilisateur de créer un Event d'un type pris en charge par l'implémentation. Il est prévu que l'interface DocumentEvent soit implémentée sur le même objet qui implémente l'interface Document dans une implémentation qui prend en charge le modèle d'événements. |
| [IEventListener](./ieventlistener/) | L'interface est la méthode principale pour gérer les événements. Les utilisateurs implémentent l'interface et enregistrent leur écouteur sur un en utilisant la méthode. Les utilisateurs doivent également les supprimer de celui-ci après avoir terminé d'utiliser l'écouteur. |
| [IEventTarget](./ieventtarget/) | L'interface EventTarget est implémentée par tous les nœuds dans une implémentation qui prend en charge le modèle d'événements DOM. Par conséquent, cette interface peut être obtenue en utilisant des méthodes de cast spécifiques au binding sur une instance de l'interface Node. L'interface permet l'enregistrement et la suppression d'écouteurs d'événements sur un et la diffusion d'événements vers celui-ci. |
