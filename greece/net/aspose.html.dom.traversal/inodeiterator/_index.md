---
title: Interface INodeIterator
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Dom.Traversal.INodeIterator διεπαφή. Οι επαναλήπτες χρησιμοποιούνται για να περάσουν μέσα από ένα σύνολο κόμβων π.χ. το σύνολο κόμβων σε ένα NodeList το υποδέντρο εγγράφου που διέπεται από έναν συγκεκριμένο Κόμβο τα αποτελέσματα ενός ερωτήματος ή οποιοδήποτε άλλο σύνολο κόμβων. Το σύνολο των κόμβων που πρόκειται να επαναληφθούν καθορίζεται από την υλοποίηση του NodeIterator. Το DOM Level 2 καθορίζει μια μεμονωμένη υλοποίηση NodeIterator για διέλευση εγγράφου σειράς ενός υποδέντρου εγγράφου. Οι εμφανίσεις αυτών των επαναλήψεων δημιουργούνται καλώντας DocumentTraversal .createNodeIterator.
type: docs
weight: 2500
url: /el/net/aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

Οι επαναλήπτες χρησιμοποιούνται για να περάσουν μέσα από ένα σύνολο κόμβων, π.χ. το σύνολο κόμβων σε ένα NodeList, το υποδέντρο εγγράφου που διέπεται από έναν συγκεκριμένο Κόμβο, τα αποτελέσματα ενός ερωτήματος ή οποιοδήποτε άλλο σύνολο κόμβων. Το σύνολο των κόμβων που πρόκειται να επαναληφθούν καθορίζεται από την υλοποίηση του NodeIterator. Το DOM Level 2 καθορίζει μια μεμονωμένη υλοποίηση NodeIterator για διέλευση εγγράφου σειράς ενός υποδέντρου εγγράφου. Οι εμφανίσεις αυτών των επαναλήψεων δημιουργούνται καλώντας DocumentTraversal .createNodeIterator().

Δείτε επίσης το[Μοντέλο αντικειμένου εγγράφου (DOM) Επίπεδο 2 Προδιαγραφή διέλευσης και εύρους](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface INodeIterator : ITraversal
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | Η τιμή αυτής της σημαίας καθορίζει εάν τα παιδιά των κόμβων αναφοράς entity είναι ορατά στον επαναλήπτη. Εάν είναι ψευδής, αυτοί και οι απόγονοί τους θα απορριφθούν. Σημειώστε ότι αυτή η απόρριψη έχει προτεραιότητα έναντι του whatToShow και του φίλτρου. Σημειώστε επίσης ότι αυτή είναι προς το παρόν η μόνη περίπτωση όπου οι NodeIterators μπορούν να απορρίψουν ένα πλήρες υποδέντρο αντί παρακάμπτοντας μεμονωμένους κόμβους. Για να δημιουργήσετε μια προβολή του εγγράφου που έχει entity references επεκτάθηκε και δεν εκθέτει την οντότητα χρήση_χρησιμοποιήστε_την οντότητα στον κόμβο αναφοράςx00. Απόκρυψη της αναφοράς οντότητας node και ορισμός του ExpandEntityReferences σε true κατά τη δημιουργία του επαναλήπτη . Για να δημιουργήσετε μια προβολή του εγγράφου που έχει κόμβους entity reference αλλά όχι επέκταση οντότητας, χρησιμοποιήστε το whatToShow flags για να εμφανίσετε τον κόμβο αναφοράς οντότητας και set expandEntityReferences σε false. |
| [ReferenceNode](../../aspose.html.dom.traversal/inodeiterator/referencenode/) { get; } | Ο τρέχων κόμβος αναφοράς. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Detach](../../aspose.html.dom.traversal/inodeiterator/detach/)() | Αποσυνδέει το NodeIterator από το σύνολο που επανέλαβε , απελευθερώνοντας τυχόν υπολογιστικούς πόρους και τοποθετώντας το iterator σε ΜΗ ΕΓΚΥΡΟ. Μετά την κλήση του detach, οι κλήσεις στο nextNode ή στο previousNode θα εγείρουν την εξαίρεση INVALID_STATE_ERR. |
| [NextNode](../../aspose.html.dom.traversal/inodeiterator/nextnode/)() | Επιστρέφει τον επόμενο κόμβο στο σύνολο και προωθεί τη θέση του επαναλήπτη στο σύνολο. Αφού δημιουργηθεί ένας NodeIterator, η πρώτη κλήση στο nextNode() επιστρέφει τον πρώτο κόμβο in το σύνολο. |
| [PreviousNode](../../aspose.html.dom.traversal/inodeiterator/previousnode/)() | Επιστρέφει τον προηγούμενο κόμβο στο σύνολο και μετακινεί τη θέση του the NodeIterator προς τα πίσω στο σύνολο. |

### Δείτε επίσης

* interface [ITraversal](../itraversal/)
* χώρος ονομάτων [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* συνέλευση [Aspose.HTML](../../)


