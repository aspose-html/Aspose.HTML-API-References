---
title: "SVGListBase-1.Item"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Ιδιότητα SVGListBase. Επιστρέφει το στοιχείο με δείκτη index στη λίστα"
type: docs

url: /el/java/com.aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

Επιστρέφει το στοιχείο με δείκτη index στη λίστα.

```java
public T this[ulong index] { get; set; }
```

| Parameter | Περιγραφή |
| --- | --- |
| index | Δείκτης στη λίστα. |

### Τιμή επιστροφής

Το αποθηκευμένο αντικείμενο στη θέση με δείκτη index στη λίστα.

### Property Value

Ο τύπος του στοιχείου που αποθηκεύεται στη λίστα.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Κώδικας [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Εμφανίζεται όταν δεν είναι δυνατή η τροποποίηση της λίστας. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Κώδικας [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Εμφανίζεται εάν ο αριθμός δείκτη είναι μεγαλύτερος ή ίσος με το numberOfItems. |

### Δείτε επίσης

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
