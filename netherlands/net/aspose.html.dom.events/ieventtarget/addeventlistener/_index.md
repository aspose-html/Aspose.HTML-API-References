---
title: IEventTarget.AddEventListener
second_title: Aspose.HTML voor .NET API-referentie
description: IEventTarget methode. Met deze methode kunnen gebeurtenislisteners worden geregistreerd op het gebeurtenisdoel.
type: docs
weight: 10
url: /nl/net/aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(string, IEventListener) {#addeventlistener}

Met deze methode kunnen gebeurtenislisteners worden geregistreerd op het gebeurtenisdoel.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Het gebeurtenistype waarvoor de gebruiker zich registreert |
| listener | IEventListener | Neemt een interface die door de gebruiker is geïmplementeerd en die de methoden bevat die moeten worden aangeroepen wanneer de gebeurtenis plaatsvindt. |

### Opmerkingen

Als een[`IEventListener`](../../ieventlistener/) wordt toegevoegd aan een[`EventTarget`](../../../aspose.html.dom/eventtarget/) terwijl het een gebeurtenis verwerkt, wordt het niet geactiveerd door de huidige acties, maar kan het worden geactiveerd tijdens een latere fase van de gebeurtenisstroom, zoals de bubbling-fase.

Als er meerdere identieke gebeurtenislisteners op hetzelfde zijn geregistreerd[`EventTarget`](../../../aspose.html.dom/eventtarget/)met dezelfde parameters worden de dubbele exemplaren weggegooid. Ze veroorzaken niet de[`IEventListener`](../../ieventlistener/) om twee keer te worden aangeroepen en aangezien ze worden weggegooid, hoeven ze niet te worden verwijderd met de [`RemoveEventListener`](../removeeventlistener/) methode.

### Zie ook

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* naamruimte [Aspose.Html.Dom.Events](../../ieventtarget/)
* montage [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_1}

Met deze methode kunnen gebeurtenislisteners worden geregistreerd op het gebeurtenisdoel.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Het gebeurtenistype waarvoor de gebruiker zich registreert |
| listener | IEventListener | Neemt een interface die door de gebruiker is geïmplementeerd en die de methoden bevat die moeten worden aangeroepen wanneer de gebeurtenis plaatsvindt. |
| useCapture | Boolean | Indien waar, geeft useCapture aan dat de gebruiker het vastleggen wil starten. Nadat het vastleggen is gestart, worden alle gebeurtenissen van het opgegeven type verzonden naar de geregistreerde [`IEventListener`](../../ieventlistener/) voordat ze worden verzonden naar gebeurtenisdoelen eronder in de boom. Gebeurtenissen die omhoog borrelen door de boom zullen geen[`IEventListener`](../../ieventlistener/) aangewezen om capture te gebruiken. |

### Opmerkingen

Als een[`IEventListener`](../../ieventlistener/) wordt toegevoegd aan een[`EventTarget`](../../../aspose.html.dom/eventtarget/) terwijl het een gebeurtenis verwerkt, wordt het niet geactiveerd door de huidige acties, maar kan het worden geactiveerd tijdens een latere fase van de gebeurtenisstroom, zoals de bubbling-fase.

Als er meerdere identieke gebeurtenislisteners op hetzelfde zijn geregistreerd[`EventTarget`](../../../aspose.html.dom/eventtarget/)met dezelfde parameters worden de dubbele exemplaren weggegooid. Ze veroorzaken niet de[`IEventListener`](../../ieventlistener/) om twee keer te worden aangeroepen en aangezien ze worden weggegooid, hoeven ze niet te worden verwijderd met de [`RemoveEventListener`](../removeeventlistener/) methode.

### Zie ook

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* naamruimte [Aspose.Html.Dom.Events](../../ieventtarget/)
* montage [Aspose.HTML](../../../)


