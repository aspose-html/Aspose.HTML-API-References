---
title: "ErrorEvent Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.events.ErrorEvent κλάση. Το ErrorEvent παρέχει πληροφορίες περιβάλλοντος σχετικά με σφάλματα που συνέβησαν κατά την εκτέλεση"
type: docs

url: /el/java/com.aspose.html.dom.events/errorevent/
---
## ErrorEvent class

Το ErrorEvent παρέχει συμφραζόμενη πληροφορία σχετικά με σφάλματα που συνέβησαν κατά την εκτέλεση.

```java
public class ErrorEvent : Event
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [ErrorEvent](errorevent/#constructor_1)(Exception) | Δημιουργεί μια νέα παρουσία της κλάσης `ErrorEvent`. |
| [ErrorEvent](errorevent/#constructor)(IDictionary&lt;String, object&gt;) |  |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Χρησιμοποιείται για να υποδείξει αν ένα συμβάν είναι συμβάν ανάδυσης. Εάν το συμβάν μπορεί να αναδυθεί, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Χρησιμοποιείται για να υποδείξει αν ένα συμβάν μπορεί να αποτρέψει την προεπιλεγμένη του ενέργεια. Εάν η προεπιλεγμένη ενέργεια μπορεί να αποτραπεί, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [getColNo](../../com.aspose.html.dom.events/errorevent/colno/) Το χαρακτηριστικό colno πρέπει να επιστρέφει την τιμή με την οποία αρχικοποιήθηκε. Όταν το αντικείμενο δημιουργείται, αυτό το χαρακτηριστικό πρέπει να αρχικοποιηθεί στο μηδέν. Αντιπροσωπεύει τον αριθμό στήλης όπου συνέβη το σφάλμα στο script. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Χρησιμοποιείται για να υποδείξει το [`IEventTarget`](../ieventtarget/) του οποίου οι [`IEventListener`](../ieventlistener/) επεξεργάζονται αυτή τη στιγμή. Αυτό είναι ιδιαίτερα χρήσιμο κατά τη σύλληψη και την ανάδυση. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Επιστρέφει true εάν κλήθηκε η preventDefault() ενώ η τιμή του χαρακτηριστικού cancelable είναι true, και false διαφορετικά. |
| [getError](../../com.aspose.html.dom.events/errorevent/error/) Το χαρακτηριστικό error πρέπει να επιστρέφει την τιμή με την οποία αρχικοποιήθηκε. Όταν το αντικείμενο δημιουργείται, αυτό το χαρακτηριστικό πρέπει να αρχικοποιηθεί σε null. Όπου είναι κατάλληλο, ορίζεται στο αντικείμενο που αντιπροσωπεύει το σφάλμα (π.χ. το αντικείμενο εξαίρεσης στην περίπτωση μη πιασμένης εξαίρεσης DOM). |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Χρησιμοποιείται για να υποδείξει σε ποια φάση της ροής του συμβάντος αξιολογείται αυτή τη στιγμή. |
| [getFileName](../../com.aspose.html.dom.events/errorevent/filename/) Το χαρακτηριστικό filename πρέπει να επιστρέφει την τιμή με την οποία αρχικοποιήθηκε. Όταν το αντικείμενο δημιουργείται, αυτό το χαρακτηριστικό πρέπει να αρχικοποιηθεί σε κενή συμβολοσειρά. Αντιπροσωπεύει το απόλυτο URL του script στο οποίο το σφάλμα εμφανίστηκε αρχικά. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Το χαρακτηριστικό isTrusted πρέπει να επιστρέφει την τιμή στην οποία αρχικοποιήθηκε. Όταν δημιουργείται ένα συμβάν, το χαρακτηριστικό πρέπει να αρχικοποιείται σε false. |
| [getLineNo](../../com.aspose.html.dom.events/errorevent/lineno/) Το χαρακτηριστικό lineno πρέπει να επιστρέφει την τιμή στην οποία αρχικοποιήθηκε. Όταν το αντικείμενο δημιουργείται, αυτό το χαρακτηριστικό πρέπει να αρχικοποιείται στο μηδέν. Αντιπροσωπεύει τον αριθμό γραμμής όπου συνέβη το σφάλμα στο script. |
| [getMessage](../../com.aspose.html.dom.events/errorevent/message/) Το χαρακτηριστικό message πρέπει να επιστρέφει την τιμή στην οποία αρχικοποιήθηκε. Όταν το αντικείμενο δημιουργείται, αυτό το χαρακτηριστικό πρέπει να αρχικοποιείται στην κενή συμβολοσειρά. Αντιπροσωπεύει το μήνυμα σφάλματος. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Χρησιμοποιείται για να υποδείξει το [`IEventTarget`](../ieventtarget/) στο οποίο το συμβάν αποστάλθηκε αρχικά. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Χρησιμοποιείται για να καθορίσει τον χρόνο (σε χιλιοστά του δευτερολέπτου σε σχέση με την εποχή) κατά τον οποίο δημιουργήθηκε το συμβάν. Λόγω του ότι ορισμένα συστήματα μπορεί να μην παρέχουν αυτήν την πληροφορία, η τιμή του timeStamp μπορεί να μην είναι διαθέσιμη για όλα τα συμβάντα. Όταν δεν είναι διαθέσιμη, θα επιστραφεί τιμή 0. Παραδείγματα χρόνου εποχής είναι ο χρόνος εκκίνησης του συστήματος ή 0:0:0 UTC 1η Ιανουαρίου 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Το όνομα του συμβάντος (χωρίς διάκριση πεζών-κεφαλαίων). Το όνομα πρέπει να είναι ένα όνομα XML. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Η μέθοδος [`InitEvent`](../event/initevent/) χρησιμοποιείται για να αρχικοποιήσει την τιμή ενός [`Event`](../event/) που δημιουργείται μέσω της διεπαφής [`IDocumentEvent`](../idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Εάν ένα συμβάν είναι ακυρώσιμο, η μέθοδος [`PreventDefault`](../event/preventdefault/) χρησιμοποιείται για να υποδείξει ότι το συμβάν πρέπει να ακυρωθεί, πράγμα που σημαίνει ότι οποιαδήποτε προεπιλεγμένη ενέργεια που κανονικά θα εκτελείτο από την υλοποίηση ως αποτέλεσμα του συμβάντος δεν θα συμβεί. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Η κλήση αυτής της μεθόδου αποτρέπει το συμβάν από το να φτάσει σε οποιονδήποτε ακροατή συμβάντων που έχει καταχωρηθεί μετά τον τρέχοντα και όταν αποστέλλεται σε ένα δέντρο αποτρέπει επίσης το συμβάν από το να φτάσει σε άλλα αντικείμενα. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Η μέθοδος [`StopPropagation`](../event/stoppropagation/) χρησιμοποιείται για να αποτρέψει περαιτέρω διάδοση ενός συμβάντος κατά τη ροή του συμβάντος. |

### Δείτε επίσης

* class [Event](../event/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
