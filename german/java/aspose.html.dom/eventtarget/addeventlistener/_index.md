---
title: "EventTarget.AddEventListener"
second_title: "Aspose.HTML für Java API-Referenz"
description: "EventTarget-Methode. Die addEventListener-Methode des EventTarget-Interfaces richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel geliefert wird."
type: docs

url: /de/java/com.aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(String, DOMEventHandler, bool) {#addeventlistener}

Die addEventListener()-Methode des [EventTarget ](T:com.aspose.html.dom.EventTarget)Interface richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel geliefert wird.

Es funktioniert, indem eine Funktion oder ein Objekt, das [EventListener](T:com.aspose.html.dom.events.IEventListener) implementiert, zur Liste der Ereignislistener für den angegebenen Ereignistyp auf dem EventTarget, auf dem es aufgerufen wird, hinzugefügt wird. Wenn die Funktion oder das Objekt bereits in der Liste der Ereignislistener für dieses Ziel enthalten ist, wird sie/er nicht ein zweites Mal hinzugefügt.

```java
public void AddEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | String | Der Ereignistyp, für den der Benutzer registriert |
| Handler | DOMEventHandler | Nimmt ein ... entgegen, das aufgerufen wird, wenn das Ereignis eintritt. |
| useCapture | Boolean | Wenn true, gibt useCapture an, dass der Benutzer die Erfassung initiieren möchte. Nach dem Initiieren der Erfassung werden alle Events des angegebenen Typs an die registrierten gesendet, bevor sie an irgendwelche Event Targets unterhalb im Baum gesendet werden. Events, die im Baum nach oben blubbern, lösen nicht das dafür vorgesehene Erfassen aus. |

## Hinweise

Wenn ein während der Verarbeitung eines Events zu einem Objekt hinzugefügt wird, wird er nicht durch die aktuellen Aktionen ausgelöst, kann jedoch in einer späteren Phase des Ereignisflusses, wie der Bubbling-Phase, ausgelöst werden. Wenn mehrere identische Event Listener am selben Objekt mit denselben Parametern registriert sind, werden die Duplikate verworfen. Sie führen nicht dazu, dass der zweimal aufgerufen wird, und da sie verworfen werden, müssen sie nicht mit der Methode entfernt werden.

### Siehe auch

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener) {#addeventlistener_1}

Die addEventListener()-Methode des [`EventTarget `](../)-Interfaces richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel geliefert wird.

Es funktioniert, indem eine Funktion oder ein Objekt, das [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/) implementiert, zur Liste der Ereignislistener für den angegebenen Ereignistyp auf dem EventTarget, auf dem es aufgerufen wird, hinzugefügt wird. Wenn die Funktion oder das Objekt bereits in der Liste der Ereignislistener für dieses Ziel enthalten ist, wird sie/er nicht ein zweites Mal hinzugefügt.

```java
public void AddEventListener(String type, IEventListener listener)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | String | Der Ereignistyp, für den der Benutzer registriert |
| Listener | IEventListener | Nimmt ein vom Benutzer implementiertes Interface entgegen, das die Methoden enthält, die aufgerufen werden sollen, wenn das Ereignis eintritt. |

## Hinweise

Wenn ein während der Verarbeitung eines Events zu einem Objekt hinzugefügt wird, wird er nicht durch die aktuellen Aktionen ausgelöst, kann jedoch in einer späteren Phase des Ereignisflusses, wie der Bubbling-Phase, ausgelöst werden. Wenn mehrere identische Event Listener am selben Objekt mit denselben Parametern registriert sind, werden die Duplikate verworfen. Sie führen nicht dazu, dass der zweimal aufgerufen wird, und da sie verworfen werden, müssen sie nicht mit der Methode entfernt werden.

### Siehe auch

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_2}

Die addEventListener()-Methode des [EventTarget ](T:com.aspose.html.dom.EventTarget)Interface richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel geliefert wird.

Es funktioniert, indem eine Funktion oder ein Objekt, das [EventListener](T:com.aspose.html.dom.events.IEventListener) implementiert, zur Liste der Ereignislistener für den angegebenen Ereignistyp auf dem EventTarget, auf dem es aufgerufen wird, hinzugefügt wird. Wenn die Funktion oder das Objekt bereits in der Liste der Ereignislistener für dieses Ziel enthalten ist, wird sie/er nicht ein zweites Mal hinzugefügt.

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | String | Der Ereignistyp, für den der Benutzer registriert |
| Listener | IEventListener | Nimmt ein vom Benutzer implementiertes Interface entgegen, das die Methoden enthält, die aufgerufen werden sollen, wenn das Ereignis eintritt. |
| useCapture | Boolean | Wenn true, gibt useCapture an, dass der Benutzer die Erfassung initiieren möchte. Nach dem Initiieren der Erfassung werden alle Events des angegebenen Typs an die registrierten gesendet, bevor sie an irgendwelche Event Targets unterhalb im Baum gesendet werden. Events, die im Baum nach oben blubbern, lösen nicht das dafür vorgesehene Erfassen aus. |

## Hinweise

Wenn ein während der Verarbeitung eines Events zu einem Objekt hinzugefügt wird, wird er nicht durch die aktuellen Aktionen ausgelöst, kann jedoch in einer späteren Phase des Ereignisflusses, wie der Bubbling-Phase, ausgelöst werden. Wenn mehrere identische Event Listener am selben Objekt mit denselben Parametern registriert sind, werden die Duplikate verworfen. Sie führen nicht dazu, dass der zweimal aufgerufen wird, und da sie verworfen werden, müssen sie nicht mit der Methode entfernt werden.

### Siehe auch

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
