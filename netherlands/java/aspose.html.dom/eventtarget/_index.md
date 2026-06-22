---
title: "EventTarget Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.EventTarget class. De EventTarget‑interface wordt geïmplementeerd door objecten die gebeurtenissen kunnen ontvangen en mogelijk listeners daarvoor hebben. Met andere woorden implementeert elk doelwit van gebeurtenissen de drie methoden die aan deze interface zijn gekoppeld."
type: docs

url: /nl/java/com.aspose.html.dom/eventtarget/
---
## EventTarget class

De EventTarget‑interface wordt geïmplementeerd door objecten die gebeurtenissen kunnen ontvangen en er mogelijk luisteraars voor hebben. Met andere woorden, elk doelwit van gebeurtenissen implementeert de drie methoden die bij deze interface horen.

[`Element`](../element/), and its children, as well as [`Document`](../document/) and Window, are the most common event targets, but other objects can be event targets, too.

```java
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [EventTarget](eventtarget/)() | Initialiseert een nieuw exemplaar van het EventTarget‑object. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener) | De addEventListener()‑methode van de `EventTarget `interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement naar het doel wordt afgeleverd. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(String, DOMEventHandler, bool) | De addEventListener()‑methode van de [EventTarget](T:com.aspose.html.dom.EventTarget)‑interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(String, IEventListener, bool) | De addEventListener()‑methode van de [EventTarget](T:com.aspose.html.dom.EventTarget)‑interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Verzendt een Event naar de opgegeven [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synchroon) en roept de betrokken EventListeners in de juiste volgorde aan. De normale regels voor gebeurtenisverwerking (inclusief de capture‑ en optionele bubbling‑fase) zijn ook van toepassing op handmatig verzonden events met [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Voert toepassingsspecifieke taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet‑beheerde bronnen. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een listener wordt verwijderd terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(String, DOMEventHandler, bool) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een listener wordt verwijderd terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(String, IEventListener, bool) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een listener wordt verwijderd terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |

### Zie ook

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
