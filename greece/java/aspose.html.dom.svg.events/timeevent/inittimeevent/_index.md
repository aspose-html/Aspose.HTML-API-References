---
title: "TimeEvent.InitTimeEvent"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος TimeEvent. Η μέθοδος initTimeEvent χρησιμοποιείται για την αρχικοποίηση της τιμής ενός TimeEvent που δημιουργείται μέσω της διεπαφής DocumentEvent. Αυτή η μέθοδος μπορεί να κληθεί μόνο πριν το TimeEvent διανεμηθεί μέσω της μεθόδου dispatchEvent, αν και μπορεί να κληθεί πολλαπλές φορές κατά τη διάρκεια αυτής της φάσης εάν είναι απαραίτητο. Εάν κληθεί πολλαπλές φορές, η τελική κλήση έχει προτεραιότητα."
type: docs

url: /el/java/com.aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

Η μέθοδος initTimeEvent χρησιμοποιείται για την αρχικοποίηση της τιμής ενός TimeEvent που δημιουργείται μέσω της διεπαφής DocumentEvent. Αυτή η μέθοδος μπορεί να κληθεί μόνο πριν το TimeEvent αποσταλεί μέσω της μεθόδου dispatchEvent, αν και μπορεί να κληθεί πολλαπλές φορές κατά τη διάρκεια αυτής της φάσης εάν είναι απαραίτητο. Εάν κληθεί πολλαπλές φορές, η τελική κλήση έχει προτεραιότητα.

```java
public void InitTimeEvent(String typeArg, IAbstractView viewArg, long detailArg)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| typeArg | String | Καθορίζει τον τύπο του γεγονότος. |
| viewArg | IAbstractView | Καθορίζει το AbstractView του γεγονότος. |
| detailArg | Int64 | Καθορίζει τις λεπτομέρειες του γεγονότος. |

### Δείτε επίσης

* interface [IAbstractView](../../../com.aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* package [com.aspose.html.dom.svg.events](../../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../../)
