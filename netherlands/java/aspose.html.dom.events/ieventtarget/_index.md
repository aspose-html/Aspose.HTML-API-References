---
title: "IEventTarget Interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.events.IEventTarget interface. De EventTarget interface wordt geïmplementeerd door alle Nodes in een implementatie die het DOM Event Model ondersteunt. Daarom kan deze interface verkregen worden door bindingspecifieke cast‑methoden te gebruiken op een instantie van de Node interface. De interface maakt registratie en verwijdering van Event Listeners op een en het verzenden van events naar die toe."
type: docs

url: /nl/java/com.aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

De EventTarget-interface wordt geïmplementeerd door alle knooppunten in een implementatie die het DOM-gebeurtenismodel ondersteunt. Daarom kan deze interface worden verkregen door bindingspecifieke castmethoden te gebruiken op een instantie van de Node-interface. De interface maakt registratie en verwijdering van Event Listeners op een en het verzenden van gebeurtenissen naar die toe mogelijk.

```java
public interface IEventTarget
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(String, IEventListener) | De EventTarget methode addEventListener() stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven event aan het doel wordt geleverd. |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener, bool) | De EventTarget methode addEventListener() stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven event aan het doel wordt geleverd. |
| [dispatchEvent](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | Verzendt een Event naar de opgegeven EventTarget, (synchroon) waarbij de betrokken EventListeners in de juiste volgorde worden aangeroepen. De normale event‑verwerkingsregels (inclusief de capture‑ en optionele bubbling‑fase) zijn ook van toepassing op events die handmatig worden verzonden met dispatchEvent(). |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(String, IEventListener) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een listener wordt verwijderd terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener, bool) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een listener wordt verwijderd terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |

### Zie ook

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
