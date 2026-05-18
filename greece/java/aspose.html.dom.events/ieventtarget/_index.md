---
title: "Διεπαφή IEventTarget"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Διεπαφή com.aspose.html.dom.events.IEventTarget. Η διεπαφή EventTarget υλοποιείται από όλους τους Κόμβους σε μια υλοποίηση που υποστηρίζει το μοντέλο DOM Event. Συνεπώς αυτή η διεπαφή μπορεί να ληφθεί χρησιμοποιώντας μεθόδους μετατροπής ειδικές για το binding σε μια παρουσία της διεπαφής Node. Η διεπαφή επιτρέπει την εγγραφή και αφαίρεση των Event Listeners σε ένα και την αποστολή συμβάντων σε αυτό."
type: docs

url: /el/java/com.aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

Το EventTarget interface υλοποιείται από όλους τους Nodes σε μια υλοποίηση που υποστηρίζει το DOM Event Model. Συνεπώς, αυτό το interface μπορεί να ληφθεί χρησιμοποιώντας μεθόδους μετατροπής ειδικές για binding σε μια παρουσία του Node interface. Το interface επιτρέπει την καταχώρηση και αφαίρεση των Event Listeners σε ένα και την αποστολή των events σε αυτό.

```java
public interface IEventTarget
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(String, IEventListener) | Η μέθοδος addEventListener() της EventTarget ορίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener, bool) | Η μέθοδος addEventListener() της EventTarget ορίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [dispatchEvent](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | Αποστέλλει ένα Event στο καθορισμένο EventTarget, (συγχρονικά) ενεργοποιώντας τους επηρεαζόμενους EventListeners με τη σωστή σειρά. Οι κανονικοί κανόνες επεξεργασίας συμβάντων (συμπεριλαμβανομένων των φάσεων σύλληψης και προαιρετικής φούσκας) ισχύουν επίσης για συμβάντα που αποστέλλονται χειροκίνητα με τη dispatchEvent(). |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(String, IEventListener) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |

### Δείτε επίσης

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
