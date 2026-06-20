---
title: "Classe KeyboardEvent"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Classe com.aspose.html.dom.events.KeyboardEvent. L'interface KeyboardEvent fournit des informations contextuelles spécifiques associées aux dispositifs clavier. Chaque événement clavier fait référence à une touche à l'aide d'une valeur. Les événements clavier sont généralement dirigés vers l'élément qui a le focus."
type: docs

url: /fr/java/com.aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

L'interface KeyboardEvent fournit des informations contextuelles spécifiques associées aux périphériques clavier. Chaque événement clavier fait référence à une touche à l'aide d'une valeur. Les événements clavier sont généralement dirigés vers l'élément qui a le focus.

```java
public class KeyboardEvent : UIEvent
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(String) | Initialise une nouvelle instance de la classe `KeyboardEvent`. |
| [KeyboardEvent](keyboardevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Propriétés

| Nom | Description |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/keyboardevent/altkey/) true si le modificateur de touche Alt (alternative) (ou \"Option\") était actif. La valeur non initialisée de cet attribut DOIT être false. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Utilisé pour indiquer si un événement est un événement de propagation (bubbling) ou non. Si l'événement peut se propager, la valeur est vraie, sinon la valeur est fausse. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Utilisé pour indiquer si un événement peut voir son action par défaut empêchée. Si l'action par défaut peut être empêchée, la valeur est vraie, sinon la valeur est fausse. |
| [getCode](../../com.aspose.html.dom.events/keyboardevent/code/) Le code contient une chaîne qui identifie la touche physique en cours de pression. La valeur n'est pas affectée par la disposition actuelle du clavier ou l'état des modificateurs, ainsi une touche particulière renverra toujours la même valeur. |
| [getCtrlKey](../../com.aspose.html.dom.events/keyboardevent/ctrlkey/) true si le modificateur de touche Control (contrôle) était actif. La valeur non initialisée de cet attribut DOIT être false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Utilisé pour indiquer le [`IEventTarget`](../ieventtarget/) dont les [`IEventListener`](../ieventlistener/) sont actuellement en cours de traitement. Ceci est particulièrement utile lors de la capture et de la propagation. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Retourne vrai si preventDefault() a été invoqué alors que la valeur de l'attribut cancelable est vraie, et faux sinon. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Spécifie certaines informations détaillées sur l'événement, en fonction du type d'événement. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Utilisé pour indiquer quelle phase du flux d'événements est actuellement évaluée. |
| [getIsComposing](../../com.aspose.html.dom.events/keyboardevent/iscomposing/) true si l'événement de touche se produit dans le cadre d'une session de composition, c'est-à-dire après un événement compositionstart et avant l'événement compositionend correspondant. La valeur non initialisée de cet attribut DOIT être false. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) L'attribut isTrusted doit renvoyer la valeur à laquelle il a été initialisé. Lorsqu'un événement est créé, l'attribut doit être initialisé à false. |
| [getKey](../../com.aspose.html.dom.events/keyboardevent/key/) La clé contient la valeur de la touche enfoncée. Si la valeur possède une représentation imprimée, elle DOIT être une chaîne de caractères Unicode non vide, conforme à l'algorithme de détermination de la valeur de la touche défini dans cette spécification. Si la valeur est une touche de contrôle qui n'a pas de représentation imprimée, elle DOIT être l'une des valeurs de touche définies dans l'ensemble des valeurs de touche, tel que déterminé par l'algorithme de détermination de la valeur de la touche. Les implémentations qui ne peuvent pas identifier une touche DOIT utiliser la valeur de touche Unidentified. |
| [getLocation](../../com.aspose.html.dom.events/keyboardevent/location/) L'attribut location contient une indication de l'emplacement logique de la touche sur le dispositif. |
| [getMetaKey](../../com.aspose.html.dom.events/keyboardevent/metakey/) true si le modificateur de touche meta (Meta) était actif. |
| [getRepeat](../../com.aspose.html.dom.events/keyboardevent/repeat/) true si la touche a été enfoncée de manière soutenue. Maintenir une touche enfoncée DOIT entraîner la répétition des événements keydown, beforeinput, input dans cet ordre, à une fréquence déterminée par la configuration du système. Pour les appareils mobiles qui ont un comportement de pression longue, le premier événement de touche avec une valeur d'attribut repeat égale à true DOIT servir d'indication d'une pression longue. La durée pendant laquelle la touche DOIT être enfoncée pour commencer à se répéter dépend de la configuration. |
| [getShiftKey](../../com.aspose.html.dom.events/keyboardevent/shiftkey/) true si le modificateur de touche shift (Shift) était actif. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Utilisé pour indiquer le [`IEventTarget`](../ieventtarget/) auquel l'événement a été initialement diffusé. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Utilisé pour spécifier le temps (en millisecondes relatives à l'époque) auquel l'événement a été créé. Étant donné que certains systèmes peuvent ne pas fournir cette information, la valeur de timeStamp peut ne pas être disponible pour tous les événements. Lorsqu'elle n'est pas disponible, une valeur de 0 sera renvoyée. Des exemples de temps d'époque sont le moment du démarrage du système ou 0:0:0 UTC le 1er janvier 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Le nom de l'événement (insensible à la casse). Le nom doit être un nom XML. |
| [getView](../../com.aspose.html.dom.events/uievent/view/) L'attribut view identifie la fenêtre à partir de laquelle l'événement a été généré. La valeur non initialisée de cet attribut DOIT être null. |

## Méthodes

| Nom | Description |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | La méthode [`InitEvent`](../event/initevent/) est utilisée pour initialiser la valeur d'un [`Event`](../event/) créé via l'interface [`IDocumentEvent`](../idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Si un événement est annulable, la méthode [`PreventDefault`](../event/preventdefault/) est utilisée pour indiquer que l'événement doit être annulé, ce qui signifie qu'aucune action par défaut normalement exécutée par l'implémentation à la suite de l'événement ne se produira. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | L'appel de cette méthode empêche l'événement d'atteindre les écouteurs d'événements enregistrés après celui-ci et, lorsqu'il est diffusé dans un arbre, empêche également l'événement d'atteindre tout autre objet. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | La méthode [`StopPropagation`](../event/stoppropagation/) est utilisée pour empêcher la propagation supplémentaire d'un événement pendant le flux d'événements. |

## Champs

| Nom | Description |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_left/) | La touche activée provient de l'emplacement gauche de la touche (lorsqu'il existe plusieurs emplacements possibles pour cette touche). |
| const [DOM_KEY_LOCATION_NUMPAD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | L'activation de la touche provient du pavé numérique ou d'une touche virtuelle correspondant au pavé numérique (lorsqu'il existe plusieurs emplacements possibles pour cette touche). Notez que la touche NumLock doit toujours être codée avec un emplacement de DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_right/) | L'activation de la touche provient de l'emplacement droit de la touche (lorsqu'il existe plusieurs emplacements possibles pour cette touche). |
| const [DOM_KEY_LOCATION_STANDARD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | L'activation de la touche NE DOIT PAS être distinguée comme la version gauche ou droite de la touche, et (à l'exception de la touche NumLock) ne provient pas du pavé numérique (ou ne provient pas d'une touche virtuelle correspondant au pavé numérique). |

### Voir aussi

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
