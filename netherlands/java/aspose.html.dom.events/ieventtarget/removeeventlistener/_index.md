---
title: "IEventTarget.RemoveEventListener"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IEventTarget methode. Deze methode maakt het verwijderen van Event Listeners van het event‑target mogelijk. Als een Event Listener wordt verwijderd terwijl het een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit worden aangeroepen nadat ze zijn verwijderd."
type: docs

url: /nl/java/com.aspose.html.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(String, IEventListener) {#removeeventlistener}

Deze methode maakt het verwijderen van event listeners van het event target mogelijk. Als een listener wordt verwijderd terwijl er een event wordt verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd.

```java
public void RemoveEventListener(String type, IEventListener listener)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Specificeert het type gebeurtenis van de te verwijderen. |
| luisteraar | IEventListener | De parameter geeft aan wat verwijderd moet worden. |

### Zie ook

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener, bool) {#removeeventlistener_1}

Deze methode maakt het verwijderen van event listeners van het event target mogelijk. Als een listener wordt verwijderd terwijl er een event wordt verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd.

```java
public void RemoveEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Specificeert het type gebeurtenis van de te verwijderen. |
| luisteraar | IEventListener | De parameter geeft aan wat verwijderd moet worden. |
| useCapture | Boolean | Specificeert of de te verwijderen EventListener geregistreerd was als een capture‑listener of niet. Als een listener twee keer is geregistreerd, één met capture en één zonder, moet elke afzonderlijk worden verwijderd. Het verwijderen van een capture‑listener heeft geen invloed op een niet‑capture‑versie van dezelfde listener, en omgekeerd. |

### Zie ook

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
