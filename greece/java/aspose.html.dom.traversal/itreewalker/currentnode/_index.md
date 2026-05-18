---
title: "ITreeWalker.CurrentNode"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "ITreeWalker ιδιότητα. Ο κόμβος στον οποίο βρίσκεται το TreeWalker αυτή τη στιγμή. Τροποποιήσεις στο δέντρο DOM μπορεί να κάνουν τον τρέχοντα κόμβο να μην γίνεται πλέον αποδεκτός από το συσχετισμένο φίλτρο του TreeWalker. Το currentNode μπορεί επίσης να οριστεί ρητά σε οποιονδήποτε κόμβο, είτε βρίσκεται εντός του υποδέντρου που ορίζεται από τον ριζικό κόμβο είτε όχι, ή θα γινόταν αποδεκτό από το φίλτρο και τις σημαίες whatToShow. Περαιτέρω διάσχιση πραγματοποιείται σε σχέση με το currentNode ακόμη και αν δεν αποτελεί μέρος της τρέχουσας προβολής, εφαρμόζοντας τα φίλτρα στην ζητούμενη κατεύθυνση· εάν δεν είναι δυνατή καμία διάσχιση, το currentNode δεν αλλάζει."
type: docs

url: /el/java/com.aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Ο κόμβος στον οποίο βρίσκεται το TreeWalker αυτή τη στιγμή. Τροποποιήσεις στο δέντρο DOM μπορεί να κάνουν τον τρέχοντα κόμβο να μην γίνεται πλέον αποδεκτός από το συσχετισμένο φίλτρο του TreeWalker. Το currentNode μπορεί επίσης να οριστεί ρητά σε οποιονδήποτε κόμβο, είτε βρίσκεται εντός του υποδέντρου που ορίζεται από τον ριζικό κόμβο είτε όχι, ή θα γινόταν αποδεκτό από το φίλτρο και τις σημαίες whatToShow. Περαιτέρω διάσχιση πραγματοποιείται σε σχέση με το currentNode ακόμη και αν δεν αποτελεί μέρος της τρέχουσας προβολής, εφαρμόζοντας τα φίλτρα στην ζητούμενη κατεύθυνση· εάν δεν είναι δυνατή καμία διάσχιση, το currentNode δεν αλλάζει.

```java
public Node CurrentNode { get; set; }
```

### Property Value

Ο τρέχων κόμβος.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Εγείρεται εάν γίνει προσπάθεια να οριστεί το currentNode σε null. |

### Δείτε επίσης

* class [Node](../../../com.aspose.html.dom/node/)
* interface [ITreeWalker](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
