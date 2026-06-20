---
title: "MediaQueryList Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.window.MediaQueryList class. Ein MediaQueryList-Objekt speichert Informationen zu einer auf ein Dokument angewendeten Media Query und unterstützt sowohl sofortige als auch ereignisgesteuerte Übereinstimmungen mit dem Zustand des Dokuments. Siehe die CSSOM View Module Spezifikation https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs

url: /de/java/com.aspose.html.window/mediaquerylist/
---
## MediaQueryList class

Ein MediaQueryList‑Objekt speichert Informationen zu einer auf ein Dokument angewendeten Media‑Query und unterstützt sowohl sofortiges als auch ereignisgesteuertes Abgleichen gegen den Zustand des Dokuments. Siehe die CSSOM‑View‑Modul‑Spezifikation: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```java
public class MediaQueryList : EventTarget
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getDocument](../../com.aspose.html.window/mediaquerylist/document/) Das mit dem Kontextobjekt verbundene Dokument. |
| [getMatches](../../com.aspose.html.window/mediaquerylist/matches/) Ein boolescher Wert, der true zurückgibt, wenn das Dokument derzeit mit der Media Query-Liste übereinstimmt, oder false, wenn nicht. |
| [getMedia](../../com.aspose.html.window/mediaquerylist/media/) Ein String, der eine serialisierte Media Query darstellt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Die addEventListener()-Methode des [`EventTarget `](../../com.aspose.html.dom/eventtarget/)‑Interfaces richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel ausgeliefert wird. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Die addEventListener()-Methode des [EventTarget ](T:com.aspose.html.dom.EventTarget)Interface richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel geliefert wird. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Die addEventListener()-Methode des [EventTarget ](T:com.aspose.html.dom.EventTarget)Interface richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel geliefert wird. |
| [addListener](../../com.aspose.html.window/mediaquerylist/addlistener/)(IEventListener) | Füge einen Event-Listener für Änderungen des matches-Zustands der MediaQueryList hinzu. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Sendet ein Event an das angegebene [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synchron) und ruft die betroffenen EventListeners in der richtigen Reihenfolge auf. Die normalen Ereignisverarbeitungsregeln (einschließlich der Erfassungs‑ und optionalen Bubbling‑Phase) gelten ebenfalls für manuell mit [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) gesendete Events. |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript-Objekt abzurufen. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Diese Methode ermöglicht das Entfernen von Ereignis‑Listenern vom Ereignis‑Ziel. Wenn ein Listener während der Verarbeitung eines Ereignisses entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignis‑Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Diese Methode ermöglicht das Entfernen von Ereignis‑Listenern vom Ereignis‑Ziel. Wenn ein Listener während der Verarbeitung eines Ereignisses entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignis‑Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Diese Methode ermöglicht das Entfernen von Ereignis‑Listenern vom Ereignis‑Ziel. Wenn ein Listener während der Verarbeitung eines Ereignisses entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignis‑Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [removeListener](../../com.aspose.html.window/mediaquerylist/removelistener/)(IEventListener) | Entferne den Event-Listener für Änderungen des matches-Zustands der MediaQueryList. |

## Ereignisse

| Name | Beschreibung |
| --- | --- |
| event [OnChange](../../com.aspose.html.window/mediaquerylist/onchange/) | Ereignis, das bei der MediaQueryList ausgelöst wird, wenn sich der matches-Zustand ändert. |

### Siehe auch

* class [EventTarget](../../com.aspose.html.dom/eventtarget/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
