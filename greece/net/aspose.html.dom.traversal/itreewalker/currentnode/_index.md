---
title: ITreeWalker.CurrentNode
second_title: Aspose.HTML για Αναφορά API .NET
description: ITreeWalker ιδιοκτησία. Ο κόμβος στον οποίο βρίσκεται επί του παρόντος το TreeWalker. Οι αλλαγές στο δέντρο DOM μπορεί να κάνουν τον τρέχοντα κόμβο να μην γίνεται πλέον αποδεκτός από το συσχετισμένο φίλτρο του TreeWalker. currentNode μπορεί επίσης να οριστεί ρητά σε οποιονδήποτε κόμβο_x00 εντός του υποδέντρου που καθορίζεται από τον ριζικό κόμβο ή θα γινόταν αποδεκτό από τα σημαίες φίλτρου and whatToShow. Περαιτέρω διέλευση λαμβάνει χώρα σε σχέση με το currentNode ακόμα κι αν δεν αποτελεί μέρος της τρέχουσας προβολής εφαρμόζοντας τα φίλτρα στην ζητούμενη κατεύθυνση. εάν δεν υπάρχει δυνατότητα traversal  το currentNode δεν αλλάζει.
type: docs
weight: 10
url: /el/net/aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Ο κόμβος στον οποίο βρίσκεται επί του παρόντος το TreeWalker. Οι αλλαγές στο δέντρο DOM μπορεί να κάνουν τον τρέχοντα κόμβο να μην γίνεται πλέον αποδεκτός από το συσχετισμένο φίλτρο του TreeWalker. currentNode μπορεί επίσης να οριστεί ρητά σε οποιονδήποτε κόμβο,_x00 εντός του υποδέντρου που καθορίζεται από τον ριζικό κόμβο ή θα γινόταν αποδεκτό από τα σημαίες φίλτρου and whatToShow. Περαιτέρω διέλευση λαμβάνει χώρα σε σχέση με το currentNode, ακόμα κι αν δεν αποτελεί μέρος της τρέχουσας προβολής, εφαρμόζοντας τα φίλτρα στην ζητούμενη κατεύθυνση. εάν δεν υπάρχει δυνατότητα traversal , το currentNode δεν αλλάζει.

```csharp
public Node CurrentNode { get; set; }
```

### Αξία περιουσίας

Ο τρέχων κόμβος.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Αυξάνεται εάν γίνει προσπάθεια να οριστεί currentNode σε null. |

### Δείτε επίσης

* class [Node](../../../aspose.html.dom/node/)
* interface [ITreeWalker](../)
* χώρος ονομάτων [Aspose.Html.Dom.Traversal](../../itreewalker/)
* συνέλευση [Aspose.HTML](../../../)


