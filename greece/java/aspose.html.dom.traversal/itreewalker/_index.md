---
title: "Διεπαφή ITreeWalker"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Διεπαφή com.aspose.html.dom.traversal.ITreeWalker. Τα αντικείμενα TreeWalker χρησιμοποιούνται για την πλοήγηση σε δέντρο ή υποδέντρο εγγράφου χρησιμοποιώντας την προβολή του εγγράφου που ορίζεται από τις σημαίες whatToShow και τυχόν φίλτρο. Οποιαδήποτε λειτουργία που εκτελεί πλοήγηση με χρήση TreeWalker θα υποστηρίζει αυτόματα οποιαδήποτε προβολή ορίζεται από ένα TreeWalker."
type: docs

url: /el/java/com.aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

Τα αντικείμενα TreeWalker χρησιμοποιούνται για την πλοήγηση σε δέντρο ή υποδέντρο εγγράφου χρησιμοποιώντας την προβολή του εγγράφου που ορίζεται από τις σημαίες whatToShow και το φίλτρο (εάν υπάρχει). Οποιαδήποτε λειτουργία που εκτελεί πλοήγηση με χρήση TreeWalker θα υποστηρίζει αυτόματα οποιαδήποτε προβολή ορίζεται από ένα TreeWalker.

Η παράλειψη κόμβων από τη λογική προβολή ενός υποδέντρου μπορεί να οδηγήσει σε μια δομή που διαφέρει σημαντικά από το ίδιο υποδέντρο στο πλήρες, αφιλτράριστο έγγραφο. Οι κόμβοι που είναι αδέρφια στην προβολή TreeWalker μπορεί να είναι παιδιά διαφορετικών, ευρέως διασκορπισμένων κόμβων στην αρχική προβολή. Για παράδειγμα, σκεφτείτε ένα NodeFilter που παραλείπει όλους τους κόμβους εκτός από τους κόμβους κειμένου και τον ριζικό κόμβο ενός εγγράφου. Στη λογική προβολή που προκύπτει, όλοι οι κόμβοι κειμένου θα είναι αδέρφια και θα εμφανίζονται ως άμεσα παιδιά του ριζικού κόμβου, ανεξάρτητα από το πόσο βαθιά είναι ενσωματωμένη η δομή του αρχικού εγγράφου.

Δείτε επίσης το [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITreeWalker : ITraversal
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
[getCurrentNode]
[setCurrentNode] The node at which the TreeWalker is currently positioned. Alterations to the DOM tree may cause the current node to no longer be accepted by the TreeWalker's associated filter. currentNode may also be explicitly set to any node, whether or not it is within the subtree specified by the root node or would be accepted by the filter and whatToShow flags. Further traversal occurs relative to currentNode even if it is not part of the current view, by applying the filters in the requested direction; if no traversal is possible, currentNode is not changed. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [firstChild](../../com.aspose.html.dom.traversal/itreewalker/firstchild/)() | Μετακινεί το TreeWalker στο πρώτο ορατό παιδί του τρέχοντος κόμβου και επιστρέφει τον νέο κόμβο. Εάν ο τρέχων κόμβος δεν έχει ορατά παιδιά, επιστρέφει null και διατηρεί τον τρέχοντα κόμβο. |
| [lastChild](../../com.aspose.html.dom.traversal/itreewalker/lastchild/)() | Μετακινεί το TreeWalker στο τελευταίο ορατό παιδί του τρέχοντος κόμβου και επιστρέφει τον νέο κόμβο. Εάν ο τρέχων κόμβος δεν έχει ορατά παιδιά, επιστρέφει null και διατηρεί τον τρέχοντα κόμβο. |
| [nextNode](../../com.aspose.html.dom.traversal/itreewalker/nextnode/)() | Μετακινεί το TreeWalker στον επόμενο ορατό κόμβο με σειρά εγγράφου σε σχέση με τον τρέχοντα κόμβο και επιστρέφει τον νέο κόμβο. Εάν ο τρέχων κόμβος δεν έχει επόμενο κόμβο, ή εάν η αναζήτηση για nextNode προσπαθήσει να ανέβει από τον ριζικό κόμβο του TreeWalker, επιστρέφει null και διατηρεί τον τρέχοντα κόμβο. |
| [nextSibling](../../com.aspose.html.dom.traversal/itreewalker/nextsibling/)() | Μετακινεί το TreeWalker στον επόμενο αδερφό του τρέχοντος κόμβου και επιστρέφει τον νέο κόμβο. Εάν ο τρέχων κόμβος δεν έχει ορατό επόμενο αδερφό, επιστρέφει null και διατηρεί τον τρέχοντα κόμβο. |
| [parentNode](../../com.aspose.html.dom.traversal/itreewalker/parentnode/)() | Μετακινείται και επιστρέφει τον πλησιέστερο ορατό πρόγονο του τρέχοντος κόμβου. Εάν η αναζήτηση για τον γονικό κόμβο προσπαθήσει να ανέβει από τον ριζικό κόμβο του TreeWalker, ή εάν αποτύχει να βρει ορατό πρόγονο, αυτή η μέθοδος διατηρεί την τρέχουσα θέση και επιστρέφει null. |
| [previousNode](../../com.aspose.html.dom.traversal/itreewalker/previousnode/)() | Μετακινεί το TreeWalker στον προηγούμενο ορατό κόμβο με σειρά εγγράφου σε σχέση με τον τρέχοντα κόμβο και επιστρέφει τον νέο κόμβο. Εάν ο τρέχων κόμβος δεν έχει προηγούμενο κόμβο ή εάν η αναζήτηση για previousNode προσπαθεί να ανέβει από τον ριζικό κόμβο του TreeWalker, επιστρέφει null και διατηρεί τον τρέχοντα κόμβο. |
| [previousSibling](../../com.aspose.html.dom.traversal/itreewalker/previoussibling/)() | Μετακινεί το TreeWalker στον προηγούμενο αδερφό του τρέχοντος κόμβου και επιστρέφει τον νέο κόμβο. Εάν ο τρέχων κόμβος δεν έχει ορατό προηγούμενο αδερφό, επιστρέφει null και διατηρεί τον τρέχοντα κόμβο. |

### Δείτε επίσης

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
