---
title: "IEventTarget.AddEventListener"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IEventTarget‑methode. De EventTarget‑methode addEventListener stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven event aan het doelwit wordt geleverd."
type: docs

url: /nl/java/com.aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(String, IEventListener) {#addeventlistener}

De EventTarget methode addEventListener() stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven event aan het doel wordt geleverd.

Veelvoorkomende doelwitten zijn Element, Document en Window, maar het doelwit kan elk object zijn dat events ondersteunt (zoals XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Een hoofdlettergevoelige String die het type event weergeeft waarnaar geluisterd moet worden. |
| listener | IEventListener | Neemt een interface die door de gebruiker is geïmplementeerd en die de methoden bevat die moeten worden aangeroepen wanneer het event plaatsvindt. |

## Opmerkingen

Als een wordt toegevoegd aan een terwijl deze een event verwerkt, wordt deze niet geactiveerd door de huidige acties maar kan later in de gebeurtenisstroom, bijvoorbeeld tijdens de bubbling‑fase, worden geactiveerd. Als meerdere identieke Event Listeners op dezelfde met dezelfde parameters zijn geregistreerd, worden de dubbele exemplaren weggegooid. Ze zorgen er niet voor dat de wordt twee keer aangeroepen en aangezien ze worden weggegooid, hoeven ze niet met de methode te worden verwijderd.

### Zie ook

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_1}

De EventTarget methode addEventListener() stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven event aan het doel wordt geleverd.

Veelvoorkomende doelwitten zijn Element, Document en Window, maar het doelwit kan elk object zijn dat events ondersteunt (zoals XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Een hoofdlettergevoelige String die het type event weergeeft waarnaar geluisterd moet worden. |
| listener | IEventListener | Neemt een interface die door de gebruiker is geïmplementeerd en die de methoden bevat die moeten worden aangeroepen wanneer het event plaatsvindt. |
| useCapture | Boolean | Als true, geeft useCapture aan dat de gebruiker capture wil starten. Na het starten van capture worden alle events van het opgegeven type naar de geregistreerde verzonden voordat ze naar enige Event Targets onder hen in de boom worden verzonden. Events die omhoog bubbelen door de boom zullen een aangewezen niet triggeren om capture te gebruiken. |

## Opmerkingen

Als een wordt toegevoegd aan een terwijl deze een event verwerkt, wordt deze niet geactiveerd door de huidige acties maar kan later in de gebeurtenisstroom, bijvoorbeeld tijdens de bubbling‑fase, worden geactiveerd. Als meerdere identieke Event Listeners op dezelfde met dezelfde parameters zijn geregistreerd, worden de dubbele exemplaren weggegooid. Ze zorgen er niet voor dat de wordt twee keer aangeroepen en aangezien ze worden weggegooid, hoeven ze niet met de methode te worden verwijderd.

### Zie ook

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
