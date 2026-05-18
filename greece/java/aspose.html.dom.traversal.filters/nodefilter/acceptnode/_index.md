---
title: "NodeFilter.AcceptNode"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος NodeFilter. Δοκιμάζει αν ένας συγκεκριμένος κόμβος είναι ορατός στην λογική προβολή ενός TreeWalker ή NodeIterator. Αυτή η λειτουργία θα κληθεί από την υλοποίηση του TreeWalker και του NodeIterator· δεν καλείται συνήθως απευθείας από κώδικα χρήστη. Ωστόσο, μπορείτε να το κάνετε εάν θέλετε να χρησιμοποιήσετε το ίδιο φίλτρο για να καθοδηγήσετε τη λογική της δικής σας εφαρμογής."
type: docs

url: /el/java/com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/
---
## NodeFilter.AcceptNode method

Δοκιμάστε αν ένας συγκεκριμένος κόμβος είναι ορατός στην λογική προβολή ενός TreeWalker ή NodeIterator. Αυτή η λειτουργία θα κληθεί από την υλοποίηση του TreeWalker και του NodeIterator· δεν καλείται συνήθως απευθείας από κώδικα χρήστη. (Ωστόσο, μπορείτε να το κάνετε εάν θέλετε να χρησιμοποιήσετε το ίδιο φίλτρο για να καθοδηγήσετε τη λογική της δικής σας εφαρμογής.)

```java
public abstract short AcceptNode(Node n)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| n | Node | κόμβος προς έλεγχο για να διαπιστωθεί αν περνάει το φίλτρο ή όχι. |

### Τιμή επιστροφής

μια σταθερά για να καθορίσει εάν ο κόμβος γίνεται αποδεκτός, απορριπτέος ή παραλείπεται, όπως ορίζεται παραπάνω.

### Δείτε επίσης

* class [Node](../../../com.aspose.html.dom/node/)
* class [NodeFilter](../)
* package [com.aspose.html.dom.traversal.filters](../../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../../)
