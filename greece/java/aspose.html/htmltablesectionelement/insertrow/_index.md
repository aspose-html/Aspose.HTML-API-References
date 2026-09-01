---
title: "HTMLTableSectionElement.InsertRow"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος HTMLTableSectionElement. Εισάγει μια γραμμή σε αυτήν την ενότητα. Η νέα γραμμή εισάγεται αμέσως πριν από τη τρέχουσα γραμμή με δείκτη index σε αυτήν την ενότητα. Εάν το index είναι -1 ή ίσο με τον αριθμό των γραμμών σε αυτήν την ενότητα, η νέα γραμμή προσαρτάται στο τέλος."
type: docs

url: /el/java/com.aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

Εισάγετε μια γραμμή σε αυτήν την ενότητα. Η νέα γραμμή εισάγεται αμέσως πριν από την τρέχουσα γραμμή `index` σε αυτήν την ενότητα. Εάν το `index` είναι -1 ή ίσο με τον αριθμό των γραμμών σε αυτήν την ενότητα, η νέα γραμμή προσαρτάται στο τέλος.

```java
public HTMLElement InsertRow(int index)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | Int32 | Ο αριθμός της γραμμής όπου θα εισαχθεί μια νέα γραμμή. Αυτό το δείκτη ξεκινά από 0 και είναι σχετικό μόνο με τις γραμμές που περιέχονται σε αυτήν την ενότητα, όχι με όλες τις γραμμές του πίνακα. |

### Τιμή Επιστροφής

Η νεοδημιουργημένη γραμμή.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Εμφανίζεται εάν ο καθορισμένος δείκτης είναι μεγαλύτερος από τον αριθμό των γραμμών ή εάν ο δείκτης είναι αρνητικός αριθμός διαφορετικός από -1. @version DOM Level 2 |

### Δείτε επίσης

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
