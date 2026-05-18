---
title: "CustomEvent.InitCustomEvent"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος CustomEvent. /// Η μέθοδος InitEvent χρησιμοποιείται για την αρχικοποίηση της τιμής ενός Event που δημιουργείται μέσω της διεπαφής IDocumentEvent"
type: docs

url: /el/java/com.aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// Η μέθοδος [`InitEvent`](../../event/initevent/) χρησιμοποιείται για την αρχικοποίηση της τιμής ενός [`Event`](../../event/) που δημιουργείται μέσω της διεπαφής [`IDocumentEvent`](../../idocumentevent/).

```java
public void InitCustomEvent(String type, bool bubbles, bool cancelable, object detail)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τύπος | String | Ο τύπος του συμβάντος. |
| bubbles | Boolean | εάν οριστεί σε `true` [bubbles]. |
| cancelable | Boolean | εάν οριστεί σε `true` [cancelable]. |
| detail | Αντικείμενο | Τα προσαρμοσμένα δεδομένα. |

## Παρατηρήσεις

Αυτή η μέθοδος μπορεί να κληθεί μόνο πριν το Event διανεμηθεί μέσω της μεθόδου [`DispatchEvent`](../../ieventtarget/dispatchevent/), αν και μπορεί να κληθεί πολλές φορές κατά τη διάρκεια αυτής της φάσης εάν είναι απαραίτητο. Εάν κληθεί πολλές φορές, η τελική κλήση έχει προτεραιότητα. Εάν κληθεί από μια υποκλάση της διεπαφής Event, μόνο οι τιμές που καθορίζονται στη μέθοδο initEvent τροποποιούνται, όλα τα άλλα χαρακτηριστικά παραμένουν αμετάβλητα.

### Δείτε επίσης

* class [CustomEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
