---
title: "IEventTarget‑interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.events.IEventTarget interface. De EventTarget‑interface wordt geïmplementeerd door alle Nodes in een implementatie die het DOM‑eventmodel ondersteunt. Daarom kan deze interface verkregen worden door bindingspecifieke cast‑methoden te gebruiken op een instantie van de Node‑interface. De interface maakt registratie en verwijdering van Event Listeners mogelijk en het verzenden van events naar die."
type: docs

url: /nl/java/com.aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

De EventTarget interface wordt geïmplementeerd door alle Nodes in een implementatie die het DOM Event Model ondersteunt. Daarom kan deze interface verkregen worden door binding‑specifieke cast‑methoden te gebruiken op een instantie van de Node interface. De interface maakt registratie en verwijdering van Event Listeners op een en het verzenden van gebeurtenissen naar dat object mogelijk.

```java
public interface IEventTarget
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(String, IEventListener) | De EventTarget‑methode addEventListener() stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven event aan het doel wordt geleverd. |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener, bool) | De EventTarget‑methode addEventListener() stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven event aan het doel wordt geleverd. |
| [dispatchEvent](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | Verzendt een Event naar het opgegeven EventTarget (synchroon) en roept de betrokken EventListeners in de juiste volgorde aan. De normale event‑verwerkingsregels (inclusief de capture‑ en optionele bubbling‑fase) zijn ook van toepassing op events die handmatig worden verzonden met dispatchEvent(). |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(String, IEventListener) | Deze methode maakt het verwijderen van event listeners van het event target mogelijk. Als een listener wordt verwijderd terwijl er een event wordt verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener, bool) | Deze methode maakt het verwijderen van event listeners van het event target mogelijk. Als een listener wordt verwijderd terwijl er een event wordt verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |

### Zie ook

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
