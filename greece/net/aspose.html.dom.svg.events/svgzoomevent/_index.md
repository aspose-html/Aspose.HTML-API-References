---
title: Class SVGZoomEvent
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Dom.Svg.Events.SVGZoomEvent τάξη. Το συμβάν ζουμ συμβαίνει όταν ο χρήστης εκκινεί μια ενέργεια που προκαλεί την αλλαγή κλίμακας της τρέχουσας προβολής του τμήματος εγγράφου SVG. Οι χειριστές συμβάντων αναγνωρίζονται μόνο σε στοιχεία svg.
type: docs
weight: 1330
url: /el/net/aspose.html.dom.svg.events/svgzoomevent/
---
## SVGZoomEvent class

Το συμβάν ζουμ συμβαίνει όταν ο χρήστης εκκινεί μια ενέργεια που προκαλεί την αλλαγή κλίμακας της τρέχουσας προβολής του τμήματος εγγράφου SVG. Οι χειριστές συμβάντων αναγνωρίζονται μόνο σε στοιχεία 'svg'.

```csharp
public class SVGZoomEvent : Event
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Χρησιμοποιείται για να υποδείξει εάν ένα συμβάν είναι ή όχι συμβάν με φυσαλίδες. Εάν το συμβάν μπορεί να σχηματίσει φυσαλίδες, η τιμή είναι true, διαφορετικά η τιμή είναι false. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Χρησιμοποιείται για να υποδείξει εάν ένα συμβάν μπορεί να αποτρέψει την προεπιλεγμένη δράση του. Εάν η προεπιλεγμένη ενέργεια μπορεί να αποτραπεί, η τιμή είναι true, διαφορετικά η τιμή είναι false. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Χρησιμοποιείται για την ένδειξη του[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) του οποίου[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) s βρίσκονται υπό επεξεργασία. Αυτό είναι ιδιαίτερα χρήσιμο κατά τη λήψη και τη δημιουργία φυσαλίδων. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Επιστρέφει true εάν κλήθηκε το preventDefault() ενώ η τιμή του ακυρώσιμου χαρακτηριστικού είναι true και false διαφορετικά. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Χρησιμοποιείται για να υποδείξει ποια φάση της ροής συμβάντος αξιολογείται αυτήν τη στιγμή. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | Το χαρακτηριστικό isTrusted πρέπει να επιστρέψει την τιμή στην οποία είχε αρχικοποιηθεί. Όταν δημιουργείται ένα συμβάν, το χαρακτηριστικό πρέπει να αρχικοποιηθεί σε false. |
| [NewScale](../../aspose.html.dom.svg.events/svgzoomevent/newscale/) { get; } | Ο συντελεστής κλίμακας που θα ισχύει μετά την επεξεργασία της λειτουργίας ζουμ. |
| [NewTranslate](../../aspose.html.dom.svg.events/svgzoomevent/newtranslate/) { get; } | Οι τιμές μετάφρασης που θα υπάρχουν μετά την επεξεργασία της λειτουργίας ζουμ. Το αντικείμενο SVGPoint είναι μόνο για ανάγνωση. |
| [PreviousScale](../../aspose.html.dom.svg.events/svgzoomevent/previousscale/) { get; } | Ο συντελεστής κλίμακας από προηγούμενες λειτουργίες μεγέθυνσης που υπήρχε πριν από τη λειτουργία ζουμ. |
| [PreviousTranslate](../../aspose.html.dom.svg.events/svgzoomevent/previoustranslate/) { get; } | Οι τιμές μετάφρασης από προηγούμενες λειτουργίες ζουμ που υπήρχαν πριν από τη λειτουργία ζουμ. Το αντικείμενο SVGPoint είναι μόνο για ανάγνωση. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Χρησιμοποιείται για την ένδειξη του[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) στο οποίο στάλθηκε αρχικά το συμβάν. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Χρησιμοποιείται για τον καθορισμό της ώρας (σε χιλιοστά του δευτερολέπτου σε σχέση με την εποχή) κατά την οποία δημιουργήθηκε το συμβάν. Λόγω του γεγονότος ότι ορισμένα συστήματα ενδέχεται να μην παρέχουν αυτές τις πληροφορίες, η τιμή του timeStamp ενδέχεται να μην είναι διαθέσιμη για όλα τα συμβάντα. Όταν δεν είναι διαθέσιμη , θα επιστραφεί μια τιμή 0. Παραδείγματα χρόνου εποχής είναι η ώρα έναρξης του συστήματος ή 0:0:0 UTC 1η Ιανουαρίου 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | Το όνομα του συμβάντος (χωρίς διάκριση πεζών-κεφαλαίων). Το όνομα πρέπει να είναι όνομα XML. |
| [ZoomRectScreen](../../aspose.html.dom.svg.events/svgzoomevent/zoomrectscreen/) { get; } | Το καθορισμένο ορθογώνιο ζουμ σε μονάδες οθόνης. Το αντικείμενο SVGRect είναι μόνο για ανάγνωση. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση αντικειμένου ECMAScriptType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | Το[`InitEvent`](../../aspose.html.dom.events/event/initevent/) Η μέθοδος χρησιμοποιείται για την προετοιμασία της τιμής του an[`Event`](../../aspose.html.dom.events/event/) δημιουργήθηκε μέσω του [`IDocumentEvent`](../../aspose.html.dom.events/idocumentevent/) διεπαφή. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Εάν ένα συμβάν μπορεί να ακυρωθεί, το[`PreventDefault`](../../aspose.html.dom.events/event/preventdefault/) Η μέθοδος χρησιμοποιείται για να υποδηλώσει ότι το συμβάν πρόκειται να ακυρωθεί, που σημαίνει ότι δεν θα πραγματοποιηθεί οποιαδήποτε προεπιλεγμένη ενέργεια που πραγματοποιείται συνήθως από την υλοποίηση ως αποτέλεσμα του συμβάντος. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Η επίκληση αυτής της μεθόδου αποτρέπει το συμβάν να φτάσει σε οποιονδήποτε ακροατή συμβάντος που έχει καταχωρηθεί μετά το τρέχον και όταν αποστέλλεται σε δέντρο επίσης εμποδίζει το συμβάν να φτάσει σε άλλα αντικείμενα. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | Το[`StopPropagation`](../../aspose.html.dom.events/event/stoppropagation/) χρησιμοποιείται η μέθοδος αποτρέπει την περαιτέρω διάδοση ενός συμβάντος κατά τη ροή συμβάντων. |

### Δείτε επίσης

* class [Event](../../aspose.html.dom.events/event/)
* χώρος ονομάτων [Aspose.Html.Dom.Svg.Events](../../aspose.html.dom.svg.events/)
* συνέλευση [Aspose.HTML](../../)


