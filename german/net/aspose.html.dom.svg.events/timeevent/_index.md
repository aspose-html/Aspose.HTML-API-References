---
title: TimeEvent
second_title: Aspose.HTML für .NET-API-Referenz
description: Die TimeEventSchnittstelle stellt spezifische Kontextinformationen bereit die Zeitereignissen zugeordnet sind. Die verschiedenen Arten von Ereignissen die auftreten können sind beginEvent endEvent und repeatEvent.
type: docs
weight: 1350
url: /de/net/aspose.html.dom.svg.events/timeevent/
---
## TimeEvent class

Die TimeEvent-Schnittstelle stellt spezifische Kontextinformationen bereit, die Zeitereignissen zugeordnet sind. Die verschiedenen Arten von Ereignissen, die auftreten können, sind: beginEvent, endEvent und repeatEvent.

```csharp
public class TimeEvent : Event
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles) { get; } | Wird verwendet, um anzugeben, ob ein Ereignis ein Blasenereignis ist oder nicht. Wenn das Ereignis sprudeln kann, ist der Wert wahr, andernfalls ist der Wert falsch. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable) { get; } | Wird verwendet, um anzugeben, ob die Standardaktion eines Ereignisses verhindert werden kann oder nicht. Wenn die Standardaktion verhindert werden kann, ist der Wert wahr, andernfalls ist der Wert falsch. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget) { get; } | Wird verwendet, um die anzuzeigen[`IEventTarget`](../../aspose.html.dom.events/ieventtarget) Deren[`IEventListener`](../../aspose.html.dom.events/ieventlistener) s werden gerade verarbeitet. Dies ist besonders nützlich beim Erfassen und Bubbling. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented) { get; } | Gibt „true“ zurück, wenn preventDefault() aufgerufen wurde, während der Wert des abbrechbaren Attributs „true“ ist, andernfalls „false“. |
| [Detail](../../aspose.html.dom.svg.events/timeevent/detail) { get; } | Gibt je nach Art des Ereignisses einige Detailinformationen zum Ereignis an. Gibt für diesen Ereignistyp die Wiederholungsnummer für die Animation an. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase) { get; } | Wird verwendet, um anzugeben, welche Phase des Ereignisflusses derzeit ausgewertet wird. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted) { get; } | Das isTrusted-Attribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn ein Ereignis erstellt wird, muss das Attribut auf „false“ initialisiert werden. |
| [Target](../../aspose.html.dom.events/event/target) { get; } | Wird verwendet, um die anzuzeigen[`IEventTarget`](../../aspose.html.dom.events/ieventtarget) an die das Ereignis ursprünglich gesendet wurde. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp) { get; } | Wird verwendet, um die Zeit (in Millisekunden relativ zur Epoche) anzugeben, zu der das Ereignis erstellt wurde. Da einige Systeme diese Informationen möglicherweise nicht bereitstellen, ist der Wert von timeStamp möglicherweise nicht für alle Ereignisse verfügbar. Wenn nicht verfügbar , wird ein Wert von 0 zurückgegeben. Beispiele für Epochenzeit sind die Zeit des Systemstarts oder 0:0:0 UTC 1. Januar 1970. |
| [Type](../../aspose.html.dom.events/event/type) { get; } | Der Name des Ereignisses (Groß-/Kleinschreibung wird nicht beachtet). Der Name muss ein XML-Name sein. |
| [View](../../aspose.html.dom.svg.events/timeevent/view) { get; } | Das Ansichtsattribut identifiziert die AbstractView [DOM2VIEWS], aus der das Ereignis generiert wurde. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent)(string, bool, bool) | Die[`InitEvent`](../../aspose.html.dom.events/event/initevent) -Methode wird verwendet, um den Wert von an zu initialisieren[`Event`](../../aspose.html.dom.events/event) erstellt durch the [`IDocumentEvent`](../../aspose.html.dom.events/idocumentevent) Schnittstelle. |
| [InitTimeEvent](../../aspose.html.dom.svg.events/timeevent/inittimeevent)(string, IAbstractView, long) | Die initTimeEvent-Methode wird verwendet, um den Wert eines TimeEvent zu initialisieren, das über die DocumentEvent-Schnittstelle erstellt wurde. Diese Methode darf nur aufgerufen werden, bevor das TimeEvent über die dispatchEvent-Methode abgesetzt wurde, obwohl sie während dieser Phase bei Bedarf mehrmals aufgerufen werden kann. Bei mehreren Aufrufen hat der letzte Aufruf Vorrang. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault)() | Wenn eine Veranstaltung stornierbar ist, wird die[`PreventDefault`](../../aspose.html.dom.events/event/preventdefault) -Methode wird verwendet, um anzugeben, dass das Ereignis abgebrochen werden soll, , was bedeutet, dass eine Standardaktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt wird, nicht ausgeführt wird. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation)() | Das Aufrufen dieser Methode verhindert, dass das Ereignis alle Ereignis-Listener erreicht, die nach dem aktuellen registriert sind, und wenn es in einem Baum gesendet wird, verhindert es auch, dass das Ereignis andere Objekte erreicht. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation)() | Die[`StopPropagation`](../../aspose.html.dom.events/event/stoppropagation) -Methode verwendet wird, verhindert die weitere Ausbreitung eines Ereignisses während des Ereignisflusses. |

### Siehe auch

* class [Event](../../aspose.html.dom.events/event)
* namensraum [Aspose.Html.Dom.Svg.Events](../../aspose.html.dom.svg.events)
* Montage [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
