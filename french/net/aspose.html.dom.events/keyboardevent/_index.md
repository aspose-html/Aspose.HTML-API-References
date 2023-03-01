---
title: Class KeyboardEvent
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Dom.Events.KeyboardEvent classe. Linterface KeyboardEvent fournit des informations contextuelles spécifiques associées aux périphériques clavier. Chaque événement de clavier fait référence à une touche à laide dune valeur. Les événements de clavier sont généralement dirigés vers lélément qui a le focus.
type: docs
weight: 830
url: /fr/net/aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

L'interface KeyboardEvent fournit des informations contextuelles spécifiques associées aux périphériques clavier. Chaque événement de clavier fait référence à une touche à l'aide d'une valeur. Les événements de clavier sont généralement dirigés vers l'élément qui a le focus.

```csharp
public class KeyboardEvent : UIEvent
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(string) | Initialise une nouvelle instance du`KeyboardEvent` classe. |
| [KeyboardEvent](keyboardevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Initialise une nouvelle instance du`KeyboardEvent` classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/keyboardevent/altkey/) { get; } | vrai si le modificateur de touche Alt (alternative) (ou "Option") était actif. La valeur non initialisée de cet attribut DOIT être fausse. |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Utilisé pour indiquer si un événement est un événement bouillonnant ou non. Si l'événement peut faire des bulles, la valeur est true, sinon la valeur est false. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Utilisé pour indiquer si un événement peut ou non voir son action par défaut empêchée. Si l'action par défaut peut être empêchée, la valeur est true, sinon la valeur est false. |
| [Code](../../aspose.html.dom.events/keyboardevent/code/) { get; } | Le code contient une chaîne qui identifie la touche physique enfoncée. La valeur n'est pas affectée par la disposition actuelle du clavier ou l'état du modificateur, donc une touche particulière renverra toujours la même valeur. |
| [CtrlKey](../../aspose.html.dom.events/keyboardevent/ctrlkey/) { get; } | true si le modificateur de clé Control (contrôle) était actif. La valeur non initialisée de cet attribut DOIT être false. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Utilisé pour indiquer le[`IEventTarget`](../ieventtarget/) dont[`IEventListener`](../ieventlistener/) s sont en cours de traitement. Ceci est particulièrement utile lors de la capture et du bouillonnement. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Renvoie true si preventDefault() a été invoqué alors que la valeur de l'attribut annulable est true, et false sinon. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | Spécifie des informations détaillées sur l'événement, selon le type d'événement. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Utilisé pour indiquer quelle phase du flux d'événements est actuellement en cours d'évaluation. |
| [IsComposing](../../aspose.html.dom.events/keyboardevent/iscomposing/) { get; } | true si l'événement clé se produit dans le cadre d'une session de composition, c'est-à-dire après un événement compositionstart et avant l'événement compositionend correspondant. La valeur non initialisée de cet attribut DOIT être fausse. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | L'attribut isTrusted doit renvoyer la valeur à laquelle il a été initialisé. Lorsqu'un événement est créé, l'attribut doit être initialisé à false. |
| [Key](../../aspose.html.dom.events/keyboardevent/key/) { get; } | La clé contient la valeur clé de la touche enfoncée. Si la valeur a une représentation imprimée, elle DOIT être une chaîne de caractères Unicode non vide, conforme à l'algorithme de détermination de la valeur de clé défini dans la présente spécification. Si la valeur est une clé de contrôle qui n'a pas de représentation imprimée, elle DOIT être l'une des valeurs de clé définies dans l'ensemble de valeurs de clé, tel que déterminé par l'algorithme de détermination de la valeur de clé. Les implémentations incapables d'identifier une clé DOIVENT utiliser la valeur de clé Unidentified. |
| [Location](../../aspose.html.dom.events/keyboardevent/location/) { get; } | L'attribut location contient une indication de l'emplacement logique de la clé sur l'appareil. |
| [MetaKey](../../aspose.html.dom.events/keyboardevent/metakey/) { get; } | true si le modificateur de clé meta (Meta) était actif. |
| [Repeat](../../aspose.html.dom.events/keyboardevent/repeat/) { get; } | vrai si la touche a été appuyée de manière soutenue. Maintenir une touche enfoncée DOIT entraîner la répétition des événements keydown, beforeinput, input dans cet ordre, à un rythme déterminé par la configuration du système. Pour les appareils mobiles qui ont un comportement d'appui long sur une touche, le premier événement de touche avec une valeur d'attribut de répétition de vrai DOIT servir d'indication d'un appui long sur une touche. La durée pendant laquelle la touche DOIT être enfoncée pour commencer à répéter dépend de la configuration. |
| [ShiftKey](../../aspose.html.dom.events/keyboardevent/shiftkey/) { get; } | vrai si le modificateur de touche Maj (Maj) était actif. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Utilisé pour indiquer le[`IEventTarget`](../ieventtarget/) auquel l'événement a été envoyé à l'origine. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Utilisé pour spécifier l'heure (en millisecondes par rapport à l'époque) à laquelle l'événement a été créé. En raison du fait que certains systèmes peuvent ne pas fournir ces informations, la valeur de timeStamp peut ne pas être disponible pour tous les événements. Lorsqu'il n'est pas disponible , une valeur de 0 sera renvoyée. Des exemples d'heure d'époque sont l'heure de démarrage du système ou 0:0:0 UTC le 1er janvier 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | Le nom de l'événement (insensible à la casse). Le nom doit être un nom XML. |
| [View](../../aspose.html.dom.events/uievent/view/) { get; } | L'attribut view identifie la fenêtre à partir de laquelle l'événement a été généré. La valeur non initialisée de cet attribut DOIT être nulle. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScriptType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | Le[`InitEvent`](../event/initevent/) méthode est utilisée pour initialiser la valeur d'un[`Event`](../event/) créé via the [`IDocumentEvent`](../idocumentevent/) interface. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Si un événement est annulable, le[`PreventDefault`](../event/preventdefault/) est utilisée pour signifier que l'événement doit être annulé, ce qui signifie que toute action par défaut normalement entreprise par l'implémentation à la suite de l'événement ne se produira pas. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | L'appel de cette méthode empêche l'événement d'atteindre les écouteurs d'événement enregistrés après celui en cours et, lorsqu'il est distribué dans une arborescence, empêche également l'événement d'atteindre tout autre objet. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | Le[`StopPropagation`](../event/stoppropagation/) méthode est utilisée pour empêcher la propagation ultérieure d'un événement pendant le flux d'événements. |

## Des champs

| Nom | La description |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../aspose.html.dom.events/keyboardevent/dom_key_location_left/) | La clé activée provient de l'emplacement de la clé de gauche (lorsqu'il existe plusieurs emplacements possibles pour cette clé). |
| const [DOM_KEY_LOCATION_NUMPAD](../../aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | L'activation de la touche provient du clavier numérique ou d'une touche virtuelle correspondant au clavier numérique (lorsqu'il y a plusieurs emplacements possibles pour cette touche). Notez que la clé NumLock doit toujours être encodée avec un emplacement de DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../aspose.html.dom.events/keyboardevent/dom_key_location_right/) | L'activation de la clé provient du bon emplacement de clé (lorsqu'il existe plusieurs emplacements possibles pour cette clé). |
| const [DOM_KEY_LOCATION_STANDARD](../../aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | L'activation de la touche NE DOIT PAS être distinguée comme la version gauche ou droite de la touche, et (autre que la touche NumLock) ne provient pas du pavé numérique (ou ne provient pas d'une touche virtuelle correspondant au pavé numérique). |

### Voir également

* class [UIEvent](../uievent/)
* espace de noms [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* Assemblée [Aspose.HTML](../../)


