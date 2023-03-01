---
title: Document.CreateTreeWalker
second_title: Aspose.HTML για Αναφορά API .NET
description: Document μέθοδος. Δημιουργήστε ένα νέο TreeWalker πάνω από το υποδέντρο που έχει ρίζες στον καθορισμένο κόμβο .
type: docs
weight: 940
url: /el/net/aspose.html.dom/document/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Δημιουργήστε ένα νέο TreeWalker πάνω από το υποδέντρο που έχει ρίζες στον καθορισμένο κόμβο .

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| root | Node | κόμβος που θα χρησιμεύσει ως ρίζα για το TreeWalker. Οι σημαίες whatToShow και το NodeFilter δεν λαμβάνονται υπόψη κατά τον ορισμό αυτής της τιμής. οποιοσδήποτε τύπος κόμβου θα γίνει δεκτός ως ρίζα. Ο currentNode του TreeWalker είναι αρχικοποιημένος σε αυτόν τον κόμβο, είτε είναι ορατός είτε όχι. Η ρίζα λειτουργεί ως σημείο στάσης για μεθόδους traversal που κοιτάζουν προς τα πάνω στη δομή του εγγράφου, όπως parentNode και nextNode. Η ρίζα πρέπει να μην είναι μηδενική. |

### Επιστρεφόμενη Αξία

Το νεοδημιουργημένο TreeWalker.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Αυξάνεται εάν η καθορισμένη ρίζα είναι null. |

### Δείτε επίσης

* interface [ITreeWalker](../../../aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* χώρος ονομάτων [Aspose.Html.Dom](../../document/)
* συνέλευση [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Δημιουργήστε ένα νέο TreeWalker πάνω από το υποδέντρο που έχει ρίζες στον καθορισμένο κόμβο .

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| root | Node | κόμβος που θα χρησιμεύσει ως ρίζα για το TreeWalker. Οι σημαίες whatToShow και το NodeFilter δεν λαμβάνονται υπόψη κατά τον ορισμό αυτής της τιμής. οποιοσδήποτε τύπος κόμβου θα γίνει δεκτός ως ρίζα. Ο currentNode του TreeWalker είναι αρχικοποιημένος σε αυτόν τον κόμβο, είτε είναι ορατός είτε όχι. Η ρίζα λειτουργεί ως σημείο στάσης για μεθόδους traversal που κοιτάζουν προς τα πάνω στη δομή του εγγράφου, όπως parentNode και nextNode. Η ρίζα πρέπει να μην είναι μηδενική. |
| whatToShow | Int64 | Η σημαία καθορίζει ποιοι τύποι κόμβων μπορούν να εμφανίζονται στο τη λογική προβολή του δέντρου που παρουσιάζεται από το δέντρο-περιπατητή. Δείτε την περιγραφή του NodeFilter για το σύνολο των τιμών possible SHOW_. Αυτές οι σημαίες μπορούν να συνδυαστούν χρησιμοποιώντας OR. |

### Επιστρεφόμενη Αξία

Το νεοδημιουργημένο TreeWalker.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Αυξάνεται εάν η καθορισμένη ρίζα είναι null. |

### Δείτε επίσης

* interface [ITreeWalker](../../../aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* χώρος ονομάτων [Aspose.Html.Dom](../../document/)
* συνέλευση [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Δημιουργήστε ένα νέο TreeWalker πάνω από το υποδέντρο που έχει ρίζες στον καθορισμένο κόμβο .

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| root | Node | κόμβος που θα χρησιμεύσει ως ρίζα για το TreeWalker. Οι σημαίες whatToShow και το NodeFilter δεν λαμβάνονται υπόψη κατά τον ορισμό αυτής της τιμής. οποιοσδήποτε τύπος κόμβου θα γίνει δεκτός ως ρίζα. Ο currentNode του TreeWalker είναι αρχικοποιημένος σε αυτόν τον κόμβο, είτε είναι ορατός είτε όχι. Η ρίζα λειτουργεί ως σημείο στάσης για μεθόδους traversal που κοιτάζουν προς τα πάνω στη δομή του εγγράφου, όπως parentNode και nextNode. Η ρίζα πρέπει να μην είναι μηδενική. |
| whatToShow | Int64 | Η σημαία καθορίζει ποιοι τύποι κόμβων μπορούν να εμφανίζονται στο τη λογική προβολή του δέντρου που παρουσιάζεται από το δέντρο-περιπατητή. Δείτε την περιγραφή του NodeFilter για το σύνολο των τιμών possible SHOW_. Αυτές οι σημαίες μπορούν να συνδυαστούν χρησιμοποιώντας OR. |
| filter | INodeFilter | NodeFilter που θα χρησιμοποιηθεί με το this TreeWalker ή null για να υποδείξει ότι δεν υπάρχει φίλτρο. |

### Επιστρεφόμενη Αξία

Το νεοδημιουργημένο TreeWalker.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Αυξάνεται εάν η καθορισμένη ρίζα είναι null. |

### Δείτε επίσης

* interface [ITreeWalker](../../../aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* χώρος ονομάτων [Aspose.Html.Dom](../../document/)
* συνέλευση [Aspose.HTML](../../../)


