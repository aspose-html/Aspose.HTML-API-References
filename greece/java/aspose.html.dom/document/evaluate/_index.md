---
title: "Document.Evaluate"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Document. Αξιολογεί μια συμβολοσειρά έκφρασης XPath και επιστρέφει ένα αποτέλεσμα του καθορισμένου τύπου εάν είναι δυνατόν."
type: docs

url: /el/java/com.aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

Αξιολογεί μια String έκφρασης XPath και επιστρέφει ένα αποτέλεσμα του καθορισμένου τύπου, εάν είναι δυνατόν.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| έκφραση | String | Η συμβολοσειρά έκφρασης XPath που θα αναλυθεί και αξιολογηθεί. |
| contextNode | Node | Το πλαίσιο είναι ο κόμβος πλαισίου για την αξιολόγηση αυτής της έκφρασης XPath. |
| resolver | IXPathNSResolver | Ο resolver επιτρέπει τη μετάφραση όλων των προθεμάτων, συμπεριλαμβανομένου του προθέματος του πακέτου xml, μέσα στην έκφραση XPath σε κατάλληλα URIs πακέτου. |
| τύπος | XPathResultType | Εάν καθοριστεί συγκεκριμένος τύπος, τότε το αποτέλεσμα θα επιστραφεί ως ο αντίστοιχος τύπος. |
| result | Αντικείμενο | Το αποτέλεσμα καθορίζει ένα συγκεκριμένο αντικείμενο αποτελέσματος που μπορεί να επαναχρησιμοποιηθεί και να επιστραφεί από αυτή τη μέθοδο. |

### Τιμή επιστροφής

Το αποτέλεσμα της αξιολόγησης της έκφρασης XPath.

### Δείτε επίσης

* interface [IXPathResult](../../../com.aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../com.aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
