---
title: "Document.CreateNodeIterator"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Document. Δημιουργεί έναν νέο NodeIterator πάνω από το υποδέντρο που ριζώνει στον καθορισμένο κόμβο"
type: docs

url: /el/java/com.aspose.html.dom/document/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

Δημιουργήστε έναν νέο NodeIterator πάνω στο υποδέντρο που έχει ρίζα τον καθορισμένο κόμβο.

```java
public INodeIterator CreateNodeIterator(Node root)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| ρίζα | Node | Κόμβος που θα επαναλαμβάνεται μαζί με τα παιδιά του. Ο iterator αρχικά τοποθετείται ακριβώς πριν από αυτόν τον κόμβο. Οι σημαίες whatToShow και το φίλτρο, εάν υπάρχει, δεν λαμβάνονται υπόψη κατά τον ορισμό αυτής της θέσης. Η ρίζα δεν πρέπει να είναι null. |

### Τιμή επιστροφής

Ο νεοδημιουργημένος NodeIterator.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Εμφανίζεται εάν η καθορισμένη ρίζα είναι null. |

### Δείτε επίσης

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

Δημιουργήστε έναν νέο NodeIterator πάνω στο υποδέντρο που έχει ρίζα τον καθορισμένο κόμβο.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| ρίζα | Node | Κόμβος που θα επαναλαμβάνεται μαζί με τα παιδιά του. Ο iterator αρχικά τοποθετείται ακριβώς πριν από αυτόν τον κόμβο. Οι σημαίες whatToShow και το φίλτρο, εάν υπάρχει, δεν λαμβάνονται υπόψη κατά τον ορισμό αυτής της θέσης. Η ρίζα δεν πρέπει να είναι null. |
| whatToShow | Int64 | Η σημαία καθορίζει ποιοι τύποι κόμβων μπορούν να εμφανιστούν στη λογική προβολή του δέντρου που παρουσιάζεται από τον iterator. Δείτε την περιγραφή του NodeFilter για το σύνολο των πιθανών τιμών SHOW_. Αυτές οι σημαίες μπορούν να συνδυαστούν χρησιμοποιώντας OR. |

### Τιμή επιστροφής

Ο νεοδημιουργημένος NodeIterator.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Εμφανίζεται εάν η καθορισμένη ρίζα είναι null. |

### Δείτε επίσης

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

Δημιουργήστε έναν νέο NodeIterator πάνω στο υποδέντρο που έχει ρίζα τον καθορισμένο κόμβο.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| ρίζα | Node | Κόμβος που θα επαναλαμβάνεται μαζί με τα παιδιά του. Ο iterator αρχικά τοποθετείται ακριβώς πριν από αυτόν τον κόμβο. Οι σημαίες whatToShow και το φίλτρο, εάν υπάρχει, δεν λαμβάνονται υπόψη κατά τον ορισμό αυτής της θέσης. Η ρίζα δεν πρέπει να είναι null. |
| whatToShow | Int64 | Η σημαία καθορίζει ποιοι τύποι κόμβων μπορούν να εμφανιστούν στη λογική προβολή του δέντρου που παρουσιάζεται από τον iterator. Δείτε την περιγραφή του NodeFilter για το σύνολο των πιθανών τιμών SHOW_. Αυτές οι σημαίες μπορούν να συνδυαστούν χρησιμοποιώντας OR. |
| φίλτρο | INodeFilter | NodeFilter που θα χρησιμοποιηθεί με αυτό το TreeWalker, ή null για να υποδείξει ότι δεν υπάρχει φίλτρο. |

### Τιμή επιστροφής

Ο νεοδημιουργημένος NodeIterator.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Εμφανίζεται εάν η καθορισμένη ρίζα είναι null. |

### Δείτε επίσης

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../com.aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
