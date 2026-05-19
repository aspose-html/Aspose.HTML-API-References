---
title: "EventTarget.AddEventListener"
second_title: "Aspose.HTML voor Java API-referentie"
description: "EventTarget-methode. De addEventListener-methode van de EventTarget-interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven event aan het doel wordt geleverd"
type: docs

url: /nl/java/com.aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(String, DOMEventHandler, bool) {#addeventlistener}

De addEventListener()‑methode van de [EventTarget ](T:com.aspose.html.dom.EventTarget)interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd.

Het werkt door een functie of een object dat [EventListener](T:com.aspose.html.dom.events.IEventListener) implementeert, toe te voegen aan de lijst van event listeners voor het opgegeven eventtype op de EventTarget waarop het wordt aangeroepen. Als de functie of het object al in de lijst van event listeners voor dit doel staat, worden ze niet een tweede keer toegevoegd.

```java
public void AddEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Het eventtype waarvoor de gebruiker zich registreert |
| handler | DOMEventHandler | Neemt een aan die wordt aangeroepen wanneer het event optreedt. |
| useCapture | Boolean | Als true, geeft useCapture aan dat de gebruiker capture wil initiëren. Na het initiëren van capture worden alle events van het opgegeven type verzonden naar de geregistreerde voordat ze worden verzonden naar enige Event Targets onder hen in de boom. Events die omhoog bubbelen door de boom zullen geen aangewezen triggeren om capture te gebruiken. |

## Opmerkingen

Als een wordt toegevoegd aan een terwijl het een event verwerkt, zal het niet worden geactiveerd door de huidige acties maar kan het wel worden geactiveerd tijdens een later stadium van de event‑stroom, zoals de bubbling‑fase. Als meerdere identieke Event Listeners op dezelfde met dezelfde parameters zijn geregistreerd, worden de dubbele exemplaren verwijderd. Ze zorgen er niet voor dat de wordt twee keer aangeroepen en aangezien ze worden verwijderd, hoeven ze niet met de methode te worden verwijderd.

### Zie ook

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener) {#addeventlistener_1}

De addEventListener()-methode van de [`EventTarget `](../)interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven event aan het doel wordt geleverd.

Het werkt door een functie of een object dat [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/) implementeert, toe te voegen aan de lijst van event listeners voor het opgegeven eventtype op de EventTarget waarop het wordt aangeroepen. Als de functie of het object al in de lijst van event listeners voor dit doel staat, worden ze niet een tweede keer toegevoegd.

```java
public void AddEventListener(String type, IEventListener listener)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Het eventtype waarvoor de gebruiker zich registreert |
| luisteraar | IEventListener | Neemt een interface die door de gebruiker is geïmplementeerd en die de methoden bevat die moeten worden aangeroepen wanneer het event plaatsvindt. |

## Opmerkingen

Als een wordt toegevoegd aan een terwijl het een event verwerkt, zal het niet worden geactiveerd door de huidige acties maar kan het wel worden geactiveerd tijdens een later stadium van de event‑stroom, zoals de bubbling‑fase. Als meerdere identieke Event Listeners op dezelfde met dezelfde parameters zijn geregistreerd, worden de dubbele exemplaren verwijderd. Ze zorgen er niet voor dat de wordt twee keer aangeroepen en aangezien ze worden verwijderd, hoeven ze niet met de methode te worden verwijderd.

### Zie ook

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_2}

De addEventListener()‑methode van de [EventTarget ](T:com.aspose.html.dom.EventTarget)interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd.

Het werkt door een functie of een object dat [EventListener](T:com.aspose.html.dom.events.IEventListener) implementeert, toe te voegen aan de lijst van event listeners voor het opgegeven eventtype op de EventTarget waarop het wordt aangeroepen. Als de functie of het object al in de lijst van event listeners voor dit doel staat, worden ze niet een tweede keer toegevoegd.

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Het eventtype waarvoor de gebruiker zich registreert |
| luisteraar | IEventListener | Neemt een interface die door de gebruiker is geïmplementeerd en die de methoden bevat die moeten worden aangeroepen wanneer het event plaatsvindt. |
| useCapture | Boolean | Als true, geeft useCapture aan dat de gebruiker capture wil initiëren. Na het initiëren van capture worden alle events van het opgegeven type verzonden naar de geregistreerde voordat ze worden verzonden naar enige Event Targets onder hen in de boom. Events die omhoog bubbelen door de boom zullen geen aangewezen triggeren om capture te gebruiken. |

## Opmerkingen

Als een wordt toegevoegd aan een terwijl het een event verwerkt, zal het niet worden geactiveerd door de huidige acties maar kan het wel worden geactiveerd tijdens een later stadium van de event‑stroom, zoals de bubbling‑fase. Als meerdere identieke Event Listeners op dezelfde met dezelfde parameters zijn geregistreerd, worden de dubbele exemplaren verwijderd. Ze zorgen er niet voor dat de wordt twee keer aangeroepen en aangezien ze worden verwijderd, hoeven ze niet met de methode te worden verwijderd.

### Zie ook

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
