---
title: "Classe MouseEvent"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.dom.events.MouseEvent class. L'interface MouseEvent fournit des informations contextuelles spécifiques associées aux événements de souris."
type: docs

url: /fr/java/com.aspose.html.dom.events/mouseevent/
---
## MouseEvent class

L'interface MouseEvent fournit des informations contextuelles spécifiques associées aux événements de souris.

```java
public class MouseEvent : UIEvent
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MouseEvent](mouseevent/#constructor)(String) | Initialise une nouvelle instance de la classe `MouseEvent`. |
| [MouseEvent](mouseevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Propriétés

| Nom | Description |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/mouseevent/altkey/) Référez‑vous à l'attribut altKey. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Utilisé pour indiquer si un événement est un événement de propagation (bubbling) ou non. Si l'événement peut se propager, la valeur est vraie, sinon la valeur est fausse. |
| [getButton](../../com.aspose.html.dom.events/mouseevent/button/) Lors des événements de souris causés par la pression ou le relâchement d'un bouton de souris, le bouton DOIT être utilisé pour indiquer quel bouton du dispositif de pointage a changé d'état. |
| [getButtons](../../com.aspose.html.dom.events/mouseevent/buttons/) Lors de tout événement de souris, les boutons DOIVENT être utilisés pour indiquer quelle combinaison de boutons de souris est actuellement enfoncée, exprimée sous forme de masque de bits. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Utilisé pour indiquer si un événement peut voir son action par défaut empêchée. Si l'action par défaut peut être empêchée, la valeur est vraie, sinon la valeur est fausse. |
| [getClientX](../../com.aspose.html.dom.events/mouseevent/clientx/) La coordonnée horizontale à laquelle l'événement s'est produit par rapport à la fenêtre d'affichage associée à l'événement. |
| [getClientY](../../com.aspose.html.dom.events/mouseevent/clienty/) La coordonnée verticale à laquelle l'événement s'est produit par rapport à la fenêtre d'affichage associée à l'événement. |
| [getCtrlKey](../../com.aspose.html.dom.events/mouseevent/ctrlkey/) Référez‑vous à l'attribut ctrlKey. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Utilisé pour indiquer le [`IEventTarget`](../ieventtarget/) dont les [`IEventListener`](../ieventlistener/) sont actuellement en cours de traitement. Ceci est particulièrement utile lors de la capture et de la propagation. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Retourne vrai si preventDefault() a été invoqué alors que la valeur de l'attribut cancelable est vraie, et faux sinon. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Spécifie certaines informations détaillées sur l'événement, en fonction du type d'événement. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Utilisé pour indiquer quelle phase du flux d'événements est actuellement évaluée. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) L'attribut isTrusted doit renvoyer la valeur à laquelle il a été initialisé. Lorsqu'un événement est créé, l'attribut doit être initialisé à false. |
| [getMetaKey](../../com.aspose.html.dom.events/mouseevent/metakey/) Référez‑vous à l'attribut metaKey. |
| [getRelatedTarget](../../com.aspose.html.dom.events/mouseevent/relatedtarget/) Utilisé pour identifier un EventTarget secondaire lié à un événement UI, selon le type d'événement. |
| [getScreenX](../../com.aspose.html.dom.events/mouseevent/screenx/) La coordonnée horizontale à laquelle l'événement s'est produit par rapport à l'origine du système de coordonnées de l'écran. |
| [getScreenY](../../com.aspose.html.dom.events/mouseevent/screeny/) La coordonnée verticale à laquelle l'événement s'est produit par rapport à l'origine du système de coordonnées de l'écran. |
| [getShiftKey](../../com.aspose.html.dom.events/mouseevent/shiftkey/) Se référer à l'attribut shiftKey. |
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

### Voir aussi

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
