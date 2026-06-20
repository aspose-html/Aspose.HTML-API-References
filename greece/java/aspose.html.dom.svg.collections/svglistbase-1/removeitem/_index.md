---
title: "SVGListBase-1.RemoveItem"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος SVGListBase. Αφαιρεί ένα υπάρχον στοιχείο από τη λίστα"
type: docs

url: /el/java/com.aspose.html.dom.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase&lt;T&gt;.RemoveItem method

Αφαιρεί ένα υπάρχον στοιχείο από τη λίστα.

```java
public T RemoveItem(ulong index)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | UInt64 | Ο δείκτης του στοιχείου που πρέπει να αφαιρεθεί. Το πρώτο στοιχείο είναι ο αριθμός 0. |

### Τιμή Επιστροφής

Το αφαιρεθέν στοιχείο.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Κώδικας [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Εμφανίζεται όταν η λίστα δεν μπορεί να τροποποιηθεί. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Κώδικας [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Εμφανίζεται εάν ο αριθμός δείκτη είναι μεγαλύτερος ή ίσος με numberOfItems. |

### Δείτε επίσης

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
