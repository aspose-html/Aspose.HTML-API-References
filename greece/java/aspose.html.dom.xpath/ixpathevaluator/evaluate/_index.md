---
title: "IXPathEvaluator.Evaluate"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος IXPathEvaluator. Αξιολογεί μια συμβολοσειρά έκφρασης XPath και επιστρέφει ένα αποτέλεσμα του καθορισμένου τύπου εάν είναι δυνατόν."
type: docs

url: /el/java/com.aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Αξιολογεί μια συμβολοσειρά έκφρασης XPath και επιστρέφει ένα αποτέλεσμα του καθορισμένου τύπου, εάν είναι δυνατόν.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έκφραση | String | Η συμβολοσειρά έκφρασης XPath που θα αναλυθεί και αξιολογηθεί. |
| contextNode | Node | Το `context` είναι ο κόμβος πλαισίου για την αξιολόγηση αυτής της έκφρασης XPath. Εάν το [`IXPathEvaluator`](../) αποκτήθηκε με μετατροπή του [`Document`](../../../com.aspose.html.dom/document/), τότε αυτό πρέπει να ανήκει στο ίδιο έγγραφο και πρέπει να είναι ένα [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/), ή κόμβος XPathNamespace. Εάν ο κόμβος πλαισίου είναι ένα [`Text`](../../../com.aspose.html.dom/text/) ή ένα [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), τότε το πλαίσιο ερμηνεύεται ως ολόκληρος λογικός κόμβος κειμένου όπως βλέπει το XPath, εκτός εάν ο κόμβος είναι κενός, οπότε δεν μπορεί να λειτουργήσει ως πλαίσιο XPath. |
| resolver | IXPathNSResolver | Ο `resolver` επιτρέπει τη μετάφραση όλων των προθεμάτων, συμπεριλαμβανομένου του προθέματος πακέτου `xml`, μέσα στην έκφραση XPath σε κατάλληλα URI πακέτων. Εάν αυτό οριστεί ως `null`, οποιοδήποτε πρόθεμα πακέτου μέσα στην έκφραση θα προκαλέσει την εμφάνιση του [`DOMException`](../../../com.aspose.html.dom/domexception/) με τον κωδικό `NAMESPACE_ERR`. |
| type | XPathResultType | Εάν καθοριστεί ένας συγκεκριμένος `type`, τότε το αποτέλεσμα θα επιστραφεί ως ο αντίστοιχος τύπος. Για αποτελέσματα XPath 1.0, αυτό πρέπει να είναι μία από τις τιμές της απαριθμήσεως [`XPathResultType`](../../xpathresulttype/). |
| result | Object | Το `result` καθορίζει ένα συγκεκριμένο αντικείμενο αποτελέσματος που μπορεί να επαναχρησιμοποιηθεί και να επιστραφεί από αυτή τη μέθοδο. Εάν αυτό οριστεί ως `null` ή η υλοποίηση δεν επαναχρησιμοποιήσει το καθορισμένο αποτέλεσμα, θα δημιουργηθεί και θα επιστραφεί ένα νέο αντικείμενο αποτελέσματος. Για αποτελέσματα XPath 1.0, αυτό το αντικείμενο θα είναι τύπου [`IXPathResult`](../../ixpathresult/). |

### Τιμή Επιστροφής

Το αποτέλεσμα της αξιολόγησης της έκφρασης XPath. Για αποτελέσματα XPath 1.0, αυτό το αντικείμενο θα είναι τύπου [`IXPathResult`](../../ixpathresult/).

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Εμφανίζεται εάν η έκφραση δεν είναι νόμιμη σύμφωνα με τους κανόνες του [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: Εμφανίζεται εάν το αποτέλεσμα δεν μπορεί να μετατραπεί ώστε να επιστρέψει τον καθορισμένο τύπο. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: Εμφανίζεται εάν η έκφραση περιέχει προθέματα πακέτων που δεν μπορούν να επιλυθούν από το καθορισμένο [`IXPathNSResolver`](../../ixpathnsresolver/). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: Ο κόμβος προέρχεται από ένα έγγραφο που δεν υποστηρίζεται από αυτό το [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Ο κόμβος δεν είναι τύπος που επιτρέπεται ως κόμβος πλαισίου XPath ή ο τύπος αιτήματος δεν επιτρέπεται από αυτό το [`IXPathEvaluator`](../). |

### Δείτε επίσης

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
