---
title: "IEventTarget.RemoveEventListener"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IEventTarget-methode. Deze methode maakt het mogelijk om event listeners van het eventdoel te verwijderen. Als een listener wordt verwijderd van een target terwijl het een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd."
type: docs

url: /nl/java/com.aspose.html.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(String, IEventListener) {#removeeventlistener}

Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een listener wordt verwijderd terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd.

```java
public void RemoveEventListener(String type, IEventListener listener)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Specificeert het type gebeurtenis van het te verwijderen. |
| listener | IEventListener | De parameter geeft aan wat verwijderd moet worden. |

### Zie ook

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener, bool) {#removeeventlistener_1}

Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een listener wordt verwijderd terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd.

```java
public void RemoveEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Specificeert het type gebeurtenis van het te verwijderen. |
| listener | IEventListener | De parameter geeft aan wat verwijderd moet worden. |
| useCapture | Boolean | Geeft aan of de te verwijderen EventListener is geregistreerd als een capture‑listener of niet. Als een listener twee keer is geregistreerd, één met capture en één zonder, moet elke afzonderlijk worden verwijderd. Het verwijderen van een capture‑listener heeft geen invloed op een niet‑capture‑versie van dezelfde listener, en vice‑versa. |

### Zie ook

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
