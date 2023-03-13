---
title: IDocumentTraversal.CreateNodeIterator
second_title: Aspose.HTML για Αναφορά API .NET
description: IDocumentTraversal μέθοδος. Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που έχει ρίζες στον καθορισμένο κόμβο .
type: docs
weight: 10
url: /el/net/aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που έχει ρίζες στον καθορισμένο κόμβο .

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| root | Node | κόμβος που θα επαναληφθεί μαζί με τα παιδιά του. Ο επαναλήπτης είναι αρχικά τοποθετημένος ακριβώς πριν από αυτόν τον κόμβο. Οι σημαίες whatToShow και το φίλτρο, εάν υπάρχει, δεν λαμβάνονται υπόψη κατά τον ορισμό αυτής της θέσης. Η ρίζα δεν πρέπει να είναι null. |

### Επιστρεφόμενη Αξία

Ο νεοδημιουργημένος NodeIterator.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Αυξάνεται εάν η καθορισμένη ρίζα είναι null. |

### Δείτε επίσης

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* χώρος ονομάτων [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* συνέλευση [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που έχει ρίζες στον καθορισμένο κόμβο .

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| root | Node | κόμβος που θα επαναληφθεί μαζί με τα παιδιά του. Ο επαναλήπτης είναι αρχικά τοποθετημένος ακριβώς πριν από αυτόν τον κόμβο. Οι σημαίες whatToShow και το φίλτρο, εάν υπάρχει, δεν λαμβάνονται υπόψη κατά τον ορισμό αυτής της θέσης. Η ρίζα δεν πρέπει να είναι null. |
| whatToShow | Int64 | Το flag καθορίζει ποιοι τύποι κόμβων μπορούν να εμφανίζονται στο τη λογική προβολή του δέντρου που παρουσιάζεται από τον επαναλήπτη. Δείτε την περιγραφή του NodeFilter για το σύνολο των τιμών possible SHOW_. Αυτές οι σημαίες μπορούν να συνδυαστούν χρησιμοποιώντας OR. |

### Επιστρεφόμενη Αξία

Ο νεοδημιουργημένος NodeIterator.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Αυξάνεται εάν η καθορισμένη ρίζα είναι null. |

### Δείτε επίσης

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* χώρος ονομάτων [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* συνέλευση [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που έχει ρίζες στον καθορισμένο κόμβο .

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| root | Node | κόμβος που θα επαναληφθεί μαζί με τα παιδιά του. Ο επαναλήπτης είναι αρχικά τοποθετημένος ακριβώς πριν από αυτόν τον κόμβο. Οι σημαίες whatToShow και το φίλτρο, εάν υπάρχει, δεν λαμβάνονται υπόψη κατά τον ορισμό αυτής της θέσης. Η ρίζα δεν πρέπει να είναι null. |
| whatToShow | Int64 | Το flag καθορίζει ποιοι τύποι κόμβων μπορούν να εμφανίζονται στο τη λογική προβολή του δέντρου που παρουσιάζεται από τον επαναλήπτη. Δείτε την περιγραφή του NodeFilter για το σύνολο των τιμών possible SHOW_. Αυτές οι σημαίες μπορούν να συνδυαστούν χρησιμοποιώντας OR. |
| filter | INodeFilter | NodeFilter που θα χρησιμοποιηθεί με το this TreeWalker ή null για να υποδείξει ότι δεν υπάρχει φίλτρο. |

### Επιστρεφόμενη Αξία

Ο νεοδημιουργημένος NodeIterator.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Αυξάνεται εάν η καθορισμένη ρίζα είναι null. |

### Δείτε επίσης

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* χώρος ονομάτων [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* συνέλευση [Aspose.HTML](../../../)


