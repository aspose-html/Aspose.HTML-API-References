---
title: "IXPathResult Διεπαφή"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.xpath.IXPathResult διεπαφή. Η διεπαφή XPathResult αντιπροσωπεύει το αποτέλεσμα της αξιολόγησης μιας έκφρασης XPath 1.0 στο πλαίσιο ενός συγκεκριμένου κόμβου. Δεδομένου ότι η αξιολόγηση μιας έκφρασης XPath μπορεί να οδηγήσει σε διάφορους τύπους αποτελεσμάτων, αυτό το αντικείμενο καθιστά δυνατό τον εντοπισμό και τη διαχείριση του τύπου και της τιμής του αποτελέσματος."
type: docs

url: /el/java/com.aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

Η διεπαφή `XPathResult` αντιπροσωπεύει το αποτέλεσμα της αξιολόγησης μιας έκφρασης XPath 1.0 στο πλαίσιο ενός συγκεκριμένου κόμβου. Δεδομένου ότι η αξιολόγηση μιας έκφρασης XPath μπορεί να έχει διάφορους τύπους αποτελεσμάτων, αυτό το αντικείμενο καθιστά δυνατό τον εντοπισμό και τη διαχείριση του τύπου και της τιμής του αποτελέσματος.

```java
public interface IXPathResult
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getBooleanValue](../../com.aspose.html.dom.xpath/ixpathresult/booleanvalue/) Η τιμή αυτού του boolean αποτελέσματος. |
| [getInvalidIteratorState](../../com.aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) Δηλώνει ότι ο iterator έχει γίνει άκυρος. Αληθές εάν ο τύπος `resultType`is `UnorderedNodeIterator` ή `OrderedNodeIterator` και το έγγραφο έχει τροποποιηθεί από τη στιγμή που αυτό το αποτέλεσμα επιστράφηκε. |
| [getNumberValue](../../com.aspose.html.dom.xpath/ixpathresult/numbervalue/) Η τιμή αυτού του αριθμητικού αποτελέσματος. |
| [getResultType](../../com.aspose.html.dom.xpath/ixpathresult/resulttype/) Ένας κώδικας που αντιπροσωπεύει τον τύπο αυτού του αποτελέσματος, όπως ορίζεται από το http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult[`XPathResultType`](../xpathresulttype/) enum. |
| [getSingleNodeValue](../../com.aspose.html.dom.xpath/ixpathresult/singlenodevalue/) Η τιμή αυτού του αποτελέσματος μοναδικού κόμβου, η οποία μπορεί να είναι `null`. |
| [getSnapshotLength](../../com.aspose.html.dom.xpath/ixpathresult/snapshotlength/) Ο αριθμός των κόμβων στο στιγμιότυπο αποτελέσματος. Οι έγκυρες τιμές για δείκτες snapshotItem είναι `0` έως `snapshotLength-1` συμπεριλαμβανομένα. |
| [getStringValue](../../com.aspose.html.dom.xpath/ixpathresult/Stringvalue/) Η τιμή αυτού του αποτελέσματος String. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [iterateNext](../../com.aspose.html.dom.xpath/ixpathresult/iteratenext/)() | Επαναλαμβάνει και επιστρέφει τον επόμενο κόμβο από το σύνολο κόμβων ή `null` εάν δεν υπάρχουν άλλοι κόμβοι. |
| [snapshotItem](../../com.aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | Επιστρέφει το στοιχείο με δείκτη `index` στη συλλογή στιγμιότυπου. Εάν το `index` είναι μεγαλύτερο ή ίσο με τον αριθμό των κόμβων στη λίστα, αυτή η μέθοδος επιστρέφει `null`. Σε αντίθεση με το αποτέλεσμα του επαναλήπτη, το στιγμιότυπο δεν γίνεται άκυρο, αλλά μπορεί να μην αντιστοιχεί στο τρέχον έγγραφο εάν αυτό μεταβληθεί. |

### Δείτε επίσης

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
