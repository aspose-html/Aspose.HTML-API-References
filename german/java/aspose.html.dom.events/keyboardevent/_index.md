---
title: "KeyboardEvent‑Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.events.KeyboardEvent‑Klasse. Das KeyboardEvent‑Interface liefert spezifische Kontextinformationen, die mit Tastaturgeräten verbunden sind. Jedes Tastaturereignis referenziert eine Taste über einen Wert. Tastaturereignisse werden typischerweise an das Element gerichtet, das den Fokus hat."
type: docs

url: /de/java/com.aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

Das KeyboardEvent-Interface liefert spezifische kontextbezogene Informationen, die mit Tastaturgeräten verbunden sind. Jedes Tastaturereignis verweist über einen Wert auf eine Taste. Tastaturereignisse werden in der Regel an das Element gerichtet, das den Fokus hat.

```java
public class KeyboardEvent : UIEvent
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(String) | Initialisiert eine neue Instanz der `KeyboardEvent`‑Klasse. |
| [KeyboardEvent](keyboardevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/keyboardevent/altkey/) true, wenn die Alt‑ (Alternative‑) (oder \"Option\"‑) Tastenkombination aktiv war. Der nicht initialisierte Wert dieses Attributs MUSS false sein. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Wird verwendet, um anzuzeigen, ob ein Ereignis ein Bubbling‑Ereignis ist. Wenn das Ereignis bubbling unterstützt, ist der Wert true, sonst false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Wird verwendet, um anzuzeigen, ob ein Ereignis seine Standardaktion verhindern kann. Wenn die Standardaktion verhindert werden kann, ist der Wert true, sonst false. |
| [getCode](../../com.aspose.html.dom.events/keyboardevent/code/) Der Code enthält eine Zeichenkette, die die physische gedrückte Taste identifiziert. Der Wert wird nicht vom aktuellen Tastaturlayout oder Modifikatorzustand beeinflusst, sodass eine bestimmte Taste stets denselben Wert zurückgibt. |
| [getCtrlKey](../../com.aspose.html.dom.events/keyboardevent/ctrlkey/) true, wenn die Steuer‑ (Control‑) Tastenkombination aktiv war. Der nicht initialisierte Wert dieses Attributs MUSS false sein. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Wird verwendet, um das [`IEventTarget`](../ieventtarget/) anzuzeigen, dessen [`IEventListener`](../ieventlistener/)s gerade verarbeitet werden. Dies ist besonders nützlich während des Capturing und Bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Gibt true zurück, wenn preventDefault() aufgerufen wurde, während das cancelable‑Attribut true ist, andernfalls false. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Gibt einige Detailinformationen über das Ereignis an, abhängig vom Ereignistyp. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Wird verwendet, um anzuzeigen, welche Phase des Ereignisflusses derzeit ausgewertet wird. |
| [getIsComposing](../../com.aspose.html.dom.events/keyboardevent/iscomposing/) true, wenn das Tastenereignis Teil einer Kompositionssitzung ist, d.h. nach einem compositionstart‑Ereignis und vor dem entsprechenden compositionend‑Ereignis. Der nicht initialisierte Wert dieses Attributs MUSS false sein. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Das Attribut isTrusted muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn ein Ereignis erstellt wird, muss das Attribut auf false initialisiert werden. |
| [getKey](../../com.aspose.html.dom.events/keyboardevent/key/) Die key enthält den Tastwert der gedrückten Taste. Wenn der Wert eine druckbare Darstellung hat, MUSS er eine nicht leere Unicode‑Zeichenkette sein, die dem im vorliegenden Dokument definierten Algorithmus zur Bestimmung des Tastwerts entspricht. Hat der Wert eine Steuertaste ohne druckbare Darstellung, MUSS er einer der im Schlüsselwert‑Set definierten Tastwerte sein, wie durch den Algorithmus bestimmt. Implementierungen, die eine Taste nicht identifizieren können, MÜSSEN den Tastwert „Unidentified“ verwenden. |
| [getLocation](../../com.aspose.html.dom.events/keyboardevent/location/) Das Attribut location enthält einen Hinweis auf die logische Position der Taste auf dem Gerät. |
| [getMetaKey](../../com.aspose.html.dom.events/keyboardevent/metakey/) true, wenn die Meta‑ (Meta) Tastenkombination aktiv war. |
| [getRepeat](../../com.aspose.html.dom.events/keyboardevent/repeat/) true, wenn die Taste über einen längeren Zeitraum gedrückt wurde. Das Gedrückthalten einer Taste MUSS dazu führen, dass die Ereignisse keydown, beforeinput, input in dieser Reihenfolge wiederholt werden, mit einer Rate, die durch die Systemkonfiguration bestimmt wird. Bei mobilen Geräten mit Langdruck‑Verhalten MUSS das erste Tastaturereignis mit dem Attributwert true als Hinweis auf einen Langdruck dienen. Die Dauer, die die Taste gedrückt werden MUSS, um mit dem Wiederholen zu beginnen, ist konfigurationsabhängig. |
| [getShiftKey](../../com.aspose.html.dom.events/keyboardevent/shiftkey/) true, wenn die Shift‑ (Shift) Tastenkombination aktiv war. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Wird verwendet, um das [`IEventTarget`](../ieventtarget/) anzugeben, an das das Ereignis ursprünglich gesendet wurde. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Wird verwendet, um die Zeit (in Millisekunden relativ zum Epoch) anzugeben, zu der das Ereignis erstellt wurde. Da einige Systeme diese Information möglicherweise nicht bereitstellen, kann der Wert von timeStamp für nicht alle Ereignisse verfügbar sein. Wenn nicht verfügbar, wird ein Wert von 0 zurückgegeben. Beispiele für Epoch‑Zeit sind der Systemstart oder 0:0:0 UTC, 1. Januar 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Der Name des Ereignisses (Groß-/Kleinschreibung wird ignoriert). Der Name muss ein XML‑Name sein. |
| [getView](../../com.aspose.html.dom.events/uievent/view/) Das Attribut view identifiziert das Fenster, aus dem das Ereignis erzeugt wurde. Der nicht initialisierte Wert dieses Attributs MUSS null sein. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript-Objekt abzurufen. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Die [`InitEvent`](../event/initevent/)‑Methode wird verwendet, um den Wert eines über die [`IDocumentEvent`](../idocumentevent/) Schnittstelle erstellten [`Event`](../event/) zu initialisieren. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Wenn ein Ereignis abbrechbar ist, wird die [`PreventDefault`](../event/preventdefault/)‑Methode verwendet, um anzuzeigen, dass das Ereignis abgebrochen werden soll, d.h. dass jede Standardaktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt wird, nicht erfolgt. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Der Aufruf dieser Methode verhindert, dass das Ereignis an Ereignis‑Listener gelangt, die nach dem aktuellen registriert wurden, und verhindert beim Versand in einem Baum, dass das Ereignis andere Objekte erreicht. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Die [`StopPropagation`](../event/stoppropagation/)‑Methode wird verwendet, um die weitere Weiterleitung eines Ereignisses während des Ereignisflusses zu verhindern. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_left/) | Die aktivierte Taste stammt aus der linken Tastposition (wenn es mehr als einen möglichen Ort für diese Taste gibt). |
| const [DOM_KEY_LOCATION_NUMPAD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | Die Tastenauslösung stammt vom numerischen Tastenfeld oder von einer virtuellen Taste, die dem numerischen Tastenfeld entspricht (wenn es mehr als einen möglichen Ort für diese Taste gibt). Hinweis: Die NumLock‑Taste sollte immer mit dem Standort DOM_KEY_LOCATION_STANDARD codiert werden. |
| const [DOM_KEY_LOCATION_RIGHT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_right/) | Die Tastenauslösung stammt vom rechten Tastenspeicherort (wenn es mehr als einen möglichen Ort für diese Taste gibt). |
| const [DOM_KEY_LOCATION_STANDARD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | Die Tastenauslösung MUSS NICHT als linke oder rechte Version der Taste unterschieden werden und (außer der NumLock‑Taste) stammt nicht vom numerischen Tastenfeld (oder nicht von einer virtuellen Taste, die dem numerischen Tastenfeld entspricht). |

### Siehe auch

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
