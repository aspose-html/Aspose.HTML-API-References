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

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| index | UInt64 | Ο δείκτης του στοιχείου που πρέπει να αφαιρεθεί. Το πρώτο στοιχείο είναι ο αριθμός 0. |

### Τιμή επιστροφής

Το αφαιρεμένο στοιχείο.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Κώδικας [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Εμφανίζεται όταν δεν είναι δυνατή η τροποποίηση της λίστας. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Κώδικας [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Εμφανίζεται εάν ο αριθμός δείκτη είναι μεγαλύτερος ή ίσος με το numberOfItems. |

### Δείτε επίσης

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
