---
title: "IXPathResult.SnapshotItem"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος IXPathResult. Επιστρέφει το στοιχείο με δείκτη index στη συλλογή στιγμιοτύπων. Εάν το index είναι μεγαλύτερο ή ίσο με τον αριθμό των κόμβων στη λίστα, αυτή η μέθοδος επιστρέφει null. Σε αντίθεση με το αποτέλεσμα του επαναλήπτη, το στιγμιότυπο δεν γίνεται άκυρο, αλλά μπορεί να μην αντιστοιχεί στο τρέχον έγγραφο εάν αυτό τροποποιηθεί."
type: docs

url: /el/java/com.aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Επιστρέφει το στοιχείο με δείκτη `index` στη συλλογή στιγμιότυπου. Εάν το `index` είναι μεγαλύτερο ή ίσο με τον αριθμό των κόμβων στη λίστα, αυτή η μέθοδος επιστρέφει `null`. Σε αντίθεση με το αποτέλεσμα του επαναλήπτη, το στιγμιότυπο δεν γίνεται άκυρο, αλλά μπορεί να μην αντιστοιχεί στο τρέχον έγγραφο εάν αυτό μεταβληθεί.

```java
public Node SnapshotItem(int index)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| index | Int32 | Δείκτης στη συλλογή στιγμιοτύπων. |

### Τιμή επιστροφής

Ο κόμβος στη θέση `index` της `NodeList`, ή `null` εάν αυτό δεν είναι έγκυρος δείκτης.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: προκαλείται εάν `resultType` δεν είναι τύπου `UnorderedNodeSnapshot` ή `OrderedNodeSnapshot`. |

### Δείτε επίσης

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
