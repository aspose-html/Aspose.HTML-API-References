---
title: "SVGListBase-1.ReplaceItem"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος SVGListBase. Αντικαθιστά ένα υπάρχον στοιχείο στη λίστα με ένα νέο στοιχείο"
type: docs

url: /el/java/com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

Αντικαθιστά ένα υπάρχον στοιχείο στη λίστα με ένα νέο στοιχείο.

```java
public T ReplaceItem(T newItem, ulong index)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| newItem | T | Το στοιχείο που πρέπει να εισαχθεί στη λίστα. |
| index | UInt64 | Ο δείκτης του στοιχείου που θα αντικατασταθεί. Το πρώτο στοιχείο είναι ο αριθμός 0. |

### Τιμή επιστροφής

Το εισαχθέν στοιχείο.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Κώδικας [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Εμφανίζεται όταν δεν είναι δυνατή η τροποποίηση της λίστας. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Κώδικας [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Εμφανίζεται εάν ο αριθμός δείκτη είναι μεγαλύτερος ή ίσος με το numberOfItems. |

### Δείτε επίσης

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
