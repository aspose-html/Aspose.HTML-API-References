---
title: "IEventTarget.AddEventListener"
second_title: "Aspose.HTML für Java API-Referenz"
description: "IEventTarget-Methode. Die EventTarget-Methode addEventListener richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Event an das Ziel geliefert wird."
type: docs

url: /de/java/com.aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(String, IEventListener) {#addeventlistener}

Die EventTarget‑Methode addEventListener() richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel geliefert wird.

Gemeinsame Ziele sind Element, Document und Window, aber das Ziel kann jedes Objekt sein, das Events unterstützt (wie XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | String | Ein case-sensitiver String, der den zu überwachenden Ereignistyp darstellt. |
| Listener | IEventListener | Nimmt ein vom Benutzer implementiertes Interface entgegen, das die Methoden enthält, die aufgerufen werden sollen, wenn das Ereignis eintritt. |

## Hinweise

Wenn ein während der Verarbeitung eines Events zu einem Objekt hinzugefügt wird, wird er nicht durch die aktuellen Aktionen ausgelöst, kann jedoch in einer späteren Phase des Ereignisflusses, wie der Bubbling-Phase, ausgelöst werden. Wenn mehrere identische Event Listener am selben Objekt mit denselben Parametern registriert sind, werden die Duplikate verworfen. Sie führen nicht dazu, dass der zweimal aufgerufen wird, und da sie verworfen werden, müssen sie nicht mit der Methode entfernt werden.

### Siehe auch

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_1}

Die EventTarget‑Methode addEventListener() richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel geliefert wird.

Gemeinsame Ziele sind Element, Document und Window, aber das Ziel kann jedes Objekt sein, das Events unterstützt (wie XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | String | Ein case-sensitiver String, der den zu überwachenden Ereignistyp darstellt. |
| Listener | IEventListener | Nimmt ein vom Benutzer implementiertes Interface entgegen, das die Methoden enthält, die aufgerufen werden sollen, wenn das Ereignis eintritt. |
| useCapture | Boolean | Wenn true, gibt useCapture an, dass der Benutzer die Erfassung initiieren möchte. Nach dem Initiieren der Erfassung werden alle Events des angegebenen Typs an die registrierten gesendet, bevor sie an irgendwelche Event Targets unterhalb im Baum gesendet werden. Events, die im Baum nach oben blubbern, lösen nicht das dafür vorgesehene Erfassen aus. |

## Hinweise

Wenn ein während der Verarbeitung eines Events zu einem Objekt hinzugefügt wird, wird er nicht durch die aktuellen Aktionen ausgelöst, kann jedoch in einer späteren Phase des Ereignisflusses, wie der Bubbling-Phase, ausgelöst werden. Wenn mehrere identische Event Listener am selben Objekt mit denselben Parametern registriert sind, werden die Duplikate verworfen. Sie führen nicht dazu, dass der zweimal aufgerufen wird, und da sie verworfen werden, müssen sie nicht mit der Methode entfernt werden.

### Siehe auch

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
