---
title: "IEventTarget.AddEventListener"
second_title: "Aspose.HTML für Java API-Referenz"
description: "IEventTarget-Methode. Die EventTarget-Methode addEventListener richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Event an das Ziel geliefert wird."
type: docs

url: /de/java/com.aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(String, IEventListener) {#addeventlistener}

Die EventTarget‑Methode addEventListener() richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird.

Gemeinsame Ziele sind Element, Document und Window, aber das Ziel kann jedes Objekt sein, das Events unterstützt (wie zum Beispiel XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | String | Ein case-sensitiver String, der den zu überwachenden Ereignistyp darstellt. |
| Listener | IEventListener | Nimmt ein vom Benutzer implementiertes Interface entgegen, das die Methoden enthält, die aufgerufen werden sollen, wenn das Ereignis eintritt. |

## Hinweise

Wenn ein is zu einem while hinzugefügt wird, während ein Ereignis verarbeitet wird, wird er nicht durch die aktuellen Aktionen ausgelöst, kann jedoch in einer späteren Phase des Ereignisflusses, wie der Bubbling-Phase, ausgelöst werden. Wenn mehrere identische Event Listener am selben with mit denselben Parametern registriert sind, werden die doppelten Instanzen verworfen. Sie führen nicht dazu, dass das to zweimal aufgerufen wird, und da sie verworfen werden, müssen sie nicht mit der Methode entfernt werden.

### Siehe auch

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_1}

Die EventTarget‑Methode addEventListener() richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel übermittelt wird.

Gemeinsame Ziele sind Element, Document und Window, aber das Ziel kann jedes Objekt sein, das Events unterstützt (wie zum Beispiel XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | String | Ein case-sensitiver String, der den zu überwachenden Ereignistyp darstellt. |
| Listener | IEventListener | Nimmt ein vom Benutzer implementiertes Interface entgegen, das die Methoden enthält, die aufgerufen werden sollen, wenn das Ereignis eintritt. |
| useCapture | Boolean | Wenn true, gibt useCapture an, dass der Benutzer die Erfassung initiieren möchte. Nach dem Initiieren der Erfassung werden alle Events des angegebenen Typs an die registrierten before gesendet, bevor sie an irgendwelche Event Targets unterhalb von ihnen im Baum gesendet werden. Events, die im Baum nach oben bubbeln, lösen keinen designated aus, um capture zu verwenden. |

## Hinweise

Wenn ein is zu einem while hinzugefügt wird, während ein Ereignis verarbeitet wird, wird er nicht durch die aktuellen Aktionen ausgelöst, kann jedoch in einer späteren Phase des Ereignisflusses, wie der Bubbling-Phase, ausgelöst werden. Wenn mehrere identische Event Listener am selben with mit denselben Parametern registriert sind, werden die doppelten Instanzen verworfen. Sie führen nicht dazu, dass das to zweimal aufgerufen wird, und da sie verworfen werden, müssen sie nicht mit der Methode entfernt werden.

### Siehe auch

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
