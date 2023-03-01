---
title: SVGSVGElement.CreateEvent
second_title: Aspose.HTML για Αναφορά API .NET
description: SVGSVGElement μέθοδος. Δημιουργεί έναEvent τύπου που υποστηρίζεται από την υλοποίηση.
type: docs
weight: 110
url: /el/net/aspose.html.dom.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

Δημιουργεί ένα[`Event`](../../../aspose.html.dom.events/event/) τύπου που υποστηρίζεται από την υλοποίηση.

```csharp
public Event CreateEvent(string eventType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| eventType | String | Η παράμετρος eventType καθορίζει τον τύπο του[`Event`](../../../aspose.html.dom.events/event/) διεπαφή που θα δημιουργηθεί.  Αν το[`Event`](../../../aspose.html.dom.events/event/)διεπαφή που καθορίστηκε υποστηρίζεται από την υλοποίηση αυτή η μέθοδος θα επιστρέψει ένα new [`Event`](../../../aspose.html.dom.events/event/) του ζητούμενου τύπου διεπαφής. Εάν το[`Event`](../../../aspose.html.dom.events/event/)πρόκειται να αποσταλεί μέσω του[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) μέθοδος η κατάλληλη [`InitEvent`](../../../aspose.html.dom.events/event/initevent/) Η μέθοδος πρέπει να κληθεί μετά τη δημιουργία για να αρχικοποιηθεί η[`Event`](../../../aspose.html.dom.events/event/) τιμές s. |

### Επιστρεφόμενη Αξία

Το νεοδημιουργημένο[`Event`](../../../aspose.html.dom.events/event/)

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Αυξάνεται εάν η υλοποίηση δεν υποστηρίζει τον τύπο[`Event`](../../../aspose.html.dom.events/event/) διεπαφή requested |

### Δείτε επίσης

* class [Event](../../../aspose.html.dom.events/event/)
* class [SVGSVGElement](../)
* χώρος ονομάτων [Aspose.Html.Dom.Svg](../../svgsvgelement/)
* συνέλευση [Aspose.HTML](../../../)


