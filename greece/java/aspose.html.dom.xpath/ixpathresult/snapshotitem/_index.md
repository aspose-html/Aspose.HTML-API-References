---
title: "IXPathResult.SnapshotItem"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "IXPathResult method. Επιστρέφει το στοιχείο στην θέση index στη συλλογή στιγμιοτύπων. Εάν το index είναι μεγαλύτερο ή ίσο με τον αριθμό των κόμβων στη λίστα, αυτή η μέθοδος επιστρέφει null. Σε αντίθεση με το αποτέλεσμα του επαναλήπτη, το στιγμιότυπο δεν γίνεται άκυρο, αλλά μπορεί να μην αντιστοιχεί στο τρέχον έγγραφο εάν έχει τροποποιηθεί."
type: docs

url: /el/java/com.aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Επιστρέφει το στοιχείο `index` στη συλλογή λήψης. Εάν το `index` είναι μεγαλύτερο ή ίσο με τον αριθμό των κόμβων στη λίστα, αυτή η μέθοδος επιστρέφει `null`. Σε αντίθεση με το αποτέλεσμα του επαναλήπτη, η λήψη δεν γίνεται άκυρη, αλλά μπορεί να μην αντιστοιχεί στο τρέχον έγγραφο εάν αυτό μεταβληθεί.

```java
public Node SnapshotItem(int index)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | Int32 | Δείκτης στη συλλογή στιγμιοτύπων. |

### Τιμή Επιστροφής

Ο κόμβος στη θέση `index` της `NodeList`, ή `null` εάν αυτό δεν είναι έγκυρος δείκτης.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: προκαλείται εάν `resultType` δεν είναι τύπου `UnorderedNodeSnapshot` ή `OrderedNodeSnapshot`. |

### Δείτε επίσης

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
