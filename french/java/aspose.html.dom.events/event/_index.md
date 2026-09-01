---
title: "Classe Event"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.dom.events.Event class. La classe est utilisée pour fournir des informations contextuelles sur un événement au gestionnaire qui traite l'événement"
type: docs

url: /fr/java/com.aspose.html.dom.events/event/
---
## Event class

Le est utilisé pour fournir des informations contextuelles sur un événement au gestionnaire qui traite l'événement.

```java
public class Event : DOMObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Event](event/#constructor)(String) | Initialise une nouvelle instance de la classe `Event`. |
| [Event](event/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Propriétés

| Nom | Description |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Utilisé pour indiquer si un événement est un événement de propagation (bubbling) ou non. Si l'événement peut se propager, la valeur est vraie, sinon la valeur est fausse. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Utilisé pour indiquer si un événement peut voir son action par défaut empêchée. Si l'action par défaut peut être empêchée, la valeur est vraie, sinon la valeur est fausse. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Utilisé pour indiquer le [`IEventTarget`](../ieventtarget/) dont les [`IEventListener`](../ieventlistener/) sont actuellement en cours de traitement. Ceci est particulièrement utile lors de la capture et de la propagation. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Retourne vrai si preventDefault() a été invoqué alors que la valeur de l'attribut cancelable est vraie, et faux sinon. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Utilisé pour indiquer quelle phase du flux d'événements est actuellement évaluée. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) L'attribut isTrusted doit renvoyer la valeur à laquelle il a été initialisé. Lorsqu'un événement est créé, l'attribut doit être initialisé à false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Utilisé pour indiquer le [`IEventTarget`](../ieventtarget/) auquel l'événement a été initialement diffusé. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Utilisé pour spécifier le temps (en millisecondes relatives à l'époque) auquel l'événement a été créé. Étant donné que certains systèmes peuvent ne pas fournir cette information, la valeur de timeStamp peut ne pas être disponible pour tous les événements. Lorsqu'elle n'est pas disponible, une valeur de 0 sera renvoyée. Des exemples de temps d'époque sont le moment du démarrage du système ou 0:0:0 UTC le 1er janvier 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Le nom de l'événement (insensible à la casse). Le nom doit être un nom XML. |

## Méthodes

| Nom | Description |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | La méthode [`InitEvent`](./initevent/) est utilisée pour initialiser la valeur d'un `Event` créé via l'interface [`IDocumentEvent`](../idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Si un événement est annulable, la méthode [`PreventDefault`](./preventdefault/) est utilisée pour indiquer que l'événement doit être annulé, ce qui signifie qu'aucune action par défaut normalement exécutée par l'implémentation à la suite de l'événement ne se produira. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | L'appel de cette méthode empêche l'événement d'atteindre les écouteurs d'événements enregistrés après celui-ci et, lorsqu'il est diffusé dans un arbre, empêche également l'événement d'atteindre tout autre objet. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | La méthode [`StopPropagation`](./stoppropagation/) est utilisée pour empêcher la propagation supplémentaire d'un événement pendant le flux d'événements. |

## Champs

| Nom | Description |
| --- | --- |
| const [AtTargetPhase](../../com.aspose.html.dom.events/event/attargetphase/) | La phase actuelle de l'événement est la phase de capture. |
| const [BubblingPhase](../../com.aspose.html.dom.events/event/bubblingphase/) | La phase actuelle de l'événement est la phase de remontée. |
| const [CapturingPhase](../../com.aspose.html.dom.events/event/capturingphase/) | L'événement est actuellement évalué sur la cible [`IEventTarget`](../ieventtarget/). |
| const [NonePhase](../../com.aspose.html.dom.events/event/nonephase/) | Les événements qui ne sont pas actuellement dispatchés se trouvent dans cette phase. |

## Remarques

Un objet qui implémente le est généralement passé comme premier paramètre à un gestionnaire d'événement. Des informations contextuelles plus spécifiques sont transmises aux gestionnaires d'événement en dérivant des interfaces supplémentaires qui contiennent des informations directement liées au type d'événement qu'elles accompagnent. Ces interfaces dérivées sont également implémentées par l'objet passé à l'écouteur d'événement.

### Voir aussi

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
