---
title: IDocumentEvent.CreateEvent
second_title: Aspose.HTML για Αναφορά API .NET
description: IDocumentEvent μέθοδος. Δημιουργεί έναEvent τύπου που υποστηρίζεται από την υλοποίηση.
type: docs
weight: 10
url: /el/net/aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

Δημιουργεί ένα[`Event`](../../event/) τύπου που υποστηρίζεται από την υλοποίηση.

```csharp
public Event CreateEvent(string eventType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| eventType | String | Η παράμετρος eventType καθορίζει τον τύπο του[`Event`](../../event/) διεπαφή που θα δημιουργηθεί.  Αν το[`Event`](../../event/)διεπαφή που καθορίστηκε υποστηρίζεται από την υλοποίηση αυτή η μέθοδος θα επιστρέψει ένα new [`Event`](../../event/) του ζητούμενου τύπου διεπαφής. Εάν το[`Event`](../../event/)πρόκειται να αποσταλεί μέσω του[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) μέθοδος η κατάλληλη [`InitEvent`](../../event/initevent/) Η μέθοδος πρέπει να κληθεί μετά τη δημιουργία για να αρχικοποιηθεί η[`Event`](../../event/) τιμές s. |

### Επιστρεφόμενη Αξία

Το νεοδημιουργημένο[`Event`](../../event/)

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Αυξάνεται εάν η υλοποίηση δεν υποστηρίζει τον τύπο[`Event`](../../event/) διεπαφή requested |

### Δείτε επίσης

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* χώρος ονομάτων [Aspose.Html.Dom.Events](../../idocumentevent/)
* συνέλευση [Aspose.HTML](../../../)


