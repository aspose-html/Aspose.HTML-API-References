---
title: "Διεπαφή ITraversal"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Διεπαφή com.aspose.html.dom.traversal.ITraversal. Οι επαναλήπτες χρησιμοποιούνται για να προχωρούν μέσα σε ένα σύνολο κόμβων, π.χ. το σύνολο των κόμβων σε ένα NodeList, το υποδέντρο του εγγράφου που διέπεται από έναν συγκεκριμένο Node, τα αποτελέσματα ενός ερωτήματος ή οποιοδήποτε άλλο σύνολο κόμβων. Το σύνολο των κόμβων που θα επαναληφθεί καθορίζεται από την υλοποίηση του NodeIterator. Το DOM Level 2 ορίζει μια μοναδική υλοποίηση NodeIterator για διάσχιση κατά σειρά εγγράφου ενός υποδέντρου εγγράφου. Οι παρουσίες αυτών των επαναληπτών δημιουργούνται με κλήση του DocumentTraversal .createNodeIterator."
type: docs

url: /el/java/com.aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

Οι Iterators χρησιμοποιούνται για να προχωρούν μέσα σε ένα σύνολο κόμβων, π.χ. το σύνολο των κόμβων σε ένα NodeList, το υποδέντρο του εγγράφου που διέπεται από έναν συγκεκριμένο Node, τα αποτελέσματα ενός ερωτήματος ή οποιοδήποτε άλλο σύνολο κόμβων. Το σύνολο των κόμβων που θα επαναληφθεί καθορίζεται από την υλοποίηση του NodeIterator. Το DOM Level 2 ορίζει μια μοναδική υλοποίηση του NodeIterator για διάσχιση με τη σειρά του εγγράφου ενός υποδέντρου εγγράφου. Παραδείγματα αυτών των iterators δημιουργούνται με την κλήση του DocumentTraversal .createNodeIterator().

Δείτε επίσης το [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITraversal : IDisposable
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getFilter](../../com.aspose.html.dom.traversal/itraversal/filter/) Το NodeFilter που χρησιμοποιείται για φιλτράρισμα κόμβων. |
| [getRoot](../../com.aspose.html.dom.traversal/itraversal/root/) Ο ριζικός κόμβος του NodeIterator, όπως ορίστηκε όταν δημιουργήθηκε. |
| [getWhatToShow](../../com.aspose.html.dom.traversal/itraversal/whattoshow/) Αυτό το χαρακτηριστικό καθορίζει ποιοι τύποι κόμβων παρουσιάζονται μέσω του επαναλήπτη. Το διαθέσιμο σύνολο σταθερών ορίζεται στη διεπαφή NodeFilter. Οι κόμβοι που δεν γίνονται αποδεκτοί από το whatToShow θα παραλειφθούν, αλλά τα παιδιά τους μπορεί ακόμη να ληφθούν υπόψη. Σημειώστε ότι αυτή η παράλειψη έχει προτεραιότητα έναντι του φίλτρου, εάν υπάρχει. |

### Δείτε επίσης

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
