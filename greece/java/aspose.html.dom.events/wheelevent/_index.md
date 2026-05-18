---
title: "Κλάση WheelEvent"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Κλάση com.aspose.html.dom.events.WheelEvent. Η διεπαφή WheelEvent παρέχει συγκεκριμένες συμφραζόμενες πληροφορίες που σχετίζονται με συμβάντα τροχού. Για να δημιουργήσετε μια παρουσία της διεπαφής WheelEvent, χρησιμοποιήστε τον κατασκευαστή WheelEvent περνώντας ένα προαιρετικό λεξικό WheelEventInit."
type: docs

url: /el/java/com.aspose.html.dom.events/wheelevent/
---
## WheelEvent class

Το WheelEvent interface παρέχει συγκεκριμένες συμφραζόμενες πληροφορίες που σχετίζονται με wheel events. Για να δημιουργήσετε μια παρουσία του WheelEvent interface, χρησιμοποιήστε τον κατασκευαστή WheelEvent, περνώντας ένα προαιρετικό λεξικό WheelEventInit.

```java
public class WheelEvent : MouseEvent
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [WheelEvent](wheelevent/#constructor)(String) | Αρχικοποιεί μια νέα παρουσία της κλάσης `WheelEvent`. |
| [WheelEvent](wheelevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

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
| [getDeltaMode](../../com.aspose.html.dom.events/wheelevent/deltamode/) Το χαρακτηριστικό deltaMode περιέχει ένδειξη των μονάδων μέτρησης για τις τιμές delta. Η προεπιλεγμένη τιμή είναι DOM_DELTA_PIXEL (pixel). |
| [getDeltaX](../../com.aspose.html.dom.events/wheelevent/deltax/) Σε πελάτες όπου η προεπιλεγμένη ενέργεια του συμβάντος τροχού είναι η κύλιση, η τιμή ΠΡΕΠΕΙ να είναι η μέτρηση κατά τον άξονα x (σε pixel, γραμμές ή σελίδες) που θα κυλιστεί εάν το συμβάν δεν ακυρωθεί. Διαφορετικά, αυτή είναι μια μέτρηση ειδική για την υλοποίηση (σε pixel, γραμμές ή σελίδες) της κίνησης μιας συσκευής τροχού γύρω από τον άξονα x. |
| [getDeltaY](../../com.aspose.html.dom.events/wheelevent/deltay/) Σε πελάτες όπου η προεπιλεγμένη ενέργεια του συμβάντος τροχού είναι η κύλιση, η τιμή ΠΡΕΠΕΙ να είναι η μέτρηση κατά τον άξονα y (σε pixel, γραμμές ή σελίδες) που θα κυλιστεί εάν το συμβάν δεν ακυρωθεί. Διαφορετικά, αυτή είναι μια μέτρηση ειδική για την υλοποίηση (σε pixel, γραμμές ή σελίδες) της κίνησης μιας συσκευής τροχού γύρω από τον άξονα y. |
| [getDeltaZ](../../com.aspose.html.dom.events/wheelevent/deltaz/) Σε πελάτες όπου η προεπιλεγμένη ενέργεια του συμβάντος τροχού είναι η κύλιση, η τιμή ΠΡΕΠΕΙ να είναι η μέτρηση κατά τον άξονα z (σε pixel, γραμμές ή σελίδες) που θα κυλιστεί εάν το συμβάν δεν ακυρωθεί. Διαφορετικά, αυτή είναι μια μέτρηση ειδική για την υλοποίηση (σε pixel, γραμμές ή σελίδες) της κίνησης μιας συσκευής τροχού γύρω από τον άξονα z. |
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

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [DOM_DELTA_LINE](../../com.aspose.html.dom.events/wheelevent/dom_delta_line/) | Οι μονάδες μέτρησης για το delta ΠΡΕΠΕΙ να είναι μεμονωμένες γραμμές κειμένου. Αυτό ισχύει για πολλά στοιχεία φόρμας. |
| const [DOM_DELTA_PAGE](../../com.aspose.html.dom.events/wheelevent/dom_delta_page/) | Οι μονάδες μέτρησης για το delta ΠΡΕΠΕΙ να είναι σελίδες, είτε ορισμένες ως μία ενιαία οθόνη είτε ως διαχωρισμένη σελίδα. |
| const [DOM_DELTA_PIXEL](../../com.aspose.html.dom.events/wheelevent/dom_delta_pixel/) | Οι μονάδες μέτρησης για το delta ΠΡΕΠΕΙ να είναι pixel. Αυτή είναι η πιο συνηθισμένη περίπτωση στις περισσότερες ρυθμίσεις λειτουργικού συστήματος και υλοποίησης. |

### Δείτε επίσης

* class [MouseEvent](../mouseevent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
