---
title: IEventTarget.DispatchEvent
second_title: Aspose.HTML για Αναφορά API .NET
description: IEventTarget μέθοδος. Αυτή η μέθοδος επιτρέπει την αποστολή συμβάντων στο μοντέλο συμβάντων υλοποιήσεων.
type: docs
weight: 20
url: /el/net/aspose.html.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

Αυτή η μέθοδος επιτρέπει την αποστολή συμβάντων στο μοντέλο συμβάντων υλοποιήσεων.

```csharp
public bool DispatchEvent(Event @event)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| event | Event | Καθορίζει τον τύπο συμβάντος, τη συμπεριφορά και τις πληροφορίες συμφραζομένων που θα χρησιμοποιηθούν για την επεξεργασία του συμβάντος. |

### Επιστρεφόμενη Αξία

Η επιστρεφόμενη τιμή του[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) υποδεικνύει εάν κάποιος από τους ακροατές που χειρίστηκαν το συμβάν κάλεσαν[`PreventDefault`](../../event/preventdefault/) . Αν[`PreventDefault`](../../event/preventdefault/) ονομάστηκε η τιμή είναι ψευδής, αλλιώς η τιμή είναι true.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) |  |

### Παρατηρήσεις

Τα συμβάντα που αποστέλλονται με αυτόν τον τρόπο θα έχουν την ίδια συμπεριφορά καταγραφής και δημιουργίας φυσαλίδων με τα συμβάντα που αποστέλλονται απευθείας από την υλοποίηση. Ο στόχος του συμβάντος είναι[`EventTarget`](../../../aspose.html.dom/eventtarget/) επί του οποίου[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) ονομάζεται.

### Δείτε επίσης

* class [Event](../../event/)
* interface [IEventTarget](../)
* χώρος ονομάτων [Aspose.Html.Dom.Events](../../ieventtarget/)
* συνέλευση [Aspose.HTML](../../../)


