---
title: "Document.CreateTreeWalker"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Document. Δημιουργήστε έναν νέο TreeWalker πάνω στο υποδέντρο που ρίζεται στον καθορισμένο node"
type: docs

url: /el/java/com.aspose.html.dom/document/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Δημιουργήστε έναν νέο TreeWalker πάνω στο υποδέντρο που έχει ρίζα τον καθορισμένο κόμβο.

```java
public ITreeWalker CreateTreeWalker(Node root)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| ρίζα | Node | Κόμβος που θα λειτουργήσει ως ρίζα για το TreeWalker. Οι σημαίες whatToShow και το NodeFilter δεν λαμβάνονται υπόψη κατά τον ορισμό αυτής της τιμής· οποιοσδήποτε τύπος κόμβου θα γίνει αποδεκτός ως ρίζα. Ο currentNode του TreeWalker αρχικοποιείται σε αυτόν τον κόμβο, ανεξάρτητα από το αν είναι ορατός. Η ρίζα λειτουργεί ως σημείο τερματισμού για τις μεθόδους διάσχισης που κοιτάζουν προς τα πάνω στη δομή του εγγράφου, όπως parentNode και nextNode. Η ρίζα δεν πρέπει να είναι null. |

### Τιμή επιστροφής

Ο νεοδημιουργημένος TreeWalker.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Εμφανίζεται εάν η καθορισμένη ρίζα είναι null. |

### Δείτε επίσης

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Δημιουργήστε έναν νέο TreeWalker πάνω στο υποδέντρο που έχει ρίζα τον καθορισμένο κόμβο.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| ρίζα | Node | Κόμβος που θα λειτουργήσει ως ρίζα για το TreeWalker. Οι σημαίες whatToShow και το NodeFilter δεν λαμβάνονται υπόψη κατά τον ορισμό αυτής της τιμής· οποιοσδήποτε τύπος κόμβου θα γίνει αποδεκτός ως ρίζα. Ο currentNode του TreeWalker αρχικοποιείται σε αυτόν τον κόμβο, ανεξάρτητα από το αν είναι ορατός. Η ρίζα λειτουργεί ως σημείο τερματισμού για τις μεθόδους διάσχισης που κοιτάζουν προς τα πάνω στη δομή του εγγράφου, όπως parentNode και nextNode. Η ρίζα δεν πρέπει να είναι null. |
| whatToShow | Int64 | Η σημαία καθορίζει ποιοι τύποι κόμβων μπορούν να εμφανιστούν στην λογική προβολή του δέντρου που παρουσιάζεται από τον περιηγητή δέντρου. Δείτε την περιγραφή του NodeFilter για το σύνολο των πιθανών τιμών SHOW_. Αυτές οι σημαίες μπορούν να συνδυαστούν χρησιμοποιώντας OR. |

### Τιμή επιστροφής

Ο νεοδημιουργημένος TreeWalker.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Εμφανίζεται εάν η καθορισμένη ρίζα είναι null. |

### Δείτε επίσης

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Δημιουργήστε έναν νέο TreeWalker πάνω στο υποδέντρο που έχει ρίζα τον καθορισμένο κόμβο.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| ρίζα | Node | Κόμβος που θα λειτουργήσει ως ρίζα για το TreeWalker. Οι σημαίες whatToShow και το NodeFilter δεν λαμβάνονται υπόψη κατά τον ορισμό αυτής της τιμής· οποιοσδήποτε τύπος κόμβου θα γίνει αποδεκτός ως ρίζα. Ο currentNode του TreeWalker αρχικοποιείται σε αυτόν τον κόμβο, ανεξάρτητα από το αν είναι ορατός. Η ρίζα λειτουργεί ως σημείο τερματισμού για τις μεθόδους διάσχισης που κοιτάζουν προς τα πάνω στη δομή του εγγράφου, όπως parentNode και nextNode. Η ρίζα δεν πρέπει να είναι null. |
| whatToShow | Int64 | Η σημαία καθορίζει ποιοι τύποι κόμβων μπορούν να εμφανιστούν στην λογική προβολή του δέντρου που παρουσιάζεται από τον περιηγητή δέντρου. Δείτε την περιγραφή του NodeFilter για το σύνολο των πιθανών τιμών SHOW_. Αυτές οι σημαίες μπορούν να συνδυαστούν χρησιμοποιώντας OR. |
| φίλτρο | INodeFilter | NodeFilter που θα χρησιμοποιηθεί με αυτό το TreeWalker, ή null για να υποδείξει ότι δεν υπάρχει φίλτρο. |

### Τιμή επιστροφής

Ο νεοδημιουργημένος TreeWalker.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Εμφανίζεται εάν η καθορισμένη ρίζα είναι null. |

### Δείτε επίσης

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../com.aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
