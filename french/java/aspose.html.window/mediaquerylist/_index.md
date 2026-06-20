---
title: "Classe MediaQueryList"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.window.MediaQueryList. Un objet MediaQueryList stocke des informations sur une requête média appliquée à un document avec prise en charge du correspondance immédiate et basée sur les événements par rapport à l'état du document. Voir la spécification du module Vue CSSOM https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs

url: /fr/java/com.aspose.html.window/mediaquerylist/
---
## MediaQueryList class

Un objet MediaQueryList stocke des informations sur une requête média appliquée à un document, avec prise en charge à la fois du correspondance immédiate et de la correspondance déclenchée par des événements par rapport à l'état du document. Voir la spécification du module Vue CSSOM : [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```java
public class MediaQueryList : EventTarget
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getDocument](../../com.aspose.html.window/mediaquerylist/document/) Document associé à l'objet de contexte. |
| [getMatches](../../com.aspose.html.window/mediaquerylist/matches/) Une valeur booléenne qui renvoie true si le document correspond actuellement à la liste de requêtes média, ou false sinon. |
| [getMedia](../../com.aspose.html.window/mediaquerylist/media/) Une chaîne représentant une requête média sérialisée. |

## Méthodes

| Nom | Description |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | La méthode addEventListener() de l'interface [`EventTarget `](../../com.aspose.html.dom/eventtarget/) configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | La méthode addEventListener() de l'interface [EventTarget ](T:com.aspose.html.dom.EventTarget) configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | La méthode addEventListener() de l'interface [EventTarget ](T:com.aspose.html.dom.EventTarget) configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible. |
| [addListener](../../com.aspose.html.window/mediaquerylist/addlistener/)(IEventListener) | Ajouter un écouteur d'événement de changement d'état des correspondances MediaQueryList. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Déclenche un Event sur le [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) spécifié, (synchroniquement) en invoquant les EventListeners concernés dans l'ordre approprié. Les règles normales de traitement des événements (y compris les phases de capture et de bouillonnement optionnelles) s'appliquent également aux événements déclenchés manuellement avec [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Effectue les tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [removeListener](../../com.aspose.html.window/mediaquerylist/removelistener/)(IEventListener) | Supprimer l'écouteur d'événement de changement d'état des correspondances MediaQueryList. |

## Événements

| Nom | Description |
| --- | --- |
| event [OnChange](../../com.aspose.html.window/mediaquerylist/onchange/) | Événement déclenché sur le MediaQueryList lorsque l'état des correspondances change. |

### Voir aussi

* class [EventTarget](../../com.aspose.html.dom/eventtarget/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
