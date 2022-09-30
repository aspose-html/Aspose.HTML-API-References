---
title: ErrorEvent
second_title: Aspose.HTML für .NET-API-Referenz
description: DieErrorEvent./errorevent liefert kontextbezogene Informationen zu Fehlern die während der Laufzeit aufgetreten sind.
type: docs
weight: 770
url: /de/net/aspose.html.dom.events/errorevent/
---
## ErrorEvent class

Die[`ErrorEvent`](../errorevent) liefert kontextbezogene Informationen zu Fehlern, die während der Laufzeit aufgetreten sind.

```csharp
public class ErrorEvent : Event
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ErrorEvent](errorevent#constructor_1)(Exception) | Initialisiert eine neue Instanz von[`ErrorEvent`](../errorevent) Klasse. |
| [ErrorEvent](errorevent#constructor)(IDictionary&lt;string, object&gt;) | Initialisiert eine neue Instanz von[`ErrorEvent`](../errorevent) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles) { get; } | Wird verwendet, um anzugeben, ob ein Ereignis ein Blasenereignis ist oder nicht. Wenn das Ereignis sprudeln kann, ist der Wert wahr, andernfalls ist der Wert falsch. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable) { get; } | Wird verwendet, um anzugeben, ob die Standardaktion eines Ereignisses verhindert werden kann oder nicht. Wenn die Standardaktion verhindert werden kann, ist der Wert wahr, andernfalls ist der Wert falsch. |
| [ColNo](../../aspose.html.dom.events/errorevent/colno) { get; } | Das colno-Attribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn das Objekt erstellt wird, muss dieses Attribut auf Null initialisiert werden. Es stellt die Spaltennummer dar, in der der Fehler im Skript aufgetreten ist. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget) { get; } | Wird verwendet, um die anzuzeigen[`IEventTarget`](../ieventtarget) Deren[`IEventListener`](../ieventlistener) s werden gerade verarbeitet. Dies ist besonders nützlich beim Erfassen und Bubbling. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented) { get; } | Gibt „true“ zurück, wenn preventDefault() aufgerufen wurde, während der Wert des abbrechbaren Attributs „true“ ist, andernfalls „false“. |
| [Error](../../aspose.html.dom.events/errorevent/error) { get; } | Das Fehlerattribut muss den Wert zurückgeben, auf den es initialisiert wurde. Wenn das Objekt erstellt wird, muss dieses Attribut auf null initialisiert werden. Gegebenenfalls wird es auf das Objekt gesetzt, das den Fehler darstellt (z. B. das Ausnahmeobjekt im Fall einer nicht abgefangenen DOM-Ausnahme). |
| [EventPhase](../../aspose.html.dom.events/event/eventphase) { get; } | Wird verwendet, um anzugeben, welche Phase des Ereignisflusses derzeit ausgewertet wird. |
| [FileName](../../aspose.html.dom.events/errorevent/filename) { get; } | Das filename-Attribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn das Objekt erstellt wird, muss dieses Attribut mit der leeren Zeichenfolge initialisiert werden. Es stellt die absolute URL des Skripts dar, in dem der Fehler ursprünglich aufgetreten ist. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted) { get; } | Das isTrusted-Attribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn ein Ereignis erstellt wird, muss das Attribut auf „false“ initialisiert werden. |
| [LineNo](../../aspose.html.dom.events/errorevent/lineno) { get; } | Das lineno-Attribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn das Objekt erstellt wird, muss dieses Attribut auf Null initialisiert werden. Es stellt die Zeilennummer dar, in der der Fehler im Skript aufgetreten ist. |
| [Message](../../aspose.html.dom.events/errorevent/message) { get; } | Das Nachrichtenattribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn das Objekt erstellt wird, muss dieses Attribut mit der leeren Zeichenfolge initialisiert werden. Es stellt die Fehlermeldung dar. |
| [Target](../../aspose.html.dom.events/event/target) { get; } | Wird verwendet, um die anzuzeigen[`IEventTarget`](../ieventtarget) an die das Ereignis ursprünglich gesendet wurde. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp) { get; } | Wird verwendet, um die Zeit (in Millisekunden relativ zur Epoche) anzugeben, zu der das Ereignis erstellt wurde. Da einige Systeme diese Informationen möglicherweise nicht bereitstellen, ist der Wert von timeStamp möglicherweise nicht für alle Ereignisse verfügbar. Wenn nicht verfügbar , wird ein Wert von 0 zurückgegeben. Beispiele für Epochenzeit sind die Zeit des Systemstarts oder 0:0:0 UTC 1. Januar 1970. |
| [Type](../../aspose.html.dom.events/event/type) { get; } | Der Name des Ereignisses (Groß-/Kleinschreibung wird nicht beachtet). Der Name muss ein XML-Name sein. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent)(string, bool, bool) | Die[`InitEvent`](../event/initevent) -Methode wird verwendet, um den Wert von an zu initialisieren[`Event`](../event) erstellt durch the [`IDocumentEvent`](../idocumentevent) Schnittstelle. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault)() | Wenn eine Veranstaltung stornierbar ist, wird die[`PreventDefault`](../event/preventdefault) -Methode wird verwendet, um anzugeben, dass das Ereignis abgebrochen werden soll, , was bedeutet, dass eine Standardaktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt wird, nicht ausgeführt wird. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation)() | Das Aufrufen dieser Methode verhindert, dass das Ereignis alle Ereignis-Listener erreicht, die nach dem aktuellen registriert sind, und wenn es in einem Baum gesendet wird, verhindert es auch, dass das Ereignis andere Objekte erreicht. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation)() | Die[`StopPropagation`](../event/stoppropagation) -Methode verwendet wird, verhindert die weitere Ausbreitung eines Ereignisses während des Ereignisflusses. |

### Siehe auch

* class [Event](../event)
* namensraum [Aspose.Html.Dom.Events](../../aspose.html.dom.events)
* Montage [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
