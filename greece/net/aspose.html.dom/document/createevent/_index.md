---
title: Document.CreateEvent
second_title: Aspose.HTML για Αναφορά API .NET
description: Document μέθοδος. Δημιουργεί έναEvent τύπου που υποστηρίζεται από την υλοποίηση.
type: docs
weight: 880
url: /el/net/aspose.html.dom/document/createevent/
---
## Document.CreateEvent method

Δημιουργεί ένα[`Event`](../../../aspose.html.dom.events/event/) τύπου που υποστηρίζεται από την υλοποίηση.

```csharp
public Event CreateEvent(string eventType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| eventType | String | Η παράμετρος eventType καθορίζει τον τύπο του[`Event`](../../../aspose.html.dom.events/event/) διεπαφή που θα δημιουργηθεί.  Αν το[`Event`](../../../aspose.html.dom.events/event/) διεπαφή που καθορίζεται υποστηρίζεται από την υλοποίηση αυτή η μέθοδος θα επιστρέψει ένα νέο[`Event`](../../../aspose.html.dom.events/event/) του ζητούμενου τύπου διεπαφής. Εάν το[`Event`](../../../aspose.html.dom.events/event/)πρόκειται να αποσταλεί μέσω του[`DispatchEvent`](../../../aspose.html.dom.events/ieventtarget/dispatchevent/) μέθοδος η κατάλληλη[`InitEvent`](../../../aspose.html.dom.events/event/initevent/) Η μέθοδος πρέπει να κληθεί μετά τη δημιουργία για να αρχικοποιηθεί η[`Event`](../../../aspose.html.dom.events/event/) τιμές s. |

### Επιστρεφόμενη Αξία

Το νεοδημιουργημένο[`Event`](../../../aspose.html.dom.events/event/)

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Αυξάνεται εάν η υλοποίηση δεν υποστηρίζει τον τύπο του[`Event`](../../../aspose.html.dom.events/event/) ζητήθηκε διεπαφή |

### Δείτε επίσης

* class [Event](../../../aspose.html.dom.events/event/)
* class [Document](../)
* χώρος ονομάτων [Aspose.Html.Dom](../../document/)
* συνέλευση [Aspose.HTML](../../../)


