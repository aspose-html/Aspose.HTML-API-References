---
title: "ITreeWalker.CurrentNode"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Ιδιότητα ITreeWalker. Ο κόμβος στον οποίο βρίσκεται επί του παρόντος το TreeWalker. Τροποποιήσεις στο δέντρο DOM μπορεί να κάνουν τον τρέχοντα κόμβο να μην γίνεται πλέον αποδεκτός από το σχετικό φίλτρο του TreeWalker. Το currentNode μπορεί επίσης να οριστεί ρητά σε οποιονδήποτε κόμβο, ανεξάρτητα από το αν βρίσκεται μέσα στο υποδέντρο που ορίζεται από τον ριζικό κόμβο ή θα γινόταν αποδεκτό από το φίλτρο και τις σημαίες whatToShow. Περαιτέρω διάσχιση πραγματοποιείται σε σχέση με το currentNode ακόμη και αν δεν αποτελεί μέρος της τρέχουσας προβολής, εφαρμόζοντας τα φίλτρα στην ζητούμενη κατεύθυνση· εάν δεν είναι δυνατή η διάσχιση, το currentNode δεν αλλάζει."
type: docs

url: /el/java/com.aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Ο κόμβος στον οποίο βρίσκεται επί του παρόντος το TreeWalker. Τροποποιήσεις στο δέντρο DOM μπορεί να κάνουν τον τρέχοντα κόμβο να μην γίνεται πλέον αποδεκτός από το σχετικό φίλτρο του TreeWalker. Το currentNode μπορεί επίσης να οριστεί ρητά σε οποιονδήποτε κόμβο, ανεξάρτητα από το αν βρίσκεται μέσα στο υποδέντρο που ορίζεται από τον ριζικό κόμβο ή θα γινόταν αποδεκτό από το φίλτρο και τις σημαίες whatToShow. Περαιτέρω διάσχιση πραγματοποιείται σε σχέση με το currentNode ακόμη και αν δεν αποτελεί μέρος της τρέχουσας προβολής, εφαρμόζοντας τα φίλτρα στην ζητούμενη κατεύθυνση· εάν δεν είναι δυνατή η διάσχιση, το currentNode δεν αλλάζει.

```java
public Node CurrentNode { get; set; }
```

### Property Value

Ο τρέχων κόμβος.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Εγείρεται εάν γίνει προσπάθεια ορισμού του currentNode σε null. |

### Δείτε επίσης

* class [Node](../../../com.aspose.html.dom/node/)
* interface [ITreeWalker](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
