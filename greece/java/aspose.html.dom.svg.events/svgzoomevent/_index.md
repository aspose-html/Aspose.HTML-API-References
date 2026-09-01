---
title: "Κλάση SVGZoomEvent"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Κλάση com.aspose.html.dom.svg.events.SVGZoomEvent. Το γεγονός ζουμ συμβαίνει όταν ο χρήστης εκκινεί μια ενέργεια που προκαλεί την επανακλιμάκωση της τρέχουσας προβολής του τμήματος του εγγράφου SVG. Οι χειριστές γεγονότων αναγνωρίζονται μόνο σε στοιχεία svg."
type: docs

url: /el/java/com.aspose.html.dom.svg.events/svgzoomevent/
---
## SVGZoomEvent class

Το συμβάν ζουμ εμφανίζεται όταν ο χρήστης εκκινεί μια ενέργεια που προκαλεί την επανακλιμάκωση της τρέχουσας προβολής του τμήματος του εγγράφου SVG. Οι χειριστές συμβάντων αναγνωρίζονται μόνο στα στοιχεία ‘svg’.

```java
public class SVGZoomEvent : Event
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Χρησιμοποιείται για να υποδείξει αν ένα συμβάν είναι συμβάν ανάδυσης. Εάν το συμβάν μπορεί να αναδυθεί, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Χρησιμοποιείται για να υποδείξει αν ένα συμβάν μπορεί να αποτρέψει την προεπιλεγμένη του ενέργεια. Εάν η προεπιλεγμένη ενέργεια μπορεί να αποτραπεί, η τιμή είναι true, αλλιώς η τιμή είναι false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Χρησιμοποιείται για να υποδείξει το [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) του οποίου οι [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/)s επεξεργάζονται αυτή τη στιγμή. Αυτό είναι ιδιαίτερα χρήσιμο κατά τη σύλληψη και την ανίχνευση. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Επιστρέφει true εάν κλήθηκε η preventDefault() ενώ η τιμή του χαρακτηριστικού cancelable είναι true, και false διαφορετικά. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Χρησιμοποιείται για να υποδείξει σε ποια φάση της ροής του συμβάντος αξιολογείται αυτή τη στιγμή. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Το χαρακτηριστικό isTrusted πρέπει να επιστρέφει την τιμή στην οποία αρχικοποιήθηκε. Όταν δημιουργείται ένα συμβάν, το χαρακτηριστικό πρέπει να αρχικοποιείται σε false. |
| [getNewScale](../../com.aspose.html.dom.svg.events/svgzoomevent/newscale/) Ο συντελεστής κλίμακας που θα ισχύει μετά την επεξεργασία της λειτουργίας ζουμ. |
| [getNewTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/newtranslate/) Οι τιμές μετάφρασης που θα ισχύσουν μετά την επεξεργασία της λειτουργίας ζουμ. Το αντικείμενο SVGPoint είναι μόνο για ανάγνωση. |
| [getPreviousScale](../../com.aspose.html.dom.svg.events/svgzoomevent/previousscale/) Ο συντελεστής κλίμακας από προηγούμενες λειτουργίες ζουμ που ήταν σε ισχύ πριν συμβεί η τρέχουσα λειτουργία ζουμ. |
| [getPreviousTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/previoustranslate/) Οι τιμές μετάφρασης από προηγούμενες λειτουργίες ζουμ που ήταν σε ισχύ πριν συμβεί η τρέχουσα λειτουργία ζουμ. Το αντικείμενο SVGPoint είναι μόνο για ανάγνωση. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Χρησιμοποιείται για να υποδείξει το [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) στο οποίο το γεγονός διανεμήθηκε αρχικά. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Χρησιμοποιείται για να καθορίσει τον χρόνο (σε χιλιοστά του δευτερολέπτου σε σχέση με την εποχή) κατά τον οποίο δημιουργήθηκε το συμβάν. Λόγω του ότι ορισμένα συστήματα μπορεί να μην παρέχουν αυτήν την πληροφορία, η τιμή του timeStamp μπορεί να μην είναι διαθέσιμη για όλα τα συμβάντα. Όταν δεν είναι διαθέσιμη, θα επιστραφεί τιμή 0. Παραδείγματα χρόνου εποχής είναι ο χρόνος εκκίνησης του συστήματος ή 0:0:0 UTC 1η Ιανουαρίου 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Το όνομα του συμβάντος (χωρίς διάκριση πεζών-κεφαλαίων). Το όνομα πρέπει να είναι ένα όνομα XML. |
| [getZoomRectScreen](../../com.aspose.html.dom.svg.events/svgzoomevent/zoomrectscreen/) Το καθορισμένο ορθογώνιο ζουμ σε μονάδες οθόνης. Το αντικείμενο SVGRect είναι μόνο για ανάγνωση. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Η μέθοδος [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/) χρησιμοποιείται για να αρχικοποιήσει την τιμή ενός [`Event`](../../com.aspose.html.dom.events/event/) που δημιουργείται μέσω της[`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/) διεπαφής. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Εάν ένα γεγονός είναι ακυρώσιμο, η μέθοδος [`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/) χρησιμοποιείται για να υποδείξει ότι το γεγονός θα ακυρωθεί, πράγμα που σημαίνει ότι οποιαδήποτε προεπιλεγμένη ενέργεια που συνήθως εκτελείται από την υλοποίηση ως αποτέλεσμα του γεγονότος δεν θα συμβεί. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Η κλήση αυτής της μεθόδου αποτρέπει το συμβάν από το να φτάσει σε οποιονδήποτε ακροατή συμβάντων που έχει καταχωρηθεί μετά τον τρέχοντα και όταν αποστέλλεται σε ένα δέντρο αποτρέπει επίσης το συμβάν από το να φτάσει σε άλλα αντικείμενα. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Η μέθοδος [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/) χρησιμοποιείται για την αποτροπή περαιτέρω διάδοσης ενός γεγονότος κατά τη ροή του γεγονότος. |

### Δείτε επίσης

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)
