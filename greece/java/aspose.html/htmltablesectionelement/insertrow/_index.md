---
title: "HTMLTableSectionElement.InsertRow"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος HTMLTableSectionElement. Εισάγει μια σειρά σε αυτήν την ενότητα. Η νέα σειρά εισάγεται αμέσως πριν από τη τρέχουσα σειρά με δείκτη index σε αυτήν την ενότητα. Εάν το index είναι -1 ή ίσο με τον αριθμό των σειρών σε αυτήν την ενότητα, η νέα σειρά προσαρτάται στο τέλος."
type: docs

url: /el/java/com.aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

Εισάγετε μια γραμμή σε αυτήν την ενότητα. Η νέα γραμμή εισάγεται αμέσως πριν από τη τρέχουσα γραμμή `index` στην ενότητα. Εάν το `index` είναι -1 ή ίσο με τον αριθμό των γραμμών σε αυτήν την ενότητα, η νέα γραμμή προσαρτάται στο τέλος.

```java
public HTMLElement InsertRow(int index)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| index | Int32 | Ο αριθμός σειράς όπου θα εισαχθεί μια νέα σειρά. Αυτό το δείκτη ξεκινά από 0 και είναι σχετικό μόνο με τις σειρές που περιέχονται σε αυτήν την ενότητα, όχι με όλες τις σειρές του πίνακα. |

### Τιμή επιστροφής

Η νεοδημιουργημένη γραμμή.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Εμφανίζεται εάν ο καθορισμένος δείκτης είναι μεγαλύτερος από τον αριθμό των σειρών ή εάν ο δείκτης είναι αρνητικός αριθμός διαφορετικός από -1. @version DOM Level 2 |

### Δείτε επίσης

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
