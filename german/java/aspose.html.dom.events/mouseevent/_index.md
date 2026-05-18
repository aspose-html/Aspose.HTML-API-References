---
title: "MouseEvent-Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.events.MouseEvent class. Das MouseEvent‑Interface liefert spezifische kontextbezogene Informationen, die mit Mausereignissen verbunden sind."
type: docs

url: /de/java/com.aspose.html.dom.events/mouseevent/
---
## MouseEvent class

Das MouseEvent-Interface liefert spezifische kontextbezogene Informationen, die mit Mausereignissen verbunden sind.

```java
public class MouseEvent : UIEvent
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MouseEvent](mouseevent/#constructor)(String) | Initialisiert eine neue Instanz der `MouseEvent`‑Klasse. |
| [MouseEvent](mouseevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/mouseevent/altkey/) Verweisen Sie auf das altKey‑Attribut. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Wird verwendet, um anzugeben, ob ein Ereignis ein Bubbling‑Ereignis ist oder nicht. Wenn das Ereignis bubbling‑fähig ist, ist der Wert true, sonst false. |
| [getButton](../../com.aspose.html.dom.events/mouseevent/button/) Während Mausereignissen, die durch das Drücken oder Loslassen einer Maustaste verursacht werden, MUSS button verwendet werden, um anzugeben, welche Maustaste den Zustand geändert hat. |
| [getButtons](../../com.aspose.html.dom.events/mouseevent/buttons/) Während aller Mausereignisse MUSS buttons verwendet werden, um anzugeben, welche Kombination von Maustasten derzeit gedrückt ist, ausgedrückt als Bitmaske. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Wird verwendet, um anzugeben, ob die Standardaktion eines Ereignisses verhindert werden kann. Wenn die Standardaktion verhindert werden kann, ist der Wert true, sonst false. |
| [getClientX](../../com.aspose.html.dom.events/mouseevent/clientx/) Die horizontale Koordinate, bei der das Ereignis relativ zum Viewport des Ereignisses auftrat. |
| [getClientY](../../com.aspose.html.dom.events/mouseevent/clienty/) Die vertikale Koordinate, bei der das Ereignis relativ zum Viewport des Ereignisses auftrat. |
| [getCtrlKey](../../com.aspose.html.dom.events/mouseevent/ctrlkey/) Verweisen Sie auf das ctrlKey‑Attribut. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Wird verwendet, um das [`IEventTarget`](../ieventtarget/) anzugeben, dessen [`IEventListener`](../ieventlistener/) gerade verarbeitet werden. Dies ist besonders nützlich während des Capturing‑ und Bubbling‑Phasen. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Gibt true zurück, wenn preventDefault() aufgerufen wurde, während das Attribut cancelable den Wert true hat, andernfalls false. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Gibt einige Detailinformationen über das Ereignis an, abhängig vom Ereignistyp. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Wird verwendet, um anzugeben, welche Phase des Ereignisflusses derzeit ausgewertet wird. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Das isTrusted-Attribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn ein Ereignis erstellt wird, muss das Attribut auf false initialisiert werden. |
| [getMetaKey](../../com.aspose.html.dom.events/mouseevent/metakey/) Verweisen Sie auf das metaKey‑Attribut. |
| [getRelatedTarget](../../com.aspose.html.dom.events/mouseevent/relatedtarget/) Wird verwendet, um ein sekundäres EventTarget zu identifizieren, das mit einem UI-Ereignis verbunden ist, abhängig vom Ereignistyp. |
| [getScreenX](../../com.aspose.html.dom.events/mouseevent/screenx/) Die horizontale Koordinate, an der das Ereignis relativ zum Ursprung des Bildschirmkoordinatensystems auftrat. |
| [getScreenY](../../com.aspose.html.dom.events/mouseevent/screeny/) Die vertikale Koordinate, an der das Ereignis relativ zum Ursprung des Bildschirmkoordinatensystems auftrat. |
| [getShiftKey](../../com.aspose.html.dom.events/mouseevent/shiftkey/) Siehe das Attribut shiftKey. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Wird verwendet, um das [`IEventTarget`](../ieventtarget/) anzugeben, an das das Ereignis ursprünglich gesendet wurde. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Wird verwendet, um die Zeit (in Millisekunden relativ zum Epoch) anzugeben, zu der das Ereignis erstellt wurde. Da einige Systeme diese Information möglicherweise nicht bereitstellen, kann der Wert von timeStamp für nicht alle Ereignisse verfügbar sein. Wenn nicht verfügbar, wird ein Wert von 0 zurückgegeben. Beispiele für Epoch‑Zeit sind die Systemstartzeit oder 0:0:0 UTC, 1. Januar 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Der Name des Ereignisses (Groß‑/Kleinschreibung ignorierend). Der Name muss ein XML‑Name sein. |
| [getView](../../com.aspose.html.dom.events/uievent/view/) Das view‑Attribut identifiziert das Fenster, aus dem das Ereignis erzeugt wurde. Der nicht initialisierte Wert dieses Attributs MUSS null sein. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript‑Objekt abzurufen. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Die Methode [`InitEvent`](../event/initevent/) wird verwendet, um den Wert eines über die[`IDocumentEvent`](../idocumentevent/)‑Schnittstelle erstellten [`Event`](../event/) zu initialisieren. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Wenn ein Ereignis abbrechbar ist, wird die Methode [`PreventDefault`](../event/preventdefault/) verwendet, um anzuzeigen, dass das Ereignis abgebrochen werden soll, d. h. jede Standardaktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt würde, findet nicht statt. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Der Aufruf dieser Methode verhindert, dass das Ereignis an Ereignislistener gelangt, die nach dem aktuellen registriert wurden, und verhindert beim Versand in einem Baum, dass das Ereignis andere Objekte erreicht. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Die Methode [`StopPropagation`](../event/stoppropagation/) wird verwendet, um die weitere Ausbreitung eines Ereignisses während des Ereignisflusses zu verhindern. |

### Siehe auch

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
