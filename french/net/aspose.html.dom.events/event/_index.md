---
title: Event
second_title: Référence de l'API Aspose.HTML pour .NET
description: LeEvent./event est utilisé pour fournir des informations contextuelles sur un événement au gestionnaire traitant lévénement.
type: docs
weight: 780
url: /fr/net/aspose.html.dom.events/event/
---
## Event class

Le[`Event`](../event) est utilisé pour fournir des informations contextuelles sur un événement au gestionnaire traitant l'événement.

```csharp
public class Event : DOMObject
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Event](event#constructor)(string) | Initialise une nouvelle instance du[`Event`](../event) classe. |
| [Event](event#constructor_1)(string, IDictionary&lt;string, object&gt;) | Initialise une nouvelle instance du[`Event`](../event) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles) { get; } | Utilisé pour indiquer si un événement est un événement bouillonnant ou non. Si l'événement peut faire des bulles, la valeur est true, sinon la valeur est false. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable) { get; } | Utilisé pour indiquer si un événement peut ou non voir son action par défaut empêchée. Si l'action par défaut peut être empêchée, la valeur est true, sinon la valeur est false. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget) { get; } | Utilisé pour indiquer le[`IEventTarget`](../ieventtarget) à qui[`IEventListener`](../ieventlistener) s sont en cours de traitement. Ceci est particulièrement utile lors de la capture et du bouillonnement. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented) { get; } | Renvoie true si preventDefault() a été invoqué alors que la valeur de l'attribut annulable est true, et false sinon. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase) { get; } | Utilisé pour indiquer quelle phase du flux d'événements est actuellement en cours d'évaluation. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted) { get; } | L'attribut isTrusted doit renvoyer la valeur à laquelle il a été initialisé. Lorsqu'un événement est créé, l'attribut doit être initialisé à false. |
| [Target](../../aspose.html.dom.events/event/target) { get; } | Utilisé pour indiquer le[`IEventTarget`](../ieventtarget) auquel l'événement a été envoyé à l'origine. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp) { get; } | Utilisé pour spécifier l'heure (en millisecondes par rapport à l'époque) à laquelle l'événement a été créé. En raison du fait que certains systèmes peuvent ne pas fournir ces informations, la valeur de timeStamp peut ne pas être disponible pour tous les événements. Lorsqu'il n'est pas disponible , une valeur de 0 sera renvoyée. Des exemples d'heure d'époque sont l'heure de démarrage du système ou 0:0:0 UTC le 1er janvier 1970. |
| [Type](../../aspose.html.dom.events/event/type) { get; } | Le nom de l'événement (insensible à la casse). Le nom doit être un nom XML. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | Cette méthode est utilisée pour récupérer l'objet ECMAScriptType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent)(string, bool, bool) | Le[`InitEvent`](./initevent) méthode est utilisée pour initialiser la valeur d'un[`Event`](../event) créé via the [`IDocumentEvent`](../idocumentevent) interface. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault)() | Si un événement est annulable, le[`PreventDefault`](./preventdefault) est utilisée pour signifier que l'événement doit être annulé, ce qui signifie que toute action par défaut normalement prise par l'implémentation à la suite de l'événement ne se produira pas. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation)() | L'appel de cette méthode empêche l'événement d'atteindre les écouteurs d'événements enregistrés après celui en cours et, lorsqu'il est distribué dans une arborescence, empêche également l'événement d'atteindre d'autres objets. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation)() | Le[`StopPropagation`](./stoppropagation) méthode est utilisée pour empêcher la propagation ultérieure d'un événement pendant le flux d'événements. |

## Des champs

| Nom | La description |
| --- | --- |
| const [AtTargetPhase](../../aspose.html.dom.events/event/attargetphase) | La phase d'événement actuelle est la phase de capture. |
| const [BubblingPhase](../../aspose.html.dom.events/event/bubblingphase) | La phase d'événement actuelle est la phase de bouillonnement. |
| const [CapturingPhase](../../aspose.html.dom.events/event/capturingphase) | L'événement est en cours d'évaluation à la cible[`IEventTarget`](../ieventtarget) . |
| const [NonePhase](../../aspose.html.dom.events/event/nonephase) | Les événements non distribués actuellement sont dans cette phase. |

### Remarques

Un objet qui implémente le[`Event`](../event) est généralement transmis comme premier paramètre à un gestionnaire d'événements. Des informations de contexte plus spécifiques sont transmises aux gestionnaires d'événements en dérivant des interfaces supplémentaires à partir de[`Event`](../event) qui contiennent des informations directement liées au type d'événement qu'elles accompagnent. Ces interfaces dérivées sont également implémentées par l'objet passé à l'écouteur d'événement.

### Voir également

* class [DOMObject](../../aspose.html.dom/domobject)
* espace de noms [Aspose.Html.Dom.Events](../../aspose.html.dom.events)
* Assemblée [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
