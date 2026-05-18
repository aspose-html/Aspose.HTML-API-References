---
title: "Classe ErrorEvent"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Classe com.aspose.html.dom.events.ErrorEvent. L'ErrorEvent fournit des informations contextuelles sur une erreur survenue pendant l'exécution"
type: docs

url: /fr/java/com.aspose.html.dom.events/errorevent/
---
## ErrorEvent class

L'ErrorEvent fournit des informations contextuelles sur les erreurs survenues pendant l'exécution.

```java
public class ErrorEvent : Event
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ErrorEvent](errorevent/#constructor_1)(Exception) | Initialise une nouvelle instance de la classe `ErrorEvent`. |
| [ErrorEvent](errorevent/#constructor)(IDictionary&lt;String, object&gt;) |  |

## Propriétés

| Nom | Description |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Utilisé pour indiquer si un événement est un événement de propagation (bubbling) ou non. Si l'événement peut se propager, la valeur est vraie, sinon la valeur est fausse. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Utilisé pour indiquer si un événement peut voir son action par défaut empêchée. Si l'action par défaut peut être empêchée, la valeur est vraie, sinon la valeur est fausse. |
| [getColNo](../../com.aspose.html.dom.events/errorevent/colno/) L'attribut colno doit renvoyer la valeur à laquelle il a été initialisé. Lors de la création de l'objet, cet attribut doit être initialisé à zéro. Il représente le numéro de colonne où l'erreur s'est produite dans le script. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Utilisé pour indiquer le [`IEventTarget`](../ieventtarget/) dont les [`IEventListener`](../ieventlistener/) sont actuellement en cours de traitement. Ceci est particulièrement utile lors de la capture et de la propagation. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Retourne vrai si preventDefault() a été invoqué alors que la valeur de l'attribut cancelable est vraie, et faux sinon. |
| [getError](../../com.aspose.html.dom.events/errorevent/error/) L'attribut error doit renvoyer la valeur à laquelle il a été initialisé. Lors de la création de l'objet, cet attribut doit être initialisé à null. Le cas échéant, il est défini sur l'objet représentant l'erreur (par ex. l'objet exception dans le cas d'une exception DOM non interceptée). |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Utilisé pour indiquer quelle phase du flux d'événements est actuellement évaluée. |
| [getFileName](../../com.aspose.html.dom.events/errorevent/filename/) L'attribut filename doit renvoyer la valeur à laquelle il a été initialisé. Lors de la création de l'objet, cet attribut doit être initialisé à la chaîne vide. Il représente l'URL absolue du script dans lequel l'erreur s'est initialement produite. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) L'attribut isTrusted doit renvoyer la valeur à laquelle il a été initialisé. Lorsqu'un événement est créé, l'attribut doit être initialisé à false. |
| [getLineNo](../../com.aspose.html.dom.events/errorevent/lineno/) L'attribut lineno doit renvoyer la valeur à laquelle il a été initialisé. Lorsqu'un objet est créé, cet attribut doit être initialisé à zéro. Il représente le numéro de ligne où l'erreur s'est produite dans le script. |
| [getMessage](../../com.aspose.html.dom.events/errorevent/message/) L'attribut message doit renvoyer la valeur à laquelle il a été initialisé. Lorsqu'un objet est créé, cet attribut doit être initialisé à la chaîne vide. Il représente le message d'erreur. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Utilisé pour indiquer le [`IEventTarget`](../ieventtarget/) auquel l'événement a été initialement diffusé. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Utilisé pour spécifier le temps (en millisecondes relatives à l'époque) auquel l'événement a été créé. Étant donné que certains systèmes peuvent ne pas fournir cette information, la valeur de timeStamp peut ne pas être disponible pour tous les événements. Lorsqu'elle n'est pas disponible, une valeur de 0 sera renvoyée. Des exemples de temps d'époque sont le moment du démarrage du système ou 0:0:0 UTC le 1er janvier 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Le nom de l'événement (insensible à la casse). Le nom doit être un nom XML. |

## Méthodes

| Nom | Description |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | La méthode [`InitEvent`](../event/initevent/) est utilisée pour initialiser la valeur d'un [`Event`](../event/) créé via l'interface [`IDocumentEvent`](../idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Si un événement est annulable, la méthode [`PreventDefault`](../event/preventdefault/) est utilisée pour indiquer que l'événement doit être annulé, ce qui signifie qu'aucune action par défaut normalement exécutée par l'implémentation à la suite de l'événement ne se produira. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | L'appel de cette méthode empêche l'événement d'atteindre les écouteurs d'événements enregistrés après celui-ci et, lorsqu'il est diffusé dans un arbre, empêche également l'événement d'atteindre tout autre objet. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | La méthode [`StopPropagation`](../event/stoppropagation/) est utilisée pour empêcher la propagation supplémentaire d'un événement pendant le flux d'événements. |

### Voir aussi

* class [Event](../event/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
