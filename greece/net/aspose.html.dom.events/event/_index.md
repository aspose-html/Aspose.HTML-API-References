---
title: Class Event
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Dom.Events.Event τάξη. ΤοEvent χρησιμοποιείται για την παροχή πληροφοριών συμφραζομένων σχετικά με ένα συμβάν στον χειριστή που επεξεργάζεται το συμβάν.
type: docs
weight: 770
url: /el/net/aspose.html.dom.events/event/
---
## Event class

Το`Event` χρησιμοποιείται για την παροχή πληροφοριών συμφραζομένων σχετικά με ένα συμβάν στον χειριστή που επεξεργάζεται το συμβάν.

```csharp
public class Event : DOMObject
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [Event](event/#constructor)(string) | Αρχικοποιεί μια νέα παρουσία του`Event` τάξη. |
| [Event](event/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Αρχικοποιεί μια νέα παρουσία του`Event` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Χρησιμοποιείται για να υποδείξει εάν ένα συμβάν είναι ή όχι συμβάν με φυσαλίδες. Εάν το συμβάν μπορεί να σχηματίσει φυσαλίδες, η τιμή είναι true, διαφορετικά η τιμή είναι false. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Χρησιμοποιείται για να υποδείξει εάν ένα συμβάν μπορεί να αποτρέψει την προεπιλεγμένη δράση του. Εάν η προεπιλεγμένη ενέργεια μπορεί να αποτραπεί, η τιμή είναι true, διαφορετικά η τιμή είναι false. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Χρησιμοποιείται για την ένδειξη του[`IEventTarget`](../ieventtarget/) του οποίου[`IEventListener`](../ieventlistener/) s βρίσκονται υπό επεξεργασία. Αυτό είναι ιδιαίτερα χρήσιμο κατά τη λήψη και τη δημιουργία φυσαλίδων. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Επιστρέφει true εάν κλήθηκε το preventDefault() ενώ η τιμή του ακυρώσιμου χαρακτηριστικού είναι true και false διαφορετικά. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Χρησιμοποιείται για να υποδείξει ποια φάση της ροής συμβάντος αξιολογείται αυτήν τη στιγμή. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | Το χαρακτηριστικό isTrusted πρέπει να επιστρέψει την τιμή στην οποία είχε αρχικοποιηθεί. Όταν δημιουργείται ένα συμβάν, το χαρακτηριστικό πρέπει να αρχικοποιηθεί σε false. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Χρησιμοποιείται για την ένδειξη του[`IEventTarget`](../ieventtarget/) στο οποίο στάλθηκε αρχικά το συμβάν. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Χρησιμοποιείται για τον καθορισμό της ώρας (σε χιλιοστά του δευτερολέπτου σε σχέση με την εποχή) κατά την οποία δημιουργήθηκε το συμβάν. Λόγω του γεγονότος ότι ορισμένα συστήματα ενδέχεται να μην παρέχουν αυτές τις πληροφορίες, η τιμή του timeStamp ενδέχεται να μην είναι διαθέσιμη για όλα τα συμβάντα. Όταν δεν είναι διαθέσιμη , θα επιστραφεί μια τιμή 0. Παραδείγματα χρόνου εποχής είναι η ώρα έναρξης του συστήματος ή 0:0:0 UTC 1η Ιανουαρίου 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | Το όνομα του συμβάντος (χωρίς διάκριση πεζών-κεφαλαίων). Το όνομα πρέπει να είναι όνομα XML. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση αντικειμένου ECMAScriptType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | Το[`InitEvent`](./initevent/) Η μέθοδος χρησιμοποιείται για την προετοιμασία της τιμής του an`Event` δημιουργήθηκε μέσω του [`IDocumentEvent`](../idocumentevent/) διεπαφή. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Εάν ένα συμβάν μπορεί να ακυρωθεί, το[`PreventDefault`](./preventdefault/) Η μέθοδος χρησιμοποιείται για να υποδηλώσει ότι το συμβάν πρόκειται να ακυρωθεί, που σημαίνει ότι δεν θα πραγματοποιηθεί οποιαδήποτε προεπιλεγμένη ενέργεια που πραγματοποιείται συνήθως από την υλοποίηση ως αποτέλεσμα του συμβάντος. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Η επίκληση αυτής της μεθόδου αποτρέπει το συμβάν να φτάσει σε οποιονδήποτε ακροατή συμβάντος που έχει καταχωρηθεί μετά το τρέχον και όταν αποστέλλεται σε δέντρο επίσης εμποδίζει το συμβάν να φτάσει σε άλλα αντικείμενα. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | Το[`StopPropagation`](./stoppropagation/) χρησιμοποιείται η μέθοδος αποτρέπει την περαιτέρω διάδοση ενός συμβάντος κατά τη ροή συμβάντων. |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| const [AtTargetPhase](../../aspose.html.dom.events/event/attargetphase/) | Η τρέχουσα φάση συμβάντος είναι η φάση λήψης. |
| const [BubblingPhase](../../aspose.html.dom.events/event/bubblingphase/) | Η τρέχουσα φάση συμβάντος είναι η φάση φυσαλίδων. |
| const [CapturingPhase](../../aspose.html.dom.events/event/capturingphase/) | Το συμβάν αξιολογείται αυτήν τη στιγμή στον στόχο[`IEventTarget`](../ieventtarget/) . |
| const [NonePhase](../../aspose.html.dom.events/event/nonephase/) | Τα συμβάντα που δεν έχουν αποσταλεί αυτήν τη στιγμή βρίσκονται σε αυτήν τη φάση. |

### Παρατηρήσεις

Ένα αντικείμενο που υλοποιεί το`Event` γενικά μεταβιβάζεται ως η πρώτη παράμετρος σε ένα πρόγραμμα χειρισμού συμβάντων. Πιο συγκεκριμένες πληροφορίες περιβάλλοντος μεταβιβάζονται στους χειριστές συμβάντων εξάγοντας πρόσθετες διεπαφές από`Event` που περιέχουν πληροφορίες που σχετίζονται άμεσα με τον τύπο του συμβάντος που συνοδεύουν. Αυτές οι παράγωγες διεπαφές υλοποιούνται επίσης από το αντικείμενο που μεταβιβάζεται στον ακροατή συμβάντων.

### Δείτε επίσης

* class [DOMObject](../../aspose.html.dom/domobject/)
* χώρος ονομάτων [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* συνέλευση [Aspose.HTML](../../)


