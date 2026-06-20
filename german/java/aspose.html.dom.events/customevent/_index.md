---
title: "CustomEvent Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.events.CustomEvent Klasse. Ereignisse, die die CustomEvent‑Schnittstelle verwenden, können zum Übertragen benutzerdefinierter Daten genutzt werden."
type: docs

url: /de/java/com.aspose.html.dom.events/customevent/
---
## CustomEvent class

Ereignisse, die das CustomEvent-Interface verwenden, können zum Übertragen benutzerdefinierter Daten genutzt werden.

```java
public class CustomEvent : Event
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [CustomEvent](customevent/#constructor)(String) | Initialisiert eine neue Instanz der `CustomEvent`‑Klasse. |
| [CustomEvent](customevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Wird verwendet, um anzuzeigen, ob ein Ereignis ein Bubbling‑Ereignis ist. Wenn das Ereignis bubbling unterstützt, ist der Wert true, sonst false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Wird verwendet, um anzuzeigen, ob ein Ereignis seine Standardaktion verhindern kann. Wenn die Standardaktion verhindert werden kann, ist der Wert true, sonst false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Wird verwendet, um das [`IEventTarget`](../ieventtarget/) anzuzeigen, dessen [`IEventListener`](../ieventlistener/)s gerade verarbeitet werden. Dies ist besonders nützlich während des Capturing und Bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Gibt true zurück, wenn preventDefault() aufgerufen wurde, während das cancelable‑Attribut true ist, andernfalls false. |
| [getDetail](../../com.aspose.html.dom.events/customevent/detail/) Ruft die benutzerdefinierten Daten ab. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Wird verwendet, um anzuzeigen, welche Phase des Ereignisflusses derzeit ausgewertet wird. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Das Attribut isTrusted muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn ein Ereignis erstellt wird, muss das Attribut auf false initialisiert werden. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Wird verwendet, um das [`IEventTarget`](../ieventtarget/) anzugeben, an das das Ereignis ursprünglich gesendet wurde. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Wird verwendet, um die Zeit (in Millisekunden relativ zum Epoch) anzugeben, zu der das Ereignis erstellt wurde. Da einige Systeme diese Information möglicherweise nicht bereitstellen, kann der Wert von timeStamp für nicht alle Ereignisse verfügbar sein. Wenn nicht verfügbar, wird ein Wert von 0 zurückgegeben. Beispiele für Epoch‑Zeit sind der Systemstart oder 0:0:0 UTC, 1. Januar 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Der Name des Ereignisses (Groß-/Kleinschreibung wird ignoriert). Der Name muss ein XML‑Name sein. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript-Objekt abzurufen. |
| [initCustomEvent](../../com.aspose.html.dom.events/customevent/initcustomevent/)(String, bool, bool, object) | /// Die [`InitEvent`](../event/initevent/) Methode wird verwendet, um den Wert eines über die [`IDocumentEvent`](../idocumentevent/) Schnittstelle erstellten [`Event`](../event/) zu initialisieren. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Die [`InitEvent`](../event/initevent/)‑Methode wird verwendet, um den Wert eines über die [`IDocumentEvent`](../idocumentevent/) Schnittstelle erstellten [`Event`](../event/) zu initialisieren. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Wenn ein Ereignis abbrechbar ist, wird die [`PreventDefault`](../event/preventdefault/)‑Methode verwendet, um anzuzeigen, dass das Ereignis abgebrochen werden soll, d.h. dass jede Standardaktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt wird, nicht erfolgt. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Der Aufruf dieser Methode verhindert, dass das Ereignis an Ereignis‑Listener gelangt, die nach dem aktuellen registriert wurden, und verhindert beim Versand in einem Baum, dass das Ereignis andere Objekte erreicht. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Die [`StopPropagation`](../event/stoppropagation/)‑Methode wird verwendet, um die weitere Weiterleitung eines Ereignisses während des Ereignisflusses zu verhindern. |

### Siehe auch

* class [Event](../event/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
