---
title: "IDocumentTraversal Διεπαφή"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.traversal.IDocumentTraversal interface. Το DocumentTraversal περιέχει μεθόδους που δημιουργούν iterators και tree-walkers για την περιήγηση ενός κόμβου και των παιδιών του με σειρά εγγράφου, βάθος-πρώτα, προ-προκαθορισμένη σειρά, η οποία είναι ισοδύναμη με τη σειρά με την οποία εμφανίζονται οι ετικέτες έναρξης στην κειμενική αναπαράσταση του εγγράφου. Σε DOM που υποστηρίζουν τη δυνατότητα Traversal, το DocumentTraversal θα υλοποιείται από τα ίδια αντικείμενα που υλοποιούν τη Document διεπαφή."
type: docs

url: /el/java/com.aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

Το DocumentTraversal περιέχει μεθόδους που δημιουργούν επαναλήπτες και διασχείς δέντρου για τη διασχίση ενός κόμβου και των παιδιών του με τη σειρά του εγγράφου (βάθος πρώτα, προ-διάταξη, η οποία είναι ισοδύναμη με τη σειρά με την οποία εμφανίζονται οι ετικέτες έναρξης στην κειμενική αναπαράσταση του εγγράφου). Σε DOM που υποστηρίζουν τη δυνατότητα Traversal, το DocumentTraversal θα υλοποιείται από τα ίδια αντικείμενα που υλοποιούν τη διεπαφή Document.

Δείτε επίσης το [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface IDocumentTraversal
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(Node) | Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που ριζώνεται στον καθορισμένο κόμβο. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(Node, long) | Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που ριζώνεται στον καθορισμένο κόμβο. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που ριζώνεται στον καθορισμένο κόμβο. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(Node) | Δημιουργήστε ένα νέο TreeWalker πάνω από το υποδέντρο που ριζώνεται στον καθορισμένο κόμβο. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(Node, long) | Δημιουργήστε ένα νέο TreeWalker πάνω από το υποδέντρο που ριζώνεται στον καθορισμένο κόμβο. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Δημιουργήστε ένα νέο TreeWalker πάνω από το υποδέντρο που ριζώνεται στον καθορισμένο κόμβο. |

### Δείτε επίσης

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
