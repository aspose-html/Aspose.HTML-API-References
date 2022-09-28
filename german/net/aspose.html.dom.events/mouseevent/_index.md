---
title: MouseEvent
second_title: Aspose.HTML für .NET-API-Referenz
description: Die MouseEventSchnittstelle stellt spezifische Kontextinformationen zu Mausereignissen bereit.
type: docs
weight: 850
url: /de/net/aspose.html.dom.events/mouseevent/
---
## MouseEvent class

Die MouseEvent-Schnittstelle stellt spezifische Kontextinformationen zu Mausereignissen bereit.

```csharp
public class MouseEvent : UIEvent
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [MouseEvent](mouseevent#constructor)(string) | Initialisiert eine neue Instanz von[`MouseEvent`](../mouseevent) Klasse. |
| [MouseEvent](mouseevent#constructor_1)(string, IDictionary&lt;string, object&gt;) | Initialisiert eine neue Instanz von[`MouseEvent`](../mouseevent) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/mouseevent/altkey) { get; } | Siehe das altKey-Attribut. |
| [Bubbles](../../aspose.html.dom.events/event/bubbles) { get; } | Wird verwendet, um anzugeben, ob ein Ereignis ein Blasenereignis ist oder nicht. Wenn das Ereignis sprudeln kann, ist der Wert wahr, andernfalls ist der Wert falsch. |
| [Button](../../aspose.html.dom.events/mouseevent/button) { get; } | Bei Mausereignissen, die durch das Drücken oder Loslassen einer Maustaste verursacht werden, MUSS die Taste verwendet werden, um anzugeben, welche Taste des Zeigegeräts den Status geändert hat. |
| [Buttons](../../aspose.html.dom.events/mouseevent/buttons) { get; } | Bei allen Mausereignissen MÜSSEN Schaltflächen verwendet werden, um anzuzeigen, welche Kombination von Maustasten gerade gedrückt wird, ausgedrückt als Bitmaske. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable) { get; } | Wird verwendet, um anzugeben, ob die Standardaktion eines Ereignisses verhindert werden kann oder nicht. Wenn die Standardaktion verhindert werden kann, ist der Wert wahr, andernfalls ist der Wert falsch. |
| [ClientX](../../aspose.html.dom.events/mouseevent/clientx) { get; } | Die horizontale Koordinate, an der das Ereignis aufgetreten ist, relativ zu dem mit dem Ereignis verknüpften Darstellungsfenster. |
| [ClientY](../../aspose.html.dom.events/mouseevent/clienty) { get; } | Die vertikale Koordinate, an der das Ereignis aufgetreten ist, relativ zu dem mit dem Ereignis verknüpften Darstellungsfenster. |
| [CtrlKey](../../aspose.html.dom.events/mouseevent/ctrlkey) { get; } | Siehe das Attribut ctrlKey. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget) { get; } | Wird verwendet, um die anzuzeigen[`IEventTarget`](../ieventtarget) Deren[`IEventListener`](../ieventlistener) s werden gerade verarbeitet. Dies ist besonders nützlich beim Erfassen und Bubbling. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented) { get; } | Gibt „true“ zurück, wenn preventDefault() aufgerufen wurde, während der Wert des abbrechbaren Attributs „true“ ist, andernfalls „false“. |
| [Detail](../../aspose.html.dom.events/uievent/detail) { get; } | Gibt je nach Art des Ereignisses einige Detailinformationen zum Ereignis an. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase) { get; } | Wird verwendet, um anzugeben, welche Phase des Ereignisflusses derzeit ausgewertet wird. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted) { get; } | Das isTrusted-Attribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn ein Ereignis erstellt wird, muss das Attribut auf „false“ initialisiert werden. |
| [MetaKey](../../aspose.html.dom.events/mouseevent/metakey) { get; } | Verweis auf das metaKey-Attribut. |
| [RelatedTarget](../../aspose.html.dom.events/mouseevent/relatedtarget) { get; } | Wird verwendet, um je nach Art des Ereignisses ein sekundäres EventTarget zu identifizieren, das sich auf ein UI-Ereignis bezieht. |
| [ScreenX](../../aspose.html.dom.events/mouseevent/screenx) { get; } | Die horizontale Koordinate, an der das Ereignis relativ zum Ursprung des Bildschirmkoordinatensystems aufgetreten ist. |
| [ScreenY](../../aspose.html.dom.events/mouseevent/screeny) { get; } | Die vertikale Koordinate, an der das Ereignis aufgetreten ist, relativ zum Ursprung des Bildschirmkoordinatensystems. |
| [ShiftKey](../../aspose.html.dom.events/mouseevent/shiftkey) { get; } | Siehe das shiftKey-Attribut. |
| [Target](../../aspose.html.dom.events/event/target) { get; } | Wird verwendet, um die anzuzeigen[`IEventTarget`](../ieventtarget) an die das Ereignis ursprünglich gesendet wurde. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp) { get; } | Wird verwendet, um die Zeit (in Millisekunden relativ zur Epoche) anzugeben, zu der das Ereignis erstellt wurde. Da einige Systeme diese Informationen möglicherweise nicht bereitstellen, ist der Wert von timeStamp möglicherweise nicht für alle Ereignisse verfügbar. Wenn nicht verfügbar , wird ein Wert von 0 zurückgegeben. Beispiele für Epochenzeit sind die Zeit des Systemstarts oder 0:0:0 UTC 1. Januar 1970. |
| [Type](../../aspose.html.dom.events/event/type) { get; } | Der Name des Ereignisses (Groß-/Kleinschreibung wird nicht beachtet). Der Name muss ein XML-Name sein. |
| [View](../../aspose.html.dom.events/uievent/view) { get; } | Das Ansichtsattribut identifiziert das Fenster, aus dem das Ereignis generiert wurde. Der nicht initialisierte Wert dieses Attributs MUSS null sein. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent)(string, bool, bool) | Die[`InitEvent`](../event/initevent) -Methode wird verwendet, um den Wert von an zu initialisieren[`Event`](../event) erstellt durch the [`IDocumentEvent`](../idocumentevent) Schnittstelle. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault)() | Wenn eine Veranstaltung stornierbar ist, wird die[`PreventDefault`](../event/preventdefault) -Methode wird verwendet, um anzugeben, dass das Ereignis abgebrochen werden soll, , was bedeutet, dass eine Standardaktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt wird, nicht ausgeführt wird. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation)() | Das Aufrufen dieser Methode verhindert, dass das Ereignis alle Ereignis-Listener erreicht, die nach dem aktuellen registriert sind, und wenn es in einem Baum gesendet wird, verhindert es auch, dass das Ereignis andere Objekte erreicht. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation)() | Die[`StopPropagation`](../event/stoppropagation) -Methode verwendet wird, verhindert die weitere Ausbreitung eines Ereignisses während des Ereignisflusses. |

### Siehe auch

* class [UIEvent](../uievent)
* namensraum [Aspose.Html.Dom.Events](../../aspose.html.dom.events)
* Montage [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
