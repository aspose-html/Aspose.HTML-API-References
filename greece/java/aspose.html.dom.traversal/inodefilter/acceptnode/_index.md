---
title: "INodeFilter.AcceptNode"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "INodeFilter μέθοδος. Δοκιμάζει εάν ένας καθορισμένος κόμβος είναι ορατός στην λογική προβολή ενός TreeWalker ή NodeIterator. Αυτή η λειτουργία θα κληθεί από την υλοποίηση του TreeWalker και του NodeIterator· δεν καλείται συνήθως απευθείας από κώδικα χρήστη. Ωστόσο, μπορείτε να το κάνετε εάν θέλετε να χρησιμοποιήσετε το ίδιο φίλτρο για να καθοδηγήσετε τη λογική της δικής σας εφαρμογής."
type: docs

url: /el/java/com.aspose.html.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

Δοκιμάστε εάν ένας καθορισμένος κόμβος είναι ορατός στην λογική προβολή ενός TreeWalker ή NodeIterator. Αυτή η λειτουργία θα κληθεί από την υλοποίηση του TreeWalker και του NodeIterator· συνήθως δεν καλείται άμεσα από κώδικα χρήστη. (Ωστόσο, μπορείτε να το κάνετε εάν θέλετε να χρησιμοποιήσετε το ίδιο φίλτρο για να καθοδηγήσετε τη λογική της εφαρμογής σας.)

```java
public short AcceptNode(Node n)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| n | Node | κόμβος για έλεγχο εάν περνά το φίλτρο ή όχι. |

### Τιμή Επιστροφής

μια σταθερά για τον καθορισμό εάν ο κόμβος γίνεται αποδεκτός, απορριπτέος ή παραλείπεται, όπως ορίζεται παραπάνω.

### Δείτε επίσης

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
