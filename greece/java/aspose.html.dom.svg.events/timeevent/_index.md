---
title: "Κλάση TimeEvent"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Κλάση com.aspose.html.dom.svg.events.TimeEvent. Η διεπαφή TimeEvent παρέχει συγκεκριμένες συμφραζόμενες πληροφορίες που σχετίζονται με γεγονότα χρόνου. Οι διαφορετικοί τύποι γεγονότων που μπορούν να συμβούν είναι beginEvent, endEvent και repeatEvent."
type: docs

url: /el/java/com.aspose.html.dom.svg.events/timeevent/
---
## TimeEvent class

Η διεπαφή TimeEvent παρέχει συγκεκριμένες συμφραζόμενες πληροφορίες που σχετίζονται με τα χρονικά συμβάντα. Οι διαφορετικοί τύποι συμβάντων που μπορούν να εμφανιστούν είναι: beginEvent, endEvent και repeatEvent.

```java
public class TimeEvent : Event
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Χρησιμοποιείται για να υποδείξει αν ένα συμβάν είναι συμβάν ανάδυσης. Εάν το συμβάν μπορεί να αναδυθεί, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Χρησιμοποιείται για να υποδείξει αν ένα συμβάν μπορεί να αποτρέψει την προεπιλεγμένη του ενέργεια. Εάν η προεπιλεγμένη ενέργεια μπορεί να αποτραπεί, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Χρησιμοποιείται για να υποδείξει το [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) του οποίου οι [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/)s επεξεργάζονται αυτή τη στιγμή. Αυτό είναι ιδιαίτερα χρήσιμο κατά τη σύλληψη και την ανίχνευση. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Επιστρέφει true εάν κλήθηκε η preventDefault() ενώ η τιμή του χαρακτηριστικού cancelable είναι true, και false διαφορετικά. |
| [getDetail](../../com.aspose.html.dom.svg.events/timeevent/detail/) Καθορίζει κάποιες λεπτομερείς πληροφορίες σχετικά με το Event, ανάλογα με τον τύπο του γεγονότος. Για αυτόν τον τύπο γεγονότος, υποδεικνύει τον αριθμό επαναλήψεων για την κίνηση. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Χρησιμοποιείται για να υποδείξει σε ποια φάση της ροής του συμβάντος αξιολογείται αυτή τη στιγμή. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Το χαρακτηριστικό isTrusted πρέπει να επιστρέφει την τιμή στην οποία αρχικοποιήθηκε. Όταν δημιουργείται ένα συμβάν, το χαρακτηριστικό πρέπει να αρχικοποιείται σε false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Χρησιμοποιείται για να υποδείξει το [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) στο οποίο το γεγονός διανεμήθηκε αρχικά. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Χρησιμοποιείται για να καθορίσει τον χρόνο (σε χιλιοστά του δευτερολέπτου σε σχέση με την εποχή) κατά τον οποίο δημιουργήθηκε το συμβάν. Λόγω του ότι ορισμένα συστήματα μπορεί να μην παρέχουν αυτήν την πληροφορία, η τιμή του timeStamp μπορεί να μην είναι διαθέσιμη για όλα τα συμβάντα. Όταν δεν είναι διαθέσιμη, θα επιστραφεί τιμή 0. Παραδείγματα χρόνου εποχής είναι ο χρόνος εκκίνησης του συστήματος ή 0:0:0 UTC 1η Ιανουαρίου 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Το όνομα του συμβάντος (χωρίς διάκριση πεζών-κεφαλαίων). Το όνομα πρέπει να είναι ένα όνομα XML. |
| [getView](../../com.aspose.html.dom.svg.events/timeevent/view/) Το χαρακτηριστικό view προσδιορίζει το AbstractView [DOM2VIEWS] από το οποίο δημιουργήθηκε το γεγονός. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Η μέθοδος [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/) χρησιμοποιείται για να αρχικοποιήσει την τιμή ενός [`Event`](../../com.aspose.html.dom.events/event/) που δημιουργείται μέσω της[`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/) διεπαφής. |
| [initTimeEvent](../../com.aspose.html.dom.svg.events/timeevent/inittimeevent/)(String, IAbstractView, long) | Η μέθοδος initTimeEvent χρησιμοποιείται για να αρχικοποιήσει την τιμή ενός TimeEvent που δημιουργείται μέσω της διεπαφής DocumentEvent. Αυτή η μέθοδος μπορεί να κληθεί μόνο πριν το TimeEvent διανεμηθεί μέσω της μεθόδου dispatchEvent, αν και μπορεί να κληθεί πολλές φορές κατά τη διάρκεια αυτής της φάσης εάν είναι απαραίτητο. Εάν κληθεί πολλές φορές, η τελική κλήση έχει προτεραιότητα. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Εάν ένα γεγονός είναι ακυρώσιμο, η μέθοδος [`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/) χρησιμοποιείται για να υποδείξει ότι το γεγονός θα ακυρωθεί, πράγμα που σημαίνει ότι οποιαδήποτε προεπιλεγμένη ενέργεια που συνήθως εκτελείται από την υλοποίηση ως αποτέλεσμα του γεγονότος δεν θα συμβεί. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Η κλήση αυτής της μεθόδου αποτρέπει το συμβάν από το να φτάσει σε οποιονδήποτε ακροατή συμβάντων που έχει καταχωρηθεί μετά τον τρέχοντα και όταν αποστέλλεται σε ένα δέντρο αποτρέπει επίσης το συμβάν από το να φτάσει σε άλλα αντικείμενα. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Η μέθοδος [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/) χρησιμοποιείται για την αποτροπή περαιτέρω διάδοσης ενός γεγονότος κατά τη ροή του γεγονότος. |

### Δείτε επίσης

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)
