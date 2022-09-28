---
title: InputEvent
second_title: Aspose.HTML für .NET-API-Referenz
description: Eingabeereignisse werden als Benachrichtigungen gesendet wenn das DOM aktualisiert wird.
type: docs
weight: 830
url: /de/net/aspose.html.dom.events/inputevent/
---
## InputEvent class

Eingabeereignisse werden als Benachrichtigungen gesendet, wenn das DOM aktualisiert wird.

```csharp
public class InputEvent : UIEvent
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [InputEvent](inputevent#constructor)(string) | Initialisiert eine neue Instanz von[`InputEvent`](../inputevent) Klasse. |
| [InputEvent](inputevent#constructor_1)(string, IDictionary&lt;string, object&gt;) | Initialisiert eine neue Instanz von[`InputEvent`](../inputevent) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles) { get; } | Wird verwendet, um anzugeben, ob ein Ereignis ein Blasenereignis ist oder nicht. Wenn das Ereignis sprudeln kann, ist der Wert wahr, andernfalls ist der Wert falsch. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable) { get; } | Wird verwendet, um anzugeben, ob die Standardaktion eines Ereignisses verhindert werden kann oder nicht. Wenn die Standardaktion verhindert werden kann, ist der Wert wahr, andernfalls ist der Wert falsch. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget) { get; } | Wird verwendet, um die anzuzeigen[`IEventTarget`](../ieventtarget) Deren[`IEventListener`](../ieventlistener) s werden gerade verarbeitet. Dies ist besonders nützlich beim Erfassen und Bubbling. |
| [Data](../../aspose.html.dom.events/inputevent/data) { get; } | Die Daten enthalten den Wert der Zeichen, die von einer Eingabemethode generiert wurden. Dies KANN ein einzelnes Unicode-Zeichen oder eine nicht leere Folge von Unicode-Zeichen [Unicode] sein. Zeichen SOLLTEN gemäß der Unicode-Normalisierungsform NFC, definiert in [UAX15], normalisiert werden. Dieses Attribut KANN die leere Zeichenkette enthalten. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented) { get; } | Gibt „true“ zurück, wenn preventDefault() aufgerufen wurde, während der Wert des abbrechbaren Attributs „true“ ist, andernfalls „false“. |
| [Detail](../../aspose.html.dom.events/uievent/detail) { get; } | Gibt je nach Art des Ereignisses einige Detailinformationen zum Ereignis an. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase) { get; } | Wird verwendet, um anzugeben, welche Phase des Ereignisflusses derzeit ausgewertet wird. |
| [IsComposing](../../aspose.html.dom.events/inputevent/iscomposing) { get; } | wahr, wenn das Eingabeereignis als Teil einer Zusammensetzungssitzung auftritt, dh nach einem Zusammensetzungsstartereignis und vor dem entsprechenden Zusammensetzungsendereignis. Der nicht initialisierte Wert dieses Attributs MUSS false sein. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted) { get; } | Das isTrusted-Attribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn ein Ereignis erstellt wird, muss das Attribut auf „false“ initialisiert werden. |
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
