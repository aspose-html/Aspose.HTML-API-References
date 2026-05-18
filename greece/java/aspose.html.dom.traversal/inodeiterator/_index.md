---
title: "Διεπαφή INodeIterator"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Διεπαφή com.aspose.html.dom.traversal.INodeIterator. Οι iterators χρησιμοποιούνται για την διαδρομή μέσω ενός συνόλου κόμβων, π.χ. το σύνολο των κόμβων σε ένα NodeList, το υποδέντρο του εγγράφου που διέπεται από έναν συγκεκριμένο Node, τα αποτελέσματα ενός ερωτήματος ή οποιοδήποτε άλλο σύνολο κόμβων. Το σύνολο των κόμβων που θα διαβαστούν καθορίζεται από την υλοποίηση του NodeIterator. Το DOM Level 2 ορίζει μια μοναδική υλοποίηση NodeIterator για την περιήγηση με τη σειρά του εγγράφου ενός υποδέντρου. Παραδείγματα αυτών των iterators δημιουργούνται με την κλήση του DocumentTraversal .createNodeIterator"
type: docs

url: /el/java/com.aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

Οι Iterators χρησιμοποιούνται για να προχωρούν μέσα σε ένα σύνολο κόμβων, π.χ. το σύνολο των κόμβων σε ένα NodeList, το υποδέντρο του εγγράφου που διέπεται από έναν συγκεκριμένο Node, τα αποτελέσματα ενός ερωτήματος ή οποιοδήποτε άλλο σύνολο κόμβων. Το σύνολο των κόμβων που θα επαναληφθεί καθορίζεται από την υλοποίηση του NodeIterator. Το DOM Level 2 ορίζει μια μοναδική υλοποίηση του NodeIterator για διάσχιση με τη σειρά του εγγράφου ενός υποδέντρου εγγράφου. Παραδείγματα αυτών των iterators δημιουργούνται με την κλήση του DocumentTraversal .createNodeIterator().

Δείτε επίσης το [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface INodeIterator : ITraversal
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getPointerBeforeReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) Η τιμή αυτής της σημαίας καθορίζει εάν τα παιδιά των κόμβων αναφοράς οντοτήτων είναι ορατά στον iterator. Εάν είναι false, αυτά και οι απόγονοί τους θα απορριφθούν. Σημειώστε ότι αυτή η απόρριψη έχει προτεραιότητα έναντι του whatToShow και του φίλτρου. Επίσης, σημειώστε ότι αυτή είναι επί του παρόντος η μοναδική κατάσταση όπου οι NodeIterators μπορούν να απορρίψουν ολόκληρο υποδέντρο αντί να παραλείπουν μεμονωμένους κόμβους. Για να δημιουργήσετε μια προβολή του εγγράφου με επεκταμένες αναφορές οντοτήτων και χωρίς να εκθέτει τον ίδιο τον κόμβο αναφοράς οντοτήτων, χρησιμοποιήστε τις σημαίες whatToShow για να κρύψετε τον κόμβο αναφοράς οντοτήτων και ορίστε expandEntityReferences σε true κατά τη δημιουργία του iterator. Για να δημιουργήσετε μια προβολή του εγγράφου που περιέχει κόμβους αναφοράς οντοτήτων αλλά χωρίς επέκταση οντοτήτων, χρησιμοποιήστε τις σημαίες whatToShow για να εμφανίσετε τον κόμβο αναφοράς οντοτήτων και ορίστε expandEntityReferences σε false. |
| [getReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/referencenode/) Ο τρέχων κόμβος αναφοράς. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [detach](../../com.aspose.html.dom.traversal/inodeiterator/detach/)() | Αποσυνδέει το NodeIterator από το σύνολο που διέσχισε, απελευθερώνοντας τυχόν υπολογιστικούς πόρους και τοποθετώντας τον iterator στην κατάσταση INVALID. Μετά την κλήση του detach, οι κλήσεις σε nextNode ή previousNode θα προκαλέσουν την εξαίρεση INVALID_STATE_ERR. |
| [nextNode](../../com.aspose.html.dom.traversal/inodeiterator/nextnode/)() | Επιστρέφει τον επόμενο κόμβο στο σύνολο και προχωρά τη θέση του iterator στο σύνολο. Μετά τη δημιουργία ενός NodeIterator, η πρώτη κλήση στο nextNode() επιστρέφει τον πρώτο κόμβο στο σύνολο. |
| [previousNode](../../com.aspose.html.dom.traversal/inodeiterator/previousnode/)() | Επιστρέφει τον προηγούμενο κόμβο στο σύνολο και μετακινεί τη θέση του NodeIterator προς τα πίσω στο σύνολο. |

### Δείτε επίσης

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
