---
title: "Κλάση TimeEvent"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.svg.events.TimeEvent class. Η διεπαφή TimeEvent παρέχει συγκεκριμένες συμφραζόμενες πληροφορίες που σχετίζονται με γεγονότα χρόνου. Οι διαφορετικοί τύποι γεγονότων που μπορούν να συμβούν είναι beginEvent, endEvent και repeatEvent."
type: docs

url: /el/java/com.aspose.html.dom.svg.events/timeevent/
---
## TimeEvent class

Η διεπαφή TimeEvent παρέχει συγκεκριμένες συμφραζόμενες πληροφορίες που σχετίζονται με τα χρονικά γεγονότα. Οι διαφορετικοί τύποι γεγονότων που μπορούν να συμβούν είναι: beginEvent, endEvent και repeatEvent.

```java
public class TimeEvent : Event
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Χρησιμοποιείται για να υποδείξει εάν ένα συμβάν είναι συμβάν φούσκωσης. Αν το συμβάν μπορεί να φουσκώσει, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Χρησιμοποιείται για να υποδείξει εάν ένα συμβάν μπορεί να αποτραπεί η προεπιλεγμένη του ενέργεια. Αν η προεπιλεγμένη ενέργεια μπορεί να αποτραπεί, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Χρησιμοποιείται για να υποδείξει το [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) του οποίου οι [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/)s επεξεργάζονται επί του παρόντος. Αυτό είναι ιδιαίτερα χρήσιμο κατά τη διάρκεια του capture και του bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Επιστρέφει true εάν κλήθηκε η preventDefault() ενώ η τιμή του χαρακτηριστικού cancelable είναι true, και false διαφορετικά. |
| [getDetail](../../com.aspose.html.dom.svg.events/timeevent/detail/) Καθορίζει ορισμένες λεπτομερείς πληροφορίες σχετικά με το Event, ανάλογα με τον τύπο του γεγονότος. Για αυτόν τον τύπο γεγονότος, υποδεικνύει τον αριθμό επαναλήψεων για το animation. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Χρησιμοποιείται για να υποδείξει ποια φάση της ροής του συμβάντος αξιολογείται αυτή τη στιγμή. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Το χαρακτηριστικό isTrusted πρέπει να επιστρέφει την τιμή με την οποία αρχικοποιήθηκε. Όταν δημιουργείται ένα συμβάν, το χαρακτηριστικό πρέπει να αρχικοποιηθεί σε false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Χρησιμοποιείται για να υποδείξει το [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) στο οποίο το γεγονός αποστέλλεται αρχικά. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Χρησιμοποιείται για να καθορίσει το χρόνο (σε χιλιοστά του δευτερολέπτου σε σχέση με την εποχή) κατά τον οποίο δημιουργήθηκε το συμβάν. Λόγω του ότι ορισμένα συστήματα ενδέχεται να μην παρέχουν αυτήν την πληροφορία, η τιμή του timeStamp μπορεί να μην είναι διαθέσιμη για όλα τα συμβάντα. Όταν δεν είναι διαθέσιμη, θα επιστραφεί τιμή 0. Παραδείγματα χρόνου εποχής είναι η ώρα εκκίνησης του συστήματος ή 0:0:0 UTC 1η Ιανουαρίου 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Το όνομα του συμβάντος (χωρίς διάκριση πεζών-κεφαλαίων). Το όνομα πρέπει να είναι ένα όνομα XML. |
| [getView](../../com.aspose.html.dom.svg.events/timeevent/view/) Το χαρακτηριστικό view προσδιορίζει το AbstractView [DOM2VIEWS] από το οποίο δημιουργήθηκε το γεγονός. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Η μέθοδος [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/) χρησιμοποιείται για την αρχικοποίηση της τιμής ενός [`Event`](../../com.aspose.html.dom.events/event/) που δημιουργείται μέσω της διεπαφής[`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/). |
| [initTimeEvent](../../com.aspose.html.dom.svg.events/timeevent/inittimeevent/)(String, IAbstractView, long) | Η μέθοδος initTimeEvent χρησιμοποιείται για την αρχικοποίηση της τιμής ενός TimeEvent που δημιουργείται μέσω της διεπαφής DocumentEvent. Αυτή η μέθοδος μπορεί να κληθεί μόνο πριν το TimeEvent αποσταλεί μέσω της μεθόδου dispatchEvent, αν και μπορεί να κληθεί πολλαπλές φορές κατά τη διάρκεια αυτής της φάσης εάν είναι απαραίτητο. Εάν κληθεί πολλαπλές φορές, η τελική κλήση έχει προτεραιότητα. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Εάν ένα γεγονός είναι ακυρώσιμο, η μέθοδος [`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/) χρησιμοποιείται για να υποδείξει ότι το γεγονός πρέπει να ακυρωθεί, πράγμα που σημαίνει ότι καμία προεπιλεγμένη ενέργεια που συνήθως εκτελεί η υλοποίηση ως αποτέλεσμα του γεγονότος δεν θα συμβεί. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Η κλήση αυτής της μεθόδου αποτρέπει το συμβάν από το να φτάσει σε οποιονδήποτε ακροατή συμβάντων που έχουν εγγραφεί μετά τον τρέχοντα και όταν διανέμεται σε δέντρο, αποτρέπει επίσης το συμβάν από το να φτάσει σε άλλα αντικείμενα. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Η μέθοδος [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/) χρησιμοποιείται για την αποτροπή περαιτέρω διάδοσης ενός γεγονότος κατά τη ροή του γεγονότος. |

### Δείτε επίσης

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)
