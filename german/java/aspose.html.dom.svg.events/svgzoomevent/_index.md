---
title: "SVGZoomEvent-Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.svg.events.SVGZoomEvent-Klasse. Das Zoom-Ereignis tritt auf, wenn der Benutzer eine Aktion initiiert, die dazu führt, dass die aktuelle Ansicht des SVG-Dokumentfragments neu skaliert wird. Ereignis-Handler werden nur bei SVG-Elementen erkannt."
type: docs

url: /de/java/com.aspose.html.dom.svg.events/svgzoomevent/
---
## SVGZoomEvent class

Das Zoom-Ereignis tritt auf, wenn der Benutzer eine Aktion auslöst, die die aktuelle Ansicht des SVG-Dokumentfragments neu skaliert. Ereignis-Handler werden nur bei ‘svg’-Elementen erkannt.

```java
public class SVGZoomEvent : Event
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Wird verwendet, um anzugeben, ob ein Ereignis ein Bubbling‑Ereignis ist oder nicht. Wenn das Ereignis bubbling‑fähig ist, ist der Wert true, sonst false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Wird verwendet, um anzugeben, ob die Standardaktion eines Ereignisses verhindert werden kann. Wenn die Standardaktion verhindert werden kann, ist der Wert true, sonst false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Wird verwendet, um das [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) anzugeben, dessen [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/)s gerade verarbeitet werden. Dies ist besonders nützlich während des Capturing und Bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Gibt true zurück, wenn preventDefault() aufgerufen wurde, während das Attribut cancelable den Wert true hat, andernfalls false. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Wird verwendet, um anzugeben, welche Phase des Ereignisflusses derzeit ausgewertet wird. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Das isTrusted-Attribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn ein Ereignis erstellt wird, muss das Attribut auf false initialisiert werden. |
| [getNewScale](../../com.aspose.html.dom.svg.events/svgzoomevent/newscale/) Der Skalierungsfaktor, der nach der Verarbeitung des Zoomvorgangs wirksam sein wird. |
| [getNewTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/newtranslate/) Die Übersetzungswerte, die nach der Verarbeitung des Zoomvorgangs wirksam sein werden. Das SVGPoint-Objekt ist schreibgeschützt. |
| [getPreviousScale](../../com.aspose.html.dom.svg.events/svgzoomevent/previousscale/) Der Skalierungsfaktor aus vorherigen Zoom-Operationen, der vor dem Auftreten der aktuellen Zoom-Operation wirksam war. |
| [getPreviousTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/previoustranslate/) Die Übersetzungswerte aus vorherigen Zoom-Operationen, die vor dem Auftreten der aktuellen Zoom-Operation wirksam waren. Das SVGPoint-Objekt ist schreibgeschützt. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Wird verwendet, um das [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) anzugeben, an das das Ereignis ursprünglich gesendet wurde. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Wird verwendet, um die Zeit (in Millisekunden relativ zum Epoch) anzugeben, zu der das Ereignis erstellt wurde. Da einige Systeme diese Information möglicherweise nicht bereitstellen, kann der Wert von timeStamp für nicht alle Ereignisse verfügbar sein. Wenn nicht verfügbar, wird ein Wert von 0 zurückgegeben. Beispiele für Epoch‑Zeit sind die Systemstartzeit oder 0:0:0 UTC, 1. Januar 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Der Name des Ereignisses (Groß‑/Kleinschreibung ignorierend). Der Name muss ein XML‑Name sein. |
| [getZoomRectScreen](../../com.aspose.html.dom.svg.events/svgzoomevent/zoomrectscreen/) Das angegebene Zoom-Rechteck in Bildschirmeinheiten. Das SVGRect-Objekt ist schreibgeschützt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript‑Objekt abzurufen. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Die [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/)-Methode wird verwendet, um den Wert eines über die [`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/)-Schnittstelle erstellten [`Event`](../../com.aspose.html.dom.events/event/)-Objekts zu initialisieren. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Wenn ein Ereignis abbrechbar ist, wird die [`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/)-Methode verwendet, um anzuzeigen, dass das Ereignis abgebrochen werden soll, was bedeutet, dass jede standardmäßige Aktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt wird, nicht stattfindet. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Der Aufruf dieser Methode verhindert, dass das Ereignis an Ereignislistener gelangt, die nach dem aktuellen registriert wurden, und verhindert beim Versand in einem Baum, dass das Ereignis andere Objekte erreicht. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Die [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/)-Methode wird verwendet, um die weitere Weiterleitung eines Ereignisses während des Ereignisflusses zu verhindern. |

### Siehe auch

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)
