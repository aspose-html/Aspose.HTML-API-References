---
title: "IEventTarget.AddEventListener"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "IEventTarget method. Η μέθοδος EventTarget addEventListener ορίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο."
type: docs

url: /el/java/com.aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(String, IEventListener) {#addeventlistener}

Η μέθοδος addEventListener() της EventTarget ορίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο.

Κοινά στόχοι είναι το Element, το Document και το Window, αλλά ο στόχος μπορεί να είναι οποιοδήποτε αντικείμενο που υποστηρίζει συμβάντα (όπως το XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τύπος | String | Μια ευαίσθητη σε πεζά-κεφαλαία String που αντιπροσωπεύει τον τύπο του συμβάντος για την ακρόαση. |
| listener | IEventListener | Δέχεται μια διεπαφή που υλοποιείται από τον χρήστη και περιέχει τις μεθόδους που θα κληθούν όταν συμβεί το συμβάν. |

## Παρατηρήσεις

Εάν ένα is προστίθεται σε ένα ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες αλλά μπορεί να ενεργοποιηθεί σε μεταγενέστερο στάδιο της ροής του συμβάντος, όπως η φάση ανόδου. Εάν πολλαπλοί ταυτόσημοι Event Listeners καταχωρηθούν στο ίδιο με τις ίδιες παραμέτρους, οι διπλότυπες εμφανίσεις απορρίπτονται. Δεν προκαλούν το να κληθεί δύο φορές και επειδή απορρίπτονται δεν χρειάζεται να αφαιρεθούν με τη μέθοδο.

### Δείτε επίσης

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_1}

Η μέθοδος addEventListener() της EventTarget ορίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο.

Κοινά στόχοι είναι το Element, το Document και το Window, αλλά ο στόχος μπορεί να είναι οποιοδήποτε αντικείμενο που υποστηρίζει συμβάντα (όπως το XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τύπος | String | Μια ευαίσθητη σε πεζά-κεφαλαία String που αντιπροσωπεύει τον τύπο του συμβάντος για την ακρόαση. |
| listener | IEventListener | Δέχεται μια διεπαφή που υλοποιείται από τον χρήστη και περιέχει τις μεθόδους που θα κληθούν όταν συμβεί το συμβάν. |
| useCapture | Boolean | Εάν είναι true, το useCapture υποδεικνύει ότι ο χρήστης επιθυμεί να ξεκινήσει τη σύλληψη. Μετά την έναρξη της σύλληψης, όλα τα συμβάντα του καθορισμένου τύπου θα αποστέλλονται στους καταχωρημένους πριν αποσταλούν σε οποιονδήποτε Event Targets κάτω από αυτούς στο δέντρο. Τα συμβάντα που ανέρχονται μέσω του δέντρου δεν θα ενεργοποιήσουν έναν καθορισμένο να χρησιμοποιήσει σύλληψη. |

## Παρατηρήσεις

Εάν ένα is προστίθεται σε ένα ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες αλλά μπορεί να ενεργοποιηθεί σε μεταγενέστερο στάδιο της ροής του συμβάντος, όπως η φάση ανόδου. Εάν πολλαπλοί ταυτόσημοι Event Listeners καταχωρηθούν στο ίδιο με τις ίδιες παραμέτρους, οι διπλότυπες εμφανίσεις απορρίπτονται. Δεν προκαλούν το να κληθεί δύο φορές και επειδή απορρίπτονται δεν χρειάζεται να αφαιρεθούν με τη μέθοδο.

### Δείτε επίσης

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
