---
title: EventTarget.DispatchEvent
second_title: Aspose.HTML για Αναφορά API .NET
description: EventTarget μέθοδος. Αυτή η μέθοδος επιτρέπει την αποστολή συμβάντων στο μοντέλο συμβάντων υλοποιήσεων.
type: docs
weight: 20
url: /el/net/aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Αυτή η μέθοδος επιτρέπει την αποστολή συμβάντων στο μοντέλο συμβάντων υλοποιήσεων.

```csharp
public bool DispatchEvent(Event @event)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| event | Event | Καθορίζει τον τύπο συμβάντος, τη συμπεριφορά και τις πληροφορίες συμφραζομένων που θα χρησιμοποιηθούν για την επεξεργασία του συμβάντος. |

### Επιστρεφόμενη Αξία

Η επιστρεφόμενη τιμή του`DispatchEvent` υποδεικνύει εάν κάποιος από τους ακροατές που χειρίστηκαν το συμβάν κάλεσαν[`PreventDefault`](../../../aspose.html.dom.events/event/preventdefault/) . Αν[`PreventDefault`](../../../aspose.html.dom.events/event/preventdefault/) ονομάστηκε η τιμή είναι ψευδής, αλλιώς η τιμή είναι true.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../domexception/) |  |

### Παρατηρήσεις

Τα συμβάντα που αποστέλλονται με αυτόν τον τρόπο θα έχουν την ίδια συμπεριφορά καταγραφής και δημιουργίας φυσαλίδων με τα συμβάντα που αποστέλλονται απευθείας από την υλοποίηση. Ο στόχος του συμβάντος είναι[`EventTarget`](../) επί του οποίου`DispatchEvent` ονομάζεται.

### Δείτε επίσης

* class [Event](../../../aspose.html.dom.events/event/)
* class [EventTarget](../)
* χώρος ονομάτων [Aspose.Html.Dom](../../eventtarget/)
* συνέλευση [Aspose.HTML](../../../)


