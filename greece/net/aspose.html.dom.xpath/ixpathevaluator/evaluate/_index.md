---
title: IXPathEvaluator.Evaluate
second_title: Aspose.HTML για Αναφορά API .NET
description: IXPathEvaluator μέθοδος. Αξιολογεί μια συμβολοσειρά έκφρασης XPath και επιστρέφει ένα αποτέλεσμα του καθορισμένου τύπου εάν είναι δυνατόν.
type: docs
weight: 30
url: /el/net/aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Αξιολογεί μια συμβολοσειρά έκφρασης XPath και επιστρέφει ένα αποτέλεσμα του καθορισμένου τύπου εάν είναι δυνατόν.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| expression | String | Η συμβολοσειρά έκφρασης XPath προς ανάλυση και αξιολόγηση. |
| contextNode | Node | ο`συμφραζόμενα` είναι ο κόμβος περιβάλλοντος για την αξιολόγηση αυτής της έκφρασης XPath. Αν το[`IXPathEvaluator`](../) λήφθηκε με χύτευση του [`Document`](../../../aspose.html.dom/document/) τότε αυτό πρέπει να ανήκει στο ίδιο έγγραφο και πρέπει να είναι [`Document`](../../../aspose.html.dom/document/) ,[`Element`](../../../aspose.html.dom/element/) ,[`Attr`](../../../aspose.html.dom/attr/) ,[`Text`](../../../aspose.html.dom/text/) , [`CDATASection`](../../../aspose.html.dom/cdatasection/) ,[`Comment`](../../../aspose.html.dom/comment/) ,[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) , ήXPathNamespace κόμβος. Εάν ο κόμβος περιβάλλοντος είναι α[`Text`](../../../aspose.html.dom/text/) ή ένα [`CDATASection`](../../../aspose.html.dom/cdatasection/)τότε το περιβάλλον ερμηνεύεται ως ολόκληρος ο κόμβος λογικού κειμένου όπως φαίνεται από το XPath, εκτός εάν ο κόμβος είναι κενός, οπότε μπορεί να μην χρησιμεύει ως περιβάλλον XPath. |
| resolver | IXPathNSResolver | ο`διαλύων` επιτρέπει τη μετάφραση όλων των προθεμάτων, συμπεριλαμβανομένου του the`xml` πρόθεμα namespace, εντός της έκφρασης XPath σε κατάλληλα URI χώρου ονομάτων. Εάν αυτό έχει καθοριστεί ως`μηδενικό` , οποιοδήποτε πρόθεμα χώρου ονομάτων εντός της έκφρασης θα έχει ως αποτέλεσμα [`DOMException`](../../../aspose.html.dom/domexception/) που ρίχνονται με τον κωδικό`NAMESPACE_ERR`. |
| type | XPathResultType | Εάν ένα συγκεκριμένο`τύπος` καθορίζεται, τότε το αποτέλεσμα θα επιστραφεί ως ο αντίστοιχος τύπος. Για αποτελέσματα XPath 1.0, αυτή πρέπει να είναι μία από τις τιμές του [`XPathResultType`](../../xpathresulttype/) αρίθμηση. |
| result | Object | ο`αποτέλεσμα` καθορίζει ένα συγκεκριμένο αντικείμενο αποτελέσματος το οποίο μπορεί να επαναχρησιμοποιηθεί και να επιστραφεί με αυτήν τη μέθοδο. Εάν αυτό προσδιορίζεται ως`μηδενικό`Εάν η υλοποίηση δεν επαναχρησιμοποιήσει το καθορισμένο αποτέλεσμα, ένα νέο αντικείμενο αποτελέσματος θα δημιουργηθεί και θα επιστραφεί. Για αποτελέσματα XPath 1.0 , αυτό το αντικείμενο θα είναι τύπου[`IXPathResult`](../../ixpathresult/). |

### Επιστρεφόμενη Αξία

Το αποτέλεσμα της αξιολόγησης της έκφρασης XPath. Για αποτελέσματα XPath 1.0, αυτό το αντικείμενο θα είναι τύπου[`IXPathResult`](../../ixpathresult/).

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Έγινε αν η έκφραση δεν είναι νόμιμη σύμφωνα με με τους κανόνες του[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: Αυξάνεται εάν το αποτέλεσμα δεν μπορεί να μετατραπεί για να επιστρέψει τον καθορισμένο τύπο . |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR: Αυξάνεται εάν η έκφραση περιέχει προθέματα χώρου ονομάτων τα οποία δεν μπορούν να επιλυθούν από το καθορισμένο[`IXPathNSResolver`](../../ixpathnsresolver/). |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: Ο κόμβος προέρχεται από ένα έγγραφο που δεν υποστηρίζεται από αυτό[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Ο κόμβος δεν είναι τύπος που επιτρέπεται ως κόμβος περιβάλλοντος XPath ή ο τύπος αιτήματος δεν επιτρέπεται από αυτό[`IXPathEvaluator`](../). |

### Δείτε επίσης

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* χώρος ονομάτων [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* συνέλευση [Aspose.HTML](../../../)


