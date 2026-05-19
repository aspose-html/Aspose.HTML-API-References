---
title: "IEventTarget.AddEventListener"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IEventTarget‑methode. De EventTarget‑methode addEventListener stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven event naar het doelwit wordt afgeleverd."
type: docs

url: /nl/java/com.aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(String, IEventListener) {#addeventlistener}

De EventTarget‑methode addEventListener() stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven event aan het doel wordt geleverd.

Veelvoorkomende doelwitten zijn Element, Document en Window, maar het doelwit kan elk object zijn dat events ondersteunt (zoals XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Een hoofdlettergevoelige String die het type event vertegenwoordigt waarop geluisterd moet worden. |
| luisteraar | IEventListener | Neemt een interface die door de gebruiker is geïmplementeerd en die de methoden bevat die moeten worden aangeroepen wanneer het event plaatsvindt. |

## Opmerkingen

Als een wordt toegevoegd aan een terwijl het een event verwerkt, zal het niet worden geactiveerd door de huidige acties maar kan het wel worden geactiveerd tijdens een later stadium van de event‑stroom, zoals de bubbling‑fase. Als meerdere identieke Event Listeners op dezelfde met dezelfde parameters zijn geregistreerd, worden de dubbele exemplaren verwijderd. Ze zorgen er niet voor dat de wordt twee keer aangeroepen en aangezien ze worden verwijderd, hoeven ze niet met de methode te worden verwijderd.

### Zie ook

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_1}

De EventTarget‑methode addEventListener() stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven event aan het doel wordt geleverd.

Veelvoorkomende doelwitten zijn Element, Document en Window, maar het doelwit kan elk object zijn dat events ondersteunt (zoals XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Een hoofdlettergevoelige String die het type event vertegenwoordigt waarop geluisterd moet worden. |
| luisteraar | IEventListener | Neemt een interface die door de gebruiker is geïmplementeerd en die de methoden bevat die moeten worden aangeroepen wanneer het event plaatsvindt. |
| useCapture | Boolean | Als true, geeft useCapture aan dat de gebruiker capture wil initiëren. Na het initiëren van capture worden alle events van het opgegeven type verzonden naar de geregistreerde voordat ze worden verzonden naar enige Event Targets onder hen in de boom. Events die omhoog bubbelen door de boom zullen geen aangewezen triggeren om capture te gebruiken. |

## Opmerkingen

Als een wordt toegevoegd aan een terwijl het een event verwerkt, zal het niet worden geactiveerd door de huidige acties maar kan het wel worden geactiveerd tijdens een later stadium van de event‑stroom, zoals de bubbling‑fase. Als meerdere identieke Event Listeners op dezelfde met dezelfde parameters zijn geregistreerd, worden de dubbele exemplaren verwijderd. Ze zorgen er niet voor dat de wordt twee keer aangeroepen en aangezien ze worden verwijderd, hoeven ze niet met de methode te worden verwijderd.

### Zie ook

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
