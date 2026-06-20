---
title: "SVGListBase-1.InsertItemBefore"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος SVGListBase. Εισάγει ένα νέο στοιχείο στη λίστα στη συγκεκριμένη θέση. Το πρώτο στοιχείο είναι ο αριθμός 0"
type: docs

url: /el/java/com.aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

Εισάγει ένα νέο στοιχείο στη λίστα στη καθορισμένη θέση. Το πρώτο στοιχείο είναι ο αριθμός 0.

```java
public T InsertItemBefore(T newItem, ulong index)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newItem | T | Το στοιχείο που θα εισαχθεί στη λίστα. |
| index | UInt64 | Ο δείκτης του στοιχείου πριν από το οποίο θα εισαχθεί το νέο στοιχείο. Το πρώτο στοιχείο είναι ο αριθμός 0. Εάν ο δείκτης είναι ίσος με 0, τότε το νέο στοιχείο εισάγεται στην αρχή της λίστας. Εάν ο δείκτης είναι μεγαλύτερος ή ίσος με numberOfItems, τότε το νέο στοιχείο προσαρμόζεται στο τέλος της λίστας. |

### Τιμή Επιστροφής

Το εισαχθέν στοιχείο.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Κώδικας [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Εμφανίζεται όταν η λίστα δεν μπορεί να τροποποιηθεί. |

### Δείτε επίσης

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
