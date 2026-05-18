---
title: "EventTarget.DispatchEvent"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος EventTarget. Αποστέλλει ένα Event στον καθορισμένο EventTarget συγχρονισμένα, ενεργοποιώντας τους επηρεαζόμενους EventListeners με τη σωστή σειρά. Οι κανονικοί κανόνες επεξεργασίας συμβάντων, συμπεριλαμβανομένης της σύλληψης και της προαιρετικής φάσης φουσκώματος, ισχύουν επίσης για τα συμβάντα που αποστέλλονται χειροκίνητα με dispatchEvent"
type: docs

url: /el/java/com.aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Αποστέλλει ένα Event στον καθορισμένο [`EventTarget`](../../../com.aspose.html.dom.events/ieventtarget/), (συγχρονισμένα) ενεργοποιώντας τους επηρεαζόμενους EventListeners με τη σωστή σειρά. Οι κανονικοί κανόνες επεξεργασίας συμβάντων (συμπεριλαμβανομένης της σύλληψης και της προαιρετικής φάσης φουσκώματος) ισχύουν επίσης για τα συμβάντα που αποστέλλονται χειροκίνητα με [`dispatchEvent()`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/).

```java
public bool DispatchEvent(Event @event)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| συμβάν | Γεγονός | Καθορίζει τον τύπο του συμβάντος, τη συμπεριφορά και τις συμφραζόμενες πληροφορίες που θα χρησιμοποιηθούν στην επεξεργασία του συμβάντος. |

### Τιμή επιστροφής

Η τιμή επιστροφής του υποδεικνύει εάν κάποιοι από τους listeners που διαχειρίστηκαν το συμβάν κλήθηκαν. Εάν κλήθηκε, η τιμή είναι false, αλλιώς η τιμή είναι true.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../domexception/) |  |

## Παρατηρήσεις

Τα συμβάντα που αποστέλλονται με αυτόν τον τρόπο θα έχουν την ίδια συμπεριφορά σύλληψης και ανόδου όπως τα συμβάντα που αποστέλλονται απευθείας από την υλοποίηση. Ο στόχος του συμβάντος είναι το on στο οποίο καλείται.

### Δείτε επίσης

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
