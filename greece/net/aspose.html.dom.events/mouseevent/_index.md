---
title: Class MouseEvent
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Dom.Events.MouseEvent τάξη. Η διεπαφή MouseEvent παρέχει συγκεκριμένες πληροφορίες σχετικά με τα συμφραζόμενα που σχετίζονται με συμβάντα Mouse.
type: docs
weight: 840
url: /el/net/aspose.html.dom.events/mouseevent/
---
## MouseEvent class

Η διεπαφή MouseEvent παρέχει συγκεκριμένες πληροφορίες σχετικά με τα συμφραζόμενα που σχετίζονται με συμβάντα Mouse.

```csharp
public class MouseEvent : UIEvent
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [MouseEvent](mouseevent/#constructor)(string) | Αρχικοποιεί μια νέα παρουσία του`MouseEvent` τάξη. |
| [MouseEvent](mouseevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Αρχικοποιεί μια νέα παρουσία του`MouseEvent` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/mouseevent/altkey/) { get; } | Ανατρέξτε στο χαρακτηριστικό altKey. |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Χρησιμοποιείται για να υποδείξει εάν ένα συμβάν είναι ή όχι συμβάν με φυσαλίδες. Εάν το συμβάν μπορεί να σχηματίσει φυσαλίδες, η τιμή είναι true, διαφορετικά η τιμή είναι false. |
| [Button](../../aspose.html.dom.events/mouseevent/button/) { get; } | Κατά τη διάρκεια συμβάντων του ποντικιού που προκαλούνται από το πάτημα ή την απελευθέρωση ενός κουμπιού ποντικιού, το κουμπί ΠΡΕΠΕΙ να χρησιμοποιείται για να υποδείξει ποιο κουμπί συσκευής δείκτη άλλαξε κατάσταση. |
| [Buttons](../../aspose.html.dom.events/mouseevent/buttons/) { get; } | Κατά τη διάρκεια οποιωνδήποτε συμβάντων ποντικιού, ΠΡΕΠΕΙ να χρησιμοποιούνται κουμπιά για να υποδεικνύουν ποιος συνδυασμός κουμπιών του ποντικιού πιέζεται αυτήν τη στιγμή, εκφραζόμενη ως μάσκα bit. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Χρησιμοποιείται για να υποδείξει εάν ένα συμβάν μπορεί να αποτρέψει την προεπιλεγμένη δράση του. Εάν η προεπιλεγμένη ενέργεια μπορεί να αποτραπεί, η τιμή είναι true, διαφορετικά η τιμή είναι false. |
| [ClientX](../../aspose.html.dom.events/mouseevent/clientx/) { get; } | Η οριζόντια συντεταγμένη στην οποία συνέβη το συμβάν σε σχέση με τη θύρα προβολής που σχετίζεται με το συμβάν. |
| [ClientY](../../aspose.html.dom.events/mouseevent/clienty/) { get; } | Η κατακόρυφη συντεταγμένη στην οποία συνέβη το συμβάν σε σχέση με τη θύρα προβολής που σχετίζεται με το συμβάν. |
| [CtrlKey](../../aspose.html.dom.events/mouseevent/ctrlkey/) { get; } | Ανατρέξτε στο χαρακτηριστικό ctrlKey. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Χρησιμοποιείται για την ένδειξη του[`IEventTarget`](../ieventtarget/) του οποίου[`IEventListener`](../ieventlistener/) s βρίσκονται υπό επεξεργασία. Αυτό είναι ιδιαίτερα χρήσιμο κατά τη λήψη και τη δημιουργία φυσαλίδων. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Επιστρέφει true εάν κλήθηκε το preventDefault() ενώ η τιμή του ακυρώσιμου χαρακτηριστικού είναι true και false διαφορετικά. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | Καθορίζει ορισμένες λεπτομέρειες σχετικά με το συμβάν, ανάλογα με τον τύπο του συμβάντος. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Χρησιμοποιείται για να υποδείξει ποια φάση της ροής συμβάντος αξιολογείται αυτήν τη στιγμή. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | Το χαρακτηριστικό isTrusted πρέπει να επιστρέψει την τιμή στην οποία είχε αρχικοποιηθεί. Όταν δημιουργείται ένα συμβάν, το χαρακτηριστικό πρέπει να αρχικοποιηθεί σε false. |
| [MetaKey](../../aspose.html.dom.events/mouseevent/metakey/) { get; } | Ανατρέξτε στο χαρακτηριστικό metaKey. |
| [RelatedTarget](../../aspose.html.dom.events/mouseevent/relatedtarget/) { get; } | Χρησιμοποιείται για τον προσδιορισμό ενός δευτερεύοντος στόχου συμβάντος που σχετίζεται με ένα συμβάν διεπαφής χρήστη, ανάλογα με τον τύπο του συμβάντος. |
| [ScreenX](../../aspose.html.dom.events/mouseevent/screenx/) { get; } | Η οριζόντια συντεταγμένη στην οποία συνέβη το συμβάν σε σχέση με την αρχή του συστήματος συντεταγμένων οθόνης. |
| [ScreenY](../../aspose.html.dom.events/mouseevent/screeny/) { get; } | Η κατακόρυφη συντεταγμένη στην οποία συνέβη το συμβάν σε σχέση με την αρχή του συστήματος συντεταγμένων οθόνης. |
| [ShiftKey](../../aspose.html.dom.events/mouseevent/shiftkey/) { get; } | Ανατρέξτε στο χαρακτηριστικό shiftKey. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Χρησιμοποιείται για την ένδειξη του[`IEventTarget`](../ieventtarget/) στο οποίο στάλθηκε αρχικά το συμβάν. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Χρησιμοποιείται για τον καθορισμό της ώρας (σε χιλιοστά του δευτερολέπτου σε σχέση με την εποχή) κατά την οποία δημιουργήθηκε το συμβάν. Λόγω του γεγονότος ότι ορισμένα συστήματα ενδέχεται να μην παρέχουν αυτές τις πληροφορίες, η τιμή του timeStamp ενδέχεται να μην είναι διαθέσιμη για όλα τα συμβάντα. Όταν δεν είναι διαθέσιμη , θα επιστραφεί μια τιμή 0. Παραδείγματα χρόνου εποχής είναι η ώρα έναρξης του συστήματος ή 0:0:0 UTC 1η Ιανουαρίου 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | Το όνομα του συμβάντος (χωρίς διάκριση πεζών-κεφαλαίων). Το όνομα πρέπει να είναι όνομα XML. |
| [View](../../aspose.html.dom.events/uievent/view/) { get; } | Το χαρακτηριστικό view προσδιορίζει το παράθυρο από το οποίο δημιουργήθηκε το συμβάν. Η μη αρχικοποιημένη τιμή αυτού του χαρακτηριστικού ΠΡΕΠΕΙ να είναι null. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση αντικειμένου ECMAScriptType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | Το[`InitEvent`](../event/initevent/) Η μέθοδος χρησιμοποιείται για την προετοιμασία της τιμής του an[`Event`](../event/) δημιουργήθηκε μέσω του [`IDocumentEvent`](../idocumentevent/) διεπαφή. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Εάν ένα συμβάν μπορεί να ακυρωθεί, το[`PreventDefault`](../event/preventdefault/) Η μέθοδος χρησιμοποιείται για να υποδηλώσει ότι το συμβάν πρόκειται να ακυρωθεί, που σημαίνει ότι δεν θα πραγματοποιηθεί οποιαδήποτε προεπιλεγμένη ενέργεια που πραγματοποιείται συνήθως από την υλοποίηση ως αποτέλεσμα του συμβάντος. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Η επίκληση αυτής της μεθόδου αποτρέπει το συμβάν να φτάσει σε οποιονδήποτε ακροατή συμβάντος που έχει καταχωρηθεί μετά το τρέχον και όταν αποστέλλεται σε δέντρο επίσης εμποδίζει το συμβάν να φτάσει σε άλλα αντικείμενα. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | Το[`StopPropagation`](../event/stoppropagation/) χρησιμοποιείται η μέθοδος αποτρέπει την περαιτέρω διάδοση ενός συμβάντος κατά τη ροή συμβάντων. |

### Δείτε επίσης

* class [UIEvent](../uievent/)
* χώρος ονομάτων [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* συνέλευση [Aspose.HTML](../../)

