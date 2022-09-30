---
title: MouseEvent
second_title: Référence de l'API Aspose.HTML pour .NET
description: Linterface MouseEvent fournit des informations contextuelles spécifiques associées aux événements de souris.
type: docs
weight: 850
url: /fr/net/aspose.html.dom.events/mouseevent/
---
## MouseEvent class

L'interface MouseEvent fournit des informations contextuelles spécifiques associées aux événements de souris.

```csharp
public class MouseEvent : UIEvent
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [MouseEvent](mouseevent#constructor)(string) | Initialise une nouvelle instance du[`MouseEvent`](../mouseevent) classe. |
| [MouseEvent](mouseevent#constructor_1)(string, IDictionary&lt;string, object&gt;) | Initialise une nouvelle instance du[`MouseEvent`](../mouseevent) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/mouseevent/altkey) { get; } | Reportez-vous à l'attribut altKey. |
| [Bubbles](../../aspose.html.dom.events/event/bubbles) { get; } | Utilisé pour indiquer si un événement est un événement bouillonnant ou non. Si l'événement peut faire des bulles, la valeur est true, sinon la valeur est false. |
| [Button](../../aspose.html.dom.events/mouseevent/button) { get; } | Lors d'événements de souris provoqués par l'enfoncement ou le relâchement d'un bouton de la souris, le bouton DOIT être utilisé pour indiquer quel bouton du dispositif de pointage a changé d'état. |
| [Buttons](../../aspose.html.dom.events/mouseevent/buttons) { get; } | Lors de tout événement de souris, les boutons DOIVENT être utilisés pour indiquer quelle combinaison de boutons de souris est actuellement enfoncée, exprimée sous la forme d'un masque de bits. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable) { get; } | Utilisé pour indiquer si un événement peut ou non voir son action par défaut empêchée. Si l'action par défaut peut être empêchée, la valeur est true, sinon la valeur est false. |
| [ClientX](../../aspose.html.dom.events/mouseevent/clientx) { get; } | La coordonnée horizontale à laquelle l'événement s'est produit par rapport à la fenêtre associée à l'événement. |
| [ClientY](../../aspose.html.dom.events/mouseevent/clienty) { get; } | La coordonnée verticale à laquelle l'événement s'est produit par rapport à la fenêtre associée à l'événement. |
| [CtrlKey](../../aspose.html.dom.events/mouseevent/ctrlkey) { get; } | Reportez-vous à l'attribut ctrlKey. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget) { get; } | Utilisé pour indiquer le[`IEventTarget`](../ieventtarget) à qui[`IEventListener`](../ieventlistener) s sont en cours de traitement. Ceci est particulièrement utile lors de la capture et du bouillonnement. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented) { get; } | Renvoie true si preventDefault() a été invoqué alors que la valeur de l'attribut annulable est true, et false sinon. |
| [Detail](../../aspose.html.dom.events/uievent/detail) { get; } | Spécifie des informations détaillées sur l'événement, selon le type d'événement. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase) { get; } | Utilisé pour indiquer quelle phase du flux d'événements est actuellement en cours d'évaluation. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted) { get; } | L'attribut isTrusted doit renvoyer la valeur à laquelle il a été initialisé. Lorsqu'un événement est créé, l'attribut doit être initialisé à false. |
| [MetaKey](../../aspose.html.dom.events/mouseevent/metakey) { get; } | Reportez-vous à l'attribut metaKey. |
| [RelatedTarget](../../aspose.html.dom.events/mouseevent/relatedtarget) { get; } | Utilisé pour identifier un EventTarget secondaire lié à un événement UI, selon le type d'événement. |
| [ScreenX](../../aspose.html.dom.events/mouseevent/screenx) { get; } | La coordonnée horizontale à laquelle l'événement s'est produit par rapport à l'origine du système de coordonnées de l'écran. |
| [ScreenY](../../aspose.html.dom.events/mouseevent/screeny) { get; } | La coordonnée verticale à laquelle l'événement s'est produit par rapport à l'origine du système de coordonnées de l'écran. |
| [ShiftKey](../../aspose.html.dom.events/mouseevent/shiftkey) { get; } | Reportez-vous à l'attribut shiftKey. |
| [Target](../../aspose.html.dom.events/event/target) { get; } | Utilisé pour indiquer le[`IEventTarget`](../ieventtarget) auquel l'événement a été envoyé à l'origine. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp) { get; } | Utilisé pour spécifier l'heure (en millisecondes par rapport à l'époque) à laquelle l'événement a été créé. En raison du fait que certains systèmes peuvent ne pas fournir ces informations, la valeur de timeStamp peut ne pas être disponible pour tous les événements. Lorsqu'il n'est pas disponible , une valeur de 0 sera renvoyée. Des exemples d'heure d'époque sont l'heure de démarrage du système ou 0:0:0 UTC le 1er janvier 1970. |
| [Type](../../aspose.html.dom.events/event/type) { get; } | Le nom de l'événement (insensible à la casse). Le nom doit être un nom XML. |
| [View](../../aspose.html.dom.events/uievent/view) { get; } | L'attribut view identifie la fenêtre à partir de laquelle l'événement a été généré. La valeur non initialisée de cet attribut DOIT être nulle. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | Cette méthode est utilisée pour récupérer l'objet ECMAScriptType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent)(string, bool, bool) | Le[`InitEvent`](../event/initevent) méthode est utilisée pour initialiser la valeur d'un[`Event`](../event) créé via the [`IDocumentEvent`](../idocumentevent) interface. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault)() | Si un événement est annulable, le[`PreventDefault`](../event/preventdefault) est utilisée pour signifier que l'événement doit être annulé, ce qui signifie que toute action par défaut normalement prise par l'implémentation à la suite de l'événement ne se produira pas. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation)() | L'appel de cette méthode empêche l'événement d'atteindre les écouteurs d'événements enregistrés après celui en cours et, lorsqu'il est distribué dans une arborescence, empêche également l'événement d'atteindre d'autres objets. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation)() | Le[`StopPropagation`](../event/stoppropagation) méthode est utilisée pour empêcher la propagation ultérieure d'un événement pendant le flux d'événements. |

### Voir également

* class [UIEvent](../uievent)
* espace de noms [Aspose.Html.Dom.Events](../../aspose.html.dom.events)
* Assemblée [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
