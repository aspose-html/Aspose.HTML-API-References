---
title: "IXPathExpression.Evaluate"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος IXPathExpression. Αξιολογεί αυτήν την έκφραση XPath και επιστρέφει ένα αποτέλεσμα."
type: docs

url: /el/java/com.aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Αξιολογεί αυτήν την έκφραση XPath και επιστρέφει ένα αποτέλεσμα.

```java
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| contextNode | Node | Το `context` είναι ο κόμβος περιβάλλοντος για την αξιολόγηση αυτής της έκφρασης XPath. Εάν το [`IXPathEvaluator`](../../ixpathevaluator/) αποκτήθηκε με μετατροπή του [`Document`](../../../com.aspose.html.dom/document/), τότε αυτό πρέπει να ανήκει στο ίδιο έγγραφο και πρέπει να είναι ένα [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/), ή κόμβος XPathNamespace. Εάν ο κόμβος περιβάλλοντος είναι ένα [`Text`](../../../com.aspose.html.dom/text/) ή ένα [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), τότε το περιβάλλον ερμηνεύεται ως ολόκληρος ο λογικός κόμβος κειμένου όπως βλέπεται από το XPath, εκτός εάν ο κόμβος είναι κενός, οπότε μπορεί να μην λειτουργεί ως περιβάλλον XPath. |
| type | XPathResultType | Εάν καθοριστεί ένα συγκεκριμένο `type`, τότε το αποτέλεσμα θα μετατραπεί ώστε να επιστρέψει τον καθορισμένο τύπο, βασιζόμενο στις μετατροπές XPath, και θα αποτύχει εάν η επιθυμητή μετατροπή δεν είναι δυνατή. Αυτό πρέπει να είναι μία από τις τιμές του [`XPathResultType`](../../xpathresulttype/). |
| result | Object | Το `result` καθορίζει ένα συγκεκριμένο αντικείμενο αποτελέσματος που μπορεί να επαναχρησιμοποιηθεί και να επιστραφεί από αυτή τη μέθοδο. Εάν αυτό οριστεί ως `null` ή η υλοποίηση δεν επαναχρησιμοποιήσει το καθορισμένο αποτέλεσμα, θα δημιουργηθεί και θα επιστραφεί ένα νέο αντικείμενο αποτελέσματος. Για αποτελέσματα XPath 1.0, αυτό το αντικείμενο θα είναι τύπου [`IXPathResult`](../../ixpathresult/). |

### Τιμή Επιστροφής

Το αποτέλεσμα της αξιολόγησης της έκφρασης XPath. Για αποτελέσματα XPath 1.0, αυτό το αντικείμενο θα είναι τύπου [`IXPathResult`](../../ixpathresult/).

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: Εμφανίζεται εάν το αποτέλεσμα δεν μπορεί να μετατραπεί ώστε να επιστρέψει τον καθορισμένο τύπο. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: Ο Node προέρχεται από ένα έγγραφο που δεν υποστηρίζεται από το [`IXPathEvaluator`](../../ixpathevaluator/) που δημιούργησε αυτή τη [`IXPathExpression`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Ο Node δεν είναι τύπος που επιτρέπεται ως κόμβος περιβάλλοντος XPath ή ο τύπος αίτησης δεν επιτρέπεται από αυτή τη [`IXPathExpression`](../). |

### Δείτε επίσης

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
