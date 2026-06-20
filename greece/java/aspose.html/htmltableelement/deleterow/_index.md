---
title: "HTMLTableElement.DeleteRow"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "HTMLTableElement method. Διαγράφει μια γραμμή πίνακα."
type: docs

url: /el/java/com.aspose.html/htmltableelement/deleterow/
---
## HTMLTableElement.DeleteRow method

Διαγράψτε μια γραμμή πίνακα.

```java
public void DeleteRow(int index)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | Int32 | Ο δείκτης της γραμμής που θα διαγραφεί. Αυτός ο δείκτης ξεκινά από το 0 και είναι σχετικός με τη λογική σειρά (όχι τη σειρά του εγγράφου) όλων των γραμμών που περιέχονται μέσα στον πίνακα. Εάν ο δείκτης είναι -1, η τελευταία γραμμή στον πίνακα διαγράφεται. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Εμφανίζεται εάν ο καθορισμένος δείκτης είναι μεγαλύτερος ή ίσος με τον αριθμό των γραμμών ή εάν ο δείκτης είναι ένας αρνητικός αριθμός διαφορετικός από -1. @version DOM Level 2 |

### Δείτε επίσης

* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
