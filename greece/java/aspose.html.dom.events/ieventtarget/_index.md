---
title: "Διεπαφή IEventTarget"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Διεπαφή com.aspose.html.dom.events.IEventTarget. Η διεπαφή EventTarget υλοποιείται από όλους τους Κόμβους σε μια υλοποίηση που υποστηρίζει το μοντέλο συμβάντων DOM. Συνεπώς, αυτή η διεπαφή μπορεί να ληφθεί χρησιμοποιώντας μεθόδους μετατροπής ειδικές για το binding σε μια παρουσία της διεπαφής Node. Η διεπαφή επιτρέπει την εγγραφή και αφαίρεση των Event Listeners σε ένα και την αποστολή συμβάντων σε αυτό."
type: docs

url: /el/java/com.aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

Το interface EventTarget υλοποιείται από όλους τους Κόμβους σε μια υλοποίηση που υποστηρίζει το μοντέλο DOM Event. Συνεπώς, αυτό το interface μπορεί να ληφθεί χρησιμοποιώντας μεθόδους μετατροπής ειδικές για binding σε μια παρουσία του interface Node. Το interface επιτρέπει την καταχώριση και αφαίρεση των Event Listeners σε ένα και την αποστολή γεγονότων σε αυτό.

```java
public interface IEventTarget
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(String, IEventListener) | Η μέθοδος addEventListener() του EventTarget ορίζει μια συνάρτηση που θα κληθεί κάθε φορά που το καθορισμένο συμβάν παραδίδεται στο στόχο. |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener, bool) | Η μέθοδος addEventListener() του EventTarget ορίζει μια συνάρτηση που θα κληθεί κάθε φορά που το καθορισμένο συμβάν παραδίδεται στο στόχο. |
| [dispatchEvent](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | Αποστέλλει ένα συμβάν στο καθορισμένο EventTarget, (συγχρονισμένα) ενεργοποιώντας τους επηρεαζόμενους EventListeners με τη σωστή σειρά. Οι κανονικοί κανόνες επεξεργασίας συμβάντων (συμπεριλαμβανομένου του φάσματος σύλληψης και της προαιρετικής φάσης φούσκας) ισχύουν επίσης για συμβάντα που αποστέλλονται χειροκίνητα με τη dispatchEvent(). |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(String, IEventListener) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένας αφαιρεθεί από ένα ενώ επεξεργάζεται ένα event, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένας αφαιρεθεί από ένα ενώ επεξεργάζεται ένα event, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |

### Δείτε επίσης

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
