---
title: "IEventListener Διεπαφή"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.events.IEventListener διεπαφή. Η διεπαφή είναι η κύρια μέθοδος για τη διαχείριση συμβάντων. Οι χρήστες υλοποιούν τη διεπαφή και καταχωρούν τον listener τους χρησιμοποιώντας τη μέθοδο. Οι χρήστες πρέπει επίσης να αφαιρέσουν τον listener τους από αυτήν μετά την ολοκλήρωση της χρήσης του."
type: docs

url: /el/java/com.aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

Το interface είναι η κύρια μέθοδος για τη διαχείριση των events. Οι χρήστες υλοποιούν το interface και καταχωρούν τον ακροατή τους σε ένα χρησιμοποιώντας τη μέθοδο. Οι χρήστες θα πρέπει επίσης να αφαιρέσουν τον ακροατή τους από αυτό μετά την ολοκλήρωση της χρήσης του.

```java
public interface IEventListener
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [handleEvent](../../com.aspose.html.dom.events/ieventlistener/handleevent/)(Event) | Αυτή η μέθοδος καλείται όποτε συμβαίνει ένα συμβάν του τύπου για τον οποίο η διεπαφή έχει καταχωρηθεί. |

## Παρατηρήσεις

Όταν ένας Node αντιγράφεται χρησιμοποιώντας τη μέθοδο cloneNode, οι Event Listeners που είναι συνδεδεμένοι με τον πηγαίο Node δεν συνδέονται με τον αντίγραφο Node. Εάν ο χρήστης επιθυμεί οι ίδιοι Event Listeners να προστεθούν στο νεοδημιουργημένο αντίγραφο, πρέπει να τους προσθέσει χειροκίνητα.

### Δείτε επίσης

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
