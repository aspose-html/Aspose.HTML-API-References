---
title: "Event.InitEvent"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Event. Η μέθοδος InitEvent χρησιμοποιείται για την αρχικοποίηση της τιμής ενός Event που δημιουργείται μέσω της διεπαφής IDocumentEvent."
type: docs

url: /el/java/com.aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

Η μέθοδος `InitEvent` χρησιμοποιείται για την αρχικοποίηση της τιμής ενός [`Event`](../) που δημιουργείται μέσω της διεπαφής [`IDocumentEvent`](../../idocumentevent/).

```java
public void InitEvent(String type, bool bubbles, bool cancelable)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | String | Ο τύπος του γεγονότος. |
| bubbles | Boolean | αν οριστεί σε `true` [bubbles]. |
| cancelable | Boolean | αν οριστεί σε `true` [cancelable]. |

## Παρατηρήσεις

Αυτή η μέθοδος μπορεί να κληθεί μόνο πριν το Event έχει αποσταλεί μέσω της μεθόδου [`DispatchEvent`](../../ieventtarget/dispatchevent/), αν και μπορεί να κληθεί πολλές φορές κατά τη διάρκεια αυτής της φάσης εάν είναι απαραίτητο. Εάν κληθεί πολλές φορές, η τελική κλήση έχει προτεραιότητα. Εάν κληθεί από μια υποκλάση της διεπαφής Event, μόνο οι τιμές που καθορίζονται στη μέθοδο initEvent τροποποιούνται, όλα τα άλλα χαρακτηριστικά παραμένουν αμετάβλητα.

### Δείτε επίσης

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
