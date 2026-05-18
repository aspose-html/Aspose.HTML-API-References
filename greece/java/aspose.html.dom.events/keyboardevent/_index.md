---
title: "KeyboardEvent Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.events.KeyboardEvent class. Η διεπαφή KeyboardEvent παρέχει συγκεκριμένες πληροφορίες περιβάλλοντος που σχετίζονται με συσκευές πληκτρολογίου. Κάθε συμβάν πληκτρολογίου αναφέρεται σε ένα πλήκτρο χρησιμοποιώντας μια τιμή. Τα συμβάντα πληκτρολογίου κατευθύνονται συνήθως προς το στοιχείο που έχει την εστίαση."
type: docs

url: /el/java/com.aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

Το KeyboardEvent interface παρέχει συγκεκριμένες συμφραζόμενες πληροφορίες που σχετίζονται με συσκευές πληκτρολογίου. Κάθε γεγονός πληκτρολογίου αναφέρεται σε ένα πλήκτρο χρησιμοποιώντας μια τιμή. Τα Keyboard events συνήθως κατευθύνονται προς το στοιχείο που έχει την εστίαση.

```java
public class KeyboardEvent : UIEvent
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(String) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `KeyboardEvent`. |
| [KeyboardEvent](keyboardevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/keyboardevent/altkey/) true εάν ο τροποποιητής πλήκτρου Alt (εναλλακτικό) (ή \"Option\") ήταν ενεργός. Η μη αρχικοποιημένη τιμή αυτού του χαρακτηριστικού ΠΡΕΠΕΙ να είναι false. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Χρησιμοποιείται για να υποδείξει εάν ένα συμβάν είναι συμβάν φούσκωσης. Αν το συμβάν μπορεί να φουσκώσει, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Χρησιμοποιείται για να υποδείξει εάν ένα συμβάν μπορεί να αποτραπεί η προεπιλεγμένη του ενέργεια. Αν η προεπιλεγμένη ενέργεια μπορεί να αποτραπεί, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [getCode](../../com.aspose.html.dom.events/keyboardevent/code/) Ο κώδικας περιέχει μια συμβολοσειρά που αναγνωρίζει το φυσικό πλήκτρο που πατιέται. Η τιμή δεν επηρεάζεται από τη τρέχουσα διάταξη πληκτρολογίου ή την κατάσταση των τροποποιητών, έτσι ένα συγκεκριμένο πλήκτρο θα επιστρέφει πάντα την ίδια τιμή. |
| [getCtrlKey](../../com.aspose.html.dom.events/keyboardevent/ctrlkey/) true εάν ο τροποποιητής πλήκτρου Control (control) ήταν ενεργός. Η μη αρχικοποιημένη τιμή αυτού του χαρακτηριστικού ΠΡΕΠΕΙ να είναι false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Χρησιμοποιείται για να υποδείξει το [`IEventTarget`](../ieventtarget/) του οποίου τα [`IEventListener`](../ieventlistener/) επεξεργάζονται αυτή τη στιγμή. Αυτό είναι ιδιαίτερα χρήσιμο κατά τη διάρκεια του capture και του bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Επιστρέφει true εάν κλήθηκε η preventDefault() ενώ η τιμή του χαρακτηριστικού cancelable είναι true, και false διαφορετικά. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Καθορίζει κάποιες λεπτομερείς πληροφορίες για το Event, ανάλογα με τον τύπο του συμβάντος. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Χρησιμοποιείται για να υποδείξει ποια φάση της ροής του συμβάντος αξιολογείται αυτή τη στιγμή. |
| [getIsComposing](../../com.aspose.html.dom.events/keyboardevent/iscomposing/) true εάν το συμβάν πλήκτρου συμβαίνει ως μέρος μιας συνεδρίας σύνθεσης, δηλαδή μετά από συμβάν compositionstart και πριν από το αντίστοιχο συμβάν compositionend. Η μη αρχικοποιημένη τιμή αυτού του χαρακτηριστικού ΠΡΕΠΕΙ να είναι false. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Το χαρακτηριστικό isTrusted πρέπει να επιστρέφει την τιμή με την οποία αρχικοποιήθηκε. Όταν δημιουργείται ένα συμβάν, το χαρακτηριστικό πρέπει να αρχικοποιηθεί σε false. |
| [getKey](../../com.aspose.html.dom.events/keyboardevent/key/) Το κλειδί περιέχει την τιμή του πλήκτρου που πατήθηκε. Εάν η τιμή έχει εκτυπώσιμη αναπαράσταση, ΠΡΕΠΕΙ να είναι μια μη κενή συμβολοσειρά Unicode χαρακτήρα, σύμφωνη με τον αλγόριθμο για τον καθορισμό της τιμής κλειδιού που ορίζεται σε αυτήν την προδιαγραφή. Εάν η τιμή είναι ένα πλήκτρο ελέγχου που δεν έχει εκτυπώσιμη αναπαράσταση, ΠΡΕΠΕΙ να είναι μία από τις τιμές κλειδιού που ορίζονται στο σύνολο τιμών κλειδιού, όπως καθορίζεται από τον αλγόριθμο για τον καθορισμό της τιμής κλειδιού. Οι υλοποιήσεις που δεν μπορούν να αναγνωρίσουν ένα κλειδί ΠΡΕΠΕΙ να χρησιμοποιούν την τιμή κλειδιού Unidentified. |
| [getLocation](../../com.aspose.html.dom.events/keyboardevent/location/) Το χαρακτηριστικό location περιέχει ένδειξη της λογικής θέσης του πλήκτρου στη συσκευή. |
| [getMetaKey](../../com.aspose.html.dom.events/keyboardevent/metakey/) true εάν ο τροποποιητής πλήκτρου meta (Meta) ήταν ενεργός. |
| [getRepeat](../../com.aspose.html.dom.events/keyboardevent/repeat/) true εάν το πλήκτρο έχει πατηθεί με διαρκή μορφή. Η διατήρηση ενός πλήκτρου ΠΡΕΠΕΙ να έχει ως αποτέλεσμα την επανάληψη των συμβάντων keydown, beforeinput, input με αυτή τη σειρά, με ρυθμό που καθορίζεται από τη διαμόρφωση του συστήματος. Για κινητές συσκευές που έχουν συμπεριφορά παρατεταμένου πατήματος πλήκτρου, το πρώτο συμβάν πλήκτρου με τιμή repeat true ΠΡΕΠΕΙ να χρησιμεύει ως ένδειξη παρατεταμένου πατήματος πλήκτρου. Το χρονικό διάστημα που ΠΡΕΠΕΙ να παραμείνει πατημένο το πλήκτρο για να αρχίσει η επανάληψη εξαρτάται από τη διαμόρφωση. |
| [getShiftKey](../../com.aspose.html.dom.events/keyboardevent/shiftkey/) true εάν ο τροποποιητής πλήκτρου shift (Shift) ήταν ενεργός. |
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
| const [DOM_KEY_LOCATION_LEFT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_left/) | Το κλειδί που ενεργοποιήθηκε προέρχεται από την αριστερή θέση του πλήκτρου (όταν υπάρχει περισσότερη από μία πιθανή θέση για αυτό το πλήκτρο). |
| const [DOM_KEY_LOCATION_NUMPAD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | Η ενεργοποίηση του πλήκτρου προέρχεται από το αριθμητικό πληκτρολόγιο ή από ένα εικονικό πλήκτρο που αντιστοιχεί στο αριθμητικό πληκτρολόγιο (όταν υπάρχει περισσότερη από μία πιθανή θέση για αυτό το πλήκτρο). Σημειώστε ότι το πλήκτρο NumLock πρέπει πάντα να κωδικοποιείται με θέση DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_right/) | Η ενεργοποίηση του πλήκτρου προέρχεται από τη δεξιά θέση του πλήκτρου (όταν υπάρχει περισσότερη από μία πιθανή θέση για αυτό το πλήκτρο). |
| const [DOM_KEY_LOCATION_STANDARD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | Η ενεργοποίηση του πλήκτρου ΔΕΝ ΠΡΕΠΕΙ να διακρίνεται ως η αριστερή ή η δεξιά έκδοση του πλήκτρου, και (εκτός του πλήκτρου NumLock) δεν προέρχεται από το αριθμητικό πληκτρολόγιο (ή δεν προέρχεται από ένα εικονικό πλήκτρο που αντιστοιχεί στο αριθμητικό πληκτρολόγιο). |

### Δείτε επίσης

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
