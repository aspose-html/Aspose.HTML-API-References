---
title: "Classe SVGZoomEvent"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Classe com.aspose.html.dom.svg.events.SVGZoomEvent. L'événement de zoom se produit lorsque l'utilisateur initie une action qui entraîne le redimensionnement de la vue actuelle du fragment de document SVG. Les gestionnaires d'événements ne sont reconnus que sur les éléments svg."
type: docs

url: /fr/java/com.aspose.html.dom.svg.events/svgzoomevent/
---
## SVGZoomEvent class

L'événement de zoom se produit lorsque l'utilisateur initie une action qui entraîne le redimensionnement de la vue actuelle du fragment de document SVG. Les gestionnaires d'événements ne sont reconnus que sur les éléments ‘svg’.

```java
public class SVGZoomEvent : Event
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Utilisé pour indiquer si un événement est un événement de propagation (bubbling) ou non. Si l'événement peut se propager, la valeur est vraie, sinon la valeur est fausse. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Utilisé pour indiquer si un événement peut voir son action par défaut empêchée. Si l'action par défaut peut être empêchée, la valeur est vraie, sinon la valeur est fausse. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Utilisé pour indiquer le [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) dont les [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/)s sont actuellement en cours de traitement. Ceci est particulièrement utile lors de la capture et de la propagation. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Retourne vrai si preventDefault() a été invoqué alors que la valeur de l'attribut cancelable est vraie, et faux sinon. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Utilisé pour indiquer quelle phase du flux d'événements est actuellement évaluée. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) L'attribut isTrusted doit renvoyer la valeur à laquelle il a été initialisé. Lorsqu'un événement est créé, l'attribut doit être initialisé à false. |
| [getNewScale](../../com.aspose.html.dom.svg.events/svgzoomevent/newscale/) Le facteur d'échelle qui sera en place après le traitement de l'opération de zoom. |
| [getNewTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/newtranslate/) Les valeurs de translation qui seront en place après le traitement de l'opération de zoom. L'objet SVGPoint est en lecture seule. |
| [getPreviousScale](../../com.aspose.html.dom.svg.events/svgzoomevent/previousscale/) Le facteur d'échelle des opérations de zoom précédentes qui était en place avant que l'opération de zoom ne se produise. |
| [getPreviousTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/previoustranslate/) Les valeurs de translation des opérations de zoom précédentes qui étaient en place avant que l'opération de zoom ne se produise. L'objet SVGPoint est en lecture seule. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Utilisé pour indiquer le [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) vers lequel l'événement a été initialement dispatché. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Utilisé pour spécifier le temps (en millisecondes relatives à l'époque) auquel l'événement a été créé. Étant donné que certains systèmes peuvent ne pas fournir cette information, la valeur de timeStamp peut ne pas être disponible pour tous les événements. Lorsqu'elle n'est pas disponible, une valeur de 0 sera renvoyée. Des exemples de temps d'époque sont le moment du démarrage du système ou 0:0:0 UTC le 1er janvier 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Le nom de l'événement (insensible à la casse). Le nom doit être un nom XML. |
| [getZoomRectScreen](../../com.aspose.html.dom.svg.events/svgzoomevent/zoomrectscreen/) Le rectangle de zoom spécifié en unités d'écran. L'objet SVGRect est en lecture seule. |

## Méthodes

| Nom | Description |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | La méthode [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/) est utilisée pour initialiser la valeur d'un [`Event`](../../com.aspose.html.dom.events/event/) créé via l'interface [`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Si un événement est annulable, la méthode [`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/) est utilisée pour indiquer que l'événement doit être annulé, ce qui signifie qu'aucune action par défaut normalement exécutée par l'implémentation à la suite de l'événement ne se produira. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | L'appel de cette méthode empêche l'événement d'atteindre les écouteurs d'événements enregistrés après celui-ci et, lorsqu'il est diffusé dans un arbre, empêche également l'événement d'atteindre tout autre objet. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | La méthode [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/) est utilisée pour empêcher la propagation supplémentaire d'un événement pendant le flux d'événements. |

### Voir aussi

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)
