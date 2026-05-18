---
title: "HTMLTableRowElement.InsertCell"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος HTMLTableRowElement. Εισάγει ένα κενό κελί TD σε αυτή τη σειρά. Αν το index είναι -1 ή ίσο με τον αριθμό των κελιών, το νέο κελί προσαρτάται."
type: docs

url: /el/java/com.aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

Εισάγετε ένα κενό κελί `TD` σε αυτή τη γραμμή. Εάν το `index` είναι -1 ή ίσο με τον αριθμό των κελιών, το νέο κελί προσαρτάται.

```java
public HTMLElement InsertCell(int index)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| index | Int32 | Η θέση για την εισαγωγή του κελιού, ξεκινώντας από 0. |

### Τιμή επιστροφής

Το νεοδημιουργημένο κελί.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Εμφανίζεται εάν το καθορισμένο `index` είναι μεγαλύτερο από τον αριθμό των κελιών ή εάν το index είναι αρνητικός αριθμός διαφορετικός από -1. @version DOM Level 2 |

### Δείτε επίσης

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableRowElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
