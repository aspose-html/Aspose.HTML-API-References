---
title: Interface IEventListener
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Dom.Events.IEventListener διεπαφή. ΤοIEventListenerΗ διεπαφή είναι η κύρια μέθοδος για το χειρισμό συμβάντων. Οι χρήστες υλοποιούν τοIEventListener διασύνδεση και εγγραφή του ακροατή τους σε έναEventTarget χρησιμοποιώντας τηνAddEventListener μέθοδος. Οι χρήστες θα πρέπει επίσης να αφαιρέσουν το δικό τουςIEventListener από τοEventTarget αφού ολοκληρώσουν τη χρήση του ακροατή.
type: docs
weight: 800
url: /el/net/aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

Το`IEventListener`Η διεπαφή είναι η κύρια μέθοδος για το χειρισμό συμβάντων. Οι χρήστες υλοποιούν το`IEventListener` διασύνδεση και εγγραφή του ακροατή τους σε ένα[`EventTarget`](../../aspose.html.dom/eventtarget/) χρησιμοποιώντας την[`AddEventListener`](../../aspose.html.dom/eventtarget/addeventlistener/) μέθοδος. Οι χρήστες θα πρέπει επίσης να αφαιρέσουν το δικό τους`IEventListener` από το[`EventTarget`](../../aspose.html.dom/eventtarget/) αφού ολοκληρώσουν τη χρήση του ακροατή.

```csharp
public interface IEventListener
```

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [HandleEvent](../../aspose.html.dom.events/ieventlistener/handleevent/)(Event) | Αυτή η μέθοδος καλείται κάθε φορά που συμβαίνει ένα συμβάν του τύπου για το οποίο το`IEventListener` Η διεπαφή καταχωρήθηκε. |

### Παρατηρήσεις

Όταν ένας κόμβος αντιγράφεται χρησιμοποιώντας τη μέθοδο cloneNode, τα Event Listeners που είναι συνδεδεμένα στον κόμβο προέλευσης δεν συνδέονται στον αντιγραμμένο κόμβο. Εάν ο χρήστης επιθυμεί να προστεθούν τα ίδια Event Listeners στο νεοδημιουργημένο αντίγραφο, ο χρήστης πρέπει να τα προσθέσει χειροκίνητα.

### Δείτε επίσης

* χώρος ονομάτων [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* συνέλευση [Aspose.HTML](../../)


