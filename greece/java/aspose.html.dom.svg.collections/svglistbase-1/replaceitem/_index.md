---
title: "SVGListBase-1.ReplaceItem"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "SVGListBase μέθοδος. Αντικαθιστά ένα υπάρχον στοιχείο στη λίστα με ένα νέο στοιχείο."
type: docs

url: /el/java/com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

Αντικαθιστά ένα υπάρχον στοιχείο στη λίστα με ένα νέο στοιχείο.

```java
public T ReplaceItem(T newItem, ulong index)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newItem | T | Το στοιχείο που θα εισαχθεί στη λίστα. |
| index | UInt64 | Ο δείκτης του στοιχείου που πρέπει να αντικατασταθεί. Το πρώτο στοιχείο είναι ο αριθμός 0. |

### Τιμή Επιστροφής

Το εισαχθέν στοιχείο.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Κώδικας [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Εμφανίζεται όταν η λίστα δεν μπορεί να τροποποιηθεί. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Κώδικας [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Εμφανίζεται εάν ο αριθμός δείκτη είναι μεγαλύτερος ή ίσος με numberOfItems. |

### Δείτε επίσης

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
