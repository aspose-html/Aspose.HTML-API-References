---
title: "Interface IEventTarget"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.dom.events.IEventTarget. L'interface EventTarget est implémentée par tous les nœuds dans une implémentation qui prend en charge le modèle d'événements DOM. Par conséquent, cette interface peut être obtenue en utilisant des méthodes de conversion spécifiques au binding sur une instance de l'interface Node. L'interface permet l'enregistrement et la suppression d'écouteurs d'événements et le dispatch d'événements vers celui-ci"
type: docs

url: /fr/java/com.aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

L'interface EventTarget est implémentée par tous les nœuds dans une implémentation qui prend en charge le modèle d'événements DOM. Par conséquent, cette interface peut être obtenue en utilisant des méthodes de cast spécifiques au binding sur une instance de l'interface Node. L'interface permet l'enregistrement et la suppression d'écouteurs d'événements sur un et la diffusion d'événements vers celui-ci.

```java
public interface IEventTarget
```

## Méthodes

| Nom | Description |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(String, IEventListener) | La méthode addEventListener() de EventTarget configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible. |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener, bool) | La méthode addEventListener() de EventTarget configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible. |
| [dispatchEvent](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | Déclenche un Event sur le EventTarget spécifié, (synchroniquement) en invoquant les EventListeners affectés dans l'ordre approprié. Les règles normales de traitement des événements (y compris les phases de capture et de bouillonnement optionnel) s'appliquent également aux événements déclenchés manuellement avec dispatchEvent(). |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(String, IEventListener) | Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener, bool) | Cette méthode permet la suppression des écouteurs d'événements de la cible d'événement. Si un écouteur est supprimé pendant le traitement d'un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événements ne peuvent jamais être invoqués après avoir été supprimés. |

### Voir aussi

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
