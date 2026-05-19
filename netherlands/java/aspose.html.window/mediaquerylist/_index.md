---
title: "MediaQueryList Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.window.MediaQueryList klasse. Een MediaQueryList‑object slaat informatie op over een mediavraag die op een document wordt toegepast, met ondersteuning voor zowel directe als gebeurtenis‑gedreven overeenstemming met de status van het document. Zie de CSSOM View Module-specificatie https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs

url: /nl/java/com.aspose.html.window/mediaquerylist/
---
## MediaQueryList class

Een MediaQueryList‑object slaat informatie op over een mediavraag die op een document is toegepast, met ondersteuning voor zowel directe als gebeurtenis‑gedreven overeenstemming met de status van het document. Zie de CSSOM View Module-specificatie: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```java
public class MediaQueryList : EventTarget
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getDocument](../../com.aspose.html.window/mediaquerylist/document/) Document dat is gekoppeld aan het contextobject. |
| [getMatches](../../com.aspose.html.window/mediaquerylist/matches/) Een booleaanse waarde die true retourneert als het document momenteel overeenkomt met de mediavraaglijst, of false als dat niet het geval is. |
| [getMedia](../../com.aspose.html.window/mediaquerylist/media/) Een string die een geserialiseerde mediavraag vertegenwoordigt. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | De addEventListener()-methode van de [`EventTarget `](../../com.aspose.html.dom/eventtarget/)interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | De addEventListener()‑methode van de [EventTarget ](T:com.aspose.html.dom.EventTarget)interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | De addEventListener()‑methode van de [EventTarget ](T:com.aspose.html.dom.EventTarget)interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [addListener](../../com.aspose.html.window/mediaquerylist/addlistener/)(IEventListener) | Voeg een MediaQueryList‑matches‑status‑wijzigings‑eventlistener toe. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Zend een Event naar het opgegeven [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synchroon) en roep de betrokken EventListeners in de juiste volgorde aan. De normale regels voor gebeurtenisverwerking (inclusief de capture‑ en optionele bubbling‑fase) zijn ook van toepassing op handmatig verzonden events met [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Voert door de toepassing gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet‑beheerde bronnen. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Deze methode maakt het verwijderen van event listeners van het event target mogelijk. Als een listener wordt verwijderd terwijl er een event wordt verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Deze methode maakt het verwijderen van event listeners van het event target mogelijk. Als een listener wordt verwijderd terwijl er een event wordt verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Deze methode maakt het verwijderen van event listeners van het event target mogelijk. Als een listener wordt verwijderd terwijl er een event wordt verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [removeListener](../../com.aspose.html.window/mediaquerylist/removelistener/)(IEventListener) | Verwijder een MediaQueryList‑matches‑status‑wijzigings‑eventlistener. |

## Gebeurtenissen

| Naam | Beschrijving |
| --- | --- |
| event [OnChange](../../com.aspose.html.window/mediaquerylist/onchange/) | Evenement dat wordt geactiveerd op de MediaQueryList wanneer de matches‑status verandert. |

### Zie ook

* class [EventTarget](../../com.aspose.html.dom/eventtarget/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
