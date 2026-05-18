---
title: "Κλάση MouseEvent"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.events.MouseEvent class. Η διεπαφή MouseEvent παρέχει συγκεκριμένες πληροφορίες περιβάλλοντος που σχετίζονται με γεγονότα ποντικιού"
type: docs

url: /el/java/com.aspose.html.dom.events/mouseevent/
---
## MouseEvent class

Το MouseEvent interface παρέχει συγκεκριμένες συμφραζόμενες πληροφορίες που σχετίζονται με Mouse events.

```java
public class MouseEvent : UIEvent
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MouseEvent](mouseevent/#constructor)(String) | Αρχικοποιεί μια νέα παρουσία της κλάσης `MouseEvent`. |
| [MouseEvent](mouseevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/mouseevent/altkey/) Αναφερθείτε στο χαρακτηριστικό altKey. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Χρησιμοποιείται για να υποδείξει εάν ένα συμβάν είναι συμβάν φούσκωσης. Αν το συμβάν μπορεί να φουσκώσει, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [getButton](../../com.aspose.html.dom.events/mouseevent/button/) Κατά τη διάρκεια των γεγονότων ποντικιού που προκαλούνται από την πίεση ή την απελευθέρωση ενός κουμπιού ποντικιού, το button ΠΡΕΠΕΙ να χρησιμοποιείται για να υποδεικνύει ποιο κουμπί της συσκευής δείκτη άλλαξε κατάσταση. |
| [getButtons](../../com.aspose.html.dom.events/mouseevent/buttons/) Κατά τη διάρκεια οποιωνδήποτε γεγονότων ποντικιού, το buttons ΠΡΕΠΕΙ να χρησιμοποιείται για να υποδεικνύει ποιος συνδυασμός κουμπιών ποντικιού είναι αυτή τη στιγμή πατημένος, εκφρασμένος ως bitmask. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Χρησιμοποιείται για να υποδείξει εάν ένα συμβάν μπορεί να αποτραπεί η προεπιλεγμένη του ενέργεια. Αν η προεπιλεγμένη ενέργεια μπορεί να αποτραπεί, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [getClientX](../../com.aspose.html.dom.events/mouseevent/clientx/) Η οριζόντια συντεταγμένη στην οποία συνέβη το γεγονός σε σχέση με το παράθυρο προβολής που σχετίζεται με το γεγονός. |
| [getClientY](../../com.aspose.html.dom.events/mouseevent/clienty/) Η κάθετη συντεταγμένη στην οποία συνέβη το γεγονός σε σχέση με το παράθυρο προβολής που σχετίζεται με το γεγονός. |
| [getCtrlKey](../../com.aspose.html.dom.events/mouseevent/ctrlkey/) Αναφερθείτε στο χαρακτηριστικό ctrlKey. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Χρησιμοποιείται για να υποδείξει το [`IEventTarget`](../ieventtarget/) του οποίου τα [`IEventListener`](../ieventlistener/) επεξεργάζονται αυτή τη στιγμή. Αυτό είναι ιδιαίτερα χρήσιμο κατά τη διάρκεια του capture και του bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Επιστρέφει true εάν κλήθηκε η preventDefault() ενώ η τιμή του χαρακτηριστικού cancelable είναι true, και false διαφορετικά. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Καθορίζει κάποιες λεπτομερείς πληροφορίες για το Event, ανάλογα με τον τύπο του συμβάντος. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Χρησιμοποιείται για να υποδείξει ποια φάση της ροής του συμβάντος αξιολογείται αυτή τη στιγμή. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Το χαρακτηριστικό isTrusted πρέπει να επιστρέφει την τιμή με την οποία αρχικοποιήθηκε. Όταν δημιουργείται ένα συμβάν, το χαρακτηριστικό πρέπει να αρχικοποιηθεί σε false. |
| [getMetaKey](../../com.aspose.html.dom.events/mouseevent/metakey/) Αναφερθείτε στο χαρακτηριστικό metaKey. |
| [getRelatedTarget](../../com.aspose.html.dom.events/mouseevent/relatedtarget/) Χρησιμοποιείται για την ταυτοποίηση ενός δευτερεύοντος EventTarget που σχετίζεται με ένα UI συμβάν, ανάλογα με τον τύπο του συμβάντος. |
| [getScreenX](../../com.aspose.html.dom.events/mouseevent/screenx/) Η οριζόντια συντεταγμένη στην οποία συνέβη το συμβάν σε σχέση με το αρχικό σημείο του συστήματος συντεταγμένων της οθόνης. |
| [getScreenY](../../com.aspose.html.dom.events/mouseevent/screeny/) Η κάθετη συντεταγμένη στην οποία συνέβη το συμβάν σε σχέση με το αρχικό σημείο του συστήματος συντεταγμένων της οθόνης. |
| [getShiftKey](../../com.aspose.html.dom.events/mouseevent/shiftkey/) Αναφέρεται στο χαρακτηριστικό shiftKey. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Χρησιμοποιείται για να υποδείξει το [`IEventTarget`](../ieventtarget/) στο οποίο το συμβάν διανέμεται αρχικά. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Χρησιμοποιείται για να καθορίσει το χρόνο (σε χιλιοστά του δευτερολέπτου σε σχέση με την εποχή) κατά τον οποίο δημιουργήθηκε το συμβάν. Λόγω του ότι ορισμένα συστήματα ενδέχεται να μην παρέχουν αυτήν την πληροφορία, η τιμή του timeStamp μπορεί να μην είναι διαθέσιμη για όλα τα συμβάντα. Όταν δεν είναι διαθέσιμη, θα επιστραφεί τιμή 0. Παραδείγματα χρόνου εποχής είναι η ώρα εκκίνησης του συστήματος ή 0:0:0 UTC 1η Ιανουαρίου 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Το όνομα του συμβάντος (χωρίς διάκριση πεζών-κεφαλαίων). Το όνομα πρέπει να είναι ένα όνομα XML. |
| [getView](../../com.aspose.html.dom.events/uievent/view/) Το χαρακτηριστικό view προσδιορίζει το Window από το οποίο δημιουργήθηκε το συμβάν. Η μη αρχικοποιημένη τιμή αυτού του χαρακτηριστικού ΠΡΕΠΕΙ να είναι null. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Η μέθοδος [`InitEvent`](../event/initevent/) χρησιμοποιείται για να αρχικοποιήσει την τιμή ενός [`Event`](../event/) που δημιουργείται μέσω της διεπαφής [`IDocumentEvent`](../idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Εάν ένα συμβάν είναι ακυρώσιμο, η μέθοδος [`PreventDefault`](../event/preventdefault/) χρησιμοποιείται για να υποδείξει ότι το συμβάν πρέπει να ακυρωθεί, πράγμα που σημαίνει ότι οποιαδήποτε προεπιλεγμένη ενέργεια που κανονικά θα εκτελούταν από την υλοποίηση ως αποτέλεσμα του συμβάντος δεν θα συμβεί. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Η κλήση αυτής της μεθόδου αποτρέπει το συμβάν από το να φτάσει σε οποιονδήποτε ακροατή συμβάντων που έχουν εγγραφεί μετά τον τρέχοντα και όταν διανέμεται σε δέντρο, αποτρέπει επίσης το συμβάν από το να φτάσει σε άλλα αντικείμενα. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Η μέθοδος [`StopPropagation`](../event/stoppropagation/) χρησιμοποιείται για να αποτρέψει περαιτέρω διάδοση ενός συμβάντος κατά τη ροή του συμβάντος. |

### Δείτε επίσης

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
